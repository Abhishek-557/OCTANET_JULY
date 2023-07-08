# OCTANET_JULY
This repo contains Summer Web Development Internship Task

HTML CODE : 

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Landing Page</title>
    <link rel="stylesheet" href="landingpage.css">
    <!-- <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
        <script src="https://code.jquery.com/jquery-3.6.4.min.js"></script> -->
    <!-- <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>  -->

</head>

<body>
    <header class="header">
        <nav>
            <div class="Logo">
                वाराणसी
            </div>
            <div class="menu">
                <a href="#">About</a>
                <a href="#">Places</a>
                <a href="#">Online Booking</a>
                <a href="#">Contact</a>
            </div>
        </nav>
        <section class="head-txt">
            <h1>बनारस </h1><span ></span>
            
            
            
        </section>
        
        
    </header>

    

    </div>
    
</body>

CSS CODE:

*{
    margin:0;
    padding:0;
    scroll-behavior: smooth;
    
    font-family:"poppins";
    outline: none;
    border: none;
    /* text-decoration: none; */
}
.header{
    width: 100%;
    height: 100vh;
    background: linear-gradient(rgba(90, 76, 66, 0.56),rgba(255, 241, 134, 0.829)) , url(https://www.outlookindia.com/outlooktraveller/public/uploads/articles/see/photoessay/Dasashvamedha-Ghat-Varanasi-Uttar-Pradesh.jpg);
    background-size: cover;
    font-family: sans-serif;
    
  /* text-align: center;
 background-color: black; */
 }
 /* img{
    width: 100%;
    height: 100%;
    opacity: 0.69;
    background-size: cover;
}

/* .cover-pic img{
    width: 1506px;
    height: 200vh;
    background-size: cover;
    background-color: crimson;
    background-attachment: fixed;
    opacity: 0.69;
} */
nav{
    display: flex;
    align-items:center;
    justify-content: space-around;
    width: 100%;
    height: 50px;
    
    text-decoration: none;
    
} 
.menu{
    font-size: 1.2em;
}
.menu a{
    text-decoration: none;
    color: azure;
    width: 50%;
    
    margin-top: 8rem;
    padding-left: 5rem;
    padding-right: 5rem;
}
.Logo{
    font-size: 2.2em;
    letter-spacing: 5px;
    color: rgb(251, 243, 9);
    cursor: pointer;
}
.menu a:hover{
    background-color: rgb(248, 207, 118);
    color: indianred;
    font-size: 1.9em;
}
.head-txt{
    display: inline-block;
    text-align: center;
   top: 50%;
   left: 50%;
   transform: translate(-50%,-50%);
    position: absolute;
    color: #e6dddd;
    white-space: nowrap;
    overflow: hidden;
    animation: 
    infinite 2s
    typing  2s steps(4);
    cursor : .4 step-end infinite ;
}

/* span::before{
    content: 'VARanasi';
    animation:  infinite 3s;
    
} */
@keyframes cursor {
    50% { border-color: transparent}
    
    
} 
@keyframes typing {
    from { width: 0;}
    
    
} 
.head-txt h1{
    max-width: 1000px;
    font-size: 900%;
}
/* .head-txt span{
    font-size: 1.5em;
    color: rgba(5, 1, 255, 0.771);
    text-shadow: black;
    
} */
