<html xmlns='http://www.w3.org/1999/xhtml' lang='' xml:lang=''>
<head>
	<meta charset='utf-8' />
	<meta name='viewport' content='width=device-width, user-scalable=no' />
	<title>Casio</title>
<style>
* {box-sizing: border-box}
	
	
.page-header{
color:#ffff;
background-color:#A067AB;
background-image:linear-gradient(120deg,#5073B8,#A067AB);
}
	
.transparent-style{

    background-color: black;

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
  background-color: white;
}
  
  .accordion {
  background-color: black;
  color: darkgrey;
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
  background-color: #555; 
}

.panel {
  padding: 0 18px;
  display: none;
  background-color: black;
  overflow: hidden;
}
  /* Popup container - can be anything you want */
.popup {
  position: relative;
  display: inline-block;
  cursor: pointer;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

/* The actual popup */
.popup .popuptext {
  visibility: hidden;
  width: 160px;
  background-color: #555;
  color: #fff;
  text-align: center;
  border-radius: 6px;
  padding: 8px 0;
  position: absolute;
  z-index: 1;
  bottom: 125%;
  left: 50%;
  margin-left: -80px;
}

/* Popup arrow */
.popup .popuptext::after {
  content: "";
  position: absolute;
  top: 100%;
  left: 50%;
  margin-left: -5px;
  border-width: 5px;
  border-style: solid;
  border-color: #555 transparent transparent transparent;
}

/* Toggle this class - hide and show the popup */
.popup .show {
  visibility: visible;
  -webkit-animation: fadeIn 1s;
  animation: fadeIn 1s;
}

/* Add animation (fade in the popup) */
@-webkit-keyframes fadeIn {
  from {opacity: 0;} 
  to {opacity: 1;}
}

@keyframes fadeIn {
  from {opacity: 0;}
  to {opacity:1 ;}
}
  
  * {
  box-sizing: border-box;
}

/* Create two equal columns that floats next to each other */
.column {
  float: left;
  width: 50%;
  padding: 10px;
  height: 300px; /* Should be removed. Only for demonstration */
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}
	
	.btn {
  background-color: #2ecc71;
  border: none;
  color: white;
  padding: 12px 16px;
  font-size: 16px;
  cursor: pointer;
}

/* Darker background on mouse-over */
.btn:hover {
  background-color: #2ecc71;
}
	
#element1 {display:inline-block;}
  

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
    <p style="font-size: 30px; color: white">The biggest calculator revolution starts <u><b>now!</b></u></p>
  </div>
    <img src="images/Taschenkind.png" alt="Test" width="600" height="540">
</center>

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
	<a href="https://aaron100-prog.github.io/futurecasio.github.io/Shop" class="button">Store</a>
    <p><br></p>
    </center>
</div>

<div id="Casedesigner" class="tabcontent">
  <center>
    <p><br></p>
    <p><br></p>
  <p>Comes in the future.</p>
  <p>(create a custom sleeves and cases for their own taste)</p>
    <div class="popup" onclick="Popupfunction()"><a class="button"><p style="color: red">Open Designer</p></a>
  <span class="popuptext" id="myPopup">Still WIP sry!</span>
</div>
    
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
  <button class="accordion"><p style="color: white">What is casio connection and how does it work?</p></button>
<div class="panel">
  <p>Casio Connection is an app adapted for school lessons. If the teacher connects their laptop to the product with a cable and Casio Connection is activated on their own device, he is the host and all students only need to activate Casio Connection as well. Then the teacher can directly set in the app which features should be on and which should be off, so that the students cannot cheat in tests, for example. If someone disconnects, the teacher sees this and recognizes the attempted fraud.</p>
</div>

  <button class="accordion"><p style="color: white">What are your plans for the future?</p></button>
<div class="panel">
  <p>For the time being, we will mainly focus on our hopefully soon launch and will provide our device with more and more tools.
If our product is very well received, we will move more and more towards a school device in the future and move away from the focus on math.</p>
</div>

  <button class="accordion"><p style="color: white">When will you start with the production</p></button>
<div class="panel">
  <p>Mrs. Schäfer, please give us a good mark for our project. The whole thing took so long. Don't we deserve it?!</p>
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
// When the user clicks on div, open the popup
function Popupfunction() {
  var popup = document.getElementById("myPopup");
  popup.classList.toggle("show");
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
  
	  
<footer>
  <div class="row">
  <div class="column" style="background-color:black;">
	  <center>
		  <p><br></p>
  <p><br></p>
	  <p><a href="https://aaron100-prog.github.io/futurecasio.github.io/Cookies">Cookies</a></p>
	  <p><a href="https://aaron100-prog.github.io/futurecasio.github.io/Legal">Legal</a></p>
	  <p><a href="https://aaron100-prog.github.io/futurecasio.github.io/Privacy">Privacy</a></p>
		  </center>
  </div>
  <div class="column" style="background-color:black;">
	  <center>
		  <p><br></p>
  <p><br></p>
    <p><a href="https://aaron100-prog.github.io/futurecasio.github.io/Support">Support</a></p>
	  <p><a href="https://aaron100-prog.github.io/futurecasio.github.io/Help">Help</a></p>
	  <p><a href="https://aaron100-prog.github.io/futurecasio.github.io/Credits">Credits</a></p>
	  </center>
  </div>
</div>
	<center>
	<div id="element1"> <button class="btn"><i class=""></i></button> </div> 
	<div id="element1"> <button class="btn"><i class=""></i></button> </div> 
	<div id="element1"> <button class="btn"><i class=""></i></button> </div>
		<p><br></p>
	  <img src="images/casio.png" alt="Test" width="426" height="82">
	</center>
</footer> 
</body>
</html> 
