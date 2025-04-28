# <!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Rota Digital | Marketing Digital</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Poppins', sans-serif;
      line-height: 1.6;
      color: #333;
      background: #f9f9f9;
    }
    header {
      background: linear-gradient(90deg, #0077cc, #00aaff);
      color: #fff;
      text-align: center;
      padding: 40px 20px;
    }
    nav {
      background: #005fa3;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
    }
    nav ul {
      list-style: none;
      display: flex;
      flex-wrap: wrap;
    }
    nav ul li {
      margin: 10px;
    }
    nav ul li a {
      color: #fff;
      text-decoration: none;
      font-weight: 600;
      padding: 10px 15px;
      border-radius: 5px;
      transition: background 0.3s;
    }
    nav ul li a:hover {
      background: #004080;
    }
    section {
      padding: 60px 20px;
      max-width: 1200px;
      margin: auto;
    }
    h2 {
      color: #0077cc;
      margin-bottom: 20px;
      text-align: center;
    }
    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      margin-top: 30px;
    }
    .service {
      background: #fff;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.05);
      text-align: center;
      transition: transform 0.3s;
    }
    .service:hover {
      transform: translateY(-5px);
    }
    .service h3 {
      margin-bottom: 10px;
      color: #005fa3;
    }
    blockquote {
      background: #fff;
      border-left: 5px solid #0077cc;
      margin: 20px 0;
      padding: 20px;
      font-style: italic;
      border-radius: 5px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.05);
    }
    blockquote footer {
      margin-top: 10px;
      text-align: right;
      font-weight: bold;
    }
    form {
      background: #fff;
      padding: 30px;
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.05);
      margin-top: 30px;
    }
    form input, form textarea {
      width: 100%;
      padding: 15px;
      margin: 10px 0;
      border: 1px solid #ccc;
      border-radius: 5px;
      font-family: 'Poppins', sans-serif;
    }
    form button {
      background: #0077cc;
      color: #fff;
      border: none;
      padding: 15px 30px;
      font-size: 16px;
      cursor: pointer;
      border-radius: 5px;
      transition: background 0.3s;
    }
    form button:hover {
      background: #005fa3;
    }
    .social {
      margin: 20px 0;
      text-align: center;
    }
    .social a {
      color: #0077cc;
      font-size: 28px;
      margin: 0 15px;
      transition: color 0.3s;
    }
    .social a:hover {
      color: #005fa3;
    }
    footer {
      background: #333;
      color: #fff;
      text-align: center;
      padding: 20px;
      font-size: 14px;
      margin-top: 40px;
    }
    @media (max-width: 768px) {
      nav ul {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
</head>
<body>

<header>
  <h1>Rota Digital</h1>
  <p>Impulsione Sua Presença Online</p>
</header>

<nav>
  <ul>
    <li><a href="#inicio">Início</a></li>
    <li><a href="#servicos">Serviços</a></li>
    <li><a href="#sobre">Sobre Nós</a></li>
    <li><a href="#portfolio">Portfólio</a></li>
    <li><a href="#depoimentos">Depoimentos</a></li>
    <li><a href="#contato">Contato</a></li>
  </ul>
</nav>

<section id="inicio">
  <h2>Bem-vindo à Rota Digital</h2>
  <p style="text-align:center;">Transformamos sua presença digital em resultados reais. Seu sucesso começa aqui!</p>
</section>

<section id="servicos">
  <h2>Nossos Serviços</h2>
  <div class="services">
    <div class="service">
      <h3>Tráfego Pago</h3>
      <p>Campanhas otimizadas no Google Ads, Facebook Ads e Instagram Ads.</p>
    </div>
    <div class="service">
      <h3>Social Media</h3>
      <p>Conteúdos criativos e estratégicos para as redes sociais da sua marca.</p>
    </div>
    <div class="service">
      <h3>Criação de Sites</h3>
      <p>Sites modernos, responsivos e focados em conversão.</p>
    </div>
    <div class="service">
      <h3>Estrutura para Instagram</h3>
      <p>Perfis organizados e otimizados para atrair mais seguidores qualificados.</p>
    </div>
    <div class="service">
      <h3>Biosites</h3>
      <p>Links inteligentes que conectam todo o seu conteúdo em um só lugar.</p>
    </div>
    <div class="service">
      <h3>Catálogo Digital</h3>
      <p>Apresente seus produtos de forma profissional e interativa.</p>
    </div>
    <div class="service">
      <h3>Google Meu Negócio</h3>
      <p>Configure e otimize sua presença local para ser facilmente encontrado.</p>
    </div>
    <div class="service">
      <h3>Atendimento com IA</h3>
      <p>Automatize o atendimento ao cliente com chatbots inteligentes 24h por dia.</p>
    </div>
  </div>
</section>

<section id="sobre">
  <h2>Sobre a Rota Digital</h2>
  <p style="text-align:center;">Acreditamos no potencial único de cada marca. Com inovação, estratégia e criatividade, ajudamos nossos clientes a alcançar novos patamares no mundo digital.</p>
</section>

<section id="portfolio">
  <h2>Portfólio</h2>
  <p style="text-align:center;">Em breve, mostras de nossos projetos de sucesso!</p>
</section>

<section id="depoimentos">
  <h2>Depoimentos</h2>
  <blockquote>
    “A Rota Digital transformou totalmente minha empresa online! Atendimento excelente e resultados rápidos.”
    <footer>— Cliente Satisfeito</footer>
  </blockquote>
  <blockquote>
    “Superaram todas as expectativas! Obrigado, Rota Digital!”
    <footer>— Empreendedor Digital</footer>
  </blockquote>
</section>

<section id="contato">
  <h2>Contato</h2>
  <p style="text-align:center;">Entre em contato e vamos impulsionar seu negócio juntos!</p>
  
  <div class="social">
    <a href="https://wa.me/5573991245925" target="_blank"><i class="fab fa-whatsapp"></i></a>
    <a href="mailto:contato@rotadigital.com" target="_blank"><i class="far fa-envelope"></i></a>
    <a href="https://www.instagram.com/rotadigital" target="_blank"><i class="fab fa-instagram"></i></a>
  </div>

  <form>
    <input type="text" name="nome" placeholder="Seu Nome" required>
    <input type="email" name="email" placeholder="Seu E-mail" required>
    <textarea name="mensagem" rows="5" placeholder="Sua Mensagem" required></textarea>
    <button type="submit">Enviar Mensagem</button>
  </form>
</section>

<footer>
  <p>© 2025 Rota Digital | Todos os direitos reservados.</p>
</footer>

</body>
</html>