
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Workshop | A Vida Que Eu Quero Viver</title>
  <meta name="description" content="Workshop gratuito de 3 noites (23, 24 e 25 de outubro, às 19h, ao vivo no YouTube) para soltar pesos do passado, liberar emoções que aprisionam e reescrever a sua história com leveza.">
  <meta name="theme-color" content="#6D5BD0">
  <!-- Open Graph -->
  <meta property="og:title" content="Workshop | A Vida Que Eu Quero Viver" />
  <meta property="og:description" content="3 Noites para soltar o passado e escolher leveza. 23–25/10 às 19h, ao vivo no YouTube." />
  <meta property="og:type" content="website" />
  <meta property="og:image" content="https://via.placeholder.com/1200x630.png?text=A+Vida+Que+Eu+Quero+Viver" />
  <meta property="og:url" content="https://seudominio.com/workshop" />
  <link rel="icon" href="data:image/svg+xml,%3Csvg xmlns=%27http://www.w3.org/2000/svg%27 viewBox=%270 0 100 100%27%3E%3Ccircle cx=%2750%27 cy=%2750%27 r=%2748%27 fill=%27%236D5BD0%27/%3E%3Ctext x=%2750%27 y=%2760%27 font-size=%2750%27 text-anchor=%27middle%27 fill=%27white%27%3E❤%3C/text%3E%3C/svg%3E" />

  <style>
    :root{
      /* Paleta clara e leve */
      --bg:#f7f7fc;
      --bg-soft:#ffffff;
      --brand:#6D5BD0;
      --brand-2:#8F83E6;
      --text:#1f2937;
      --muted:#475569;
      --ok:#16a34a;
      --warn:#b45309;
      --line:#e6e8f0;
      --shadow: 0 8px 22px rgba(17,24,39,.06);
      --radius:16px;

      /* Gradientes azuis para painéis e rodapé */
      --grad-blue: linear-gradient(90deg,#ecfeff 0%, #f5f3ff 100%);
      --grad-footer: linear-gradient(90deg, #6D5BD0 0%, #8F83E6 100%);
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      font-family: ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, "Helvetica Neue", Arial, "Noto Sans";
      background: linear-gradient(180deg, #ffffff 0%, var(--bg) 100%);
      color:var(--text);
      line-height:1.55;
      -webkit-font-smoothing: antialiased;
      -moz-osx-font-smoothing: grayscale;
    }

    /* Força remover header/título do GitHub Pages */
    .site-header, .page-header, header.page-header, .project-name, .project-tagline,
    .Header, .AppHeader, .application-main > header, .markdown-body > h1:first-child,
    body > header[role="banner"].site-header, body > .page-header {
      display:none !important; height:0 !important; overflow:hidden !important;
    }

    .wrap{max-width:1080px;margin:0 auto;padding:24px}
    .hero{
      display:grid; gap:24px; align-items:center;
      grid-template-columns: 1.2fr .8fr;
      padding: clamp(22px,5vw,56px) 0;
    }

    /* Sem badge no hero */
    .badge{display:none}

    /* Título GRANDE e chamativo */
    h1{
      font-size: clamp(3.4rem, 8.5vw, 5.6rem);
      margin:10px 0 14px;
      line-height:1.02;
      font-weight:900;
      letter-spacing:.3px;
      text-align:left;
      background: linear-gradient(90deg, #4338ca 0%, #6D5BD0 40%, #8F83E6 80%, #a89cf5 100%);
      -webkit-background-clip:text; background-clip:text; color:transparent;
      text-shadow: 0 4px 22px rgba(109,91,208,.25);
    }

    .sub{color:var(--muted); font-size: clamp(1rem, 2.2vw, 1.15rem); margin-bottom:18px}

    .meta{display:flex; gap:12px; flex-wrap:wrap; margin:10px 0 24px}
    .chip{
      background:#fff; color:var(--muted);
      border:1px solid var(--line); padding:8px 12px;
      border-radius:999px; font-size:.92rem; box-shadow:var(--shadow)
    }

    .cta{
      display:inline-flex; align-items:center; justify-content:center; gap:10px;
      background:linear-gradient(90deg,var(--brand-2),var(--brand));
      color:#fff; font-weight:800; letter-spacing:.2px;
      padding:16px 22px; border-radius:12px; text-decoration:none; box-shadow:var(--shadow);
      transition: transform .08s ease, filter .15s ease;
    }
    .cta:hover{transform: translateY(-1px); filter:brightness(1.05)}
    .cta:focus{outline:3px solid #c7befa; outline-offset:2px}

    .card{
      background:var(--bg-soft); border:1px solid var(--line);
      border-radius: var(--radius); padding:24px; box-shadow:var(--shadow)
    }

    .grid{display:grid; gap:18px}
    .nights{grid-template-columns: repeat(3,1fr)}
    .night h3{margin:0 0 8px}
    .night ul{margin:10px 0 0 18px}
    .why{grid-template-columns: repeat(2,1fr)}

    /* Painéis com fundo azul (degradê leve) */
    .panel-blue{
      background: var(--grad-blue);
      border:1px solid #e5e7eb;
      border-radius:20px;
      padding:18px;
      box-shadow: 0 8px 24px rgba(17,24,39,.05);
      margin-top:22px;
    }

    .notice{
      display:flex; align-items:center; gap:10px; color:#0f172a;
      background:var(--grad-blue);
      border:1px solid #e5e7eb;
      border-radius:12px; padding:12px 14px; font-weight:600;
    }
    .notice a{color:#0b7; font-weight:800; text-decoration:underline}

    .illus{
      aspect-ratio: 4/3; border-radius: var(--radius);
      background:
        radial-gradient(500px 400px at 30% 20%, rgba(109,91,208,.15), transparent 65%),
        linear-gradient(180deg, #ffffff, #fafaff);
      border:1px solid var(--line);
      display:flex; align-items:center; justify-content:center;
      color:#5b5bd6; font-weight:800; letter-spacing:.5px; text-align:center;
    }
    .illus small{display:block; color:#6d5bd0; font-weight:700}

    /* Rodapé fixo visualmente (barra) com countdown */
    footer{
      margin-top:64px;
      background: var(--grad-footer);
      border-top:1px solid #d9d6fb;
      color:#fff;
    }
    .footer-inner{
      max-width:1080px; margin:0 auto; padding:18px 24px;
      display:flex; align-items:center; justify-content:center; gap:12px;
      text-align:center;
      font-weight:500; /* mais fino */
      letter-spacing:.01em;
      flex-wrap:wrap;    /* mesmo visual em desktop e celular */
    }
    .footer-sep{opacity:.65}
    .footer-count{
      display:inline-flex; gap:8px; align-items:center;
      font-weight:800;
      background:rgba(255,255,255,.18);
      padding:6px 10px; border-radius:10px;
    }
    .footer-count .countdown{font-variant-numeric: tabular-nums; font-weight:900}

    @media (max-width: 900px){
      .hero{grid-template-columns:1fr}
      .nights{grid-template-columns:1fr}
      .why{grid-template-columns:1fr}
    }
  </style>

  <script>
    // Contagem regressiva até 23/10/2025 19:00 America/Sao_Paulo (UTC-03)
    document.addEventListener('DOMContentLoaded', ()=>{
      const out = document.querySelectorAll('.countdown');
      function tick(){
        const target = new Date('2025-10-23T19:00:00-03:00').getTime();
        const now = Date.now();
        let ms = target - now;
        if(ms < 0){ out.forEach(el=>el.textContent="Começa hoje • 19h"); return; }
        const d = Math.floor(ms/86400000); ms-=d*86400000;
        const h = Math.floor(ms/3600000); ms-=h*3600000;
        const m = Math.floor(ms/60000);
        const txt = `${d}d ${String(h).padStart(2,'0')}h ${String(m).padStart(2,'0')}m`;
        out.forEach(el=>el.textContent=txt);
      }
      tick(); setInterval(tick, 30000);
    });
  </script>

  <!-- JSON-LD de evento para SEO -->
  <script type="application/ld+json">
  {
    "@context":"https://schema.org",
    "@type":"Event",
    "name":"Workshop: A Vida Que Eu Quero Viver",
    "startDate":"2025-10-23T19:00:00-03:00",
    "endDate":"2025-10-25T21:00:00-03:00",
    "eventAttendanceMode":"https://schema.org/OnlineEventAttendanceMode",
    "eventStatus":"https://schema.org/EventScheduled",
    "location":{"@type":"VirtualLocation","url":"https://youtube.com/"},
    "image":"https://via.placeholder.com/1200x630.png?text=A+Vida+Que+Eu+Quero+Viver",
    "description":"3 noites para soltar pesos do passado, liberar emoções que aprisionam e reescrever a história com leveza. Inscreva-se entrando no grupo de WhatsApp.",
    "organizer":{"@type":"Organization","name":"Mentoria O Seu Lugar"}
  }
  </script>

  <!-- Meta Pixel Code -->
  <script>
  !function(f,b,e,v,n,t,s)
  {if(f.fbq)return;n=f.fbq=function(){n.callMethod?
  n.callMethod.apply(n,arguments):n.queue.push(arguments)};
  if(!f._fbq)f._fbq=n;n.push=n;n.loaded=!0;n.version='2.0';
  n.queue=[];t=b.createElement(e);t.async=!0;
  t.src=v;s=b.getElementsByTagName(e)[0];
  s.parentNode.insertBefore(t,s)}(window, document,'script',
  'https://connect.facebook.net/en_US/fbevents.js');
  fbq('init', '1284878359977607');
  fbq('track', 'PageView');
  </script>
  <noscript><img height="1" width="1" style="display:none"
  src="https://www.facebook.com/tr?id=1284878359977607&ev=PageView&noscript=1"
  /></noscript>
</head>

<body>
  <header class="wrap hero" role="banner" aria-label="Cabeçalho do Workshop">
    <div>
      <h1>A Vida Que Eu Quero Viver</h1>
      <p class="sub">Três noites para soltar os barulhos da mente, liberar emoções que aprisionam e reescrever sua história com leveza.</p>
      <div class="meta" aria-label="Informações rápidas">
        <span class="chip">📅 23, 24 e 25 de outubro</span>
        <span class="chip">🕖 19h (ao vivo)</span>
        <span class="chip">🎥 YouTube</span>
        <span class="chip">⏳ Começa em: <span class="countdown" aria-live="polite">Calculando…</span></span>
      </div>
      <a class="cta js-whatsapp"
         href="https://chat.whatsapp.com/CeXf6hjhBziAzvXl9HGFFp?mode=ems_copy_t"
         target="_blank" rel="noopener"
         aria-label="Entrar no grupo de WhatsApp e garantir minha vaga"
         data-track="whatsapp_header">💬 Entrar no grupo de WhatsApp</a>
      <p class="sub" style="margin-top:10px">❗ A confirmação e os links das aulas serão enviados apenas no grupo.</p>
    </div>

    <div class="illus card" role="img" aria-label="Ilustração do Workshop">
      <div>
        WORKSHOP • 3 NOITES
        <small>Consciência • Liberação • Um novo começo</small>
      </div>
    </div>
  </header>

  <main class="wrap" role="main">
    <!-- Painel azul: Convite -->
    <section class="panel-blue" aria-labelledby="convite">
      <div class="card">
        <h2 id="convite">Um convite simples: Um novo começo</h2>
        <p>
          Se a sua vida parece <em>travada</em> e você sente um peso que não sabe explicar, este encontro é para você.
          O passado não muda — mas o peso que você carrega dele pode mudar. Em três noites, vamos sair do automático,
          diminuir o barulho interno e criar um caminho real de leveza.
        </p>
        <div class="notice" role="note">
          📩 Para participar, basta clicar no botão acima (link do WhatsApp será confirmado depois).
        </div>
      </div>
    </section>

    <!-- Painel azul: O que vai rolar -->
    <section class="panel-blue" aria-labelledby="noites">
      <div class="wrap-in" style="display:block">
        <h2 id="noites" style="margin:2px 0 12px">O que vai rolar em cada noite</h2>
        <div class="grid nights">
          <article class="card night" aria-label="Noite 1">
            <h3>🌌 Noite 1 — O barulho invisível da mente</h3>
            <p>Como pensamentos acelerados e autocobrança nos afastam do essencial. O falso “estar ocupado” que esconde ansiedade.</p>
            <ul>
              <li>Identificar ruídos (produtividade-fuga, controle, comparação)</li>
              <li>Microprática de presença</li>
              <li>Clareza do essencial (o que realmente importa agora)</li>
            </ul>
          </article>

          <article class="card night" aria-label="Noite 2">
            <h3>🔥 Noite 2 — Emoções que sabotam meus passos</h3>
            <p>Quando uma emoção vale mais que uma vida inteira: medo, culpa, vergonha e a arte de ressignificar.</p>
            <ul>
              <li>Mapa da emoção raiz (psico + neuro)</li>
              <li>Soltar com método: reconhecer → acolher → ressignificar → ancorar</li>
              <li>Exercício “da dor ao recurso”</li>
            </ul>
          </article>

          <article class="card night" aria-label="Noite 3">
            <h3>🌱 Noite 3 — Reescrevendo meu lugar no mundo</h3>
            <p>Quem eu precisei ser para caber vs. quem eu escolho ser agora. Pertencer sem carregar o que não é meu.</p>
            <ul>
              <li>Carta de compromisso: “A vida que eu quero viver”</li>
              <li>Equilíbrio dar/receber (pertencimento saudável)</li>
              <li>Meditação de integração + próximos passos</li>
            </ul>
          </article>
        </div>
      </div>
    </section>

    <!-- Painel azul: Por que participar -->
    <section class="panel-blue" aria-labelledby="porque">
      <div class="wrap-in">
        <h2 id="porque" style="margin:2px 0 12px">Por que participar</h2>
        <div class="grid why">
          <div class="card">
            <ul>
              <li>Online, gratuito e direto ao ponto</li>
              <li>Três encontros ao vivo com práticas reais</li>
              <li>Materiais para imprimir e aplicar na semana</li>
            </ul>
          </div>
          <div class="card">
            <ul>
              <li>Clareza emocional e mental para decidir o próximo passo</li>
              <li>Leveza para relações e rotina</li>
              <li>Um começo novo, com consciência</li>
            </ul>
          </div>
        </div>
      </div>
    </section>

    <!-- CTA central -->
    <section class="card" aria-labelledby="cta2" style="margin-top:22px;text-align:center">
      <h2 id="cta2" style="margin-top:0">Garanta sua vaga agora</h2>
      <p class="sub">As informações e links serão enviados somente dentro do grupo.</p>
      <a class="cta js-whatsapp"
         href="https://chat.whatsapp.com/CeXf6hjhBziAzvXl9HGFFp?mode=ems_copy_t"
         target="_blank" rel="noopener"
         data-track="whatsapp_mid">💬 Entrar no grupo de WhatsApp</a>
      <p class="sub" style="margin-top:10px">📅 23, 24 e 25/10 • 🕖 19h • 🎥 YouTube</p>
    </section>
  </main>

  <!-- Rodapé com contagem regressiva (único lugar) -->
  <footer role="contentinfo" aria-label="Barra fixa com contagem regressiva e direitos autorais">
    <div class="footer-inner">
      <span class="footer-count">⏳ Começa em: <span class="countdown" aria-live="polite">Calculando…</span></span>
      <span class="footer-sep">•</span>
      <span>© <span id="y"></span> Mentoria O Seu Lugar — Todos os direitos reservados</span>
    </div>
  </footer>

  <script>document.getElementById('y').textContent = new Date().getFullYear();</script>

  <!-- Rastreamento de cliques no WhatsApp -->
  <script>
    (function(){
      function trackLead(){
        try{
          fbq && fbq('track', 'Lead', {
            content_name: 'WhatsApp Group Join',
            content_category: 'Workshop A Vida Que Eu Quero Viver',
            value: 0.00, currency: 'BRL'
          });
        }catch(err){}
      }
      document.addEventListener('click', function(ev){
        const a = ev.target.closest('a'); if(!a) return;
        const href = a.getAttribute('href') || '';
        if (a.classList.contains('js-whatsapp') || href.includes('chat.whatsapp.com')) trackLead();
      }, true);
    })();
  </script>
</body>
</html>
