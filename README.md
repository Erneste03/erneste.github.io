.header {
  font-family: "Comic Sans MS", "Comic Sans", cursive;
  padding: 22px;
  text-align: center;
  background: #000000;
  color: white;
  font-size: 30px;
}

/* Add a black background color to the top navigation */
.topnav {
  background-color: rgb(33, 6, 130);
  overflow: hidden;
}

/* Style the links inside the navigation bar */
.topnav a {
  font-family: "Comic Sans MS", "Comic Sans", cursive;
  float: left;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}

/* Change the color of links on hover */
.topnav a:hover {
  background-color: rgb(221, 221, 221);
  color: black;
}

/* Add a color to the active/current link */
.topnav a.active {
  background-color: #04AA6D;
  color: white;
}

.single_shoes {
  position: absolute;
  top: 500px;
  left: 30px;

}

.single_shoes {
  position: absolute;
  top: 500px;
  left: 30px;

}

.single_shoes2 {
  position: absolute;
  top: 500px;
  left: 300px;

}

.single_shoes3 {
  position: absolute;
  top: 500px;
  left: 570px;

}

.single_shoes4 {
  position: absolute;
  top: 500px;
  left: 840px;

}

.single_shoes5 {
  position: absolute;
  top: 500px;
  left: 1110px;

}

/*position Caution image on page 3*/

.Caution {
  position: absolute;
  top: 500px;
  left: 500px;

  /*Bacground of page*/
}

body {
  background-image: url(images/pileofjordans.jpeg);
}

/*make all images on page 2 circle*/
.single_shoes img {

  border-radius: 50%;
}

.single_shoes2 img {

  border-radius: 50%;
}

.single_shoes3 img {

  border-radius: 50%;
}

.single_shoes4 img {

  border-radius: 50%;
}

.single_shoes5 img {

  border-radius: 50%;
}

.tooltip {
  position: relative;
  display: inline-block;
  border-bottom: black;
}

.single_shoes .tooltiptext {
  visibility: hidden;
  width: 120px;
  background-color: black;
  color: #fff;
  text-align: center;
  border-radius: 6px;
  padding: 5px 0;

  /* Position the tooltip */

  position: absolute;
  z-index: 1;
  width: 120px;
  bottom: 100%;
  left: 50%;
  margin-left: -60px;


}

.single_shoes2 .tooltiptext {
  visibility: hidden;
  width: 120px;
  background-color: blue;
  color: #fff;
  text-align: center;
  border-radius: 6px;
  padding: 5px 0;

  /* Position the tooltip */

  position: absolute;
  z-index: 1;
  width: 120px;
  bottom: 100%;
  left: 50%;
  margin-left: -60px;

}

.single_shoes3 .tooltiptext {
  visibility: hidden;
  width: 120px;
  background-color: black;
  color: #fff;
  text-align: center;
  border-radius: 6px;
  padding: 5px 0;

  /* Position the tooltip */

  position: absolute;
  z-index: 1;
  width: 120px;
  bottom: 100%;
  left: 50%;
  margin-left: -60px;
  /* Use half of the width (120/2 = 60), to center the tooltip */


}

.single_shoes4 .tooltiptext {
  visibility: hidden;
  width: 120px;
  background-color: blue;
  color: #fff;
  text-align: center;
  border-radius: 6px;
  padding: 5px 0;

  /* Position the tooltip */

  position: absolute;
  z-index: 1;
  width: 120px;
  bottom: 100%;
  left: 50%;
  margin-left: -60px;
  /* Use half of the width (120/2 = 60), to center the tooltip */

}

.single_shoes5 .tooltiptext {
  visibility: hidden;
  width: 120px;
  background-color: darkgray;
  color: #fff;
  text-align: center;
  border-radius: 6px;
  padding: 5px 0;

  /* Position the tooltip */

  position: absolute;
  z-index: 1;
  width: 120px;
  bottom: 100%;
  left: 50%;
  margin-left: -60px;
  /* Use half of the width (120/2 = 60), to center the tooltip */

}

.single_shoes:hover .tooltiptext {
  visibility: visible;
}

.single_shoes2:hover .tooltiptext {
  visibility: visible;
}

.single_shoes3:hover .tooltiptext {
  visibility: visible;
}

.single_shoes4:hover .tooltiptext {
  visibility: visible;
}

.single_shoes5:hover .tooltiptext {
  visibility: visible;
}

.size_of_img {
  width: 90px
}

.latestnews a:link {
  text-decoration: black;
  font-size: 20px;
  color: #000000;
}

.latestnews a:visited {
  text-decoration: none;
  color: black;
}

.latestnews a:hover {
  text-decoration: underline;
}

.latestnews a:active {
  text-decoration: underline;
}

.latestnews li {
  margin-bottom: 60px;
  background-color: orange;
}

.latestnews p {
  color: rgb(255, 255, 255);
  height: 10%;
  background-color: rgb(33, 6, 130);
  font-size: 24px;

  line-height: -700px;
  margin-top: 0px;

}

@keyframes moveIt {
  from {
    background-position: bottom left;
  }

  to {
    background-position: top right;
  }
}

.latestnews {
  font-family: "Comic Sans MS", "Comic Sans", cursive;
  background-image: url(images/camo.jpeg);
  background-size: 261px;
  animation: moveIt 20s linear infinite;
  color: white;
  height: 500px;
  width: 300px;
  text-align: center;
  border-radius: 25%;
  background-color: rgb(0, 0, 0);
  overflow: hidden;
  position: absolute;
  left: 25px;
  top: 400px;
  border: 3px solid #ad7721;
}

.latestshoes a:link {
  text-decoration: rgb(134, 17, 17);
  font-size: 20px;
  color: #861313;
}

.latestshoes a:visited {
  text-decoration: none;
  color: black;
}

.latestshoes a:hover {
  text-decoration: underline;
}

.latestshoes a:active {
  text-decoration: underline;
}

.latestshoes {
  font-family: "Comic Sans MS", "Comic Sans", cursive;
  background-color: black;
  background-size: 261px;

  color: white;
  height: 500px;
  width: 800px;
  text-align: center;
  border-radius: 25%;
  background-color: rgb(0, 0, 0);
  overflow: hidden
}

.latestshoes {

  position: absolute;
  left: 400px;
  top: 400px;
  border: 3px solid #ad7721;
}

.latestshoes {
  background-color: #333;
  overflow: auto;
  white-space: nowrap;
}

.latestshoes a {
  display: inline-block;
  color: white;
  text-align: center;
  padding: 14px;
  text-decoration: none;
}

.latestshoes a:hover {
  background-color: #777;
  text-decoration: none;
}

.text-block {
  position: absolute;
  bottom: 400px;
  right: 90px;
  background-color: black;
  color: rgb(0, 13, 255);
  padding-left: 20px;
  padding-right: 20px;
  text-align: center;
  font-size: 35px;
}

.latestshoes h4 {
  color: rgb(255, 255, 255);
  height: 10%;
  background-color: rgb(33, 6, 130);
  font-size: 24px;

}

.latestshoes li {
  display: inline;
}

.latestshoes1 {
  position: absolute;
  top: 310px;
  left: 70px;
}

.latestshoes2 {
  position: absolute;
  top: 310px;
  left: 250px;
}

.latestshoes3 {
  position: absolute;
  position: absolute;
  top: 310px;
  left: 430px;
}

.latestshoes4 {
  position: absolute;
  position: absolute;
  top: 310px;
  left: 610px;
}

.latestshoes1 img {

  border-radius: 50%;
}

.latestshoes2 img {

  border-radius: 50%;
}

.latestshoes3 img {

  border-radius: 50%;
}

.latestshoes4 img {

  border-radius: 50%;
}

.latestshoes h4 {
  line-height: -700px;
  margin-top: 0px;
}

.footer {
  font-family: "Comic Sans MS", "Comic Sans", cursive;
  text-align: center;
  padding: 7px;
  background-color: rgb(33, 6, 130);
  color: white;
}
.box{
  font-family: "Comic Sans MS", "Comic Sans", cursive;
  text-align: center;
left :500px;
  position: absolute;
  top: 500px;
  border: blue solid 6px;
}

input {
  width: 100%;
}

.box {
  color: rgb(255, 255, 255);
  height: 10%;
  background-color: rgb(33, 6, 130);
  font-size: 24px;
  left: 400px;
  top: 500px;
  

}


.box {
  font-family: "Comic Sans MS", "Comic Sans", cursive;
font-size: 15px;
  color: white;
  height: 500px;
  width: 600px;
  text-align: center;
  border-radius: 25%;
  background-color: #333;
  overflow: auto;
  position: absolute;

  border: 3px solid #ad7721;
}


input[type=text] {
  font-family: "Comic Sans MS", "Comic Sans", cursive;

  height: 10px;
 
  width: 40%;
  padding: 12px 20px;
  margin: 8px 0;
  box-sizing: border-box;
  border: 3px solid #ccc;
  -webkit-transition: 0.5s;
  transition: 0.5s;
  background-color: #333;
  outline: none;
  
}

input[type=text]:focus {
  border: 3px solid rgb(79, 55, 201);
}

textarea{
  font-family: "Comic Sans MS", "Comic Sans", cursive;

  background-color: #333;
}

  
.Fname-lname  {  
  font-family: "Comic Sans MS", "Comic Sans", cursive;

  margin-top: 50px;

}

form {
  font-family: "Comic Sans MS", "Comic Sans", cursive;

  margin-left: 0px; 
}
input[type=submit] {
  width: 100px;
}
.box h4 {
  color: rgb(255, 255, 255);
  height: 10%;
  background-color: rgb(33, 6, 130);
  font-size: 24px;
  line-height: -700px;
  margin-top: 0px;
  margin-bottom: -40px;
}
.df :focus {
  font-family: "Comic Sans MS", "Comic Sans", cursive;

  height: 10px;
 
  width: 40%;
  padding: 12px 20px;
  margin: 8px 0;
  box-sizing: border-box;
  border: 3px solid #ccc;
  -webkit-transition: 0.5s;
  transition: 0.5s;
  background-color: #333;
  outline: none;
}

.df :focus {
  border: 3px solid rgb(79, 55, 201);
}
.shoeszshirt select{
  background-color: #333;
  font-family: "Comic Sans MS", "Comic Sans", cursive;

 color: #777;
   padding: 2px 20px;
  margin: 8px 0;
  box-sizing: border-box;
  border: 3px solid #ccc;
  -webkit-transition: 0.5s;
  transition: 0.5s;
  background-color: #333;
  outline: none;
}
.shoeszshirt select:focus{
  background-color: #333;
  font-family: "Comic Sans MS", "Comic Sans", cursive;

 
   padding: 12px 20px;
  margin: 8px 0;
  box-sizing: border-box;
  border: 3px solid #ccc;
  -webkit-transition: 0.5s;
  transition: 0.5s;
  background-color: #333;
  outline: none;
}
.shoeszshirt select:focus{
border: 3px solid rgb(79, 55, 201);
}
