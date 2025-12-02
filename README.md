<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>A História de Toquinho | O Poeta do Violão</title>
    <style>
        /* Estilos Gerais (CSS) */
        @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,700;1,400&family=Lato:wght@300;400;700&display=swap');

        :root {
            --cor-fundo: #fdfbf7; /* Tom de papel antigo */
            --cor-texto: #333333;
            --cor-destaque: #c5a059; /* Dourado envelhecido */
            --cor-fundo-secao: #ffffff;
        }

        body {
            font-family: 'Lato', sans-serif;
            background-color: var(--cor-fundo);
            color: var(--cor-texto);
            margin: 0;
            line-height: 1.6;
        }

        h1, h2, h3 {
            font-family: 'Playfair Display', serif;
            color: #1a1a1a;
        }

        /* Cabeçalho Hero */
        header {
            background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('https://images.unsplash.com/photo-1510915361894-db8b60106cb1?q=80&w=2070&auto=format&fit=crop');
            background-size: cover;
            background-position: center;
            height: 80vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: white;
            padding: 20px;
        }

        header h1 {
            font-size: 4rem;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
        }

        header p {
            font-size: 1.5rem;
            font-style: italic;
        }

        /* Container Principal */
        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 40px 20px;
        }

        /* Seções da Linha do Tempo */
        .timeline-section {
            background: var(--cor-fundo-secao);
            margin-bottom: 60px;
            padding: 40px;
            border-radius: 8px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.05);
            border-left: 5px solid var(--cor-destaque);
            transition: transform 0.3s ease;
        }

        .timeline-section:hover {
            transform: translateY(-5px);
        }

        .timeline-date {
            color: var(--cor-destaque);
            font-weight: bold;
            text-transform: uppercase;
            letter-spacing: 2px;
            margin-bottom: 10px;
            display: block;
        }

        .content-grid {
            display: grid;
            grid-template-columns: 1fr;
            gap: 20px;
        }

        @media(min-width: 768px) {
            .content-grid {
                grid-template-columns: 1fr 1fr; /* Texto na esquerda, midia na direita */
                align-items: center;
            }
        }

        /* Imagens */
        .img-container img {
            width: 100%;
            border-radius: 4px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.2);
        }

        .caption {
            font-size: 0.85rem;
            color: #666;
            text-align: center;
            margin-top: 5px;
            font-style: italic;
        }

        /* Vídeos Responsivos */
        .video-wrapper {
            position: relative;
            padding-bottom: 56.25%; /* 16:9 */
            height: 0;
            overflow: hidden;
            border-radius: 4px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.2);
        }

        .video-wrapper iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            border: 0;
        }

        /* Rodapé */
        footer {
            background-color: #1a1a1a;
            color: white;
            text-align: center;
            padding: 40px 20px;
            margin-top: 60px;
        }
        
        .destaque-texto {
            font-size: 1.1rem;
            border-left: 3px solid var(--cor-destaque);
            padding-left: 15px;
            margin: 20px 0;
            font-style: italic;
            color: #555;
        }

    </style>
</head>
<body>

    <header>
        <h1>Toquinho</h1>
        <p>"A vida tem sempre razão"</p>
    </header>

    <div class="container">
        
        <div style="text-align: center; margin-bottom: 60px;">
            <h2>Antonio Pecci Filho</h2>
            <p>Conheça a trajetória de um dos maiores violonistas do Brasil, do apelido de infância aos palcos do mundo.</p>
        </div>

        <section class="timeline-section">
            <span class="timeline-date">1946 – 1960</span>
            <h2>Infância e O "Toquinho" de Gente</h2>
            <div class="content-grid">
                <div>
                    <p>Nascido em São Paulo, o apelido "Toquinho" foi dado por sua mãe, que o achava pequeno demais: "meu toquinho de gente".</p>
                    <p>Aos 14 anos, sua vida mudou ao encontrar o violão. Teve aulas com o mestre <strong>Paulinho Nogueira</strong>, que lhe deu a base popular, e aprimorou a técnica clássica com Isaias Sávio.</p>
                    <p>Essa formação sólida fez dele um instrumentista virtuoso antes mesmo de ser cantor.</p>
                </div>
                <div class="img-container">
                    <img src="https://images.unsplash.com/photo-1466085526362-d277d33b8a1e?q=80&w=2070&auto=format&fit=crop" alt="Violão Clássico">
                    <p class="caption">O instrumento que virou extensão do seu corpo.</p>
                </div>
            </div>
        </section>

        <section class="timeline-section">
            <span class="timeline-date">1970 – 1980</span>
            <h2>A Era de Ouro com Vinicius de Moraes</h2>
            <div class="content-grid">
                <div>
                    <p>O encontro que definiu a MPB. Vinicius de Moraes convidou o jovem Toquinho para uma temporada na Argentina, na boate <em>La Fusa</em>.</p>
                    <div class="destaque-texto">
                        "Foram 10 anos de uma simbiose perfeita entre poeta e violonista, gerando mais de 120 canções."
                    </div>
                    <p>Juntos, criaram hinos como "Tarde em Itapuã", "Regra Três" e "O Velho e a Flor". A parceria só terminou com a morte do Poeta em 1980.</p>
                </div>
                <div class="video-wrapper">
                    <iframe src="https://www.youtube.com/embed/w1j6i02GgCg" title="Tarde em Itapuã" allowfullscreen></iframe>
                </div>
            </div>
        </section>

        <section class="timeline-section">
            <span class="timeline-date">Anos 80</span>
            <h2>Carreira Solo e o Fenômeno "Aquarela"</h2>
            <div class="content-grid">
                <div class="video-wrapper">
                    <iframe src="https://www.youtube.com/embed/h8pT9w6p-Fk" title="Aquarela Toquinho" allowfullscreen></iframe>
                </div>
                <div>
                    <p>Após a perda de Vinicius, Toquinho provou seu valor solo. Em 1983, lança <strong>"Aquarela"</strong>.</p>
                    <p>A música estourou primeiro na Itália e depois conquistou o Brasil, tornando-se sua canção mais icônica. </p>
                    <p>Nessa época, Toquinho mergulhou no universo infantil com o projeto <em>"Casa de Brinquedos"</em> e <em>"A Arca de Noé"</em>, criando músicas eternas como "O Caderno".</p>
                </div>
            </div>
        </section>

        <section class="timeline-section">
            <span class="timeline-date">Atualmente</span>
            <h2>O Legado Vivo</h2>
            <div class="content-grid">
                <div>
                    <p>Com mais de 50 anos de carreira, Toquinho continua na estrada.</p>
                    <p>Ele é um dos últimos guardiões da técnica e da batida original da Bossa Nova. Seus shows atuais são celebrações da música brasileira, frequentemente acompanhado por novas vozes femininas, mantendo viva a estrutura que consagrou com Vinicius.</p>
                </div>
                <div class="img-container">
                    <img src="https://images.unsplash.com/photo-1514320291840-2e0a9bf2a9ae?q=80&w=2070&auto=format&fit=crop" alt="Ambiente de Show">
                    <p class="caption">Toquinho segue lotando casas de show pelo mundo.</p>
                </div>
            </div>
        </section>

    </div>

    <footer>
        <p>Desenvolvido como homenagem à Música Popular Brasileira.</p>
    </footer>

</body>
</html>
