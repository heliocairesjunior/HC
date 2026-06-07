<style>
    /* DEFINIÇÃO DO TEMA FUTURISTA: PRATA ICE E DOURADO OURO */
    :root {
        --prata-ice: #e2e8f0; /* Fundo Metálico Claro */
        --prata-dark: #cbd5e1; /* Sombras Metálicas */
        --dourado-ouro: #ffd700; /* Brilho de Energia Dourada (Gold Neon) */
        --dourado-logo: #856404; /* Dourado Escuro/Bronze para Contraste */
        --chumbo-tech: #1e293b; /* Texto e Detalhes */
        --branco-glass: rgba(255, 255, 255, 0.5); /* Efeito Vidro */
    }

    body {
        margin: 0;
        font-family: 'Orbitron', 'Segoe UI', Roboto, sans-serif; /* Fonte Sci-Fi */
        background-color: var(--prata-ice);
        background-image: 
            radial-gradient(circle at 10% 20%, rgba(255, 215, 0, 0.05) 0%, transparent 40%),
            radial-gradient(circle at 90% 80%, rgba(255, 215, 0, 0.05) 0%, transparent 40%);
        color: var(--chumbo-tech);
        overflow-x: hidden;
    }

    /* HEADER TOTALMENTE REFORMULADO - HIGH TECH */
    header {
        background: linear-gradient(135deg, #f8fafc 0%, var(--prata-ice) 50%, var(--prata-dark) 100%);
        padding: 80px 20px;
        text-align: center;
        border-bottom: 3px solid var(--dourado-ouro);
        box-shadow: 0 0 50px rgba(255, 215, 0, 0.2);
        position: relative;
    }

    /* Efeito de linhas de circuito no fundo do header */
    header::before {
        content: "";
        position: absolute;
        top: 0; left: 0; width: 100%; height: 100%;
        background-image: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" width="100" height="100" viewBox="0 0 100 100"><g fill-rule="evenodd"><g fill="%23856404" fill-opacity="0.05"><path d="M11 18c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zm48 25c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zm-43 0c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zm-3 46c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zM55 80c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zM11 72c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zm48-61c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zM34 38c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zm16 61c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zM34 1c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zm56 57c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zm0-47c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zm0 94c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zM34 75c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zM89 86c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zM11 113c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zM34 113c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zm48-61c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zM34 38c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zm16 61c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zM34 1c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zm56 57c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zm0-47c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zm0 94c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zM34 75c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zM89 86c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7z"/></g></g></svg>');
        opacity: 0.5;
    }

    header h1 {
        font-size: 3.5em;
        margin: 0;
        color: var(--dourado-logo);
        text-transform: uppercase;
        letter-spacing: 5px;
        text-shadow: 0 0 15px rgba(255, 215, 0, 0.5);
        position: relative;
    }

    header p {
        font-size: 1.3em;
        max-width: 700px;
        margin: 20px auto;
        position: relative;
        font-weight: 500;
    }

    .contact-info {
        font-size: 1.1em;
        color: var(--dourado-logo);
        font-weight: bold;
        letter-spacing: 1px;
        margin-top: 30px;
    }

    /* SEÇÕES GERAIS */
    section {
        padding: 80px 20px;
        max-width: 1100px;
        margin: auto;
        text-align: center;
    }

    h2 {
        color: var(--dourado-logo);
        font-size: 2.5em;
        text-transform: uppercase;
        letter-spacing: 2px;
        margin-bottom: 50px;
        position: relative;
        display: inline-block;
    }

    /* Linha neon abaixo do título */
    h2::after {
        content: "";
        position: absolute;
        bottom: -15px; left: 0; width: 100%; height: 3px;
        background: var(--dourado-ouro);
        box-shadow: 0 0 15px var(--dourado-ouro);
    }

    /* GRID E CARDS FUTURISTAS - EFEITO GLASSMORPHISM */
    .benefits, .steps {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
        gap: 30px;
    }

    .card {
        background: rgba(255, 255, 255, 0.1); /* Vidro Transparente */
        backdrop-filter: blur(10px); /* Desfoque do Fundo */
        -webkit-backdrop-filter: blur(10px);
        border-radius: 20px;
        padding: 40px;
        border: 1px solid rgba(255, 255, 255, 0.2);
        box-shadow: 0 10px 30px rgba(0, 0, 0, 0.05);
        transition: 0.4s ease;
        position: relative;
        overflow: hidden;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
    }

    /* Borda neon no hover */
    .card:hover {
        transform: translateY(-10px) scale(1.02);
        border-color: var(--dourado-ouro);
        box-shadow: 0 0 30px rgba(255, 215, 0, 0.3);
    }

    /* Brilho interno no card */
    .card::before {
        content: "";
        position: absolute;
        top: -50%; left: -50%; width: 200%; height: 200%;
        background: radial-gradient(circle, rgba(255, 215, 0, 0.1) 0%, transparent 70%);
        opacity: 0;
        transition: 0.4s;
    }

    .card:hover::before {
        opacity: 1;
    }

    /* Ícones e Números nos Cards */
    .card i {
        font-size: 3em;
        color: var(--dourado-logo);
        margin-bottom: 20px;
        transition: 0.3s;
    }

    .card:hover i {
        color: var(--dourado-ouro);
        transform: rotate(-10deg);
    }

    .step-number {
        font-size: 4em;
        font-weight: 800;
        color: rgba(133, 100, 4, 0.1); /* Número超淡 */
        position: absolute;
        top: 10px; right: 20px;
        transition: 0.3s;
    }

    .card:hover .step-number {
        color: rgba(255, 215, 0, 0.2);
    }

    .card-text {
        font-size: 1.2em;
        font-weight: 600;
        position: relative;
        z-index: 1;
    }

    /* BOTÃO CTA - SUPER NEON */
    .cta {
        text-align: center;
        margin: 80px 0;
        position: relative;
    }

    .cta a {
        background-color: transparent;
        color: var(--dourado-ouro);
        padding: 20px 40px;
        border-radius: 50px;
        font-size: 1.3em;
        font-weight: bold;
        text-decoration: none;
        text-transform: uppercase;
        letter-spacing: 2px;
        border: 2px solid var(--dourado-ouro);
        box-shadow: 0 0 15px rgba(255, 215, 0, 0.5);
        transition: 0.3s;
        display: inline-block;
        position: relative;
        overflow: hidden;
    }

    /* Efeito de preenchimento no hover */
    .cta a::after {
        content: "";
        position: absolute;
        top: 0; left: -100%; width: 100%; height: 100%;
        background: var(--dourado-ouro);
        transition: 0.4s;
        z-index: -1;
    }

    .cta a:hover {
        color: var(--chumbo-tech);
        box-shadow: 0 0 40px var(--dourado-ouro);
    }

    .cta a:hover::after {
        left: 0;
    }

    /* FOOTER TECH */
    footer {
        background-color: var(--chumbo-tech);
        background-image: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" width="100" height="100" viewBox="0 0 100 100"><g fill-rule="evenodd"><g fill="%23ffd700" fill-opacity="0.03"><path d="M11 18c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zm48 25c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zm-43 0c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zm-3 46c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zM55 80c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zM11 72c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zm48-61c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zM34 38c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zm16 61c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zM34 1c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zm56 57c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zm0-47c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zm0 94c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zM34 75c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zM89 86c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zM11 113c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zM34 113c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zm48-61c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zM34 38c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zm16 61c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zM34 1c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zm56 57c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zm0-47c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zm0 94c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zM34 75c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zM89 86c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7z"/></g></g></svg>');
        color: var(--prata-ice);
        text-align: center;
        padding: 40px 20px;
        font-size: 1em;
        border-top: 1px solid rgba(255, 255, 255, 0.1);
    }

    footer p { margin: 10px 0; }
    footer strong { color: var(--dourado-ouro); }

    /* Fontes Sci-Fi do Google Fonts */
    @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700;900&display=swap');

    /* RESPONSIVIDADE FUTURISTA */
    @media (max-width: 768px) {
        header h1 { font-size: 2.2em; letter-spacing: 2px; }
        header p { font-size: 1em; }
        h2 { font-size: 1.8em; }
        .card { padding: 30px 20px; }
        .cta a { font-size: 1.1em; padding: 15px 30px; }
    }
</style>

 
