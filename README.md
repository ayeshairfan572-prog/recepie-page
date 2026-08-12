# recepie-page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Document</title>
</head>
<body>
    <center>
 <div class="container"> 
         <div class="img" >
            <br>
        <h1>today feature recepie</h1>
        </div>
     
     <h1 class="heading2">alfrado pasta</h1>
     <hr width="550">
     
     <div class="icon">
        <div class="icon1"><img src="icons8-clock-50.png" width="40">
            <span class="num">25</span>
            <br>
            <span class="item">minute</span>
        </div>
        <div class="icon2">
            <img src="icons8-open-book-50.png" alt="" width="40">
            <span class="num">7</span>
            <br>
            <span class="item">ingridient</span>
        </div>
        <div class="icon3">
            <img src="icons8-human-64.png" width="40">
            <span class="num">6-8</span>
            <br>
            <span class="item">serving</span>
    
            
        </div>
        
        
        
     </div>
     <br>
     <p class="text">Lorem ipsum dolor sit amet consectetur adipisicing elit. <br> Praesentium rem voluptatibus dolores deserunt repudiandae dicta nemo quis, sapiente <br> perferendis, odio officiis modi molestias reiciendis culpa velit possimus temporibus illo dolorum.</p>
    <br><br><br><br>
    
    <a href="https://www.allrecipes.com/recipe/23431/to-die-for--alfredo/fettuccine" target="_blank"><button > view recepie</button></a>
 </div>


     
        
    </div>
</center>
body{
    background-image: linear-gradient(rgb(91, 79, 79) rgb(168, 137, 137));
    height: 300px;
    background-color: rgb(199, 202, 202);
}
.container{
width: 550px;
height: 700px;
background-color: rgb(243, 239, 239);
margin-top: 30px;
border-radius: 12px;
box-shadow: 0px 8px 20px rgb(37, 21, 21);

}
.img{
    background-image: url(Instant-Pot-Fettuccine-Alfredo25-1-scaled.jpg);
    width: 550px;
    height: 320px;
    background-size: cover;
    background-repeat: no-repeat;
    
}
.img:hover{
    background-image: url(How-to-Make-Chicken-Alfredo-Pasta-hero-02082017.webp);
    cursor: pointer;
    width: 550px;
    height: 320px;
    background-size: cover;
}
h1{
    color: rgb(37, 28, 5);
    
    font-size: 25px;
    padding-top: 20px;
    text-shadow: 2px 4px 5px rgb(43, 26, 26);
    
}
.heading2{
    
    
    font-size: 32px;
    color: rgb(47, 34, 15);
    margin-top: 10px;
    
}
hr{
    width: 500px;
}
.icon{
    display: flex;
    justify-content: center;
    
    gap: 15px;
}
.icon1{
    width: 250px;
    text-align: center;
    
}
.icon2{
    width: 250px;
    text-align: center;
}
.icon3{
    width:250px;
    text-align: center;

}
.num{
    font-size: 26px;
    font-weight: bold;
    color: rgba(70, 57, 57, 0.401);
}
.item{
    font-size: 18px;
    color: rgb(26, 38, 38);
}
.text{
    width: 460px;
    height: 50px;
    margin: auto;
    font-size: 18px;
}

button{
    width: 220px;
    height: 50px;
    background-color: rgb(36, 26, 26);
    color: aliceblue;
    border: none;
    border-radius: 18px;
    font-size: 18px;
    cursor: pointer;
}
button.hover{
    background-color: rgb(48, 42, 42);
}


    



    
</body>
</html>
