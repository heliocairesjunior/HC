<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HC Solar | Economia e Tecnologia</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        /* CORES: DOURADO (#C5B358) e CHUMBO (#36454F) */
        :root {
            --dourado: #C5B358;
            --chumbo: #36454F;
            --branco: #ffffff;
            --gelo: #f4f4f4;
        }

        body {
            font-family: 'Segoe UI', Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: var(--gelo);
            color: #333;
            line-height: 1.6;
        }

        /* HEADER & HERO */
        header {
            background: var(--chumbo);
            color: white;
            padding: 60px 20px;
            text-align: center;
            border-bottom: 5px solid var(--dourado);
        }

        .logo-container img {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            border: 3px solid var(--dourado);
            box-shadow: 0 0 20px rgba(197, 179, 88, 0.4);
            margin-bottom: 20px;
        }

        header h1 {
            margin: 0;
            font-size: 2.5em;
            color: var(--dourado);
            text-transform: uppercase;
        }

        header p {
            font-size: 1.2em;
            max-width: 600px;
            margin: 15px auto 30px;
        }

        .btn-cta {
            background-color: var(--dourado);
            color: var(--chumbo);
            padding: 18px 35px;
            text-decoration: none;
            font-weight: bold;
            border-radius: 50px;
            font-size: 1.1em;
            transition: 0.3s;
            display: inline-block;
        }

        .btn-cta:hover {
            transform: scale(1.05);
            background-color: #d4c16a;
        }

        /* SERVIÇOS */
        section {
            padding: 60px 20px;
            max-width: 1100px;
            margin: 0 auto;
            text-align: center;
        }

        h2 {
            color: var(--chumbo);
            font-size: 2em;
            margin-bottom: 40px;
        }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .card {
            background: var(--branco);
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 10px 20px rgba(0,0,0,0.05);
            border-top: 5px solid var(--dourado);
            transition: 0.3s;
        }

        .card:hover {
            transform: translateY(-10px);
        }

        .card i {
            font-size: 40px;
            color: var(--dourado);
            margin-bottom: 20px;
        }

        .card h3 {
            color: var(--chumbo);
            margin-bottom: 10px;
        }

        /* RODAPÉ */
        footer {
            background: var(--chumbo);
            color: white;
            text-align: center;
            padding: 40px 20px;
            margin-top: 50px;
        }

        footer p { margin: 5px 0; }
        footer strong { color: var(--dourado); }

        /* WHATSAPP FLUTUANTE */
        .whatsapp-float {
            position: fixed;
            width: 60px;
            height: 60px;
            bottom: 40px;
            right: 40px;
            background-color: #25d366;
            color: white;
            border-radius: 50px;
            text-align: center;
            font-size: 30px;
            box-shadow: 2px 2px 10px rgba(0,0,0,0.2);
            z-index: 100;
            display: flex;
            align-items: center;
            justify-content: center;
            text-decoration: none;
            transition: 0.3s;
        }

        .whatsapp-float:hover {
            transform: scale(1.1);
        }

        @media (max-width: 768px) {
            header h1 { font-size: 2em; }
            .whatsapp-float { width: 50px; height: 50px; bottom: 20px; right: 20px; }
        }
    </style>
</head>
<body>

    <header>
        <div class="logo-container">
            <img src="https://via.placeholder.com/120/36454F/C5B358?text=HC+SOLAR" alt="HC Solar Logo">
        </div>
        <h1>HC Solar</h1>
        <p>Economize até 95% na sua conta de luz com tecnologia fotovoltaica de ponta.</p>
        <a href="https://wa.me/5544920003969" class="btn-cta">QUERO UM ORÇAMENTO GRÁTIS</a>
    </header>

    <section id="servicos">
        <h2>Nossos Serviços</h2>
        <div class="services-grid">
            <div class="card">
                <i class="fas fa-home"></i>
                <h3>Residencial</h3>
                <p>Sistemas personalizados para sua casa, garantindo conforto e economia imediata.</p>
            </div>
            <div class="card">
                <i class="fas fa-industry"></i>
                <h3>Comercial</h3>
                <p>Reduza os custos fixos da sua empresa e aumente sua competitividade no mercado.</p>
            </div>
            <div class="card">
                <i class="fas fa-tools"></i>
                <h3>Manutenção</h3>
                <p>Limpeza e assistência técnica para garantir que seu sistema opere 100%.</p>
            </div>
            <div class="card">
                <i class="fas fa-file-invoice-dollar"></i>
                <h3>Projetos</h3>
                <p>Equipe técnica qualificada para homologação e instalação completa.</p>
            </div>
        </div>
    </section>

    <section style="background-color: #eee; width: 100%; max-width: none;">
        <div style="max-width: 800px; margin: 0 auto;">
            <h2>Por que a HC Solar?</h2>
            <p>Trabalhamos com os melhores componentes do mercado, incluindo painéis de alta eficiência e inversores <strong>Growatt</strong>. Tecnologia, durabilidade e suporte para você não se preocupar com nada.</p>
        </div>
    </section>

    <footer>
        <p><strong>HC Solar - Soluções em Energia</strong></p>
        <p>📞 (44) 92000-3969</p>
        <p>© 2026 Todos os direitos reservados.</p>
    </footer>

    <a href="https://wa.me/5544920003969" class="whatsapp-float" target="_blank">
        <i class="fab fa-whatsapp"></i>
    </a>

</body>
</html>
