# OCTANET_JULY
This repo contains Summer Web Development Internship Task

HTML CODE and CSS CODE : 

<!DOCTYPE html>
<html lang="en">
<head>
    <title>Creative Landing Page Using Html and Css</title>
    <style type="text/css">
        *{padding: 0; margin:0; box-sizing: border-box;}
        header{
            width: 100%;
            height: 100vh;
            background-image:linear-gradient(rgba(0,0,0,0.8),rgba(0,0,0,0.2)), url('Agency.jpg');
            background-repeat: no-repeat;
            background-attachment: fixed;
            background-size: 100% 100%;   
            font-family: sans-serif;

        }
        nav{
            width:100%;
            height:100px;
            color:white;
            display: flex;
            justify-content: space-around;
            align-items: center;
        }
        .logo{
            font-size:2em;
            letter-spacing: 2px;
        }
        .menu a{
            text-decoration: none;
            color:white;
            padding: 10px 20px;
            font-size: 20px;
            position: relative;
        }
        .menu a:before{
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width:0%;
            height:100%;
            border-bottom: 2px solid indianred;
            transition:0.3s linear;
        }
        .menu a:hover:before {
            width: 90%;
        }
        .register a{
            text-decoration: none;
            color:white;
            padding: 10px 20px;
            font-size: 20px;
            background:indianred;
            border-radius: 8px;
            transition:0.4s;
        }
        .register a:hover{
            background: transparent;
            border:1px solid indianred;
        }
        .h-txt{
            max-width:650px;
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%,-50%);
            text-align: center;
            color:white;
        }
        .h-txt span{
            letter-spacing: 5px;
        }
        .h-txt h1{
            font-size: 3.5em;
        }
        .h-txt a{
            text-decoration: none;
            background: indianred;
            color: white;
            padding: 10px 20px;
            letter-spacing: 5px;
            transition: 0.4s;
        }
        .h-txt a:hover{
            background: transparent;
            border:1px solid indianred;
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <div class="logo">
                Travel-X
            </div>
            <div class="menu">
                <a href="#">Home</a>
                <a href="#">Hill Stations</a>
                <a href="#">Best Offer</a>
                <a href="#">Our Sites</a>
                <a href="#">Contact</a>
            </div>
            <div class="register">
                <a href="#">Register</a>
            </div>
        </nav>

        <section class="h-txt">
            <span>Enjoy</span>
            <h1>International Travel Agency</h1>
            <br>
            <a href="#">Book your Trip</a>
        </section>
    </header>
</body>
</html>
