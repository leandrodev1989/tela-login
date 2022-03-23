# Projeto Tela De Login
Criação de Uma tela de Login Criada Com html - CSS

![telalogin](https://user-images.githubusercontent.com/83560879/159604857-676d36b0-5fea-4d25-b5db-c2f77fd27495.png)




# Codigo CSS - HTML


<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Tela de login</title>
	<style type="text/css">

    body{
       font-family: Arial, Helvetica, sans-serif;
        background-image: linear-gradient(to right, rgba(255,0,0,0), rgba(255,0,0,1));
    }

    .tela-login{
      background-color: rgb(0, 0, 0, 0.8);
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      padding: 80px;
      border-radius: 15px;
      color: white;
    }

    input{
      padding: 15px;
      border-radius: none;
      outline: none;
      font-size: 15px;
    }

    button{
     background-color: dodgerblue;
     border: none;
     padding: 15px;
     width: 100%;
     border-radius: 10px;
     color: white;
     font-size: 15px;
    }

    button:hover{
     background-color: deepskyblue;
     cursor: pointer;
    }

	</style>
</head>

<body>

	<div class="tela-login">
     <h1>Login</h1>

     <input type="text" placeholder="Nome">
     <br><br>
      
      <input type="password" placeholder="Senha">
      <br><br>

      <button>Enviar</button>
	</div>

</body>
</html>

