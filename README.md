<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Finbud</title>
        <style>
            h1 { 
            font-size: 36px; 
            color: #fcfcfc; 
            font-family: 'Arial', sans-serif;
            margin-left:200px;
        }
        
         p1 {
             font-size: 70px; 
             color: black; 
             font-family: 'Times New Roman', serif;
             margin-left:200px;
             margin-top:30px;
         }
         p2 {
             font-size: 70px; 
             color: black; 
             font-family: 'Times New Roman', serif;
             margin-left:200px;
             margin-top:30px;
         }
         p3 {
             font-size: 70px; 
             color:black; 
             font-family: 'Times New Roman', serif;
             margin-left:200px;
             
         }
         p4 {
            font-size:40px;
            color:rgb(242, 212, 15);
            margin-left:500px;
            margin-top:2000px;


         }
         .home-button
         {
            background-color:black;
            color:white;
            height:32px;
            width:100px;
            border-radius:32px;
            border-color:white;
            border-width:3px ;
            margin-left:900px;
            border:none;
            cursor:pointer;
        
         }
        .aboutus-button
        {
            background-color:black;
            color:white;
            height:32px;
            width:100px;
            border-radius:32px;
            border-color:white;
            border-width:3px ;
            margin-left:12px;
            border:none;
            cursor:pointer;
        
         } 
        .login-button
         {
            background-color:black;
            color:white;
            height:32px;
            width:100px;
            border-radius:32px;
            border-color:white;
            border-width:3px ;
            margin-left:12px;
            cursor:pointer;
        
         }
         .login-button a {
            color: white; 
            text-decoration: none;
         }
         .signup-button
         {
            background-color:black;
            color:white;
            height:32px;
            width:100px;
            border-radius:32px;
            border-color:white;
            border-width:3px ;
            margin-left:12px;
            cursor:pointer;
            
         }
         .help-button
         {
            background-color:black;
            color:white;
            height:32px;
            width:100px;
            border-radius:32px;
            border-color:white;
            border-width:3px ;
            margin-left:12px;
            border:none;
            cursor:pointer;
            
         }
         .multi-bg
         {
            background: linear-gradient(to right,#5d8ff5,#161a39)
         }
         .fade-in
         {
            opacity:0;
            animation:fadeInAnimation 2s forwards;
         }

         @keyframes fadeInAnimation {
            to {
                opacity:1; 
            }
         }
         .slide-in {
            transform: translateX(-100%);
            animation: slideIn 2s forwards;
         }

         @keyframes slideIn {
            to {
               transform: translateX(0);
            }
         }
         .expand {
            transform: scale(0);
            animation: expand 1s forwards;
         }

         @keyframes expand {
            to {
               transform: scale(1);
            }
         }
            


         </style>
         <body class="multi-bg">
            <div class="fixed-margin">
        <button class="home-button">HOME</button>
        <button class="aboutus-button">ABOUT US</button>
        <button class="help-button">HELP</button>
        <button class="login-button">
         <a href ="FBlogin.html">LOG IN</a>
        </button>
        <button class="signup-button">SIGN UP</button>
        
        </div>
        <h1>FinBud.</h1> 
        
        <p1 class="fade-in">The only place<br> </p1>
        <p2 class="fade-in"><b>that gets your </b><br></p2>
        <p3 class="fade-in"><b>money into shape</b></p3><br>
        <p4 class="expand"> Managing expenses just got easier with FinBud! </p4>
</body>
<script src= "project1.js" ></script>
</head>
</html>
