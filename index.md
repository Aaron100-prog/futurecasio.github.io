
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
  padding: 100px 20px;
  height: 100%;
}
  
  .button {
  background-color: #000000;
  border: none;
  color: red;
  padding: 10px 20px;
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

#Shop {background-color: darkblue;}
#Casedesigner {background-color: darkblue;}
#Surveys {background-color: darkblue;}
#Improvements  {background-color: darkblue;}
  
#Donations {background-color: darkblue;}
#Aboutus {background-color: darkblue;}
#Rezensionen {background-color: darkblue;}
#QandA {background-color: darkblue;}
</style>
</head>
<body style="background-color:black;">
  
<center>
    <h1 style="font-size: 4rem; color: #2ecc71">Casio</h1>
    <p>The biggest revolution to standard calculators <b>yet</b></p>
    <img src="images/schueler-in-friedrichshafen.png" alt="Test">>
</center>

  
  <!--Obere Reiterbox-->
  
<button class="tablink" onclick="openPage('Shop', this, 'darkblue')">Shop</button>
<button class="tablink" onclick="openPage('Casedesigner', this, 'darkblue')" >Case Designer</button>
<button class="tablink" onclick="openPage('Surveys', this, 'darkblue')">Surveys</button>
<button class="tablink" onclick="openPage('Improvements', this, 'darkblue')">Improvments</button>

<div id="Shop" class="tabcontent">
  <center>
  <p>From our calculator to a large variety of tools & gadgets, we have everything that your heart desires.</p>
  <a href="https://google.com" class="button">Shop</a>
    </center>
</div>

<div id="Casedesigner" class="tabcontent">
  <center>
  <p>We give our customers a possibility to create a indiviual case for their own calculator. with this feature, we want to give our customers a bit of freedom in individualising their calculator.</p>
  
  <p> WIP Cases</p>
    </center>
</div>

<div id="Surveys" class="tabcontent">
  <center>
    <p>We will use surveys to make sure that our ideas are accepted by our customers or to ask them if our recent update was a sucess or a total flop.</p>
  </center>
</div>

<div id="Improvements" class="tabcontent">
  <center>
    <p>We love to be in touch with our customers. We love it so much that we decided to make a section on our website for people that want to be involved with the future of our products. We give them the opportunity to share their ideas to the world and of course, to us.</p>
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
  
<button class="tablink" onclick="openPage2('Donations', this, 'darkblue')">Donations</button>
<button class="tablink" onclick="openPage2('Aboutus', this, 'darkblue')" >About us</button>
<button class="tablink" onclick="openPage2('Rezensionen', this, 'darkblue')">Rezensionen</button>
<button class="tablink" onclick="openPage2('QandA', this, 'darkblue')">Q&A</button>
  
  <div id="Donations" class="tabcontent">
    <center>
    <p> </p>
    <p>We would be very happy to use the donations to improve our products and to help various Foundations like researches for cancer or to help people, that are currently in war or in a 3rd world country.</p>
      </center>
</div>

<div id="Aboutus" class="tabcontent">
  <center>
  <p> </p>
  <p>Fehlt!</p> 
    </center>
</div>

<div id="Rezensionen" class="tabcontent">
  <center>
  <p> </p>
  <p>Critique can be harsh but also useful. We thank everyone that uses the review section to tell us the problems that they encountered while using our products and also the positive aspects they encountered.</p>
    </center>
</div>

<div id="QandA" class="tabcontent">
  <center>
  <p> </p>
  <p>Fehlt!</p>
  </center>
</div>
  
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
  
  <p> </p>
  <p> </p>
  <p> </p>
</body>
</html> 
