
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Valente Store</title>
  <style>
    :root {
      --bg: #0f172a; --card: #111827; --surface: #0b1220; --text: #e5e7eb;
      --muted: #9ca3af; --brand: #8fb3ff; --accent: #5fd3a1; --border: #1f2937;
      --cta: #8fb3ff; --cta-contrast: #00121a;
    }
    html,body{height:100%}
    body{margin:0;background:linear-gradient(180deg,var(--bg),#0b1020 60%);color:var(--text);
      font:16px/1.5 system-ui,-apple-system,Segoe UI,Roboto,Ubuntu,'Helvetica Neue',Arial}
    a{color:inherit;text-decoration:none}

    header{position:sticky;top:0;z-index:20;background:rgba(11,18,32,.7);backdrop-filter:blur(8px);border-bottom:1px solid var(--border)}
    .container{max-width:1200px;margin:0 auto;padding:16px}
    .flex{display:flex;gap:12px;align-items:center;flex-wrap:wrap}
    .grow{flex:1 1 auto}

    .btn{border:1px solid var(--border);background:#111826;color:var(--text);padding:10px 14px;border-radius:999px;cursor:pointer;transition:.2s}
    .btn:hover{transform:translateY(-1px);border-color:#293446}
    .btn.primary-light{background:#111b2e;border-color:#24324a}
    .btn.dark{background:#0b1220;border-color:#1f2a3d}
    .btn.small{padding:6px 10px;border-radius:10px}
    .btn.active{outline:2px solid var(--brand)}

    input,select{background:#0c1322;color:var(--text);border:1px solid var(--border);border-radius:10px;padding:10px 12px}
    input::placeholder{color:var(--muted)}

    main{max-width:1200px;margin:24px auto;padding:0 16px;display:grid;grid-template-columns:1fr;gap:24px}
    h2{margin:24px 0 8px;font-size:20px;font-weight:700}
    .muted{color:var(--muted)}

    .grid{display:grid;gap:16px;grid-template-columns:repeat(auto-fill,minmax(220px,1fr))}
    .card{background:radial-gradient(1200px 600px at -10% -10%,#13203a 0%,#0c1426 50%,#0a1020 100%);
      border:1px solid #111a2a;border-radius:16px;overflow:hidden;box-shadow:0 10px 30px rgba(0,0,0,.35)}
    .card.dark{background:radial-gradient(1200px 600px at 110% -10%,#131b27 0%,#0a111e 50%,#081020 100%)}
    .card-img{position:relative;aspect-ratio:4/3;background:#0d1424}
    .card-img img{width:100%;height:100%;object-fit:cover;display:block}
    .card-badges{position:absolute;top:8px;left:8px;display:flex;gap:6px;flex-wrap:wrap}
    .badge{font-size:12px;border-radius:999px;padding:4px 8px;border:1px solid #264060;background:#0b1930;color:#c7dcff}
    .badge-yellow{background:#2a2108;border-color:#3b2e09;color:#ffea9c}
    .p-4{padding:14px}
    .title{font-weight:700;min-height:44px}
    .desc{color:var(--muted);font-size:13px;min-height:38px}
    .row{display:flex;align-items:center;justify-content:space-between;gap:8px;margin:8px 0}
    .price{font-weight:800;font-size:18px}
    .price-dark{color:#d8e3ff}

    /* toast */
    [data-role='toast'] .toast{background:#0b1426;border:1px solid #1a2a43;color:var(--text);padding:12px 14px;border-radius:12px;box-shadow:0 8px 24px rgba(0,0,0,.5)}
    .toast-title{font-weight:700}.toast-desc{color:var(--muted)}

    /* landing (hero) */
    .hero{display:grid;place-items:center;min-height:64vh;text-align:center;padding:40px 16px;position:relative;overflow:hidden}
    .hero h1{font-size:clamp(32px,6vw,64px);line-height:1.05;margin:0 0 12px;font-weight:900;letter-spacing:-.02em}
    .hero p{color:var(--muted);font-size:clamp(14px,2.4vw,18px);margin:0 0 22px}
    .hero .glow{position:absolute;inset:-30%;background:
      radial-gradient(600px 300px at 50% 40%,rgba(0,191,255,.12),transparent 60%),
      radial-gradient(600px 300px at 50% 60%,rgba(255,79,216,.10),transparent 60%);filter:blur(42px);opacity:.9;pointer-events:none}
    .brand-strip{display:flex;gap:10px;justify-content:center;flex-wrap:wrap;margin-top:10px}
    .brand-pill{border:1px solid var(--border);background:#0b1424;color:var(--text);padding:8px 14px;border-radius:999px;font-weight:700;letter-spacing:.02em}

    /* signup (discreto, canto) */
    .signup-widget{position:fixed;right:12px;bottom:12px;z-index:60;width:240px;max-width:calc(100% - 24px);
      background:rgba(8,12,20,.70);border:1px solid #152030;border-radius:12px;box-shadow:0 6px 16px rgba(0,0,0,.35);padding:8px;backdrop-filter:blur(4px);opacity:.85}
    .signup-widget h3{margin:0 0 4px;font-size:14px;font-weight:700}
    .signup-widget .sub{margin:0 0 6px;color:var(--muted);font-size:11px}
    .signup-widget .row{display:grid;gap:6px}
    .signup-widget .close{position:absolute;top:4px;right:4px;background:transparent;color:var(--muted);border:0;cursor:pointer;font-size:14px;opacity:.8}
    .signup-widget .actions{display:flex;gap:8px;justify-content:flex-end}
    .hidden{display:none!important}

    /* carrinho — botão carro + modal */
    .cart-car-fab{position:fixed;top:50%;right:16px;transform:translateY(-50%);z-index:90;display:none}
    .cart-car-fab button{position:relative;width:64px;height:64px;border-radius:50%;border:1px solid #15324a;background:linear-gradient(180deg,#0a1826,#08121e);color:#e6f7ff;cursor:pointer;box-shadow:0 10px 30px rgba(0,0,0,.45);display:grid;place-items:center}
    .cart-car-fab .badge-qty{position:absolute;top:-6px;right:-6px;min-width:22px;height:22px;padding:0 6px;border-radius:999px;background:var(--cta);color:var(--cta-contrast);font-size:12px;font-weight:900;display:grid;place-items:center;border:2px solid #08121e}
    .cart-modal-backdrop{position:fixed;inset:0;background:rgba(0,0,0,.6);backdrop-filter:blur(4px);display:none;z-index:80}
    .cart-modal{position:fixed;inset:0;display:none;place-items:center;z-index:81;pointer-events:none}
    .cart-modal .panel{pointer-events:all;width:min(720px,92vw);max-height:80vh;overflow:auto;background:linear-gradient(180deg,#0c1426,#091224);border:1px solid #132036;border-radius:16px;box-shadow:0 20px 60px rgba(0,0,0,.55);padding:16px}
    .cart-modal .panel header{position:sticky;top:0;background:transparent;border:0;display:flex;justify-content:space-between;align-items:center;padding:0 0 8px;margin-bottom:8px}
    .cart-modal .close{background:transparent;border:0;color:var(--muted);cursor:pointer;font-size:18px}

    /* temas por segmento (sem azul no feminino) */
    html[data-segment="landing"]{--brand:#8fb3ff;--cta:#8fb3ff;--cta-contrast:#00121a}
    html[data-segment="feminino"]{--cta:#ff4fd8;--cta-contrast:#1a0010}
    html[data-segment="masculino"]{--cta:#00bfff;--cta-contrast:#00121a}
  </style>
</head>
<body>
  <div data-role="toast" style="display:none;position:fixed;right:16px;bottom:16px;z-index:80"></div>

  <!-- áudio de introdução (landing) -->
  <audio id="intro-audio" preload="auto" loop autoplay muted class="hidden">
    <source src="intro.mp3.mp3" type="audio/mpeg" />
    <source src="intro.mp3" type="audio/mpeg" />
  </audio>

  <!-- cadastro -->
  <div class="signup-widget" id="signup-widget">
    <button class="close" data-action="signup-close" aria-label="Fechar cadastro">✕</button>
    <h3>Crie sua conta</h3>
    <p class="sub">Ganhe experiência melhor salvando preferências.</p>
    <div class="row">
      <input data-role="login-name" placeholder="Nome (opcional)" />
      <input data-role="login-email" placeholder="voce@email.com" />
      <label class="muted" style="display:flex;gap:6px;align-items:center"><input type="checkbox" data-role="login-client" /> Tornar-se cliente</label>
      <div class="actions"><button class="btn small" data-action="login">Começar</button></div>
    </div>
  </div>

  <header>
    <div class="container flex">
      <div class="flex" style="gap:8px">
        <button class="btn" data-action="go-landing">Home</button>
        <button class="btn" data-action="go-fem">Feminino</button>
        <button class="btn" data-action="go-mas">Masculino</button>
      </div>
      <div class="grow"></div>
      <div class="flex" style="gap:8px">
        <span class="muted">Olá, <strong data-role="user">Convidado</strong></span>
        <span class="muted">Itens: <b data-role="cart-count">0</b></span>
      </div>
    </div>
    <div class="container" style="padding-top:0">
      <div class="flex">
        <div class="flex" style="gap:8px">
          <button class="btn small" data-role="brand" data-value="all">Todas</button>
          <button class="btn small" data-role="brand" data-value="Nike">Nike</button>
          <button class="btn small" data-role="brand" data-value="Adidas">Adidas</button>
          <button class="btn small" data-role="brand" data-value="Lupo" data-lupo>Lupo</button>
        </div>
        <input class="grow" data-role="search" placeholder="Buscar produtos..." />
        <select data-role="category"></select>
        <select data-role="sort">
          <option value="relevancia">Relevância</option>
          <option value="preco_asc">Preço: menor ao maior</option>

