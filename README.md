# Alura---Site-Demon-Slayer-
Um site feito para aula de programação 
<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Demon Slayer - Trabalho</title>
  <style>
    :root{--bordo:#800000;--texto:#f5f5f5}
    body{font-family: Arial, Helvetica, sans-serif; margin:0; background:#111; color:#eee}
    .container{max-width:900px;margin:30px auto;padding:20px;background:rgba(0,0,0,0.6);border-radius:8px}
    header{display:flex;align-items:center;gap:18px}
    header img.logo{width:120px;height:auto}
    h1{margin:0;font-size:28px}
    p{line-height:1.5}
    /* bloco bordo sem texto */
    .bordo-block{background:var(--bordo);padding:30px 0;min-height:60px}
    .bordo-block *{display:none !important} /* garante que nenhum texto apareça */
    .gallery{display:grid;grid-template-columns:repeat(3,1fr);gap:12px;margin-top:18px}
    .gallery img{width:100%;height:160px;object-fit:cover;border-radius:6px;border:2px solid rgba(255,255,255,0.05)}
    footer{margin-top:18px;text-align:center;font-size:14px;color:#ccc}
    /* responsivo */
    @media(max-width:720px){.gallery{grid-template-columns:repeat(2,1fr)}header{flex-direction:column;align-items:flex-start}header img.logo{width:100px}}
    @media(max-width:420px){.gallery{grid-template-columns:1fr}}
  </style>
</head>
<body>
  <!-- Bloco de fundo bordo (primeiro) -->
  <div class="bordo-block" aria-hidden="true"></div>

  <div class="container">
    <!-- Logo -->
    <header>
      <img class="logo" src="https://i.postimg.cc/yYN9G7mW/59a36a307d8896102df01e7a532d42e7-1.jpg" alt="Logo Demon Slayer (Kimetsu no Yaiba)">
      <div>
        <h1>Demon Slayer (Kimetsu no Yaiba)</h1>
        <p>Este site é um trabalho sobre a série <em>Demon Slayer</em>. Abaixo tem uma breve explicação sobre o que é a história e como ela funciona, seguida por imagens da série.</p>
      </div>
    </header>

    <!-- Parágrafo explicativo -->
    <section>
      <h2>O que é e como a história funciona</h2>
      <p>
        <strong>Demon Slayer</strong> (em japonês, <em>Kimetsu no Yaiba</em>) é uma história em mangá e anime que acompanha Tanjiro Kamado, um jovem que virou caçador de demônios depois que sua família foi atacada e sua irmã, Nezuko, foi transformada em demônio. A trama mistura ação, drama e elementos sobrenaturais: os personagens treinam para dominar técnicas de espada e ataques elementais, caçam demônios perigosos e enfrentam vilões cada vez mais fortes. A narrativa costuma alternar momentos emocionais (como a relação fraternal entre Tanjiro e Nezuko) com batalhas intensas e arcos que apresentam novos personagens e inimigos.
      </p>
      <p>
        A série também explora temas como coragem, amizade, sacrifício e a luta entre o bem e o mal. Cada arco costuma ter um objetivo claro (derrotar um demônio poderoso, libertar alguém, ou descobrir segredos do passado), e os protagonistas vão se fortalecendo enquanto aprendem sobre si mesmos e sobre o mundo ao redor.
      </p>
    </section>

    <!-- Galeria com 7 imagens adicionais -->
    <section>
      <h2>Imagens da série</h2>
      <div class="gallery">
        <img src="https://i.postimg.cc/7LSTzhkt/81c79cb8cfcb320fb7890403fc9bc81d.jpg" alt="Demon Slayer - logo alternativa" />
        <img src="https://i.postimg.cc/nhyDM76Q/c2567392377c09fc5dbe52aabadd5dd3.jpg" alt="Zenitsu e Inosuke " />
        <img src="https://i.postimg.cc/7ZGzxXQk/8a32d145d0a78cab1dee7e4fbed5ab07.jpg" alt="Tomioka e Tanjiro" />
        <img src="https://i.postimg.cc/SsqYf4QS/c4f5692fa1ee298c010264d9cfcf5437.jpg" alt="Hashiras" />
        <img src="https://i.postimg.cc/RFR6PYqc/c006ca91a4dbddf73edfaab007027b7c.jpg" alt="Melhor Luta (segunda tenporada)" />
        <img src="https://i.postimg.cc/kXh83Lss/35f2c0efe2d3c18e40af9f8591dccc97.jpg" alt="Amiguinhos" />
        <img src="https://i.postimg.cc/G9nrwL4V/ffac0c1a0fe68408405d8a1854167377.jpg" alt="Tomioka" />
        <img src="https://i.postimg.cc/GmJ3RyJQ/b385e8ba70430b376337379a24bc8f0a.jpg" alt="Irmãozinhos" />
         </div>
     
    <footer>
      <p>Trabalho para a Alura — Demon Slayer (Kimetsu no Yaiba)</p>
    </footer>
  </div>

  <!-- Bloco de fundo bordo (último) -->
  <div class="bordo-block" aria-hidden="true"></div>

</body>
</html>
<!-- Parágrafo explicativo -->
<section>
  <h2>O que é e como a história funciona</h2>
  <p>
    <strong>Demon Slayer</strong> (em japonês, <em>Kimetsu no Yaiba</em>) é uma história em mangá e anime que acompanha Tanjiro Kamado, um jovem que virou caçador de demônios depois que sua família foi atacada e sua irmã, Nezuko, foi transformada em demônio. A trama mistura ação, drama e elementos sobrenaturais: os personagens treinam para dominar técnicas de espada e ataques elementais, caçam demônios perigosos e enfrentam vilões cada vez mais fortes. A narrativa costuma alternar momentos emocionais (como a relação fraternal entre Tanjiro e Nezuko) com batalhas intensas e arcos que apresentam novos personagens e inimigos.
  </p>
  <p>
    A série também explora temas como coragem, amizade, sacrifício e a luta entre o bem e o mal. Cada arco costuma ter um objetivo claro (derrotar um demônio poderoso, libertar alguém, ou descobrir segredos do passado), e os protagonistas vão se fortalecendo enquanto aprendem sobre si mesmos e sobre o mundo ao redor.
  </p>
</section>

<!-- Galeria com 7 imagens adicionais -->
<section>
  <h2>Imagens da série</h2>
  <div class="gallery">
    <img src="https://i.postimg.cc/7LSTzhkt/81c79cb8cfcb320fb7890403fc9bc81d.jpg" alt="Demon Slayer - logo alternativa" />
    <img src="https://i.postimg.cc/nhyDM76Q/c2567392377c09fc5dbe52aabadd5dd3.jpg" alt="Zenitsu e Inosuke " />
    <img src="https://i.postimg.cc/7ZGzxXQk/8a32d145d0a78cab1dee7e4fbed5ab07.jpg" alt="Tomioka e Tanjiro" />
    <img src="https://i.postimg.cc/SsqYf4QS/c4f5692fa1ee298c010264d9cfcf5437.jpg" alt="Hashiras" />
    <img src="https://i.postimg.cc/RFR6PYqc/c006ca91a4dbddf73edfaab007027b7c.jpg" alt="Melhor Luta (segunda tenporada)" />
    <img src="https://i.postimg.cc/kXh83Lss/35f2c0efe2d3c18e40af9f8591dccc97.jpg" alt="Amiguinhos" />
    <img src="https://i.postimg.cc/G9nrwL4V/ffac0c1a0fe68408405d8a1854167377.jpg" alt="Tomioka" />
    <img src="https://i.postimg.cc/GmJ3RyJQ/b385e8ba70430b376337379a24bc8f0a.jpg" alt="Irmãozinhos" />
     </div>
 
<footer>
  <p>Trabalho para a Alura — Demon Slayer (Kimetsu no Yaiba)</p>
</footer>
