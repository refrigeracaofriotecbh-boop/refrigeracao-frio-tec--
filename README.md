<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">

  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Refrigeração Frio Tec BH | Assistência Técnica</title>

  <meta name="description" content="Refrigeração Frio Tec BH. Manutenção e assistência técnica em geladeiras, freezers, cervejeiras, frigobares e ar-condicionado.">

  <meta name="keywords" content="refrigeração BH, conserto geladeira, manutenção freezer, cervejeira, frigobar, ar condicionado">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      font-family: Arial, Helvetica, sans-serif;
      background: #f5f8fb;
      color: #17212b;
      line-height: 1.6;
    }

    header {
      background: #071d33;
      color: white;
      position: sticky;
      top: 0;
      z-index: 1000;
      box-shadow: 0 3px 15px rgba(0,0,0,0.15);
    }

    .navbar {
      max-width: 1150px;
      margin: auto;
      padding: 18px 20px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 20px;
    }

    .logo {
      font-size: 21px;
      font-weight: bold;
      letter-spacing: .5px;
    }

    .logo span {
      color: #19a7ff;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin-left: 20px;
      font-size: 15px;
      font-weight: bold;
    }

    nav a:hover {
      color: #19a7ff;
    }

    .hero {
      background:
        linear-gradient(rgba(4,25,45,.88), rgba(4,25,45,.88)),
        radial-gradient(circle at center, #146ca3, #06192c);
      color: white;
      padding: 100px 20px;
    }

    .hero-content {
      max-width: 1150px;
      margin: auto;
      display: grid;
      grid-template-columns: 1.4fr .8fr;
      gap: 50px;
      align-items: center;
    }

    .hero h1 {
      font-size: clamp(38px, 6vw, 65px);
      line-height: 1.05;
      margin-bottom: 20px;
    }

    .hero h1 span {
      color: #20b5ff;
    }

    .hero p {
      font-size: 20px;
      max-width: 650px;
      color: #e3edf5;
      margin-bottom: 30px;
    }

    .hero-box {
      background: rgba(255,255,255,.1);
      border: 1px solid rgba(255,255,255,.2);
      padding: 35px;
      border-radius: 20px;
      backdrop-filter: blur(8px);
    }

    .hero-box h3 {
      font-size: 25px;
      margin-bottom: 15px;
    }

    .hero-box p {
      font-size: 16px;
    }

    .btn {
      display: inline-block;
      background: #18b96b;
      color: white;
      padding: 15px 25px;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
      transition: .3s;
      box-shadow: 0 8px 20px rgba(24,185,107,.25);
    }

    .btn:hover {
      transform: translateY(-3px);
      background: #119957;
    }

    .section {
      max-width: 1150px;
      margin: auto;
      padding: 80px 20px;
    }

    .section-title {
      text-align: center;
      margin-bottom: 45px;
    }

    .section-title h2 {
      font-size: 38px;
      color: #092640;
      margin-bottom: 10px;
    }

    .section-title p {
      color: #657482;
      max-width: 650px;
      margin: auto;
    }

    .services {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 22px;
    }

    .card {
      background: white;
      padding: 30px;
      border-radius: 15px;
      box-shadow: 0 8px 30px rgba(0,0,0,.07);
      border: 1px solid #e7edf2;
      transition: .3s;
    }

    .card:hover {
      transform: translateY(-6px);
      box-shadow: 0 15px 35px rgba(0,0,0,.11);
    }

    .icon {
      font-size: 42px;
      margin-bottom: 15px;
    }

    .card h3 {
      color: #092640;
      margin-bottom: 10px;
      font-size: 21px;
    }

    .card p {
      color: #63727f;
    }

    .about {
      background: white;
    }

    .about-content {
      max-width: 900px;
      margin: auto;
      text-align: center;
    }

    .about-content p {
      font-size: 18px;
      color: #596976;
      margin-bottom: 18px;
    }

    .benefits {
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      gap: 20px;
    }

    .benefit {
      background: #f8fbfd;
      padding: 25px;
      border-radius: 12px;
      text-align: center;
      border: 1px solid #e2eaf0;
    }

    .benefit strong {
      display: block;
      color: #092640;
      font-size: 18px;
      margin-bottom: 8px;
    }

    .steps {
      display: grid;
      grid-template-columns: repeat(5, 1fr);
      gap: 15px;
    }

    .step {
      text-align: center;
      background: white;
      padding: 25px 15px;
      border-radius: 12px;
      box-shadow: 0 5px 20px rgba(0,0,0,.06);
    }

    .step-number {
      width: 45px;
      height: 45px;
      display: flex;
      align-items: center;
      justify-content: center;
      background: #0a75b8;
      color: white;
      border-radius: 50%;
      margin: 0 auto 15px;
      font-weight: bold;
      font-size: 20px;
    }

    .faq {
      max-width: 850px;
      margin: auto;
    }

    details {
      background: white;
      margin-bottom: 12px;
      border-radius: 10px;
      padding: 20px;
      border: 1px solid #e3e9ee;
      box-shadow: 0 4px 15px rgba(0,0,0,.04);
    }

    summary {
      cursor: pointer;
      font-weight: bold;
      color: #092640;
      font-size: 17px;
    }

    details p {
      margin-top: 12px;
      color: #657482;
    }

    .contact {
      background: #071d33;
      color: white;
    }

    .contact .section-title h2 {
      color: white;
    }

    .contact .section-title p {
      color: #c8d7e4;
    }

    .contact-box {
      max-width: 800px;
      margin: auto;
      text-align: center;
      background: rgba(255,255,255,.07);
      padding: 45px 25px;
      border-radius: 20px;
      border: 1px solid rgba(255,255,255,.12);
    }

    .phone {
      font-size: 30px;
      font-weight: bold;
      margin: 20px 0 30px;
    }

    footer {
      background: #04111e;
      color: #9aabb9;
      text-align: center;
      padding: 30px 20px;
      font-size: 14px;
    }

    .whatsapp-float {
      position: fixed;
      right: 22px;
      bottom: 22px;
      width: 62px;
      height: 62px;
      border-radius: 50%;
      background: #18b96b;
      color: white;
      display: flex;
      align-items: center;
      justify-content: center;
      text-decoration: none;
      font-size: 30px;
      box-shadow: 0 8px 25px rgba(0,0,0,.25);
      z-index: 2000;
      transition: .3s;
    }

    .whatsapp-float:hover {
      transform: scale(1.08);
    }

    @media (max-width: 900px) {
      .hero-content {
        grid-template-columns: 1fr;
      }

      .services {
        grid-template-columns: repeat(2, 1fr);
      }

      .benefits {
        grid-template-columns: repeat(2, 1fr);
      }

      .steps {
        grid-template-columns: repeat(2, 1fr);
      }

      nav {
        display: none;
      }
    }

    @media (max-width: 600px) {
      .hero {
        padding: 70px 20px;
      }

      .hero h1 {
        font-size: 42px;
      }

      .services,
      .benefits,
      .steps {
        grid-template-columns: 1fr;
      }

      .section {
        padding: 60px 20px;
      }

      .section-title h2 {
        font-size: 30px;
      }

      .phone {
        font-size: 24px;
      }
    }
  </style>
</head>

<body>

<header>
  <div class="navbar">

    <div class="logo">
      FRIO <span>TEC</span> BH
    </div>

    <nav>
      <a href="#inicio">Início</a>
      <a href="#servicos">Serviços</a>
      <a href="#sobre">Sobre</a>
      <a href="#faq">Dúvidas</a>
      <a href="#contato">Contato</a>
    </nav>

  </div>
</header>

<main>

  <!-- INÍCIO -->
  <section class="hero" id="inicio">
    <div class="hero-content">

      <div>
        <h1>
          Refrigeração<br>
          <span>Frio Tec BH</span>
        </h1>

        <p>
          Assistência técnica em refrigeração residencial e comercial.
          Manutenção e reparos em diversos equipamentos.
        </p>

        <a
          class="btn"
          href="https://wa.me/5531973624049"
          target="_blank"
        >
          📱 CHAMAR NO WHATSAPP
        </a>
      </div>

      <div class="hero-box">
        <h3>Seu equipamento apresentou problema?</h3>

        <p>
          Entre em contato conosco pelo WhatsApp,
          explique o problema e solicite seu atendimento.
        </p>

        <br>

        <strong>📞 (31) 97362-4049</strong>
      </div>

    </div>
  </section>


  <!-- SERVIÇOS -->
  <section class="section" id="servicos">

    <div class="section-title">
      <h2>Nossos Serviços</h2>
      <p>
        Soluções em manutenção e assistência técnica
        para equipamentos de refrigeração.
      </p>
    </div>

    <div class="services">

      <div class="card">
        <div class="icon">🧊</div>
        <h3>Geladeiras</h3>
        <p>
          Manutenção, diagnóstico e reparos em geladeiras
          residenciais e comerciais.
        </p>
      </div>

      <div class="card">
        <div class="icon">❄️</div>
        <h3>Freezers</h3>
        <p>
          Manutenção e reparos em freezers para diferentes
          necessidades de refrigeração.
        </p>
      </div>

      <div class="card">
        <div class="icon">🍺</div>
        <h3>Cervejeiras</h3>
        <p>
          Diagnóstico e manutenção de cervejeiras para
          manter a refrigeração adequada.
        </p>
      </div>

      <div class="card">
        <div class="icon">🧃</div>
        <h3>Frigobares</h3>
        <p>
          Reparos e manutenção em frigobares e equipamentos
          compactos de refrigeração.
        </p>
      </div>

      <div class="card">
        <div class="icon">🌬️</div>
        <h3>Ar-Condicionado</h3>
        <p>
          Manutenção e reparos em aparelhos de
          ar-condicionado.
        </p>
      </div>

      <div class="card">
        <div class="icon">🔧</div>
        <h3>Diagnóstico e Reparos</h3>
        <p>
          Avaliação do equipamento para identificar problemas
          e buscar a melhor solução.
        </p>
      </div>

    </div>

  </section>


  <!-- SOBRE -->
  <section class="about" id="sobre">

    <div class="section">

      <div class="section-title">
        <h2>Sobre a Frio Tec BH</h2>
      </div>

      <div class="about-content">

        <p>
          A <strong>Refrigeração Frio Tec BH</strong> trabalha
          com manutenção e assistência técnica em equipamentos
          de refrigeração.
        </p>

        <p>
          Atendemos clientes que precisam de manutenção ou
          reparo em geladeiras, freezers, cervejeiras,
          frigobares e aparelhos de ar-condicionado.
        </p>

        <p>
          Nosso objetivo é oferecer um atendimento profissional,
          transparente e eficiente, buscando identificar o
          problema e apresentar a melhor solução para cada
          equipamento.
        </p>

      </div>

    </div>

  </section>


  <!-- BENEFÍCIOS -->
  <section class="section">

    <div class="section-title">
      <h2>Por que escolher a Frio Tec BH?</h2>
    </div>

    <div class="benefits">

      <div class="benefit">
        <div class="icon">🔧</div>
        <strong>Atendimento profissional</strong>
        Serviço cuidadoso e eficiente.
      </div>

      <div class="benefit">
        <div class="icon">⚙️</div>
        <strong>Experiência</strong>
        Atendimento em equipamentos de refrigeração.
      </div>

      <div class="benefit">
        <div class="icon">📱</div>
        <strong>Contato rápido</strong>
        Fale conosco pelo WhatsApp.
      </div>

      <div class="benefit">
        <div class="icon">🤝</div>
        <strong>Compromisso</strong>
        Atendimento transparente ao cliente.
      </div>

    </div>

  </section>


  <!-- COMO FUNCIONA -->
  <section class="about">

    <div class="section">

      <div class="section-title">
        <h2>Como funciona o atendimento?</h2>
      </div>

      <div class="steps">

        <div class="step">
          <div class="step-number">1</div>
          <strong>Contato</strong>
          <p>Chame pelo WhatsApp.</p>
        </div>

        <div class="step">
          <div class="step-number">2</div>
          <strong>Agendamento</strong>
          <p>Combinamos o atendimento.</p>
        </div>

        <div class="step">
          <div class="step-number">3</div>
          <strong>Avaliação</strong>
          <p>Verificamos o equipamento.</p>
        </div>

        <div class="step">
          <div class="step-number">4</div>
          <strong>Orçamento</strong>
          <p>Informamos o serviço necessário.</p>
        </div>

        <div class="step">
          <div class="step-number">5</div>
          <strong>Serviço</strong>
          <p>Realizamos o reparo aprovado.</p>
        </div>

      </div>

    </div>

  </section>


  <!-- FAQ -->
  <section class="section" id="faq">

    <div class="section-title">
      <h2>Perguntas Frequentes</h2>
    </div>

    <div class="faq">

      <details>
        <summary>Minha geladeira não está gelando. Vocês fazem esse reparo?</summary>
        <p>
          Sim. Trabalhamos com manutenção e reparos em geladeiras.
        </p>
      </details>

      <details>
        <summary>Vocês consertam freezers?</summary>
        <p>
          Sim. Realizamos manutenção e reparos em freezers.
        </p>
      </details>

      <details>
        <summary>Vocês trabalham com cervejeiras?</summary>
        <p>
          Sim. Também realizamos manutenção em cervejeiras.
        </p>
      </details>

      <details>
        <summary>Vocês trabalham com frigobares?</summary>
        <p>
          Sim. Realizamos manutenção e reparos em frigobares.
        </p>
      </details>

      <details>
        <summary>Vocês fazem manutenção em ar-condicionado?</summary>
        <p>
          Sim. Trabalhamos com manutenção e reparos em
          aparelhos de ar-condicionado.
        </p>
      </details>

      <details>
        <summary>Como solicito um orçamento?</summary>
        <p>
          Entre em contato pelo WhatsApp (31) 97362-4049,
          informe qual equipamento está apresentando problema
          e explique o que está acontecendo.
        </p>
      </details>

    </div>

  </section>


  <!-- CONTATO -->
  <section class="contact" id="contato">

    <div class="section">

      <div class="section-title">
        <h2>Fale Conosco</h2>
        <p>
          Precisa de manutenção ou assistência técnica?
          Entre em contato.
        </p>
      </div>

      <div class="contact-box">

        <h3>Refrigeração Frio Tec BH</h3>

        <div class="phone">
          📱 (31) 97362-4049
        </div>

        <p>
          Solicite seu orçamento pelo WhatsApp.
        </p>

        <br>

        <a
          class="btn"
          href="https://wa.me/5531973624049"
          target="_blank"
        >
          💬 SOLICITAR ORÇAMENTO
        </a>

      </div>

    </div>

  </section>

</main>


<footer>

  <strong>REFRIGERAÇÃO FRIO TEC BH</strong>

  <br><br>

  Assistência técnica em refrigeração

  <br>

  Geladeiras • Freezers • Cervejeiras • Frigobares • Ar-Condicionado

  <br><br>

  WhatsApp: (31) 97362-4049

  <br><br>

  © 2026 Refrigeração Frio Tec BH - Todos os direitos reservados.

</footer>


<!-- BOTÃO WHATSAPP -->
<a
  class="whatsapp-float"
  href="https://wa.me/5531973624049"
  target="_blank"
  aria-label="Falar no WhatsApp"
>
  💬
</a>

</body>
</html>
