<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Gyula Kosice — En tiempo real</title>
  <link href="https://fonts.googleapis.com/css2?family=Syne:wght@700;800&family=Chivo+Mono:wght@300;400&display=swap" rel="stylesheet" />
  <style>
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    :root {
      --black: #0a0a0a;
      --dark: #111111;
      --card: #161616;
      --cyan: #00e5d1;
      --white: #f0ede8;
      --muted: #888;
      --rule: #2a2a2a;
    }

    html { scroll-behavior: smooth; }

    body {
      background: var(--black);
      color: var(--white);
      font-family: 'Chivo Mono', monospace;
      font-weight: 400;
      font-size: 15px;
      line-height: 1.7;
    }

    /* ── TYPOGRAPHY ── */
    h1, h2, h3, h4, .label {
      font-family: 'Syne', sans-serif;
      font-weight: 700;
      text-transform: uppercase;
      letter-spacing: 0.04em;
      line-height: 1.05;
    }

    .label {
      font-size: 10px;
      letter-spacing: 0.18em;
      color: var(--cyan);
    }

    /* ── NAV ── */
    nav {
      position: fixed;
      top: 0; left: 0; right: 0;
      z-index: 100;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 18px 48px;
      background: rgba(10,10,10,0.85);
      backdrop-filter: blur(8px);
      border-bottom: 1px solid var(--rule);
    }

    .nav-logo {
      font-family: 'Syne', sans-serif;
      font-weight: 700;
      font-size: 13px;
      letter-spacing: 0.14em;
      text-transform: uppercase;
      color: var(--white);
      text-decoration: none;
    }

    .nav-logo span { color: var(--cyan); }

    nav ul {
      list-style: none;
      display: flex;
      gap: 36px;
    }

    nav ul a {
      font-family: 'Chivo Mono', monospace;
      font-size: 11px;
      letter-spacing: 0.12em;
      text-transform: uppercase;
      color: var(--muted);
      text-decoration: none;
      transition: color .2s;
    }

    nav ul a:hover { color: var(--cyan); }

    /* ── HERO ── */
    .hero {
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: flex-end;
      padding: 0 48px 80px;
      position: relative;
      overflow: hidden;
      background: radial-gradient(ellipse at 70% 40%, #0d2a2a 0%, var(--black) 65%);
    }

    .hero::before {
      content: '';
      position: absolute;
      inset: 0;
      background: 
        radial-gradient(circle at 78% 38%, rgba(0,229,209,0.07) 0%, transparent 55%),
        radial-gradient(circle at 20% 80%, rgba(0,229,209,0.04) 0%, transparent 40%);
      pointer-events: none;
    }

    /* floating particles */
    .hero-particles {
      position: absolute;
      inset: 0;
      overflow: hidden;
      pointer-events: none;
    }
    .particle {
      position: absolute;
      border-radius: 50%;
      background: var(--cyan);
      opacity: 0.15;
      animation: drift linear infinite;
    }
    @keyframes drift {
      0%   { transform: translateY(0) scale(1);   opacity: .15; }
      50%  { transform: translateY(-30px) scale(1.2); opacity: .25; }
      100% { transform: translateY(0) scale(1);   opacity: .15; }
    }

    .hero-dates {
      font-family: 'Chivo Mono', monospace;
      font-size: 12px;
      letter-spacing: 0.2em;
      color: var(--cyan);
      text-transform: uppercase;
      margin-bottom: 24px;
    }

    .hero h1 {
      font-size: clamp(64px, 10vw, 140px);
      line-height: 0.92;
      margin-bottom: 16px;
    }

    .hero-subtitle {
      font-family: 'Syne', sans-serif;
      font-weight: 700;
      font-size: clamp(22px, 3vw, 42px);
      color: var(--cyan);
      text-transform: uppercase;
      letter-spacing: 0.08em;
      margin-bottom: 32px;
    }

    .hero-venue {
      font-family: 'Chivo Mono', monospace;
      font-size: 13px;
      letter-spacing: 0.16em;
      color: var(--muted);
      text-transform: uppercase;
    }

    .hero-scroll {
      position: absolute;
      right: 48px;
      bottom: 80px;
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 10px;
      color: var(--muted);
      font-size: 10px;
      letter-spacing: 0.16em;
      text-transform: uppercase;
      font-family: 'Chivo Mono', monospace;
    }

    .scroll-line {
      width: 1px;
      height: 48px;
      background: linear-gradient(to bottom, var(--cyan), transparent);
      animation: scrollPulse 2s ease-in-out infinite;
    }

    @keyframes scrollPulse {
      0%, 100% { opacity: .4; }
      50% { opacity: 1; }
    }

    /* ── QUOTE BAND ── */
    .quote-band {
      background: var(--dark);
      border-top: 1px solid var(--rule);
      border-bottom: 1px solid var(--rule);
      padding: 64px 48px;
      text-align: center;
    }

    .quote-band blockquote {
      font-family: 'Chivo Mono', monospace;
      font-size: clamp(13px, 1.4vw, 16px);
      line-height: 1.9;
      color: var(--muted);
      max-width: 760px;
      margin: 0 auto;
      font-style: normal;
    }

    .quote-band blockquote em {
      color: var(--white);
      font-style: normal;
    }

    .quote-attr {
      margin-top: 24px;
      font-size: 11px;
      letter-spacing: 0.18em;
      color: var(--cyan);
      text-transform: uppercase;
    }

    /* ── SECTIONS ── */
    section {
      padding: 96px 48px;
      max-width: 1280px;
      margin: 0 auto;
    }

    .section-header {
      display: flex;
      align-items: flex-end;
      gap: 24px;
      margin-bottom: 56px;
      padding-bottom: 20px;
      border-bottom: 1px solid var(--rule);
    }

    .section-header h2 {
      font-size: clamp(28px, 4vw, 52px);
    }

    .section-header .label {
      padding-bottom: 6px;
    }

    /* ── EXPOSITION TEXT ── */
    .expo-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 48px;
    }

    .expo-grid p {
      font-size: 14px;
      line-height: 1.85;
      color: #b8b4ae;
    }

    .expo-grid p + p { margin-top: 20px; }

    /* ── BIO ── */
    .bio-layout {
      display: grid;
      grid-template-columns: 1fr 1.6fr;
      gap: 64px;
      align-items: start;
    }

    .bio-meta h3 {
      font-size: clamp(28px, 3vw, 44px);
      margin-bottom: 8px;
    }

    .bio-meta .years {
      font-family: 'Chivo Mono', monospace;
      font-size: 12px;
      color: var(--cyan);
      letter-spacing: 0.14em;
      text-transform: uppercase;
      margin-bottom: 36px;
    }

    .bio-timeline {
      list-style: none;
      display: flex;
      flex-direction: column;
      gap: 0;
    }

    .bio-timeline li {
      display: flex;
      gap: 20px;
      padding: 16px 0;
      border-bottom: 1px solid var(--rule);
      font-size: 13px;
      color: #b8b4ae;
    }

    .bio-timeline li:first-child { padding-top: 0; }

    .bio-timeline .yr {
      font-family: 'Syne', sans-serif;
      font-weight: 700;
      font-size: 12px;
      color: var(--cyan);
      letter-spacing: 0.1em;
      min-width: 44px;
      padding-top: 2px;
    }

    .bio-text p { font-size: 14px; line-height: 1.85; color: #b8b4ae; margin-bottom: 18px; }

    .bio-quote {
      margin-top: 32px;
      padding: 28px 32px;
      background: var(--card);
      border-left: 2px solid var(--cyan);
      font-size: 14px;
      line-height: 1.8;
      color: var(--white);
    }

    /* ── OBRAS ── */
    .obras-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 2px;
    }

    .obra-card {
      background: var(--card);
      padding: 32px 28px;
      position: relative;
      overflow: hidden;
      transition: background .25s;
    }

    .obra-card:hover { background: #1e1e1e; }

    .obra-card::before {
      content: '';
      position: absolute;
      top: 0; left: 0;
      width: 2px; height: 100%;
      background: var(--cyan);
      transform: scaleY(0);
      transform-origin: top;
      transition: transform .3s;
    }

    .obra-card:hover::before { transform: scaleY(1); }

    .obra-title {
      font-family: 'Syne', sans-serif;
      font-weight: 700;
      font-size: 15px;
      letter-spacing: 0.04em;
      text-transform: uppercase;
      margin-bottom: 10px;
      line-height: 1.2;
    }

    .obra-year {
      font-family: 'Chivo Mono', monospace;
      font-size: 11px;
      color: var(--cyan);
      letter-spacing: 0.14em;
      margin-bottom: 12px;
    }

    .obra-media {
      font-size: 11px;
      color: var(--muted);
      line-height: 1.6;
      text-transform: uppercase;
      letter-spacing: 0.06em;
    }

    .obra-dims {
      font-size: 11px;
      color: #555;
      margin-top: 6px;
      letter-spacing: 0.06em;
    }

    .obra-col {
      font-size: 10px;
      color: var(--cyan);
      margin-top: 12px;
      letter-spacing: 0.1em;
      text-transform: uppercase;
      opacity: .7;
    }

    /* ── INFO GRID ── */
    .info-band {
      background: var(--dark);
      border-top: 1px solid var(--rule);
    }

    .info-inner {
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      max-width: 1280px;
      margin: 0 auto;
    }

    .info-block {
      padding: 56px 40px;
      border-right: 1px solid var(--rule);
    }

    .info-block:last-child { border-right: none; }

    .info-block .label {
      display: block;
      margin-bottom: 16px;
    }

    .info-block p, .info-block address {
      font-style: normal;
      font-size: 13px;
      color: #b8b4ae;
      line-height: 1.7;
    }

    /* ── HORARIOS ── */
    .horario-item {
      display: flex;
      justify-content: space-between;
      align-items: baseline;
      padding: 10px 0;
      border-bottom: 1px solid var(--rule);
      font-size: 12px;
    }

    .horario-item:last-child { border-bottom: none; }

    .horario-item .days { color: var(--muted); }
    .horario-item .hours {
      font-family: 'Syne', sans-serif;
      font-size: 13px;
      color: var(--cyan);
    }

    /* ── CREDITS ── */
    .credits-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 32px 56px;
    }

    .credit-item .label { display: block; margin-bottom: 8px; }
    .credit-item p { font-size: 14px; color: var(--white); }

    /* ── LOGOS ── */
    .logos-bar {
      border-top: 1px solid var(--rule);
      padding: 48px 48px;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      gap: 24px;
    }

    .sponsors-svg {
      height: 30px;
      width: auto;
      max-width: 90%;
      filter: brightness(0.85);
      transition: filter .25s;
    }

    .sponsors-svg:hover { filter: brightness(1); }

    /* ── CASTAGNINO MACRO LOGO (SVG) ── */
    .cm-logo-svg {
      height: 13px;
      width: auto;
      display: block;
    }

    .nav-logo {
      display: flex;
      align-items: center;
    }

    /* ── FOOTER ── */
    footer {
      background: var(--black);
      border-top: 1px solid var(--rule);
      padding: 40px 48px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 24px;
    }

    footer .f-left { font-size: 11px; color: var(--muted); }
    footer .f-right {
      font-size: 11px;
      color: var(--muted);
      text-align: right;
    }
    footer a { color: var(--cyan); text-decoration: none; }

    /* ── RESPONSIVE ── */
    @media (max-width: 900px) {
      nav { padding: 16px 24px; }
      nav ul { gap: 20px; }
      .hero { padding: 0 24px 64px; }
      section { padding: 64px 24px; }
      .expo-grid, .bio-layout, .obras-grid, .info-inner, .credits-grid { grid-template-columns: 1fr; }
      .info-block { border-right: none; border-bottom: 1px solid var(--rule); }
      .logos-bar { padding: 32px 24px; gap: 32px; }
      footer { flex-direction: column; text-align: center; }
      footer .f-right { text-align: center; }
    }
  </style>
</head>
<body>

  <!-- NAV -->
  <nav>
    <a class="nav-logo" href="#">
      <svg class="cm-logo-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 161.169 12.636"><defs><style>.cls-1{fill:#fff;}</style></defs><g id="Capa_2" data-name="Capa 2"><g id="Portada_1_y_8" data-name="Portada 1 y 8"><g id="Layer_2" data-name="Layer 2"><g id="Capa_1-2" data-name="Capa 1"><path class="cls-1" d="M6.4,12.559H6.054a6.2,6.2,0,0,1,0-12.387H6.4v.969H6.065a5.218,5.218,0,0,0,0,10.431H6.4Z"/><path class="cls-1" d="M42.237,12.557h-.351A6.194,6.194,0,0,1,41.9.172h.352v.969L41.9,1.15a5.218,5.218,0,0,0-.368,10.411v-4.6h-.744V5.991h1.724v6.566Z"/><path class="cls-1" d="M14.5,12.55h-1l-.948-3.933H9.641L8.693,12.55H7.681L10.669.172h.852ZM9.876,7.641h2.439L11.1,2.577Z"/><path class="cls-1" d="M35.145,12.55h-1L33.2,8.617h-2.91l-.958,3.933h-1L31.3.172h.854ZM30.511,7.641H32.95L31.731,2.577Z"/><polygon class="cls-1" points="50.788 12.636 49.809 12.636 49.809 8.361 45.293 2.162 45.293 12.636 44.313 12.636 44.313 0.265 45.123 0.265 49.809 6.699 49.809 0.265 50.788 0.265 50.788 12.636"/><polygon class="cls-1" points="62.487 12.55 61.507 12.55 61.507 8.274 56.991 2.076 56.991 12.55 56.011 12.55 56.011 0.179 56.821 0.179 61.507 6.613 61.507 0.179 62.487 0.179 62.487 12.55"/><rect class="cls-1" x="52.976" y="0.179" width="0.975" height="12.371"/><path class="cls-1" d="M67.963,12.541A3.347,3.347,0,0,1,64.57,9.326v-5.9a3.4,3.4,0,0,1,6.787-.019V9.317a3.4,3.4,0,0,1-3.394,3.224m0-11.377a2.432,2.432,0,0,0-2.425,2.409V9.25a2.423,2.423,0,0,0,4.843-.082V3.454a2.422,2.422,0,0,0-2.418-2.29"/><path class="cls-1" d="M18.466,12.636A3.15,3.15,0,0,1,15.32,9.482V9.145h.973v.337a2.169,2.169,0,1,0,4.336.142c0-.047,0-.094,0-.142a2.157,2.157,0,0,0-.077-.57l-.1-.279a2,2,0,0,0-.165-.314,3.879,3.879,0,0,0-.654-.652l-.068-.047c-.27-.214-.593-.465-.968-.723-.621-.445-1.233-.848-1.559-1.064l-.149-.1a6.378,6.378,0,0,1-.559-.465,3.907,3.907,0,0,1-.272-.37,2.937,2.937,0,0,1-.435-1,3,3,0,0,1-.077-.668,2.968,2.968,0,0,1,5.935,0v.564h-.971V3.228a1.988,1.988,0,0,0-3.975,0,1.871,1.871,0,0,0,.016.249s.019.135.035.2v.025a2.337,2.337,0,0,0,.3.668,2.049,2.049,0,0,0,.331.371l.023.021a2.34,2.34,0,0,0,.286.2l.026.014L19.47,6.31c.265.193.5.372.7.538l.037.028a3.18,3.18,0,0,1,.868.87,1.789,1.789,0,0,1,.34.649,3.148,3.148,0,0,1-2.947,4.241"/><polygon class="cls-1" points="25.663 12.55 24.683 12.55 24.683 1.159 21.941 1.159 21.941 0.179 28.47 0.179 28.47 1.159 25.663 1.159 25.663 12.55"/></g></g><path class="cls-1" d="M127.245,11.274a5.262,5.262,0,0,1-1.552-2.206,7.925,7.925,0,0,1-.518-2.886,9.194,9.194,0,0,1,.218-1.988,7.444,7.444,0,0,1,.654-1.743,5.824,5.824,0,0,1,1.117-1.443A5.638,5.638,0,0,1,128.717,0h-8.742a4.558,4.558,0,0,1,.789.6,4.027,4.027,0,0,1,.545.79,4.143,4.143,0,0,1,.326.925h.026c.026.218.055.518.081.872.027.3.027.708.027,1.2V7.161c0,.98.026,1.771.054,2.37a7.463,7.463,0,0,0,.109,1.2v.026a2.574,2.574,0,0,0,.164.626c.11.218.219.435.326.625l.409.626h6.754a1.391,1.391,0,0,0-.3-.11A6.472,6.472,0,0,1,127.245,11.274Z"/><path class="cls-1" d="M117.823,2.7H117.8a2.4,2.4,0,0,0-.873-.435,7.189,7.189,0,0,0-1.416-.136h-.3a5.789,5.789,0,0,0-1.034.109,1.934,1.934,0,0,0-.79.3,1.871,1.871,0,0,0-.518.518,4.6,4.6,0,0,0-.409,1.034h-3.675l.164-.68a5.713,5.713,0,0,1,.463-1.307,4.918,4.918,0,0,1,.708-1.089,3.963,3.963,0,0,1,1.035-.818L111.4.028h-8.169A4.555,4.555,0,0,0,99.36,2.18,3.007,3.007,0,0,0,98.107.6,4.193,4.193,0,0,0,95.82.028,4.321,4.321,0,0,0,93.587.6a4.454,4.454,0,0,0-1.579,1.443V0H90.13V12.636h2.123v-6.4a7.805,7.805,0,0,1,.326-2.56A2.532,2.532,0,0,1,93.7,2.314a2.955,2.955,0,0,1,1.662-.464,1.966,1.966,0,0,1,1.688.68,3.458,3.458,0,0,1,.518,2.1v8.007h2.123V5.473a3.782,3.782,0,0,1,.873-2.751,2.935,2.935,0,0,1,2.206-.872,2.488,2.488,0,0,1,1.279.326,1.707,1.707,0,0,1,.735.9,3.416,3.416,0,0,1,.19,1.117v8.442H110.8a4.042,4.042,0,0,1-.818-.518,3.857,3.857,0,0,1-1.089-1.334,3.566,3.566,0,0,1-.381-1.688,4.333,4.333,0,0,1,.136-1.034,3.334,3.334,0,0,1,.435-.953,4.169,4.169,0,0,1,.626-.79,4.337,4.337,0,0,1,.789-.6,4.787,4.787,0,0,1,.9-.463,7.935,7.935,0,0,1,.98-.3c.273-.055.572-.136.953-.19.326-.027.763-.081,1.225-.136.245-.026.435-.055.653-.081.681-.081,1.28-.164,1.8-.245.49-.081.872-.164,1.224-.245V3.977A1.6,1.6,0,0,0,117.823,2.7Z"/><path class="cls-1" d="M115.208,7.544l-.19.026c-.464.055-.872.136-1.2.19a5,5,0,0,0-.709.191,1.644,1.644,0,0,0-.38.218.783.783,0,0,0-.274.245c-.054.109-.109.19-.163.3a1.124,1.124,0,0,0-.027.326.893.893,0,0,0,.109.463.847.847,0,0,0,.355.409,1.445,1.445,0,0,0,.653.3,3.8,3.8,0,0,0,1.035.136,6.986,6.986,0,0,0,.789-.054c.136-.027.245-.055.381-.082a3.745,3.745,0,0,0,.979-.326,4.269,4.269,0,0,0,.79-.518,3.073,3.073,0,0,0,.518-.653,3.373,3.373,0,0,0,.218-.681c.027-.3.055-.625.082-1.034-.274.081-.545.136-.873.219C116.706,7.325,116,7.434,115.208,7.544Z"/><path class="cls-1" d="M144.755.435a5.072,5.072,0,0,0-1.362,1.717V0h-7.242a4.452,4.452,0,0,1,.49.3,4.843,4.843,0,0,1,1.417,1.362,5.056,5.056,0,0,1,.789,1.823l.136.6-3.759.026a2.707,2.707,0,0,0-.381-.9,2.406,2.406,0,0,0-.572-.6,2.9,2.9,0,0,0-.79-.354,3.722,3.722,0,0,0-.979-.136,4.1,4.1,0,0,0-1.444.245,3.048,3.048,0,0,0-1.143.68,3.244,3.244,0,0,0-.626.926c-.026.081-.054.163-.081.245a6.2,6.2,0,0,0-.245,1.851,6.345,6.345,0,0,0,.245,1.907c.027.081.055.19.081.273a3.064,3.064,0,0,0,.6.9,3.058,3.058,0,0,0,1.089.68,3.807,3.807,0,0,0,1.389.245,3.938,3.938,0,0,0,1.172-.164,2.831,2.831,0,0,0,.9-.463,1.985,1.985,0,0,0,.626-.709,5.524,5.524,0,0,0,.381-1.334h3.785l-.136.681a5.606,5.606,0,0,1-.79,2.042,5.515,5.515,0,0,1-1.5,1.579,5.819,5.819,0,0,1-1.717.925h8.524V6.155a7.664,7.664,0,0,1,.354-2.423,2.183,2.183,0,0,1,.789-1.143,2.079,2.079,0,0,1,1.253-.409,4.645,4.645,0,0,1,1.553.19V.273A3.517,3.517,0,0,0,146.117,0,2.465,2.465,0,0,0,144.755.435Z"/><path class="cls-1" d="M159.236,1.334A5.994,5.994,0,0,0,155.316,0c-.152,0-.3.009-.446.018-.148-.009-.294-.018-.446-.018A6,6,0,0,0,150.5,1.334a6.193,6.193,0,0,0-1.933,4.983,6.4,6.4,0,0,0,1.634,4.712,5.723,5.723,0,0,0,4.22,1.607c.15,0,.3,0,.446-.016.148.009.3.016.446.016a5.723,5.723,0,0,0,4.22-1.607,6.4,6.4,0,0,0,1.633-4.712A6.186,6.186,0,0,0,159.236,1.334Z"/><path class="cls-1" d="M79.983,9.12V6.909h-2.2V5.727h2.2V3.516H81.2V5.727h2.189V6.909H81.2V9.12Z"/></g></g></svg>
    </a>
    <ul>
      <li><a href="#exposicion">Exposición</a></li>
      <li><a href="#obras">Obras</a></li>
      <li><a href="#biografia">Biografía</a></li>
      <li><a href="#visita">Visita</a></li>
    </ul>
  </nav>

  <!-- HERO -->
  <header class="hero">
    <div class="hero-particles" id="particles"></div>
    <div class="hero-dates">30 ABR — 17 AGO 2026</div>
    <h1>GYULA<br>KOSICE</h1>
    <div class="hero-subtitle">En tiempo real</div>
    <div class="hero-venue">Museo Castagnino · Rosario, Argentina</div>
    <div class="hero-scroll">
      <div class="scroll-line"></div>
      Scroll
    </div>
  </header>

  <!-- QUOTE BAND -->
  <div class="quote-band">
    <blockquote>
      <em>"Progresivamente habrá que ahondar en las posibilidades y el comportamiento que ofrece la medida cúbica, el volumen líquido. Habrá que permutar su conducta poética y su exacta naturaleza interior, cambiante y móvil"</em>
    </blockquote>
    <p class="quote-attr">— Kosice, 1959</p>
  </div>

  <!-- EXPOSICIÓN -->
  <section id="exposicion">
    <div class="section-header">
      <span class="label">Sobre la muestra</span>
      <h2>Exposición</h2>
    </div>
    <div class="expo-grid">
      <div>
        <p>
          <em style="color:var(--white); font-style:normal;">Gyula Kosice: En tiempo real</em> es la primera exposición individual en Rosario del artista argentino Gyula Kosice (1924–2016), un vanguardista único e inclasificable, pionero en el cruce entre el arte, la ciencia y la tecnología, y figura central en el arte nacional e internacional del siglo XX.
        </p>
        <p>
          Curada por Jazmín Adler, esta exhibición nos invita a zambullirnos en el universo kosiceano conformado por obras con agua, luz y movimiento, proyectos utópicos, experimentaciones con materialidades novedosas, sueños sensibles, y poesía acuosa y porvenirista.
        </p>
        <p>
          La exposición marca el regreso de las obras del artista a la Argentina luego de su paso por el Museum of Fine Arts of Houston, e incluye piezas de la década del cuarenta hasta otras realizadas ya entrado el siglo XXI, procedentes tanto del Museo Kosice como de distintas colecciones públicas y privadas del país, entre ellas el MNBA, Malba, MACBA y Planetario de Buenos Aires.
        </p>
      </div>
      <div>
        <p>
          El concepto de <em style="color:var(--white); font-style:normal;">tiempo real</em> en el campo de las artes remite a aquellas prácticas cuyos procesos de acción y recepción se corresponden temporalmente: las transformaciones experimentadas por las obras coinciden sincrónicamente con el tiempo del público. En lugar de representar acontecimientos pasados o construir ficciones diferidas, el arte en tiempo real sucede en el mismo momento en que es experimentado.
        </p>
        <p>
          La exhibición incluye una sala dedicada a las relaciones de Kosice con artistas rosarinos como Antonio Berni y Lucio Fontana, una instalación realizada especialmente para la ocasión por la artista Mariana De Matteis, y una sala con obras contemporáneas de la Colección Castagnino+macro que dan cuenta de los devenires recientes de aquellas búsquedas tempranamente inauguradas por Kosice.
        </p>
        <p>
          Es a través de la dimensión de tiempo real que Kosice articula las búsquedas de las primeras vanguardias con preocupaciones que definirán la esfera del arte contemporáneo: la participación activa del público, la obsolescencia y variabilidad de la obra, la generatividad, la primacía de la experiencia sobre el objeto cerrado y terminado.
        </p>
      </div>
    </div>
  </section>

  <!-- OBRAS -->
  <section id="obras" style="padding-top:0;">
    <div class="section-header">
      <span class="label">Selección</span>
      <h2>Obras expuestas</h2>
    </div>
    <div class="obras-grid">

      <div class="obra-card">
        <div class="obra-year">1944</div>
        <div class="obra-title">Röyi</div>
        <div class="obra-media">Escultura articulada y móvil</div>
        <div class="obra-dims">Primera obra articulada y móvil con participación del espectador en América Latina</div>
      </div>

      <div class="obra-card">
        <div class="obra-year">1949</div>
        <div class="obra-title">Dos espacios.<br>Pintura Madí</div>
        <div class="obra-media">Esmalte sobre madera</div>
        <div class="obra-dims">77 × 46 × 1 cm</div>
        <div class="obra-col">Colección Castagnino+macro</div>
      </div>

      <div class="obra-card">
        <div class="obra-year">1964–2004</div>
        <div class="obra-title">La Ciudad Hidroespacial en la constelación de Vivian</div>
        <div class="obra-media">Instalación</div>
        <div class="obra-col">Museo Kosice</div>
      </div>

      <div class="obra-card">
        <div class="obra-year">1968</div>
        <div class="obra-title">Gota de agua móvil con círculos</div>
        <div class="obra-media">Acrílico, luz, agua móvil</div>
        <div class="obra-dims">65 × 50 × 23 cm</div>
        <div class="obra-col">Museo Kosice</div>
      </div>

      <div class="obra-card">
        <div class="obra-year">1988</div>
        <div class="obra-title">Móvil de luz</div>
        <div class="obra-media">Plexiglás (acrílico), lámparas coloreadas y madera</div>
        <div class="obra-dims">45 × 45 × 13 cm</div>
        <div class="obra-col">Museo Kosice</div>
      </div>

      <div class="obra-card">
        <div class="obra-year">2005</div>
        <div class="obra-title">Escultura lumínica gas neón</div>
        <div class="obra-media">Gas neón</div>
        <div class="obra-dims">76 × 26 × 23 cm</div>
        <div class="obra-col">Fundación Kosice</div>
      </div>

      <div class="obra-card">
        <div class="obra-year">2009</div>
        <div class="obra-title">Homenaje a Moholy-Nagy</div>
        <div class="obra-media">Acrílico, agua móvil, luz móvil LED, gas neón</div>
        <div class="obra-dims">79 × 61 × 15 cm</div>
        <div class="obra-col">Museo Kosice</div>
      </div>

    </div>
  </section>

  <!-- BIOGRAFÍA -->
  <section id="biografia">
    <div class="section-header">
      <span class="label">El artista</span>
      <h2>Biografía</h2>
    </div>
    <div class="bio-layout">
      <div class="bio-meta">
        <h3>Gyula<br>Kosice</h3>
        <p class="years">Kosice, 1924 — Buenos Aires, 2016</p>
        <ul class="bio-timeline">
          <li><span class="yr">1924</span><span>Nace el 26 de abril como Ferdinand Fallik, en una familia húngara. Adopta el nombre de su ciudad natal.</span></li>
          <li><span class="yr">1928</span><span>Llega a Argentina a los cuatro años. Más tarde se naturaliza argentino.</span></li>
          <li><span class="yr">1944</span><span>Crea Röyi, primera escultura articulada y móvil de Latinoamérica. Integra el grupo editor de la revista Arturo.</span></li>
          <li><span class="yr">1945</span><span>Participa en exposiciones en las casas de Enrique Pichon-Rivière y Grete Stern. Co-funda Arte Concreto-Invención.</span></li>
          <li><span class="yr">1946</span><span>Funda el Arte Madí, lo nombra y escribe su manifiesto. Dirige la revista Arte Madí Universal (8 números).</span></li>
          <li><span class="yr">1948</span><span>Invitado a exponer en el Salon des Réalités Nouvelles de París. Madí se consagra internacionalmente.</span></li>
          <li><span class="yr">1950s</span><span>Incorpora luz neón, agua y movimiento permanente en sus obras. Inicia esculturas hidrocinéticas.</span></li>
          <li><span class="yr">1970s</span><span>Crea la Ciudad Hidroespacial, proyecto urbanístico-poético con hábitats suspendidos en el aire.</span></li>
          <li><span class="yr">2016</span><span>Fallece el 25 de mayo en Buenos Aires, a los 92 años, tras 50 exposiciones individuales y más de 500 colectivas.</span></li>
        </ul>
      </div>
      <div class="bio-text">
        <p>
          Gyula Kosice fue un vanguardista único e inclasificable, pionero en el cruce entre el arte, la ciencia y la tecnología. Nacido Ferdinand Fallik en Kosice, Eslovaquia, tomó el nombre de su ciudad natal como modo perpetuo de recordarla. Llegó a la Argentina a los cuatro años, en 1928.
        </p>
        <p>
          Estudió dibujo y modelado en academias de cursos libres, y asistió por un período breve a la Escuela de Bellas Artes Manuel Belgrano. Atraído por el uso de nuevos materiales, experimentó con plexiglás, vidrio y tubos de gas de neón. Más adelante, a su interés por el movimiento, le sumó el uso del agua y empezó a hacer esculturas hidrocinéticas.
        </p>
        <p>
          A partir de su afirmación "El hombre no ha de terminar en la tierra", a comienzos de los años setenta creó la Ciudad Hidroespacial, un proyecto urbanístico, artístico y poético que propone hábitats suspendidos en el aire a partir de la energía contenida en el agua. La mayor parte de esta obra se encuentra hoy en el Museum of Fine Arts of Houston.
        </p>
        <p>
          Hizo cincuenta exposiciones individuales e integró más de 500 muestras colectivas. Publicó 18 libros. Sus obras figuran en museos y colecciones privadas de Argentina, Latinoamérica, Estados Unidos, Europa y Asia.
        </p>
        <blockquote class="bio-quote">
          "Si la obra de arte, si mi obra de arte no habla, entonces no valgo nada; la obra tiene que hablar por sí misma, a través de su presencia y su creación. Hay una predisposición a considerar el arte solamente como una superestructura, pero es más que eso."
          <br><br>
          <span style="font-size:11px; color:var(--cyan); letter-spacing:.14em; text-transform:uppercase;">— Kosice, 2011</span>
        </blockquote>
      </div>
    </div>
  </section>

  <!-- HORARIOS E INFO -->
  <div class="info-band" id="visita">
    <div class="info-inner">
      <div class="info-block">
        <span class="label">Horarios de visita</span>
        <div class="horario-item">
          <span class="days">Martes a viernes</span>
          <span class="hours">13 — 19 h</span>
        </div>
        <div class="horario-item">
          <span class="days">Sábados, domingos y feriados</span>
          <span class="hours">10 — 19 h</span>
        </div>
      </div>
      <div class="info-block">
        <span class="label">Visitas acompañadas para todo público</span>
        <div class="horario-item">
          <span class="days">Miércoles a viernes</span>
          <span class="hours">17 h</span>
        </div>
        <div class="horario-item">
          <span class="days">Sábado, domingo y feriados</span>
          <span class="hours">11 y 17 h</span>
        </div>
      </div>
      <div class="info-block">
        <span class="label">Ubicación</span>
        <address>
          <p>Museo Municipal de Bellas Artes Juan B. Castagnino</p>
          <p style="margin-top:8px; color:var(--cyan);">Av. Pellegrini 2202<br>Rosario, Argentina</p>
          <p style="margin-top:8px;"><a href="https://castagninomacro.org" style="color:var(--cyan); text-decoration:none;">castagninomacro.org</a></p>
        </address>
      </div>
      <div class="info-block">
        <span class="label">Colaboradores especiales</span>
        <p>Fundación Kosice</p>
        <p>Planetario del Complejo Astronómico Municipal</p>
      </div>
    </div>
  </div>

  <!-- CRÉDITOS -->
  <section>
    <div class="section-header">
      <span class="label">Equipo</span>
      <h2>Créditos</h2>
    </div>
    <div class="credits-grid">
      <div class="credit-item">
        <span class="label">Organización</span>
        <p>Museo Municipal de Bellas Artes Juan B. Castagnino</p>
      </div>
      <div class="credit-item">
        <span class="label">Organiza también</span>
        <p>Secretaría de Cultura y Educación, Municipalidad de Rosario</p>
      </div>
      <div class="credit-item">
        <span class="label">Curaduría e Investigación</span>
        <p>Jazmín Adler</p>
      </div>
      <div class="credit-item">
        <span class="label">Textos y Museografía</span>
        <p>Equipo Castagnino+macro</p>
      </div>
      <div class="credit-item">
        <span class="label">Dirección Ejecutiva</span>
        <p>Melania Toia</p>
      </div>
      <div class="credit-item">
        <span class="label">Dirección Artística</span>
        <p>Roberto Echen</p>
      </div>
      <div class="credit-item">
        <span class="label">Coordinación General</span>
        <p>Daniela Quintero</p>
      </div>
    </div>
  </section>

  <!-- LOGOS SPONSORS -->
  <div class="logos-bar">
    <span class="label" style="color:var(--muted);">Con el apoyo de</span>
    <svg class="sponsors-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 511.859 36.011"><defs><style>.cls-1,.cls-2{fill:#fff;}.cls-2{fill-rule:evenodd;}</style></defs><g id="Capa_2" data-name="Capa 2"><g id="Portada_1_y_8" data-name="Portada 1 y 8"><path class="cls-1" d="M78.411,32.918a2.885,2.885,0,0,0-1-.244l-.627-.054a1.082,1.082,0,0,1-.711-.28.759.759,0,0,1-.24-.551.993.993,0,0,1,.547-.892,1.7,1.7,0,0,1,1.4.007.992.992,0,0,1,.4.395,1.088,1.088,0,0,1,.127.512h.758a1.7,1.7,0,0,0-.251-.935,1.66,1.66,0,0,0-.7-.609,2.581,2.581,0,0,0-2.081,0,1.729,1.729,0,0,0-.7.608,1.625,1.625,0,0,0-.25.907,1.354,1.354,0,0,0,.449,1.062,1.98,1.98,0,0,0,1.2.465l.627.054a1.712,1.712,0,0,1,.881.283.7.7,0,0,1,.3.578.987.987,0,0,1-.154.532,1.084,1.084,0,0,1-.48.4,2,2,0,0,1-.836.15,1.877,1.877,0,0,1-.871-.17,1.061,1.061,0,0,1-.456-.427A1.092,1.092,0,0,1,75.6,34.2h-.757a1.686,1.686,0,0,0,.263.93,1.762,1.762,0,0,0,.758.642,2.806,2.806,0,0,0,1.2.234,2.85,2.85,0,0,0,1.168-.225,1.816,1.816,0,0,0,.78-.628,1.573,1.573,0,0,0,.278-.922,1.349,1.349,0,0,0-.227-.787,1.62,1.62,0,0,0-.651-.527Zm4.222.415h2.523v-.682H82.633V30.89h2.686v-.682H81.875v5.661H85.4v-.682H82.633V33.333Zm7.653.427H92.12v.951a2.1,2.1,0,0,1-.476.347,2.434,2.434,0,0,1-1.158.267,2.382,2.382,0,0,1-.854-.147,1.87,1.87,0,0,1-.677-.438,1.978,1.978,0,0,1-.444-.729,2.983,2.983,0,0,1-.159-1.019,2.733,2.733,0,0,1,.146-.923,2.1,2.1,0,0,1,.414-.705,1.816,1.816,0,0,1,.638-.454,2.133,2.133,0,0,1,1.621,0,1.611,1.611,0,0,1,.63.472,1.49,1.49,0,0,1,.31.786h.774a2.239,2.239,0,0,0-.387-1.106,2.29,2.29,0,0,0-.881-.745,2.855,2.855,0,0,0-1.254-.267,2.78,2.78,0,0,0-1.168.237,2.568,2.568,0,0,0-.877.644,2.9,2.9,0,0,0-.55.916,2.969,2.969,0,0,0-.19,1.05v.17a3.223,3.223,0,0,0,.209,1.174,2.8,2.8,0,0,0,.591.935,2.609,2.609,0,0,0,.918.612,3.106,3.106,0,0,0,1.19.217,3.219,3.219,0,0,0,1.371-.278,2.6,2.6,0,0,0,.974-.775V33.758h.48v-.635H90.286v.637Zm9.238-.047a1.833,1.833,0,0,1-.183.842,1.288,1.288,0,0,1-.533.558,1.977,1.977,0,0,1-1.731,0,1.305,1.305,0,0,1-.537-.562,1.833,1.833,0,0,1-.181-.833V30.21H95.6v3.412a2.791,2.791,0,0,0,.267,1.253,1.929,1.929,0,0,0,.789.838,2.939,2.939,0,0,0,2.579,0,1.906,1.906,0,0,0,.781-.838,2.818,2.818,0,0,0,.264-1.253V30.21h-.758v3.5Zm6.854-.461a1.348,1.348,0,0,0,.627-.542,1.614,1.614,0,0,0,.21-.842v-.124a1.615,1.615,0,0,0-.21-.841,1.321,1.321,0,0,0-.627-.539,2.566,2.566,0,0,0-1.044-.187h-2.2v5.692h.758V33.442h1.447c.057,0,.109,0,.165-.007l1.073,2.434h.843L106.251,33.3c.043-.017.088-.029.127-.049Zm-.9-.485h-1.594V30.845h1.594a.93.93,0,0,1,.72.26,1.16,1.16,0,0,1,.007,1.4.934.934,0,0,1-.727.26Zm9.122-1.778a2.693,2.693,0,0,0-.91-.679,3.38,3.38,0,0,0-2.576,0,2.7,2.7,0,0,0-.909.679,2.837,2.837,0,0,0-.541.935,3.069,3.069,0,0,0-.178,1.016v.17a2.956,2.956,0,0,0,.174.969,3.11,3.11,0,0,0,.53.946,2.631,2.631,0,0,0,.905.713,3.29,3.29,0,0,0,2.615,0,2.639,2.639,0,0,0,.9-.713,3.131,3.131,0,0,0,.53-.946,2.93,2.93,0,0,0,.174-.969v-.17a3.093,3.093,0,0,0-.177-1.016,2.857,2.857,0,0,0-.541-.935Zm-.2,2.9a2.289,2.289,0,0,1-.426.729,2.009,2.009,0,0,1-.677.508,2.23,2.23,0,0,1-1.788,0,2.005,2.005,0,0,1-.676-.508,2.3,2.3,0,0,1-.427-.729,2.5,2.5,0,0,1-.147-.856,2.593,2.593,0,0,1,.147-.883,2.209,2.209,0,0,1,.427-.725,1.95,1.95,0,0,1,.676-.492,2.334,2.334,0,0,1,1.788,0,1.98,1.98,0,0,1,.677.492,2.187,2.187,0,0,1,.426.725,2.585,2.585,0,0,1,.147.883A2.417,2.417,0,0,1,114.4,33.889Zm7.315-.441a1.6,1.6,0,0,0-.65-.528,2.847,2.847,0,0,0-1-.244l-.626-.054a1.078,1.078,0,0,1-.711-.28.757.757,0,0,1-.24-.551.99.99,0,0,1,.546-.892,1.7,1.7,0,0,1,1.4.007.986.986,0,0,1,.4.395,1.074,1.074,0,0,1,.128.512h.757a1.7,1.7,0,0,0-.251-.936,1.665,1.665,0,0,0-.7-.608,2.581,2.581,0,0,0-2.081,0,1.712,1.712,0,0,0-.7.608,1.614,1.614,0,0,0-.251.906,1.355,1.355,0,0,0,.45,1.063,1.977,1.977,0,0,0,1.2.465l.627.054a1.719,1.719,0,0,1,.882.283.7.7,0,0,1,.3.578.978.978,0,0,1-.154.532,1.076,1.076,0,0,1-.48.394,1.987,1.987,0,0,1-.836.151,1.875,1.875,0,0,1-.87-.17,1.058,1.058,0,0,1-.457-.427,1.094,1.094,0,0,1-.136-.512H117.5a1.689,1.689,0,0,0,.263.93,1.762,1.762,0,0,0,.758.642,2.809,2.809,0,0,0,1.2.234,2.85,2.85,0,0,0,1.168-.225,1.819,1.819,0,0,0,.781-.628,1.581,1.581,0,0,0,.277-.923,1.343,1.343,0,0,0-.227-.786Z"/><path class="cls-1" d="M161.044,6.727h-2.686a.2.2,0,0,0-.167.094l-1.334,2.135a.108.108,0,0,1-.19-.01,3.78,3.78,0,0,0-3.829-2.361c-2.993,0-4.745,2.388-4.745,5.832V14.05c0,3.649,1.75,5.931,4.745,5.931a3.947,3.947,0,0,0,3.824-2.379.109.109,0,0,1,.188,0l1.341,2.152a.2.2,0,0,0,.169.094h2.686a.109.109,0,0,0,.109-.11V6.835a.109.109,0,0,0-.109-.11Zm-6.421,9.7a1.94,1.94,0,0,1-2.138-1.683,7.565,7.565,0,0,1-.09-1.505,8.774,8.774,0,0,1,.115-1.43,1.937,1.937,0,0,1,2.112-1.648,1.9,1.9,0,0,1,2.12,1.881v2.459a1.874,1.874,0,0,1-2.12,1.926ZM146.641,1.346h-4.186a.109.109,0,0,0-.109.11v7.2a.11.11,0,0,1-.206.051,3.748,3.748,0,0,0-3.707-2.118c-2.993,0-4.745,2.387-4.745,5.831v1.634c0,3.649,1.75,5.93,4.745,5.93a3.944,3.944,0,0,0,3.823-2.378.109.109,0,0,1,.188-.006l1.342,2.152a.2.2,0,0,0,.168.094h2.687a.109.109,0,0,0,.109-.11V1.456A.109.109,0,0,0,146.641,1.346Zm-4.3,13.293a2.172,2.172,0,0,1-4.255.11,7.565,7.565,0,0,1-.09-1.505,8.894,8.894,0,0,1,.114-1.43,1.938,1.938,0,0,1,2.112-1.648,1.893,1.893,0,0,1,2.117,1.871v2.6ZM68.505,11.905c-1.649-.28-2.179-.522-2.163-1.258v-.032c.014-.634.533-1.291,1.694-1.269,1.073.027,1.59.6,1.6,1.264l0,.459a.109.109,0,0,0,.11.108h3.89a.109.109,0,0,0,.109-.106l.006-.189c.059-2.672-2.318-4.483-5.64-4.557-3.274-.073-5.871,1.628-5.929,4.186l0,.178c-.06,2.669,2.367,3.456,5.423,4.029v0c1.458.281,2.36.328,2.341,1.186v.068c-.022.932-.908,1.226-2.067,1.2-1.023-.023-1.884-.485-1.965-1.413l-.021-.272a.109.109,0,0,0-.11-.1H61.86a.11.11,0,0,0-.109.11c0,2.924,2.468,4.56,5.968,4.639,3.238.072,6.329-.938,6.4-4.081l.008-.347c.059-2.669-2.5-3.279-5.619-3.807ZM81.764,6.489c-3.566,0-6.544,2.033-6.544,5.858V14.14c0,3.825,2.9,5.841,6.544,5.841,3.326,0,5.916-1.443,6.423-4.127a.113.113,0,0,0-.109-.131H83.743a.108.108,0,0,0-.093.056,2.07,2.07,0,0,1-1.9.926,1.912,1.912,0,0,1-2.117-1.685c0-.015,0-.21,0-.5a.109.109,0,0,1,.109-.11h8.432a.108.108,0,0,0,.109-.109V12.347c0-3.825-2.95-5.858-6.516-5.858Zm2.02,5.745H79.733a.109.109,0,0,1-.109-.11v-.412a2.159,2.159,0,0,1,4.238-.234s.016.264.03.641a.11.11,0,0,1-.109.113Zm33.561-5.507h-4.186a.109.109,0,0,0-.109.11v7.475a2.156,2.156,0,0,1-2.135,2.165,2.1,2.1,0,0,1-2.119-2.344v-7.3a.109.109,0,0,0-.109-.11H104.5a.109.109,0,0,0-.109.11v8.642a4.37,4.37,0,0,0,4.548,4.5A4.8,4.8,0,0,0,113.2,17.8a.108.108,0,0,1,.181.005l1.209,1.94a.2.2,0,0,0,.168.094h2.581a.109.109,0,0,0,.109-.11V6.835a.109.109,0,0,0-.109-.11ZM127.8,6.585a4.8,4.8,0,0,0-4.264,2.179.108.108,0,0,1-.181,0L122.12,6.779a.111.111,0,0,0-.093-.052H119.4a.11.11,0,0,0-.11.11v12.9a.11.11,0,0,0,.11.11h4.185a.109.109,0,0,0,.109-.11V12.309a2.19,2.19,0,0,1,2.135-2.216,2.1,2.1,0,0,1,2.119,2.344v7.3a.109.109,0,0,0,.109.11h4.186a.109.109,0,0,0,.109-.11V11.091A4.371,4.371,0,0,0,127.8,6.585Zm-25.232.142H99.881a.2.2,0,0,0-.167.094L98.38,8.958a.107.107,0,0,1-.188-.011,3.78,3.78,0,0,0-3.831-2.362c-2.993,0-4.745,2.388-4.745,5.832V14.05c0,3.649,1.75,5.931,4.745,5.931a3.913,3.913,0,0,0,3.73-2.177.109.109,0,0,1,.2.055v.829c0,1.5-.312,2.635-2.32,2.635H91.891a.109.109,0,0,0-.106.137l.8,3.1a.11.11,0,0,0,.106.083h4.157c3.358,0,5.833-.779,5.833-4.8V6.835a.109.109,0,0,0-.109-.11Zm-4.3,7.9a2.171,2.171,0,0,1-4.255.122,7.565,7.565,0,0,1-.09-1.505,8.774,8.774,0,0,1,.115-1.43,1.937,1.937,0,0,1,2.111-1.648,1.892,1.892,0,0,1,2.117,1.881v2.581Zm-56.34,1.9H40.839a.626.626,0,0,1-.625-.627V1.456a.109.109,0,0,0-.109-.11H35.919a.109.109,0,0,0-.109.11V17.511a2.266,2.266,0,0,0,2.28,2.33h3.831a.109.109,0,0,0,.109-.11v-3.1a.108.108,0,0,0-.109-.109ZM26.652,21.268H5.885a.228.228,0,0,1-.227-.228V.228A.225.225,0,0,0,5.432,0H.227A.228.228,0,0,0,0,.228V17.412a6.149,6.149,0,0,0,1.678,4.224L3.03,23.068q.407.427.833.834l1.43,1.356A6.125,6.125,0,0,0,9.507,26.94H26.654a.229.229,0,0,0,.228-.229V21.5a.228.228,0,0,0-.228-.228Zm0-7.088H13.44a.709.709,0,0,1,0-1.418h7.072A6.37,6.37,0,0,0,26.4,8.824a2.628,2.628,0,0,0-.523-2.806L23.853,3.875c-.27-.287-.55-.567-.836-.838L21.589,1.684A6.118,6.118,0,0,0,17.373,0H7.3a.228.228,0,0,0-.227.228V5.444a.228.228,0,0,0,.227.228h13.2a.709.709,0,1,1,.009,1.418H13.442a6.373,6.373,0,0,0-6.367,6.381v6.152a.228.228,0,0,0,.227.228H26.654a.228.228,0,0,0,.228-.228V14.408a.228.228,0,0,0-.228-.228ZM55.6,6.729H52.916a.2.2,0,0,0-.167.093L51.415,8.958a.108.108,0,0,1-.19-.011A3.779,3.779,0,0,0,47.4,6.587c-2.993,0-4.744,2.387-4.744,5.832v1.633c0,3.649,1.75,5.93,4.744,5.93A3.947,3.947,0,0,0,51.22,17.6a.109.109,0,0,1,.188,0l1.341,2.152a.2.2,0,0,0,.169.093H55.6a.109.109,0,0,0,.11-.109V6.835a.11.11,0,0,0-.11-.11Zm-6.421,9.705a1.941,1.941,0,0,1-2.139-1.684,7.659,7.659,0,0,1-.089-1.5,8.781,8.781,0,0,1,.114-1.43,1.937,1.937,0,0,1,2.112-1.648A1.9,1.9,0,0,1,51.3,12.049v2.459a1.874,1.874,0,0,1-2.121,1.926Z"/><path class="cls-1" d="M243.97,15.08c.295-1.225.554-2.355.857-3.472.034-.125.32-.25.493-.257a19.5,19.5,0,0,1,2.229,0c.6.047.767-.248.844-.755a17.513,17.513,0,0,1,.4-2.117,6.115,6.115,0,0,1,6.089-4.655c1.245.009,2.489.16,3.732.265.527.045.715.285.522.85-.313.918-.543,1.864-.814,2.82-.516-.085-.987-.173-1.46-.24a2.059,2.059,0,0,0-2.3,1.1,12.339,12.339,0,0,0-.763,2.206c-.153.532.253.514.607.514q3.506,0,7.009,0c.83,0,.833,0,.665.808-.541,2.587-1.089,5.173-1.62,7.762a8.512,8.512,0,0,0-.172,1.385,2.012,2.012,0,0,0,2.395,1.992,4.488,4.488,0,0,0,4.057-3.86c.541-2.437,1.042-4.882,1.529-7.33.107-.538.277-.793.892-.773,1.524.048,3.052.016,4.695.016-.159.8-.3,1.534-.452,2.267-.927,4.452-1.863,8.9-2.773,13.356-.08.389-.241.476-.59.472-1.253-.013-2.506-.015-3.759,0-.462.005-.59-.127-.479-.606a7.027,7.027,0,0,0,.153-2.06c-.156.149-.324.286-.466.447a7.3,7.3,0,0,1-5.676,2.57c-3.182,0-4.83-2-5.039-4.919a26.008,26.008,0,0,1,.816-6.345c.259-1.477.56-1.459-1.161-1.442-1.8.018-1.489-.208-1.81,1.354-.717,3.48-1.437,6.959-2.129,10.444-.083.419-.228.578-.652.573-1.444-.017-2.889-.013-4.333,0-.443,0-.589-.1-.48-.6.806-3.7,1.566-7.408,2.377-11.106.124-.567-.057-.675-.545-.668C245.949,15.09,245.037,15.08,243.97,15.08Z"/><path class="cls-1" d="M304.147,24.875c-.145.166-.292.33-.435.5a6.436,6.436,0,0,1-7,2.142,5.743,5.743,0,0,1-4.281-5.316,11.265,11.265,0,0,1,2.43-8.769,6.752,6.752,0,0,1,4.974-2.486,6.6,6.6,0,0,1,5,1.357,17.9,17.9,0,0,1,1.471,1.666c.17-.7.329-1.318.465-1.939.354-1.611.684-3.227,1.059-4.833.05-.214.3-.538.468-.542,1.628-.041,3.258-.025,4.981-.025-.317,1.442-.613,2.8-.914,4.155q-1.591,7.153-3.177,14.308a11.472,11.472,0,0,0-.211,1.7c-.029.434-.163.657-.647.649-1.273-.023-2.548-.015-3.822,0-.409,0-.577-.09-.466-.559.149-.627.2-1.276.3-1.916Zm-3.44-1.242a7.462,7.462,0,0,0,1.053-.175,5.266,5.266,0,0,0,2.937-6.844,2.638,2.638,0,0,0-2.372-1.551,3.331,3.331,0,0,0-2.7,1.038,5.609,5.609,0,0,0-1.368,5.7A2.3,2.3,0,0,0,300.707,23.633Z"/><path class="cls-1" d="M280.489,13.843c.448-.4.88-.829,1.346-1.211a6.913,6.913,0,0,1,6.613-1.417,4.851,4.851,0,0,1,3.2,4.413,25.561,25.561,0,0,1-.812,6.531c-.305,1.577-.667,3.144-.967,4.722-.08.419-.251.574-.669.569q-2.2-.021-4.395,0c-.476,0-.624-.106-.51-.632.534-2.48,1.03-4.968,1.514-7.458A11.224,11.224,0,0,0,286,17.53a1.911,1.911,0,0,0-1.985-2.086,3.945,3.945,0,0,0-3.975,2.707,27.922,27.922,0,0,0-1.016,3.916q-.548,2.412-1,4.843c-.084.448-.3.542-.69.539-1.422-.011-2.845-.015-4.268,0-.5.006-.6-.14-.493-.645.945-4.511,1.86-9.029,2.777-13.546.092-.455.153-.918.207-1.379a.529.529,0,0,1,.619-.548c1.316.017,2.633.021,3.949,0,.527-.009.6.206.5.666-.123.587-.177,1.189-.261,1.784Z"/><path class="cls-1" d="M314.641,15.413c.135-.961.262-2.052.461-3.129a.9.9,0,0,1,.539-.591,24.412,24.412,0,0,1,3.409-.686,13.665,13.665,0,0,1,4.86.212,5.055,5.055,0,0,1,3.956,6.158c-.455,2.753-1.069,5.479-1.6,8.219-.089.456-.1.93-.222,1.375-.048.179-.292.428-.454.433-1.188.036-2.379.012-3.568.024-.453,0-.458-.264-.425-.592.052-.515.1-1.031.141-1.546l-.261-.164a2.149,2.149,0,0,1-.227.443,5.881,5.881,0,0,1-4.658,2.1,10.431,10.431,0,0,1-2.946-.317c-2.219-.658-3.027-2.541-2.843-4.679.235-2.725,2.091-4.058,4.45-4.813a12.663,12.663,0,0,1,5.394-.562,13.615,13.615,0,0,0,1.592.032c.571,0,.8-.259.713-.826a2.146,2.146,0,0,0-1.357-1.715,4.833,4.833,0,0,0-2.87-.308C317.359,14.735,316.017,15.094,314.641,15.413Zm3.694,8.784c.124-.021.4-.049.663-.115a4.3,4.3,0,0,0,3.179-3.152c.191-.624.063-.748-.58-.773-.486-.019-.971-.075-1.457-.083a5.394,5.394,0,0,0-3.206.818,1.811,1.811,0,0,0-.956,1.417C315.921,23.437,316.8,24.19,318.335,24.2Z"/><path class="cls-1" d="M335.972,11.218l-.55,3.208.127.067c.13-.192.265-.381.388-.577a5.572,5.572,0,0,1,4.1-3.006,9.56,9.56,0,0,1,2.428.277.487.487,0,0,1,.253.405c-.346,1.457-.724,2.906-1.116,4.446a4.182,4.182,0,0,0-3.463-.521,4.3,4.3,0,0,0-3.147,3.5c-.621,2.524-1.135,5.075-1.656,7.622-.116.566-.289.824-.93.8-1.523-.052-3.048-.017-4.676-.017.22-1.076.422-2.082.631-3.086q1.173-5.649,2.347-11.3c.085-.413.076-.849.191-1.251.063-.215.293-.541.455-.545C332.861,11.2,334.365,11.218,335.972,11.218Z"/><g id="surface1"><path class="cls-2" d="M477.456,13.47l1.036,1.659c1.2-.634,2.755-2,3.84-.414l-.109,1.346c-2.845,0-5.7,1.895-5.7,4.87,0,1.334.78,2.591,1.969,2.591,1.787,0,2.15-1.084,3.523-1.451.3,1.282,1.665,1.243,2.665,1.242l.151-2.087-.351-.4.541-6.215c0-2.229-2.255-2.59-3.938-2.59A6.531,6.531,0,0,0,477.456,13.47Zm1.761,6.218V20.1c0,.5.285,1.14.726,1.14h.207c1.5,0,1.865-2,1.865-3.523-1.092,0-2.8,1.122-2.8,1.969"/><path class="cls-2" d="M434.394,10.665l.058.318,3.579,0-1.3,12.232,3.155.005,1.3-11.818v-.415h3.731v-.414l.312-2.487-10.523-.007-.312,2.59"/><path class="cls-2" d="M466.679,21.139c0,1.263.465,2.383,1.969,2.383,1.852,0,2.237-1.416,3.519-2.28l-.2,1.969,2.728,0L475.9,12.227h-2.8l.014.416-.74,6.941a2.865,2.865,0,0,1-2.072,1.243.717.717,0,0,1-.774-.626l.878-7.974-2.642-.013s-1.089,8.2-1.089,8.925"/><path class="cls-2" d="M494.347,19.688c0,4.292,4.092,4.371,7.15,3.108V20.517c-2.709,1.27-4.771.986-4.456-2.176h4.973c0-3.267.793-6.321-3.523-6.321C494.827,12.02,494.347,17.034,494.347,19.688Zm2.9-3h2.591c0-.9.125-2.788-.957-2.788-1.585,0-1.6,1.263-1.634,2.788"/><path class="cls-2" d="M442.949,19.481c0,4.708,3.7,4.421,7.047,3.315V20.621c-.969.021-4.457,1.632-4.457-.622V18.341h4.97c.188-3.213.751-6.321-3.415-6.321C443.46,12.02,442.949,16.81,442.949,19.481Zm2.9-2.8,2.474,0c.064-.909.536-2.8-.92-2.8-1.476,0-1.554,1.737-1.554,2.8"/><path class="cls-2" d="M468.545,10.051h34.3c-.209-2.5-8.009-2.176-10.156-2.176-3.577,0-22.963,1.355-24.143,2.176"/><path class="cls-2" d="M487.909,23.213l2.646-.024,4-10.962-2.623.024-2.247,6.3-.623-6.321-2.823,0,1.671,10.982"/><path class="cls-2" d="M459.011,15.129c0,2.74,3.834,3.886,3.834,5.077,0,2.109-2.643.618-3.257-.241l-1.51,2a4.8,4.8,0,0,0,3.109,1.554c2.168,0,4.352-1.4,4.352-3.834,0-2.678-4.041-3.337-4.041-4.767,0-1.686,2.4-.4,3.008,0l1.344-1.971a7.128,7.128,0,0,0-3.42-.932c-1.577,0-3.419,1.607-3.419,3.109"/><path class="cls-2" d="M455.073,14.507l.207-2.28h-2.5l-1.23,10.985,2.756,0,.663-6.42a5.026,5.026,0,0,1,3.167-1.042l.356-3.725c-2.061,0-2.535,1.839-3.419,2.487"/><path class="cls-2" d="M440.1,1.346h57.2A14.5,14.5,0,0,1,511.859,15.7,14.5,14.5,0,0,1,497.3,30.05H440.1A14.5,14.5,0,0,1,425.54,15.7,14.5,14.5,0,0,1,440.1,1.346Zm0,1.469h57.2A13.026,13.026,0,0,1,510.39,15.7,13.026,13.026,0,0,1,497.3,28.581H440.1A13.026,13.026,0,0,1,427.009,15.7,13.026,13.026,0,0,1,440.1,2.815"/></g></g></g></svg>
  </div>

  <!-- FOOTER -->
  <footer>
    <div class="f-left">
      <svg class="cm-logo-svg" style="margin-bottom:14px; height:14px; width:auto;" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 161.169 12.636"><defs><style>.cls-1{fill:#fff;}</style></defs><g id="Capa_2" data-name="Capa 2"><g id="Portada_1_y_8" data-name="Portada 1 y 8"><g id="Layer_2" data-name="Layer 2"><g id="Capa_1-2" data-name="Capa 1"><path class="cls-1" d="M6.4,12.559H6.054a6.2,6.2,0,0,1,0-12.387H6.4v.969H6.065a5.218,5.218,0,0,0,0,10.431H6.4Z"/><path class="cls-1" d="M42.237,12.557h-.351A6.194,6.194,0,0,1,41.9.172h.352v.969L41.9,1.15a5.218,5.218,0,0,0-.368,10.411v-4.6h-.744V5.991h1.724v6.566Z"/><path class="cls-1" d="M14.5,12.55h-1l-.948-3.933H9.641L8.693,12.55H7.681L10.669.172h.852ZM9.876,7.641h2.439L11.1,2.577Z"/><path class="cls-1" d="M35.145,12.55h-1L33.2,8.617h-2.91l-.958,3.933h-1L31.3.172h.854ZM30.511,7.641H32.95L31.731,2.577Z"/><polygon class="cls-1" points="50.788 12.636 49.809 12.636 49.809 8.361 45.293 2.162 45.293 12.636 44.313 12.636 44.313 0.265 45.123 0.265 49.809 6.699 49.809 0.265 50.788 0.265 50.788 12.636"/><polygon class="cls-1" points="62.487 12.55 61.507 12.55 61.507 8.274 56.991 2.076 56.991 12.55 56.011 12.55 56.011 0.179 56.821 0.179 61.507 6.613 61.507 0.179 62.487 0.179 62.487 12.55"/><rect class="cls-1" x="52.976" y="0.179" width="0.975" height="12.371"/><path class="cls-1" d="M67.963,12.541A3.347,3.347,0,0,1,64.57,9.326v-5.9a3.4,3.4,0,0,1,6.787-.019V9.317a3.4,3.4,0,0,1-3.394,3.224m0-11.377a2.432,2.432,0,0,0-2.425,2.409V9.25a2.423,2.423,0,0,0,4.843-.082V3.454a2.422,2.422,0,0,0-2.418-2.29"/><path class="cls-1" d="M18.466,12.636A3.15,3.15,0,0,1,15.32,9.482V9.145h.973v.337a2.169,2.169,0,1,0,4.336.142c0-.047,0-.094,0-.142a2.157,2.157,0,0,0-.077-.57l-.1-.279a2,2,0,0,0-.165-.314,3.879,3.879,0,0,0-.654-.652l-.068-.047c-.27-.214-.593-.465-.968-.723-.621-.445-1.233-.848-1.559-1.064l-.149-.1a6.378,6.378,0,0,1-.559-.465,3.907,3.907,0,0,1-.272-.37,2.937,2.937,0,0,1-.435-1,3,3,0,0,1-.077-.668,2.968,2.968,0,0,1,5.935,0v.564h-.971V3.228a1.988,1.988,0,0,0-3.975,0,1.871,1.871,0,0,0,.016.249s.019.135.035.2v.025a2.337,2.337,0,0,0,.3.668,2.049,2.049,0,0,0,.331.371l.023.021a2.34,2.34,0,0,0,.286.2l.026.014L19.47,6.31c.265.193.5.372.7.538l.037.028a3.18,3.18,0,0,1,.868.87,1.789,1.789,0,0,1,.34.649,3.148,3.148,0,0,1-2.947,4.241"/><polygon class="cls-1" points="25.663 12.55 24.683 12.55 24.683 1.159 21.941 1.159 21.941 0.179 28.47 0.179 28.47 1.159 25.663 1.159 25.663 12.55"/></g></g><path class="cls-1" d="M127.245,11.274a5.262,5.262,0,0,1-1.552-2.206,7.925,7.925,0,0,1-.518-2.886,9.194,9.194,0,0,1,.218-1.988,7.444,7.444,0,0,1,.654-1.743,5.824,5.824,0,0,1,1.117-1.443A5.638,5.638,0,0,1,128.717,0h-8.742a4.558,4.558,0,0,1,.789.6,4.027,4.027,0,0,1,.545.79,4.143,4.143,0,0,1,.326.925h.026c.026.218.055.518.081.872.027.3.027.708.027,1.2V7.161c0,.98.026,1.771.054,2.37a7.463,7.463,0,0,0,.109,1.2v.026a2.574,2.574,0,0,0,.164.626c.11.218.219.435.326.625l.409.626h6.754a1.391,1.391,0,0,0-.3-.11A6.472,6.472,0,0,1,127.245,11.274Z"/><path class="cls-1" d="M117.823,2.7H117.8a2.4,2.4,0,0,0-.873-.435,7.189,7.189,0,0,0-1.416-.136h-.3a5.789,5.789,0,0,0-1.034.109,1.934,1.934,0,0,0-.79.3,1.871,1.871,0,0,0-.518.518,4.6,4.6,0,0,0-.409,1.034h-3.675l.164-.68a5.713,5.713,0,0,1,.463-1.307,4.918,4.918,0,0,1,.708-1.089,3.963,3.963,0,0,1,1.035-.818L111.4.028h-8.169A4.555,4.555,0,0,0,99.36,2.18,3.007,3.007,0,0,0,98.107.6,4.193,4.193,0,0,0,95.82.028,4.321,4.321,0,0,0,93.587.6a4.454,4.454,0,0,0-1.579,1.443V0H90.13V12.636h2.123v-6.4a7.805,7.805,0,0,1,.326-2.56A2.532,2.532,0,0,1,93.7,2.314a2.955,2.955,0,0,1,1.662-.464,1.966,1.966,0,0,1,1.688.68,3.458,3.458,0,0,1,.518,2.1v8.007h2.123V5.473a3.782,3.782,0,0,1,.873-2.751,2.935,2.935,0,0,1,2.206-.872,2.488,2.488,0,0,1,1.279.326,1.707,1.707,0,0,1,.735.9,3.416,3.416,0,0,1,.19,1.117v8.442H110.8a4.042,4.042,0,0,1-.818-.518,3.857,3.857,0,0,1-1.089-1.334,3.566,3.566,0,0,1-.381-1.688,4.333,4.333,0,0,1,.136-1.034,3.334,3.334,0,0,1,.435-.953,4.169,4.169,0,0,1,.626-.79,4.337,4.337,0,0,1,.789-.6,4.787,4.787,0,0,1,.9-.463,7.935,7.935,0,0,1,.98-.3c.273-.055.572-.136.953-.19.326-.027.763-.081,1.225-.136.245-.026.435-.055.653-.081.681-.081,1.28-.164,1.8-.245.49-.081.872-.164,1.224-.245V3.977A1.6,1.6,0,0,0,117.823,2.7Z"/><path class="cls-1" d="M115.208,7.544l-.19.026c-.464.055-.872.136-1.2.19a5,5,0,0,0-.709.191,1.644,1.644,0,0,0-.38.218.783.783,0,0,0-.274.245c-.054.109-.109.19-.163.3a1.124,1.124,0,0,0-.027.326.893.893,0,0,0,.109.463.847.847,0,0,0,.355.409,1.445,1.445,0,0,0,.653.3,3.8,3.8,0,0,0,1.035.136,6.986,6.986,0,0,0,.789-.054c.136-.027.245-.055.381-.082a3.745,3.745,0,0,0,.979-.326,4.269,4.269,0,0,0,.79-.518,3.073,3.073,0,0,0,.518-.653,3.373,3.373,0,0,0,.218-.681c.027-.3.055-.625.082-1.034-.274.081-.545.136-.873.219C116.706,7.325,116,7.434,115.208,7.544Z"/><path class="cls-1" d="M144.755.435a5.072,5.072,0,0,0-1.362,1.717V0h-7.242a4.452,4.452,0,0,1,.49.3,4.843,4.843,0,0,1,1.417,1.362,5.056,5.056,0,0,1,.789,1.823l.136.6-3.759.026a2.707,2.707,0,0,0-.381-.9,2.406,2.406,0,0,0-.572-.6,2.9,2.9,0,0,0-.79-.354,3.722,3.722,0,0,0-.979-.136,4.1,4.1,0,0,0-1.444.245,3.048,3.048,0,0,0-1.143.68,3.244,3.244,0,0,0-.626.926c-.026.081-.054.163-.081.245a6.2,6.2,0,0,0-.245,1.851,6.345,6.345,0,0,0,.245,1.907c.027.081.055.19.081.273a3.064,3.064,0,0,0,.6.9,3.058,3.058,0,0,0,1.089.68,3.807,3.807,0,0,0,1.389.245,3.938,3.938,0,0,0,1.172-.164,2.831,2.831,0,0,0,.9-.463,1.985,1.985,0,0,0,.626-.709,5.524,5.524,0,0,0,.381-1.334h3.785l-.136.681a5.606,5.606,0,0,1-.79,2.042,5.515,5.515,0,0,1-1.5,1.579,5.819,5.819,0,0,1-1.717.925h8.524V6.155a7.664,7.664,0,0,1,.354-2.423,2.183,2.183,0,0,1,.789-1.143,2.079,2.079,0,0,1,1.253-.409,4.645,4.645,0,0,1,1.553.19V.273A3.517,3.517,0,0,0,146.117,0,2.465,2.465,0,0,0,144.755.435Z"/><path class="cls-1" d="M159.236,1.334A5.994,5.994,0,0,0,155.316,0c-.152,0-.3.009-.446.018-.148-.009-.294-.018-.446-.018A6,6,0,0,0,150.5,1.334a6.193,6.193,0,0,0-1.933,4.983,6.4,6.4,0,0,0,1.634,4.712,5.723,5.723,0,0,0,4.22,1.607c.15,0,.3,0,.446-.016.148.009.3.016.446.016a5.723,5.723,0,0,0,4.22-1.607,6.4,6.4,0,0,0,1.633-4.712A6.186,6.186,0,0,0,159.236,1.334Z"/><path class="cls-1" d="M79.983,9.12V6.909h-2.2V5.727h2.2V3.516H81.2V5.727h2.189V6.909H81.2V9.12Z"/></g></g></svg>
      <p>Av. Pellegrini 2202, Rosario</p>
      <p><a href="https://castagninomacro.org">castagninomacro.org</a></p>
    </div>
    <div class="f-right">
      <p>Gyula Kosice: En tiempo real</p>
      <p>30 ABR — 17 AGO 2026</p>
      <p style="margin-top:8px; color:var(--muted); font-size:10px;">Museo Municipal de Bellas Artes Juan B. Castagnino<br>Secretaría de Cultura y Educación · Municipalidad de Rosario</p>
    </div>
  </footer>

  <script>
    // Particles
    const container = document.getElementById('particles');
    for (let i = 0; i < 18; i++) {
      const p = document.createElement('div');
      p.className = 'particle';
      const size = Math.random() * 4 + 2;
      p.style.cssText = `
        width:${size}px; height:${size}px;
        left:${Math.random() * 100}%;
        top:${Math.random() * 100}%;
        animation-duration:${4 + Math.random() * 6}s;
        animation-delay:${Math.random() * 4}s;
      `;
      container.appendChild(p);
    }
  </script>
</body>
</html>
