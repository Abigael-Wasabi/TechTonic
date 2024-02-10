<template>
  <div class="about">
    <h1>Services we offer</h1>
    <div class="row">
      <div class="col-md-4">
        <div class="about-content">
          <h4>Software Development</h4>
          <p>Unlock the power of custom software solutions tailored to your business needs. Our experienced team of developers will work closely with you to understand your requirements and deliver high-quality, scalable software applications.</p>
          <ul>
            <li>Web Application Development</li>
            <li>Mobile Application Development</li>
            <li>Enterprise Software Solutions</li>
            <li>UI/UX Design</li>
            <li>Quality Assurance and Testing</li>
          </ul>
        </div>
      </div>
      <div class="col-md-4">
        <div class="about-content">
          <h4>Cyber Security</h4>
          <p>Safeguard your digital assets with cutting-edge cyber security measures and expert consultation. Our dedicated team of security professionals will assess your organization's vulnerabilities, implement robust security protocols, and provide ongoing monitoring and support.</p>
          <ul>
            <li>Penetration Testing</li>
            <li>Network Security</li>
            <li>Endpoint Security</li>
            <li>Security Awareness Training</li>
            <li>Incident Response</li>
          </ul>
        </div>
      </div>
      <div class="col-md-4">
        <div class="about-content">
          <h4>Android App Development</h4>
          <p>Bring your ideas to life with innovative Android applications designed for optimal user experience. Our team of Android developers specializes in creating feature-rich, user-friendly apps that meet your business objectives and resonate with your target audience.</p>
          <ul>
            <li>Native Android App Development</li>
            <li>Cross-Platform App Development</li>
            <li>UI/UX Design</li>
            <li>App Maintenance and Support</li>
            <li>App Store Optimization</li>
          </ul>
        </div>
      </div>
    </div>
    <FooterView/>
  </div>
</template>

<script>
import FooterView from './FooterView.vue';

export default {
  name: 'ServView',
  components: {
    FooterView
  },
}
</script>

<style scoped>
.about {
  text-align: center;
  font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}

.about-content {
  padding: 20px;
}

.about-content ul {
  list-style-type: none;
  padding: 0;
}

.about-content ul li {
  margin-bottom: 10px;
}

@media (max-width: 767px) {
  .about-content {
    margin-bottom: 20px;
  }
}
</style>
