<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Wirtschaft Facharbeit</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300;0,400;0,500;0,600;0,700;0,800;1,300;1,400;1,500;1,600;1,700;1,800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
    
  <style>
    font-family: 'Open Sans', sans-serif;
            background-color: #F3F5F6;
            padding-left: 100px;
            padding-right: 100px;
        }
            

    

        .header-image {
            width: 100%;
            height: 300px;
            object-fit: cover;
            display: block;
        }
        
        .headline {
            color: #831D17;
        }

        .image-container{
           background-color: white;
           padding: 16px; 
        }

        .navbar{
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        a {
            color: #831D17;
            text-decoration: none;
            margin-left: 16px;
            font-weight: 700;
        }

        a:hover {
            text-decoration: underline; 
        }

        .text-hilight{
            color: #484846;
            font-size: 46px;
        }

        .text-container{
            background-color: #DEDEDE;
            padding: 8px;
            background-color: #F3F5F6;
            font-weight: 600;
            
        }

        .maps-container{
            margin-top: 16px;
            display: flex;
            justify-content: space-between;
        }

        .maps-right{
            margin-left: 16px;
            width: 30%;
        }

        .maps-frame{
            border: 0;
            height: 350px;
            width: 70%;
        }

        .navbar-left{
            width: 40%;
        }
        
        


@media (max-width: 800px){
        html, body{
            font-family: Arial, Helvetica, sans-serif;
            background-color: #F3F5F6;
            padding-left: 5px;
            padding-right: 5px; 
        }
        
        .text-hilight{
            font-size: 16px;
        }
        
        .text-first{
            font-size: 18px;
        }
        
        .navbar-left{
            width: 50%;
        }  

        .infos{
            width: 30%;
        }
        .infos-space{
            display: flex;
            margin-bottom: 1px;
        }
        
        .header-image{
            width: 100%;
            height: 100px;

        }

        .image-container{
            margin-top: 10px;
        }

        a{
            text-decoration: underline;
        }
        
        .maps-right{
            width: 30%;
            font-size: 10px;
        }
        
        .maps-container{
            height: 100px;
        }

        .maps-frame{
            height: 100px;
        }
      }
  }


  </style>
    
</head>
<body>
    <div class="navbar">
        <div class="navbar-left">
            <h1 class="headline left-headline">
            <span class="text-first">Wirtschaft Projektarbeit</span><br> <span class="text-hilight">BBS 1 Northeim</span>
            </h1>
        </div>
            <div class="infos">
                <a href="#"><span class="infos-space">Infos</span></a>
                <a href="#"><span class="infos-space">Preise</span></a>
                <a href="#"><span class="infos-space">Termine</span></a>
                <a href="#"><span class="infos-space">Standort</span></a>
            </div>

    </div>


    <div class="image-container">
        <img class="header-image" src="Kurse.jpg">

        <div class="text-container">
            Marketing Auswirkungen auf die Marktwirtschaft
        </div>

        <div class="maps-container">
            <iframe class="maps-frame" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2473.2465379454875!2d9.993550416061643!3d51.691933379665834!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x47a52c97f17a35a5%3A0xfa8ac86380f6fb23!2sBerufsbildende%20Schulen%20I%20Northeim!5e0!3m2!1sde!2sde!4v1642277303208!5m2!1sde!2sde" 
            allowfullscreen="" loading="lazy"></iframe>
         
            <div class="text-container maps-right">
                Standort der BBS1 Northeim
            </div>
        </div>
        
    </div>
