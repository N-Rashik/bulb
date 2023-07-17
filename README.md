

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        #bulb{
            height: 500px;
            width: 350px;
            margin-top: 50px;
        }
        .A
        {
            text-align:center;  
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            color: rgb(9, 255, 0);
            border: 6px dashed black;
            background:linear-gradient(rgb(107, 16, 16),rgb(11, 11, 87),black);
            border-color: rgb(37, 20, 8);
            
            width: 200px;
            margin:30px;
            margin-left: 120px;
            margin-right: 140px;
            background-clip: content-box;
           
            background:linear-gradient(rgb(rgb(255, 0, 0) 255),rgb(60, 0, 255));
        }
        .A1
        {
            height: 600px;
            width: 450px;
            border: 6px dashed black;
            margin-top: 70px;
            
        }
        .A2
        {
            margin-left: 5px;
            border: 5px solid rgb(21, 19, 128);
            
        }
        .A2:hover
        {
            background: yellowgreen;
        }
        .A3
        {
            margin-left: 5px;
            border: 5px solid rgb(21, 19, 128);
            
        }
        .A3:hover
        {
            background: yellowgreen;
        }

        
    </style>
</head>
<body>
    <h1 class="A"><b>BULB</b></h1>
<div class="A1">
      <button class="A2"  onclick="turnon()">on</button>
      <img id="bulb" src="https://tse2.mm.bing.net/th?id=OIP.buto_JEbE4tf3NwWhH5XAQHaMT&pid=Api&P=0&h=180">
      <button class="A3" onclick="turnoff()">off</button><br>
    </div>
      <script>
        function turnon(){
            document.getElementById("bulb").src="https://tse2.mm.bing.net/th?id=OIP.RZnLzFsFh7tqQF_NqQlfEQHaLG&pid=Api&P=0&h=180";
        }

        function turnoff() {
            document.getElementById("bulb").src="https://tse2.mm.bing.net/th?id=OIP.buto_JEbE4tf3NwWhH5XAQHaMT&pid=Api&P=0&h=180";
        }
      </script>

    </body>
</html>
