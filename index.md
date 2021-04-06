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

/* Style the header */
.header {
  text-align: center;
  font-size: 20px;
}

/* Create three equal columns that floats next to each other */
.column {
  float: left;
  width: 33.3%;
  padding: 10px;
  margin: 5px;
  height: 30%;
  border-radius: 8%;
  background-color:#cbd5e8;
  opacity: 0.75;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Style the footer background-color: #f1f1f1;*/
.footer { 
  padding: 10px;
  text-align: center;
  color: #878e9c;
  opacity: 0.5;
}

/* Responsive layout - makes the three columns stack on top of each other instead of next to each other */
@media (max-width: 600px) {
  .column {
    width: 100%;
  }
}
</style>
</head>
<body>

<div class="header">
  <h1 style="color: #878e9c; letter-spacing: 10px">Learning Design by Tina Leard</h1>
</div>

<div class="row">
  <div class="column"><b>Sports Analytics</b>
    <p><br>
    <img src = "images/models.png" style="width: 90%; border-radius: 8%; display: block;
      margin-left: auto; margin-right: auto;">
    </p>
  </div>
  
  <div class="column"><b>Hackathon</b>
  <p><br>
    <img src = "images/curiosity.png" style="width: 90%; border-radius: 8%; display: block;
      margin-left: auto; margin-right: auto;">
    </p>
  </div>
  
  <div class="column"><b>Machine Learning</b>
    <p><br>
    <img src = "images/matrix.png" style="width: 80%; border-radius: 8%; display: block;
      margin-left: auto; margin-right: auto;">
    </p>
  </div>  
</div>
  
<div class="row">
  <div class="column"><b>Learning Management</b>
    <p><br>
    <img src = "images/.png" style="width: 90%; border-radius: 8%; display: block;
      margin-left: auto; margin-right: auto;">
    </p>
  </div>
  
  <div class="column"><b>Storyboarding</b>
  <p><br>
    <img src = "images/.png" style="width: 90%; border-radius: 8%; display: block;
      margin-left: auto; margin-right: auto;">
    </p>
  </div>
  
  <div class="column"><b>Research</b>
  <p><br>
    <img src = "images/.png" style="width: 90%; border-radius: 8%; display: block;
      margin-left: auto; margin-right: auto;">
    </p>
  </div>
</div>

<div class="footer">
  <p>Updated April 2021</p>
</div>

</body>
</html>
