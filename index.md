
<html>
<head>
  <meta name="description" content="Die Website von Future Casio">
  <meta name="title" content="Future Casio">
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

#Shop {background-color: red;}
#Huellendesignen {background-color: green;}
#Spenden {background-color: blue;}
#Ueberuns {background-color: orange;}
  
#Umfragen {background-color: red;}
#Ideeneintragen {background-color: green;}
#Rezensionen {background-color: blue;}
#Kundensupport {background-color: orange;}
</style>
</head>
<body>
<center>Future Casio
<p>Die Revolution der Casio Taschenrechner!</p>
</center>

  
  <!--Obere Reiterbox-->
  
<button class="tablink" onclick="openPage('Shop', this, 'red')">Shop</button>
<button class="tablink" onclick="openPage('Huellendesignen', this, 'green')" >Hüllen designen</button>
<button class="tablink" onclick="openPage('Spenden', this, 'blue')">Spenden</button>
<button class="tablink" onclick="openPage('Ueberuns', this, 'orange')">Über uns</button>

<div id="Shop" class="tabcontent">
  <p>Der Shop von Future casio</p>
  <p>Kaufen sie jetzt unseren brandneuen Taschenrechner</p>
</div>

<div id="Huellendesignen" class="tabcontent">
  <p>Some news this fine day!</p> 
</div>

<div id="Spenden" class="tabcontent">
  <h3>Contact</h3>
  <p>Get in touch, or swing by for a cup of coffee.</p>
</div>

<div id="Ueberuns" class="tabcontent">
  <p>Who we are and what we do.</p>
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
  
<button class="tablink" onclick="openPage2('Umfragen', this, 'red')">Umfragen</button>
<button class="tablink" onclick="openPage2('Ideeneintragen', this, 'green')" >Ideen eintragen</button>
<button class="tablink" onclick="openPage2('Rezensionen', this, 'blue')">Rezensionen</button>
<button class="tablink" onclick="openPage2('Kundensupport', this, 'orange')">Kundensupport</button>
  
  <div id="Umfragen" class="tabcontent">
  <p>Der Shop von Future casio</p>
  <p>Kaufen sie jetzt unseren brandneuen Taschenrechner</p>
</div>

<div id="Ideeneintragen" class="tabcontent">
  <p>Some news this fine day!</p> 
</div>

<div id="Rezensionen" class="tabcontent">
  <h3>Contact</h3>
  <p>Get in touch, or swing by for a cup of coffee.</p>
</div>

<div id="Kundensupport" class="tabcontent">
  <p>Who we are and what we do.</p>
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
</body>
</html> 
