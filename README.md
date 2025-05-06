<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Portfólio - Luiza Macêdo</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet">
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Inter', sans-serif;
        }

        body {
            background: radial-gradient(circle at top left, #eef2ff, #ffffff);
            color: #1a1a1a;
            line-height: 1.6;
        }

        header {
            background: linear-gradient(to right, #4f46e5, #3b82f6);
            color: #fff;
            padding: 4rem 2rem;
            text-align: center;
            clip-path: ellipse(150% 100% at 50% 0%);
        }

        header h1 {
            font-size: 3rem;
            font-weight: 800;
        }

        header p {
            font-size: 1.2rem;
            font-weight: 400;
            margin-top: 0.5rem;
            color: #e0e7ff;
        }

        nav {
            background-color: #fff;
            padding: 1rem;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 100;
            border-bottom: 2px solid #e5e7eb;
        }

        nav a {
            margin: 0 1rem;
            color: #4f46e5;
            text-decoration: none;
            font-weight: 600;
            transition: all 0.3s;
        }

        nav a:hover {
            color: #1e3a8a;
            transform: scale(1.05);
        }

        section {
            max-width: 1000px;
            margin: 3rem auto;
            padding: 2rem;
            background: #ffffffcc;
            border-radius: 16px;
            backdrop-filter: blur(8px);
            box-shadow: 0 8px 30px rgba(0, 0, 0, 0.05);
            animation: fadeIn 1s ease forwards;
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(20px);
            }

            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        section h2 {
            font-size: 2rem;
            margin-bottom: 1rem;
            color: #1e3a8a;
        }

        .project-list {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 1.5rem;
        }

        .project-card {
            background: #f1f5ff;
            border-radius: 12px;
            padding: 1.5rem;
            transition: transform 0.3s ease;
            box-shadow: 0 4px 14px rgba(0, 0, 0, 0.1);
            border-left: 5px solid #4f46e5;
        }

        .project-card:hover {
            transform: translateY(-5px);
        }

        .project-card h3 {
            font-size: 1.25rem;
            margin-bottom: 0.5rem;
        }

        .project-card p {
            font-size: 0.95rem;
            color: #444;
        }

        ul {
            padding-left: 1.5rem;
            margin-top: 0.5rem;
        }

        li {
            margin-bottom: 0.75rem;
        }

        a {
            color: #4f46e5;
        }

        footer {
            text-align: center;
            padding: 2rem;
            font-size: 0.9rem;
            color: #666;
            background: #e5e7eb;
            margin-top: 3rem;
        }
    </style>
</head>

<body>
    <header>
        <h1>Luiza Macêdo</h1>
        <p>UX/UI Designer • Estudante de Design na UNOPAR • Formada pela Awari</p>
    </header>

    <nav>
        <a href="#sobre">Sobre</a>
        <a href="#projetos">Projetos</a>
        <a href="#estudos">Estudos de Caso</a>
        <a href="#experiencia">Experiência</a>
        <a href="#skills">Skills</a>
        <a href="#certificados">Certificados</a>
        <a href="#contato">Contato</a>
    </nav>

    <section id="sobre">
        <h2>Sobre mim</h2>
        <p>
            Sou uma designer com foco em UX/UI, apaixonada por criar experiências digitais intuitivas e acessíveis.
            Tenho experiência prática em design de interfaces, design systems, acessibilidade (WCAG), heurísticas de
            Nielsen e prototipagem no Figma. Já atuei em projetos web e mobile usando metodologias ágeis. Estou em
            constante evolução profissional, buscando sempre melhorar minhas habilidades com foco no usuário.
        </p>
    </section>

    <section id="projetos">
        <h2>Projetos</h2>
        <div class="project-list">
            <div class="project-card">
                <h3>Redesign do Globoplay</h3>
                <p>Estudo de caso focado na usabilidade e hierarquia visual. Feito no Figma com foco em navegação e
                    jornada do usuário.</p>
            </div>
            <div class="project-card">
                <h3>Landing Page - Awari</h3>
                <p>Interface responsiva com foco em acessibilidade e testes via Maze.</p>
            </div>
        </div>
    </section>

    <section id="estudos">
        <h2>Estudos de Caso</h2>
        <div class="project-list">
            <div class="project-card">
                <h3>Redesign do Globoplay</h3>
                <p>Este estudo teve como foco principal melhorar a usabilidade da plataforma, utilizando heurísticas de
                    Nielsen, entrevistas com usuários, criação de personas e protótipos navegáveis no Figma. O resultado
                    foi uma interface mais intuitiva e acessível, com navegação otimizada para diferentes públicos.</p>
            </div>
        </div>
    </section>

    <section id="experiencia">
        <h2>Experiência Profissional</h2>
        <ul>
            <li><strong>UI Designer - Pagie Portal</strong> (Jan 2023 - Jul 2023)<br />Criação de interfaces web/mobile,
                adaptação mobile-first, uso de Trello e aplicação de feedbacks de testes.</li>
            <li><strong>UI Designer - Battle Damage</strong> (Dez 2024 - Fev 2025)<br />Design para produto gamer,
                manutenção de design system, wireframes e protótipos no Figma.</li>
        </ul>
    </section>

    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>Figma, Miro, Maze, Trello, Notion, Google Forms, Hotjar</li>
            <li>HTML/CSS (básico), Design Systems</li>
            <li>Acessibilidade (WCAG), Heurísticas de Nielsen</li>
            <li>Wireframes e protótipos (baixa e alta fidelidade)</li>
            <li>UX Writing básico</li>
            <li>Comunicação clara, criatividade, colaboração, proatividade e organização</li>
            <li>Português (nativo), Inglês (fluente), Espanhol (básico), Francês (básico)</li>
        </ul>
    </section>

    <section id="certificados">
        <h2>Cursos e Certificados</h2>
        <ul>
            <li>Formação em UX/UI Design - Awari</li>
            <li>UX - NTT Data</li>
            <li>Design Rules: Principles + Practices for Great UI Design - Udemy</li>
        </ul>
    </section>

    <section id="contato">
        <h2>Contato</h2>
        <p>Email: <a href="mailto:ludefranca03@hotmail.com">ludefranca03@hotmail.com</a></p>
        <p>Telefone: (81) 98575-9910</p>
    </section>

    <footer>
        <p>&copy; 2025 Luiza Macêdoo. Todos os direitos reservados.</p>
    </footer>
</body>

</html>
