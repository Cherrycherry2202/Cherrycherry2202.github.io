<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="keywords"content = "suppy chain, logistic, book">
<meta name="author" content = "CHERRY">

<meta property="og:title" content ="Little Corner">
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
 <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
 <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

<title> My little corner</title>

<style>
.fa {
  padding: 10px;
  font-size: 20px;
  width: 40px;
  text-align: center;
  text-decoration: none;
  margin: 5px 2px;
}

.fa:hover {
  opacity: 0.7;
}

.fa-facebook {
  background: #3B5998;
  color: white;
  float: right;
}

.fa-twitter {
  background: #55ACEE;
  color: white;
  float:right;
}
/* Make the image fully responsive */
.carousel-inner img {
  width: 100%;
  height: 100%;
  }

* {
  box-sizing: border-box;
}

body {
  background-color: #f1f1f1;
  padding: 20px;
  font-family: Arial;
}

/* Center website */
.main {
  max-width: 1000px;
  margin: auto;
}

h1 {
  font-size: 50px;
  word-break: break-all;
  text-align: center;
}

.row {
  margin: 8px -16px;
}

/* Add padding BETWEEN each column */
.row,
.row > .column {
  padding: 8px;
}

/* Create four equal columns that floats next to each other */
.column {
  float: left;
  width: 25%;
}

/* Clear floats after rows */ 
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Content */
.content {
  background-color: white;
  padding: 10px;
}

/* Responsive layout - makes a two column-layout instead of four columns */
@media screen and (max-width: 900px) {
  .column {
    width: 50%;
  }
}

/* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
  }
}
img.sticky {
  position: -webkit-sticky;
  position: sticky;
  top: 0;
  width: 200px;
}
.navbar {
  width:100%;
  background-color: #555;
  overflow: auto;
}

.navbar a {
  float: justify;
  padding: 10px;
  color: white;
  text-decoration: none;
  font-size: 17px;
}

.navbar a:hover {
  background-color: #000;
}

.active {
  background-color: #4CAF50;
}
.search input[type=text] {
  padding: 6px;
  margin-top: 8px;
  font-size: 17px;
  border: none;
}

.navbar .search-container button {
  float: right;
  padding: 6px 10px;
  margin-top: 0px;
  margin-right: 16px;
  background: #ddd;
  font-size: 8px;
  border: none;
  cursor: pointer;
}

.search-container button:hover {
  background: #ccc;
}

@media screen and (max-width: 500px) {
  .navbar a {
    float: none;
    display: block;
  }
  
  .search-container button {
    float: none;
    display: block;
    text-align: left;
    width: 30%;
    margin: 0;
    padding: 0 px;
  }
  .navbar input[type=text] {
    border: 1px solid #ccc;  
  }
}

</style>
</head>
<body>
<div class="navbar">
  <a  href="#"><i class="fa fa-fw fa-home"></i> Home</a> 
  <a  href="#">      Supply Chain      </a> 
  <a  href="#">        Logistics        </a> 
  <a  href="#">      Coding        </a> 
  <a  href="#">       AI       </a> 
  <a href="#"><i class="fa fa-fw fa-envelope"></i> Contact</a> 
   <div class="search-container">
    <form action="/action_page.php">
      <input type="text" placeholder="Search.." name="search">
      <button type="submit"><i class="fa fa-search"></i></button>
    </form>
  </div>
</div>
<a href="#" class="fa fa-facebook"></a>
<a href="#" class="fa fa-twitter"></a>

<!-- MAIN (Center website) -->
<div class="main">

<h1><br> <br>LITTLECORNER.COM <br>
-----Sharing-----</h1>

<br>
<div id="demo" class="carousel slide" data-ride="carousel">
  <ul class="carousel-indicators">
    <li data-target="#demo" data-slide-to="0" class="active"></li>
    <li data-target="#demo" data-slide-to="1"></li>
    <li data-target="#demo" data-slide-to="2"></li>
  </ul>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="featured1.jpg" alt="Have Fun!" width="1100" height="500">
      <div class="carousel-caption">
        <h2>Have Fun!</h2>
      </div>   
    </div>
    <div class="carousel-item">
      <img src="featured4-1170x865.jpg" alt="Relaxed" width="1100" height="500">
      <div class="carousel-caption">
        <h2>Relaxed</h2>
   
      </div>   
    </div>
    <div class="carousel-item">
      <img src="featured2.jpg" alt="Work Hard!" width="1100" height="500">
      <div class="carousel-caption">
        <h2>Work Hard!</h2>
        
      </div>   
    </div>
  </div>
  <a class="carousel-control-prev" href="#demo" data-slide="prev">
    <span class="carousel-control-prev-icon"></span>
  </a>
  <a class="carousel-control-next" href="#demo" data-slide="next">
    <span class="carousel-control-next-icon"></span>
  </a>
</div>

<!-- Portfolio Gallery Grid -->
<div class="row">
  <div class="column">
    <div class="content">
      <a rel= "supply chain" href="file:///Users/cherrycherry2202/html/supply_chain.html">
        <img src="supply chain.jpg" alt="Supply Chain" style="width:100%">
      </a>
      <h3>Supply Chain </h3>
      <p> write later .</p>
    </div>
  </div>
  <div class="column">
    <div class="content">
    <img src="logistics.jpg" alt="Logistics" style="width:100%">
      <h3> Logistics </h3>
      <p>Information , my views about current logistic system.</p>
    </div>
  </div>
  <div class="column">
    <div class="content">
    <img src="coding.jpg" alt="Coding world" style="width:100%">
      <h3> coding </h3>
      <p> Little corner about coding.</p>
    </div>
  </div>
  <div class="column">
    <div class="content">
    <img src="data.jpg" alt="AI world" style="width:100%">
      <h3> AI </h3>
      <p>AI </p>
    </div>
  </div>
<!-- END GRID -->
</div>

<div class="content">
  <img src="profile.jpg" alt="author" style="width:30%">
  <h3>Author</h3>
  <p> Hello, My nickname is Cherry. I am living and working in Japan, like traveling and reading. I am a introvert. Have fun and enjoy my webside!</p>
  <p> Please contact my email: huongnguyen2202@gmail.com<br>
  Thank you</p>
</div>

<!-- END MAIN -->
</div>

</body>
</html>

V
