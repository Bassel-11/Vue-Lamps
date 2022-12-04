# Vue-Lamps
HTML AND CSS
i used html and css in this project 


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>website_1</title>
<!--     <link rel="stylesheet" href="style.css"> -->

</head>
    <style>
        *{
    margin: 0;
    padding: 0;
    font-family: 'Poppins', 'sans-serif';
    box-sizing: border-box;
}
.hero{
    background: #1d2026;
    min-height: 100vh;
    width: 100%;
    color: #fff;
    position: relative;
}
nav{
    display:flex;
    align-items: center;
}
nav .menu-img{
    width: 25px;
    margin-right: 20px;
    cursor: pointer;
}
nav .logo {
    width: 160px;
    cursor: pointer;
}
nav ul{
     flex: 1; 
    text-align: right;
}
nav ul li {
    display: inline-block;
    list-style-type: none;
    margin: 0 20px;
}
nav ul li a {
    text-decoration: none;
    color: white;
}
button {
    background: #efefef;
    height: 30px;
    width: 60px;
    border-radius: 20px;
    border: 0;
    outline: 0;
    cursor: pointer;
}
button span {
    display: block;
    background: #999;
    height: 26px;
    width: 26px;
    border-radius: 50%;
    margin-left: 2px;
}
.lamp-container{
    position: absolute;
    top: -20;
    left: 22%;
    width: 200px;
}
.lamp{
    width: 100px;
}
.light{
    position:absolute;
    top: 97%;
    left: 50%;
    transform: translateX(-50%);
    width: 370px;
    margin-left: -54px;
}
.text-container {
    max-width: 600px;
    margin-top: 7%;
    margin-left: 50%
}
.text-container h1 {
    font-size: 80px;
    font-weight: 400;
}
.text-container a {
    text-decoration: none;
    background: #00986f;
    padding: 14px 40px;
    display: inline-block;
    color: #fff;
    font-size: 18px;
    margin-top: 30px;
    border-radius: 30px;

}
    </style>
<body>
    <div class="hero">
        <nav>
            <img src="images/menu.png" class="menu-img">
            <img src="images/logo.png" class="logo">
            <ul>
                <li><a href="">Latest</a></li>
                <li><a href="">Modren</a></li>
                <li><a href="">Contemporary</a></li>
                <li><a href="">Affordable</a></li>
            </ul>
            <button type="button"><span></span></button>
        </nav>
        <div class="lamp-container">
            <img src="images/lamp.png" class="lamp">
            <img src="images/light.png" class="light">
        </div>
        <div class="text-container">
            <h1>Latest <br> in Lighting</h1>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit.
                 Fugiat ipsa debitis voluptas consequatur atque.
                 Sequi quos autem quia laudantium accusantium?
                 </p>
                 <a href="">Check All Collections</a>
        </div>
    </div>
</body>
</html>
