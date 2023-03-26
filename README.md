# Amazon-Clone
Amazon website clone
<--! HTML part-->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>amazonclone</title>
    <link rel="stylesheet" href="amazonclone.css">
    <script src="https://kit.fontawesome.com/211484dd5c.js" crossorigin="anonymous"></script>
</head>
<body>
    <!--top navigation bar8-->
    <nav class="d-flex">
        <!--brand logo-->
        <div class="nav-brand">
            <a href="">
                <img src="1671722381385_logo.png" alt="Amazon">
                <span>.in</span>
            </a>
        </div>
        <!--select address-->
    <ul class="d-inline-block">
        <li>&nbsp</li>
        <li>
            <!--font awesome for location-->
            <i class="fa-sharp fa-solid fa-location-dot"></i>
        </li>

    </ul>
    <div class="addr">
        <a href="">
            <p>Hello</p>
            <h3>Select your address</h3>
        </a>
    </div>
    <!--end of select address-->
    <!--start of search-->
    <div class="d-flex search">
        <select name="allmenu" id="allmenu">
            <option value="all1">ALL1</option>
            <option value="all2">ALL2</option>
        </select>
        <!--INPUT TEXT-->
        <input type="text">
        <!--search icon-->
        <i class="fa-solid fa-magnifying-glass"></i>
    </div>
   
    <!--end of search-->
    <!--country flag-->
    <div>
        <!--flag image-->
        <img src="1671722385779_india.png" alt="india flag">
        <!--font awesome dropdown-->
        <i class="fa-sharp fa-solid fa-caret-down"></i>
    </div>
    <!--start of hello sign in account-->
    <ul class="d-flex nav_menu">
        <li>
            <a href="">
                Hello Sign in<br>
                <span>Account and lists <i class="fa-sharp fa-solid fa-caret-down"></i></span>
            </a>
        </li>

    
    <!--end of hello sign in account-->
    <!--start of returns and orders-->
        <li>
            <a href="">
                Returns<br>
                <span>& orders</span>
            </a>
        </li>
    <!--end of returns and orders-->
    <!--cart-->
    <li>
        <a href="#">
            <i class="fa-solid fa-cart-shopping"></i>
            <span>0</span>
        </a>
    </li>
    </ul>
    </nav>
    <!--end of main nav-->
    <!--start of submenu-->
    <div class="submenu">
        <a href="">
            <i class="fa-solid fa-bars"></i>
            ALL
        </a>
        <a href="">Best Seller</a>
        <a href="">Mobiles</a>
        <a href="">Electronics</a>
        <a href="">Prime
            <i class="fa-sharp fa-solid fa-caret-down"></i>
        </a>
        <a href="">Books</a>
        <a href="">Home & Kitchen</a>
        <a href="">
            <i class="fa-brands fa-amazon"></i>
            Prime day 23rd to 27th july
        </a>
    </div>
    <!--end of submenu-->
    <!--start of banner-->
    <div class="banner">
        <img src="1671722356263_banner1.jpg" alt="banner1"> 
    </div>
    <!--end of banner-->
    <!--start of products -->
    <div class="product">
        <div class="productsmall">
            <p class="heading">
                Prime day is back
            </p>
            <img src="1671722399253_product2.jpg" alt="product2">
            <a href="">see more</a>
        </div>

    </div>
    <div class="product">
        <div class="productsmall">
            <p class="heading">
                Smart gadgets in your home!.
            </p>
            <img src="1671722394326_product1.jpg" alt="product1">
            <a href="">see more</a>
        </div>
        <div class="productsmall">
            <p class="heading">
                smart watch
            </p>
            <img src="1671722404447_product3.jpg" alt="product3">
            <a href="">see more</a>
        </div>

    </div>
    <div class="product">
        <div class="productsmall">
            <p class="heading">
                Alexa
            </p>
            <img src="1671722410308_product4.jpg" alt="product4">
            <a href="">see more</a>
        </div>
        <div class="productsmall">
            <p class="heading">
                Tab
            </p>
            <img src="1671722417844_product5.jpg" alt="product5">
            <a href="">see more</a>
        </div>

    </div>
    <div class="product">
        <div class="productsmall">
            <p class="heading">
                Samsung TV
            </p>
            <img src="1671722425138_product6.jpg" alt="product6">
            <a href="">see more</a>
        </div>

    </div>
    <!--end of products -->

</body>
</html>




<--! css part-->
*{
    margin: 0;
    padding: 0;
    font-family: Arial, Helvetica, sans-serif;
    box-sizing: border-box;
}
:root{
    --color1: white;
    --color2: orange;
    --color3: grey;
    --bg-nav:rgb(29, 29, 67);
    --bg-subnav:#232f3e;
    --body-bg:#eaeded;
}
body{
    background-color: var(--body-bg);
}
ul{
    list-style-type: none;
}
a{
    text-decoration: none;
}
.d-flex{
    display: flex;
}
nav{
    margin: 0px;
    width: 100%;
    background-color: var(--bg-nav);
    align-items: center;
    position: sticky;
    top: 0;
    z-index: 1000;/*if the z-index value is high then the image will be supiriour , and that is how different stacking of elements are done*/
}   
nav .nav-brand a img{
    width: 100px;
    margin: 20px 18px 0;
}

nav .nav-brand a{
    display: flex;
    text-align: center;
    align-items: center;
    padding: 5px;
    font-weight: 600;
    color:var(--color1);
}
nav .nav-brand:hover{
    border: 1px solid var(--color2);
    /*margin: -1px;*/
    border-radius: 3px;
}
nav .nav-brand a span{
    font-size: 18px;
    margin-left: -17px;
    color: var(--color1);
}
nav .d-inline-block{
    color: var(--color1);
    padding: 10px;
}
nav .addr a {
    padding: 10px;
    color: var(--color1);
}
nav .addr p h3{
    font-size: 12px;
    line-height: 15px;
    
}
nav .addr:hover{
    border: 1px solid var(--color2);
    border-radius: 3px;
}
nav .search{
    flex: 1;
}
nav .search:hover{
    border-radius: 2px;
    border: 1px solid var(--color2);
}

nav .search #allmenu{
    border-radius: 5px 0px 0px 5px;
}
nav .search #allmenu option{
    border-radius: 5px 0px 0px 5px;
    background-color: var(--color2);
}

nav .search input{
    width: 100%;
    padding: 10px;
    border: 0;/*none also can be return instead of zero*/
}
nav .search .fa-magnifying-glass{
    padding: 10px  15px;
    background-color: var(--color2);
    border-radius: 0 5px 5px 0;
}
nav .countryflag{
    padding: 10px;
    color: var(--color1);
    margin-left: 10px;
}
nav .nav_menu li a{
    color: var(--color1);
    font-size: 12px;
    margin: 10px;
}
nav .nav_menu li a span{
    font-size: 14px;
    font-weight: bold;
    padding: 10px;
}
nav .nav_menu li:hover{
    border: 1px solid var(--color1);
    border-radius: 3px;

}
.submenu{
    background-color: var(--bg-subnav);
    padding: 16px;
}
.submenu a{
    color: var(--color1);
    font-size: 14px;
    margin: 0 35px;
    padding: 10px;
}
.submenu i{
   
    padding: 6px;
}
.fa-amazon {
    background-color: var(--color2);
}
.submenu a:hover{
    border: 1px solid var(--color1);
    border-radius: 3px;
}
.banner img{
    width: 100%;
    mask-image: linear-gradient(90deg,#000000,transparent);
    mask-image: radial-gradient(#000000 50%,white);
}
.product{
    background-color: aqua;
    
}
.product .productsmall p,a{
    font-size: large;
    text-align: left;
    color: rgb(26, 42, 18);
}

.product .productsmall img{
    width: 50%;
    border-radius: 40px;
    box-shadow: 2px 2px 5px black;
    border: 16px solid rgb(235, 230, 218);
}
