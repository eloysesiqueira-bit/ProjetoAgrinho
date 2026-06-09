# ProjetoAgrinho
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AGRO FORTE | Futuro Sustentável - Paraná</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            background: #f8f9f7;
        }

        header {
            background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), url('https://images.unsplash.com/photo-1625246333197-6c2b9d4e2c3c?w=1600') center/cover no-repeat;
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: white;
        }

        .hero-content {
            max-width: 900px;
            padding: 0 20px;
        }

        h1 {
            font-size: 3.8rem;
            margin-bottom: 15px;
            text-shadow: 0 4px 10px rgba(0,0,0,0.6);
        }

        .subtitle {
            font-size: 1.6rem;
            margin-bottom: 30px;
            font-weight: 400;
        }

        .btn {
            display: inline-block;
            background: #4CAF50;
            color: white;
            padding: 14px 35px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: bold;
            margin-top: 20px;
            transition: all 0.3s;
        }

        .btn:hover {
            background: #388E3C;
            transform: translateY(-5px);
        }

        section {
            padding: 90px 5%;
        }

        .section-title {
            text-align: center;
            font-size: 2.5rem;
            margin-bottom: 60px;
            color: #1B5E20;
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            gap: 30px;
            max-width: 1200px;
            margin: 0 auto;
        }

        .card {
            background: white;
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
            transition: transform 0.3s;
        }

        .card:hover {
            transform: translateY(-10px);
        }

        .card img {
            width: 100%;
            height: 220px;
            object-fit: cover;
        }

        .card-content {
            padding: 25px;
        }

        footer {
            background: #1B5E20;
            color: white;
            text-align: center;
            padding: 60px 20px;
        }

        .green {
            color: #4CAF50;
        }
    </style>
</head>
<body>

    <!-- HERO -->
    <header>
        <div class="hero-content">
            <h1>AGRO FORTE</h1>
            <p class="subtitle">FUTURO SUSTENTÁVEL</p>
            <h2 style="font-size: 2.2rem; margin: 20px 0;">Equilíbrio entre Produção e Meio Ambiente</h2>
            <p style="font-size: 1.3rem; max-width: 700px; margin: 0 auto 30px;">
                O Paraná mostra ao Brasil e ao mundo como produzir muito, <strong>respeitando a natureza</strong>.
            </p>
            <a href="#conteudo" class="btn">CONHEÇA NOSSA REALIDADE</a>
        </div>
    </header>

    <!-- CONTEÚDO -->
    <section id="conteudo">
        <h2 class="section-title">Paraná: Potência Agroambiental</h2>
        
        <div class="grid">
            <div class="card">
                <img src="https://images.unsplash.com/photo-1592982537447-6f2a6a0c7c4f?w=800" alt="Soja Paraná">
                <div class="card-content">
                    <h3>🚜 Produção de Destaque</h3>
                    <p>O Paraná é o 2º maior produtor de grãos do Brasil. Destaque em soja, milho, trigo, feijão e pecuária.</p>
                </div>
            </div>

            <div class="card">
                <img src="https://images.unsplash.com/photo-1464226184884-fa280b87c399?w=800" alt="Sustentabilidade">
                <div class="card-content">
                    <h3>🌱 Práticas Sustentáveis</h3>
                    <p>Plantio direto, rotação de culturas, integração lavoura-pecuária-floresta (ILPF) e recuperação de matas ciliares.</p>
                </div>
            </div>

            <div class="card">
                <img src="https://images.unsplash.com/photo-1542601906990-b4d3d9d4d5b9?w=800" alt="Meio Ambiente">
                <div class="card-content">
                    <h3>🌳 Compromisso Ambiental</h3>
                    <p>Mais de 1,8 milhão de hectares de Reserva Legal e Áreas de Preservação Permanente preservadas no estado.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- PILARES -->
    <section style="background: #E8F5E9;">
        <h2 class="section-title">Os Pilares do Agro Forte Sustentável</h2>
        <div class="grid">
            <div class="card">
                <div class="card-content">
                    <h3 style="color:#1B5E20">✅ Tecnologia no Campo</h3>
                    <ul style="margin-top:15px; line-height:2">
                        <li>→ Agricultura de Precisão</li>
                        <li>→ Drones e Sensores</li>
                        <li>→ Biotecnologia</li>
                        <li>→ Irrigação Eficiente</li>
                    </ul>
                </div>
            </div>
            <div class="card">
                <div class="card-content">
                    <h3 style="color:#1B5E20">✅ Conservação do Solo</h3>
                    <ul style="margin-top:15px; line-height:2">
                        <li>→ Plantio Direto</li>
                        <li>→ Terracing</li>
                        <li>→ Cobertura Verde</li>
                        <li>→ Recuperação de áreas degradadas</li>
                    </ul>
                </div>
            </div>
            <div class="card">
                <div class="card-content">
                    <h3 style="color:#1B5E20">✅ Biodiversidade</h3>
                    <ul style="margin-top:15px; line-height:2">
                        <li>→ Corredores Ecológicos</li>
                        <li>→ Polinização</li>
                        <li>→ Preservação de Nascentes</li>
                        <li>→ Florestas Comerciais Sustentáveis</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- CHAMADA -->
    <section style="background: linear-gradient(135deg, #1B5E20, #4CAF50); color: white; text-align: center;">
        <h2 style="font-size: 2.8rem; margin-bottom: 25px;">O Paraná está construindo o futuro</h2>
        <p style="font-size: 1.4rem; max-width: 800px; margin: 0 auto 40px;">
            Um agro forte, moderno e <strong>sustentável</strong>. 
            Onde produção recorde caminha junto com a preservação ambiental.
        </p>
        <a href="#" class="btn" style="background:white; color:#1B5E20; font-size:1.1rem;">Seja parte dessa transformação</a>
    </section>

    <footer>
        <h2>AGRO FORTE • PARANÁ</h2>
        <p>Equilíbrio entre Produção e Meio Ambiente</p>
        <p style="margin-top: 20px; opacity: 0.9;">
            Um legado para as próximas gerações
        </p>
        <p style="margin-top: 40px; font-size: 0.9rem;">
            &copy; 2026 - Desenvolvimento Sustentável do Agronegócio Paranaense
        </p>
    </footer>

</body>
</html>