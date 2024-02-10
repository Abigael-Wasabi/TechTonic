  <template>
    <footer class="footer">
    <div class="container">
        <p>Sign up for our newsletter to receive the latest updates on features and releases</p>
        <div><input
            placeholder="Enter your email address"
            /><button>SUBSCRIBE</button></div>
      <div class="footer-columns">
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
        
        <div class="footer-column">
          <h2>CONTACT US</h2>
          <a href="mailto:techtonic@gmail.com">techtonic@gmail.com</a><br>
          <a>+254 7 123 456 07</a><br>
          <a>Moi Avenue, Twins Tower</a><br>
          <a>P.O BOX 00100, Nairobi</a><br>
        </div>
      </div>
    </div>
    </footer>
  </template>
  
  <script>
  export default {
    name: 'FooterView',
  }
  </script>
  
  <style scoped>
  .footer {
  position: fixed;
  bottom: 0;
  left: 0;
  width: 100%; 
  background-color: #DAF3EF;
  color: black;
  display: flex;
  flex-direction: column; 
  align-items: center;
}

.footer a {
  color: black;
  text-decoration: none;
  transition: color 0.3s;
}

.footer a:hover {
  color: rgb(41,61,68,0.5);
}
  
  .footer-columns {
    display: flex;
  }
  
  .footer-column {
    flex: 1;
    padding: 20px;
    /* Additional column styles */
  }
  p{
    text-align: center;
  }
  input{
    border-radius: 35px;
    border: transparent;
    height: 40px;
    width:400px;
    margin-right: 10px;
  }
  button{
    border-radius: 35px;
    border:transparent;
    height: 40px;
    background-color:rgb(37,102,106);
  }
  .sub{
    align-content: baseline;
  }
  </style>
  

