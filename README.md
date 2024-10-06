# ErichEdu
aplicativo escolar
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ErichEDU - Conectando Educação</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #004a87;
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
            display: flex;
            justify-content: center;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        .banner {
            background: url('https://via.placeholder.com/1500x500') no-repeat center center;
            background-size: cover;
            color: white;
            text-align: center;
            padding: 100px 0;
        }

        .banner h1 {
            font-size: 50px;
            margin: 0;
        }

        .banner p {
            font-size: 24px;
            margin: 10px 0 20px;
        }

        .btn {
            background-color: #ff6f61;
            color: white;
            padding: 15px 30px;
            text-decoration: none;
            border-radius: 5px;
            font-size: 18px;
        }

        .funcionalidades {
            padding: 50px 0;
            text-align: center;
            background-color: #fff;
        }

        .funcionalidades h2 {
            font-size: 36px;
            margin-bottom: 20px;
        }

        .funcionalidades p {
            font-size: 18px;
            margin-bottom: 30px;
        }

        .cards {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }

        .card {
            background-color: #f4f4f4;
            padding: 20px;
            margin: 15px;
            border-radius: 10px;
            width: 300px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }

        .card h3 {
            font-size: 24px;
            color: #004a87;
            margin-bottom: 10px;
        }

        footer {
            background-color: #004a87;
            color: white;
            text-align: center;
            padding: 20px 0;
        }

        footer p {
            margin: 0;
        }
    </style>
</head>
<body>

    <header>
        <nav>
            <ul>
                <li><a href="#">Início</a></li>
                <li><a href="#">Funcionalidades</a></li>
                <li><a href="#">Login</a></li>
                <li><a href="#">Contato</a></li>
            </ul>
        </nav>
    </header>

    <section class="banner">
        <h1>Bem-vindo ao ErichEDU</h1>
        <p>Conectando Alunos, Professores e Pais</p>
        <a href="#" class="btn">Baixe o App Agora</a>
    </section>

    <section class="funcionalidades">
        <h2>Funcionalidades do ErichEDU</h2>
        <p>Descubra como o ErichEDU facilita a vida escolar para todos.</p>

        <div class="cards">
            <div class="card">
                <h3>Agenda Escolar</h3>
                <p>Acompanhe as aulas e prazos de tarefas de forma fácil.</p>
            </div>
            <div class="card">
                <h3>Mensagens</h3>
                <p>Comunique-se diretamente com professores e colegas.</p>
            </div>
            <div class="card">
                <h3>Notas e Desempenho</h3>
                <p>Veja suas notas e acompanhe o progresso escolar.</p>
            </div>
        </div>
    </section>

    <footer>
        <p>© 2024 ErichEDU - Todos os direitos reservados.</p>
    </footer>

</body>
</html>
