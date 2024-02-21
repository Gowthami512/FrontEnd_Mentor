<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- displays site properly based on user's device -->

  <link rel="icon" type="image/png" sizes="32x32" href="./images/favicon-32x32.png">
  <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@100..900&display=swap" rel="stylesheet">

  
  <title> QR code component</title>

  <!-- Feel free to remove these styles or customise in your own stylesheet 👍 -->
  <style>
    .attribution { font-size: 11px; text-align: center; }
    .attribution a { color: hsl(228, 45%, 44%); }
    body{
      background: hsl(220, 82%, 72%);
    }
    .container{
      width:270px;
      height: 430px;
      background-color: ghostwhite;
      display:flex;
      flex-wrap: wrap;
      position:relative;
      left:40%;
      top:4rem;
      justify-content: center;
      padding:10px;
      border-radius: 20px;
    }
    .logo{
      height: 200px;
    }
    .qr-code{
      width:250px;
      height:250px;
      border-radius:20px;
      margin-bottom: 0;

    }
    .description{
      padding:20px;
      height:100px;
      font-size:13px;
      text-align: center;
    }
    .description h2{
      font-family: 'Outfit','sanserif'; 
      margin-top: 1px;
    }
    p{
      font-family: 'Outfit','sanserif';
      margin-bottom: 0;
      
    }
    @media screen and (max-width:480px){
      .container{
        position:relative;
        left:10%;
        top:4rem;
      }

    }
    @media screen and (481px> width< 768px){
      .container{
        position:relative;
        left:20%;
        top:4rem;
      }
    }

  </style>
</head>
<body>
  <div class="container">
    <div class="logo">
      <img  class="qr-code" src="images/image-qr-code.png" alt="Qr code">
    </div>
    <div class="description">
      <div class="main-cont">
         <h2>Improve your front-end skills by building projects </h2>
      </div>
      <div class="sub-cont">
          <p> Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
      </div>
    </div>
  </div>

</body>
</html>
