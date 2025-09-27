<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>HC Automação Elétrica Residencial</title>
  <style>
    /* ------------------------------------------------------------------- */
    /* CORES: DOURADO (#C5B358) e CHUMBO (#36454F) */
    /* ------------------------------------------------------------------- */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #fcfcfc;
      color: #333;
    }
    header {
      background: #36454F;
      color: white;
      text-align: center;
      padding: 40px 20px 20px;
    }
    .logo-container {
      margin-bottom: 20px;
    }
    .logo-container img {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      border: 3px solid #C5B358;
      box-shadow: 0 0 15px rgba(197, 179, 88, 0.5);
    }
    header h1 {
      margin: 0;
      font-size: 2.5em;
      color: #C5B358;
    }
    header p {
      margin: 10px 0 0;
      font-size: 1.2em;
      color: #f0f0f0;
    }
    section {
      padding: 40px 20px;
      text-align: center;
    }
    h2 {
      color: #36454F;
      margin-bottom: 20px;
    }
    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      margin-top: 30px;
    }
    .card {
      background: white;
      border-radius: 12px;
      padding: 20px;
      box-shadow: 0px 4px 10px rgba(0,0,0,0.08);
      transition: 0.3s;
      border-top: 5px solid #C5B358;
    }
    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0px 8px 20px rgba(0,0,0,0.15);
    }
    .card img {
      width: 60px;
      margin-bottom: 15px;
      /* Simulação da cor DOURADA nos ícones */
      filter: invert(70%) sepia(30%) saturate(600%) hue-rotate(15deg) brightness(80%) contrast(100%);
    }
    .card h3 {
      color: #36454F;
    }
    footer {
      background: #36454F;
      color: #f0f0f0;
      text-align: center;
      padding: 15px;
      font-size: 0.9em;
    }
    footer p strong {
      color: #C5B358;
    }
    a {
      color: #C5B358;
      text-decoration: none;
    }

    /* ------------------------------------------------------------------- */
    /* ESTILO BOTÃO WHATSAPP FLUTUANTE */
    /* ------------------------------------------------------------------- */
    .whatsapp-float {
      position: fixed;
      width: 60px;
      height: 60px;
      bottom: 40px;
      right: 40px;
      background-color: #25d366; /* Verde WhatsApp */
      color: #FFF;
      border-radius: 50px;
      text-align: center;
      font-size: 30px;
      box-shadow: 2px 2px 3px #999;
      z-index: 100;
      display: flex;
      align-items: center;
      justify-content: center;
      transition: transform 0.3s;
    }

    .whatsapp-float:hover {
      transform: scale(1.1);
    }

    /* Ícone do WhatsApp (usando uma imagem SVG externa para simplicidade) */
    .whatsapp-float img {
        width: 35px;
        height: 35px;
        filter: invert(1); /* Deixa o ícone branco */
    }

    @media (max-width: 768px) {
        .whatsapp-float {
            width: 50px;
            height: 50px;
            bottom: 20px;
            right: 20px;
        }
        .whatsapp-float img {
            width: 30px;
            height: 30px;
        }
    }
  </style>
</head>
<body>
  <header>
    <div class="logo-container">
      <img src="URL_DA_SUA_LOGO_AQUI.png" alt="Logo HC">
    </div>

    <h1>HC Automação Elétrica Residencial</h1>
    <p>Soluções modernas em automação, elétrica e energia solar</p>
    <p><strong>📞 (44) 92000-3969</strong></p>
  </header>

  <section>
    <h2>Nossos Serviços</h2>
    <div class="services">
      <div class="card">
        <img src="https://img.icons8.com/ios-filled/100/C5B358/idea.png" alt="Automação">
        <h3>Automação Residencial</h3>
        <p>Controle sua casa com tecnologia inteligente e moderna.</p>
      </div>
      <div class="card">
        <img src="https://img.icons8.com/ios-filled/100/C5B358/electrical.png" alt="Elétrica">
        <h3>Instalações Elétricas</h3>
        <p>Segurança e eficiência em projetos elétricos residenciais.</p>
      </div>
      <div class="card">
        <img src="https://img.icons8.com/ios-filled/100/C5B358/solar-panel.png" alt="Energia Solar">
        <h3>Energia Solar</h3>
        <p>Economize até 95% na conta de luz com sistemas fotovoltaicos.</p>
      </div>
      <div class="card">
        <img src="https://img.icons8.com/ios-filled/100/C5B358/maintenance.png" alt="Manutenção">
        <h3>Manutenção</h3>
        <p>Serviços rápidos e seguros para garantir seu conforto.</p>
      </div>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 HC Automação Elétrica Residencial - Todos os direitos reservados</p>
    <p>📞 <strong>(44) 92000-3969</strong></p>
  </footer>

  <a href="https://wa.me/SEU_NUMERO_WHATSAPP?text=Ol%C3%A1%2C%20gostaria%20de%20um%20or%C3%A7amento%20de%20automa%C3%A7%C3%A3o%20e%20el%C3%A9trica." class="whatsapp-float" target="_blank">
    <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" alt="WhatsApp">
  </a>
</body>
</html>
