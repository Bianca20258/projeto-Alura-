<h3>projeto-Alura</h3> 
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Betty Boop - Ícone Retrô</h1>
    <p>A eterna diva animada dos anos 30</p>
  </header>

  <nav>
    <a href="#historia">História</a>
    <a href="#quem">Quem é</a>
    <a href="#impacto">Impacto Cultural</a>
    <a href="#curiosidades">Curiosidades</a>
  </nav>

  <!-- Botão flutuante para abrir o menu -->
  <button id="btnAcessibilidade">☰</button>

  <!-- Menu lateral acessibilidade -->
  <div id="acessibilidade">
    <h3>Acessibilidade</h3>
    <button onclick="aumentarFonte()">Aumentar Fonte</button>
    <button onclick="diminuirFonte()">Diminuir Fonte</button>
    <button onclick="modoContraste()">Alto Contraste</button>
    <button onclick="modoEscuro()">Tema Escuro</button>
    <button onclick="modoLeitura()">Modo Leitura</button>
    <button onclick="resetar()">Resetar</button>
  </div>

  <main>
    <section id="historia">
      <h2>História</h2>
      <p>Betty Boop surgiu em 1930, criada por Max Fleischer, e se tornou um dos primeiros grandes símbolos femininos da animação. Inspirada nas flappers da época — mulheres ousadas e modernas —, ela encantava o público com sua voz meiga, estilo pin-up e personalidade independente.</p>
    </section>
    <section id="quem">
      <h2>Quem é Betty Boop?</h2>
      <p>Betty Boop é uma personagem animada que representa uma jovem mulher charmosa, confiante e divertida. Com seu vestido curto, voz doce e bordão "Boop-Oop-a-Doop", ela rapidamente se tornou ícone de moda e estilo.</p>
    </section>
    <section id="impacto">
      <h2>Impacto Cultural</h2>
      <p>Mais do que apenas uma personagem, Betty Boop foi pioneira em trazer temas como sensualidade, liberdade feminina e empoderamento para o cinema de animação. Ela inspirou artistas, estilistas e músicos ao longo das décadas e permanece um símbolo cultural até hoje.</p>
    </section>
    <section id="curiosidades">
      <h2>Curiosidades</h2>
      <ul>
        <li>Betty Boop foi inspirada na cantora Helen Kane.</li>
        <li>Durante os anos 30, Betty foi considerada ousada demais, sofrendo censura em vários episódios.</li>
        <li>É um dos primeiros ícones femininos a ganhar fama mundial na cultura pop.</li>
        <li>Até hoje, seu estilo retrô aparece em roupas, objetos de coleção e tatuagens.</li>
      </ul>
    </section>
  </main>

  <footer>
    <strong>Feito por Bianca Gomes</strong>.
  </footer>
</body>
</html>

