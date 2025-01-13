```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" /> 
    <title>Document</title>
    <link rel="stylesheet" href="estilo.css" />
  </head>
  <body>
    <header>
      <h1>Cadastro de pessoas</h1>
    </header>

    <form>
      <div class="form-container">
        <div class="form-group">
          <label for="nome-text"> Nome completo:</label>
          <input
            type="text"
            id="nome-text"
            name="nome-text"
            placeholder=" Nome"
          />
        </div>
<br>
        <div class="form-group">
          <label for="number-input">Qual é a sua idade:</label>
          <input
            type="number"
            id="number-input"
            name="number-input"
            placeholder="idade"
            min="0"
            max="100"
            step="1"
          />
        </div>
<br>
        <div class="form-group">
          <label for="cpfinput"> CPF:</label>
          <input
            type="text"
            id="cpfinput"
            name="cpf"
            placeholder="000.000.000.00"
            inputmode="numeric"
          />
        </div>
<br>
        <div class="form-group">
           <label for="email-input"> Digite o seu Email:</label>
           <input
                type="email"
                name="email-email"
                class="email"
                placeholder="Email"
           />
        </div>
<br>
        <div class="form-group">
            <p>Deseja receber informaçoes por email ?</p>
             <input type="checkbox" id="checkbox" name="checkbox" value="sim" />
             <button> Enviar</button>
        </div>

      </div>
    </form>
     </body>
</html>


CSS



 body {
      font-family: Arial, sans-serif;
      margin: 20px;
      background-color: #f4f4f4;
      text-align: center;
    }
    header {
      background-color: #333;
      color: #fff;
      padding: 10px 0;
    }
    .form-container {
      margin-top: 20px;
      background-color: white;
      padding: 20px;
      max-width: 400px;
      margin: auto;
      border-radius: 5px;
    }

    .form-group {
        text-align: left;
    }
    .form-group input{
        width: 98%;
        padding: 8px;
        border: 1px solid #ccc;
        border-radius: 4px;

    }
    .form-group button {
      padding: 8px 16px;
      background-color: #4CAF50;
      color: white;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }
    .form-group button:hover {
      background-color: #45a049;
    }

