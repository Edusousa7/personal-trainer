<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Edu Sousa - Personal Trainer</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            background: linear-gradient(to right, #000000, #ff0000);
            color: #fff;
        }
        header {
            background: url(https://ultramacho.com.br/wp-content/uploads/2020/07/academia-2.jpg) no-repeat center center/cover;
            color: #fff;
            text-align: center;
            padding: 3rem 1rem;
            position: relative;
        }
        header h1 {
            margin: 0;
            font-size: 3rem;
            text-shadow: 2px 2px 4px #000;
        }
        .container {
            display: flex;
            flex-direction: column;
            margin: 0 auto;
            padding: 2rem;
            max-width: 1200px;
        }
        .section {
            margin-bottom: 2rem;
            padding: 1rem;
            border-radius: 8px;
            background-color: #1a1a1a;
        }
        .section h2 {
            margin-top: 0;
            font-size: 2.5rem;
            color: #ff0000;
            text-shadow: 1px 1px 2px #000;
        }
        .section-content {
            display: flex;
            flex-direction: column;
            gap: 1rem;
        }
        .form-group {
            margin-bottom: 1rem;
        }
        .form-group label {
            display: block;
            margin-bottom: 0.5rem;
        }
        .form-group input,
        .form-group textarea {
            width: 100%;
            padding: 0.5rem;
            border: 1px solid #ddd;
            border-radius: 4px;
            background-color: #333;
            color: #fff;
        }
        .form-group textarea {
            resize: vertical;
        }
        button {
            padding: 0.5rem 1rem;
            background-color: #ff0000;
            color: #fff;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        button:hover {
            background-color: #cc0000;
        }
        footer {
            background-color: #1a1a1a;
            color: #fff;
            text-align: center;
            padding: 1rem;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Edu Sousa - Personal Trainer</h1>
    </header>

    <div class="container">
        <section class="section" id="produtos-serviços">
            <h2>Produtos e Serviços</h2>
            <div class="section-content">
                <p>Edu Sousa oferece uma gama completa de serviços personalizados para atender às suas necessidades de fitness. Nossos serviços incluem:</p>
                <ul>
                    <li>Avaliações físicas detalhadas</li>
                    <li>Planos de treinamento individualizados</li>
                    <li>Treinamento em grupo</li>
                    <li>Consultoria nutricional</li>
                    <li>Orientação sobre recuperação e prevenção de lesões</li>
                </ul>
            </div>
        </section>

        <section class="section" id="diferencial">
            <h2>Diferencial</h2>
            <div class="section-content">
                <p>O diferencial de Edu Sousa está na sua abordagem personalizada e na experiência acumulada ao longo de 10 anos como personal trainer. Ele utiliza métodos comprovados e adapta cada treinamento às necessidades individuais dos clientes.</p>
            </div>
        </section>

        <section class="section" id="vantagens-benefícios">
            <h2>Vantagens e Benefícios</h2>
            <div class="section-content">
                <p>Ao contratar Edu Sousa como seu personal trainer, você terá acesso a:</p>
                <ul>
                    <li>Treinamentos personalizados e eficazes</li>
                    <li>Melhoria na condição física e saúde geral</li>
                    <li>Suporte contínuo e motivação</li>
                    <li>Programas adaptados ao seu ritmo e objetivos</li>
                    <li>Acompanhamento e ajustes regulares nos planos de treinamento</li>
                </ul>
            </div>
        </section>

        <section class="section" id="sobre">
            <h2>Sobre Edu Sousa</h2>
            <div class="section-content">
                <p>Edu Sousa tem 35 anos e é personal trainer há 10 anos. Com vasta experiência e uma abordagem focada no bem-estar e resultados, Edu é a escolha certa para quem busca transformação e excelência em seu treinamento.</p>
            </div>
        </section>

        <section class="section" id="contato">
            <h2>Formulário de Contato</h2>
            <form>
                <div class="form-group">
                    <label for="nome">Nome</label>
                    <input type="text" id="nome" name="nome" required>
                </div>
                <div class="form-group">
                    <label for="email">E-mail</label>
                    <input type="email" id="email" name="email" required>
                </div>
                <div class="form-group">
                    <label for="mensagem">Mensagem</label>
                    <textarea id="mensagem" name="mensagem" rows="4" required></textarea>
                </div>
                <button type="submit">Enviar</button>
            </form>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 Edu Sousa. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
