<template>
  <div class="flex h-screen overflow-hidden">
    <Sidebar />
    <div class="flex flex-col w-full overflow-y-scroll">
      <slot />
      <WebsiteFooter
        :class="{
          'pl-56':
            sidebar.collapsed == false || sidebar.collapsedSwitch == false,
          'pl-24': sidebar.collapsed == true && sidebar.collapsedSwitch == true,
        }"
      />
    </div>
  </div>
</template>

<script setup lang="ts">
const sidebar = useSidebar();
</script>
