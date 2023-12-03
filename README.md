<!DOCTYPE html>
<html lang="en">
<head>
<title>Page Title</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}
html{
    background-color:rgb(103, 145, 128);
  color:dark rgb(112, 216, 148);
}
/* Style the body */
body {
  font-family: Arial, Helvetica, sans-serif;
  margin: 0;
 background-color:rgb(155, 216, 190);
  color:dark rgb(41, 118, 63);
}

/* Header/logo Title */
.header {
  padding: 80px;
  text-align: center;
  background: #5c9396;
  color: white;
}

/* Increase the font size of the heading */
.header h1 {
  font-size: 40px;
}

/* Style the top navigation bar */
.navbar {
  overflow: hidden;
  background-color: rgb(113, 230, 189);

}

/* Style the navigation bar links */
.navbar a {
  float: left;
  display: block;
  color: rgb(15, 100, 84);
  text-align: center;
  padding: 14px 20px;
  text-decoration: none;
}

/* Right-aligned link */
.navbar a.right {
  float: center
  ;
}

/* Change color on hover */
.navbar a:hover {
  background-color:rgb(196, 160, 196);
  color:rgb(130, 38, 217);
}

/* Column container */
.row {  
  display: -ms-flexbox; /* IE10 */
  display: flex;
  -ms-flex-wrap: wrap; /* IE10 */
  flex-wrap: wrap;
}

/* Create two unequal columns that sits next to each other */
/* Sidebar/left column */
.side {
  -ms-flex: 30%; /* IE10 */
  flex: 30%;
  background-color: #f1f1f1;
  padding: 20px;
}

/* Main column */
.main {   
  -ms-flex: 70%; /* IE10 */
  flex: 70%;
  background-color: rgb(255, 255, 255);
  padding: 20px;
}

/* Fake image, just for this example */
.fakeimg {
  background-color: rgb(128, 222, 208);
  width: 100%;
  padding: 20px;
}

/* Footer */
.footer {
  padding: 20px;
  text-align: center;
  background:rgb(192, 255, 241);
}

/* Responsive layout - when the screen is less than 700px wide, make the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 700px) {
  .row {   
    flex-direction: column;
  }
}

/* Responsive layout - when the screen is less than 400px wide, make the navigation links stack on top of each other instead of next to each other */
@media screen and (max-width: 400px) {
  .navbar a {
    float: none;
    width: 100%;
  }
}
</style>
</head>
<body>

<div class="header">
  <h1>Mirchi-Dhaba</h1>
  <p>Variety of food</p>
</div>

<div class="navbar">
  <a href="#" class="menu">MENU</a>
  <a href="#" class="contact">Contact Us</a>
  <a href="#" class="about">About Us</a>
  <a href="#" class="right">Work With Us</a>
</div>

<div class="row">
  <div class="side">
    <h2>About us</h2>
    <h5>WE located in the GTA region </h5>
    <div class="img" style="height:200px;">
            <img src="images/img1.mhtml" alt="our branch" width="200" height="200">
    </div>
    <p>Some text about me in culpa qui officia deserunt mollit anim..</p>
    <h3></h3>
    <p><iframe src="https://www.google.com/maps/embed?pb=!1m16!1m12!1m3!1d11541.004568527896!2d-79.82908826890868!3d43.68454199503338!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!2m1!1sindian%20restaurants!5e0!3m2!1sen!2sca!4v1701217059770!5m2!1sen!2sca" width="300" height="200" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe></p>
    <div class="fakeimg" style="height:60px;">Image</div><br>
    <div class="fakeimg" style="height:60px;">Image</div><br>
    <div class="fakeimg" style="height:60px;">Image</div>

  </div>
 
  <div class="main">
    <h2>MENU</h2>
    <h5>veg option,best dish of the year, Dec 21, 2019</h5>
   
    <img src="images/img2.mhtml" alt="Another branch" width="200" height="200">
   
    <p>Shahi Paneer<br>
      Originating from India’s Mughlai cuisine, shahi paneer is a rich, hearty and nutritious cheese.
      <div>
    <h2>new dish</h3>
    <h5>NON-veg option,best dish of the year,Apr 2, 2015</h5>
  
</div>
<div class="footer">
  <h2>Footer</h2>
</div>

</body>
</html>
