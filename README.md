Aqui está o código refinado, com foco absoluto em energia solar. Removi qualquer distração e foquei nos benefícios específicos da tecnologia fotovoltaica, mantendo o tema Verde e Prata Ice.

HTML
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="HC Solar - Especialista em sistemas fotovoltaicos. Reduza sua conta de luz em até 95% com tecnologia de ponta.">
    <title>HC Solar | Especialista em Energia Fotovoltaica</title>
    
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    
    <style>
        /* TEMA: VERDE (#2D5A27) e PRATA ICE (#E2E8F0) */
        :root {
            --verde-logo: #2D5A27;
            --verde-claro: #3e7a36;
            --prata-ice: #E2E8F0;
            --prata-metal: #CBD5E1;
            --chumbo-texto: #1e293b;
            --branco: #ffffff;
        }

        body {
            font-family: 'Segoe UI', Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: var(--branco);
            color: var(--chumbo-texto);
            line-height: 1.6;
        }

        /* HEADER & HERO */
        header {
            background: linear-gradient(135deg, #f8fafc 0%, var(--prata-ice) 50%, var(--prata-metal) 100%);
            color: var(--chumbo-texto);
            text-align: center;
            padding: 80px 20px;
            border-bottom: 5px solid var(--verde-logo);
            box-shadow: inset 0 0 100px rgba(255,255,255,0.5);
        }

        .logo-container img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 3px solid var(--verde-logo);
            box-shadow: 0 0 25px rgba(45, 90, 39, 0.2);
            margin-bottom: 25px;
            background: #fff;
        }

        header h1 {
            margin: 0;
            font-size: 3.5em;
            color: var(--verde-logo);
            text-transform: uppercase;
            letter-spacing: 2px;
            font-weight: 800;
        }

        header p {
            margin: 15px 0 30px;
            font-size: 1.4em;
            color: var(--chumbo-texto);
            font-weight: 500;
            max-width: 800px;
            margin-left: auto;
            margin-right: auto;
        }

        .cta-button {
            display: inline-block;
            background: var(--verde-logo);
            color: white;
            padding: 18px 40px;
            text-decoration: none;
            font-weight: bold;
            border-radius: 50px;
            transition: 0.3s;
            text-transform: uppercase;
            box-shadow: 0 4px 15px rgba(45, 90, 39, 0.3);
            font-size: 1.1em;
        }

        .cta-button:hover {
            background: var(--verde-claro);
            transform: scale(1.05);
            box-shadow: 0 6px 20px rgba(45, 90, 39, 0.4);
        }

        /* SEÇÕES */
        section {
            padding: 80px 20px;
            max-width: 1100px;
            margin: 0 auto;
            text-align: center;
        }

        h2 {
            color: var(--verde-logo);
            font-size: 2.5em;
            margin-bottom: 50px;
            position: relative;
        }

        h2::after {
            content: '';
            width: 80px;
            height: 4px;
            background: var(--prata-metal);
            display: block;
            margin: 15px auto;
        }

        /* CARDS DE FOCO SOLAR */
        .services {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 30px;
        }

        .card {
            background: white;
            border-radius: 20px;
            padding: 45px 35px;
            box-shadow: 0px 10px 30px rgba(0,0,0,0.05);
            transition: 0.3s;
            border: 1px solid var(--prata-ice);
            border-bottom: 6px solid var(--verde-logo);
        }

        .card:hover {
            transform: translateY(-10px);
            border-color: var(--verde-logo);
        }

        .card i {
            font-size: 55px;
            color: var(--verde-logo);
            margin-bottom: 25px;
        }

        .card h3 {
            color: var(--verde-logo);
            margin-bottom: 15px;
            font-size: 1.6em;
        }

        /* SEÇÃO DIFERENCIAL TECNOLÓGICO */
        .diferencial {
            background: linear-gradient(to right, #f1f5f9, var(--prata-ice));
            width: 100%;
            max-width: none;
            border-top: 1px solid var(--prata-metal);
            border-bottom: 1px solid var(--prata-metal);
            padding: 100px 20px;
        }

        .highlight-box {
            max-width: 900px;
            margin: 0 auto;
            font-size: 1.2em;
        }

        /* WHATSAPP */
        .whatsapp-float {
            position: fixed;
            width: 70px;
            height: 70px;
            bottom: 40px;
            right: 40px;
            background-color: #25d366;
            color: #FFF;
            border-radius: 50px;
            text-align: center;
            font-size: 40px;
            box-shadow: 2px 5px 20px rgba(0,0,0,0.2);
            z-index: 100;
            display: flex;
            align-items: center;
            justify-content: center;
            transition: 0.3s;
            text-decoration: none;
        }

        .whatsapp-float:hover {
            transform: scale(1.1) rotate(5deg);
        }

        /* FOOTER */
        footer {
            background: var(--chumbo-texto);
            color: var(--prata-ice);
            text-align: center;
            padding: 60px 20px;
        }

        footer strong { color: var(--verde-logo); }

        @media (max-width: 768px) {
            header h1 { font-size: 2.5em; }
            header p { font-size: 1.1em; }
            .whatsapp-float { width: 60px; height: 60px; bottom: 20px; right: 20px; font-size: 30px; }
        }
    </style>
</head>
<body>

    <header>
        <div class="logo-container">
            <img src="https://via.placeholder.com/150/FFFFFF/2D5A27?text=HC+SOLAR" alt="HC Solar Logo">
        </div>
        <h1>HC Solar</h1>
        <p>Transforme a luz do sol em economia real. Instale seu sistema fotovoltaico com quem entende de tecnologia e eficiência.</p>
        <a href="https://wa.me/5544920003969" class="cta-button">Gerar minha própria energia</a>
    </header>

    <section id="solucoes-solares">
        <h2>Especialista em Energia Fotovoltaica</h2>
        <div class="services">
            <div class="card">
                <i class="fas fa-solar-panel"></i>
                <h3>Sistemas Geradores</h3>
                <p>Projetos completos de engenharia para residências e empresas, garantindo o máximo de captação solar.</p>
            </div>
            <div class="card">
                <i class="fas fa-chart-line"></i>
                <h3>Redução de Custos</h3>
                <p>Economize até 95% na sua fatura mensal. O sol trabalha para você e seu dinheiro rende mais.</p>
            </div>
            <div class="card">
                <i class="fas fa-sun"></i>
                <h3>Limpeza e Performance</h3>
                <p>Manutenção especializada em painéis para garantir que sua geração nunca caia.</p>
            </div>
            <div class="card">
                <i class="fas fa-file-signature"></i>
                <h3>Homologação Solar</h3>
                <p>Toda a burocracia técnica com a concessionária de energia resolvida por nossa equipe.</p>
            </div>
        </div>
    </section>

    <div class="diferencial">
        <section class="highlight-box">
            <h2>Tecnologia Fotovoltaica de Ponta</h2>
            <p>A <strong>HC Solar</strong> utiliza exclusivamente componentes de alta performance. Nossos projetos unem o design <strong>Prata Ice</strong> com a sustentabilidade <strong>Verde</strong>, utilizando painéis de alta eficiência (OSDA) e inversores líderes de mercado (Growatt).</p>
        </section>
    </div>

    <footer>
        <p><strong>HC Solar</strong> - Referência em Energia Solar</p>
        <p>📞 (44) 92000-3969</p>
        <p>Atendimento especializado em toda a região.</p>
        <p>© 2026 Todos os direitos reservados.</p>
    </footer>

    <a href="https://wa.me/5544920003969" class="whatsapp-float" target="_blank">
        <i class="fab fa-whatsapp"></i>
    </a>

</body>
</html>

    
