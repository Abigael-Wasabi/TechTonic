<script setup>
import WelcomeItem from '../components/WelcomeItem.vue'
import SupportIcon from '../components/icons/IconSupport.vue'

</script>

<template>
  <main>
    
  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Support Vue</template>

    As an independent project, Vue relies on community backing for its sustainability. You can help
    us by
    <a href="https://vuejs.org/sponsor/" target="_blank" rel="noopener">becoming a sponsor</a>.
  </WelcomeItem>

  </main>
</template>
