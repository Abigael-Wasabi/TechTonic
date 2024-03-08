<script setup>
import WelcomeItem from '../components/WelcomeItem.vue'
import ToolingIcon from '../components/icons/IconTooling.vue'
</script>

<template>
  <main>
  
  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>About TechTonic</template>

    Dynamic Software Solutions is a forward-thinking software development 
    and cybersecurity agency committed to pioneering innovative solutions. 
    Our focus lies in engineering resilient, scalable software applications, 
    with a steadfast dedication to security throughout the development 
    process.Collaborating closely with our clients, our team of adept developers 
    and cybersecurity professionals crafts customized, leading-edge solutions 
    that surpass expectations.
  </WelcomeItem>
  
  </main>
</template>
