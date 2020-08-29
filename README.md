#HTML page 
<!DOCTYPE html>
<html>
<head>
      <title> FIRST TEST </title> # title would be appread in the TAB 
      <link rel="stylesheet" type="text/css" href="css/style.css"> # link between external file 
 </head> 
 <body>
       <header> # beginning
           <div class="main"> # division or a section , container for HTML elements
               <div class="logo">
                   <img src="LOGO.png">
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">Service</a></li>
                    <li><a href="#">Gallery</a></li>
                    <li><a href="#">About</a></li>
                    <li><a href="#">Contact us</a></li>
                </ul>
            </div>
        </header>
 </body>
 </html>
 
 
 #CSS
 *{
    margin: 0;
    padding: 0;
    font-family: Century Gothic;
}

header{
	background-image:url(../bg.jpg);
	height: 100vh;
	background-size: cover;
	background-position: center;
}

ul{
	float: right;
	list-style-type: none;
	margin-top: 25px;

}

ul li{
	display: inline-block;
}

ul li a{
	text-decoration: none;
	color: #fff;
	padding: 5px 20px;
	border:1px solid #fff;
	transition: 0.6s ease; 

}

ul li a:hover{
	background-color: #fff;
	color: #000;
}

.logo img{
	float: left;
	width: 150px;
	height: auto;
}

.main{
	max-width: 1200px;
	margin: auto;
}
 
 
