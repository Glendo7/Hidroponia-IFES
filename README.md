# Hidroponia-IFES

<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hidroponia</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
            color: #333;
        }
        header {
            background-color: #4caf50;
            color: white;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 10px;
            text-decoration: none;
        }
        section {
            padding: 15px;
            max-width: 600px;
            margin: auto;
        }
        h2 {
            color: #4caf50;
        }
        .image-container {
            text-align: center;
            margin: 10px 0;
        }
        .image-container img {
            max-width: 100%;
            height: auto;
            border-radius: 5px;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            margin: 5px 0;
            padding: 8px;
        }
        .contact-form button {
            background-color: #4caf50;
            color: white;
            padding: 8px;
            border: none;
            cursor: pointer;
        }
    </style>
</head>
<body>

<header>
    <h1>Hidroponia</h1>
    <nav>
        <a href="#about">O que é</a>
        <a href="#advantages">Vantagens</a>
        <a href="#systems">Sistemas</a>
        <a href="#tips">Dicas</a>
        <a href="#contact">Contato</a>
    </nav>
</header>

<section id="about">
    <h2>O que é Hidroponia</h2>
    <p>Hidroponia é uma técnica de cultivo de plantas sem solo, onde elas crescem em uma solução rica em nutrientes. Essa prática é excelente para quem deseja cultivar alimentos de forma controlada e sustentável, especialmente em locais onde o solo é limitado ou de baixa qualidade.</p>
    <div class="image-container">
        <img src="https://i.ibb.co/56sryF5/Huerto-hidroponico11.jpg" alt="Exemplo de cultivo hidropônico">
    </div>
</section>

<section id="advantages">
    <h2>Vantagens</h2>
    <ul>
        <li>Economia de água</li>
        <li>Controle total dos nutrientes</li>
        <li>Possibilidade de cultivo em áreas urbanas</li>
        <li>Redução de pragas e doenças</li>
    </ul>
    <div class="image-container">
        <img src="https://i.ibb.co/FhZpb1L/sistema-de-hidroponia-600x600-444.webp" alt="Benefícios da hidroponia">
    </div>
</section>

<section id="systems">
    <h2>Tipos de Sistemas</h2>
    <p>A hidroponia pode ser feita de várias maneiras. Veja alguns sistemas comuns:</p>
    <ul>
        <li><strong>NFT:</strong> Um fino filme de nutrientes passa pelas raízes das plantas.</li>
        <li><strong>Sistema de Pavio:</strong> A solução nutritiva é absorvida através de um pavio.</li>
        <li><strong>Sistema de Imersão:</strong> Parte das raízes é submersa na solução nutritiva.</li>
    </ul>
    <div class="image-container">
        <img src="https://i.ibb.co/6bc070X/b2d0bd9-hydroponic-systemas-555.png" alt="Diferentes sistemas hidropônicos">
    </div>
</section>

<section id="tips">
    <h2>Dicas para Iniciantes</h2>
    <ol>
        <li>Escolha um local com boa iluminação.</li>
        <li>Prepare a solução nutritiva com cuidado.</li>
        <li>Comece com plantas de fácil cultivo, como alface e manjericão.</li>
    </ol>
    <div class="image-container">
        <img src="https://i.ibb.co/NLjZSnS/esquemahidro.jpg" alt="Dicas para iniciantes na hidroponia">
    </div>
</section>


<section id="contact">
    <h2>Contato</h2>
    <form>
        <div>
            <label for="name">Nome:</label><br>
            <input type="text" id="name" name="name">
        </div>
        
        <div>
            <label for="email">E-mail:</label><br>
            <input type="text" id="email" name="email">
        </div>
        
        <div>
            <label for="message">Mensagem:</label><br>
            <textarea id="message" name="message" rows="4"></textarea>
        </div>
        
        <div>
            <button type="submit">Enviar</button>
        </div>
    </form>
</section>



</body>
</html>
