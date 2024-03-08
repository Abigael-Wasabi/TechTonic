<script setup>
import WelcomeItem from '../components/WelcomeItem.vue'
import DocumentationIcon from '../components/icons/IconDocumentation.vue'
</script>

<template>
  <main>
    <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Documentation</template>

    We exist to unlock human potential at scale. We envision a world where the most 
    talented people can build a career commensurate with their ability – not their 
    race, gender, or geography.
  </WelcomeItem>
  </main>
</template>
