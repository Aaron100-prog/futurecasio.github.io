
<html>
<head>
  <meta charset = "utf-8" />
  <meta name="description" content="Die Website von Future Casio">
  <meta name="title" content="Future Casio">
  <title>Future Casio Website</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {box-sizing: border-box}
  
.page-header{
color:#ffff;
background-color:#A067AB;
background-image:linear-gradient(120deg,#5073B8,#A067AB);
}
/* Set height of body and the document to 100% */
body, html {
  height: 100%;
  margin: 0;
  font-family: Arial;
}
  
 .rectangle {
  height: 50px;
  width: 100px;
  background-color: #555;
}

/* Style tab links */
.tablink {
  background-color: #555;
  color: white;
  float: left;
  border: none;
  outline: none;
  cursor: pointer;
  padding: 14px 16px;
  font-size: 17px;
  width: 25%;
}

.tablink:hover {
  background-color: #777;
}

/* Style the tab content (and add height:100% for full page content) */
.tabcontent {
  color: white;
  display: none;
  padding: 0px 20px;
  height: 100%;
}
  
  .button {
  background-color: #000000;
  border: none;
  color: red;
  padding: 10px 40px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  margin: 4px 2px;
  cursor: pointer;
  border-radius: 16px;
}

.button:hover {
  background-color: #f1f1f1;
}
  
  .accordion {
  background-color: #eee;
  color: #444;
  cursor: pointer;
  padding: 18px;
  width: 100%;
  border: none;
  text-align: left;
  outline: none;
  font-size: 15px;
  transition: 0.4s;
}

.active, .accordion:hover {
  background-color: #ccc; 
}

.panel {
  padding: 0 18px;
  display: none;
  background-color: white;
  overflow: hidden;
}

#Store {background-color: #2ecc71;}
#Casedesigner {background-color: #2ecc71;}
#Surveys {background-color: #2ecc71;}
#Improvements  {background-color: #2ecc71;}
  
#Donations {background-color: #2ecc71;}
#Aboutus {background-color: #2ecc71;}
#Reviews {background-color: #2ecc71;}
#QandA {background-color: #2ecc71;}
</style>
</head>
<body style="background-color:black;">
  
<center>
  <div class="centered">
  <h1 style="font-size: 60px; color: #2ecc71">Casio</h1>
    <p style="font-size: 30px;">The biggest revolution to standard calculators <u><b>yet</b></u></p>
  </div>
    <img src="images/schueler-in-friedrichshafen.png" alt="Test">
</center>

  <p><br></p>
  <p><br></p>
  <p><br></p>
  
  <!--Obere Reiterbox-->
  
<button class="tablink" onclick="openPage('Store', this, '#2ecc71')">Store</button>
<button class="tablink" onclick="openPage('Casedesigner', this, '#2ecc71')" >Case Designer(WIP)</button>
<button class="tablink" onclick="openPage('Surveys', this, '#2ecc71')">Surveys</button>
<button class="tablink" onclick="openPage('Improvements', this, '#2ecc71')">Improvements</button>

<div id="Store" class="tabcontent">
  <center>
    <p><br></p>
    <p><br></p>
  <p>Would you like a Hightech-math product with a big range of tools & gadgets, or even a case to go with it?</p>
  <p>Then hit it!</p>
  <a href="https://aaron100-prog.github.io/futurecasio.github.io/Shop" class="button">Shop</a>
    <p><br></p>
    </center>
</div>

<div id="Casedesigner" class="tabcontent">
  <center>
    <p><br></p>
    <p><br></p>
  <p>Comes in the future.</p>
  <p>(create custom the sleeve and case for their own taste)</p>
    
    <a href="https://aaron100-prog.github.io/futurecasio.github.io/Shop" class="button">Open Designer</a>
    <p><br></p>
    </center>
</div>

<div id="Surveys" class="tabcontent">
  <center>
    <p><br></p>
    <p><br></p>
    <p>Participate in our surveys to ensure that we make our products even better and give you, our customers, the very best.</p>
    <p><br></p>
  </center>
</div>

<div id="Improvements" class="tabcontent">
  <center>
    <p><br></p>
    <p><br></p>
    <p>Contact with our customers is very important to us! We love it so much that we decided to create a section on our website for people who want to be involved in the future of our products. We give them the opportunity to share their ideas with the world and of course with us. We look forward to your suggestions.</p>
<p>When we read a great idea, we ask our customers in the poll section if they think this idea should be used in future updates or projects.</p>
    <p><br></p>
  </center>
</div>

<script>
function openPage(pageName,elmnt,color) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablink");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].style.backgroundColor = "";
  }
  document.getElementById(pageName).style.display = "block";
  elmnt.style.backgroundColor = color;
}

// Get the element with id="defaultOpen" and click on it
document.getElementById("defaultOpen").click();
</script>
  
  <!--Untere Reiterbox-->
  
<button class="tablink" onclick="openPage2('Donations', this, '#2ecc71')">Donations</button>
<button class="tablink" onclick="openPage2('Aboutus', this, '#2ecc71')" >About us</button>
<button class="tablink" onclick="openPage2('Reviews', this, '#2ecc71')">Reviews</button>
<button class="tablink" onclick="openPage2('QandA', this, '#2ecc71')">Q&A</button>
  
  <div id="Donations" class="tabcontent">
    <center>
    <p><br></p>
    <p><br></p>
    <p><br></p>
    <p>Would you like to support other than buying and using our products? Then you can also donate to us here, which we use to improve our work and for various foundations such as cancer research or the environment.</p>
      <p><br></p>
      </center>
</div>

<div id="Aboutus" class="tabcontent">
  <center>
  <p><br></p>
    <p><br></p>
    <p><br></p>
  <p>We are a subsidiary of calculator giant Casio, which has set itself the task of developing a n ultramodern educational device that will be sold in industrialized places such as the USA, Japan and parts of Europe.</p> 
    <p> Our priorities are customer friendliness, openness and efficiency.</p> 
    <p><br></p>
    </center>
</div>

<div id="Reviews" class="tabcontent">
  <center>
    <p><br></p>
    <p><br></p>
    <p><br></p>
  <p>Criticism can be hard, but it can also be useful. Thank you to everyone who uses the review section to share with us the problems as well as the positives they encountered while using our products. You are also welcome to rate our central points such as technology, number of functions and possibilities with points from 1 to 10.</p>
    <p><br></p>
    </center>
</div>

<div id="QandA" class="tabcontent">
  <p><br></p>
    <p><br></p>
    <p><br></p>
  <button class="accordion">What is casio connection and how does it work?</button>
<div class="panel">
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
</div>

<button class="accordion">What are your plans for the future?</button>
<div class="panel">
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
</div>

<button class="accordion">Section 3</button>
<div class="panel">
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
</div>
  <p><br></p>
  <p>If you have any other problems with our products or have any other questions, please don't hesitate to ask our friendly staff who will assist you in any way and as soon as possible</p>
  <center>
  <a href="https://aaron100-prog.github.io/futurecasio.github.io/Support" class="button">Support</a>
    </center>
  <p><br></p>
</div>
  
  <script>
var acc = document.getElementsByClassName("accordion");
var i;

for (i = 0; i < acc.length; i++) {
  acc[i].addEventListener("click", function() {
    this.classList.toggle("active");
    var panel = this.nextElementSibling;
    if (panel.style.display === "block") {
      panel.style.display = "none";
    } else {
      panel.style.display = "block";
    }
  });
}
</script>
  
  <script>
function openPage2(pageName,elmnt,color) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablink");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].style.backgroundColor = "";
  }
  document.getElementById(pageName).style.display = "block";
  elmnt.style.backgroundColor = color;
}

// Get the element with id="defaultOpen" and click on it
document.getElementById("defaultOpen").click();
</script>
  
  <p><br></p>
  <p><br></p>
  <p><br></p>
</body>
</html> 
