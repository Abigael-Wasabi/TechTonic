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
    <template #heading>Next-gen Tech Innovations</template>
    We're prepared to transform your concepts into state-of-the-art solutions leveraging our extensive IT knowledge.
  </WelcomeItem>
  </main>
</template>