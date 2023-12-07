- 👋 Hi, I’m @adminternetgroup
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
adminternetgroup/adminternetgroup is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html>
<head>
    <title>Checkout Completo</title>
    <style>
        .container {
            width: 70%;
            margin: 20px auto;
            padding: 20px;
            background-color: #f3f3f3;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        input[type="text"], input[type="email"], input[type="tel"], select, textarea {
            width: 100%;
            padding: 12px;
            margin: 8px 0;
            display: inline-block;
            border: 1px solid #ccc;
            border-radius: 4px;
            box-sizing: border-box;
        }
        input[type="submit"] {
            width: 100%;
            background-color: #4CAF50;
            color: white;
            padding: 14px 20px;
            margin: 8px 0;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        input[type="submit"]:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

<div class="container">
    <h2>Formulário de Checkout</h2>
    <form action="processa_pagamento.php" method="post">

        <label for="nome">Nome Completo:</label>
        <input type="text" id="nome" name="nome" required>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>

        <label for="endereco">Endereço de Entrega:</label>
        <input type="text" id="endereco" name="endereco" required>

        <label for="cidade">Cidade:</label>
        <input type="text" id="cidade" name="cidade" required>

        <label for="estado">Estado:</label>
        <select id="estado" name="estado" required>
            <option value="">Selecione um Estado</option>
            <!-- Adicione opções de estados aqui -->
        </select>

        <label for="cep">CEP:</label>
        <input type="text" id="cep" name="cep" required>

        <label for="telefone">Telefone:</label>
        <input type="tel" id="telefone" name="telefone" required>

        <h3>Informações de Pagamento</h3>

        <label for="nome_cartao">Nome no Cartão:</label>
        <input type="text" id="nome_cartao" name="nome_cartao" required>

        <label for="numero_cartao">Número do Cartão:</label>
        <input type="text" id="numero_cartao" name="numero_cartao" required>

        <label for="validade">Validade (MM/AA):</label>
        <input type="text" id="validade" name="validade" required>

        <label for="cvv">CVV:</label>
        <input type="text" id="cvv" name="cvv" required>

        <input type="submit" value="Concluir Pedido">

    </form>
</div>

</body>
</html>
