# CSS
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<link rel="stylesheet" href="style.css">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Aula CSS</title>
</head>
<body>
    <img src="https://i1.sndcdn.com/artworks-817H6rKyPKYPAmCw-0XjOeg-t240x240.jpg" alt="Leno Brega" srcset="" class="leno">
    <h1>Aula CSS</h1>
    <div class="section">
        <p>CSS (Cascading Style Sheets) é a tecnologia responsável pela estilização das páginas web. Ele define como os elementos HTML devem ser exibidos na tela, proporcionando controle sobre cores, fontes, espaçamentos e layouts.</p>

    <table>
        <thead>
            <tr>
                <th>ID</th>
                <th>Número</th>
                <th>Email</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Ronald</td>
                <td>400</td>
                <td>ronald@gmail.com</td>
            </tr>
             <tr>
                <td>Ronaldinho</td>
                <td>480</td>
                <td>ronaldinho@gmail.com</td>
            </tr>
             <tr>
                <td>Ronaldo</td>
                <td>8000</td>
                <td>ronaldaw8@gmail.com</td>
            </tr>
        </tbody>
    </table>
    <form action="">
        <label for="nome">Nome:</label>
        <input type="text" name="nome" id="nome" required>
        <label for="email">Email:</label>
        <input type="email" name="email" id="email" required>
        <input type="submit" value="Enviar">
    </form>
     </div>
</body>
</html>
*{}
body{font-family: fantasy; background:linear-gradient(135deg, rgb(173, 204, 230), rgb(150, 139, 116));
color: rgb(51, 8, 119); 
padding: 20px;}
h1{ font-size: 2,5 rem;
    margin-bottom: 20px;
    text-align: center;
    text-transform: uppercase;
    color: rgb(50, 2, 161);
    font-weight: bold;
}
.leno{
    width: 150px;
    height: 30%;
    border-radius: 50% ;
    margin: 0 auto;
    display:block;
   
}
.section{background-color:rgba(235, 216, 192, 0.74);  
border-radius:10px;
box-shadow:20px, black;
margin-bottom: 40px;
}
.section p{
    font-size: 1;
    margin-bottom: 20px;
    line-height: 1.6;
    margin-bottom: 15px;
    color:rgb(83, 5, 83);
    text-align: center;
    font-style: italic;

}
table{
    width: 100%;
    border-collapse: collapse;
    margin-top: 20px;
    margin-bottom: 20px;
}
th,td {
    padding: 12px;
    text-align: center;
 border: 1px solid #f5f5f5;
}
th{background-color: rgb(133, 174, 214)}
tr:nth-child(odd){background-color:rgba(219, 87, 87, 0.767)}
tr:nth-child(even){background-color: rgb(133, 174, 214);}
form{ margin-top:20px ;
    margin-bottom: 20px;
   padding: 30px;
   border-radius: 10px;
   width:100%;
   max-width: 500px;
   margin:0 auto;
   box-shadow: 0 1px 1px wheat;
}
label{
    font-size: 1rem; 
    margin-bottom: 5px;
    display: block;
}
input[type="text"],input[type="email"],input[type="submit"]{width:100%;
padding: 12px;
margin-bottom: 15px;
border-radius: 5px;
border: 1px solid #f5f5f5;}
input[type="submit"]{background-color:deepskyblue; cursor: pointer ;
    color:rgb(83, 5, 83) ;
    font-weight: bold;
}
input[type="submit"]:hover{background-color: rgb(173, 173, 173);}
