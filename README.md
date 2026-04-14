<título>HC Solar | Prata Gelo & Verde | Instalações Reais</title> <style> /* TEMA: PRATA ICE e VERDE FOLHA */ :root { --prata-ice: #e2e8f0; --prata-dark: #cbd5e1; --verde-folha: #2d5a27; --verde-brilhante: #3e7a36; --chumbo-texto: #1e293b; --branco: #ffffff; --gelo-fundo: #f8fafc; }
    body {
        font-family: 'Segoe UI', Arial, sans-serif;
        margin: 0;
        padding: 0;
        background-color: var(--gelo-fundo);
        color: var(--chumbo-texto);
        line-height: 1.6;
    }

    /* HEADER & HERO */
    header {
        background: linear-gradient(135deg, #f8fafc 0%, var(--prata-ice) 50%, var(--prata-dark) 100%);
        color: var(--chumbo-texto);
        padding: 60px 20px;
        text-align: center;
        border-bottom: 5px solid var(--verde-folha);
    }

    
        width: 140px;
        height: 140px;
        border-radius: 50%;
        border: 3px solid var(--verde-folha);
        box-shadow: 0 0 25px rgba(45, 90, 39, 0.3);
        margin-bottom: 20px;
        background: white;
    }

    header h1 {
        margin: 0;
        font-size: 2.8em;
        color: var(--verde-folha);
        text-transform: uppercase;
    }

    header p {
        font-size: 1.2em;
        max-width: 600px;
        margin: 15px auto 30px;
        font-weight: 500;
    }

    .btn-cta {
        background-color: var(--verde-folha);
        color: white;
        padding: 18px 35px;
        text-decoration: none;
        font-weight: bold;
        border-radius: 50px;
        font-size: 1.1em;
        transition: 0.3s;
        display: inline-block;
        box-shadow: 0 4px 15px rgba(45, 90, 39, 0.3);
    }

    .btn-cta:hover {
        transform: scale(1.05);
        background-color: var(--verde-brilhante);
    }

    /* SEÇÕES GERAIS */
    section {
        padding: 70px 20px;
        max-width: 1100px;
        margin: 0 auto;
        text-align: center;
    }

    h2 {
        color: var(--verde-folha);
        font-size: 2.2em;
        margin-bottom: 10px;
    }

    .subtitle {
        color: #666;
        margin-bottom: 50px;
        font-size: 1.1em;
    }

    /* SERVIÇOS */
    .services-grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
        gap: 25px;
        margin-bottom: 50px;
    }

    .card {
        background: var(--branco);
        padding: 40px 30px;
        border-radius: 20px;
        box-shadow: 0 10px 30px rgba(0,0,0,0.05);
        border: 1px solid var(--prata-ice);
        transition: 0.3s;
    }

    .card:hover {
        transform: translateY(-5px);
        border-color: var(--verde-folha);
    }

    .card i {
        font-size: 45px;
        color: var(--verde-folha);
        margin-bottom: 20px;
    }

    /* NOVA SEÇÃO: PORTFÓLIO (GALERIA) */
    .portfolio-section {
        background-color: var(--branco);
        width: 100%;
        padding: 80px 0;
        border-top: 1px solid var(--prata-ice);
        border-bottom: 1px solid var(--prata-ice);
    }

    .portfolio-grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
        gap: 15px;
        max-width: 1200px;
        margin: 0 auto;
        padding: 0 20px;
    }

    .portfolio-item {
        overflow: hidden;
        border-radius: 10px;
        box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        position: relative;
        aspect-ratio: 4/3; /* Mantém as fotos na mesma proporção */
    }

    .portfolio-item img {
        width: 100%;
        height: 100%;
        object-fit: cover; /* Faz a foto preencher o espaço sem distorcer */
        transition: 0.5s ease;
    }

    .portfolio-item:hover img {
        transform: scale(1.1); /* Efeito de zoom no hover */
    }

    /* RODAPÉ */
    footer {
        background: var(--chumbo-texto);
        color: var(--prata-ice);
        text-align: center;
        padding: 50px 20px;
    }

    footer strong { color: var(--verde-folha); }

    /* WHATSAPP FLUTUANTE */
    .whatsapp-float {
        position: fixed;
        width: 65px;
        height: 65px;
        bottom: 40px;
        right: 40px;
        background-color: #25d366;
        color: white;
        border-radius: 50px;
        display: flex;
        align-items: center;
        justify-content: center;
        font-size: 35px;
        box-shadow: 0 5px 20px rgba(0,0,0,0.3);
        z-index: 100;
        text-decoration: none;
        transition: 0.3s;
    }

    .whatsapp-float:hover {
        transform: scale(1.1);
    }

    @media (max-width: 768px) {
        header h1 { font-size: 2.2em; }
        .portfolio-grid { grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); }
    }
</style>
<header>
    <div class="logo-container">
        <img src="https://via.placeholder.com/140/f4f4f4/2d5a27?text=HC+SOLAR" alt="HC Solar Logo">
    </div>
    <h1>HC Solar</h1>
    <p>A força da natureza <strong>Verde</strong> com a tecnologia <strong>Prata Ice</strong>.</p>
    <a href="https://wa.me/5544920003969" class="btn-cta">SOLICITAR ORÇAMENTO GRÁTIS</a>
</header>

<section id="servicos">
    <h2>Nossas Soluções</h2>
    <p class="subtitle">Economia, Sustentabilidade e Tecnologia de Ponta.</p>
    <div class="services-grid">
        <div class="card">
            <i class="fas fa-home"></i>
            <h3>Residencial</h3>
            <p>Reduza sua conta de luz  e valorize seu imóvel.</p>
        </div>
        <div class="card">
            <i class="fas fa-building"></i>
            <h3>Comercial</h3>
            <p>Sustentabilidade e redução de custos fixos para o seu negócio.</p>
        </div>
        <div class="card">
            <i class="fas fa-tools"></i>
            <h3>Manutenção</h3>
            <p>Garantia de eficiência com suporte técnico especializado.</p>
        </div>
    </div>
</section>

<div class="portfolio-section">
    <section>
        <h2>Nossas Instalações</h2>
        <p class="subtitle">Veja fotos reais de projetos entregues pela HC Solar.</p>
        
        <div class="portfolio-grid">
            <div class="portfolio-item">
                <img src="WhatsApp Image 2025-08-19 at 17.13.58.jpeg" alt="Instalação HC Solar 1">
            </div>
            <div class="portfolio-item">
                <img src="WhatsApp Image 2025-08-19 at 17.13.59 (3).jpeg" alt="Instalação HC Solar 2">
            </div>
            <div class="portfolio-item">
                <img src="WhatsApp Image 2025-08-19 at 17.13.59 (4).jpeg" alt="Instalação HC Solar 3">
            </div>
            <div class="portfolio-item">
                <img src="WhatsApp Image 2025-08-19 at 17.14.00 (1).jpeg" alt="Instalação HC Solar 4">
            </div>
            <div class="portfolio-item">
                <img src="WhatsApp Image 2025-08-19 at 17.14.00 (2).jpeg" alt="Instalação HC Solar 5">
            </div>
            <div class="portfolio-item">
                <img src="WhatsApp Image 2025-08-19 at 17.14.00 (3).jpeg" alt="Instalação HC Solar 6">
            </div>
            <div class="portfolio-item">
                <img src="WhatsApp Image 2025-08-19 at 17.14.00.jpeg" alt="Instalação HC Solar 7">
            </div>
            <div class="portfolio-item">
                <img src="WhatsApp Image 2025-08-19 at 17.14.02 (2).jpeg" alt="Instalação HC Solar 8">
            </div>
            <div class="portfolio-item">
                <img src="WhatsApp Image 2025-08-19 at 17.14.02 (4).jpeg" alt="Instalação HC Solar 9">
            </div>
             <div class="portfolio-item">
                <img src="WhatsApp Image 2025-08-19 at 17.14.04 (3).jpeg" alt="Instalação HC Solar 10">
            </div>
        </div>
    </section>
</div>

<footer>
    <p><strong>HC Solar - Energia e Tecnologia</strong></p>
    <p>📞 (44) 92000-3969</p>
    <p>© 2026 Todos os direitos reservados.</p>
</footer>

<a href="https://wa.me/5544920003969" class="whatsapp-float" target="_blank">
    <i class="fab fa-whatsapp"></i>
</a>
</body>
</html>
