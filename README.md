<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Portfólio - José Marcos</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      background: linear-gradient(90deg, #2c5364, #203a43, #0f2027);
      color: #fff;
      padding-top: 70px;
      line-height: 1.5;
    }

    header {
      position: fixed;
      top: 0;
      width: 100%;
      background: #0f2027;
      padding: 15px 30px;
      display: flex;
      justify-content: center;
      gap: 30px;
    }

    header h1 {
      position: absolute;
      left: 30px;
      color: #00ffc8;
      font-size: 1.5rem;
    }

    nav a {
      color: #00ffc8;
      text-decoration: none;
      font-weight: 600;
      font-size: 1rem;
    }

    nav a:hover {
      text-decoration: underline;
    }

    section {
      max-width: 900px;
      margin: 40px auto;
      padding: 0 15px;
      text-align: center;
    }

    #hero h1 {
      font-size: 2.5rem;
      margin-bottom: 10px;
      color: #00ffc8;
    }

    #hero h2 {
      font-weight: 400;
      margin-bottom: 15px;
    }

    #hero p {
      color: #c4f1f9;
      margin-bottom: 20px;
    }

    #hero a {
      display: inline-block;
      background: #00ffc8;
      color: #022;
      font-weight: 700;
      padding: 10px 24px;
      border-radius: 20px;
      text-decoration: none;
    }

    #about {
      background: #12232e;
      border-radius: 10px;
      padding: 25px;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
      text-align: left;
    }

    #about img {
      width: 220px;
      border-radius: 10px;
    }

    .about-text {
      max-width: 560px;
      color: #a1d9d1;
    }

    .about-text h2 {
      color: #00ffc8;
      margin-bottom: 10px;
    }

    #skills h2, #projects h2 {
      color: #00ffc8;
      margin-bottom: 25px;
    }

    .skills-list {
      display: flex;
      flex-wrap: wrap;
      gap: 15px;
      justify-content: center;
    }

    .skill-item {
      background: #1b2c36;
      padding: 15px;
      border-radius: 8px;
      width: 170px;
      color: #a1d9d1;
      text-align: center;
    }

    .skill-item h3 {
      color: #00ffc8;
      margin-bottom: 8px;
      font-size: 1.1rem;
    }

    .projects-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 20px;
    }

    .project-card {
      background: #1b2c36;
      border-radius: 10px;
      overflow: hidden;
    }

    .project-card img {
      width: 100%;
      height: 150px;
      object-fit: cover;
    }

    .project-info {
      padding: 12px;
      text-align: left;
    }

    .project-info h3 {
      color: #00ffc8;
      margin-bottom: 8px;
      font-size: 1.1rem;
    }

    .project-info p {
      color: #a1d9d1;
      font-size: 0.95rem;
      margin-bottom: 10px;
    }

    .project-info a {
      color: #00ffc8;
      border: 1px solid #00ffc8;
      padding: 6px 10px;
      border-radius: 6px;
      text-decoration: none;
      font-size: 0.9rem;
    }

    footer {
      margin: 50px 0 20px;
      text-align: center;
      color: #a1d9d1;
    }

    footer a {
      color: #00ffc8;
      text-decoration: none;
      margin: 0 5px;
    }

    @media (max-width: 700px) {
      #about {
        flex-direction: column;
        text-align: center;
      }

      .about-text {
        max-width: 100%;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>José Marcos</h1>
    <nav>
      <a href="#hero">Home |</a>
      <a href="#about">Sobre |</a>
      <a href="#skills">Conhecimentos |</a>
      <a href="#projects">Projetos </a>
    </nav>
  </header>

  <section id="hero">
    <h2>Olá, eu sou</h2>
    <h1>José Marcos de Sousa</h1>
    <p>Sou estudante de Análise e Desenvolvimento de Sistemas, apaixonado por criar soluções eficientes. Estou sempre buscando aprender e crescer na área de tecnologia, focando no desenvolvimento de habilidades práticas.</p>
    <a href="#projects">Ver meus projetos</a>
  </section>

  <section id="about">
    <img src="foto.jpg" alt="Foto de José Marcos" />
    <div class="about-text">
      <h2>Sobre Mim</h2>
      <p>Atualmente trabalho como Analista de Controle Operacional e Key User em um CCO portuário. Tenho grande interesse por tecnologia e estou sempre em busca de crescimento profissional.
Aplico os conhecimentos que venho adquirindo em Python, HTML, CSS e JavaScript para desenvolver pequenas soluções e projetos voltados à otimização de rotinas e melhoria de processos.
Essa combinação entre a operação e a tecnologia me permite enxergar oportunidades reais de melhoria, sempre com foco em eficiência, simplicidade e usabilidade.</p>
    </div>
  </section>

  <section id="skills">
    <h2>Conhecimentos</h2>
    <div class="skills-list">
      <div class="skill-item">
        <h3>Python</h3>
        <p>Estudo Python com foco em lógica de programação e automações simples.</p>
      </div>
      <div class="skill-item">
        <h3>HTML & CSS</h3>
        <p>Tenho domínio básico e consigo criar páginas simples, responsivas e bem estruturadas.</p>
      </div>
      <div class="skill-item">
        <h3>JavaScript</h3>
        <p>Estou em processo de aprendizado, iniciando a desenvolver paginas simples e intuitivas.</p>
      </div>
      <div class="skill-item">
        <h3>Motivação para Aprender</h3>
        <p>Estou sempre buscando evoluir com dedicação e prática diária.</p>
      </div>
    </div>
  </section>

  <section id="projects">
    <h2>Projetos em Destaque</h2>
    <div class="projects-grid">
      <div class="project-card">
        <img src="diário.png" alt="Aplicativo Diário Simples" />
        <div class="project-info">
          <h3>Aplicativo Diário Simples</h3>
          <p>Um app para registrar pensamentos e atividades diárias com interface simples e intuitiva que facilita a usabilidade do usuário.</p>
          <a href="#">Ver Projeto</a>
        </div>
      </div>

      <div class="project-card">
        <img src="BuyList.jpg" alt="Lista de Compras" />
        <div class="project-info">
          <h3>Lista de Compras</h3>
          <p>Aplicação web para gerenciar listas de compras, com cadastro e remoção de itens.</p>
          <a href="#">Ver Projeto</a>
        </div>
      </div>

      <div class="project-card">
        <img src="form.jpg" alt="Formulário de Contato" />
        <div class="project-info">
          <h3>Formulário de Contato</h3>
          <p>Formulário com HTML e CSS, para envio de mensagens reais.</p>
          <a href="#">Ver Projeto</a>
        </div>
      </div>

      <div class="project-card">
        <img src="login_screen.jpg" alt="Login Simples" />
        <div class="project-info">
          <h3>Login Simples</h3>
          <p>Uma tela de login com HTML e CSS, ideal para autenticação básica em páginas web.</p>
          <a href="#">Ver Projeto</a>
        </div>
      </div>

      <div class="project-card">
        <img src="form-simples.jpg" alt="Formulário de Cadastro" />
        <div class="project-info">
          <h3>Formulário de Cadastro</h3>
          <p>Formulário com campos de entrada interativos, feito com HTML e CSS.</p>
          <a href="#">Ver Projeto</a>
        </div>
      </div>
    </div>
  </section>

  <footer>
    <p>Desenvolvido por José Marcos - © 2025</p>
    <p>
      <a href="https://github.com/seuusuario" target="_blank">GitHub</a> | 
      <a href="mailto:seuemail@dominio.com">Email</a>
    </p>
  </footer>

</body>
</html>
