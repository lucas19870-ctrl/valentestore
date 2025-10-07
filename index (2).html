<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Loja Esportiva — Nike, Adidas e Lupo</title>
  <style>
    :root {
      --bg: #0f172a; /* slate-900 */
      --card: #111827; /* gray-900 */
      --surface: #0b1220;
      --text: #e5e7eb; /* gray-200 */
      --muted: #9ca3af; /* gray-400 */
      --brand: #60a5fa; /* blue-400 */
      --accent: #22c55e; /* green-500 */
      --warn: #eab308; /* yellow-500 */
      --danger: #ef4444; /* red-500 */
      --border: #1f2937; /* gray-800 */
    }
    html,body { height: 100%; }
    body {
      margin: 0; background: linear-gradient(180deg, var(--bg), #0b1020 60%);
      color: var(--text); font: 16px/1.5 system-ui, -apple-system, Segoe UI, Roboto, Ubuntu, 'Helvetica Neue', Arial;
      -webkit-font-smoothing: antialiased; -moz-osx-font-smoothing: grayscale;
    }
    a { color: inherit; text-decoration: none; }

    header {
      position: sticky; top: 0; z-index: 20;
      background: rgba(11,18,32,.7); backdrop-filter: blur(8px);
      border-bottom: 1px solid var(--border);
    }
    .container { max-width: 1200px; margin: 0 auto; padding: 16px; }
    .flex { display: flex; gap: 12px; align-items: center; flex-wrap: wrap; }
    .grow { flex: 1 1 auto; }

    .btn { border: 1px solid var(--border); background: #111826; color: var(--text); padding: 10px 14px; border-radius: 999px; cursor: pointer; transition: .2s; }
    .btn:hover { transform: translateY(-1px); border-color: #293446; }
    .btn.primary-light { background: #111b2e; border-color: #24324a; }
    .btn.dark { background: #0b1220; border-color: #1f2a3d; }
    .btn.active { outline: 2px solid var(--brand); }
    .btn.small { padding: 6px 10px; border-radius: 10px; }

    input, select { background: #0c1322; color: var(--text); border: 1px solid var(--border); border-radius: 10px; padding: 10px 12px; }
    input::placeholder { color: var(--muted); }

    main { max-width: 1200px; margin: 24px auto; padding: 0 16px; display: grid; grid-template-columns: 1fr; gap: 24px; }

    h2 { margin: 24px 0 8px; font-size: 20px; font-weight: 700; }
    .muted { color: var(--muted); }

    .grid { display: grid; gap: 16px; grid-template-columns: repeat( auto-fill, minmax(220px, 1fr) ); }
    .card { background: radial-gradient(1200px 600px at -10% -10%, #13203a 0%, #0c1426 50%, #0a1020 100%); border: 1px solid #111a2a; border-radius: 16px; overflow: hidden; box-shadow: 0 10px 30px rgba(0,0,0,.35); }
    .card.dark { background: radial-gradient(1200px 600px at 110% -10%, #131b27 0%, #0a111e 50%, #081020 100%); }
    .card-img { position: relative; aspect-ratio: 4/3; background: #0d1424; }
    .card-img img { width: 100%; height: 100%; object-fit: cover; display: block; }
    .card-badges { position: absolute; top: 8px; left: 8px; display: flex; gap: 6px; flex-wrap: wrap; }
    .badge { font-size: 12px; border-radius: 999px; padding: 4px 8px; border: 1px solid #264060; background: #0b1930; color: #c7dcff; }
    .badge.neon-light { border-color: #355f9c; }
    .badge.neon-dark { box-shadow: var(--accent-glow) var(--accent2); color: var(--accent2); }
    .badge-yellow { background: #2a2108; border-color: #3b2e09; color: #ffea9c; }

    .p-4 { padding: 14px; }
    .title { font-weight: 700; min-height: 44px; }
    .desc { color: var(--muted); font-size: 13px; min-height: 38px; }
    .row { display: flex; align-items: center; justify-content: space-between; gap: 8px; margin: 8px 0; }
    .price { font-weight: 800; font-size: 18px; }
    .price-dark { color: #d8e3ff; }

    /* Carrinho lateral antigo (oculto por padrão) */
    aside { display: none; }

    /* Toast */
    [data-role='toast'] .toast { background: #0b1426; border: 1px solid #1a2a43; color: var(--text); padding: 12px 14px; border-radius: 12px; box-shadow: 0 8px 24px rgba(0,0,0,.5); }
    .toast-title { font-weight: 700; }
    .toast-desc { color: var(--muted); }

    footer { max-width: 1200px; margin: 32px auto; padding: 16px; color: var(--muted); text-align: center; border-top: 1px solid var(--border); }

    /* ===== Temas por segmento ===== */
    html[data-segment="landing"] {
      /* paleta neutra (cinza/azul suave) */
      --bg: #0f1620; --card: #111824; --surface: #0c131e; --text: #e7eaf0; --muted: #a7b0bd;
      --brand: #8fb3ff; --accent: #5fd3a1; --warn: #f2cf66; --danger: #ff8a8a; --border: #1a2433;
    }

    /* Feminino — preto + rosa neon */
    html[data-segment="feminino"] { --accent: #ff4fd8; --accent2: #ff1fb3; --card-bg: rgba(255,79,216,0.08); --accent-glow: 0 0 20px #ff4fd8; }
    html[data-segment="feminino"] .badge.neon-light { border-color: #ff4fd8; background: #160818; color: #ffd6f1; }
    html[data-segment="feminino"] .badge.neon-dark  { border-color: #ff3ca5; background: #130714; color: #ffd6f1; }
    html[data-segment="feminino"] .price { color: #ffd6f1; }
    html[data-segment="feminino"] .btn.primary-light { background: linear-gradient(180deg,#120617,#0c0812); border-color: #3a0b2b; box-shadow: 0 0 0 0 rgba(255,79,216,0.4); }
    html[data-segment="feminino"] .btn.primary-light:hover { border-color: #ff4fd8; box-shadow: 0 0 0 2px rgba(255,79,216,0.15); }
    html[data-segment="feminino"] .card { border-color: #1a0e1a; background: radial-gradient(1200px 600px at -10% -10%, #18081c 0%, #100515 50%, #0a0610 100%); }

    /* Masculino — preto + azul neon (azure) */
    html[data-segment="masculino"] {
      --bg: #060a12; --card: #0b101a; --surface: #090d14; --text: #e6f7ff; --muted: #a0b3c9;
      --brand: #00bfff; --accent: #1ecfff; --warn: #ffd633; --danger: #ff6666; --border: #122033;
    }
    html[data-segment="masculino"] .badge.neon-light { border-color: #1ecfff; background: #061420; color: #cceeff; box-shadow: 0 0 12px #00bfff; }
    html[data-segment="masculino"] .badge.neon-dark  { border-color: #00bfff; background: #05101a; color: #e0f8ff; box-shadow: 0 0 12px #1ecfff; }
    html[data-segment="masculino"] .price { color: #cceeff; }
    html[data-segment="masculino"] .btn.dark { background: linear-gradient(180deg,#0a1826,#08121e); border-color: #0e3a56; box-shadow: 0 0 0 0 rgba(0,191,255,0.4); }
    html[data-segment="masculino"] .btn.dark:hover { border-color: #00bfff; box-shadow: 0 0 0 2px rgba(0,191,255,0.15); }
    html[data-segment="masculino"] .card { border-color: #0e243a; background: radial-gradient(1200px 600px at -10% -10%, #0b1a2a 0%, #081524 50%, #06101a 100%); }

    /* ===== Widget de cadastro (canto, discreto) ===== */
    .signup-widget { position: fixed; right: 12px; bottom: 12px; z-index: 60; width: 240px; max-width: calc(100% - 24px); background: rgba(8,12,20,.70); border: 1px solid #152030; border-radius: 12px; box-shadow: 0 6px 16px rgba(0,0,0,.35); padding: 8px; backdrop-filter: blur(4px); opacity: 0.85; }
    .signup-widget h3 { margin: 0 0 4px; font-size: 14px; font-weight: 700; }
    .signup-widget .sub { margin: 0 0 6px; color: var(--muted); font-size: 11px; }
    .signup-widget .row { display: grid; gap: 6px; }
    .signup-widget .close { position: absolute; top: 4px; right: 4px; background: transparent; color: var(--muted); border: 0; cursor: pointer; font-size: 14px; opacity: 0.8; }
    .signup-widget .actions { display: flex; gap: 8px; justify-content: flex-end; }
    .hidden { display: none !important; }

    /* ===== HERO (landing) ===== */
    .hero { display: grid; place-items: center; min-height: 64vh; text-align: center; padding: 40px 16px; position: relative; overflow: hidden; }
    .hero h1 { font-size: clamp(32px, 6vw, 64px); line-height: 1.05; margin: 0 0 12px; font-weight: 900; letter-spacing: -0.02em; }
    .hero p { color: var(--muted); font-size: clamp(14px, 2.4vw, 18px); margin: 0 0 22px; }
    .hero .glow { position: absolute; inset: -30%; background: radial-gradient(600px 300px at 50% 40%, rgba(0,191,255,0.12), transparent 60%), radial-gradient(600px 300px at 50% 60%, rgba(255,79,216,0.10), transparent 60%); filter: blur(42px); opacity: .9; pointer-events: none; }
    .brand-strip { display: flex; gap: 10px; justify-content: center; flex-wrap: wrap; margin-top: 10px; }
    .brand-pill { border: 1px solid var(--border); background: #0b1424; color: var(--text); padding: 8px 14px; border-radius: 999px; font-weight: 700; letter-spacing: .02em; }

    /* ===== Botão carrinho (carro) + Modal ===== */
    .cart-car-fab { position: fixed; top: 50%; right: 16px; transform: translateY(-50%); z-index: 90; display: none; }
    .cart-car-fab button { position: relative; width: 64px; height: 64px; border-radius: 50%; border: 1px solid #15324a; background: linear-gradient(180deg,#0a1826,#08121e); color: #e6f7ff; cursor: pointer; box-shadow: 0 10px 30px rgba(0,0,0,.45); display: grid; place-items: center; }
    .cart-car-fab button:hover { box-shadow: 0 14px 36px rgba(0,0,0,.55); border-color: var(--cta); }
    .cart-car-fab svg { width: 32px; height: 32px; display: block; }
    .cart-car-fab .badge-qty { position: absolute; top: -6px; right: -6px; min-width: 22px; height: 22px; padding: 0 6px; border-radius: 999px; background: var(--cta); color: var(--cta-contrast); font-size: 12px; font-weight: 900; display: grid; place-items: center; border: 2px solid #08121e; }

    .cart-modal-backdrop { position: fixed; inset: 0; background: rgba(0,0,0,.6); backdrop-filter: blur(4px); display: none; z-index: 80; }
    .cart-modal { position: fixed; inset: 0; display: none; place-items: center; z-index: 81; pointer-events: none; }
    .cart-modal .panel { pointer-events: all; width: min(720px, 92vw); max-height: 80vh; overflow: auto; background: linear-gradient(180deg,#0c1426,#091224); border: 1px solid #132036; border-radius: 16px; box-shadow: 0 20px 60px rgba(0,0,0,.55); padding: 16px; }
    .cart-modal .panel header { position: sticky; top: 0; background: transparent; border: 0; display: flex; justify-content: space-between; align-items: center; padding: 0 0 8px; margin-bottom: 8px; }
    .cart-modal .close { background: transparent; border: 0; color: var(--muted); cursor: pointer; font-size: 18px; }
  
    /* Variáveis de destaque por segmento para evitar azul no feminino */
    :root { --cta: #8fb3ff; --cta-contrast: #00121a; }
    html[data-segment="feminino"] { --cta: #ff4fd8; --cta-contrast: #1a0010; }
    html[data-segment="masculino"] { --cta: #00bfff; --cta-contrast: #00121a; }
  </style>
</head>
<body>
  <div data-role="toast" style="display:none;position:fixed;right:16px;bottom:16px;z-index:80"></div>

  <!-- Áudio de introdução (toca apenas na landing, até escolher o segmento) -->
  <audio id="intro-audio" preload="auto" loop autoplay muted class="hidden">
    <source src="intro.mp3.mp3" type="audio/mpeg" />
    <source src="intro.mp3" type="audio/mpeg" />
  </audio>

  <!-- Widget de cadastro (discreto, canto) -->
  <div class="signup-widget" id="signup-widget">
    <button class="close" data-action="signup-close" aria-label="Fechar cadastro">✕</button>
    <h3>Crie sua conta</h3>
    <p class="sub">Ganhe uma experiência melhor salvando suas preferências.</p>
    <div class="row">
      <input data-role="login-name" placeholder="Nome (opcional)" />
      <input data-role="login-email" placeholder="voce@email.com" />
      <label class="muted" style="display:flex;gap:6px;align-items:center"><input type="checkbox" data-role="login-client" /> Tornar-se cliente</label>
      <div class="actions">
        <button class="btn small" data-action="login">Começar</button>
      </div>
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
          <option value="preco_desc">Preço: maior ao menor</option>
          <option value="rating">Avaliação</option>
        </select>
      </div>
    </div>
  </header>

  <main>
    <!-- HERO (Landing) -->
    <section class="hero" data-role="hero">
      <div class="glow"></div>
      <div>
        <h1>bem vindo a <span style="background:linear-gradient(90deg,#ff4fd8,#00bfff); -webkit-background-clip:text; background-clip:text; color:transparent;">valente store</span></h1>
        <p>Moda esportiva moderna, rápida e do seu jeito. Escolha seu universo e comece agora.</p>
        <div class="brand-strip">
          <span class="brand-pill">Nike</span>
          <span class="brand-pill">Adidas</span>
          <span class="brand-pill">Lupo</span>
        </div>
        <div style="margin-top:18px; display:flex; gap:10px; justify-content:center; flex-wrap:wrap;">
          <button class="btn" data-action="go-fem">Entrar no Feminino</button>
          <button class="btn" data-action="go-mas">Entrar no Masculino</button>
        </div>
      </div>
    </section>

    <!-- Conteúdo de catálogo/sugestões -->
    <section data-role="content">
      <div class="row" style="margin: 8px 0 16px">
        <span class="muted"><b data-role="count">0</b> produtos</span>
      </div>

      <h2 data-role="suggestions-title">Sugestões</h2>
      <div data-role="suggestions" class="grid"></div>

      <section data-role="catalog-section">
        <h2>Catálogo</h2>
        <div data-role="grid" class="grid"></div>
      </section>
    </section>

    <!-- Lateral antiga (mantida, mas oculta) -->
    <aside>
      <h2>Seu carrinho</h2>
      <div data-role="cart-list"></div>
      <div class="row" style="margin-top:8px">
        <input data-role="coupon-input" placeholder="Cupom (OFF10)" />
        <div class="flex">
          <button class="btn small" data-action="apply-coupon">Aplicar</button>
          <button class="btn small" data-action="remove-coupon">Remover</button>
        </div>
      </div>
      <div style="margin-top:8px" data-role="cart-totals"></div>
      <div class="flex" style="margin-top:8px">
        <button class="btn primary-light" data-action="checkout">Finalizar</button>
        <button class="btn" data-action="clear-cart">Limpar</button>
      </div>
    </aside>
  </main>

  <!-- Botão carrinho (carro) e modal -->
  <div class="cart-car-fab" id="cart-car-fab">
    <button data-action="open-cart" aria-label="Abrir carrinho">
      <!-- Ícone de carro (SVG) -->
      <svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path d="M3 13l1-3.5A3 3 0 0 1 6.88 7H17.1a3 3 0 0 1 2.85 2.06L21 13v4a1 1 0 0 1-1 1h-1a2 2 0 1 1 0-4h-2a2 2 0 1 1 0 4H7a2 2 0 1 1 0-4H5a2 2 0 1 1 0 4H4a1 1 0 0 1-1-1v-4z" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round"/>
      </svg>
      <span class="badge-qty" data-role="cart-badge">0</span>
    </button>
  </div>
  <div class="cart-modal-backdrop" id="cart-backdrop"></div>
  <div class="cart-modal" id="cart-modal" aria-hidden="true">
    <div class="panel">
      <header>
        <h3 style="margin:0">Seu carrinho</h3>
        <button class="close" data-action="close-cart" aria-label="Fechar">✕</button>
      </header>
      <div data-role="cart-list-modal"></div>
      <div style="margin-top:12px" data-role="cart-totals-modal"></div>
      <div class="flex" style="margin-top:12px; justify-content:flex-end; gap:8px;">
        <input data-role="coupon-input" placeholder="Cupom (OFF10)" style="max-width:220px" />
        <button class="btn small" data-action="apply-coupon">Aplicar</button>
        <button class="btn small" data-action="remove-coupon">Remover</button>
        <button class="btn primary-light" data-action="checkout">Finalizar</button>
      </div>
    </div>
  </div>

  <footer class="container">Demo educacional. Marcas e imagens pertencem aos respectivos proprietários.</footer>

  <script>
  /* =========================
     JS da loja
  ========================= */
  const BRL = new Intl.NumberFormat("pt-BR", { style: "currency", currency: "BRL" });
  const clamp = (n, min = 0) => (n < min ? min : n);
  const Segment = { LANDING: "landing", FEM: "feminino", MAS: "masculino" };
  function validateEmail(email) { return /^[^\s@]+@[^\s@]+\.[^\s@]{2,}$/.test(email); }

  const PRODUCTS = [
    { id: "f1", name: "Camiseta Nike Dri-FIT Feminina", brand: "Nike", price: 12990, category: "Vestuário", gender: "Feminino", image: "https://images.unsplash.com/photo-1547949003-9792a18a2601?q=80&w=1200&auto=format&fit=crop", rating: 4.7, stock: 24, description: "Tecido respirável para treino e casual." },
    { id: "f2", name: "Calça Jogger Adidas Feminina", brand: "Adidas", price: 15990, category: "Vestuário", gender: "Feminino", image: "https://images.unsplash.com/photo-1591047139829-d91aecb6caea?q=80&w=1200&auto=format&fit=crop", rating: 4.6, stock: 18, description: "Conforto com 3 listras icônicas." },
    { id: "f3", name: "Top Lupo Seamless", brand: "Lupo", price: 7990, category: "Underwear", gender: "Feminino", image: "https://images.unsplash.com/photo-1592876545807-9f3b6f3f7d73?q=80&w=1200&auto=format&fit=crop", rating: 4.5, stock: 40, description: "Sem costura, suporte e conforto diário." },
    { id: "f4", name: "Legging Lupo Emana", brand: "Lupo", price: 12990, category: "Underwear", gender: "Feminino", image: "https://images.unsplash.com/photo-1559087867-ce4c91325525?q=80&w=1200&auto=format&fit=crop", rating: 4.6, stock: 22, description: "Tecnologia Emana com compressão moderada." },
    { id: "f5", name: "Jaqueta Corta-Vento Adidas", brand: "Adidas", price: 21990, category: "Vestuário", gender: "Feminino", image: "https://assets.adidas.com/images/w_600,f_auto,q_auto/cc13a12d2f4543a3851faed6016f6ef6_9366/Windbreaker_Jacket_Black_HL9211_21_model.jpg", rating: 4.7, stock: 12, description: "Proteção leve para o dia a dia." },
    { id: "m1", name: "Camiseta Nike Sportswear", brand: "Nike", price: 14990, category: "Vestuário", gender: "Masculino", image: "https://static.nike.com/a/images/t_PDP_1280_v1/f_auto,q_auto:eco/6a42a01f-f94a-44a5-84ec-22c44f4bea7a/sportswear-t-shirt-nike.png", rating: 4.6, stock: 35, description: "Algodão macio para o dia a dia." },
    { id: "m2", name: "Moletom Nike Club Fleece", brand: "Nike", price: 24990, category: "Vestuário", gender: "Masculino", image: "https://static.nike.com/a/images/t_PDP_1280_v1/f_auto,q_auto:eco/f55b8af3-8765-47f2-b94d-3c17a16b80a4/club-fleece-pullover-hoodie.png", rating: 4.7, stock: 15, description: "Macio e confortável com capuz clássico." },
    { id: "m3", name: "Camiseta Adidas Essentials", brand: "Adidas", price: 12990, category: "Vestuário", gender: "Masculino", image: "https://assets.adidas.com/images/w_600,f_auto,q_auto/7e0876a3d7b9429fa427ad2200d4ff68_9366/Essentials_Logo_Tee_Black_HS3231_21_model.jpg", rating: 4.5, stock: 30, description: "Básica com logo adidas estampado." },
    { id: "m4", name: "Adidas Superstar", brand: "Adidas", price: 39990, category: "Calçados", gender: "Masculino", image: "https://assets.adidas.com/images/w_600,f_auto,q_auto/17e38b8120a54a88a28dad2a01354ad8_9366/Superstar_Shoes_White_FV3284_01_standard.jpg", rating: 4.8, stock: 18, description: "Clássico com as 3 listras." },
    { id: "u1", name: "Meia Esportiva Pack 3", brand: "Outros", price: 4990, category: "Acessórios", gender: "Unissex", image: "https://images.unsplash.com/photo-1582582621959-48d0b665b2f1?q=80&w=1200&auto=format&fit=crop", rating: 4.4, stock: 50, description: "Conforto diário com ótimo custo-benefício." },
  ];

  function computeSubtotal(items) { return items.reduce((acc, it) => acc + it.price * it.qty, 0); }
  function computeShipping(subtotal) { return subtotal > 25000 || subtotal === 0 ? 0 : 1990; }
  function computeDiscount(subtotal, coupon) { if (!coupon) return 0; if (coupon === "OFF10") return Math.floor(subtotal * 0.1); return 0; }
  function computeTotals(items, coupon) {
    const subtotal = computeSubtotal(items);
    const discount = computeDiscount(subtotal, coupon);
    const shipping = computeShipping(subtotal);
    const total = subtotal - discount + shipping;
    return { subtotal, discount, shipping, total };
  }

  const STORAGE = { CART: "loja_cart_v1", USER: "loja_user_v1", SEG: "loja_pref_segment_v1" };
  const State = { segment: Segment.LANDING, search: "", category: "todas", brand: "all", sort: "relevancia", cart: [], coupon: "", couponApplied: null, user: null };
  function loadState(){ try{ const c=localStorage.getItem(STORAGE.CART); if(c) State.cart=JSON.parse(c); const u=localStorage.getItem(STORAGE.USER); if(u) State.user=JSON.parse(u); const s=localStorage.getItem(STORAGE.SEG); if(s) State.segment=s; }catch{} }
  function persistCart(){ try{ localStorage.setItem(STORAGE.CART, JSON.stringify(State.cart)); }catch{} }
  function persistUser(){ try{ localStorage.setItem(STORAGE.USER, JSON.stringify(State.user)); }catch{} }
  function persistSeg(){ try{ if(State.segment!==Segment.LANDING) localStorage.setItem(STORAGE.SEG, State.segment); }catch{} }

  function listCategories(){
    const base = PRODUCTS.filter(p => {
      if(State.segment===Segment.LANDING) return true;
      if(State.segment===Segment.FEM) return p.gender==="Feminino";
      return p.gender==="Masculino" || p.gender==="Unissex";
    });
    return ["todas", ...Array.from(new Set(base.map(p=>p.category)))];
  }

  function filteredProducts(){
    if(State.segment===Segment.LANDING) return [];
    const pool = PRODUCTS.filter(p=>{
      const genderMatch = State.segment===Segment.FEM ? p.gender==="Feminino" : (p.gender==="Masculino" || p.gender==="Unissex");
      const brandMatch = State.brand==="all" ? true : p.brand===State.brand;
      const catMatch = State.category==="todas" ? true : p.category===State.category;
      const searchMatch = p.name.toLowerCase().includes(State.search.toLowerCase());
      return genderMatch && brandMatch && catMatch && searchMatch;
    });
    let list = [...pool];
    switch(State.sort){
      case "preco_asc": list.sort((a,b)=>a.price-b.price); break;
      case "preco_desc": list.sort((a,b)=>b.price-a.price); break;
      case "rating": list.sort((a,b)=>b.rating-a.rating); break;
      default:
        list.sort((a,b)=> Number(b.name.toLowerCase().includes(State.search.toLowerCase())) - Number(a.name.toLowerCase().includes(State.search.toLowerCase())));
    }
    return list;
  }

  function suggestions(){
    const isFem = State.segment===Segment.FEM;
    const baseFilter = (p) => p.category !== "Acessórios";

    let pool;
    if(State.segment===Segment.LANDING){
      pool = PRODUCTS.filter(baseFilter);
    } else {
      pool = PRODUCTS.filter(p =>
        (isFem ? p.gender === "Feminino" : (p.gender === "Masculino" || p.gender === "Unissex")) &&
        baseFilter(p) &&
        (p.brand === "Nike" || p.brand === "Adidas" || (isFem && p.brand === "Lupo"))
      );
    }

    const inBudget = pool.filter(p => p.price <= 15000 && p.rating >= 4.4);
    const scored = inBudget.map(p => ({ p, score: (p.rating * 1000) / Math.max(1, p.price) }))
                           .sort((a,b)=>b.score-a.score)
                           .map(x=>x.p);
    const fallback = [...pool].sort((a,b)=>a.price-b.price);
    return (scored.length ? scored : fallback).slice(0,6);
  }

  function addToCart(id, qty=1){
    const prod = PRODUCTS.find(p=>p.id===id);
    const currentQty = State.cart.find(i=>i.id===id)?.qty ?? 0;
    const max = prod?.stock ?? Infinity;
    if(currentQty+qty>max){ toast("Estoque insuficiente", "Quantidade solicitada excede o estoque disponível."); return; }
    const found = State.cart.find(i=>i.id===id);
    if(found) found.qty += qty; else State.cart.push({id, qty});
    State.cart = State.cart.filter(i=>i.qty>0); persistCart(); toast("Adicionado ao carrinho", "Item incluído com sucesso."); render();
  }
  function setQty(id, qty){ State.cart = State.cart.map(i => i.id===id ? {...i, qty: clamp(qty,0)} : i).filter(i=>i.qty>0); persistCart(); render(); }
  function removeItem(id){ State.cart = State.cart.filter(i=>i.id!==id); persistCart(); render(); }
  function clearCart(){ State.cart=[]; State.couponApplied=null; persistCart(); render(); }
  function applyCoupon(){ const code=(State.coupon||"").trim().toUpperCase(); if(!code) return; if(code==="OFF10"){ State.couponApplied=code; toast("Cupom aplicado","Desconto de 10% nos itens."); } else { State.couponApplied=null; toast("Cupom inválido","Verifique o código e tente novamente."); } render(); }
  function removeCoupon(){ State.couponApplied=null; render(); }

  function loginOrCreate({email,name,isClient}){
    if(!validateEmail(email)){ toast("Email inválido","Insira um email válido."); return; }
    State.user = { email, name: name||undefined, isClient: !!isClient, preferredSegment: State.segment!==Segment.LANDING ? State.segment : undefined };
    persistUser(); toast(`Bem-vindo${name ? ", "+name : ""}!`, isClient?"Conta de cliente criada.":"Login como convidado."); render();
  }
  function toggleClient(){ if(!State.user) return; State.user.isClient=!State.user.isClient; persistUser(); toast(State.user.isClient?"Agora você é cliente":"Agora você é convidado"); render(); }
  function logout(){ State.user=null; try{ localStorage.removeItem(STORAGE.USER); }catch{} toast("Você saiu da conta"); render(); }

  let toastTimer=null;
  function toast(title, description){ const box=document.querySelector("[data-role='toast']"); if(!box) return; box.innerHTML = `
    <div class="toast" role="status" aria-live="polite">
      <div class="toast-title">${title}</div>
      ${description ? `<div class="toast-desc">${description}</div>` : ""}
    </div>
  `; box.style.display='block'; clearTimeout(toastTimer); toastTimer=setTimeout(()=>{ box.style.display='none'; }, 3200); }

  // ===== Cart modal utils =====
  function openCartModal(){
    const b = document.getElementById('cart-backdrop'); if (b) b.style.display='block';
    const m = document.getElementById('cart-modal'); if (m) { m.style.display='grid'; m.setAttribute('aria-hidden','false'); }
    document.addEventListener('keydown', escCloseCartOnce);
  }
  function closeCartModal(){
    const b = document.getElementById('cart-backdrop'); if (b) b.style.display='none';
    const m = document.getElementById('cart-modal'); if (m) { m.style.display='none'; m.setAttribute('aria-hidden','true'); }
    document.removeEventListener('keydown', escCloseCartOnce);
  }
  function escCloseCartOnce(e){ if(e.key==='Escape') closeCartModal(); }
  function updateCartFab(){
    const fab = document.getElementById('cart-car-fab');
    const badge = document.querySelector('[data-role="cart-badge"]');
    const count = State.cart.reduce((a,b)=>a+b.qty,0);
    if (badge) badge.textContent = count;
    if (fab) fab.style.display = count > 0 ? 'block' : 'none';
  }

  function stars(n){ return "★".repeat(Math.round(n)); }
  function price(n){ return BRL.format(n/100); }

  function renderProducts(container, list, { showCheapBadge=false }={}){
    if(!container) return;
    container.innerHTML = list.map(p=>{
      const cheapBadge = showCheapBadge ? `<span class=\"badge ${State.segment===Segment.MAS?'neon-dark':'neon-light'}\">Bom & Barato</span>` : "";
      return `
      <div class="card ${State.segment===Segment.MAS?'dark':''}">
        <div class="card-img">
          <img src="${p.image}" alt="${p.name}" />
          <div class="card-badges">
            <span class="badge ${State.segment===Segment.MAS?'neon-dark':'neon-light'}">${p.brand}</span>
            <span class="badge">${p.category}</span>
            ${cheapBadge}
          </div>
        </div>
        <div class="p-4">
          <div class="title">${p.name}</div>
          <div class="desc">${p.description||""}</div>
          <div class="row">
            <div class="price ${State.segment===Segment.MAS?'price-dark':''}">${price(p.price)}</div>
            <div class="badge badge-yellow">${stars(p.rating)}</div>
          </div>
          <button class="btn ${State.segment===Segment.MAS?'dark':'primary-light'}" data-action="add" data-id="${p.id}" ${( (p.stock ?? Infinity) - (State.cart.find(i=>i.id===p.id)?.qty ?? 0) <= 0) ? 'disabled' : ''}>
            ${((p.stock ?? Infinity) - (State.cart.find(i=>i.id===p.id)?.qty ?? 0) <= 0) ? 'Esgotado' : 'Adicionar'}
          </button>
        </div>
      </div>
    `;
    }).join("");
    container.querySelectorAll("[data-action='add']").forEach(btn=> btn.addEventListener('click', ()=> addToCart(btn.dataset.id)) );
  }

  function renderCart(){
    const listEl=document.querySelector("[data-role='cart-list']");
    const totalsEl=document.querySelector("[data-role='cart-totals']");
    const listModal=document.querySelector("[data-role='cart-list-modal']");
    const totalsModal=document.querySelector("[data-role='cart-totals-modal']");
    const cartCountBadge=document.querySelector("[data-role='cart-count']");

    const detailed = State.cart.map(ci=>({...ci, product: PRODUCTS.find(p=>p.id===ci.id)})).filter(it=>!!it.product);

    const renderListHtml = (items) => items.map(({id,qty,product})=>`
      <div class='cart-row' style="display:grid;grid-template-columns:64px 1fr auto;gap:12px;padding:10px 0;border-bottom:1px dashed #1a2640;">
        <img src='${product.image}' alt='${product.name}' style="width:64px;height:64px;object-fit:cover;border-radius:10px;" />
        <div class='info'>
          <div class='name' style="font-weight:700">${product.name}</div>
          <div class='sub muted'>${product.brand} • ${product.category} • ${stars(product.rating)}</div>
          <div class='p' style="font-weight:700">${price(product.price)}</div>
        </div>
        <div class='qty' style="display:grid;grid-auto-flow:column;gap:8px;align-items:center;">
          <button data-action='qty-dec' data-id='${id}'>−</button>
          <div class='q'>${qty}</div>
          <button data-action='qty-inc' data-id='${id}'>+</button>
          <button data-action='remove' data-id='${id}'>🗑</button>
        </div>
      </div>`).join("");

    const totals = computeTotals(detailed.map(it=>({price:it.product.price, qty:it.qty})), State.couponApplied);
    const totalsHtml = `
      <div class='row'><span>Subtotal</span><span>${price(totals.subtotal)}</span></div>
      ${totals.discount>0 ? `<div class='row green'><span>Desconto (${State.couponApplied})</span><span>-${price(totals.discount)}</span></div>` : ""}
      <div class='row'><span>Frete</span><span>${totals.shipping===0 ? `<span class='free'>Grátis</span>` : price(totals.shipping)}</span></div>
      <div class='row total'><span>Total</span><span>${price(totals.total)}</span></div>`;

    if (listEl) listEl.innerHTML = detailed.length ? renderListHtml(detailed) : `<div class='muted'>Seu carrinho está vazio.</div>`;
    if (totalsEl) totalsEl.innerHTML = detailed.length ? totalsHtml : '';
    if (listModal) listModal.innerHTML = detailed.length ? renderListHtml(detailed) : `<div class='muted'>Seu carrinho está vazio.</div>`;
    if (totalsModal) totalsModal.innerHTML = detailed.length ? totalsHtml : '';

    document.querySelectorAll("[data-action='qty-dec']").forEach(b=> b.addEventListener('click', ()=> setQty(b.dataset.id, (State.cart.find(i=>i.id===b.dataset.id)?.qty ?? 1)-1)) );
    document.querySelectorAll("[data-action='qty-inc']").forEach(b=> b.addEventListener('click', ()=> setQty(b.dataset.id, (State.cart.find(i=>i.id===b.dataset.id)?.qty ?? 0)+1)) );
    document.querySelectorAll("[data-action='remove']").forEach(b=> b.addEventListener('click', ()=> removeItem(b.dataset.id)) );

    if(cartCountBadge) cartCountBadge.textContent = detailed.reduce((a,b)=>a+b.qty,0);

    updateCartFab();
    if (!detailed.length) closeCartModal();
  }

  function setupIntroAudio(){
    const audio = document.getElementById('intro-audio');
    if(!audio) return;
    audio.volume = 0.4;
    if(State.segment === Segment.LANDING){
      const tryPlay = () => {
        audio.play().catch(()=>{});
        window.removeEventListener('pointerdown', tryPlay);
        window.removeEventListener('keydown', tryPlay);
      };
      window.addEventListener('pointerdown', tryPlay);
      window.addEventListener('keydown', tryPlay);
    } else {
      try{ audio.pause(); audio.currentTime = 0; }catch{}
    }
  }

  function render(){
    const root=document.documentElement; root.setAttribute('data-segment', State.segment);

    const searchInput=document.querySelector("[data-role='search']");
    const brandBtns=document.querySelectorAll("[data-role='brand']");
    const catSelect=document.querySelector("[data-role='category']");
    const sortSelect=document.querySelector("[data-role='sort']");

    if (catSelect) {
      const cats = listCategories();
      const prev = State.category;
      catSelect.innerHTML = cats.map(c => `<option value="${c}">${c}</option>`).join("");
      if (!cats.includes(prev)) State.category = "todas";
      catSelect.value = State.category;
    }

    const lupoBtn = document.querySelector('[data-lupo]');
    if (lupoBtn) lupoBtn.style.display = (State.segment === Segment.FEM) ? 'inline-flex' : 'none';
    if (State.segment !== Segment.FEM && State.brand === 'Lupo') State.brand = 'all';

    if (searchInput) searchInput.value = State.search;
    brandBtns.forEach(btn => btn.classList.toggle('active', btn.dataset.value === State.brand));
    if (sortSelect) sortSelect.value = State.sort;

    // LANDING vs SEGMENTOS
    const hero = document.querySelector('[data-role="hero"]');
    const content = document.querySelector('[data-role="content"]');
    const isLanding = State.segment === Segment.LANDING;
    if (hero && content) { hero.style.display = isLanding ? '' : 'none'; content.style.display = isLanding ? 'none' : ''; }

    const countEl=document.querySelector("[data-role='count']");
    const list=filteredProducts();
    if(countEl) countEl.textContent=String(list.length);

    if (!isLanding) {
      const suggestionsEl = document.querySelector('[data-role="suggestions"]');
      const suggestionsTitle = document.querySelector('[data-role="suggestions-title"]');
      if (suggestionsTitle) suggestionsTitle.textContent = 'Sugestões (bons & baratos)';
      renderProducts(suggestionsEl, suggestions(), {showCheapBadge:true});
    } else {
      const suggestionsEl = document.querySelector('[data-role="suggestions"]');
      const suggestionsTitle = document.querySelector('[data-role="suggestions-title"]');
      if (suggestionsEl) suggestionsEl.innerHTML = '';
      if (suggestionsTitle) suggestionsTitle.textContent = '';
    }

    renderProducts(document.querySelector("[data-role='grid']"), list);

    renderCart();

    const userEl=document.querySelector("[data-role='user']");
    if(userEl) userEl.textContent = State.user ? (State.user.name || State.user.email.split('@')[0]) : 'Convidado';

    setupIntroAudio();
  }

  function bindEvents(){
    // Segmentos
    document.addEventListener('click', (e)=>{
      const fem = e.target.closest('[data-action="go-fem"]');
      const mas = e.target.closest('[data-action="go-mas"]');
      const home = e.target.closest('[data-action="go-landing"]');
      if (fem){ State.segment=Segment.FEM; persistSeg(); render(); }
      if (mas){ State.segment=Segment.MAS; persistSeg(); render(); }
      if (home){ State.segment=Segment.LANDING; render(); }

      const brandBtn = e.target.closest('[data-role="brand"]');
      if (brandBtn){ State.brand = brandBtn.dataset.value; render(); }

      const apply = e.target.closest('[data-action="apply-coupon"]'); if (apply) applyCoupon();
      const rem = e.target.closest('[data-action="remove-coupon"]'); if (rem) removeCoupon();

      const checkout = e.target.closest('[data-action="checkout"]'); if (checkout) toast('Checkout iniciado','Simulação de pagamento');
      const clearBtn = e.target.closest('[data-action="clear-cart"]'); if (clearBtn) clearCart();

      const loginBtn = e.target.closest('[data-action="login"]');
      if (loginBtn){
        const email=document.querySelector("[data-role='login-email']")?.value||"";
        const name=document.querySelector("[data-role='login-name']")?.value||"";
        const client=document.querySelector("[data-role='login-client']")?.checked||false;
        loginOrCreate({email,name,isClient:client});
        document.getElementById('signup-widget')?.classList.add('hidden');
      }
      const toggleClientBtn = e.target.closest('[data-action="toggle-client"]'); if (toggleClientBtn) toggleClient();
      const logoutBtn = e.target.closest('[data-action="logout"]'); if (logoutBtn) logout();

      const closeSignup = e.target.closest('[data-action="signup-close"]'); if (closeSignup) document.getElementById('signup-widget')?.classList.add('hidden');

      const openCart = e.target.closest('[data-action="open-cart"]'); if (openCart) openCartModal();
      const closeCart = e.target.closest('[data-action="close-cart"]'); if (closeCart) closeCartModal();
    });

    const backdrop=document.getElementById('cart-backdrop'); if(backdrop) backdrop.addEventListener('click', closeCartModal);

    const searchInput=document.querySelector("[data-role='search']"); if(searchInput) searchInput.addEventListener('input', e=>{ State.search=e.target.value; render(); });
    const catSelect=document.querySelector("[data-role='category']"); if(catSelect) catSelect.addEventListener('change', e=>{ State.category=e.target.value; render(); });
    const sortSelect=document.querySelector("[data-role='sort']"); if(sortSelect) sortSelect.addEventListener('change', e=>{ State.sort=e.target.value; render(); });

    const couponInputs=document.querySelectorAll("[data-role='coupon-input']"); couponInputs.forEach(i=> i.addEventListener('input', e=>{ State.coupon=e.target.value; }));
  }

  function boot(){ loadState(); bindEvents(); render(); }
  if(document.readyState==='loading') document.addEventListener('DOMContentLoaded', boot); else boot();

  // =========================
  // Auto-tests (adicionados)
  // =========================
  (function tests(){
    // Totais / frete / cupom
    const t1=computeTotals([],null); console.assert(t1.subtotal===0 && t1.discount===0 && t1.shipping===0 && t1.total===0, 't1');
    const t2=computeTotals([{price:10000,qty:1}],null); console.assert(t2.total===11990,'t2');
    const t3=computeTotals([{price:30000,qty:1}],"OFF10"); console.assert(t3.total===27000,'t3');
    const t4=computeTotals([{price:9999,qty:1}],"OFF10"); console.assert(t4.discount===999,'t4');
    const t5=computeTotals([{price:15000,qty:1}],"FOO"); console.assert(t5.discount===0,'t5');
    const t6=computeTotals([{price:25000,qty:1}],null); console.assert(t6.shipping===1990,'t6');
    const t7=computeTotals([{price:26000,qty:1}],"OFF10"); console.assert(t7.shipping===0 && t7.total===23400,'t7');
    console.assert(validateEmail('a@b.com')===true,'email ok');
    console.assert(validateEmail('a@b')===false,'email invalido');

    // Sugestões — garantias por segmento
    const prev = {...State};
    try{
      State.segment = Segment.LANDING; let s = suggestions(); console.assert(Array.isArray(s) && s.length<=6, 'sug landing len');
      State.segment = Segment.FEM; s = suggestions(); console.assert(s.every(p=>p.gender==='Feminino') || s.length===0, 'sug fem gender');
      State.segment = Segment.MAS; s = suggestions(); console.assert(s.every(p=>p.gender==='Masculino' || p.gender==='Unissex') || s.length===0, 'sug mas gender');
    } finally { Object.assign(State, prev); }

    // Filtro: na landing não deve listar produtos
    State.segment = Segment.LANDING; console.assert(filteredProducts().length===0,'landing sem produtos');
    State.segment = Segment.FEM; console.assert(filteredProducts().every(p=>p.gender==='Feminino'), 'fem somente feminino');
    State.segment = Segment.MAS; console.assert(filteredProducts().every(p=>p.gender==='Masculino' || p.gender==='Unissex'), 'masc masculino/unissex');

    console.log('%c✔ auto-tests passaram','color:#16a34a;font-weight:bold');
  })();
  </script>
  <script>
    // Re-define setupIntroAudio to garantir autoplay (muted) na landing e desmute no primeiro gesto
    function setupIntroAudio(){
      var audio = document.getElementById('intro-audio');
      if(!audio) return;
      var targetVol = 0.4;
      if (State.segment === Segment.LANDING) {
        try { audio.muted = true; audio.volume = targetVol; audio.play().catch(function(){}); } catch(e){}
        var tryUnmute = function(){
          if (State.segment === Segment.LANDING) {
            try { audio.muted = false; audio.volume = targetVol; audio.play().catch(function(){}); } catch(e){}
          }
          window.removeEventListener('pointerdown', tryUnmute, true);
          window.removeEventListener('keydown', tryUnmute, true);
        };
        window.addEventListener('pointerdown', tryUnmute, true); // capture para ocorrer antes do clique que troca segmento
        window.addEventListener('keydown', tryUnmute, true);
      } else {
        try { audio.pause(); audio.currentTime = 0; audio.muted = true; } catch(e){}
      }
    }
    // chama uma vez no final para garantir o estado correto ao carregar
    try { setupIntroAudio(); } catch(e){}
  </script>
</body>
</html>
