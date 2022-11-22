<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Peso Ideal</title>
    <style>/* estilo interno pois e simples */
    
     body{
            background-color: rgb(127, 101, 189);
        }
    main{
        background-color: white;
        min-width: 300px;
        max-width: 800px;
        padding: 30px;
        margin: 50px auto;
        border-radius: 10px;
        text-align: center;
        box-shadow: 2px 3px 10px black;
        
    }
    main > h1 {
        font-weight: bolder;
        font-style: italic;
        text-shadow: 1px 1px 4px black;
        padding-bottom: 22px;
        

    }
    
    footer{
        background-color: black;
        text-align: center;
        color: white;
        font-weight: bolder;
        padding: 2px;

    }
    
    </style> 
</head>
<body>
    
    <main>

         <h1>Peso Ideal</h1>
        <p>
            Peso:<input type="number" name="txtpeso" id="txtpeso">
            Altura:<input type="number" name="txtaltura" id="txtaltura">
            Sexo: 
            Masculino<input type="radio" name="radsexo" id="masculino" checked >
            Feminino<input type="radio" name="radsexo" id="feminino">
            <input type="button" value="Verificar" onclick="verificar()">
        </p>
        <p>Dados por parametros da OMS</p>
        <div id="resultadopeso">

        </div>
    </main>
    <footer>
        <p>Desenvolvido por Kauai Staingel.</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
