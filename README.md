*{
    margin: 0;
    padding: 0;
}
.main{
    width: 100%;
    background: linear-gradient(to right,blue,tomato);
    background-position: center;
    background-size: cover;
    height: 100vh;
}
.logo{
   padding-left: 35px;
   padding-top: 35px;
   font-size: bold;
   color: tomato;
   font-size: 50px;
   
}
ul{
    display: flex;
}
ul li {
    color: aliceblue;
    font-size: 14px;
    font-family: Arial;
    margin-top: 30px;
    margin-left: 100px;
    font-size: 15px;
}
ul li a{
    color: white;
}
ul li a:hover{
    color: tomato;
}

.srch{
    background: tomato;
    border: 2px solid white;
    font-size: 15px;
    font-family: sans-serif;
    color: white;
    margin-left: 950px;
    margin-top: 5px;
    width: 250px;
    border-radius: 20px;

}
.butn{
    background:blue;
    border: 2px solid white;
    color: white;
    border-radius: 5px;
    width: 80px;
    font-size: 14px;
    height: 20px;
}
.content{
    padding-left: 80px;
    padding-top: 25px;
    color: white;

}
.content h1{
    font-size: 55px;
    padding-top: 50px;
}
.content .par{
    padding-left: 80px;
    padding-top: 40px;
    line-height: 20px;
    letter-spacing: 1px;
    font-size: 15px;
    font-family: serif;
    color: white;
}
.content .join{
    
    background: tomato;
    width: 80px;
    border-radius: 10px;
    font-size: 14px;
    margin-top: 40px;
    margin-left: 80px;
    color: white;
    border: 1px solid black;
}
.content span{
    color: tomato;
}
.form{
    width: 300px;
    height: 350px;
    left: 950px;
    top: 220px;
    background: linear-gradient(to right,blue,tomato);
    box-shadow: 5px 5px 5px 5px;
    position: absolute;
    text-align: center;
    justify-content: center;
    font-size: 17px;
    
}
.form h1{
    padding-top: 5px;
    color: whitesmoke;

}
.form input{
    border-bottom: 1px solid white;
    border-top: none;
    border-right: none;
    border-left:none ;
    background: transparent;
    color: white;
    width: 250px;
}
.form button{
    background: tomato;
    border-radius: 55px;
    width: 90px;
    height: 30px;
}
.form a{
    color: white;
   
}
.form p{
    font-size: 20px;
}
.form p1{
    font-size: 20px;
}
.icon a{
    padding-left: 20px;
    padding-top: 40px;
    font-size: 25px;
}
.icon :hover{
    color: tomato;
}
.form a:hover{
    color: tomato;
}
---------------------------------------------------------
<!DOCTYPE html>
<html lang="en">
<head>
    <title>webpage design</title>
    <link rel="stylesheet" href="stylesheet.css">
</head>
<body>
    <div class="main">
        <div class="navbar">
            <div class="icon">
                <h2 class="logo">PROGRAMS</h2>
            </div>
            <div class="menu">
                <ul>
                    <li><a href="#" >HOME</a></li>
                    <li><a href="#" >ABOUT</a></li>
                    <li><a href="#" >SERVICE</a></li>
                    <li><a href="#" >DESIGN</a></li>
                    <li><a href="#" >CONTACT</a></li>
                </ul>
            </div>
            <div class="search">
                <input type="text" class="srch">
                <a href="#">
                    <button class="butn"> SEARCH </button>
                </a>
            </div>
            <div class="content">
                <h1>WEB DESIGN & <br><span>DEVELOPEMENT</span><br>COURSE</h1>
                <p class="par">HTML was created by Sir Tim Berners-Lee in late 1991 but was not released officially,<br> published in 1995 as HTML 2.0.
                    HTML 4.01 was published in late 1999 and was a major <br>version of HTML. HTML 1.0 was released in 1993 with the intention of sharing 
                    information <br> can be readable and accessible via web browsers.</p>
                <button class="join"><a href="#" >JOIN US</a></button>
            </div>
            <div class="form">
                <h1>Login Here</h1><br><br>
                <input type="text "  name="username" placeholder="Username"><br><br>
                <input type="password" name="password" placeholder="Password"><br><br>
                <button >login </button><br><br>
                <p>Don't have an account?</p>
                <a href="#" >Sign up </a>here<br><br>
                <p1>login in with</p1><br><br>
                <div class="icon">
                    <a href="#" ><ion-icon name="logo-facebook"></ion-icon></a>
                    <a href="#" ><ion-icon name="logo-instagram"></ion-icon></a>
                    <a href="#" ><ion-icon name="logo-twitter"></ion-icon></a>
                    <a href="#" ><ion-icon name="logo-google"></ion-icon></a>
                    <a href="#" ><ion-icon name="logo-skype"></ion-icon></a>

                </div>

            </div> 
            
            
        </div>
    </div>
    <script src="https://unpkg.com/ionicons@5.4.0/dist/ionicons.js" ></script>
    
</body>
</html>
---------------------------------------------------------
https://unpkg.com/ionicons@5.4.0/dist/ionicons.js
