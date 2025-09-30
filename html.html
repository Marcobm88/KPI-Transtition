<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>KPI Transition - SPS Puebla</title>
  <meta name="description" content="KPI Transition: La forma fácil y visual de presentar tus indicadores de desempeño. Creado por SPS Puebla.">
  <meta name="keywords" content="KPI, indicadores, SPS Puebla, dashboard, métricas, empresa">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body { 
      font-family: "Segoe UI", Roboto, Oxygen, Ubuntu, sans-serif;
      min-height: 100vh; 
      display: flex; 
      flex-direction: column;
      justify-content: center; 
      align-items: center; 
      background: #0F58D6; 
      color: #fff; 
      text-align: center;
      overflow: hidden;
      position: relative;
    }

    /* --- Título animado --- */
    h1 {
      position: absolute;
      top: 20%;
      left: 50%;
      transform: translate(-50%, -50%) scale(1);
      font-size: 3.5rem;
      text-transform: uppercase;
      color: rgba(255,255,255,0.2);
      overflow: hidden;
      z-index: auto;
      transition: top 1.5s ease, left 1.5s ease, transform 1.5s ease, font-size 1.5s ease;
    }
    h1::before {
      content: 'KPI Transition';
      position: absolute;
      top: 0; left: 0;
      width: 0;
      height: 100%;
      color: #0ff;
      -webkit-text-stroke: 1.5px #fff;
      text-shadow: 0 0 20px #0ff;
      overflow: hidden;
      animation: fillText 3s forwards, neonPulse 1.5s ease-in-out infinite alternate;
    }
    @keyframes fillText { 0% { width: 0; } 100% { width: 100%; } }
    @keyframes neonPulse {
      0%,100% { text-shadow: 0 0 10px #0ff, 0 0 20px #0ff; }
      50% { text-shadow: 0 0 30px #0ff, 0 0 60px #0ff; }
    }
    h1.moveTopRight {
      position: fixed;
      top: 10px;
      right: 20px;
      left: auto;
      transform: scale(0.6);
      font-size: 2rem;
      z-index: auto;
    }

    /* --- Contenido principal (landing) --- */
    main {
      display: flex;
      flex-direction: column;
      align-items: center;
      height: 70vh;
      padding-top: 10%;
      transition: opacity 0.8s ease;
    }
    main .texto > * {
      opacity: 0;
      transform: translateY(30px);
      transition: opacity 0.8s ease, transform 0.8s ease;
    }
    main.show .texto h2 { transition-delay: 0.2s; opacity: 1; transform: translateY(0); }
    main.show .texto p { transition-delay: 0.6s; opacity: 1; transform: translateY(0); }
    .boton { margin-top: 30px; opacity: 0; transform: translateY(30px); transition: opacity 0.8s ease, transform 0.8s ease; }
    main.show .boton { transition-delay: 1s; opacity: 1; transform: translateY(0); }
    .cta {
      padding: 12px 24px;
      background: #0ff;
      color: #0F58D6;
      font-weight: bold;
      border-radius: 30px;
      cursor: pointer;
      transition: transform 0.3s, box-shadow 0.3s;
    }
    .cta:hover { transform: scale(1.05); box-shadow: 0 0 15px #0ff; }

    /* --- Panel de botones inicial --- */
    #panelBotones {
      display: none;
      flex-direction: column;
      gap: 20px;
      position: absolute;
      top: 50%; left: 50%;
      transform: translate(-50%, -50%);
    }
    #panelBotones button {
      padding: 12px 24px;
      border: none;
      border-radius: 20px;
      background-color: #0ff;
      color: #0F58D6;
      font-weight: bold;
      cursor: pointer;
      transition: transform 0.3s, box-shadow 0.3s;
    }
    #panelBotones button:hover { transform: scale(1.05); box-shadow: 0 0 15px #0ff; }

    /* --- Pulse Meeting Page --- */
    #pulsePage {
      display: none;
      padding: 5px;
      text-align: center;
      width: 100%;
      height: 100vh;
      overflow-y:auto;
      
    }
    #pulsePage h2 { color: #0ff; margin-bottom: 10px; }
#pulsePage iframe {
  width: 100%;
  height: 100vh; /* 80% de la altura de la pantalla */
  max-height: 1000px;
  border: none;
  border-radius: 12px;
  box-shadow: 0 0 15px #0ff;
  margin-top: 10px;
}
    .control-button {
      padding: 5px 24px;
      border: none;
      border-radius: 20px;
      background-color: #0ff;
      color: #0F58D6;
      font-weight: bold;
      cursor: pointer;
      margin: 5px;
      transition: transform 0.3s, box-shadow 0.3s;
    }
    .control-button:hover { transform: scale(1.05); box-shadow: 0 0 15px #0ff; }

    #toggleHeader {
  position: absolute;  /* o 'fixed' si quieres que siempre esté visible */
  top: 5px;           /* distancia desde el borde superior */
  left: 150px;          /* distancia desde el borde izquierdo */
  margin: 0;           /* eliminar margen heredado */
}

    #btnBack {
  position: absolute;  /* o 'fixed' si quieres que siempre esté visible */
  top: 5px;           /* distancia desde el borde superior */
  left: 5px;          /* distancia desde el borde izquierdo */
  margin: 0;           /* eliminar margen heredado */
}

    /* --- Footer --- */
    footer {
      position: fixed; bottom: 10px; left: 50%;
      transform: translateX(-50%);
      font-size: 0.9rem;
      opacity: 0.8;
    }
    footer a { color: #fff; text-decoration: none; }
    footer a:hover { text-decoration: underline; }

    @media (max-width: 600px) {
      h1 { font-size: 2.5rem; }
      main { font-size: 1rem; padding-top: 40%; }
      #pulsePage iframe { height: 400px; }
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <h1 id="title">KPI Transition</h1>
  </header>

  <!-- Landing -->
  <main id="mainContent">
    <div class="texto">
      <h2>Creado por SPS Puebla</h2>
      <p>La forma fácil de presentar tus indicadores.</p>
    </div>
    <div class="boton">
      <a class="cta">Comenzar</a>
    </div>
  </main>

  <!-- Panel de botones -->
  <div id="panelBotones">
    <button id="btnPulse">Pulse Meeting Operations</button>
    <button>⚙️ Próximamente DM3</button>
    <button>⚙️ Próximamente DM2</button>
  </div>
  <script>
const btnPulse = document.getElementById("btnPulse");

btnPulse.addEventListener("click", () => {
  // Inicia un temporizador de 5 segundos (5000 ms)
  setTimeout(() => {
    const toggleHeaderBtn = document.getElementById("toggleHeader");
    const pulseHeader = document.querySelector("#pulsePage h2");
    const btnBack = document.getElementById("btnBack");
    const pulsePage = document.getElementById("pulsePage");

    toggleHeaderBtn.addEventListener("click", () => {
      const isHidden = pulseHeader.style.display === "none";

      // Desplazamiento automático hacia abajo del contenedor
      if (!isHidden) {
        pulsePage.scrollTo({ top: 1000, behavior: 'smooth' });
      }
    });

  }, 5000); // 5000 milisegundos = 5 segundos
});
</script>

  <!-- Pulse Meeting integrado -->
  <div id="pulsePage">
    <h2>Pulse Meeting Operations</h2>
    <div>
      <button id="btnBack" class="control-button">⬅ Regresar</button>
<button id="toggleHeader" class="control-button"> ✖️Ocultar Encabezado</button>
    </div>
   <!-- Script al final del body -->
<script>
const toggleHeaderBtn = document.getElementById("toggleHeader");
const pulseHeader = document.querySelector("#pulsePage h2");
const btnBack = document.getElementById("btnBack");
const pulsePage = document.getElementById("pulsePage");

toggleHeaderBtn.addEventListener("click", () => {
  const isHidden = pulseHeader.style.display === "none";

  
 



  // Desplazamiento automático hacia arriba del contenedor
  if (!isHidden) {
    pulsePage.scrollTo({ top: 1000, behavior: 'smooth' });
  }
});
</script>
</script> 
    
    <!-- Contenedor para embeber el slideshow -->
<div id="embeddedKPI" style="width:100%;height:100vh;"></div>

<script>
(function(){
  const container = document.getElementById("embeddedKPI");
  container.innerHTML = `
    <style>
      /* --- ESTILOS ENCERRADOS EN EL CONTENEDOR --- */
      #embeddedKPI * { box-sizing: border-box; margin:0; padding:0; font-family: Arial, sans-serif; }
      #embeddedKPI { position: relative; background-color: #f0f0f0; overflow: hidden; height: 100%; }

      #embeddedKPI .slideshow-container { width: 100%; height: 100%; position: relative; overflow: hidden; }
      #embeddedKPI .slide { position: absolute; top:0; left:0; width:100%; height:100%; opacity:0; transition: opacity 1s ease-in-out; pointer-events:none; }
      #embeddedKPI .slide.active { opacity:1; z-index:1; pointer-events:auto; }
      #embeddedKPI iframe { width:100%; height:100%; border:none; }

      #embeddedKPI .dots-container { position: absolute; bottom:20px; left:50%; transform:translateX(-50%); display:flex; gap:8px; z-index:1000; }
      #embeddedKPI .dot { width:12px; height:12px; border-radius:50%; background: linear-gradient(145deg, #0F58D6, #0A47B5); border:2px solid rgba(0,0,0,0.5); cursor:pointer; transition: transform 0.2s, box-shadow 0.2s; }
      #embeddedKPI .dot.active { transform: scale(1.2); box-shadow: 0 0 8px rgba(15,88,214,0.8); }

      #embeddedKPI .progress-bar-container { position: absolute; bottom:5px; left:50%; transform:translateX(-50%); display:flex; align-items:center; justify-content:flex-start; height:6px; border:2px solid rgba(15,88,214,0.3); border-radius:3px; overflow:hidden; max-width:90%; z-index:1000; }
      #embeddedKPI .progress-bar { height:100%; width:0; background: linear-gradient(90deg, #0F58D6, #0F58D6); transition: width 0.5s linear; border-radius:10px 0 0 10px; transform-origin:left center; }

      #embeddedKPI .controls-container { position:absolute; top:92%; left:50%; display:flex; justify-content:center; gap:10px; background:rgba(0,0,0,0.5); padding:10px; border-radius:20px; z-index:1001; align-items:center; transform-origin:center center; }
      #embeddedKPI .controls-container.hidden { opacity:0; transform:translate(-50%,-50%) scaleX(0); transition: opacity 0.5s ease-in, transform 0.5s ease-in; }
      #embeddedKPI .controls-container.visible { opacity:1; transform:translate(-50%,-50%) scaleX(1); transition: opacity 0.5s ease-out, transform 0.5s ease-out; }

      #embeddedKPI .control-button, #embeddedKPI .menu-toggle { background: linear-gradient(145deg, #0F58D6, #0A47B5); color:white; border:none; padding:6px 12px; border-radius:5px; cursor:pointer; font-weight:bold; transition: transform 0.2s, box-shadow 0.2s, background 0.3s; }
      #embeddedKPI .control-button:hover, #embeddedKPI .menu-toggle:hover { background: linear-gradient(145deg, #0A47B5, #0842A0); transform:scale(1.1); box-shadow:0 4px 10px rgba(0,0,0,0.3); }
      #embeddedKPI #pinBtn.active, #embeddedKPI .menu-toggle.active { background-color:#d9534f; }

      #embeddedKPI .menu { position:absolute; top:0; left:-250px; width:250px; height:100%; background:rgba(0,0,0,0.9); color:white; padding:20px; box-shadow:2px 0 5px rgba(0,0,0,0.5); transition:left 0.3s ease; z-index:2000; display:flex; flex-direction:column; }
      #embeddedKPI .menu.open { left:0; }
      #embeddedKPI .menu h2 { margin-bottom:10px; font-size:1.2em; }
      #embeddedKPI .menu input { margin-bottom:15px; padding:8px; border:none; border-radius:5px; outline:none; }
      #embeddedKPI .menu ul { list-style:none; flex-grow:1; overflow-y:auto; }
      #embeddedKPI .menu ul li { margin:10px 0; cursor:pointer; padding:8px; border-radius:5px; transition:background 0.2s; }
      #embeddedKPI .menu ul li:hover { background: rgba(255,255,255,0.2); }

      #embeddedKPI .time-container { position:absolute; bottom:5px; right:10px; display:flex; gap:15px; background:rgba(0,0,0,0.6); padding:4px 8px; border-radius:5px; font-weight:bold; color:white; font-size:14px; z-index:1001; }

      #embeddedKPI .slide-notification { position:absolute; bottom:110px; left:50%; transform:translateX(-50%); background:rgba(255,50,50,0.9); color:white; font-weight:bold; padding:12px 20px; border-radius:10px; font-size:18px; z-index:1500; opacity:0; pointer-events:none; text-align:center; }
      #embeddedKPI .slide-notification.show-notification { opacity:1; pointer-events:auto; animation:bounceBlink 1s infinite alternate; }
      @keyframes bounceBlink { 0%{transform:translateX(-50%) translateY(0);opacity:1;} 50%{transform:translateX(-50%) translateY(-5px);opacity:0.7;} 100%{transform:translateX(-50%) translateY(0);opacity:1;} }
    </style>

    <div class="menu" id="menu">
      <h2>Reportes</h2>
      <input type="text" id="searchInput" placeholder="Buscar...">
      <ul id="menuList"></ul>
    </div>

    <div class="slideshow-container">
 <div class="slide active" data-title="Dias Sin Accidentes" data-src="https://app.powerbi.com/reportEmbed?reportId=05d44c7e-77dc-4ddb-b90b-1ac36cb2510d&appId=9220bfcd-f95a-4cbd-b5b0-7fc72910ddd1&autoAuth=true&ctid=41875f2b-33e8-4670-92a8-f643afbb243a"></div>
  <div class="slide" data-title="Observaciones Preventivas" data-src="https://app.powerbi.com/reportEmbed?reportId=59c560e7-ec2a-4051-8c91-643f02e2b97b&appId=9220bfcd-f95a-4cbd-b5b0-7fc72910ddd1&autoAuth=true&ctid=41875f2b-33e8-4670-92a8-f643afbb243a"></div>
  <div class="slide" data-title="Condiciones Inseguras" data-src="https://app.powerbi.com/reportEmbed?reportId=19272e79-e578-4910-9c45-6985a9e1151a&appId=9220bfcd-f95a-4cbd-b5b0-7fc72910ddd1&autoAuth=true&ctid=41875f2b-33e8-4670-92a8-f643afbb243a"></div>
  <div class="slide" data-title="Reclamos de Cliente" data-src="https://app.powerbi.com/reportEmbed?reportId=3c08cd3b-f9f2-4e45-aa10-b0e8f351c754&appId=9220bfcd-f95a-4cbd-b5b0-7fc72910ddd1&autoAuth=true&ctid=41875f2b-33e8-4670-92a8-f643afbb243a"></div>
  <div class="slide" data-title="GP12" data-src="https://app.powerbi.com/reportEmbed?reportId=32f007fe-1b6a-486d-a552-ba6421124586&appId=9220bfcd-f95a-4cbd-b5b0-7fc72910ddd1&autoAuth=true&ctid=41875f2b-33e8-4670-92a8-f643afbb243a"></div>
  <div class="slide" data-title="LPA" data-src="https://app.powerbi.com/reportEmbed?reportId=0e614365-b8de-4f24-9c93-42739b5b51e3&appId=9220bfcd-f95a-4cbd-b5b0-7fc72910ddd1&autoAuth=true&ctid=41875f2b-33e8-4670-92a8-f643afbb243a"></div>
  <div class="slide" data-title="Art3mis Report" data-src="https://app.powerbi.com/reportEmbed?reportId=98aa1ef0-daa3-4e6c-8a86-fec0798b6354&autoAuth=true&ctid=41875f2b-33e8-4670-92a8-f643afbb243a"></div>
  <div class="slide" data-title="Deliveries & Shipments" data-src="https://app.powerbi.com/reportEmbed?reportId=2e3c7de4-1fa9-42dd-bebf-2af29dfb9a57&appId=9220bfcd-f95a-4cbd-b5b0-7fc72910ddd1&autoAuth=true&ctid=41875f2b-33e8-4670-92a8-f643afbb243a"></div>
  <div class="slide" data-title="Traker MTD" data-src="https://app.powerbi.com/reportEmbed?reportId=3b26177e-e126-4f10-9e78-c9eb69469d68&appId=9220bfcd-f95a-4cbd-b5b0-7fc72910ddd1&autoAuth=true&ctid=41875f2b-33e8-4670-92a8-f643afbb243a"></div>
  <div class="slide" data-title="Cumplimiento AM" data-src="https://app.powerbi.com/reportEmbed?reportId=1761e44b-ad0b-4e6d-b1e4-00a05912e351&appId=9220bfcd-f95a-4cbd-b5b0-7fc72910ddd1&autoAuth=true&ctid=41875f2b-33e8-4670-92a8-f643afbb243a"></div>
  <div class="slide" data-title="SLR" data-src="https://app.powerbi.com/reportEmbed?reportId=a2f6c47d-fb15-4486-bb83-e2bc2ece58bd&appId=9220bfcd-f95a-4cbd-b5b0-7fc72910ddd1&autoAuth=true&ctid=41875f2b-33e8-4670-92a8-f643afbb243a"></div>
  <div class="slide" data-title="Shop Supplies" data-src="https://app.powerbi.com/reportEmbed?reportId=c2e48330-25d8-4b0b-bd20-888e44bcf0a0&appId=9220bfcd-f95a-4cbd-b5b0-7fc72910ddd1&autoAuth=true&ctid=41875f2b-33e8-4670-92a8-f643afbb243a"></div>
  <div class="slide" data-title="WIP" data-src="https://app.powerbi.com/reportEmbed?reportId=4b98a0c5-2153-47d4-ad51-3dae2fadff9e&appId=9220bfcd-f95a-4cbd-b5b0-7fc72910ddd1&autoAuth=true&ctid=41875f2b-33e8-4670-92a8-f643afbb243a"></div>
  <div class="slide" data-title="Calendario" data-src="https://app.powerbi.com/reportEmbed?reportId=675a7c87-8634-43b4-8a11-d053f8471a5e&appId=9220bfcd-f95a-4cbd-b5b0-7fc72910ddd1&autoAuth=true&ctid=41875f2b-33e8-4670-92a8-f643afbb243a"></div>
  <div class="slide" data-title="5s Walks" data-src="https://app.powerbi.com/reportEmbed?reportId=e783cd68-b88e-46a7-9e67-40af94bc8476&appId=9220bfcd-f95a-4cbd-b5b0-7fc72910ddd1&autoAuth=true&ctid=41875f2b-33e8-4670-92a8-f643afbb243a"></div>
  <div class="slide" data-title="Gemba Walks" data-src="https://app.powerbi.com/reportEmbed?reportId=db3deed8-a212-4ae1-9764-820e57282398&appId=9220bfcd-f95a-4cbd-b5b0-7fc72910ddd1&autoAuth=true&ctid=41875f2b-33e8-4670-92a8-f643afbb243a"></div>
      <div class="dots-container" id="dotsContainer"></div>
      <div class="progress-bar-container" id="progressBarContainer"><div class="progress-bar" id="progressBar"></div></div>
      <div class="controls-container visible" id="controls">
        <button class="control-button" id="prevBtn">⟨</button>
        <button class="control-button" id="playBtn">Iniciar</button>
        <button class="control-button" id="pauseBtn">Pausar</button>
        <button class="control-button" id="nextBtn">⟩</button>
        <button class="control-button" id="fullscreenBtn">Pantalla Completa</button>
        <button class="control-button" id="refreshBtn">🔄 Refrescar</button>
        <button class="control-button" id="pinBtn">📌 Fijar</button>
        <button class="menu-toggle" id="menuToggle">☰ Menú</button>
      </div>
      <div class="time-container">
        <div id="currentTime">🕑 00:00:00</div>
        <div id="slideTimer">⏱️ 0s</div>
      </div>
      <div id="slideNotification" class="slide-notification">⏱️ Tiempo de diapositiva agotado</div>
    </div>
  `;

  // --- JS ENCERRADO ---
  const slides = container.querySelectorAll('.slide');
  const dotsContainer = container.querySelector('#dotsContainer');
  const progressBar = container.querySelector('#progressBar');
  const progressBarContainer = container.querySelector('#progressBarContainer');
  const playBtn = container.querySelector('#playBtn');
  const pauseBtn = container.querySelector('#pauseBtn');
  const fullscreenBtn = container.querySelector('#fullscreenBtn');
  const menu = container.querySelector('#menu');
  const menuToggle = container.querySelector('#menuToggle');
  const menuList = container.querySelector('#menuList');
  const searchInput = container.querySelector('#searchInput');
  const controls = container.querySelector('#controls');
  const pinBtn = container.querySelector('#pinBtn');
  const currentTimeDiv = container.querySelector('#currentTime');
  const slideTimerDiv = container.querySelector('#slideTimer');
  const slideNotification = container.querySelector('#slideNotification');

  let currentSlide = 0, intervalId = null, slideDuration = 120000;
  let hideControlsTimeout, timerInterval = null, secondsElapsed = 0;
  let controlsPinned = false;

  slides.forEach((slide, i) => {
    const dot = document.createElement('div');
    dot.classList.add('dot');
    if(i===0) dot.classList.add('active');
    dot.addEventListener('click', ()=>goToSlide(i));
    dotsContainer.appendChild(dot);

    const li = document.createElement('li');
    li.textContent = slide.dataset.title;
    li.dataset.index = i;
    li.addEventListener('click', ()=>{ goToSlide(i); closeMenu(); });
    menuList.appendChild(li);
  });

  const dots = container.querySelectorAll('.dot');
  pauseBtn.style.display = 'none';
  controls.classList.add('visible');

  function resetProgressBar(){ progressBar.style.transition='none'; progressBar.style.width='0%'; setTimeout(()=>animateProgressBar(),50); }
  function animateProgressBar(){ progressBar.style.transition=`width ${slideDuration}ms linear`; progressBar.style.width='100%'; }

  function showSlide(index){
    slides.forEach((slide,i)=>{
      slide.classList.toggle('active', i===index);
      dots[i].classList.toggle('active', i===index);
      if(i===index && !slide.querySelector('iframe')){
        const iframe = document.createElement('iframe');
        iframe.src = slide.dataset.src;
        slide.appendChild(iframe);
      }
    });
    slideNotification.classList.remove('show-notification');
    resetProgressBar(); startTimer();
    setTimeout(()=>{ if(currentSlide===index){ slideNotification.classList.add('show-notification'); } }, slideDuration);
  }

  function goToSlide(index){ currentSlide=index; showSlide(currentSlide); }
  function nextSlide(){ currentSlide=(currentSlide+1)%slides.length; showSlide(currentSlide); }
  function prevSlide(){ currentSlide=(currentSlide-1+slides.length)%slides.length; showSlide(currentSlide); }

  function startSlideshow(){
    if(!intervalId) intervalId=setInterval(()=>{ nextSlide(); resetProgressBar(); }, slideDuration);
    playBtn.style.display='none'; pauseBtn.style.display='inline'; resetProgressBar();
  }

  function stopSlideshow(){
    clearInterval(intervalId); intervalId=null;
    playBtn.style.display='inline'; pauseBtn.style.display='none';
    const computedStyle = window.getComputedStyle(progressBar);
    progressBar.style.transition='none';
    progressBar.style.width=computedStyle.width;
  }

  function closeMenu(){ menu.classList.remove('open'); menuToggle.classList.remove('active'); menuToggle.textContent="☰ Menú"; }

  container.querySelector('#refreshBtn').addEventListener('click', ()=>{
    const iframe = slides[currentSlide].querySelector('iframe');
    if(iframe) iframe.src = slides[currentSlide].dataset.src;
  });

  container.querySelector('#nextBtn').addEventListener('click', nextSlide);
  container.querySelector('#prevBtn').addEventListener('click', prevSlide);
  playBtn.addEventListener('click', startSlideshow);
  pauseBtn.addEventListener('click', stopSlideshow);

  fullscreenBtn.addEventListener('click', ()=>{
    if(!document.fullscreenElement){ document.documentElement.requestFullscreen(); fullscreenBtn.textContent="Salir de Pantalla Completa"; }
    else{ document.exitFullscreen(); fullscreenBtn.textContent="Pantalla Completa"; }
  });

  menuToggle.addEventListener('click', ()=>{ menu.classList.toggle('open'); menuToggle.classList.toggle('active'); menuToggle.textContent=menu.classList.contains('open')?"Cerrar Menú":"☰ Menú"; });

  searchInput.addEventListener('input', ()=>{
    const filter=searchInput.value.toLowerCase();
    menuList.querySelectorAll('li').forEach(item=>item.style.display=item.textContent.toLowerCase().includes(filter)?'block':'none');
  });

  function formatTime(seconds){ const m=Math.floor(seconds/60); const s=seconds%60; return (m>0?m+'m ':'')+s+'s'; }
  function startTimer(){ clearInterval(timerInterval); secondsElapsed=0; slideTimerDiv.textContent=`⏱️ ${formatTime(secondsElapsed)}`; timerInterval=setInterval(()=>{ secondsElapsed++; slideTimerDiv.textContent=`⏱️ ${formatTime(secondsElapsed)}`; },1000); }

  function showControls(){ controls.classList.remove('hidden'); controls.classList.add('visible'); clearTimeout(hideControlsTimeout); if(!controlsPinned){ hideControlsTimeout=setTimeout(()=>{ if(!controls.matches(':hover') && !menu.matches(':hover')){ controls.classList.remove('visible'); controls.classList.add('hidden'); } },2000); } }
  document.addEventListener('mousemove', showControls);

  pinBtn.addEventListener('click', ()=>{
    controlsPinned=!controlsPinned;
    pinBtn.classList.toggle('active', controlsPinned);
    pinBtn.textContent=controlsPinned?"📌 Desfijar":"📌 Fijar";
    if(controlsPinned){ controls.classList.remove('hidden'); controls.classList.add('visible'); }
  });

  function updateClock(){ const now=new Date(); currentTimeDiv.textContent=`🕑 ${String(now.getHours()).padStart(2,'0')}:${String(now.getMinutes()).padStart(2,'0')}:${String(now.getSeconds()).padStart(2,'0')}`; }
  setInterval(updateClock,1000); updateClock();

  showSlide(currentSlide); startSlideshow();
})();
</script>

    
  </div>
  

  <!-- Footer -->
  <footer>
    <p>
      <a href="#" id="correoFooter">📧 Dudas y Sugerencias, aquí | SPS Puebla</a>
    </p>
  </footer>

  <script>
    // Animación inicial
    window.addEventListener("load", () => {
      const mainContent = document.getElementById("mainContent");
      const title = document.getElementById("title");
      const cta = document.querySelector(".cta");
      const panel = document.getElementById("panelBotones");

      mainContent.classList.add('show');
      cta.addEventListener("click", () => {
        mainContent.style.opacity = 0;
        setTimeout(() => {
          mainContent.style.display = "none";
          title.classList.add('moveTopRight');
          panel.style.display = "flex";
        }, 800);
      });
    });

    // Navegación entre panel y Pulse Meeting
    document.getElementById("btnPulse").addEventListener("click", () => {
      document.getElementById("panelBotones").style.display = "none";
      document.getElementById("pulsePage").style.display = "block";
      document.querySelector("footer").style.display = "none"; // Ocultar footer
    });
    document.getElementById("btnBack").addEventListener("click", () => {
      document.getElementById("pulsePage").style.display = "none";
      document.getElementById("panelBotones").style.display = "flex";
      document.querySelector("footer").style.display = "block"; // Mostrar footer
    });

    // Footer dinámico
    document.getElementById("correoFooter").addEventListener("click", function(e) {
      e.preventDefault();
      const now = new Date();
      const fechaHora = now.toLocaleString('es-MX', { hour12: false });
      const asunto = encodeURIComponent(`Consulta KPI Transition - ${fechaHora}`);
      const cuerpo = encodeURIComponent("Hola, quiero ayuda o tengo feedback en KPI Transition.");
      window.location.href = `mailto:marco.barranco@skf.com,skf.de.mexico.manufactura@skf.com?subject=${asunto}&body=${cuerpo}`;
    });
  </script>
</body>
</html>
