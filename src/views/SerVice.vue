<script setup>
import WelcomeItem from '../components/WelcomeItem.vue'
import EcosystemIcon from '../components/icons/IconEcosystem.vue'

</script>

<template>
  <main>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>SERVICE REPERTOIRE</template>

    <div class="footer-column">
        <h2>SOFTWARE DEVELOPMENT</h2>
        <a>Backend Development</a><br>
        <a>Frontend Development</a><br>
        <a>DevOps</a><br>
        <a>Data Science</a><br>
      </div>
      
      <div class="footer-column">
        <h2>CYBER SECURITY</h2>
        <a>Penetration testing</a><br>
        <a>Forensics</a><br>
        <a>Security architecture.</a><br>
        <a>Threat intelligence.</a><br>
      </div>
      
      <div class="footer-column">
        <h2>ANDROID APP DEVELOPMENT</h2>
        <a>Kotlin</a><br>
        <a>Android architecture</a><br>
        <a>Android testing</a><br>
        <a>Database technologies</a><br>
        <a>Android ui state holders</a><br>
      </div>

    
  </WelcomeItem>

  
  </main>
</template>
