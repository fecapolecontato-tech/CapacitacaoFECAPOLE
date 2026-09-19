<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Capacitação Profissional FECAPOLE de Pole Esporte 2026</title>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700;800;900&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary: #006837; /* Verde FECAPOLE */
            --secondary: #C8102E; /* Vermelho FECAPOLE */
            --dark: #121814;
            --light: #F4F7F5;
            --white: #FFFFFF;
            --gray: #666666;
            --accent-yellow: #FFC72C;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Montserrat', sans-serif;
        }

        body {
            background-color: var(--light);
            color: var(--dark);
            line-height: 1.6;
            overflow-x: hidden;
        }

        /* Top Bar Urgência */
        .top-bar {
            background: var(--secondary);
            color: var(--white);
            text-align: center;
            padding: 10px 15px;
            font-weight: 700;
            font-size: 0.9rem;
            text-transform: uppercase;
            letter-spacing: 0.5px;
        }

        .container {
            max-width: 1140px;
            margin: 0 auto;
            padding: 0 20px;
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(135deg, #004d28 0%, #002b16 100%);
            color: var(--white);
            padding: 60px 0 80px 0;
            text-align: center;
            position: relative;
        }

        .hero-badge {
            display: inline-block;
            background: rgba(255, 255, 255, 0.15);
            border: 1px solid rgba(255, 255, 255, 0.3);
            padding: 8px 20px;
            border-radius: 30px;
            font-size: 0.85rem;
            font-weight: 700;
            margin-bottom: 20px;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        .hero h1 {
            font-size: 2.6rem;
            font-weight: 900;
            line-height: 1.2;
            margin-bottom: 20px;
            text-transform: uppercase;
        }

        .hero h1 span {
            color: var(--accent-yellow);
        }

        .hero p.subtitle {
            font-size: 1.25rem;
            max-width: 800px;
            margin: 0 auto 30px auto;
            color: #E0E0E0;
            font-weight: 400;
        }

        .hero-info-cards {
            display: flex;
            justify-content: center;
            gap: 15px;
            flex-wrap: wrap;
            margin-bottom: 35px;
        }

        .info-card {
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(5px);
            border-left: 4px solid var(--secondary);
            padding: 12px 20px;
            border-radius: 6px;
            font-weight: 600;
            font-size: 0.95rem;
        }

        /* Botões CTA */
        .btn {
            display: inline-block;
            width: 100%;
            max-width: 450px;
            padding: 18px 25px;
            border-radius: 8px;
            font-weight: 800;
            font-size: 1.1rem;
            text-decoration: none;
            text-transform: uppercase;
            text-align: center;
            transition: all 0.3s ease;
            box-shadow: 0 4px 15px rgba(0,0,0,0.2);
            cursor: pointer;
            border: none;
        }

        .btn-green {
            background-color: #28a745;
            color: var(--white);
        }

        .btn-green:hover {
            background-color: #218838;
            transform: translateY(-3px);
            box-shadow: 0 6px 20px rgba(40, 167, 69, 0.4);
        }

        .btn-red {
            background-color: var(--secondary);
            color: var(--white);
        }

        .btn-red:hover {
            background-color: #a00d24;
            transform: translateY(-3px);
            box-shadow: 0 6px 20px rgba(200, 16, 46, 0.4);
        }

        /* Seção Reflexão / Problema */
        .intro {
            padding: 70px 0;
            background: var(--white);
        }

        .intro-box {
            max-width: 850px;
            margin: 0 auto;
            text-align: center;
        }

        .intro-box h2 {
            font-size: 2rem;
            color: var(--primary);
            margin-bottom: 25px;
            font-weight: 800;
        }

        .intro-box p {
            font-size: 1.1rem;
            color: #444;
            margin-bottom: 20px;
        }

        .highlight-text {
            background: #E8F5E9;
            border-left: 5px solid var(--primary);
            padding: 20px;
            border-radius: 6px;
            font-size: 1.15rem;
            font-weight: 600;
            color: var(--primary);
            margin-top: 30px;
            text-align: left;
        }

        /* Autoridade FECAPOLE */
        .authority {
            background: var(--light);
            padding: 70px 0;
            border-top: 1px solid #E0E0E0;
            border-bottom: 1px solid #E0E0E0;
        }

        .authority-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 40px;
            align-items: center;
        }

        @media(max-width: 768px) {
            .authority-grid { grid-template-columns: 1fr; }
        }

        .authority-content h2 {
            font-size: 2rem;
            color: var(--dark);
            margin-bottom: 15px;
            font-weight: 800;
        }

        .authority-content h2 span {
            color: var(--secondary);
        }

        .authority-content p {
            margin-bottom: 15px;
            color: #555;
            font-size: 1rem;
        }

        .badge-year {
            display: inline-block;
            background: var(--primary);
            color: var(--white);
            padding: 5px 12px;
            font-weight: 700;
            border-radius: 4px;
            margin-bottom: 10px;
        }

        /* Para quem é */
        .target {
            padding: 70px 0;
            background: var(--white);
        }

        .section-title {
            text-align: center;
            font-size: 2.2rem;
            font-weight: 800;
            color: var(--dark);
            margin-bottom: 40px;
            text-transform: uppercase;
        }

        .target-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 25px;
        }

        .target-card {
            background: var(--light);
            padding: 25px;
            border-radius: 10px;
            border-top: 4px solid var(--primary);
            box-shadow: 0 2px 10px rgba(0,0,0,0.05);
        }

        .target-card h3 {
            font-size: 1.1rem;
            color: var(--primary);
            margin-bottom: 10px;
        }

        /* O que você vai aprender */
        .curriculum {
            padding: 70px 0;
            background: linear-gradient(to bottom, #121814, #0a0e0c);
            color: var(--white);
        }

        .curriculum .section-title {
            color: var(--white);
        }

        .curriculum-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            gap: 20px;
            margin-bottom: 40px;
        }

        .curriculum-item {
            background: rgba(255,255,255,0.05);
            border: 1px solid rgba(255,255,255,0.1);
            padding: 18px 20px;
            border-radius: 8px;
            display: flex;
            align-items: center;
            gap: 12px;
            font-weight: 600;
        }

        .curriculum-item span {
            color: var(--accent-yellow);
            font-size: 1.2rem;
        }

        /* Bloco de Preços / Oferta */
        .pricing {
            padding: 80px 0;
            background: var(--light);
        }

        .pricing-header {
            text-align: center;
            margin-bottom: 50px;
        }

        .pricing-header h2 {
            font-size: 2.4rem;
            font-weight: 900;
            color: var(--dark);
        }

        .pricing-header p {
            font-size: 1.2rem;
            color: var(--secondary);
            font-weight: 700;
            margin-top: 10px;
        }

        .pricing-cards {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            align-items: stretch;
        }

        .price-card {
            background: var(--white);
            border-radius: 12px;
            padding: 35px 25px;
            text-align: center;
            box-shadow: 0 5px 20px rgba(0,0,0,0.08);
            position: relative;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            border: 2px solid transparent;
        }

        .price-card.featured {
            border-color: var(--secondary);
            transform: scale(1.03);
        }

        .featured-tag {
            position: absolute;
            top: -15px;
            left: 50%;
            transform: translateX(-50%);
            background: var(--secondary);
            color: var(--white);
            padding: 5px 15px;
            border-radius: 20px;
            font-size: 0.8rem;
            font-weight: 800;
            text-transform: uppercase;
        }

        .price-card h3 {
            font-size: 1.4rem;
            color: var(--dark);
            margin-bottom: 15px;
            font-weight: 800;
        }

        .old-price {
            text-decoration: line-through;
            color: #888;
            font-size: 1rem;
            margin-bottom: 5px;
        }

        .current-price {
            font-size: 2.5rem;
            font-weight: 900;
            color: var(--primary);
            margin-bottom: 10px;
        }

        .savings-badge {
            display: inline-block;
            background: #E8F5E9;
            color: var(--primary);
            padding: 6px 12px;
            border-radius: 6px;
            font-weight: 700;
            font-size: 0.85rem;
            margin-bottom: 25px;
        }

        .price-card.featured .savings-badge {
            background: #FFEBEE;
            color: var(--secondary);
        }

        .price-features {
            list-style: none;
            margin-bottom: 25px;
            text-align: left;
            font-size: 0.95rem;
        }

        .price-features li {
            margin-bottom: 10px;
            color: #555;
        }

        /* GALERIA DE FOTOS E VÍDEOS (CANVA READY) */
        .gallery {
            padding: 70px 0;
            background: var(--white);
        }

        .gallery-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }

        .media-placeholder {
            position: relative;
            border-radius: 12px;
            overflow: hidden;
            border: 2px dashed var(--primary);
            background: #F8FAF9;
            min-height: 280px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            text-align: center;
            padding: 20px;
            transition: all 0.3s ease;
        }

        .media-placeholder:hover {
            background: #E8F5E9;
            border-color: var(--secondary);
        }

        .media-placeholder .icon {
            font-size: 2.5rem;
            margin-bottom: 10px;
            color: var(--primary);
        }

        .media-placeholder h4 {
            font-size: 1rem;
            color: var(--dark);
            margin-bottom: 5px;
            font-weight: 700;
        }

        .media-placeholder p {
            font-size: 0.8rem;
            color: var(--gray);
        }

        /* DEPOIMENTOS EM MÍDIA / CANVA */
        .testimonials {
            padding: 70px 0;
            background: var(--light);
            border-top: 1px solid #E0E0E0;
        }

        .testimonials-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 25px;
        }

        .testimonial-media-card {
            background: var(--white);
            border-radius: 12px;
            padding: 15px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.05);
            border-top: 4px solid var(--secondary);
            display: flex;
            flex-direction: column;
            gap: 15px;
        }

        .testimonial-media-box {
            position: relative;
            border-radius: 8px;
            border: 2px dashed var(--secondary);
            background: #FFF8F8;
            min-height: 320px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            text-align: center;
            padding: 20px;
            transition: all 0.3s ease;
        }

        .testimonial-media-box:hover {
            background: #FFEBEE;
        }

        .testimonial-media-box .icon {
            font-size: 3rem;
            margin-bottom: 10px;
            color: var(--secondary);
        }

        /* Seção FAQ */
        .faq {
            padding: 70px 0;
            background: var(--white);
            border-top: 1px solid #E0E0E0;
        }

        .faq-item {
            max-width: 800px;
            margin: 0 auto 15px auto;
            border: 1px solid #E0E0E0;
            border-radius: 8px;
            padding: 20px;
        }

        .faq-item h4 {
            font-size: 1.1rem;
            color: var(--primary);
            margin-bottom: 8px;
        }

        .faq-item p {
            color: #555;
            font-size: 0.95rem;
        }

        /* Footer */
        footer {
            background: var(--dark);
            color: var(--white);
            padding: 40px 0;
            text-align: center;
            font-size: 0.9rem;
            border-top: 4px solid var(--primary);
        }

        footer strong {
            color: var(--accent-yellow);
        }

        /* Responsive */
        @media(max-width: 768px) {
            .hero h1 { font-size: 1.8rem; }
            .hero p.subtitle { font-size: 1.05rem; }
            .price-card.featured { transform: none; }
            .btn { font-size: 0.95rem; padding: 15px 20px; }
        }
    </style>
</head>
<body>

    <!-- TOP BAR DE URGÊNCIA -->
    <div class="top-bar">
        ⚡ CONDIÇÃO ESPECIAL VÁLIDA ATÉ 20/10/2026 | VAGAS PRESENCIAIS LIMITADAS!
    </div>

    <!-- HERO SECTION -->
    <header class="hero">
        <div class="container">
            <span class="hero-badge">FECAPOLE — Desde 2013 Fortalecendo o Pole Esporte</span>
            <h1>CAPACITAÇÃO PROFISSIONAL FECAPOLE DE<br><span>POLE ESPORTE 2026</span></h1>
            <p class="subtitle">Formação Técnica, Esportiva e Profissional para quem quer ensinar, treinar e desenvolver atletas para o Pole Esporte.</p>
            
            <div class="hero-info-cards">
                <div class="info-card">📅 14 e 15 de Novembro de 2026</div>
                <div class="info-card">📍 Presencial (Vagas Limitadas)</div>
                <div class="info-card">💻 2 Anos de Acesso Online</div>
            </div>

            <a href="#oferta" class="btn btn-green">GARANTIR MINHA VAGA COM DESCONTO</a>
        </div>
    </header>

    <!-- INTRODUÇÃO / REFLEXÃO -->
    <section class="intro">
        <div class="container">
            <div class="intro-box">
                <h2>O próximo nível da sua atuação no Pole Esporte começa aqui.</h2>
                <p>Você já treina Pole. Já ensina movimentos. Já acompanha alunos.</p>
                <p><strong>Mas você está preparado para atuar com o Pole dentro de uma metodologia esportiva estruturada?</strong></p>
                <p>A FECAPOLE – Federação Catarinense de Pole Esporte e Aéreos apresenta uma capacitação criada para quem deseja ampliar seus conhecimentos técnicos e profissionais e compreender o Pole sob a perspectiva do treinamento esportivo, preparação física e desenvolvimento de atletas para campeonatos e eventos esportivos.</p>
                
                <div class="highlight-text">
                    🔥 <strong>UMA TURMA PRESENCIAL COM VAGAS LIMITADAS:</strong> Uma experiência mais próxima, técnica e direcionada à precisão do pole esportivo. Não deixe sua inscrição para depois.
                </div>
            </div>
        </div>
    </section>

    <!-- AUTORIDADE FECAPOLE -->
    <section class="authority">
        <div class="container">
            <div class="authority-grid">
                <div class="authority-content">
                    <span class="badge-year">TRADIÇÃO E EXCELÊNCIA</span>
                    <h2>Uma Capacitação de uma <span>Federação Esportiva</span></h2>
                    <p>A <strong>FECAPOLE</strong> atua desde 2013 na construção, desenvolvimento e fortalecimento do Pole Esporte em Santa Catarina e no Brasil. Foi a Entidade que desenvolveu os primeiros campeonatos ligados à IPFS (organização internacional esportiva) em 2017, 2018 e 2019.</p>
                    <p>Ao longo dessa trajetória, a Federação vem trabalhando para ampliar a qualidade técnica, a organização e a profissionalização da modalidade.</p>
                    <p><strong>Agora, essa experiência chega a uma nova etapa:</strong> Uma metodologia reestruturada e atualizada, pensada especificamente para o Pole Esporte, com conteúdo direcionado ao treinamento e à preparação esportiva.</p>
                </div>
                <div class="authority-box" style="background: var(--white); padding: 30px; border-radius: 12px; box-shadow: 0 4px 15px rgba(0,0,0,0.05); text-align: center;">
                    <h3 style="color: var(--primary); font-size: 1.5rem; margin-bottom: 15px;">MEU POLE É ESPORTE. 🏆</h3>
                    <p style="color: #666; font-size: 0.95rem;">Aqui, o objetivo não é simplesmente ensinar mais movimentos. É ajudar você a compreender como treinar, orientar, preparar e desenvolver atletas com base científica e prática esportiva.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- PARA QUEM É -->
    <section class="target">
        <div class="container">
            <h2 class="section-title">🎯 Para Quem é Esta Capacitação?</h2>
            <div class="target-grid">
                <div class="target-card">
                    <h3>Professores e Instrutores</h3>
                    <p>Que querem aprimorar sua metodologia de ensino e oferecer treinos mais seguros e estruturados.</p>
                </div>
                <div class="target-card">
                    <h3>Treinadores</h3>
                    <p>Que desejam estruturar melhor o treinamento e a rotina de preparação dos seus atletas.</p>
                </div>
                <div class="target-card">
                    <h3>Atletas de Pole</h3>
                    <p>Que querem ampliar seus conhecimentos e construir uma nova possibilidade profissional na modalidade.</p>
                </div>
                <div class="target-card">
                    <h3>Donos de Estúdios</h3>
                    <p>Profissionais e responsáveis por escolas que desejam fortalecer o segmento esportivo em seus espaços.</p>
                </div>
                <div class="target-card">
                    <h3>Futuros Treinadores</h3>
                    <p>Profissionais que desejam ingressar no Pole Esporte competitivo e dominar a preparação para campeonatos.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- O QUE VOCÊ VAI APRENDER -->
    <section class="curriculum">
        <div class="container">
            <h2 class="section-title">📚 O Que Você Vai Aprender?</h2>
            <p style="text-align: center; color: #BBB; margin-bottom: 30px;">A programação foi totalmente estruturada para oferecer uma visão técnica e esportiva de alto nível:</p>
            
            <div class="curriculum-grid">
                <div class="curriculum-item"><span>✔️</span> Formação técnica esportiva em Pole Esporte</div>
                <div class="curriculum-item"><span>✔️</span> Metodologia de treinamento</div>
                <div class="curriculum-item"><span>✔️</span> Preparação para campeonatos e eventos esportivos</div>
                <div class="curriculum-item"><span>✔️</span> Desenvolvimento e treinamento de atletas</div>
                <div class="curriculum-item"><span>✔️</span> Noções fisioesportivas</div>
                <div class="curriculum-item"><span>✔️</span> Fortalecimento direcionado para o Pole</div>
                <div class="curriculum-item"><span>✔️</span> Preparação física</div>
                <div class="curriculum-item"><span>✔️</span> Desenvolvimento técnico e treinamento</div>
                <div class="curriculum-item"><span>✔️</span> Estratégias para evolução esportiva</div>
                <div class="curriculum-item"><span>✔️</span> Conhecimentos aplicados à atuação do treinador</div>
                <div class="curriculum-item"><span>✔️</span> Atualização metodológica</div>
                <div class="curriculum-item"><span>✔️</span> Conceito de Eventos e Campeonatos</div>
            </div>

            <div style="text-align: center; background: rgba(255,255,255,0.08); padding: 25px; border-radius: 8px; max-width: 800px; margin: 0 auto;">
                <h3 style="color: var(--accent-yellow); margin-bottom: 10px;">🎓 Não é só um final de semana de curso!</h3>
                <p>Além das aulas presenciais, você recebe material didático (apostilas/conteúdos de apoio) e <strong>02 ANOS DE ACESSO ONLINE AO CONTEÚDO</strong>. Você aprende no presencial, estuda, revisa e continua evoluindo!</p>
            </div>
        </div>
    </section>

    <!-- BLOCO DE OFERTA / PREÇOS -->
    <section class="pricing" id="oferta">
        <div class="container">
            <div class="pricing-header">
                <h2>GARANTA SUA VAGA COM CONDIÇÃO PROMOCIONAL</h2>
                <p>⏰ Preços promocionais válidos somente de 20/09 a 20/10/2026!</p>
            </div>

            <div class="pricing-cards">
                
                <!-- PLANO 1: NÃO FILIADO -->
                <div class="price-card">
                    <div>
                        <h3>NÃO FILIADO</h3>
                        <p style="color: #666; font-size: 0.9rem; margin-bottom: 15px;">Para profissionais que buscam excelência técnica.</p>
                        <div class="old-price">De R$ 1.700,00</div>
                        <div class="current-price">R$ 1.200,00</div>
                        <div class="savings-badge">💰 Você economiza R$ 500,00</div>
                        <ul class="price-features">
                            <li>✔️ Presencial nos dias 14 e 15/Nov/2026</li>
                            <li>✔️ Material Didático Incluso</li>
                            <li>✔️ 2 Anos de Acesso Online</li>
                            <li>✔️ Vagas Limitadas</li>
                        </ul>
                    </div>
                    <a href="https://pay.hotmart.com/H72066623X?off=0rxkoh3o" class="btn btn-green" style="font-size: 0.95rem;">QUERO GARANTIR MINHA VAGA</a>
                </div>

                <!-- PLANO 2: FILIADO FECAPOLE -->
                <div class="price-card featured">
                    <div class="featured-tag">MAIS POPULAR</div>
                    <div>
                        <h3>FILIADO FECAPOLE</h3>
                        <p style="color: #666; font-size: 0.9rem; margin-bottom: 15px;">Condição especial para membros ativos.</p>
                        <div class="old-price">De R$ 1.700,00</div>
                        <div class="current-price">R$ 1.000,00</div>
                        <div class="savings-badge">🔥 Você economiza R$ 700,00</div>
                        <ul class="price-features">
                            <li>✔️ Presencial nos dias 14 e 15/Nov/2026</li>
                            <li>✔️ Material Didático Incluso</li>
                            <li>✔️ 2 Anos de Acesso Online</li>
                            <li>✔️ Desconto Exclusivo Filiado</li>
                        </ul>
                    </div>
                    <a href="https://pay.hotmart.com/H72066623X?off=9z01t8cs" class="btn btn-red" style="font-size: 0.9rem;">SOU FILIADO(A) QUERO GARANTIR MINHA VAGA</a>
                </div>

                <!-- PLANO 3: RECICLAGEM -->
                <div class="price-card">
                    <div class="featured-tag" style="background: var(--primary);">MAIOR ECONOMIA</div>
                    <div>
                        <h3>RECICLAGEM</h3>
                        <p style="color: #666; font-size: 0.9rem; margin-bottom: 15px;">Já fez a capacitação anteriormente? Atualize-se!</p>
                        <div class="old-price">De R$ 1.700,00</div>
                        <div class="current-price">R$ 850,00</div>
                        <div class="savings-badge">♻️ Você economiza R$ 850,00</div>
                        <ul class="price-features">
                            <li>✔️ Atualização metodológica completa</li>
                            <li>✔️ Presencial nos dias 14 e 15/Nov/2026</li>
                            <li>✔️ Material Didático Atualizado</li>
                            <li>✔️ 2 Anos de Acesso Online</li>
                        </ul>
                    </div>
                    <a href="https://pay.hotmart.com/H72066623X?off=n5daf5pn" class="btn btn-green" style="font-size: 0.95rem;">QUERO RECICLAR</a>
                </div>

            </div>

            <p style="text-align: center; margin-top: 30px; font-size: 0.85rem; color: #777;">* Vagas presenciais limitadas. Condições promocionais válidas até 20/10/2026 ou enquanto houver disponibilidade de vagas na turma.</p>
        </div>
    </section>

    <!-- GALERIA DE FOTOS E VÍDEOS (EXPERIÊNCIA PRESENCIAL E PRÁTICA) -->
    <section class="gallery">
        <div class="container">
            <h2 class="section-title">📸 Experiência Presencial e Prática</h2>
            <p style="text-align: center; color: #666; margin-bottom: 40px; font-weight: 500;">Espaço reservado para inclusão de 6 fotos ou vídeos criados e exportados no Canva:</p>
            
            <div class="gallery-grid">
                
                <!-- ESPAÇO MÍDIA 1 -->
                <div class="media-placeholder">
                    <div class="icon">🖼️ / 🎥</div>
                    <h4>Foto ou Vídeo 01 (Canva)</h4>
                    <p>Insira aqui o link de embed do Canva, &lt;img&gt; ou &lt;video&gt;</p>
                </div>

                <!-- ESPAÇO MÍDIA 2 -->
                <div class="media-placeholder">
                    <div class="icon">🖼️ / 🎥</div>
                    <h4>Foto ou Vídeo 02 (Canva)</h4>
                    <p>Insira aqui o link de embed do Canva, &lt;img&gt; ou &lt;video&gt;</p>
                </div>

                <!-- ESPAÇO MÍDIA 3 -->
                <div class="media-placeholder">
                    <div class="icon">🖼️ / 🎥</div>
                    <h4>Foto ou Vídeo 03 (Canva)</h4>
                    <p>Insira aqui o link de embed do Canva, &lt;img&gt; ou &lt;video&gt;</p>
                </div>

                <!-- ESPAÇO MÍDIA 4 -->
                <div class="media-placeholder">
                    <div class="icon">🖼️ / 🎥</div>
                    <h4>Foto ou Vídeo 04 (Canva)</h4>
                    <p>Insira aqui o link de embed do Canva, &lt;img&gt; ou &lt;video&gt;</p>
                </div>

                <!-- ESPAÇO MÍDIA 5 -->
                <div class="media-placeholder">
                    <div class="icon">🖼️ / 🎥</div>
                    <h4>Foto ou Vídeo 05 (Canva)</h4>
                    <p>Insira aqui o link de embed do Canva, &lt;img&gt; ou &lt;video&gt;</p>
                </div>

                <!-- ESPAÇO MÍDIA 6 -->
                <div class="media-placeholder">
                    <div class="icon">🖼️ / 🎥</div>
                    <h4>Foto ou Vídeo 06 (Canva)</h4>
                    <p>Insira aqui o link de embed do Canva, &lt;img&gt; ou &lt;video&gt;</p>
                </div>

            </div>
        </div>
    </section>

    <!-- DEPOIMENTOS DE ALUNAS E ALUNOS (CANVA READY) -->
    <section class="testimonials">
        <div class="container">
            <h2 class="section-title">💬 O Que Dizem Nossos Alunos e Alunas</h2>
            <p style="text-align: center; color: #666; margin-bottom: 40px; font-weight: 500;">Espaços para inclusão de depoimentos em vídeo, reels ou artes gráficas editadas no Canva:</p>
            
            <div class="testimonials-grid">
                
                <!-- DEPOIMENTO MÍDIA 1 -->
                <div class="testimonial-media-card">
                    <div class="testimonial-media-box">
                        <div class="icon">🎬</div>
                        <h4 style="color: var(--secondary);">Depoimento em Vídeo / Foto 01</h4>
                        <p style="color: var(--gray); font-size: 0.85rem;">Cole o código embed do Canva, Instagram ou YouTube aqui.</p>
                    </div>
                </div>

                <!-- DEPOIMENTO MÍDIA 2 -->
                <div class="testimonial-media-card">
                    <div class="testimonial-media-box">
                        <div class="icon">🎬</div>
                        <h4 style="color: var(--secondary);">Depoimento em Vídeo / Foto 02</h4>
                        <p style="color: var(--gray); font-size: 0.85rem;">Cole o código embed do Canva, Instagram ou YouTube aqui.</p>
                    </div>
                </div>

                <!-- DEPOIMENTO MÍDIA 3 -->
                <div class="testimonial-media-card">
                    <div class="testimonial-media-box">
                        <div class="icon">🎬</div>
                        <h4 style="color: var(--secondary);">Depoimento em Vídeo / Foto 03</h4>
                        <p style="color: var(--gray); font-size: 0.85rem;">Cole o código embed do Canva, Instagram ou YouTube aqui.</p>
                    </div>
                </div>

                <!-- DEPOIMENTO MÍDIA 4 -->
                <div class="testimonial-media-card">
                    <div class="testimonial-media-box">
                        <div class="icon">🎬</div>
                        <h4 style="color: var(--secondary);">Depoimento em Vídeo / Foto 04</h4>
                        <p style="color: var(--gray); font-size: 0.85rem;">Cole o código embed do Canva, Instagram ou YouTube aqui.</p>
                    </div>
                </div>

                <!-- DEPOIMENTO MÍDIA 5 -->
                <div class="testimonial-media-card">
                    <div class="testimonial-media-box">
                        <div class="icon">🎬</div>
                        <h4 style="color: var(--secondary);">Depoimento em Vídeo / Foto 05</h4>
                        <p style="color: var(--gray); font-size: 0.85rem;">Cole o código embed do Canva, Instagram ou YouTube aqui.</p>
                    </div>
                </div>

                <!-- DEPOIMENTO MÍDIA 6 -->
                <div class="testimonial-media-card">
                    <div class="testimonial-media-box">
                        <div class="icon">🎬</div>
                        <h4 style="color: var(--secondary);">Depoimento em Vídeo / Foto 06</h4>
                        <p style="color: var(--gray); font-size: 0.85rem;">Cole o código embed do Canva, Instagram ou YouTube aqui.</p>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- PERGUNTAS FREQUENTES (FAQ) -->
    <section class="faq">
        <div class="container">
            <h2 class="section-title">❓ Dúvidas Frequentes</h2>
            
            <div class="faq-item">
                <h4>Quais são as Condições de Pagamento?</h4>
                <p>O Pagamento é feito diretamente no HOTMART, você pode parcelar no cartão.</p>
            </div>

            <div class="faq-item">
                <h4>Quando e onde acontecerá a capacitação?</h4>
                <p>A etapa presencial será realizada nos dias 14 e 15 de novembro de 2026, no litoral de Santa Catarina, na cidade de Itajaí . As vagas presenciais são limitadas para garantir o acompanhamento técnico individualizado.</p>
            </div>

            <div class="faq-item">
                <h4>Por quanto tempo terei acesso ao conteúdo online?</h4>
                <p>Você terá acesso garantido à plataforma online com todo o conteúdo e materiais didáticos de apoio por <strong>2 anos (24 meses)</strong> após o curso.</p>
            </div>

            <div class="faq-item">
                <h4>Quem tem direito ao valor de Reciclagem?</h4>
                <p>O valor promocional de Reciclagem (R$ 850,00) é exclusivo para alunos que já concluíram a Capacitação FECAPOLE em edições anteriores e desejam se atualizar com a nova metodologia.</p>
            </div>

            <div class="faq-item">
                <h4>Até quando vai o valor com desconto?</h4>
                <p>Os valores promocionais de pré-venda/lote especial são válidos exclusivamente até o dia <strong>20 de outubro de 2026</strong> ou até o esgotamento das vagas da turma.</p>
            </div>
        </div>
    </section>

    <!-- FOOTER -->
    <footer>
        <div class="container">
            <p><strong>FECAPOLE — Federação Catarinense de Pole Esporte e Aéreos</strong></p>
            <p style="margin-top: 5px;">Desde 2013 fortalecendo, estruturando e desenvolvendo o Pole Esporte.</p>
            <p style="margin-top: 15px; font-size: 0.8rem; color: #888;">Conhecimento. Técnica. Preparação. Esporte. | Todos os direitos reservados © 2026</p>
        </div>
    </footer>

</body>
</html>
