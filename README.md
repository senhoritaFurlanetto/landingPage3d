<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rocitros - Refrigerante Rosa</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Rocitros - Refrigerante Rosa</h1>
        <nav>
            <ul>
                <li><a href="#description">Descrição</a></li>
                <li><a href="#features">Características</a></li>
                <li><a href="#reviews">Avaliações</a></li>
                <li><a href="#pricing">Valores</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="description" class="section">
            <h2>Descrição</h2>
            <div class="product-container">
                <img src="refrigerante-rosa.jpg" alt="Refrigerante Rocitros" class="product-image">
                <p>O Rocitros é um refrigerante cor de rosa que combina um sabor refrescante com uma cor vibrante. Ideal para todas as ocasiões, seu sabor único vai conquistar você!</p>
                <button onclick="window.location.href='#pricing'">Comprar Agora</button>
            </div>
        </section>

        <section id="features" class="section">
            <h2>Características</h2>
            <ul>
                <li>Cor vibrante rosa</li>
                <li>Sabor refrescante e doce</li>
                <li>Embalagem de 500ml</li>
                <li>Sem conservantes artificiais</li>
            </ul>
            <button onclick="window.location.href='#description'">Saiba Mais</button>
        </section>

        <section id="reviews" class="section">
            <h2>Avaliações</h2>
            <article class="review">
                <h3>Maria Silva</h3>
                <p>“Amei o Rocitros! O sabor é incrível e a cor é linda. Recomendo para todos os meus amigos!”</p>
            </article>
            <article class="review">
                <h3>João Pereira</h3>
                <p>“Ótimo refrigerante! Refrescante e saboroso. Com certeza vou comprar novamente.”</p>
            </article>
        </section>

        <section id="pricing" class="section">
            <h2>Valores</h2>
            <p class="price">R$ 5,99</p>
            <button onclick="window.location.href='#description'">Comprar Agora</button>
        </section>

        <aside class="login-form">
            <h2>Faça Login para Receber Mais Informações</h2>
            <form action="submit-form.php" method="post">
                <label for="username">Usuário:</label>
                <input type="text" id="username" name="username" required>
                <label for="password">Senha:</label>
                <input type="password" id="password" name="password" required>
                <button type="submit">Entrar</button>
            </form>
        </aside>
    </main>

    <footer>
        <p>&copy; 2024 Rocitros. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
/* Reset básico */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Estilo geral do corpo */
body {
    font-family: Arial, sans-serif;
    background: linear-gradient(to right, #ff69b4, #ff1493); /* Gradiente rosa */
    color: #333;
    line-height: 1.6;
}

/* Estilo do cabeçalho */
header {
    background: #fff;
    color: #ff69b4; /* Rosa claro */
    padding: 20px;
    text-align: center;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
}

header h1 {
    margin-bottom: 10px;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 10px;
}

nav a {
    color: #ff69b4; /* Rosa claro */
    text-decoration: none;
    font-weight: bold;
}

nav a:hover {
    text-decoration: underline;
}

/* Estilo principal */
main {
    padding: 20px;
}

/* Seções */
.section {
    margin-bottom: 40px;
    background: #fff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
}

/* Estilo do produto */
.product-container {
    display: flex;
    flex-direction: column;
    align-items: center;
}

.product-image {
    max-width: 100%;
    height: auto;
    border-radius: 8px;
    margin-bottom: 20px;
}

button {
    background-color: #ff69b4; /* Rosa claro */
    border: none;
    color: white;
    padding: 10px 20px;
    font-size: 1em;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s;
    margin-top: 10px;
}

button:hover {
    background-color: #f06292; /* Rosa mais escuro */
}

/* Estilo das avaliações */
.review {
    background: #f8f9fa;
    border: 1px solid #ddd;
    border-radius: 8px;
    padding: 10px;
    margin-bottom: 20px;
}

.review h3 {
    margin-bottom: 10px;
}

/* Formulário de login */
.login-form {
    background: #fff;
    border: 1px solid #ddd;
    border-radius: 8px;
    padding: 20px;
    margin: 20px 0;
}

.login-form form {
    display: flex;
    flex-direction: column;
}

.login-form label {
    margin-bottom: 5px;
}

.login-form input {
    margin-bottom: 15px;
    padding: 10px;
    border: 1px solid #ddd;
    border-radius: 5px;
}

.login-form button {
    background-color: #ff69b4; /* Rosa claro */
    border: none;
    color: white;
    padding: 10px;
    font-size: 1em;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s;
}

.login-form button:hover {
    background-color: #f06292; /* Rosa mais escuro */
}

/* Estilo do rodapé */
footer {
    background: #fff;
    color: #ff69b4; /* Rosa claro */
    padding: 10px;
    text-align: center;
    box-shadow: 0 -4px 6px rgba(0,0,0,0.1);
}

/* Responsividade */
@media (max-width: 768px) {
    .product-container {
        fle
