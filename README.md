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
  <meta property="og:image" content="https://via.placeholder.com/1200x630.png?text=A Vida Que Eu Quero Viver" />
  <meta property="og:url" content="https://seudominio.com/workshop" />
  <link rel="icon" href="data:image/svg+xml,%3Csvg xmlns=%27http://www.w3.org/2000/svg%27 viewBox=%270 0 100 100%27%3E%3Ccircle cx=%2750%27 cy=%2750%27 r=%2748%27 fill=%27%236D5BD0%27/%3E%3Ctext x=%2750%27 y=%2760%27 font-size=%2750%27 text-anchor=%27middle%27 fill=%27white%27%3E❤%3C/text%3E%3C/svg%3E" />

  <style>
    :root{
      --bg:#0f1020;
      --bg-soft:#151735;
      --brand:#6D5BD0;
      --brand-2:#8F83E6;
      --text:#E9E9F3;
      --muted:#BFC2D9;
      --ok:#27C498;
      --warn:#FFC86B;
      --shadow: 0 10px 30px rgba(0,0,0,.35);
      --radius:16px;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      font-family: ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, "Helvetica Neue", Arial, "Noto Sans", "Apple Color Emoji","Segoe UI Emoji";
      background: radial-gradient(1200px 800px at 70% -10%, #222455 0%, transparent 60%) , var(--bg);
      color:var(--text);
      line-height:1.5;
    }

    /* 🔧 FORÇAR a remoção do cabeçalho/título padrão do GitHub Pages */
    .site-header, .page-header, header.page-header, .project-name, .project-tagline,
    .Header, .AppHeader, .application-main > header,
    .markdown-body > h1:first-child,                        /* alguns temas empurram um H1 azul */
    body > header[role="banner"].site-header,               /* tema padrão */
    body > .page-header                                    /* fallback */
    { display:none !important; height:0 !important; overflow:hidden !important; }

    /* Faixa fixa no topo (reforça Workshop gratuito • ao vivo) */
    .top-ribbon{
      position:sticky; top:0; z-index:1000;
      display:flex; justify-content:center; gap:12px; align-items:center; flex-wrap:wrap;
      padding:10px 14px;
      background:linear-gradient(90deg,var(--brand),var(--brand-2));
      color:#fff; box-shadow:0 8px 24px rgba(0,0,0,.35);
      font-weight:900; letter-spacing:.02em;
    }
    .top-ribbon .pill{
      display:inline-flex; align-items:center; gap:8px;
      background:rgba(255,255,255,.12);
      border:1px solid rgba(255,255,255,.22);
      padding:8px 12px; border-radius:999px;
      font-size:clamp(.9rem,2.4vw,1rem);
      white-space:nowrap;
    }

    .wrap{max-width:1080px;margin:0 auto;padding:24px}
    .hero{
      display:grid; gap:24px; align-items:center;
      grid-template-columns: 1.2fr .8fr;
      padding: clamp(18px,4.6vw,48px) 0;   /* encosta mais no topo */
    }
    .badge{
      display:inline-flex; gap:8px; align-items:center;
      background:linear-gradient(90deg,var(--brand),var(--brand-2));
      color:#fff; padding:10px 16px; border-radius:999px; font-weight:800; font-size:1rem;
      box-shadow:var(--shadow)
    }
    h1{font-size: clamp(2rem, 5vw, 3.2rem); margin:10px 0 8px; line-height:1.1}
    .sub{color:var(--muted); font-size: clamp(1rem, 2.2vw, 1.15rem); margin-bottom:18px}
    .cta{
      display:inline-flex; align-items:center; justify-content:center; gap:10px;
      background:linear-gradient(90deg,var(--brand-2),var(--brand));
      color:#fff; font-weight:800; letter-spacing:.2px;
      padding:16px 22px; border-radius:12px; text-decoration:none; box-shadow:var(--shadow);
      transition: transform .08s ease;
    }
    .cta:hover{transform: translateY(-1px)}
    .meta{display:flex; gap:14px; flex-wrap:wrap; margin:10px 0 24px}
    .chip{background:rgba(255,255,255,.06); color:var(--muted); border:1px solid rgba(255,255,255,.08); padding:8px 12px; border-radius:999px; font-size:.92rem}
    .card{
      background:linear-gradient(180deg, rgba(255,255,255,.04), rgba(255,255,255,.02));
      border:1px solid rgba(255,255,255,.08);
      border-radius: var(--radius);
      padding:24px; box-shadow:var(--shadow)
    }
    .grid{display:grid; gap:18px}
    .nights{grid-template-columns: repeat(3,1fr)}
    .night h3{margin:0 0 8px}
    .night ul{margin:10px 0 0 18px}
    .why{grid-template-columns: repeat(2,1fr)}
    .notice{
      display:flex; align-items:center; gap:10px; color:#111; background:linear-gradient(90deg,#D1F7EC,#F6F0FF);
      border-radius:12px; padding:12px 14px; font-weight:600;
    }
    .sticky-bar{
      position:sticky; bottom:12px; z-index:100;
      display:flex; justify-content:center;
    }
    .sticky-inner{
      backdrop-filter: blur(10px);
      background: rgba(21, 23, 53, .75);
      border:1px solid rgba(255,255,255,.1);
      padding:10px; border-radius:14px; box-shadow:var(--shadow);
      display:flex; gap:12px; align-items:center;
    }
    .countdown{font-variant-numeric: tabular-nums; color:var(--warn); font-weight:700}
    footer{color:var(--muted); font-size:.9rem; padding:40px 0}
    .illus{
      aspect-ratio: 4/3; border-radius: var(--radius);
      background: radial-gradient(500px 400px at 30% 20%, rgba(111,92,210,.35), transparent 60%),
                  linear-gradient(180deg, rgba(255,255,255,.05), rgba(255,255,255,.02));
      border:1px solid rgba(255,255,255,.08);
      display:flex; align-items:center; justify-content:center;
      color:#cfc9ff; font-weight:700; letter-spacing:.5px;
    }
    .illus small{display:block; color:#bdb7ee; font-weight:600}
    @media (max-width: 900px){
      .hero{grid-template-columns:1fr}
      .nights{grid-template-columns:1fr}
      .why{grid-template-columns:1fr}
      .top-ribbon{justify-content:flex-start}
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
        if(ms < 0){ out.forEach(el=>el.textContent="começa hoje • 19h"); return; }
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
    "description":"3 Noites para soltar pesos do passado, liberar emoções que aprisionam e reescrever a história com leveza. Inscreva-se entrando no grupo de WhatsApp.",
    "organizer":{"@type":"Organization","name":"Mentoria O Seu Lugar"}
  }
  </script>

  <!-- Meta Pixel Code -->
  <script>
  !function(f,b,e,v,n,t,s)
  {if(f.fbq)return;n=f.fbq=function(){n.callMethod?
  n.callMethod.apply(n,arguments):n.queue.push(arguments)};
  if(!f._fbq)f._fbq=n;n.push=n;n;n.loaded=!0;n.version='2.0';
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
  <!-- End Meta Pixel Code -->
</head>

<body>
  <!-- Faixa fixa no topo -->
  <div class="top-ribbon" role="note" aria-label="Informação principal do evento">
    <span class="pill">🎉 Workshop gratuito</span>
    <span class="pill">🔴 Ao vivo no YouTube</span>
    <span class="pill">📅 23–25/10 • 🕖 19h</span>
  </div>

  <header class="wrap hero" role="banner" aria-label="Cabeçalho do workshop">
    <div>
      <span class="badge" aria-label="Workshop gratuito">Workshop gratuito • ao vivo no YouTube</span>
      <h1>A Vida Que Eu Quero Viver</h1>
      <p class="sub">3 Noites para soltar os barulhos da mente, liberar emoções que aprisionam e reescrever sua história com leveza.</p>
      <div class="meta" aria-label="Informações rápidas">
        <span class="chip">📅 23, 24 e 25 de outubro</span>
        <span class="chip">🕖 19h (ao vivo)</span>
        <span class="chip">🎥 YouTube</span>
        <span class="chip">⏳ Começa em: <span class="countdown" aria-live="polite">calculando…</span></span>
      </div>
      <a class="cta js-whatsapp"
         href="https://chat.whatsapp.com/CeXf6hjhBziAzvXl9HGFFp?mode=ems_copy_t"
         target="_blank"
         rel="noopener"
         aria-label="Entrar no grupo de WhatsApp e garantir minha vaga"
         data-track="whatsapp_header">💬 Entrar no grupo de WhatsApp</a>
      <p class="sub" style="margin-top:10px">❗ A confirmação e os links das aulas serão enviados apenas no grupo.</p>
    </div>
    <div class="illus card" role="img" aria-label="Ilustração do workshop">
      <div>
        WORKSHOP • 3 NOITES
        <small>Consciência • Liberação • Novo começo</small>
      </div>
    </div>
  </header>

  <main class="wrap" role="main">
    <section class="card" aria-labelledby="convite">
      <h2 id="convite">Um convite simples: Um novo começo</h2>
      <p>
        Se a sua vida parece <em>travada</em> e você sente um peso que não sabe explicar, este encontro é para você.
        O passado não muda — mas o peso que você carrega dele pode mudar. Em três noites, vamos sair do automático,
        diminuir o barulho interno e criar um caminho real de leveza.
      </p>
      <div class="notice" role="note">📩 Para participar, basta clicar no botão e entrar no grupo de WhatsApp.</div>
    </section>

    <section class="grid nights" aria-labelledby="noites" style="margin-top:22px">
      <h2 id="noites" style="grid-column:1/-1;margin:0 0 6px">o que vai rolar em cada noite</h2>

      <article class="card night" aria-label="Noite 1">
        <h3>🌌 Noite 1 — O Barulho Invisível da Mente</h3>
        <p>Como pensamentos acelerados e autocobrança nos afastam do essencial. O falso “estar ocupado” que esconde ansiedade.</p>
        <ul>
          <li>Identificar ruídos (produtividade-fuga, controle, comparação)</li>
          <li>Microprática de presença:</li>
          <li>Clareza do essencial (O que realmente importa agora)</li>
        </ul>
      </article>

      <article class="card night" aria-label="Noite 2">
        <h3>🔥 Noite 2 — Emoções que Sabotam Meus Passos</h3>
        <p>Quando uma emoção vale mais que uma vida inteira: Medo, Culpa, Vergonha e a arte de ressignificar.</p>
        <ul>
          <li>Mapa da emoção raiz (psico + neuro)</li>
          <li>Soltar com método: reconhecer → acolher → ressignificar → ancorar</li>
          <li>Exercício “da dor ao recurso”</li>
        </ul>
      </article>

      <article class="card night" aria-label="Noite 3">
        <h3>🌱 Noite 3 — Reescrevendo Meu Lugar no Mundo</h3>
        <p>Quem eu precisei ser para caber vs. Quem eu escolho ser agora. Pertencer sem carregar o que não é meu.</p>
        <ul>
          <li>Carta de compromisso: “A vida que eu quero viver”</li>
          <li>Equilíbrio dar/receber (Pertencimento saudável)</li>
          <li>Meditação de integração + próximos passos</li>
        </ul>
      </article>
    </section>

    <section class="grid why" aria-labelledby="porque" style="margin-top:22px">
      <h2 id="porque" style="grid-column:1/-1;margin:0 0 6px">por que participar</h2>
      <div class="card">
        <ul>
          <li>ONLINE, GRATUITO e direto ao ponto</li>
          <li>3 Encontros ao vivo com práticas reais (nada de teoria solta)</li>
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
    </section>

    <section class="card" aria-labelledby="cta2" style="margin-top:22px;text-align:center">
      <h2 id="cta2" style="margin-top:0">garanta sua vaga agora</h2>
      <p class="sub">As informações e links serão enviados somente dentro do grupo.</p>
      <a class="cta js-whatsapp"
         href="https://chat.whatsapp.com/CeXf6hjhBziAzvXl9HGFFp?mode=ems_copy_t"
         target="_blank"
         rel="noopener"
         data-track="whatsapp_mid">💬 Entrar no grupo de WhatsApp</a>
      <p class="sub" style="margin-top:10px">📅 23, 24 e 25/10 • 🕖 19h • 🎥 YouTube</p>
    </section>

    <div class="sticky-bar" aria-hidden="false">
      <div class="sticky-inner">
        <span>⏳ Começa em: <span class="countdown">calculando…</span></span>
        <a class="cta js-whatsapp"
           href="https://chat.whatsapp.com/CeXf6hjhBziAzvXl9HGFFp?mode=ems_copy_t"
           target="_blank"
           rel="noopener"
           data-track="whatsapp_sticky">💬 GARANTIR MINHA VAGA</a>
      </div>
    </div>
  </main>

  <footer class="wrap" role="contentinfo">
    <div style="opacity:.9">© <span id="y"></span> Mentoria O Seu Lugar • Todos os direitos reservados</div>
    <script>document.getElementById('y').textContent = new Date().getFullYear();</script>
  </footer>

  <!-- RASTREAMENTO DE CLIQUES NO WHATSAPP (Lead) -->
  <script>
    // Gatilho de Lead ao clicar nos botões que levam ao WhatsApp
    (function(){
      function trackLead(e){
        try{
          fbq && fbq('track', 'Lead', {
            content_name: 'WhatsApp Group Join',
            content_category: 'Workshop A Vida Que Eu Quero Viver',
            value: 0.00,
            currency: 'BRL'
          });
        }catch(err){}
      }
      document.addEventListener('click', function(ev){
        const a = ev.target.closest('a');
        if(!a) return;
        const href = a.getAttribute('href') || '';
        if (a.classList.contains('js-whatsapp') || href.includes('chat.whatsapp.com')){
          trackLead();
        }
      }, true);
    })();
  </script>
</body>
</html>
