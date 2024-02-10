<template>
    <div class="careers">
      <h1>Join Our Team</h1>
      
      <div class="row">
        <div class="col-md-6">
          <h2>Current Job Openings</h2>
          <ul>
            <li><strong>Software Developer:</strong> We're seeking experienced software developers to join our innovative team.</li>
            <li><strong>Cybersecurity Analyst:</strong> Join us in protecting our digital assets and ensuring a secure environment.</li>
            <li><strong>Android App Developer:</strong> Help us create cutting-edge mobile applications for Android platforms.</li>
          </ul>
          <p>View all our open positions <router-link to="/careers/open-positions">here</router-link>.</p>
        </div>
        
        <div class="col-md-6">
          <h2>Benefits and Perks</h2>
          <ul>
            <li>Competitive salaries and performance bonuses</li>
            <li>Comprehensive health and wellness benefits</li>
            <li>Flexible work hours and remote work options</li>
            <li>Ongoing professional development and training opportunities</li>
            <li>Company-sponsored social events and team-building activities</li>
            <li>Generous vacation and paid time off</li>
          </ul>
        </div>
      </div>
      
      <div class="culture">
        <h2>Our Company Culture</h2>
        <p>At TechTonic, we foster a culture of innovation, collaboration, and continuous learning. We believe in empowering our employees to reach their full potential and create a positive impact on the world. Our inclusive and diverse workplace encourages creativity, transparency, and mutual respect among team members.</p>
      </div>
      
      
      <div class="apply">
        <h2>How to Apply</h2>
        <p>If you're interested in joining our team, please submit your resume and cover letter to careers@techtonic.com. Be sure to specify the position you're applying for in the subject line. Our hiring team will review your application and reach out if your qualifications match our current needs.</p>
      </div>
      
      <FooterView/>
    </div>
  </template>
  
  <script>
  import FooterView from './FooterView.vue';
  
  export default {
    name: 'CareersView',
    components: {
      FooterView
    },
  }
  </script>
  
  <style scoped>
  .careers {
    text-align: center;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
  }
  
  .careers h1 {
    margin-bottom: 20px;
  }
  
  .careers h2 {
    margin-top: 40px;
  }
  
  @media (max-width: 767px) {
    .careers {
      padding: 0 20px;
    }
  }
  </style>
  