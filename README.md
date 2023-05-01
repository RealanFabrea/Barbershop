<!DOCTYPE html>
<html>
<head>
    <meta name="viewport" content="width=device-width, intial-scale=1.0">
    <title>3 CJS Barbershop</title>
    <link rel="stylesheet"  href="style.css">
</head>
<body>

    
    <div class="navbar">
        <ul>
            <li><a href="home.html">Home</a></li>
            <li><a href="about.html">About us</a></li>
            <li><a href="services.html">Services</a></li>
            <li><a href="contactus.html">CONTACT US</a></li>       
        </ul>  
</div>
 
        <div class="wrapper1">
                <img src="images/final.png">
                <div class="info">
                <h2> Barbershop Details</h2><br>
                <p>• Established on December 28,2016</p> 
                <p>• Block-15 Lot-1 2nd gate</p>
                <p>• Xavier Heights Subdivision,Cagayan de Oro City</p>  
                <p>• Opens on Monday - Sunday 7:30am - 7:30pm</p>  
                </div>
        </div>

        <div class="wrapper1">
            <img src="images/owner.jpg">
            <div class="info">
            <h2> Owner of 3CJ's Barbershop</h2><br>
            <p>Christine Jeza Buot</p> 
            <p>• Graduate in Chemical Engineering</p> 
            <p>• Secondary Teacher in Bulua National High School</p> 
            <p></p> 

            </div>
        </div>

        <div class="wrapper1">
            <img src="images/barbers.jpg">
            <div class="info">
            <h2> Name of Barbers</h2><br>
            <p>Kearl Mortos and Kurt Sarbida</p> <br>
            <p>• Schedule: Monday - Sunday</p>
            </div>
        </div>


    


       <div class="footer">

        <div class="footer-down">
            <p>All right reserved 2023  3CJ's Barbershop</p>
        </div>
    </div>
  </div>
</body>
</html>

<!DOCTYPE html>
<html>
<head>
    <meta name="viewport" content="width=device-width, intial-scale=1.0">
    <title>3 CJS Barbershop</title>
    <link rel="stylesheet"  href="style.css">
</head>
<body>

    <div class="navbar">
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="about.html">About us</a></li>
                <li><a href="services.html">Services</a></li>
                <li><a href="styles.html">Styles</a></li>            
            </ul>  
    </div>

    <div class="content">
        
        
        </b><h1>CONTACT US</h1>
        <p>+639062865211</p><br>
        <p>Block-15 Lot-1 2nd gate Xavier Heights Subdivision, Cagayan de Oro City, Philippines</p><br>
        <p>christinejeza.bout@deped.gov.ph</p><br>
    </div>
    
    

   <div class="footer">

        <div class="footer-down">
            <p>All right reserved 2023  3CJ's Barbershop</p>
        </div>
    </div>
  </div>
</body>
</html>

<!DOCTYPE html>
<html>
<head>
    <meta name="viewport" content="width=device-width, intial-scale=1.0">
    <title>3 CJS Barbershop</title>
    <link rel="stylesheet"  href="style.css">
</head>
<body>

    <div class="navbar">
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="about.html">About us</a></li>
                <li><a href="services.html">Services</a></li>
                <li><a href="contactus.html">CONTACT US</a></li>            
            </ul>  
    </div>

    <div class="content">
        
        
        </b><h1>3 CJ's BARBERSHOP</h1>
        <p>an establishment that offers haircutting</p>
        <p>services for men, women and children.</p>
    </div>
    
    

   <div class="footer">

        <div class="footer-down">
            <p>All right reserved 2023  3CJ's Barbershop</p>
        </div>
    </div>
  </div>
</body>
</html>

<!DOCTYPE html>
<html>
<head>
    <meta name="viewport" content="width=device-width, intial-scale=1.0">
    <title>3 CJS Barbershop</title>
    <link rel="stylesheet"  href="style.css">
</head>
<body>
    <div class="navbar">
        <ul>
            <li><a href="home.html">Home</a></li>
            <li><a href="about.html">About us</a></li>
            <li><a href="services.html">Services</a></li>
            <li><a href="contactus.html">CONTACT US</a></li>        
        </ul>  
</div>

<div class="wrapper1">
    <img src="images/shave.jpg">
    <div class="info"><br><br><br><br><br>
    <h2> SHAVE 80.00 PHP</h2><br>
    </div>
</div>
<div class="wrapper1">
    <img src="images/haircut.jpg">
    <div class="info"><br><br><br><br><br>
    <h2> HAIRCUT 80.00 PHP</h2><br>
    </div>
</div>
<div class="wrapper1">
    <img src="images/haircolor.jpg">
    <div class="info"><br><br><br><br><br>
    <h2> HAIRCOLOR 200.00 PHP</h2><br>
    </div>
</div>

</body>
</html>

*{
    margin: 0;
    padding: 0;
    font-family: "Poppins", sans-serif;
    box-sizing: border-box;
}


html, body{
    width: 100%;
    background-image: url("images/background.jpg");
    background-size: cover;
    height: 100%;
    position: relative;
}



.navbar{
   width: 80%;
   margin-left: 200px;
   padding: 30px 0;
   
   align-items: center;
   justify-content: space-between;
   text-align: right;
   
}
.navbar ul li{
    display: inline-block;
    list-style: none;
    margin: 10px 20px;
    position: relative;
    margin-top: 10px;
    font-size: x-large;
    
}
.navbar ul li a{
    text-decoration: none;
    color: white;
    text-align: right;
}
.navbar ul li a:hover{
    color:red;
    
}
    

.navbar ul li::after{
    content: '';
    height: 3px;
    width: 0;
    background: red;
    position: absolute;
    left: 0;
    bottom: -10px;
    transition: 0.3s;
    
}
.navbar ul li:hover::after{
    width: 100%;
    
}

.content{
    width: 60%;
    margin: 160px auto 0;
    text-align: center;
    color: white;
}

.content h1{
    font-size: 75px;
    color: red;
    margin-bottom: 20px;
    font-family: 'Times New Roman', Times, serif;
}

.content p{
    font-size: 30px;
}






.footer{
    padding: 50px 0 20px;
    background: darkkhaki;
    position: relative;
    display: block;
    margin-top: 20%;
}
.title{
    text-align: center;
    font-size: medium;
    color: red;
}
.footer-row{
    width: 80%;
    margin: 0 auto;
    display:flex;
    justify-content: space-between;
    flex-wrap: wrap;

}
.footer-down{
    text-align: left;
    margin-left: 40%;
}

.wrapper1{

    margin: 200px auto;
    width: 33%;
    display: inline-flex;
    margin-left: 3.3px;
    padding: 70px;

    
}
img{
    
    max-width: 250px;
    float: left;
    border: 3px solid #fff;
    border-radius: 20px;
    margin-right: 2%;
    


}
.info{
    margin-right: 10%;
    font-family: 'Times New Roman';
    font-size:large;
    color: white;
    
    
}<!DOCTYPE html>
<html>
<head>
        <style>
            *{
                    padding:0px;
                    margin:0px;
            }
                header{
                    background-color: #fff;
                    height:20%;
                    border:1px solid red;
                }
                nav a{
                    background-color: rgb(166, 5, 5);
                    padding:10px;
                    color: #fff;
                    text-decoration: none;
                }
                nav{
                    border:1px solid blue;  

                }
                footer{
                    border:1px solid green;

                }
                #wrapper{
                    border:1px solid black;
                    width: 85%;
                    margin-left:7%;
                    margin-right:5%;
                }
            
        </style>
</head>
<body>
    <div id="wrapper">
        <header>
            <nav>   
                <a href="#" >HOME</a>
                <a href="#about" >ABOUT</a>
                <a href="#" >SERVICES</a>
                <a href="#" >CONTACT US </a>
            </nav>
            <h3>BARBER SHOP</h3>
        </header>
        <div id="container">
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>  <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>  <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>  <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>  <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>

            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>  <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
        <div id="about">
            <p >ABOUT US</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>  <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p><p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>  <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p><p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>  <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p><p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>  <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p><p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>  <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p><p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>  <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
        </div>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
            <p>hello hello hello hellofnbdjfjhdsbfbjdsfkjdskfjbdf</p>
        </div>
        <footer>
                <a href="#" >HOME</a>
                <a href="#" >ABOUT</a>
                <a href="#" >SERVICES</a>
                <a href="#" >CONTACT US</a>
        </footer>

    </div>
</body>
</html>
