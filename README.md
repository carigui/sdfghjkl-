<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Exploração do tema 'Do Campo à Cidade, Colhendo Oportunidades', com foco nas inovações sustentáveis no campo e seu impacto nas cidades.">
    <title>Do Campo à Cidade, Colhendo Oportunidades</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <style>
        /* Resetando o estilo e configurando a fonte */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            background-color: #f5f5f5;
            color: #333;
            line-height: 1.6;
            overflow-x: hidden;
        }

        h1, h2, p {
            text-align: center;r Desconhecido
        }

        /* Cabeçalho */
        header {
            background-color: #4caf50; /* Verde claro */
            color: white;
            padding: 100px 20px;
            position: relative;
            text-align: center;
            animation: fadeIn 2s ease-in-out;
        }

        header h1 {
            font-size: 50px;
            animation: slideUp 1s ease-out;
        }

        header p {
            font-size: 20px;
            margin-top: 10px;
            animation: slideUp 1.5s ease-out;
        }

        /* Menu de navegação */
        nav {
            background-color: #333; /* Cor escura para contraste */
            text-align: center;
            padding: 15px 0;
            position: sticky;
            top: 0;
            z-index: 1000;
            animation: fadeIn 2s ease-in-out;
        }

        nav a {
            color: white;
            text-decoration: none;
            padding: 12px 20px;
            font-size: 18px;
            margin: 0 15px;
            display: inline-block;
            transition: background-color 0.3s;
        }

        nav a:hover {
            background-color: #ddd;
            color: #333;
        }

        /* Animações */
        @keyframes fadeIn {
            0% { opacity: 0; }
            100% { opacity: 1; }
        }

        @keyframes slideUp {
            0% { transform: translateY(20px); opacity: 0; }
            100% { transform: translateY(0); opacity: 1; }
        }

        @keyframes zoomIn {
            0% { transform: scale(0.8); opacity: 0; }
            100% { transform: scale(1); opacity: 1; }
        }

        /* Seções principais */
        section {
            padding: 60px 20px;
            background-color: white;
            margin: 20px auto;
            max-width: 1000px;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            animation: zoomIn 1.5s ease-out;
        }

        section#impacto {
            background-color: #007bff; /* Azul suave */
            color: white;
        }

        section#inovacao {
            background-color: #ffb74d; /* Laranja suave */
            color: white;
        }

        section img {
            width: 100%;
            border-radius: 8px;
            margin-bottom: 30px;
            opacity: 0.9;
            transition: transform 0.5s ease-in-out;
        }

        section img:hover {
            transform: scale(1.05);
        }

        /* Cartões informativos */
        .cards {
            display: flex;
            justify-content: space-between;
            flex-wrap: wrap;
            gap: 20px;
            margin-top: 30px;
        }

        .card {
            background-color: #4caf50; /* Verde claro */
            color: white;
            padding: 20px;
            width: 45%;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease-in-out, background-color 0.3s ease-in-out;
            animation: slideUp 1.5s ease-in-out;
        }

        .card:hover {
            transform: scale(1.05);
            background-color: #388e3c; /* Verde mais escuro */
        }

        .card h3 {
            font-size: 24px;
            margin-bottom: 15px;
            animation: fadeIn 2s ease-in-out;
        }

        .card p {
            font-size: 16px;
        }

        /* Formulário de contato */
        .contact-form {
            background-color: #f8f9fa; /* Cinza suave */
            padding: 40px;
            margin-top: 30px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            animation: zoomIn 2s ease-out;
        }

        .contact-form input,
        .contact-form textarea {
            width: 100%;
            padding: 15px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 8px;
            font-size: 16px;
        }

        .contact-form button {
            background-color: #4caf50; /* Verde claro */
            color: white;
            border: none;
            padding: 15px;
            border-radius: 8px;
            font-size: 18px;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        r Desconhecido
        .contact-form button:hover {
            background-color: #388e3c; /* Verde mais escuro */
        }

        /* Rodapé */
        footer {
            background-color: #333; /* Cor escura para contraste */
            color: white;
            text-align: center;
            padding: 20px 0;
            position: relative;
            bottom: 0;
            width: 100%;
            animation: fadeIn 2s ease-in-out;
        }

        footer p {
            font-size: 14px;
        }

        /* Ícones interativos */
        .icons-container {
            display: flex;
            justify-content: center;
            gap: 30px;
            margin-top: 40px;
        }

        .icon {
            font-size: 40px;
            color: #4caf50; /* Verde claro */
            transition: transform 0.3s ease-in-out, color 0.3s ease-in-out;
        }

        .icon:hover {
            transform: scale(1.3);
            color: #388e3c; /* Verde mais escuro */
        }

        /* Nova seção - Citações inspiradoras */
        #citacoes {
            background-color: #f1f1f1; /* Cinza suave */
            padding: 60px 20px;
            margin-top: 40px;
            animation: zoomIn 2s ease-out;
        }

        .citacao {
            font-style: italic;
            color: #555;
            margin-bottom: 20px;
        }

        .citacao p {
            font-size: 22px;
        }

        .citacao span {
            font-weight: bold;
        }

        /* Seção de Gráficos */
        #graficos {
            padding: 60px 20px;
            background-color: #f4f4f4;
            margin-top: 40px;
            animation: zoomIn 2s ease-out;
        }

        .grafico {
            width: 48%;
            display: inline-block;
            padding: 20px;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            text-align: center;
            margin-right: 4%;
            margin-bottom: 20px;
        }

        .grafico:last-child {
            margin-right: 0;
        }

        /* Seção de Exemplos de Inovação */
        #exemplos {
            background-color: #007bff; /* Azul suave */
            color: white;
            padding: 60px 20px;
            margin-top: 40px;
            animation: zoomIn 2s ease-out;
        }

        .exemplo {
            margin-bottom: 20px;
        }

        .exemplo h3 {
            font-size: 28px;
            margin-bottom: 10px;
        }

        .exemplo p {
            font-size: 16px;
        }
    </style>
</head>
<body>

<!-- Cabeçalho -->
<header>
    <h1>Do Campo à Cidade, Colhendo Oportunidades</h1>
    <p>Conectando o campo e a cidade com soluções sustentáveis e inovações do agronegócio</p>
</header>

<!-- Menu de navegação -->
<nav>
    <a href="#introducao">Introdução</a>
    <a href="#impacto">Impacto</a>
    <a href="#inovacao">Inovações</a>
    <a href="#citacoes">Citações</a>
    <a href="#graficos">Gráficos</a>
    <a href="#exemplos">Exemplos</a>
    <a href="#contato">Contato</a>
</nav>

<!-- Introdução -->
<section id="introducao">
    <h2>O Significado do Tema</h2>
    <p>O tema "Do Campo à Cidade, Colhendo Oportunidades" mostra como as práticas agrícolas e inovações sustentáveis do campo podem impactar positivamente as cidades. Ao integrar novas tecnologias no campo, conseguimos não apenas melhorar a produção rural, mas também solucionar desafios urbanos, como a escassez de alimentos e poluição. O campo e a cidade se conectam, criando soluções para ambos.</p>
</section>

<!-- Impacto do Campo nas Cidades -->
<section id="impacto">
    <h2>Impacto do Campo nas Cidades</h2>
    <div class="cards">
        <div class="card">
            <h3>Produção Sustentável</h3>
            <p>A sustentabilidade no campo não é apenas uma tendência, mas uma necessidade. As práticas sustentáveis garantem alimentos de qualidade para as cidades, com menos impacto ambiental.</p>
        </div>
        <div class="card">
            <h3>Uso de Energia Renovável</h3>
            <p>A transição para energias limpas no campo, como solar e biocombustíveis, também afeta positivamente as cidades, ajudando a reduzir a poluição e os custos energéticos.</p>
        </div>
    </div>
</section>

<!-- Inovações Sustentáveis -->
<section id="inovacao">
    <h2>Inovações Sustentáveis</h2>
    <p>A inovação tecnológica está transformando o campo. Drones para monitoramento de safras, técnicas de irrigação inteligentes e o uso de energia solar são apenas algumas das maneiras pelas quais a agricultura está evoluindo para ser mais sustentável e eficiente.</p>
</section>

<!-- Citações Inspiradoras -->
<section id="citacoes">
    <h2>Citações Inspiradoras</h2>
    <div class="citacao">
        <p>"A agricultura sustentável não é apenas o futuro, mas o presente que construímos juntos." <span>- Autor Desconhecido</span></p>
    </div>
    <div class="citacao">
        <p>"O campo e a cidade, quando interconectados, criam um futuro mais resiliente e sustentável para todos." <span>- Agrônomo João Silva</span></p>
    </div>
</section>

<!-- Gráficos -->
<section id="graficos">
    <h2>Gráficos e Dados</h2>
    <div class="grafico">
        <h3>Produção Sustentável x Produção Convencional</h3>
        <p>Gráfico sobre como a produção sustentável está ganhando mais espaço nos últimos anos.</p>
    </div>
    <div class="grafico">
        <h3>Crescimento de Energias Renováveis no Campo</h3>
        <p>Gráfico sobre a implementação de tecnologias renováveis no setor agrícola.</p>
    </div>
</section>

<!-- Exemplos de Inovação -->
<section id="exemplos">
    <h2>Exemplos de Inovação no Campo</h2>
    <div class="exemplo">
        <h3>Uso de Drones para Monitoramento</h3>
        <p>Drones ajudam os agricultores a monitorar as colheitas com precisão, identificando áreas de risco e melhorando o uso de recursos naturais.</p>
    </div>
    <div class="exemplo">
        <h3>Técnicas de Irrigação Inteligente</h3>
        <p>A irrigação controlada e eficiente economiza água e aumenta a produtividade das safras.</p>
    </div>
</section>

<!-- Formulário de Contato -->
<section id="contato">
    <h2>Entre em Contato</h2>
    <form class="contact-form" action="#" method="post">
        <input type="text" name="nome" placeholder="Seu nome" required>
        <input type="email" name="email" placeholder="Seu e-mail" required>
        <textarea name="mensagem" rows="6" placeholder="Sua mensagem" required></textarea>
        <button type="submit">Enviar Mensagem</button>
    </form>
</section>

<!-- Rodapé -->
<footer>
    <p>© 2025 Agrinho - Todos os direitos reservados.</p>
</footer>

</body>
</html>
