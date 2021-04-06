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
  padding: 30px;
  text-align: center;
  font-size: 35px;
}

/* Create three equal columns that floats next to each other */
.column {
  float: left;
  width: 33.33%;
  padding: 10px;
  height: 300px;
  border-radius: 25px;
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
  <h2 style="color: #636efa>Learning Design by Tina Leard</h2>
</div>

<div class="row">
  <div class="column" style="background-color:#b3cde3;">Column</div>
  <div class="column" style="background-color:#b3cde3;">Column</div>
  <div class="column" style="background-color:#b3cde3;">Column</div>
</div>

<div class="footer">
  <p>Footer</p>
</div>

</body>
</html>
