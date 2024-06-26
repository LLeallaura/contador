 <!DOCTYPE html>
 <html lang="pt-br">
 <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
      * {
         margin: 0;
         box-sizing: border-box;
      }
      body {
         border: 10px solid red;
       background-color: black;
       color: white;
       display: grid;
       place-items: center;
       min-height: 100vh;}
            
   section{
      blackground: rgba (255, 255, 255, .2)
     padding: 20px;
     boder-radius: 5px 
     text-alin: center; 
   }
   
   p{
      font-size: 100px;
   }
    </style>
 </head>
 <body>
   <section>  
      
      <h1>contador</h1>
      <p id="resutado"></p>
      <button onclick="diminuir()">menos</button>
      <button onclick="aumentar()">mais</button>
   </section>
 


