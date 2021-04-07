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
  height: 30%;
  border-radius: 8%;
  background-color:#cbd5e8;
  font-size: 20px;
}

.row:after {
  content: "";
  display: table;
  clear: both;
}

.footer { 
  padding: 10px;
  text-align: center;
  color: #9299a6;
  opacity: 0.75;
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
  
  <div class="column"><b>Data Science</b>
    <p><br>
    <img src = "images/models.png" style="width: 90%; border-radius: 8%; display: block;
      margin-left: auto; margin-right: auto;">
    </p>
  </div>
  
  <div class="column"><b>Storyboards</b>
    <p><br>
    <img src = "images/.png" style="width: 90%; border-radius: 8%; display: block;
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
  
 <div class="column"><b>Hackathons</b>
  <p><br>
    <img src = "images/curiosity.png" style="width: 90%; border-radius: 8%; display: block;
      margin-left: auto; margin-right: auto;">
    </p>
  </div>
  
 <div class="column"><b>Learning Analytics</b>
  <p><br>
    <img src = "images/.png" style="width: 90%; border-radius: 8%; display: block;
      margin-left: auto; margin-right: auto;">
    </p>
  </div>

<div class="row">
  <div class="column"><b>Learning Management</b>
    <p><br>
    <img src = "images/.png" style="width: 90%; border-radius: 8%; display: block;
      margin-left: auto; margin-right: auto;">
    </p>
  </div>
  
</div>

<div class="footer">
  <p>Updated April 2021</p>
</div>
