<template>
  <div
    class="grid grid-cols-1 gap-6 sm:grid-cols-4 md:grid-cols-4 lg:grid-cols-4"
  >
    <CardMetric
      text="New Organizations"
      number="10"
      textColor="text-light-header dark:text-dark-header"
      borderColor="border-light-header dark:border-dark-header"
      backgroundColor="bg-light-menu-selection dark:bg-dark-menu-selection"
    />

    <CardMetric
      text="Events"
      number="123"
      textColor="text-light-text dark:text-dark-text"
      borderColor="border-light-text dark:border-dark-text"
      backgroundColor="bg-light-distinct dark:bg-dark-distinct"
    />

    <CardMetric
      text="Act events"
      number="100"
      textColor="text-light-act-red dark:text-dark-act-red"
      borderColor="border-light-act-red dark:border-dark-act-red"
      backgroundColor="bg-light-act-red/20 dark:bg-dark-act-red/40"
    />

    <CardMetric
      text="Learn events"
      number="23"
      textColor="text-light-learn-blue dark:text-dark-learn-blue"
      borderColor="border-light-learn-blue dark:border-dark-learn-blue"
      backgroundColor="bg-light-learn-blue/20 dark:bg-dark-learn-blue/40"
    />
  </div>
</template>

<script setup lang="ts"></script>
