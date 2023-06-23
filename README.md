# Exp-2-Create-a-commercial-website-using-HTML-CSS
## AIM:
To create a commercial website using HTML & CSS.

## ALGORITHM:
## STEP 1:
Create basic outline for website using html.

## STEP 2:
Create style part of the website using css.

## STEP 3:
Link the css file with html code using link tag.

## STEP 4:
Run the code and check the webpage in an web browser.

## PROGRAM:
```.html
HTML:
<!DOCTYPE html>
<html>
    <head>
        <title>Webpage</title>
        <link rel="stylesheet" href="style.css">
    </head>
    <header>
        <div class="first">
        <h2 class="logo"><span>A</span>nto Mess-Both veg & Non-Veg</h2>
        <!--<p>Anto Mess-Both veg & Non-Veg</p>-->
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Catalog</a>
        <button>Order now</button>
        </div>
    </header>
    <br>
    <br>
    <body>
        <p><img align="right"src="burger.webp"height="300">
            <h2>Quality food delivered</h2>
            </p>
        <p>Retail food delivery is a courier service in which a restaurant, store, or independent food-delivery company delivers food to a customer. An order is typically made either through a restaurant or grocer's website or mobile app, or through a food ordering company.
        </p>
        <button> Get started </button>     
       <br>
       <br>
       <div class="first">
        <div id="l">
    <p><img src="Masala-Dosa.webp"height="300">
    </div>
</div>
        <h1><b>Traditional vegetarian food</b></h1>
    </p>
    <p>Vegetarian food is good for health and thats's what we provide here in Anto Mess-Both veg & Non-Veg,as we focus on customers health before money reaches the table</p>
    <button>Order veg food</button>
    <div class="first">
        <div id="l">
    <p><img src="Guntur-Gongura-Biryani.jpg"height="300">
    </div>
</div>
        <h1><b>Traditional Non-vegetarian food</b></h1>
    </p>
    <p>Non-Vegetarian food is good for health and thats's what we provide here in Anto Mess-Both veg & Non-Veg,as we focus on customers health before money reaches the tableA non-vegetarian diet includes chicken, meat, eggs and fish. A non-vegetarian diet also has several health benefits because this type of food is rich in protein and vitamin B.</p>
    <button>Order Non-veg food</button>
    <!--<footer>-->
    <footer>
        <div class="footer_main">
            <div class="footer_tag">
                <h2><span>Contact</span></h2>
                <p>+91 6663334442</p>
                <p>+91 88884444220</p>
                <p>johndeo123@gmail.com</p>
                <p>foodshop123@gmail.com</p>
            </div>
    
            <div class="footer_tag">
                <h2><span>More Links</span></h2>
                <p>Gallery</p>
                <p>Inside our shop</p>
                <p>Pricing</p>
            </div>
    
            <div class="footer_tag">
                <h2><span>Follow us</span></h2>
                <i class="fa-brands fa-facebook-f"></i>
                <i class="fa-brands fa-twitter"></i>
                <i class="fa-brands fa-instagram"></i>
                <i class="fa-brands fa-linkedin-in"></i>
            </div>
    
        </div>
    
    </footer>
    </body>
</html>

```

```.css
CSS:
.first{
    color:black;
    font-size: large;
    display: flex;
    justify-content:space-around;
    background-color: rgb(82, 233, 250);
}
.logo{
    font-size: 2em;
    color: #c51691;
    cursor: default;
}

.logo span{
    color: #7d2ae8;
}
button{
    background-color: rgb(200, 31, 68);
    border-radius: 0%;
    color: #000000;;
}
a{
    color: black;
}
p{
    font-size:x-large;
    color: rgb(33, 104, 186);
}
body{
    background-color: rgb(207, 250, 135);
}
img {
    float: right;
    border: 1px dotted black;
    margin: 0px 0px 15px 20px;
  }
.l{
    float:left; 
}
footer{
    width: 100%;
    padding: 20px 0 0 10px;
    background:rgb(118, 247, 197);
    bottom:50px;
    position: relative;
}

footer .footer_main{
    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr 1fr;
}

footer .footer_main .footer_tag{
    text-align: center;
}

footer .footer_main .footer_tag h1 span{
    color: #fac1317c;
}
footer .footer_main .footer_tag h2 span{
    color: #d5b562;
}

footer .footer_main .footer_tag h2{
    color:white;
    margin-bottom: 25px;
    font-size: 30px;
}

footer .footer_main .footer_tag p{
    margin: 10px 0;
}

footer .footer_main .footer_tag i{
    
    margin: 0 5px;
    cursor: pointer;
}

footer .footer_main .footer_tag i:hover{
    color: black;
}

footer .end{
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 15px;
}

footer .end span{
    color: black;
    margin-left: 10px;
}
::-webkit-scrollbar{
    width: 13px;
}

::-webkit-scrollbar-track{
    border-radius: 15px;
    box-shadow: inset 0 0 5px rgba(0,0,0,0.5);
}

::-webkit-scrollbar-thumb{
    background: rgb(153, 217, 221);
    border-radius: 15px;
}

```

## OUTPUT:

![web-1](https://github.com/Guruprasad21002001/Exp-2-Create-a-commercial-website-using-HTML-CSS/assets/95342910/bd1b037a-8e9d-48ed-bc85-f8e88662fbb5)

![web-2](https://github.com/Guruprasad21002001/Exp-2-Create-a-commercial-website-using-HTML-CSS/assets/95342910/f76d9b62-1bc2-43ce-b264-1e4b9878d71a)

![web-3](https://github.com/Guruprasad21002001/Exp-2-Create-a-commercial-website-using-HTML-CSS/assets/95342910/c0b57527-3b35-439c-8a3e-8ace53ce7266)

## RESULT:
A commercial website using HTML & CSS has been created and output verified sucessfully.
