# Amazon-Clone
Amazon website clone
<--! HTML part-->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Events in javascript</title>
    <script>
function myfunc(){
    console.log("button is clicked");
}
function myfunc2(){
    console.log("key is pressed");
}
function dosomething(){
    alert("hello"); 
}
    </script>
</head>
<body>
    <h2>welcome to javascript events class</h2>
    <form action="#" method="get">
        <label for="firstname">First Name</label>
        <input type="text" name="firstname" id="fn" onkeyup="myfunc()"/>
        <br>
        <br>
        <label for="lastname">Last Name</label>

        <input type="text" name="lastname" id="ln"/>
        <br>
        <br>
        <label for="email">Email</label>
        <input type="email" name="email" id="em"/>
        <br>
        <br>
        <label for="contact">contact</label>
        <input type="number" name="contact" id="contact"/>
        <br>
        <br>
    </form>
    <div onclick="dosomething()">hello</div>
    <button onmouseover="myfunc()">submit</button>

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
