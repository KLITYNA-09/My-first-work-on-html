<htrml>
<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
   <link rel="stylesheet" href="style.css">
</head>
<body>
    <ul class="kod">
        <li class="cyfra">6</li>
        <li class="cyfra">4</li>
        <li class="cyfra">2</li>
        <li class="cyfra">0</li>
        <li class="cyfra">1</li>
        <li class="cyfra">2</li>
    </ul>
</body>
</html>

body{
    background-color: blueviolet;
    color: #00ff73;
    font-family: fantasy;
    display: grid;
    place-items: center;
    min-height: 600px;
    
}

.kod{
    list-style-type: none;
    display: flex;
    gap: 10px;
    background-color: #101296;
    padding:15px 30px ;
    border-radius: 20px;
}

.cyfra{
    font-size: 50px;
    padding: 18px;
    filter: blur(30px);
    transition: 0.09s;
}

.cyfra:hover{
    filter: blur(0px);
    cursor: pointer;
}
