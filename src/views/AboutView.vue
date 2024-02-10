<template>
  <div class="about">
    <h1>About TechTonic</h1>
    
    <div class="row">
      <div class="col-md-6">
        <h2>Our Mission</h2>
        <p>At TechTonic, our mission is to empower businesses and individuals with innovative technology solutions that drive growth, efficiency, and success. We are committed to delivering cutting-edge software development, cybersecurity, and digital transformation services tailored to meet the unique needs of our clients.</p>
      </div>
      <div class="col-md-6">
        <h2>Our Vision</h2>
        <p>Our vision is to be a global leader in technology innovation, known for our exceptional quality, reliability, and customer satisfaction. We aspire to create a positive impact on the world by harnessing the power of technology to solve complex challenges and drive positive change.</p>
      </div>
    </div>
    
    <h2>Why Choose TechTonic?</h2>
    <ul>
      <li>Expertise: Our team of skilled professionals brings years of experience and expertise in their respective fields, ensuring top-notch quality and reliability in every project we undertake.</li>
      <li>Innovation: We embrace innovation and creativity in everything we do, constantly pushing the boundaries of what's possible to deliver innovative solutions that exceed our clients' expectations.</li>
      <li>Customer-Centric Approach: We prioritize customer satisfaction above all else, striving to understand our clients' needs and objectives to deliver personalized solutions that drive tangible results.</li>
      <li>Commitment to Excellence: We are dedicated to excellence in everything we do, from the quality of our work to the level of service we provide. We hold ourselves to the highest standards to ensure our clients' success.</li>
    </ul>
    
    <FooterView/>
  </div>
</template>

<script>
import FooterView from './FooterView.vue';

export default {
  name: 'AboutView',
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

.about h1 {
  margin-bottom: 20px;
}

.about h2 {
  margin-top: 40px;
}

.about ul {
  text-align: left;
  padding-left: 0;
}

.about ul li {
  margin-bottom: 10px;
}

@media (max-width: 767px) {
  .about {
    padding: 0 20px;
  }
}
</style>
