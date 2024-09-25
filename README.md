<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="">
    <style>
        body{
            background-image: url("gost.jpg");
        }
        .Uni,.Ui,.un{
          border: 2px solid red;
          height: 40px;
          width: 150px;
        background-color: beige;}
        .Uni:hover{
           transform: rotate(+600000000deg);
           transition: 1000000s;}
        .Ui:hover{
            transform: scale(2);
            transition: 5s;}
        .un:hover{
            transform: skew(-30deg);}
        .d{
            animation: ds 5s ease-in 5s ;}
            @keyframes ds {
                from{transform: translatex(500px);}
                to{transform: translatey(600px);}}
    </style>
</head>
<body>
    <center>
    <h1 class="Uni">Karthik</h1><br><br><br><br><br><br>
    <h1 class="Ui">Kaushik</h1><br><br><br><br><br><br>
    <h1 class="d">Jai Prakash</h1><br><br><br><br><br><br><br><br>
    </center>
</body>
</html>
