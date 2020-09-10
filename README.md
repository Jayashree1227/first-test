# Flask 

from flask import Flask
from flask import render_template

app = Flask(__name__, static_url_path = '')

@app.route('/')
def index():
    return render_template('index.html')


if __name__ == '__main__':
    app.run(host='0.0.0.0',port='80',debug ='True')


--------------------------------------------------------------------------------------------------------------------------------------------------------

# HTML 


<!DOCTYPE html>
<html>
<head>
      <title> FIRST TEST </title>
      <link rel="stylesheet" type="text/css" href="template.css">
 </head>
 <body>

<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">


<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>

<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>

       <header>
           <div class="main">
               <div class="logo">
                   <img src="LOGO.png">
                <ul>
                    <li class="active"><a href="#">Home</a></li>
                    <li><a href="#">Service</a></li>
                    <li><a href="#">Gallery</a></li>
                    <li><a href="#">About</a></li>
                    <li><a href="#">Contact us</a></li>
                </ul>
            </div>
            <div class="title">
                 <h1> FIRST TEST </h1>
            </div>

            <div class='button'>
                 <a href="#" class="btn">WATCH VIDEO</a>
                 <a href="#" class="btn">LERAN MORE</a>
            </div>
        </header>
 </body>
 </html>
 
---------------------------------------------------------------------------------------------------------------------------------------------------------

# CSS 

  height: auto;
}

.main{
        max-width: 1200px;
        margin: auto;
}


.title{
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%,-50%);
}
 .title h1{
        color: #fff;
        font-size: 90px;
 }

 .button{
        position:absolute;
        top: 55%;
        left: 42%;
        text-align: center;

}

.btn:hover{
        background-color: #fff;
        color: #000;
}

.btn{
        text-decoration: underline;
        padding: 5px 20px;
        border:1px solid transparent;
        transition: 0.6s ease;
        color: #000;



























