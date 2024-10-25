<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfólio Interativo de Abner Cezar</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div id="container">
        <header>
            <h1>Abner Cezar 🚀</h1>
            <button id="flip">Vire-me!</button>
        </header>
        
        <main>
            <section id="about">
                <h2>Sobre mim</h2>
                <p>Desenvolvedor full-stack apaixonado por criar soluções inovadoras.</p>
            </section>

            <section id="projects" class="hidden">
                <h2>Meus Projetos</h2>
                <div id="project-grid"></div>
            </section>

            <section id="skills" class="hidden">
                <h2>Habilidades</h2>
                <ul>
                    <li>Laravel</li>
                    <li>Vue.js</li>
                    <li>PHP</li>
                    <li>Python</li>
                    <li>JavaScript</li>
                </ul>
            </section>
        </main>

        <footer>
            <h3>Obrigado por visitar! 😊</h3>
            <button onclick="showStats()">Ver Estatísticas</button>
        </footer>
    </div>

    <script src="script.js"></script>
</body>
</html>
