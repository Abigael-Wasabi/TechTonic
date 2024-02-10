 <template>
  <div class="home">
    <section class="hero">
      <div class="container">
        <h1>Welcome to TechTonic</h1>
        <p>Your trusted partner in technology solutions</p>
        <button><router-link to="/services">Explore Our Services</router-link></button>
      </div>
    </section>
    
    <section class="about">
      <div class="container">
        <h2>About Us</h2>
        <p>TechTonic is a leading provider of innovative technology solutions, specializing in software development, cybersecurity, and digital transformation. With a team of skilled professionals and a customer-centric approach, we help businesses and individuals harness the power of technology to achieve their goals and drive success.</p>
        <button><router-link to="/about">Learn More</router-link></button>
      </div>
    </section>
    
    
    <section class="contact">
      <div class="container">
        <h2>Contact Us</h2>
        <p>Have a question or want to discuss your project? Get in touch with us today.</p>
        <button><router-link to="/contact">Contact Now</router-link></button>
      </div>
    </section>
    
    <vue-particles class="particles"></vue-particles>

    <FooterView/>
  </div>
</template>

<script>
import VueParticles from 'vue-particles';
import FooterView from './FooterView.vue';

export default {
  name: 'HomeView',
  components: {
    FooterView,
    VueParticles
  },
}
</script>

<style scoped>
.home {
  text-align: center;
  font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}

.home .hero {
  background-image: url('/assets/hero-background.jpg');
  background-size: cover;
  color: #000;
  padding: 100px 0;
}

.home .hero h1 {
  font-size: 3rem;
  margin-bottom: 20px;
}

.home .hero p {
  font-size: 1.25rem;
  margin-bottom: 40px;
}

.home .about,
.home .contact {
  padding: 80px 0;
}

.home .about h2,
.home .contact h2 {
  margin-bottom: 40px;
}

@media (max-width: 767px) {
  .home .hero h1 {
    font-size: 2.5rem;
  }

  .home .hero p {
    font-size: 1rem;
  }
}
button{
    border-radius: 35px;
    border:transparent;
    height: 40px;
    background-color:rgb(37,102,106);
  }
.particles {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}
</style>
