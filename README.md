<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Finbud</title>
        <style>
         *{
            margin: 0;
            padding: 0;
            box-sizing: border-box;
         }
            h1 { 
            font-size: 36px; 
            color: #fcfcfc; 
            font-family: 'Arial', sans-serif;
            margin-left:200px;
        }
        p{
         font-size: 3rem;
         color: white;
         margin-left: 15rem;

        }
        
         p1 {
             font-size: 4rem; 
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
             margin-top:0.5rem;
         }
         p3 {
             font-size: 70px; 
             color:black; 
             font-family: 'Times New Roman', serif;
             margin-left:200px;
             
         }
         p4 {
            font-size:5rem;
            color:rgb(242, 212, 15);
            margin-left:30%;
            margin-top:4rem;


         }
         .home-button
         {
            background-color:black;
            color:white;
            height:32px;
            width:8rem;
            border-radius:32px;
            border-color:white;
            border-width:3px ;
            margin-left:50rem;
            border:none;
            cursor:pointer;
        
         }
        .aboutus-button
        {
            background-color:black;
            color:white;
            height:32px;
            width:8rem;
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
            width:8rem;
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
            width:8rem;
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
            width:8rem;
            border-radius:32px;
            border-color:white;
            border-width:3px ;
            margin-left:12px;
            border:none;
            cursor:pointer;
            
         }
         .multi-bg
         {
            background: linear-gradient(to right,#5d8ff5,#161a39);
            overflow-x: hidden;
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
            animation: expand 1.5s backwards ;
         }

         @keyframes expand {
            to {
               transform: scale(1);
            }
         }
         .fixed-margin{
            display: flex;
            background-color: aliceblue;
            height: 5rem;
            align-items: center;
            gap: 10px;
            z-index: 1000;
            position: fixed;
            width: 100vw;
         }
         .main{
            display: flex;
            flex-direction: column;
            height: 50%;
         }
            
.text{
   display: flex;
   flex-direction: column;
   gap: 30px;
}
.buttons{
   display: flex;
}
.logo p{
   color: #5d8ff5;
   font-weight: bolder;
}

         </style>
         <body class="multi-bg">
            <div class="fixed-margin">
               <div class="logo">
                  <p>FinBud.</p>
               </div> 

        <div class="buttons">
         <button class="home-button">HOME</button>
         <button class="aboutus-button">ABOUT US</button>
         <button class="help-button">HELP</button>
         <button class="login-button">
          <a href ="FBlogin.html">LOG IN</a>
         </button>
         <button class="signup-button">SIGN UP</button>
 
        </div>
        </div>

      <div class="text">
         <br> <br> <br>
         <p1 class="fade-in">The only place </p1>
         <p2 class="fade-in"><b>that gets your </b><br></p2>
         <p3 class="fade-in"><b>money into shape</b></p3><br> 
         <p4 class="slide-in"> Managing expenses just <br> got easier with FinBud! </p4>

      </div>
</body>
<script src= "project1.js" ></script>
</head>
</html>
