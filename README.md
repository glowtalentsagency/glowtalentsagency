<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Glow Talents - Agência de Live Streamers</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background-color: #ffcc00;
            color: #333;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: white;
            padding: 15px 20px;
            text-decoration: none;
            text-transform: uppercase;
        }
        nav a:hover {
            background-color: #ffcc00;
            color: #333;
        }
        section {
            padding: 20px;
            max-width: 1000px;
            margin: auto;
        }
        .team-photo {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            margin-right: 10px;
        }
        .team-member {
            display: flex;
            align-items: center;
            margin-bottom: 20px;
        }
        .portfolio-item {
            margin-bottom: 20px;
        }
        .testimonials, .blog {
            background-color: #f9f9f9;
            padding: 20px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 5px 0;
        }
        .contact-form button {
            background-color: #ffcc00;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
        }
    </style>
</head>
<body>

<header>
    <h1>Glow Talents</h1>
    <p>Agência de Live Streamers</p>
</header>

<nav>
    <a href="#sobre-nos">Sobre Nós</a>
    <a href="#nossa-equipe">Nossa Equipe</a>
    <a href="#servicos">Serviços</a>
    <a href="#portfolio">Portfólio</a>
    <a href="#testemunhos">Testemunhos</a>
    <a href="#blog">Blog</a>
    <a href="#contato">Contato</a>
</nav>

<section id="sobre-nos">
    <h2>Sobre Nós</h2>
    <p>A Glow Talents é uma agência dedicada ao gerenciamento e promoção de talentos em plataformas de live streaming como TikTok e Bigo Live. Nossa missão é ajudar influenciadores, cantores e dubladores a alcançarem seu potencial máximo, conectando-os com oportunidades incríveis.</p>
</section>

<section id="nossa-equipe">
    <h2>Nossa Equipe</h2>
    <div class="team-member">
        <img src="team1.jpg" alt="Nome do Membro" class="team-photo">
        <div>
            <h3>Nome do Membro</h3>
            <p>Descrição do membro da equipe.</p>
        </div>
    </div>
    <div class="team-member">
        <img src="team2.jpg" alt="Nome do Membro" class="team-photo">
        <div>
            <h3>Nome do Membro</h3>
            <p>Descrição do membro da equipe.</p>
        </div>
    </div>
</section>

<section id="servicos">
    <h2>Serviços</h2>
    <ul>
        <li>Gerenciamento de Talentos</li>
        <li>Promoção de Live Streamers</li>
        <li>Parcerias e Colaborações</li>
        <li>Consultoria de Marketing</li>
    </ul>
</section>

<section id="portfolio">
    <h2>Portfólio</h2>
    <div class="portfolio-item">
        <h3>Influenciador 1</h3>
        <p>Descrição e link para o perfil.</p>
    </div>
    <div class="portfolio-item">
        <h3>Cantor 1</h3>
        <p>Descrição e link para o perfil.</p>
    </div>
</section>

<section id="testemunhos">
    <h2>Testemunhos</h2>
    <p>"A Glow Talents me ajudou a transformar minha paixão em profissão!" - Cliente Satisfeito</p>
    <p>"Excelente suporte e ótimas oportunidades!" - Outro Cliente Satisfeito</p>
</section>

<section id="blog">
    <h2>Blog</h2>
    <article>
        <h3>Notícia 1</h3>
        <p>Atualização sobre eventos e novas parcerias.</p>
    </article>
    <article>
        <h3>Notícia 2</h3>
        <p>Conquistas recentes e novos talentos.</p>
    </article>
</section>

<section id="contato">
    <h2>Contato</h2>
    <form class="contact-form">
        <input type="text" name="nome" placeholder="Seu nome" required>
        <input type="email" name="email" placeholder="Seu email" required>
        <textarea name="mensagem" placeholder="Sua mensagem" required></textarea>
        <button type="submit">Enviar</button>
    </form>
    <p>Email: contato@glowtalents.com</p>
    <p>Telefone: (11) 1234-5678</p>
</section>

<footer>
    <p>&copy; 2024 Glow Talents. Todos os direitos reservados.</p>
</footer>

</body>
</html>
