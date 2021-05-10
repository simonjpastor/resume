<head>
<style>
body {
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
}

.topnav {
  overflow: hidden;
  top: 50%;
  background-color: #5DADE2;
  border-top-left-radius: 10px;
  border-bottom-left-radius: 10px;
  border-top-right-radius: 10px;
  border-bottom-right-radius: 10px;

}

.topnav a {
  float: left;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
  width: 20%;
  margin:0;
  border-top-left-radius: 6px;
  border-bottom-left-radius: 6px;
  border-top-right-radius: 6px;
  border-bottom-right-radius: 6px;
}


.topnav a:hover {
  background-color: #ddd;
  color: black;
}

.topnav a.active {
  background-color: #3498DB;
  color: white;
}
      /* The dropdown container */
      .dropdown {
      float: left;
      overflow: hidden;
      color: #3498DB;
      }
      /* Dropdown button */
      .dropdown .dropbtn {
      float: center;
      color: #3498DB;
      text-align: center;
      padding: 14px 16px;
      text-decoration: none;
      font-size: 17px;
      min-width:18.5%;
      margin:0;
      }
      /* Dropdown content (hidden by default) */
      .dropdown-content {
      display: none;
      position: absolute;
      background-color: #f9f9f9;
      min-width: 18.6%;
      box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
      z-index: 1;
      }
      /* Links inside the dropdown */
      .dropdown-content a {
      float: none;
      color: black;
      padding: 12px 16px;
      text-decoration: none;
      display: block;
      text-align: center;
      min-width:100%;
      }
      /* Add a grey background color to dropdown links on hover */
      .dropdown-content a:hover {
      min-width:100%;
      background-color: #cc2;
      }
      /* Show the dropdown menu on hover */
      .dropdown:hover .dropdown-content {
      display: block;
      }

@media screen and (max-width: 600px) {
  .topnav {position: relative;}
  .topnav a {
    float: left;
    display: block;
    text-align: center;
    width:100%;
  }
  .topnav a.icon {
    float: right;
    display: block;
  }

}

* {
  box-sizing: border-box;
}

input[type=text], select, textarea, input[type=email]{
  width: 40%;
  padding: 12px;
  border: 1px solid #ccc;
  border-radius: 4px;
  margin-top: 6px;
  margin-bottom: 16px;
  resize: vertical;
}

input[type=submit] {
  background-color: #04AA6D;
  color: white;
  padding: 12px 20px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

input[type=submit]:hover {
  background-color: #45a049;
  border-radius: 4px;
}


.container {
  border-radius: 5px;
  background-color: #f2f2f2;
  padding: 10px;
}

@media screen and (max-width: 600px) {
  .container, input[type=submit] {
    width:90%;
    height: 65%;
    margin-top: 0;
  }

  .column {
    width: 100%;
    height: auto;
  }
}

</style>
</head>
<body>
  <div class="topnav">
    <a href="https://simonpastor.com">Home</a>
    <a href="https://simonpastor.com/portfolio">Portfolio</a>
    <!-- <div class="dropdown"> */
      <button class="dropbtn">
        <a href="#contact">SimonSays</a>
      <i class="fa fa-caret-down"></i>
      </button>
      <div class="dropdown-content">
         <a href="#">Emperor Gaius Trump</a>
         <a href="#">Harmless Tradition or (Khat)astrophe?</a>
         <a href="#">Post-Covid Social Status:Unclear</a>
      </div>
    </div> -->
    <a href="https://simonpastor.substack.com">SimonSays</a>
    <a class="active" href="">Resume</a>
    <a href="https://simonpastor.com/contact">Contact</a>
  </div>

<!-- <center>
<h1> <font color='#5DADE2'>Welcome to my Portfolio!</font></h1>
</center>
<br> -->
<center>
  <br>
  <br>

<div class="container">
  <div style="text-align:center">
    <center>
    <p style="font-size:33px">
    <font color='#5DADE2'>
      <strong>Download Resume</strong>
    </font>
    </p>
    </center>
  </div>
  <center>
  <div class="row">
    <form action="https://formspree.io/f/mknkjweb" method="POST">
      <label for="full-name"><p style="font-size:18px">Full Name</p></label>
      <input type="text" id="full-name" name="name" placeholder="Your full name..." required="">
      <br><br>
      <label for="email-address"><p style="font-size:18px">Email Address</p></label>
      <input type="email" id="email-address" name="_replyto" placeholder="Your email..." required="">
      <br><br>
      <center><input type="submit" value="Download Resume"></center>
    </form>
  </div>
  </center>
</div>

<br><br>

<center>
<a href="https://www.linkedin.com/in/simonpastor/"><p style="font-size:20px">View My Linkedin Profile</p></a>
<a href="https://twitter.com/the_simonpastor"><p style="font-size:20px">Follow me on Twitter 🐦</p></a>
<a href="https://simonpastor.substack.com"><p style="font-size:20px">Check out my Substack 💭</p></a>
</center>

<!-- ### Other Projects Simon Pastor -->

<!-- [Project 1 Title](http://example.com/) Simon Pastor
- [Project 2 Title](http://example.com/) Simon Pastor
- [Project 3 Title](http://example.com/) Simon Pastor
- [Project 4 Title](http://example.com/) Simon Pastor
- [Project 5 Title](http://example.com/) Simon Pastor -->
<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-192273691-1"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'UA-192273691-1');
</script>


