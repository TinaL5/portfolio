<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

body {
font-family: Arial, Helvetica, sans-serif;
}

a:link {
  text-decoration: none;
  color: #2368cf;
}

a:visited {
  text-decoration: none;
  color: #2368cf;
}

a:hover {
  text-decoration: underline;
  color: #2368cf;
}

a:active {
  text-decoration: underline;
  color: #2368cf;
}

.header {
text-align: center;
font-size: 20px;
color: #9299a6;
letter-spacing: 10px;
}

.column {
float: left;
width: 31.3%;
padding: 10px;
margin: 1%;
height: 50%;
border-radius: 8%;
background-color: rgba(203, 213, 232, 0.15);
font-size: 20px;
text-align: center;
overflow: hidden;
}

.row:after {
content: "";
display: table;
clear: both;
}

.footer {
margin-top: 2%;
font-size: 18px
}

@media (max-width: 600px) {
.column {
width: 100%;
}
}
</style>

</head>

<body>
  
<div class="header">
  <h1>Learning Systems by Tina Leard</h1>
</div>

<div class="row">
  
  <br>
  <div class="column"><a href="hci.html"><b>Human-computer</b>
    <p><br>
    <img src = "images/models.png" style="width: 90%; border-radius: 8%; display: block;
      margin-left: auto; margin-right: auto;">
  </p></a>
  </div>
  
   <br>
   <div class="column"><a href="research.html"><b>Research</b>
  <p><br>
   <img src="https://docs.google.com/drawings/d/e/2PACX-1vQwQyC0dtsPFWQuJpiWCLqVaIOfZWn3PDrzf9lUs5OPxf99E-tP4smM5_ABtj2TSdKepIIP-RZVQ9sG/pub?w=1067&amp;h=527" style="width: 98%; margin-left: auto; margin-right: auto; border-radius: 8%; display: block;">
  </p></a>
  </div>
  
   <br>
   <div class="column"><a href="design.html"><b>Interactive design</b>
  <p><br>
    <img src = "images/curiosity.png" style="width: 90%; border-radius: 8%; display: block;
      margin-left: auto; margin-right: auto;">
  </p></a>
  </div>
  
</div>

<div class="footer">
  <p style="text-align:center; color:#9299a6;">&#169; Tina Leard 2022</p>
</div>
  
</body>
