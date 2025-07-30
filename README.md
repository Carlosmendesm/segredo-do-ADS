<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Segredos do Google Ads - Curso Online</title>
  <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Rubik:wght@400&family=Lato:wght@400;700&family=Open+Sans:wght@300;400;600;700&family=Roboto:wght@300;400;600;700&display=swap">
  <script src="https://www.google.com/recaptcha/api.js" async defer></script>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Lato', sans-serif;
      color: #333;
      line-height: 1.6;
      background-color: #f9f9f9;
    }

    header {
      background: linear-gradient(135deg, #1e3a8a, #3b82f6);
      color: white;
      text-align: center;
      padding: 4rem 2rem;
    }

    header h1 {
      font-family: 'Roboto', sans-serif;
      font-size: 2.5rem;
      font-weight: 700;
      margin-bottom: 1rem;
    }

    header p {
      font-family: 'Open Sans', sans-serif;
      font-size: 1.2rem;
      max-width: 600px;
      margin: 0 auto;
    }

    .container {
      max-width: 1200px;
      margin: 0 auto;
      padding: 2rem;
    }

    .section-title {
      font-family: 'Roboto', sans-serif;
      font-size: 2rem;
      font-weight: 600;
      color: #1e3a8a;
      text-align: center;
      margin-bottom: 2rem;
    }

    .benefits, .instructor, .cta {
      margin-bottom: 3rem;
    }

    .benefits-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
      text-align: center;
    }

    .benefit-card {
      background: white;
      padding: 2rem;
      border-radius: 8px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      transition: transform 0.3s;
    }

    .benefit-card:hover {
      transform: translateY(-5px);
    }

    .benefit-card h3 {
      font-family: 'Lato', sans-serif;
      font-size: 1.5rem;
      color: #1e3a8a;
      margin-bottom: 1rem;
    }

    .instructor {
      background: #fff;
      padding: 2rem;
      border-radius: 8px;
      text-align: center;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    }

    .instructor img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      margin-bottom: 1rem;
    }

    .cta-buttons {
      display: flex;
      justify-content: center;
      gap: 1.5rem;
      flex-wrap: wrap;
    }

    .cta-button {
      background: #22c55e;
      color: white;
      padding: 1rem 2rem;
      font-family: 'Roboto', sans-serif;
      font-size: 1.1rem;
      font-weight: 600;
      text-decoration: none;
      border-radius: 5px;
      transition: background 0.3s;
    }

    .cta-button:hover {
      background: #16a34a;
    }

    .security-notice {
      text-align: center;
      font-size: 0.9rem;
      color: #666;
      margin-top: 1rem;
    }

    footer {
      background: #1e3a8a;
      color: white;
      text-align: center;
      padding: 1rem;
      font-family: 'Open Sans', sans-serif;
      font-size: 0.9rem;
    }

    footer a {
      color: #93c5fd;
      text-decoration: none;
    }

    footer a:hover {
      text-decoration: underline;
    }

    @media (max-width: 768px) {
      header h1 {
        font-size: 2rem;
      }

      header p {
        font-size: 1rem;
      }

      .section-title {
        font-size: 1.5rem;
      }

      .cta-button {
        padding: 0.8rem 1.5rem;
        font-size: 1rem;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Segredos do Google Ads</h1>
    <p>Domine o Google Ads e transforme seus resultados com estratégias comprovadas e técnicas avançadas!</p>
  </header>

  <div class="container">
    <section class="benefits">
      <h2 class="section-title">Por que escolher nosso curso?</h2>
      <div class="benefits-grid">
        <div class="benefit-card">
          <h3>Conteúdo de Alta Qualidade</h3>
          <p>Aprenda com materiais atualizados e estratégias testadas por especialistas no mercado.</p>
        </div>
        <div class="benefit-card">
          <h3>Suporte Exclusivo</h3>
          <p>Tire suas dúvidas com nossa equipe dedicada e receba orientação personalizada.</p>
        </div>
        <div class="benefit-card">
          <h3>Resultados Comprovados</h3>
          <p>Aplique técnicas que já geraram milhões em campanhas de Google Ads para nossos alunos.</p>
        </div>
      </div>
    </section>

    <section class="instructor">
      <h2 class="section-title">Sobre a Instrutora</h2>
      <img src="https://via.placeholder.com/150" alt="Rosana Miranda">
      <h3>Rosana Miranda</h3>
      <p>Especialista em Google Ads com mais de 10 anos de experiência, Rosana já ajudou milhares de alunos a alcançarem resultados incríveis em suas campanhas publicitárias.</p>
    </section>

    <section class="cta">
      <h2 class="section-title">Comece Agora Mesmo!</h2>
      <div class="cta-buttons">
        <a href="https://pay.kiwify.com.br/FIv8MLL" class="cta-button">Comprar via Kiwify</a>
        <a href="https://pay.cakto.com.br/36f5poo_298089" class="cta-button">Comprar via Cakto</a>
      </div>
      <p class="security-notice">Seus dados de pagamento estão protegidos com criptografia de nível bancário. <br>
      Este site é protegido pelo Google reCAPTCHA. <a href="#">Política de Privacidade</a> e <a href="#">Termos de Serviço</a>.</p>
    </section>
  </div>

  <footer>
    <p>&copy; 2025 Segredos do Google Ads. Todos os direitos reservados. <br>
    Ao clicar em "Comprar", você declara que leu e concorda com os <a href="#">Termos de Compra</a>, <a href="#">Termos de Uso</a> e <a href="#">Política de Privacidade</a>.</p>
  </footer>
</body>
</html>
