<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Meu Portfólio no GitHub</title>
  <style>
    :root {
      --bg-color: #0e0e0e;
      --text-color: #f1f1f1;
      --accent-color: #00bcd4;
      --secondary-color: #1a1a1a;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: var(--bg-color);
      color: var(--text-color);
      line-height: 1.6;
    }

    header {
      background-color: var(--secondary-color);
      padding: 2rem 1rem;
      text-align: center;
    }

    header img {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      border: 3px solid var(--accent-color);
      margin-bottom: 1rem;
    }

    header h1 {
      font-size: 2.5rem;
    }

    header p {
      font-size: 1.1rem;
      color: #ccc;
    }

    main {
      max-width: 900px;
      margin: 2rem auto;
      padding: 0 1rem;
    }

    section {
      margin-bottom: 3rem;
    }

    h2 {
      font-size: 1.8rem;
      margin-bottom: 1rem;
      color: var(--accent-color);
      border-left: 5px solid var(--accent-color);
      padding-left: 10px;
    }

    .skills {
      display: flex;
      flex-wrap: wrap;
      gap: 1rem;
    }

    .skill {
      background-color: var(--secondary-color);
      padding: 0.75rem 1.5rem;
      border-radius: 5px;
      font-weight: bold;
      color: var(--text-color);
      box-shadow: 0 0 5px #00000055;
    }

    .projects-btn {
      display: inline-block;
      margin-top: 2rem;
      padding: 1rem 2rem;
      background-color: var(--accent-color);
      color: #000;
      font-weight: bold;
      text-decoration: none;
      border-radius: 5px;
      transition: background 0.3s ease;
    }

    .projects-btn:hover {
      background-color: #00acc1;
    }

    footer {
      text-align: center;
      padding: 2rem 1rem;
      background-color: var(--secondary-color);
      color: #aaa;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 2rem;
      }

      .skills {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
</head>
<body>

  <header>
    <!-- Substitua a imagem abaixo pela sua foto de perfil -->
    <img src="https://via.placeholder.com/120" alt="Minha foto de perfil" />
    <h1>Olá, eu sou [Seu Nome]</h1>
    <p>Desenvolvedor apaixonado por tecnologia, código limpo e boas ideias.</p>
  </header>

  <main>
    <section>
      <h2>🧑‍💻 Sobre mim</h2>
      <p>Sou desenvolvedor com experiência em projetos web e backend, sempre buscando aprender novas tecnologias e criar soluções criativas. Meu foco é escrever código eficiente, organizado e fácil de manter. Aqui no GitHub, compartilho meus estudos, ferramentas e projetos abertos para o mundo.</p>
    </section>

    <section>
      <h2>🛠️ Linguagens e Ferramentas</h2>
      <div class="skills">
        <div class="skill">HTML</div>
        <div class="skill">CSS</div>
        <div class="skill">JavaScript</div>
        <div class="skill">Python</div>
        <div class="skill">React</div>
        <div class="skill">Node.js</div>
        <div class="skill">TypeScript</div>
        <div class="skill">Git</div>
        <div class="skill">SQL</div>
        <div class="skill">Docker</div>
      </div>
    </section>

    <section>
      <h2>📂 Projetos</h2>
      <p>Confira meus repositórios públicos, com projetos pessoais, estudos e contribuições para a comunidade.</p>
      <a class="projects-btn" href="https://github.com/SEU_USUARIO?tab=repositories" target="_blank">Ver meus projetos</a>
    </section>
  </main>

  <footer>
    <p>© 2025 - Criado por [Seu Nome] | <a href="mailto:seuemail@exemplo.com" style="color: #00bcd4;">Contato</a></p>
  </footer>

</body>
</html>
