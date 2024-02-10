<template>
  <div class="contact">
    <h1>Contact Us</h1>
    
    <div class="row">
      <!-- Contact Form -->
      <div class="col-md-6">
        <h2>Get in Touch</h2>
        <p>Have a question or want to learn more about our services? Fill out the form below and we'll get back to you as soon as possible.</p>
        <form>
          <div class="form-group">
            <label for="name">Your Name:</label>
            <input type="text" class="form-control" id="name" placeholder="Enter your name" required>
          </div>
          <div class="form-group">
            <label for="email">Your Email:</label>
            <input type="email" class="form-control" id="email" placeholder="Enter your email" required>
          </div>
          <div class="form-group">
            <label for="message">Your Message:</label>
            <textarea class="form-control" id="message" rows="5" placeholder="Enter your message" required></textarea>
          </div>
          <button type="submit">SUBMIT</button>
        </form>
      </div>
      
      <!-- Contact Info -->
      <div class="col-md-6">
        <h2>Contact Information</h2>
        <ul>
          <strong>Email:</strong> info@techtonic.com<br>
          <strong>Phone:</strong> +254 7 123 456 07<br>
          <strong>Address:</strong> Moi Avenue, P.O BOX 00100, Nairobi
        </ul>
        
        <!-- Social Media Icons -->
        <div class="social-media">
          <a href="#" target="_blank"><i class="fab fa-linkedin"></i></a>
          <a href="#" target="_blank"><i class="fab fa-x"></i></a>
        </div>
      </div>
    </div>
    
    <FooterView/>
  </div>
</template>

<script>
import FooterView from './FooterView.vue';

export default {
  name: 'ContactView',
  components: {
    FooterView
  },
}
</script>

<style scoped>
.contact {
  text-align: center;
  font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}

.contact h1 {
  margin-bottom: 20px;
}

.contact h2 {
  margin-top: 40px;
}

.contact form {
  margin-bottom: 40px;
}

.contact .form-group {
  margin-bottom: 20px;
}

.contact .social-media {
  margin-top: 20px;
}

.contact .social-media a {
  display: inline-block;
  margin-right: 10px;
}

.contact .social-media a i {
  font-size: 24px;
}

button{
    border-radius: 35px;
    border:transparent;
    height: 40px;
    background-color:rgb(37,102,106);
  }
</style>
