<script setup>
import WelcomeItem from '../components/WelcomeItem.vue'
import CommunityIcon from '../components/icons/IconCommunity.vue'
import { faEnvelope, faPhone, faMapMarkerAlt } from '@fortawesome/free-solid-svg-icons'
import { faLinkedin } from '@fortawesome/free-brands-svg-icons'
import { FontAwesomeIcon } from '@fortawesome/vue-fontawesome'
</script>

<template>
  <main>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Drop us a line</template>
        <a target='_blank' href="mailto:techtonic@gmail.com" rel="noreferrer" style="display: flex; align-items: center;">
          <span style="margin-left: 200px;"><FontAwesomeIcon :icon="faEnvelope" size="3x" /></span>
                    <span style="margin-left: 30px;">techtonic@gmail.com</span>
        </a><br>
        <hr>

        <a target='_blank' href="+254 7 123 456 07" rel="noreferrer" style="display: flex; align-items: center;">
          <span style="margin-left: 200px;"><FontAwesomeIcon :icon="faPhone" size="3x" /></span>
                   <span style="margin-left: 30px;">+254 7 123 456 07</span>
        </a><br>
        <hr>

        <a target='_blank' href="+254 7 123 456 07" rel="noreferrer" style="display: flex; align-items: center;">
          <span style="margin-left: 200px;"><FontAwesomeIcon :icon="faMapMarkerAlt" size="3x" /></span>
          <span style="margin-left: 30px;">Moi Avenue, Twins Tower</span>
        </a>
        <hr>

        <a></a><br>
        <a target='_blank' href="https://www.linkedin.com/in/abigael-wanjala-96a7b5265/" rel="noreferrer" style="display: flex; align-items: center;">
          <span style="margin-left: 200px;"><FontAwesomeIcon :icon="faLinkedin" size="3x" /></span>
                    <span style="margin-left: 30px;">Let's Connect</span>
        </a>
        <hr>
  </WelcomeItem>
  
  </main>
</template>


