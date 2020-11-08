

# Request Header Parser Microservice


  A request to **/api/whoami**  should return a JSON object with your
  - IP address in the ipaddress key.
  - preferred language in the language key.
  - software in the software key
  
                                               Example Output:
  
  {    
  
      "ipaddress":"::ffff:123.45.6.7",       
      "language":"en-US,en;q=0.5",   
      "software":"Mozilla/5.0 (X11; Ubuntu; Linux x86_64; rv:80.0) Gecko/20100101 Firefox/80.0"    
  }
  
<!--lint disable no-literal-urls-->
<p align="center">
  <a href="https://nodejs.org/">
    <img
      alt="Node.js"
      src="https://nodejs.org/static/images/logo-light.svg"
      width="400"
    />
  </a>
</p>
