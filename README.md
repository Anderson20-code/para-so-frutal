[index.html](https://github.com/user-attachments/files/34085213/index.html)# paraíso-frutal
Curiosidades y pasos para elaborar conservas frutales.

[Uploadin<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Descubre las conservas frutales: sabor, tradición y aprovechamiento de la fruta.">
  <title>Paraíso Frutal | Fruit Preserves</title>
  <style>
    :root{--green:#245b43;--leaf:#6f9e55;--cream:#fff8e9;--orange:#efaa49;--ink:#25352c;--pink:#f6d6c8}
    *{box-sizing:border-box}
    html{scroll-behavior:smooth}
    body{margin:0;font-family:Arial,Helvetica,sans-serif;background:var(--cream);color:var(--ink);line-height:1.6}
    header{background:linear-gradient(120deg,#245b43ee,#6f9e55dd),radial-gradient(circle at top right,#f6d6c8,transparent 45%);color:white;padding:22px 6% 70px}
    nav{display:flex;justify-content:space-between;align-items:center;gap:16px;flex-wrap:wrap}
    .brand{font-weight:800;font-size:1.15rem;letter-spacing:.3px}
    .navlinks{display:flex;gap:16px;flex-wrap:wrap}
    a{color:inherit}
    .navlinks a{text-decoration:none;font-weight:700}
    .lang{border:1px solid #ffffff99;background:#ffffff18;color:white;padding:9px 13px;border-radius:20px;cursor:pointer;font-weight:700}
    .hero{max-width:900px;margin:64px auto 0;text-align:center}
    .hero h1{font-size:clamp(2.3rem,6vw,4.5rem);line-height:1.05;margin:0 0 18px}
    .hero p{font-size:1.15rem;max-width:680px;margin:0 auto 25px}
    .button{display:inline-block;background:var(--orange);color:#302819;text-decoration:none;padding:12px 20px;border-radius:25px;font-weight:800;border:0;cursor:pointer}
    main{max-width:1100px;margin:auto;padding:36px 22px 70px}
    section{padding:35px 0;scroll-margin-top:20px}
    h2{color:var(--green);font-size:clamp(1.7rem,4vw,2.4rem);line-height:1.2}
    .intro{max-width:800px}
    .cards{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:18px}
    .card{background:white;border-radius:18px;padding:22px;box-shadow:0 8px 22px #294d3210;border:1px solid #e7e2d3}
    .emoji{font-size:2.5rem}
    .steps{counter-reset:step;display:grid;grid-template-columns:repeat(auto-fit,minmax(190px,1fr));gap:14px}
    .step{background:#edf3e8;padding:18px;border-radius:14px}
    .step strong{display:block;color:var(--green);font-size:1.08rem;margin-bottom:5px}
    .two-col{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:24px;align-items:start}
    .note{background:#fff0d7;border-left:5px solid var(--orange);padding:17px 19px;border-radius:8px}
    .qrbox{text-align:center;background:white;padding:24px;border-radius:18px;border:1px dashed #91a98b}
    #qr{width:190px;height:190px;max-width:100%;object-fit:contain;margin:10px auto;display:block}
    .small{font-size:.92rem;color:#536158}
    footer{background:var(--green);color:white;padding:30px 6%;text-align:center}
    .editbar{position:sticky;bottom:0;background:#fffdf5;border-top:1px solid #ded7c5;padding:12px 18px;display:flex;gap:10px;justify-content:center;align-items:center;flex-wrap:wrap;z-index:10}
    .editbar button{border:0;border-radius:20px;padding:10px 15px;font-weight:700;cursor:pointer}
    .editbtn{background:var(--green);color:white}.savebtn{background:var(--orange);color:#302819}
    [contenteditable="true"]{outline:2px dashed #efaa49;outline-offset:3px;border-radius:3px}
    @media(max-width:600px){header{padding-bottom:48px}.hero{margin-top:42px}.navlinks{gap:10px}.navlinks a{font-size:.92rem}}
  </style>
</head>
<body>
<header>
  <nav>
    <div class="brand">🍑 Paraíso Frutal</div>
    <div class="navlinks">
      <a href="#about" data-es="Conócenos" data-en="About">Conócenos</a>
      <a href="#benefits" data-es="Beneficios" data-en="Benefits">Beneficios</a>
      <a href="#process" data-es="Proceso" data-en="Process">Proceso</a>
      <a href="#qr-section" data-es="Código QR" data-en="QR code">Código QR</a>
    </div>
    <button class="lang" id="langBtn" type="button">English</button>
  </nav>
  <div class="hero">
    <h1 data-es="El sabor de la fruta, todo el año" data-en="The taste of fruit, all year round">El sabor de la fruta, todo el año</h1>
    <p data-es="Descubre las conservas frutales: una forma deliciosa de aprovechar frutas de temporada y convertirlas en algo especial." data-en="Discover fruit preserves: a delicious way to make the most of seasonal fruit and turn it into something special.">Descubre las conservas frutales: una forma deliciosa de aprovechar frutas de temporada y convertirlas en algo especial.</p>
    <a class="button" href="#about" data-es="Explorar la página" data-en="Explore the website">Explorar la página</a>
  </div>
</header>

<main>
  <section id="about" class="intro">
    <h2 data-es="¿Qué son las conservas frutales?" data-en="What are fruit preserves?">¿Qué son las conservas frutales?</h2>
    <p data-es="Son preparaciones hechas con frutas que se cocinan, normalmente con azúcar y a veces con jugo de limón, para obtener una mermelada o conserva. Si se preparan y almacenan correctamente, pueden durar más que la fruta fresca." data-en="Fruit preserves are made by cooking fruit, usually with sugar and sometimes lemon juice, to make jam or preserves. When prepared and stored correctly, they can last longer than fresh fruit.">Son preparaciones hechas con frutas que se cocinan, normalmente con azúcar y a veces con jugo de limón, para obtener una mermelada o conserva. Si se preparan y almacenan correctamente, pueden durar más que la fruta fresca.</p>
    <p data-es="Nuestro proyecto, “Paraíso Frutal”, busca valorar las frutas de temporada, aprender sobre su preparación y reducir el desperdicio de alimentos." data-en="Our project, “Fruitful Paradise,” celebrates seasonal fruit, teaches how preserves are made, and encourages reducing food waste.">Nuestro proyecto, “Paraíso Frutal”, busca valorar las frutas de temporada, aprender sobre su preparación y reducir el desperdicio de alimentos.</p>
  </section>

  <section id="benefits">
    <h2 data-es="Beneficios de las conservas" data-en="Benefits of fruit preserves">Beneficios de las conservas</h2>
    <div class="cards">
      <article class="card"><div class="emoji">🍊</div><h3 data-es="Aprovechan la fruta" data-en="Make use of fruit">Aprovechan la fruta</h3><p data-es="Ayudan a utilizar fruta madura que todavía está en buenas condiciones." data-en="They help use ripe fruit that is still in good condition.">Ayudan a utilizar fruta madura que todavía está en buenas condiciones.</p></article>
      <article class="card"><div class="emoji">🫙</div><h3 data-es="Más tiempo para disfrutar" data-en="Enjoy it for longer">Más tiempo para disfrutar</h3><p data-es="Un proceso correcto y un almacenamiento seguro ayudan a conservar el producto." data-en="A correct process and safe storage help preserve the product.">Un proceso correcto y un almacenamiento seguro ayudan a conservar el producto.</p></article>
      <article class="card"><div class="emoji">🌱</div><h3 data-es="Menos desperdicio" data-en="Less food waste">Menos desperdicio</h3><p data-es="Aprovechar frutas de temporada puede reducir el desperdicio de alimentos." data-en="Using seasonal fruit can help reduce food waste.">Aprovechar frutas de temporada puede reducir el desperdicio de alimentos.</p></article>
    </div>
  </section>

  <section id="fruits">
    <h2 data-es="Frutas que podemos utilizar" data-en="Fruits we can use">Frutas que podemos utilizar</h2>
    <div class="cards">
      <article class="card"><div class="emoji">🥭</div><h3 data-es="Mango" data-en="Mango">Mango</h3><p data-es="Aporta un sabor dulce y tropical." data-en="Adds a sweet, tropical flavor.">Aporta un sabor dulce y tropical.</p></article>
      <article class="card"><div class="emoji">🍓</div><h3 data-es="Fresa" data-en="Strawberry">Fresa</h3><p data-es="Ideal para una conserva de color intenso y aroma agradable." data-en="Great for preserves with a bright color and pleasant aroma.">Ideal para una conserva de color intenso y aroma agradable.</p></article>
      <article class="card"><div class="emoji">🍍</div><h3 data-es="Piña" data-en="Pineapple">Piña</h3><p data-es="Tiene un sabor fresco y ligeramente ácido." data-en="Has a fresh, slightly tangy flavor.">Tiene un sabor fresco y ligeramente ácido.</p></article>
      <article class="card"><div class="emoji">🍑</div><h3 data-es="Durazno" data-en="Peach">Durazno</h3><p data-es="Su textura suave funciona bien en preparaciones dulces." data-en="Its soft texture works well in sweet preserves.">Su textura suave funciona bien en preparaciones dulces.</p></article>
    </div>
  </section>

  <section id="process">
    <h2 data-es="¿Cómo se preparan?" data-en="How are they made?">¿Cómo se preparan?</h2>
    <div class="steps">
      <div class="step"><strong data-es="1. Limpiar" data-en="1. Clean">1. Limpiar</strong><span data-es="Lavar las manos, los utensilios y la fruta." data-en="Wash hands, utensils, and fruit.">Lavar las manos, los utensilios y la fruta.</span></div>
      <div class="step"><strong data-es="2. Preparar" data-en="2. Prepare">2. Preparar</strong><span data-es="Retirar las partes dañadas y cortar la fruta." data-en="Remove damaged parts and cut the fruit.">Retirar las partes dañadas y cortar la fruta.</span></div>
      <div class="step"><strong data-es="3. Cocinar" data-en="3. Cook">3. Cocinar</strong><span data-es="Cocinar la fruta con azúcar, siguiendo una receta confiable." data-en="Cook the fruit with sugar, following a reliable recipe.">Cocinar la fruta con azúcar, siguiendo una receta confiable.</span></div>
      <div class="step"><strong data-es="4. Envasar con seguridad" data-en="4. Jar safely">4. Envasar con seguridad</strong><span data-es="Usar frascos preparados correctamente y seguir las indicaciones de conservación." data-en="Use properly prepared jars and follow safe preservation instructions.">Usar frascos preparados correctamente y seguir las indicaciones de conservación.</span></div>
    </div>
    <p class="note" data-es="Importante: esta página es informativa. Para guardar conservas a temperatura ambiente, sigue una receta probada y recomendaciones oficiales de seguridad alimentaria. No pruebes ni consumas frascos con señales de deterioro." data-en="Important: this page is for information only. For shelf-stable preserves, follow a tested recipe and official food-safety guidance. Do not taste or eat jars that show signs of spoilage.">Importante: esta página es informativa. Para guardar conservas a temperatura ambiente, sigue una receta probada y recomendaciones oficiales de seguridad alimentaria. No pruebes ni consumas frascos con señales de deterioro.</p>
  </section>

  <section id="qr-section" class="two-col">
    <div>
      <h2 data-es="Comparte nuestra página" data-en="Share our website">Comparte nuestra página</h2>
      <p data-es="Cuando publiques esta página en internet, el código QR se actualizará para apuntar a su dirección pública. Otras personas podrán escanearlo con la cámara de su teléfono." data-en="Once you publish this website online, the QR code will point to its public address. Other people can scan it with their phone camera.">Cuando publiques esta página en internet, el código QR se actualizará para apuntar a su dirección pública. Otras personas podrán escanearlo con la cámara de su teléfono.</p>
      <p class="small" data-es="Nota: si abres el archivo en tu computadora, el QR solo apuntará al archivo local. Para que todos puedan visitarlo, primero debes publicarlo en internet." data-en="Note: if you open this file on your computer, the QR will only point to the local file. To let everyone visit it, you must publish it online first.">Nota: si abres el archivo en tu computadora, el QR solo apuntará al archivo local. Para que todos puedan visitarlo, primero debes publicarlo en internet.</p>
    </div>
    <div class="qrbox">
      <strong data-es="Código QR de la página" data-en="Website QR code">Código QR de la página</strong>
      <img id="qr" alt="Código QR de la dirección actual de la página">
      <div id="urlText" class="small"></div>
      <button class="button" id="downloadQr" type="button" data-es="Abrir / guardar QR" data-en="Open / save QR">Abrir / guardar QR</button>
    </div>
  </section>
</main>

<footer>
  <strong>🍑 Paraíso Frutal | Fruitful Paradise</strong>
  <p data-es="Un proyecto para aprender, crear y aprovechar mejor las frutas." data-en="A project to learn, create, and make better use of fruit.">Un proyecto para aprender, crear y aprovechar mejor las frutas.</p>
</footer>

<div class="editbar">
  <span id="editStatus" class="small" data-es="¿Quieres cambiar los textos? Activa el modo edición." data-en="Want to change the text? Turn on edit mode.">¿Quieres cambiar los textos? Activa el modo edición.</span>
  <button class="editbtn" id="editBtn" type="button" data-es="Editar textos" data-en="Edit text">Editar textos</button>
  <button class="savebtn" id="saveBtn" type="button" data-es="Guardar en este dispositivo" data-en="Save on this device">Guardar en este dispositivo</button>
</div>

<script>
  let currentLang = 'es';
  let editing = false;
  const langBtn = document.getElementById('langBtn');
  const editBtn = document.getElementById('editBtn');
  const saveBtn = document.getElementById('saveBtn');
  const status = document.getElementById('editStatus');

  function setLanguage(lang) {
    currentLang = lang;
    document.documentElement.lang = lang;
    document.querySelectorAll('[data-es][data-en]').forEach(el => {
      const value = el.getAttribute('data-' + lang);
      if (value !== null && !el.isContentEditable) el.textContent = value;
    });
    langBtn.textContent = lang === 'es' ? 'English' : 'Español';
    document.title = lang === 'es' ? 'Paraíso Frutal | Conservas frutales' : 'Paraíso Frutal | Fruit Preserves';
    document.getElementById('urlText').textContent = window.location.href.startsWith('file:') ? (lang === 'es' ? 'Publica la página para compartirla.' : 'Publish the site to share it.') : window.location.href;
    status.textContent = lang === 'es' ? '¿Quieres cambiar los textos? Activa el modo edición.' : 'Want to change the text? Turn on edit mode.';
    editBtn.textContent = lang === 'es' ? (editing ? 'Terminar edición' : 'Editar textos') : (editing ? 'Finish editing' : 'Edit text');
    saveBtn.textContent = lang === 'es' ? 'Guardar en este dispositivo' : 'Save on this device';
  }
  langBtn.addEventListener('click', () => setLanguage(currentLang === 'es' ? 'en' : 'es'));

  function updateQR() {
    const url = window.location.href;
    document.getElementById('urlText').textContent = url.startsWith('file:') ? (currentLang === 'es' ? 'Publica la página para obtener un QR compartible.' : 'Publish the site to get a shareable QR.') : url;
    const qrUrl = 'https://api.qrserver.com/v1/create-qr-code/?size=220x220&data=' + encodeURIComponent(url);
    document.getElementById('qr').src = qrUrl;
    document.getElementById('downloadQr').onclick = () => window.open(qrUrl, '_blank', 'noopener');
  }
  editBtn.addEventListener('click', () => {
    editing = !editing;
    document.querySelectorAll('main h2, main h3, main p, main .step strong, main .step span, .hero h1, .hero p, footer p').forEach(el => {
      el.contentEditable = editing ? 'true' : 'false';
    });
    editBtn.textContent = currentLang === 'es' ? (editing ? 'Terminar edición' : 'Editar textos') : (editing ? 'Finish editing' : 'Edit text');
    status.textContent = editing
      ? (currentLang === 'es' ? 'Puedes cambiar los textos directamente. Luego pulsa guardar.' : 'You can edit text directly. Then press save.')
      : (currentLang === 'es' ? 'Modo edición desactivado.' : 'Edit mode is off.');
  });
  saveBtn.addEventListener('click', () => {
    try {
      const edits = {};
      document.querySelectorAll('main h2, main h3, main p, main .step strong, main .step span, .hero h1, .hero p, footer p').forEach((el, i) => edits[i] = el.innerHTML);
      localStorage.setItem('fruitPreservesEdits', JSON.stringify(edits));
      status.textContent = currentLang === 'es'
        ? 'Cambios guardados en este navegador. Para que todos los vean, edita el archivo del sitio y vuelve a publicarlo.'
        : 'Changes saved in this browser. To show them to everyone, edit the website files and publish again.';
    } catch(e) {
      status.textContent = currentLang === 'es' ? 'No se pudieron guardar los cambios en este navegador.' : 'Could not save changes in this browser.';
    }
  });
  updateQR();
  setLanguage('es');
</script>
</body>
</html>
g index.html…]()
