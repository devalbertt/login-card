<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <title>Formulário de Login</title>
    <style>
      /* Estilos CSS para o formulário de login */
      body {
        background-color: #f1f1f1;
        font-family: Arial, sans-serif;
      }
      form {
        background-color: #fff;
        border: 1px solid #ccc;
        border-radius: 5px;
        box-shadow: 0 2px 5px rgba(0,0,0,0.3);
        margin: 50px auto;
        max-width: 400px;
        padding: 20px;
      }
      input[type="text"],
      input[type="password"] {
        border: 1px solid #ccc;
        border-radius: 3px;
        font-size: 16px;
        padding: 10px;
        width: 100%;
      }
      input[type="submit"] {
        background-color: #4CAF50;
        border: none;
        border-radius: 3px;
        color: #fff;
        cursor: pointer;
        font-size: 16px;
        padding: 10px;
        width: 100%;
      }
      input[type="submit"]:hover {
        background-color: #3e8e41;
      }
    </style>
  </head>
  <body>
    <form action="login.php" method="post">
      <h2>Login</h2>
      <label for="username">Nome de Usuário:</label>
      <input type="text" id="username" name="username" required>
      <br>
      <label for="password">Senha:</label>
      <input type="password" id="password" name="password" required>
      <br>
      <input type="submit" value="Entrar">
    </form>
  </body>
</html>



Tela de login com um card interativo
