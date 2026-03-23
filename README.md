Aqui está um site completo em **um único arquivo HTML com CSS interno**, com design moderno em **dark mode com detalhes em azul**:

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfólio - Fernando Almeida</title>
  <style>
    :root {
      --bg: #0f172a;
      --card: #1e293b;
      --primary: #3b82f6;
      --text: #e2e8f0;
      --muted: #94a3b8;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background: var(--bg);
      color: var(--text);
      line-height: 1.6;
    }

    header {
      background: #020617;
      padding: 15px 30px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      position: sticky;
      top: 0;
    }

    header h1 {
      color: var(--primary);
      font-size: 20px;
    }

    nav a {
      color: var(--text);
      margin-left: 20px;
      text-decoration: none;
      transition: 0.3s;
    }

    nav a:hover {
      color: var(--primary);
    }

    section {
      padding: 60px 30px;
      max-width: 1000px;
      margin: auto;
    }

    .intro {
      text-align: center;
    }

    .intro h2 {
      font-size: 32px;
      margin-bottom: 10px;
    }

    .intro p {
      color: var(--muted);
      margin-bottom: 20px;
    }

    .btn {
      display: inline-block;
      padding: 10px 20px;
      background: var(--primary);
      color: white;
      border-radius: 5px;
      text-decoration: none;
      transition: 0.3s;
    }

    .btn:hover {
      background: #2563eb;
    }

    .card {
      background: var(--card);
      padding: 20px;
      margin-top: 20px;
      border-radius: 10px;
      transition: 0.3s;
    }

    .card:hover {
      transform: translateY(-5px);
    }

    .skills {
      display: flex;
      gap: 20px;
      flex-wrap: wrap;
    }

    .skill {
      flex: 1;
      min-width: 200px;
      text-align: center;
      padding: 20px;
      background: var(--card);
      border-radius: 10px;
    }

    footer {
      text-align: center;
      padding: 30px;
      background: #020617;
      margin-top: 40px;
    }

    .social i {
      margin: 0 10px;
      font-style: normal;
      cursor: pointer;
      transition: 0.3s;
    }

    .social i:hover {
      color: var(--primary);
    }
  </style>
</head>
<body>

  <header>
    <h1>Fernando Almeida</h1>
    <nav>
      <a href="#sobre">Sobre</a>
      <a href="#formacao">Formação</a>
      <a href="#projetos">Projetos</a>
      <a href="#contato">Contato</a>
    </nav>
  </header>

  <section class="intro" id="sobre">
    <h2>Olá, eu sou Fernando</h2>
    <p>Estudante do 1º semestre de Análise e Desenvolvimento de Sistemas (ADS).</p>
    <a href="#contato" class="btn">Entrar em Contato</a>
  </section>

  <section>
    <h2>Habilidades</h2>
    <div class="skills">
      <div class="skill">HTML</div>
      <div class="skill">CSS</div>
      <div class="skill">Lógica de Programação</div>
    </div>
  </section>

  <section id="formacao">
    <h2>Formação</h2>
    <div class="card">
      <p>Estudante de Análise e Desenvolvimento de Sistemas (ADS)</p>
      <p>Instituição: Uninassau</p>
      <p>1º semestre</p>
    </div>
  </section>

  <section id="projetos">
    <h2>Projetos</h2>
    <div class="card">
      <p>Em breve...</p>
    </div>
  </section>

  <section id="contato">
    <h2>Contato</h2>
    <div class="card">
      <p>Email: almeidafernando05802@gmail.com</p>
    </div>
  </section>

  <footer>
    <p>© 2026 Fernando da Silva Almeida</p>
    <div class="social">
      <i>🌐</i>
      <i>🐦</i>
      <i>📸</i>
      <i>💼</i>
    </div>
  </footer>

</body>
</html>
```



