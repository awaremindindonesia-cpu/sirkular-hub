<!DOCTYPE html>
<html lang=\"id\">
<head>
<meta charset=\"UTF-8\" />
<meta name=\"viewport\" content=\"width=device-width, initial-scale=1.0\" />
<title>SEMENDO · Sistem Ekosistem Mandiri Ekonomi Daerah</title>
<meta name=\"description\" content=\"Platform agritech futuristik untuk Sriwijaya Economic Forum 2026 — Bank Indonesia & UIN Raden Fatah.\" />

<!-- Fonts: Syne (display), Space Grotesk (UI), JetBrains Mono (numbers) -->
<link rel=\"preconnect\" href=\"https://fonts.googleapis.com\" />
<link rel=\"preconnect\" href=\"https://fonts.gstatic.com\" crossorigin />
<link href=\"https://fonts.googleapis.com/css2?family=Syne:wght@500;600;700;800&family=Space+Grotesk:wght@300;400;500;600;700&family=JetBrains+Mono:wght@400;500;700&family=Unbounded:wght@400;500;700;800&display=swap\" rel=\"stylesheet\" />

<!-- Tailwind via CDN -->
<script src=\"https://cdn.tailwindcss.com\"></script>
<!-- GSAP -->
<script src=\"https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.5/gsap.min.js\"></script>
<script src=\"https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.5/ScrollTrigger.min.js\"></script>
<!-- Three.js -->
<script src=\"https://cdnjs.cloudflare.com/ajax/libs/three.js/0.158.0/three.min.js\"></script>

<style>
:root{
  --bg-0:#04070a;
  --bg-1:#070d11;
  --bg-2:#0b1417;
  --forest-900:#06140e;
  --forest-700:#0a2a1c;
  --forest-500:#0f4830;
  --emerald:#19f5a3;
  --emerald-glow:#3affb9;
  --emerald-deep:#0bbd7c;
  --gold:#f4c95d;
  --gold-deep:#c9962c;
  --line:rgba(255,255,255,0.07);
  --line-bright:rgba(25,245,163,0.32);
  --txt-0:#f2faf6;
  --txt-1:#c6d7ce;
  --txt-2:#7a8d83;
  --danger:#ff5577;
  --warn:#ffb547;
}
*{ -webkit-font-smoothing:antialiased; -moz-osx-font-smoothing:grayscale; }
html,body{ background:var(--bg-0); color:var(--txt-0); font-family:'Space Grotesk',system-ui,sans-serif; overflow-x:hidden; }
body{
  background:
    radial-gradient(1200px 800px at 12% -10%, rgba(25,245,163,0.10), transparent 60%),
    radial-gradient(1000px 700px at 110% 10%, rgba(244,201,93,0.06), transparent 60%),
    radial-gradient(900px 700px at 50% 120%, rgba(25,245,163,0.07), transparent 60%),
    var(--bg-0);
  min-height:100vh;
  cursor:none;
}
.font-display{ font-family:'Syne','Unbounded',sans-serif; letter-spacing:-0.02em; }
.font-mono{ font-family:'JetBrains Mono', monospace; }

/* Selection */
::selection{ background:var(--emerald); color:#04070a; }

/* Custom cursor */
.cursor-dot, .cursor-ring{ position:fixed; top:0; left:0; pointer-events:none; z-index:9999; mix-blend-mode:difference; will-change:transform; }
.cursor-dot{ width:6px; height:6px; background:#fff; border-radius:50%; transform:translate(-50%,-50%); }
.cursor-ring{ width:34px; height:34px; border:1px solid rgba(255,255,255,0.7); border-radius:50%; transform:translate(-50%,-50%); transition:width .25s ease, height .25s ease, background .25s ease; }
.cursor-ring.hover{ width:64px; height:64px; background:rgba(25,245,163,0.12); border-color:var(--emerald); }
@media (hover:none),(pointer:coarse){
  body{ cursor:auto; }
  .cursor-dot,.cursor-ring{ display:none !important; }
}

/* Scrollbar */
::-webkit-scrollbar{ width:10px; height:10px; }
::-webkit-scrollbar-track{ background:#06100c; }
::-webkit-scrollbar-thumb{ background:linear-gradient(180deg,var(--forest-500),var(--emerald-deep)); border-radius:10px; }

/* Loader */
.loader{ position:fixed; inset:0; background:var(--bg-0); z-index:1000; display:flex; align-items:center; justify-content:center; flex-direction:column; gap:24px; }
.loader-mark{ font-family:'Syne',sans-serif; font-weight:800; letter-spacing:0.4em; font-size:1rem; color:var(--emerald); }
.loader-bar{ width:240px; height:2px; background:rgba(255,255,255,0.08); overflow:hidden; border-radius:2px; }
.loader-bar > span{ display:block; height:100%; width:0%; background:linear-gradient(90deg,var(--emerald),var(--gold)); box-shadow:0 0 24px var(--emerald); }

/* Glass */
.glass{
  background:linear-gradient(180deg, rgba(15,72,48,0.22), rgba(7,13,17,0.55));
  backdrop-filter:blur(22px) saturate(140%);
  -webkit-backdrop-filter:blur(22px) saturate(140%);
  border:1px solid var(--line);
  border-radius:22px;
  box-shadow: 0 1px 0 rgba(255,255,255,0.04) inset, 0 40px 80px -40px rgba(0,0,0,0.7);
  position:relative;
  overflow:hidden;
}
.glass::before{
  content:\"\"; position:absolute; inset:0; border-radius:inherit; padding:1px;
  background:linear-gradient(135deg, rgba(25,245,163,0.45), rgba(244,201,93,0.18) 35%, rgba(255,255,255,0.04) 60%, rgba(25,245,163,0.18));
  -webkit-mask:linear-gradient(#000 0 0) content-box,linear-gradient(#000 0 0);
  -webkit-mask-composite:xor; mask-composite:exclude;
  pointer-events:none; opacity:.55;
}
.glass.dim{ background:linear-gradient(180deg, rgba(11,20,23,0.65), rgba(4,7,10,0.7)); }

/* Glow follow */
.glow-card{ position:relative; isolation:isolate; transition:transform .3s ease; }
.glow-card::after{
  content:\"\"; position:absolute; inset:-1px; border-radius:inherit; pointer-events:none; z-index:-1;
  background: radial-gradient(400px circle at var(--mx,50%) var(--my,50%), rgba(25,245,163,0.18), transparent 50%);
  opacity:0; transition:opacity .25s ease;
}
.glow-card:hover::after{ opacity:1; }

/* Buttons */
.btn{ position:relative; display:inline-flex; align-items:center; gap:.6rem; padding:.85rem 1.25rem; border-radius:999px; font-weight:600; letter-spacing:.02em; transition:transform .25s ease, box-shadow .25s ease; overflow:hidden; cursor:none; }
.btn-primary{ background:linear-gradient(135deg, var(--emerald), var(--emerald-deep)); color:#04140d; box-shadow:0 10px 30px -10px rgba(25,245,163,0.55), 0 0 0 1px rgba(25,245,163,0.4) inset; }
.btn-primary:hover{ box-shadow:0 18px 50px -10px rgba(25,245,163,0.75), 0 0 0 1px rgba(25,245,163,0.7) inset; }
.btn-ghost{ background:rgba(255,255,255,0.04); color:var(--txt-0); border:1px solid var(--line); }
.btn-ghost:hover{ border-color:var(--line-bright); }
.btn .ripple{ position:absolute; border-radius:50%; transform:translate(-50%,-50%) scale(0); background:rgba(255,255,255,0.25); pointer-events:none; }

/* Navbar */
.navbar{ position:fixed; top:18px; left:50%; transform:translateX(-50%); z-index:80; transition:all .35s cubic-bezier(.2,.7,.2,1); width:min(1280px, calc(100% - 28px)); }
.navbar.scrolled{ top:10px; }
.navbar .nav-inner{ display:flex; align-items:center; justify-content:space-between; padding:10px 14px; border-radius:999px; }

/* Tab pill */
.tab-pill{ position:relative; padding:.55rem .95rem; border-radius:999px; color:var(--txt-1); font-size:.82rem; font-weight:500; cursor:none; white-space:nowrap; }
.tab-pill:hover{ color:#fff; }
.tab-pill.active{ color:#04140d; background:linear-gradient(135deg, var(--emerald), var(--gold)); box-shadow:0 6px 24px -8px rgba(25,245,163,0.6); }

/* Stats number */
.stat-num{ font-family:'Syne',sans-serif; font-weight:700; font-size:clamp(2rem, 4.5vw, 3.4rem); line-height:1; letter-spacing:-0.03em; background:linear-gradient(180deg,#fff, #9eb5a8); -webkit-background-clip:text; background-clip:text; color:transparent; }

/* Live ticker */
.ticker{ display:flex; gap:48px; white-space:nowrap; animation:tickX 38s linear infinite; }
@keyframes tickX{ from{transform:translateX(0)} to{transform:translateX(-50%)} }

/* Section reveal */
.tab-section{ display:none; }
.tab-section.active{ display:block; }

/* Pulse orb */
.pulse-orb{ width:10px; height:10px; border-radius:50%; background:var(--emerald); box-shadow:0 0 0 0 rgba(25,245,163,0.55); animation:pulseRing 1.8s infinite; }
@keyframes pulseRing{
  0%{ box-shadow:0 0 0 0 rgba(25,245,163,0.6); }
  70%{ box-shadow:0 0 0 18px rgba(25,245,163,0); }
  100%{ box-shadow:0 0 0 0 rgba(25,245,163,0); }
}

/* SVG draw chart */
.draw-path{ stroke-dasharray:1; stroke-dashoffset:1; animation:drawPath 2.4s ease forwards; }
@keyframes drawPath{ to{ stroke-dashoffset:0; } }

/* Scanner hologram */
.scanner-shell{ position:relative; height:340px; perspective:1200px; }
.scanner-canvas{ position:absolute; inset:0; }
.scanner-overlay{ position:absolute; inset:0; pointer-events:none; }
.corner{ position:absolute; width:28px; height:28px; border:2px solid var(--emerald); }
.corner.tl{ top:18px; left:18px; border-right:none; border-bottom:none; }
.corner.tr{ top:18px; right:18px; border-left:none; border-bottom:none; }
.corner.bl{ bottom:18px; left:18px; border-right:none; border-top:none; }
.corner.br{ bottom:18px; right:18px; border-left:none; border-top:none; }
.scan-line{ position:absolute; left:18px; right:18px; height:2px; background:linear-gradient(90deg, transparent, var(--emerald), transparent); box-shadow:0 0 20px var(--emerald); top:18px; animation:scanY 2.6s ease-in-out infinite; }
@keyframes scanY{ 0%,100%{ top:18px } 50%{ top:calc(100% - 20px) } }

/* Phone */
.phone-wrap{ perspective:1400px; }
.phone-3d{ transform-style:preserve-3d; transition:transform .15s ease; }
.phone-frame{
  width:300px; height:600px; border-radius:42px;
  background:linear-gradient(160deg, #0d1612, #03080a);
  border:1px solid rgba(255,255,255,0.08);
  box-shadow: 0 60px 120px -40px rgba(0,0,0,0.9), 0 0 0 1px rgba(25,245,163,0.18) inset, 0 0 80px -20px rgba(25,245,163,0.25);
  padding:14px; position:relative;
}
.phone-screen{ width:100%; height:100%; border-radius:30px; overflow:hidden; background:#04100b; position:relative; }
.phone-notch{ position:absolute; top:10px; left:50%; transform:translateX(-50%); width:110px; height:24px; background:#000; border-radius:14px; z-index:5; }

/* Bento */
.bento-grid{ display:grid; gap:18px; grid-template-columns: repeat(12, 1fr); }
.b-1{ grid-column: span 3; } .b-2{ grid-column: span 6; } .b-3{ grid-column: span 9; } .b-4{ grid-column: span 12; }
@media (max-width: 1024px){
  .b-1,.b-2,.b-3,.b-4{ grid-column: span 12; }
}

/* Map */
.map-shell{ position:relative; height:520px; border-radius:22px; overflow:hidden; }
.map-canvas{ position:absolute; inset:0; }
.map-legend{ position:absolute; left:18px; bottom:18px; display:flex; gap:14px; font-size:.72rem; color:var(--txt-1); z-index:3; }
.map-legend .dot{ width:8px; height:8px; border-radius:50%; display:inline-block; margin-right:6px; vertical-align:middle; }

/* Tags & chips */
.chip{ display:inline-flex; align-items:center; gap:.4rem; padding:.3rem .6rem; border-radius:999px; font-size:.7rem; border:1px solid var(--line); color:var(--txt-1); background:rgba(255,255,255,0.02); }
.chip.em{ color:var(--emerald); border-color:rgba(25,245,163,0.35); }
.chip.gd{ color:var(--gold); border-color:rgba(244,201,93,0.35); }
.chip.dn{ color:var(--danger); border-color:rgba(255,85,119,0.4); }

/* Progress */
.progress{ height:6px; background:rgba(255,255,255,0.06); border-radius:999px; overflow:hidden; }
.progress > i{ display:block; height:100%; border-radius:999px; background:linear-gradient(90deg, var(--emerald), var(--gold)); box-shadow:0 0 18px rgba(25,245,163,0.35); }

/* Section heading */
.section-eyebrow{ display:inline-flex; align-items:center; gap:.5rem; color:var(--emerald); font-size:.72rem; letter-spacing:.32em; text-transform:uppercase; }
.section-eyebrow::before{ content:\"\"; width:18px; height:1px; background:var(--emerald); }

/* Hover lift */
.lift{ transition:transform .35s cubic-bezier(.2,.7,.2,1), box-shadow .35s ease; }
.lift:hover{ transform:translateY(-4px); }

/* Grain overlay (lightweight) */
.grain::after{
  content:\"\"; position:absolute; inset:0; pointer-events:none; opacity:.05; mix-blend-mode:overlay;
  background-image:url(\"data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='160' height='160'><filter id='n'><feTurbulence baseFrequency='0.9'/></filter><rect width='100%' height='100%' filter='url(%23n)' opacity='0.7'/></svg>\");
}

/* Reveal initial state for GSAP */
.reveal{ opacity:0; transform:translateY(20px); }

/* Phone screen content */
.phone-content{ padding:36px 14px 14px 14px; height:100%; color:#dff5e8; font-size:.72rem; }
.phone-balance{ background:linear-gradient(135deg, rgba(25,245,163,0.18), rgba(244,201,93,0.08)); border:1px solid rgba(25,245,163,0.25); border-radius:16px; padding:14px; }

/* Tilt indicator */
.dot-grid{
  background-image:radial-gradient(rgba(255,255,255,0.08) 1px, transparent 1px);
  background-size: 22px 22px;
}

.divider{ height:1px; background:linear-gradient(90deg, transparent, var(--line-bright), transparent); }

.kbd{ font-family:'JetBrains Mono',monospace; font-size:.65rem; padding:2px 6px; border:1px solid var(--line); border-radius:6px; color:var(--txt-1); }

a, button { cursor:none; }

/* Magnetic */
.magnetic{ display:inline-flex; transition:transform .2s ease; will-change:transform; }
</style>
</head>
<body>

<!-- Loader -->
<div class=\"loader\" id=\"loader\">
  <div class=\"loader-mark\">SEMENDO • Booting Ecosystem</div>
  <div class=\"loader-bar\"><span id=\"loaderBar\"></span></div>
  <div class=\"text-[11px] tracking-[0.35em] uppercase\" style=\"color:var(--txt-2)\">Initializing topographic mesh · GSAP · WebGL</div>
</div>

<!-- Custom cursor -->
<div class=\"cursor-ring\" id=\"cursorRing\"></div>
<div class=\"cursor-dot\" id=\"cursorDot\"></div>

<!-- NAVBAR -->
<nav class=\"navbar\" id=\"navbar\" data-testid=\"navbar\">
  <div class=\"nav-inner glass\">
    <a href=\"#\" class=\"flex items-center gap-3 pl-2\" data-testid=\"brand-link\">
      <div class=\"relative\">
        <div style=\"width:34px;height:34px;border-radius:10px;background:conic-gradient(from 0deg, var(--emerald), var(--gold), var(--emerald));box-shadow:0 0 20px rgba(25,245,163,.45)\"></div>
        <div style=\"position:absolute;inset:3px;border-radius:8px;background:#04070a;display:flex;align-items:center;justify-content:center;font-family:'Syne',sans-serif;font-weight:800;color:var(--emerald)\">S</div>
      </div>
      <div class=\"hidden sm:block\">
        <div class=\"font-display text-[15px] font-bold tracking-wide\">SEMENDO</div>
        <div class=\"text-[10px] tracking-[0.32em] uppercase\" style=\"color:var(--txt-2)\">Ekosistem · BI · 2026</div>
      </div>
    </a>
    <div class=\"hidden lg:flex items-center gap-1 glass dim\" style=\"padding:6px; border-radius:999px;\">
      <button class=\"tab-pill active\" data-tab=\"dashboard\" data-testid=\"nav-tab-dashboard\">Dashboard BI</button>
      <button class=\"tab-pill\" data-tab=\"petani\" data-testid=\"nav-tab-petani\">Aplikasi Petani</button>
      <button class=\"tab-pill\" data-tab=\"hama\" data-testid=\"nav-tab-hama\">Deteksi Hama</button>
      <button class=\"tab-pill\" data-tab=\"harga\" data-testid=\"nav-tab-harga\">Prediksi Harga</button>
      <button class=\"tab-pill\" data-tab=\"cuaca\" data-testid=\"nav-tab-cuaca\">BMKG</button>
      <button class=\"tab-pill\" data-tab=\"dampak\" data-testid=\"nav-tab-dampak\">Dampak</button>
    </div>
    <div class=\"flex items-center gap-2 pr-2\">
      <div class=\"hidden md:flex items-center gap-2 chip em\"><span class=\"pulse-orb\"></span> LIVE · <span class=\"font-mono\" id=\"navTime\">08:19:54</span></div>
      <button class=\"btn btn-primary magnetic\" data-testid=\"cta-bi-data\"><span>BI Data Console</span><span>→</span></button>
    </div>
  </div>
</nav>

<!-- HERO -->
<header class=\"relative pt-32 md:pt-40 pb-12 px-5 md:px-10 max-w-[1320px] mx-auto\">
  <div class=\"grid grid-cols-12 gap-6 items-end\">
    <div class=\"col-span-12 lg:col-span-8\">
      <div class=\"reveal section-eyebrow mb-5\">Sriwijaya Economic Forum · Bank Indonesia · 2026</div>
      <h1 class=\"reveal font-display font-extrabold leading-[0.92] text-[clamp(2.6rem,7vw,5.6rem)]\">
        Sistem<br/>
        <span style=\"background:linear-gradient(120deg,var(--emerald),var(--gold) 60%,#fff);-webkit-background-clip:text;background-clip:text;color:transparent\">Ekosistem Mandiri</span><br/>
        Ekonomi Daerah.
      </h1>
      <p class=\"reveal mt-6 max-w-[640px] text-[15px] md:text-base\" style=\"color:var(--txt-1)\">
        Jembatan data dua-arah antara <span style=\"color:var(--emerald)\">1.247 petani Sumatera Selatan</span> dan
        Bank Indonesia. Offline-first, prediksi 7–14 hari, dan diagnosa AI — diramu dengan behavioral nudge
        yang mengurangi <em style=\"color:var(--gold)\">asimetri informasi</em> di blank spot.
      </p>
      <div class=\"reveal flex flex-wrap gap-3 mt-7\">
        <button class=\"btn btn-primary magnetic\" data-testid=\"hero-cta-explore\"><span>Telusuri Ekosistem</span><span>→</span></button>
        <button class=\"btn btn-ghost magnetic\" data-testid=\"hero-cta-watch\"><span>▶</span><span>Live Sinkron Demo</span></button>
      </div>
    </div>
    <div class=\"col-span-12 lg:col-span-4\">
      <div class=\"glass glow-card grain p-5 md:p-6 lift reveal\" data-testid=\"hero-mini-card\">
        <div class=\"flex items-center justify-between\">
          <div class=\"section-eyebrow\">Sumsel · Real-time</div>
          <span class=\"chip em\"><span class=\"pulse-orb\"></span>Streaming</span>
        </div>
        <div class=\"mt-5\">
          <div class=\"text-[11px] uppercase tracking-[0.3em]\" style=\"color:var(--txt-2)\">Akurasi data BI</div>
          <div class=\"stat-num mt-2 font-mono\"><span id=\"accNum\">0</span><span style=\"color:var(--emerald)\">%</span></div>
          <div class=\"text-xs mt-1\" style=\"color:var(--txt-2)\">vs manual 71% · validated PBPS</div>
        </div>
        <div class=\"divider my-4\"></div>
        <div class=\"grid grid-cols-3 gap-3\">
          <div>
            <div class=\"text-[10px] uppercase tracking-[0.25em]\" style=\"color:var(--txt-2)\">Petani</div>
            <div class=\"font-display text-xl mt-1 font-bold font-mono\" id=\"kpiFarmers\">0</div>
          </div>
          <div>
            <div class=\"text-[10px] uppercase tracking-[0.25em]\" style=\"color:var(--txt-2)\">Records</div>
            <div class=\"font-display text-xl mt-1 font-bold font-mono\" id=\"kpiRecords\">0</div>
          </div>
          <div>
            <div class=\"text-[10px] uppercase tracking-[0.25em]\" style=\"color:var(--txt-2)\">Desa</div>
            <div class=\"font-display text-xl mt-1 font-bold font-mono\" id=\"kpiVillages\">0</div>
          </div>
        </div>
      </div>
    </div>
  </div>
</header>

<!-- LIVE TICKER -->
<div class=\"border-y\" style=\"border-color:var(--line); background:linear-gradient(180deg, rgba(255,255,255,0.02), transparent)\">
  <div class=\"overflow-hidden py-3\">
    <div class=\"ticker font-mono text-[12px]\" style=\"color:var(--txt-1)\" id=\"liveTicker\">
      <!-- Filled by JS -->
    </div>
  </div>
</div>

<!-- MAIN TAB CONTENT -->
<main class=\"max-w-[1320px] mx-auto px-5 md:px-10 py-10 md:py-14\">

<!-- ====== DASHBOARD BI ====== -->
<section class=\"tab-section active\" data-section=\"dashboard\">
  <div class=\"flex items-end justify-between flex-wrap gap-4 mb-6\">
    <div>
      <div class=\"section-eyebrow mb-2\">Konsol Komando BI</div>
      <h2 class=\"font-display text-3xl md:text-4xl font-bold\">Peta Sinkronisasi Real-Time<br/>Sumatera Selatan</h2>
    </div>
    <div class=\"flex gap-2 flex-wrap\">
      <span class=\"chip em\"><span class=\"pulse-orb\"></span> 8 kab online</span>
      <span class=\"chip gd\">Δ Delta Sync 65%</span>
      <span class=\"chip\">Starlink mesh aktif</span>
    </div>
  </div>

  <div class=\"bento-grid\">
    <!-- 3D MAP -->
    <div class=\"b-3 glass grain glow-card lift reveal p-3 md:p-4\" data-testid=\"map-card\">
      <div class=\"map-shell\">
        <canvas class=\"map-canvas\" id=\"mapCanvas\"></canvas>
        <div class=\"map-legend glass\" style=\"padding:8px 12px;border-radius:999px;\">
          <span><span class=\"dot\" style=\"background:var(--emerald);box-shadow:0 0 12px var(--emerald)\"></span>Online</span>
          <span><span class=\"dot\" style=\"background:var(--gold);box-shadow:0 0 12px var(--gold)\"></span>Syncing</span>
          <span><span class=\"dot\" style=\"background:var(--danger);box-shadow:0 0 12px var(--danger)\"></span>Blank Spot</span>
        </div>
        <div class=\"absolute top-4 right-4 glass\" style=\"padding:8px 12px;border-radius:14px;font-size:.7rem;color:var(--txt-1)\">
          <span class=\"kbd\">DRAG</span> rotate · <span class=\"kbd\">SCROLL</span> zoom
        </div>
      </div>
    </div>

    <!-- BI Stat Tower -->
    <div class=\"b-1 reveal flex flex-col gap-4\">
      <div class=\"glass grain glow-card lift p-5\" data-testid=\"stat-petani\">
        <div class=\"section-eyebrow\">Petani Aktif</div>
        <div class=\"stat-num font-mono mt-3\" id=\"bigFarmers\">0</div>
        <div class=\"text-xs\" style=\"color:var(--txt-2)\">terhubung real-time</div>
        <div class=\"progress mt-3\"><i style=\"width:82%\"></i></div>
      </div>
      <div class=\"glass grain glow-card lift p-5\" data-testid=\"stat-records\">
        <div class=\"section-eyebrow gd\" style=\"color:var(--gold)\">Records Hari Ini</div>
        <div class=\"stat-num font-mono mt-3\" id=\"bigRecords\">0</div>
        <div class=\"text-xs\" style=\"color:var(--txt-2)\">→ BI Data Lake</div>
        <div class=\"progress mt-3\"><i style=\"width:67%; background:linear-gradient(90deg,var(--gold),var(--emerald))\"></i></div>
      </div>
      <div class=\"glass grain glow-card lift p-5\" data-testid=\"stat-blank\">
        <div class=\"section-eyebrow\" style=\"color:var(--danger)\">Blank Spot Tercover</div>
        <div class=\"stat-num font-mono mt-3\" id=\"bigBlank\">0</div>
        <div class=\"text-xs\" style=\"color:var(--txt-2)\">dari 814 desa target</div>
        <div class=\"progress mt-3\"><i style=\"width:54%; background:linear-gradient(90deg,#ff7798,var(--gold))\"></i></div>
      </div>
    </div>

    <!-- Andil Inflasi -->
    <div class=\"b-2 glass grain glow-card lift reveal p-6\" data-testid=\"inflasi-card\">
      <div class=\"flex items-center justify-between mb-4\">
        <div>
          <div class=\"section-eyebrow\">Andil Inflasi · Volatile Food</div>
          <div class=\"font-display text-xl mt-1 font-bold\">Sumatera Selatan · Des 2025 (BPS)</div>
        </div>
        <span class=\"chip gd\">y-on-y 2.91%</span>
      </div>
      <div class=\"grid grid-cols-2 md:grid-cols-4 gap-3\">
        <div class=\"glass dim p-4 lift\">
          <div class=\"text-2xl\">🌶️</div>
          <div class=\"text-xs mt-2\" style=\"color:var(--txt-2)\">Cabai Merah</div>
          <div class=\"font-display text-2xl font-bold font-mono\" style=\"color:var(--danger)\">+0.44%</div>
          <div class=\"text-[10px]\" style=\"color:var(--txt-2)\">→ Agregasi koperasi</div>
        </div>
        <div class=\"glass dim p-4 lift\">
          <div class=\"text-2xl\">🌾</div>
          <div class=\"text-xs mt-2\" style=\"color:var(--txt-2)\">Beras IR64</div>
          <div class=\"font-display text-2xl font-bold font-mono\" style=\"color:var(--warn)\">+0.18%</div>
          <div class=\"text-[10px]\" style=\"color:var(--txt-2)\">→ Direct pasar induk</div>
        </div>
        <div class=\"glass dim p-4 lift\">
          <div class=\"text-2xl\">🍗</div>
          <div class=\"text-xs mt-2\" style=\"color:var(--txt-2)\">Daging Ayam</div>
          <div class=\"font-display text-2xl font-bold font-mono\" style=\"color:var(--gold)\">+0.09%</div>
          <div class=\"text-[10px]\" style=\"color:var(--txt-2)\">→ Real-time supply</div>
        </div>
        <div class=\"glass dim p-4 lift\">
          <div class=\"text-2xl\">🧅</div>
          <div class=\"text-xs mt-2\" style=\"color:var(--txt-2)\">Bawang Merah</div>
          <div class=\"font-display text-2xl font-bold font-mono\" style=\"color:var(--emerald)\">+0.07%</div>
          <div class=\"text-[10px]\" style=\"color:var(--txt-2)\">→ Potong perantara</div>
        </div>
      </div>
      <div class=\"divider my-5\"></div>
      <p class=\"text-sm\" style=\"color:var(--txt-1)\"><span style=\"color:var(--emerald)\">Insight BI:</span> Data 1.247 petani di 12 kabupaten diterima real-time. Memungkinkan kebijakan pengendalian volatile food berbasis bukti, bukan estimasi triwulanan.</p>
    </div>

    <!-- Aktivitas + Status -->
    <div class=\"b-2 glass grain glow-card lift reveal p-6\" data-testid=\"activity-card\">
      <div class=\"flex items-center justify-between mb-4\">
        <div class=\"section-eyebrow\">⚡ Aktivitas Real-Time</div>
        <span class=\"chip em\"><span class=\"pulse-orb\"></span>streaming</span>
      </div>
      <div class=\"space-y-3\" id=\"activityList\"></div>
    </div>

    <div class=\"b-2 glass grain glow-card lift reveal p-6\" data-testid=\"kabupaten-card\">
      <div class=\"flex items-center justify-between mb-4\">
        <div class=\"section-eyebrow gd\" style=\"color:var(--gold)\">Sinkronisasi per Kabupaten</div>
        <span class=\"chip\">8 / 12</span>
      </div>
      <div class=\"space-y-3\" id=\"kabList\"></div>
    </div>

  </div>
</section>

<!-- ====== APLIKASI PETANI ====== -->
<section class=\"tab-section\" data-section=\"petani\">
  <div class=\"flex items-end justify-between flex-wrap gap-4 mb-6\">
    <div>
      <div class=\"section-eyebrow mb-2\">Petani · Genggaman pertama Desa</div>
      <h2 class=\"font-display text-3xl md:text-4xl font-bold\">Aplikasi Petani · Offline-First<br/><span style=\"color:var(--emerald)\">Mode Luring</span> Otonom</h2>
    </div>
    <span class=\"chip em\">Delta Sync siap kirim</span>
  </div>

  <div class=\"bento-grid\">
    <div class=\"b-2 reveal flex items-center justify-center py-8\">
      <div class=\"phone-wrap\" id=\"phoneWrap\">
        <div class=\"phone-3d\" id=\"phone3D\">
          <div class=\"phone-frame\">
            <div class=\"phone-notch\"></div>
            <div class=\"phone-screen\">
              <div class=\"phone-content\">
                <div class=\"flex items-center justify-between\" style=\"color:var(--txt-2)\">
                  <span class=\"font-mono\">09:41</span>
                  <span class=\"chip dn\" style=\"font-size:.6rem\">📵 Luring</span>
                </div>
                <div class=\"mt-4\">
                  <div style=\"color:var(--txt-2);font-size:.65rem\">Halo, Pak Rudi 👋</div>
                  <div class=\"font-display text-lg font-bold mt-1\">Mode Luring Aktif</div>
                </div>
                <div class=\"phone-balance mt-3\">
                  <div style=\"color:var(--gold);font-size:.65rem\">⚠ PERINGATAN KERUGIAN</div>
                  <div style=\"font-size:.7rem;margin-top:4px\">Jual ke tengkulak = rugi est. <b style=\"color:var(--danger)\">Rp 1.200.000</b> vs koperasi</div>
                </div>
                <div class=\"mt-3 grid grid-cols-2 gap-2\">
                  <div class=\"glass dim\" style=\"padding:8px;border-radius:10px\">
                    <div style=\"font-size:.6rem;color:var(--txt-2)\">Hasil Panen</div>
                    <div class=\"font-display font-bold\" style=\"color:var(--emerald)\">240<span style=\"font-size:.6rem\">kg</span></div>
                  </div>
                  <div class=\"glass dim\" style=\"padding:8px;border-radius:10px\">
                    <div style=\"font-size:.6rem;color:var(--txt-2)\">Est. Pendapatan</div>
                    <div class=\"font-display font-bold\" style=\"color:var(--gold)\">Rp4,8<span style=\"font-size:.6rem\">jt</span></div>
                  </div>
                </div>
                <div class=\"mt-3\" style=\"font-size:.62rem;color:var(--txt-2)\">💡 87% petani Desa Srimenanti pakai pantau harga — rata-rata untung +Rp 2,1jt</div>
                <div class=\"mt-4\" style=\"font-size:.6rem;color:var(--txt-2)\">3 record antri · aman saat sinyal putus</div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class=\"b-2 reveal space-y-4\">
      <div class=\"glass grain glow-card lift p-6\" data-testid=\"nudge-default\">
        <div class=\"flex items-start gap-4\">
          <div style=\"font-size:1.6rem\">⚙️</div>
          <div>
            <div class=\"section-eyebrow\">Default Options</div>
            <h3 class=\"font-display text-xl font-bold mt-1\">Sistem rekomendasi sebagai pilihan standar</h3>
            <p class=\"text-sm mt-2\" style=\"color:var(--txt-1)\">Mengurangi beban kognitif petani (bounded rationality). Harga wajar & koperasi terdekat di-default-kan, bukan dicari.</p>
          </div>
        </div>
      </div>
      <div class=\"glass grain glow-card lift p-6\" data-testid=\"nudge-social\">
        <div class=\"flex items-start gap-4\">
          <div style=\"font-size:1.6rem\">👥</div>
          <div>
            <div class=\"section-eyebrow\" style=\"color:var(--gold)\">Social Norms</div>
            <h3 class=\"font-display text-xl font-bold mt-1\">\"87% petani desa Anda sudah gunakan\"</h3>
            <p class=\"text-sm mt-2\" style=\"color:var(--txt-1)\">Memanfaatkan validasi kelompok untuk mempercepat adopsi teknologi di desa konservatif.</p>
          </div>
        </div>
      </div>
      <div class=\"glass grain glow-card lift p-6\" data-testid=\"nudge-loss\">
        <div class=\"flex items-start gap-4\">
          <div style=\"font-size:1.6rem\">⚠️</div>
          <div>
            <div class=\"section-eyebrow\" style=\"color:var(--danger)\">Loss Aversion</div>
            <h3 class=\"font-display text-xl font-bold mt-1\">Kerugian konkret vs harga koperasi</h3>
            <p class=\"text-sm mt-2\" style=\"color:var(--txt-1)\">Secara psikologis lebih kuat menggerakkan tindakan dari pada janji keuntungan masa depan.</p>
          </div>
        </div>
      </div>
    </div>

    <div class=\"b-4 reveal glass grain p-6 md:p-8\" data-testid=\"supply-compare\">
      <div class=\"section-eyebrow mb-4\">Transformasi Rantai Pasok Pangan</div>
      <div class=\"grid md:grid-cols-2 gap-6\">
        <div class=\"glass dim p-5\">
          <div class=\"flex items-center justify-between\">
            <div class=\"font-display font-bold text-lg\" style=\"color:var(--danger)\">❌ Tanpa SEMENDO</div>
            <span class=\"chip dn\">Konvensional</span>
          </div>
          <ul class=\"mt-4 space-y-2 text-sm\" style=\"color:var(--txt-1)\">
            <li class=\"flex justify-between\"><span>Lapis Distribusi</span><b class=\"font-mono\">5–7 lapis</b></li>
            <li class=\"flex justify-between\"><span>Farmer's Share</span><b class=\"font-mono\">&lt; 50%</b></li>
            <li class=\"flex justify-between\"><span>Asimetri Informasi</span><b class=\"font-mono\" style=\"color:var(--danger)\">Tinggi</b></li>
            <li class=\"flex justify-between\"><span>Akurasi Data BI</span><b class=\"font-mono\">~71%</b></li>
            <li class=\"flex justify-between\"><span>Locus of Control</span><b class=\"font-mono\">Eksternal</b></li>
          </ul>
        </div>
        <div class=\"glass dim p-5\" style=\"border:1px solid rgba(25,245,163,0.3)\">
          <div class=\"flex items-center justify-between\">
            <div class=\"font-display font-bold text-lg\" style=\"color:var(--emerald)\">✅ Dengan SEMENDO</div>
            <span class=\"chip em\">Koperasi Digital</span>
          </div>
          <ul class=\"mt-4 space-y-2 text-sm\" style=\"color:var(--txt-1)\">
            <li class=\"flex justify-between\"><span>Lapis Distribusi</span><b class=\"font-mono\" style=\"color:var(--emerald)\">2–3 lapis</b></li>
            <li class=\"flex justify-between\"><span>Farmer's Share</span><b class=\"font-mono\" style=\"color:var(--emerald)\">&gt; 83.29%</b></li>
            <li class=\"flex justify-between\"><span>Asimetri Informasi</span><b class=\"font-mono\" style=\"color:var(--emerald)\">Rendah</b></li>
            <li class=\"flex justify-between\"><span>Akurasi Data BI</span><b class=\"font-mono\" style=\"color:var(--emerald)\">98.3%</b></li>
            <li class=\"flex justify-between\"><span>Locus of Control</span><b class=\"font-mono\" style=\"color:var(--emerald)\">Internal</b></li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ====== HAMA ====== -->
<section class=\"tab-section\" data-section=\"hama\">
  <div class=\"flex items-end justify-between flex-wrap gap-4 mb-6\">
    <div>
      <div class=\"section-eyebrow mb-2\">AgriVision-ID v2.1</div>
      <h2 class=\"font-display text-3xl md:text-4xl font-bold\">Deteksi Hama AI · <span style=\"color:var(--emerald)\">Hologram Scanner</span></h2>
    </div>
    <span class=\"chip em\">91.4% akurasi</span>
  </div>

  <div class=\"bento-grid\">
    <div class=\"b-2 reveal glass grain p-4\">
      <div class=\"scanner-shell\">
        <canvas class=\"scanner-canvas\" id=\"scannerCanvas\"></canvas>
        <div class=\"scanner-overlay\">
          <div class=\"corner tl\"></div><div class=\"corner tr\"></div>
          <div class=\"corner bl\"></div><div class=\"corner br\"></div>
          <div class=\"scan-line\"></div>
        </div>
        <div class=\"absolute bottom-4 left-1/2 -translate-x-1/2 chip em\" style=\"z-index:3\"><span class=\"pulse-orb\"></span>Analyzing leaf · 94%</div>
      </div>
      <div class=\"grid grid-cols-4 gap-3 mt-5\">
        <div class=\"text-center\"><div class=\"font-display font-bold text-xl font-mono\">2.847</div><div class=\"text-[10px]\" style=\"color:var(--txt-2)\">Total Scan</div></div>
        <div class=\"text-center\"><div class=\"font-display font-bold text-xl font-mono\" style=\"color:var(--gold)\">312</div><div class=\"text-[10px]\" style=\"color:var(--txt-2)\">Terdeteksi</div></div>
        <div class=\"text-center\"><div class=\"font-display font-bold text-xl font-mono\" style=\"color:var(--emerald)\">91.4%</div><div class=\"text-[10px]\" style=\"color:var(--txt-2)\">Akurasi</div></div>
        <div class=\"text-center\"><div class=\"font-display font-bold text-xl font-mono\">67%</div><div class=\"text-[10px]\" style=\"color:var(--txt-2)\">Hemat Biaya</div></div>
      </div>
    </div>

    <div class=\"b-2 reveal space-y-3\" data-testid=\"detection-list\">
      <div class=\"glass grain glow-card lift p-5\">
        <div class=\"flex items-start gap-3\">
          <div class=\"text-2xl\">🌶️</div>
          <div class=\"flex-1\">
            <div class=\"flex items-center justify-between\"><div class=\"font-display font-bold\">Antraknosa (Colletotrichum)</div><span class=\"chip dn\">94%</span></div>
            <div class=\"text-xs mt-1\" style=\"color:var(--txt-2)\">Pak Ahmad · Semendo Darat Ulu · 4 Jun 2026</div>
            <div class=\"text-xs mt-2\" style=\"color:var(--txt-1)\">💊 Semprot mankozeb + azoksistrobin. Cabut tanaman terinfeksi berat.</div>
          </div>
        </div>
      </div>
      <div class=\"glass grain glow-card lift p-5\">
        <div class=\"flex items-start gap-3\">
          <div class=\"text-2xl\">🌾</div>
          <div class=\"flex-1\">
            <div class=\"flex items-center justify-between\"><div class=\"font-display font-bold\">Wereng Batang Coklat</div><span class=\"chip gd\">89%</span></div>
            <div class=\"text-xs mt-1\" style=\"color:var(--txt-2)\">Ibu Sari · Kec. Betung Banyuasin · 3 Jun 2026</div>
            <div class=\"text-xs mt-2\" style=\"color:var(--txt-1)\">🔫 Insektisida imidakloprid stadia nimfa. Monitoring 3 hari.</div>
          </div>
        </div>
      </div>
      <div class=\"glass grain glow-card lift p-5\">
        <div class=\"flex items-start gap-3\">
          <div class=\"text-2xl\">☕</div>
          <div class=\"flex-1\">
            <div class=\"flex items-center justify-between\"><div class=\"font-display font-bold\">Penggerek Buah Kopi (PBKo)</div><span class=\"chip gd\">82%</span></div>
            <div class=\"text-xs mt-1\" style=\"color:var(--txt-2)\">Pak Suparman · Semendo Darat Muara Enim</div>
            <div class=\"text-xs mt-2\" style=\"color:var(--txt-1)\">🪤 Perangkap alkohol 3% + Beauveria bassiana bioinsektisida.</div>
          </div>
        </div>
      </div>
      <div class=\"glass grain glow-card lift p-5\">
        <div class=\"flex items-start gap-3\">
          <div class=\"text-2xl\">🌿</div>
          <div class=\"flex-1\">
            <div class=\"flex items-center justify-between\"><div class=\"font-display font-bold\" style=\"color:var(--emerald)\">Bawang Merah · Sehat</div><span class=\"chip em\">97%</span></div>
            <div class=\"text-xs mt-1\" style=\"color:var(--txt-2)\">Pak Hendra · Lahat</div>
            <div class=\"text-xs mt-2\" style=\"color:var(--txt-1)\">✅ Pertahankan jadwal pemupukan. Estimasi panen 14 hari.</div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ====== HARGA ====== -->
<section class=\"tab-section\" data-section=\"harga\">
  <div class=\"flex items-end justify-between flex-wrap gap-4 mb-6\">
    <div>
      <div class=\"section-eyebrow mb-2\">PIHPS+ · Model SEMENDO</div>
      <h2 class=\"font-display text-3xl md:text-4xl font-bold\">Prediksi Harga 7–14 Hari<br/><span style=\"color:var(--gold)\">87.6%</span> akurasi vs aktual</h2>
    </div>
    <span class=\"chip em\">4 komoditas live</span>
  </div>

  <div class=\"bento-grid\">
    <div class=\"b-3 reveal glass grain p-6\" data-testid=\"chart-card\">
      <div class=\"flex items-center justify-between mb-4\">
        <div class=\"font-display font-bold text-lg\">🌶️ Cabai Merah · Proyeksi 14 hari</div>
        <div class=\"flex items-center gap-3\">
          <span class=\"chip dn\">↑ +18%</span>
          <span class=\"font-mono text-sm\" style=\"color:var(--txt-2)\">Rp 28.000 → Rp 33.900</span>
        </div>
      </div>
      <svg id=\"priceChart\" viewBox=\"0 0 800 280\" preserveAspectRatio=\"none\" style=\"width:100%;height:280px\">
        <defs>
          <linearGradient id=\"gA\" x1=\"0\" x2=\"0\" y1=\"0\" y2=\"1\">
            <stop offset=\"0%\" stop-color=\"#19f5a3\" stop-opacity=\"0.35\"/>
            <stop offset=\"100%\" stop-color=\"#19f5a3\" stop-opacity=\"0\"/>
          </linearGradient>
          <linearGradient id=\"gB\" x1=\"0\" x2=\"1\" y1=\"0\" y2=\"0\">
            <stop offset=\"0%\" stop-color=\"#19f5a3\"/>
            <stop offset=\"100%\" stop-color=\"#f4c95d\"/>
          </linearGradient>
          <filter id=\"glowChart\" x=\"-20%\" y=\"-20%\" width=\"140%\" height=\"140%\">
            <feGaussianBlur stdDeviation=\"3.4\" result=\"blur\"/>
            <feMerge><feMergeNode in=\"blur\"/><feMergeNode in=\"SourceGraphic\"/></feMerge>
          </filter>
        </defs>
        <!-- grid -->
        <g stroke=\"rgba(255,255,255,0.05)\" stroke-width=\"1\">
          <line x1=\"0\" y1=\"60\" x2=\"800\" y2=\"60\"/><line x1=\"0\" y1=\"120\" x2=\"800\" y2=\"120\"/>
          <line x1=\"0\" y1=\"180\" x2=\"800\" y2=\"180\"/><line x1=\"0\" y1=\"240\" x2=\"800\" y2=\"240\"/>
        </g>
        <!-- Area -->
        <path id=\"areaPath\" d=\"\" fill=\"url(#gA)\"/>
        <!-- Line -->
        <path id=\"linePath\" class=\"draw-path\" d=\"\" fill=\"none\" stroke=\"url(#gB)\" stroke-width=\"3\" stroke-linecap=\"round\" stroke-linejoin=\"round\" filter=\"url(#glowChart)\"/>
        <!-- Points -->
        <g id=\"chartPoints\"></g>
      </svg>
      <div class=\"grid grid-cols-3 gap-3 mt-3 text-xs\" style=\"color:var(--txt-2)\">
        <div>Hist: <b style=\"color:var(--txt-1)\" class=\"font-mono\">Rp 23.100</b></div>
        <div>Saat ini: <b style=\"color:var(--emerald)\" class=\"font-mono\">Rp 28.000</b></div>
        <div>Pred max: <b style=\"color:var(--gold)\" class=\"font-mono\">Rp 33.900</b></div>
      </div>
    </div>

    <div class=\"b-1 reveal space-y-3\">
      <div class=\"glass grain glow-card lift p-5\">
        <div class=\"flex items-center justify-between\"><span>🌾 Beras IR64</span><span class=\"chip dn\">↓ -8%</span></div>
        <div class=\"stat-num font-mono mt-3\" style=\"font-size:1.6rem\">Rp 12.500</div>
        <div class=\"text-[11px] mt-1\" style=\"color:var(--txt-2)\">⚡ Jual segera sebelum 10 Jun</div>
      </div>
      <div class=\"glass grain glow-card lift p-5\">
        <div class=\"flex items-center justify-between\"><span>🧅 Bawang Merah</span><span class=\"chip gd\">↑ +11%</span></div>
        <div class=\"stat-num font-mono mt-3\" style=\"font-size:1.6rem\">Rp 22.000</div>
        <div class=\"text-[11px] mt-1\" style=\"color:var(--txt-2)\">🎯 Jual optimal 12–15 Jun</div>
      </div>
      <div class=\"glass grain glow-card lift p-5\">
        <div class=\"flex items-center justify-between\"><span>☕ Kopi Semendo</span><span class=\"chip em\">→ Stabil</span></div>
        <div class=\"stat-num font-mono mt-3\" style=\"font-size:1.6rem\">Rp 62.000</div>
        <div class=\"text-[11px] mt-1\" style=\"color:var(--txt-2)\">⏳ Pantau 5 hari ke depan</div>
      </div>
    </div>

    <div class=\"b-4 reveal glass grain p-6\" data-testid=\"insight\">
      <div class=\"section-eyebrow mb-3\">🧠 Insight Prediksi Minggu Ini</div>
      <div class=\"grid md:grid-cols-3 gap-4\">
        <div class=\"glass dim p-4\"><div class=\"chip em mb-2\">BELI</div><p class=\"text-sm\" style=\"color:var(--txt-1)\">Cabai Merah diprediksi naik 18% dalam 7 hari — tunda jual hingga puncak harga.</p></div>
        <div class=\"glass dim p-4\"><div class=\"chip gd mb-2\">JUAL</div><p class=\"text-sm\" style=\"color:var(--txt-1)\">Beras IR64 diprediksi turun 8% dalam 10 hari — segera jual via koperasi.</p></div>
        <div class=\"glass dim p-4\"><div class=\"chip mb-2\">PANTAU</div><p class=\"text-sm\" style=\"color:var(--txt-1)\">Kopi Semendo: musim panen raya — monitor 5 hari ke depan.</p></div>
      </div>
    </div>
  </div>
</section>

<!-- ====== CUACA ====== -->
<section class=\"tab-section\" data-section=\"cuaca\">
  <div class=\"flex items-end justify-between flex-wrap gap-4 mb-6\">
    <div>
      <div class=\"section-eyebrow mb-2\">BMKG Sumsel · Cache 24 jam</div>
      <h2 class=\"font-display text-3xl md:text-4xl font-bold\">Prakiraan & Peringatan<br/>Cuaca Lokal</h2>
    </div>
    <span class=\"chip\" style=\"color:var(--warn);border-color:rgba(255,181,71,0.4)\">⚠ Peringatan dini aktif</span>
  </div>
  <div class=\"bento-grid\">
    <div class=\"b-4 reveal glass grain p-6\" style=\"border:1px solid rgba(255,181,71,0.3)\">
      <div class=\"flex items-start gap-4\">
        <div class=\"text-4xl\">⛈️</div>
        <div>
          <div class=\"section-eyebrow\" style=\"color:var(--warn)\">⚠ Peringatan dini BMKG</div>
          <h3 class=\"font-display text-2xl font-bold mt-1\">Hujan lebat + angin kencang</h3>
          <p class=\"mt-2 text-sm\" style=\"color:var(--txt-1)\">Wilayah Muba, PALI, OKU Timur · 3–5 Juni 2026 · 14.00–22.00 WIB · curah hujan 80–120 mm/hari.</p>
          <div class=\"mt-3 chip em\">💡 Nudge: \"Curah hujan tinggi 2 hari ke depan — pertimbangkan panen lebih awal!\"</div>
        </div>
      </div>
    </div>

    <div class=\"b-1 reveal glass grain glow-card lift p-5\">
      <div class=\"flex items-center justify-between\"><span>☀️ Palembang</span><span class=\"chip em\">Aman</span></div>
      <div class=\"font-display text-4xl font-bold font-mono mt-3\">29°</div>
      <div class=\"text-xs\" style=\"color:var(--txt-2)\">Berawan · 72% lembab · 20% hujan</div>
      <div class=\"divider my-3\"></div>
      <div class=\"text-xs\" style=\"color:var(--emerald)\">✓ Ideal pemupukan daun</div>
    </div>
    <div class=\"b-1 reveal glass grain glow-card lift p-5\">
      <div class=\"flex items-center justify-between\"><span>⛈️ Muba</span><span class=\"chip dn\">Waspada</span></div>
      <div class=\"font-display text-4xl font-bold font-mono mt-3\">24°</div>
      <div class=\"text-xs\" style=\"color:var(--txt-2)\">Hujan lebat · 35km/j · 95% hujan</div>
      <div class=\"divider my-3\"></div>
      <div class=\"text-xs\" style=\"color:var(--danger)\">⚠ Tunda panen 2 hari</div>
    </div>
    <div class=\"b-1 reveal glass grain glow-card lift p-5\">
      <div class=\"flex items-center justify-between\"><span>🌤️ Muara Enim</span><span class=\"chip gd\">Optimal</span></div>
      <div class=\"font-display text-4xl font-bold font-mono mt-3\">26°</div>
      <div class=\"text-xs\" style=\"color:var(--txt-2)\">Cerah berawan · ideal</div>
      <div class=\"divider my-3\"></div>
      <div class=\"text-xs\" style=\"color:var(--gold)\">☕ Panen kopi optimal Kam–Jum</div>
    </div>
  </div>
</section>

<!-- ====== DAMPAK ====== -->
<section class=\"tab-section\" data-section=\"dampak\">
  <div class=\"flex items-end justify-between flex-wrap gap-4 mb-6\">
    <div>
      <div class=\"section-eyebrow mb-2\">Proyeksi Dampak · 18 bulan</div>
      <h2 class=\"font-display text-3xl md:text-4xl font-bold\">Roadmap Akselerasi<br/>Digitalisasi Desa Pangan</h2>
    </div>
    <span class=\"chip em\">Target inflasi &lt; 2%</span>
  </div>
  <div class=\"bento-grid\">
    <div class=\"b-2 reveal glass grain p-6\">
      <div class=\"section-eyebrow\">Farmer's Share</div>
      <div class=\"mt-4 grid grid-cols-2 gap-4\">
        <div>
          <div class=\"text-xs\" style=\"color:var(--txt-2)\">Tengkulak</div>
          <div class=\"stat-num font-mono mt-1\" style=\"color:var(--danger);font-size:2.2rem\">&lt;50%</div>
          <div class=\"text-[11px] mt-1\" style=\"color:var(--txt-2)\">Margin tipis</div>
        </div>
        <div>
          <div class=\"text-xs\" style=\"color:var(--txt-2)\">SEMENDO</div>
          <div class=\"stat-num font-mono mt-1\" style=\"color:var(--emerald);font-size:2.2rem\">83.29%</div>
          <div class=\"text-[11px] mt-1\" style=\"color:var(--txt-2)\">Petani untung</div>
        </div>
      </div>
      <div class=\"divider my-4\"></div>
      <div class=\"chip em\">+33 pp per petani per musim panen</div>
    </div>

    <div class=\"b-2 reveal glass grain p-6\">
      <div class=\"section-eyebrow gd\" style=\"color:var(--gold)\">Andil Inflasi Volatile Food</div>
      <div class=\"mt-5 space-y-3\">
        <div>
          <div class=\"flex justify-between text-sm\"><span>Cabai Merah</span><b class=\"font-mono\">0.44%</b></div>
          <div class=\"progress mt-1\"><i style=\"width:88%;background:linear-gradient(90deg,#ff5577,#ffb547)\"></i></div>
        </div>
        <div>
          <div class=\"flex justify-between text-sm\"><span>Beras</span><b class=\"font-mono\">0.18%</b></div>
          <div class=\"progress mt-1\"><i style=\"width:36%;background:linear-gradient(90deg,#ffb547,#f4c95d)\"></i></div>
        </div>
        <div>
          <div class=\"flex justify-between text-sm\"><span>Daging Ayam</span><b class=\"font-mono\">0.09%</b></div>
          <div class=\"progress mt-1\"><i style=\"width:18%;background:linear-gradient(90deg,#f4c95d,#19f5a3)\"></i></div>
        </div>
        <div>
          <div class=\"flex justify-between text-sm\"><span>Bawang Merah</span><b class=\"font-mono\">0.07%</b></div>
          <div class=\"progress mt-1\"><i style=\"width:14%\"></i></div>
        </div>
      </div>
      <div class=\"divider my-4\"></div>
      <div class=\"text-sm\" style=\"color:var(--txt-1)\">Inflasi y-on-y Sumsel <b class=\"font-mono\" style=\"color:var(--gold)\">2.91%</b> · target SEMENDO <b style=\"color:var(--emerald)\">&lt; 2%</b></div>
    </div>

    <div class=\"b-4 reveal grid md:grid-cols-4 gap-4\" data-testid=\"roadmap\">
      <div class=\"glass grain glow-card lift p-5\">
        <div class=\"chip em\">FASE I · 1–4</div>
        <h4 class=\"font-display font-bold text-lg mt-3\">Konsolidasi</h4>
        <p class=\"text-xs mt-2\" style=\"color:var(--txt-1)\">Pembentukan koperasi agregator berbadan hukum & pemetaan 814 desa blank spot.</p>
      </div>
      <div class=\"glass grain glow-card lift p-5\">
        <div class=\"chip gd\">FASE II · 5–8</div>
        <h4 class=\"font-display font-bold text-lg mt-3\">Penguatan</h4>
        <p class=\"text-xs mt-2\" style=\"color:var(--txt-1)\">Literasi digital petani & pelatihan manajemen koperasi.</p>
      </div>
      <div class=\"glass grain glow-card lift p-5\">
        <div class=\"chip em\">FASE III · 9–14</div>
        <h4 class=\"font-display font-bold text-lg mt-3\">Integrasi</h4>
        <p class=\"text-xs mt-2\" style=\"color:var(--txt-1)\">SEMENDO penuh & koneksi pasar induk + BI real-time.</p>
      </div>
      <div class=\"glass grain glow-card lift p-5\">
        <div class=\"chip gd\">FASE IV · 15–18</div>
        <h4 class=\"font-display font-bold text-lg mt-3\">Evaluasi</h4>
        <p class=\"text-xs mt-2\" style=\"color:var(--txt-1)\">Monitoring output ekonomi & penyesuaian model berbasis BPS Sumsel.</p>
      </div>
    </div>
  </div>
</section>

</main>

<!-- FOOTER -->
<footer class=\"border-t mt-10\" style=\"border-color:var(--line)\">
  <div class=\"max-w-[1320px] mx-auto px-5 md:px-10 py-10 grid md:grid-cols-3 gap-6 items-end\">
    <div>
      <div class=\"font-display text-2xl font-bold\">SEMENDO</div>
      <p class=\"text-sm mt-2\" style=\"color:var(--txt-2)\">Sriwijaya Economic Forum · Bank Indonesia · 2026</p>
    </div>
    <div class=\"text-sm\" style=\"color:var(--txt-1)\">
      <div>Sofia Ghina Syahira · Mgs. M. Fatih Abdurrahman</div>
      <div class=\"text-xs mt-1\" style=\"color:var(--txt-2)\">UIN Raden Fatah Palembang · Pembimbing: Kusumasari Kartika Hima Darmayanti, M.Si.</div>
    </div>
    <div class=\"md:text-right text-xs\" style=\"color:var(--txt-2)\">
      © 2026 · Crafted for Inflation Stability of Volatile Food
    </div>
  </div>
</footer>

<script>
/* ============ STATE ============ */
const STATE = {
  farmers: 1247, records: 3942, villages: 312, accuracy: 98.3,
};

/* ============ LOADER ============ */
gsap.to('#loaderBar', { width:'100%', duration:1.6, ease:'power2.inOut',
  onComplete:()=>{
    gsap.to('#loader',{opacity:0,duration:.45,onComplete:()=>{
      document.getElementById('loader').style.display='none';
      runIntro();
    }});
  }});

/* ============ CUSTOM CURSOR ============ */
const ring = document.getElementById('cursorRing');
const dot = document.getElementById('cursorDot');
let mx=window.innerWidth/2, my=window.innerHeight/2, rx=mx, ry=my;
window.addEventListener('mousemove', e=>{
  mx=e.clientX; my=e.clientY;
  dot.style.transform=`translate(${mx}px,${my}px) translate(-50%,-50%)`;
});
function loopCursor(){
  rx += (mx-rx)*0.18; ry += (my-ry)*0.18;
  ring.style.transform=`translate(${rx}px,${ry}px) translate(-50%,-50%)`;
  requestAnimationFrame(loopCursor);
}
loopCursor();
document.querySelectorAll('a,button,.tab-pill,.glow-card').forEach(el=>{
  el.addEventListener('mouseenter',()=>ring.classList.add('hover'));
  el.addEventListener('mouseleave',()=>ring.classList.remove('hover'));
});

/* Glow follow on cards */
document.querySelectorAll('.glow-card').forEach(card=>{
  card.addEventListener('mousemove', e=>{
    const r=card.getBoundingClientRect();
    card.style.setProperty('--mx',(e.clientX-r.left)+'px');
    card.style.setProperty('--my',(e.clientY-r.top)+'px');
  });
});

/* Magnetic buttons */
document.querySelectorAll('.magnetic').forEach(el=>{
  el.addEventListener('mousemove', e=>{
    const r=el.getBoundingClientRect();
    const x=e.clientX-(r.left+r.width/2);
    const y=e.clientY-(r.top+r.height/2);
    gsap.to(el,{x:x*0.25,y:y*0.35,duration:.35,ease:'power3.out'});
  });
  el.addEventListener('mouseleave', ()=>gsap.to(el,{x:0,y:0,duration:.5,ease:'elastic.out(1,0.4)'}));
});

/* Ripple */
document.querySelectorAll('.btn').forEach(btn=>{
  btn.addEventListener('click', e=>{
    const r=btn.getBoundingClientRect();
    const c=document.createElement('span'); c.className='ripple';
    c.style.left=(e.clientX-r.left)+'px'; c.style.top=(e.clientY-r.top)+'px';
    c.style.width=c.style.height=Math.max(r.width,r.height)*2+'px';
    btn.appendChild(c);
    gsap.to(c,{scale:1,opacity:0,duration:.7,ease:'power2.out',onComplete:()=>c.remove()});
  });
});

/* ============ NAVBAR scroll ============ */
const navbar=document.getElementById('navbar');
window.addEventListener('scroll', ()=>{
  if(window.scrollY>60) navbar.classList.add('scrolled'); else navbar.classList.remove('scrolled');
});

/* ============ CLOCK ============ */
function tickClock(){
  const d=new Date();
  const t=`${String(d.getHours()).padStart(2,'0')}:${String(d.getMinutes()).padStart(2,'0')}:${String(d.getSeconds()).padStart(2,'0')}`;
  const n=document.getElementById('navTime'); if(n) n.textContent=t;
}
setInterval(tickClock,1000); tickClock();

/* ============ TICKER ============ */
const tickerItems=[
  '⟁ Pak Suparman · 23kg Kopi Semendo → KSP Maju Bersama · Rp 1.426.000',
  '⟁ Ibu Sari · 80kg Beras IR64 → Pasar Induk Palembang · +Rp 1.000.000',
  '↗ Sinkron Muba 78% via Starlink desa · 14 record antri',
  '⚠ BMKG: Hujan lebat Muba · PALI · OKU Timur · 3–5 Jun',
  '🌶️ Cabai Merah: prediksi naik 18% dalam 7 hari',
  '◆ BI menerima 3.942 record hari ini · akurasi 98.3%',
  '✓ Antraknosa terdeteksi · Pak Ahmad · Semendo Darat Ulu · 94%',
  '☕ Kopi Semendo grade A · optimal panen Kamis–Jumat',
];
const tickerEl=document.getElementById('liveTicker');
const tickHTML=tickerItems.map(t=>`<span style=\"color:var(--txt-1)\">${t}</span>`).join('');
tickerEl.innerHTML=tickHTML+tickHTML;

/* ============ INTRO ANIM ============ */
function runIntro(){
  gsap.to('.reveal',{opacity:1,y:0,duration:1,stagger:0.06,ease:'power3.out'});
  // counters
  gsap.to(STATE,{accuracy:98.3,duration:1.8,ease:'power2.out',
    onUpdate:()=>document.getElementById('accNum').textContent=STATE.accuracy.toFixed(1)});
  countTo('kpiFarmers',1247,1.8);
  countTo('kpiRecords',3942,1.8);
  countTo('kpiVillages',312,1.8);
  countTo('bigFarmers',1247,1.6);
  countTo('bigRecords',3942,1.6);
  countTo('bigBlank',438,1.6);
  drawChart();
  buildActivity();
  buildKabList();
}
function countTo(id,val,dur){
  const o={v:0};
  gsap.to(o,{v:val,duration:dur,ease:'power3.out',
    onUpdate:()=>{ const el=document.getElementById(id); if(el) el.textContent=Math.round(o.v).toLocaleString('id-ID'); }});
}

/* ============ ACTIVITY LIST ============ */
function buildActivity(){
  const items=[
    { ic:'🌐', t:'Data terkirim — Banyuasin', s:'78% sinkronisasi via Starlink desa', loc:'Kec. Betung · -2.85°S 104.17°E', time:'08:19:54' },
    { ic:'☕', t:'Pak Suparman — Muara Enim', s:'23 kg Kopi Semendo tersinkron → BI', loc:'Ds. Semendo Darat Ulu', time:'08:19:54' },
    { ic:'🌶️', t:'Ibu Dewi — OKU Selatan', s:'Antraknosa terdeteksi · rekomendasi otomatis', loc:'Ds. Sumber Karya', time:'08:18:21' },
    { ic:'🌾', t:'Pak Heri — Banyuasin', s:'80 kg Beras IR64 dijual via koperasi', loc:'Pasar Induk Palembang', time:'08:17:09' },
  ];
  document.getElementById('activityList').innerHTML = items.map(i=>`
    <div class=\"glass dim p-3 flex items-start gap-3 lift\">
      <div class=\"text-xl\">${i.ic}</div>
      <div class=\"flex-1\">
        <div class=\"text-sm font-semibold\">${i.t}</div>
        <div class=\"text-xs\" style=\"color:var(--txt-1)\">${i.s}</div>
        <div class=\"text-[11px] mt-1\" style=\"color:var(--txt-2)\">${i.loc}</div>
      </div>
      <div class=\"font-mono text-xs\" style=\"color:var(--emerald)\">${i.time}</div>
    </div>`).join('');
}
function buildKabList(){
  const list=[
    ['Palembang',100],['Banyuasin',78],['Muara Enim',92],['OKU Timur',61],
    ['Muba',23],['PALI',18],['Lahat',87],['Prabumulih',95]
  ];
  document.getElementById('kabList').innerHTML=list.map(([n,v])=>`
    <div>
      <div class=\"flex justify-between text-sm\"><span>${n}</span><b class=\"font-mono\" style=\"color:${v>=80?'var(--emerald)':v>=50?'var(--gold)':'var(--danger)'}\">${v}%</b></div>
      <div class=\"progress mt-1\"><i style=\"width:${v}%; background:${v>=80?'linear-gradient(90deg,var(--emerald),#7af0c0)':v>=50?'linear-gradient(90deg,var(--gold),var(--emerald))':'linear-gradient(90deg,#ff5577,var(--gold))'}\"></i></div>
    </div>`).join('');
}

/* ============ PRICE CHART ============ */
function drawChart(){
  const data=[23.1,22.6,23.9,24.4,25.2,26.1,27.0,28.0,29.3,30.4,31.5,32.4,33.1,33.9];
  const w=800,h=280,pad=20;
  const max=Math.max(...data)*1.04, min=Math.min(...data)*0.94;
  const pts=data.map((v,i)=>{
    const x=pad+(i/(data.length-1))*(w-pad*2);
    const y=h-pad-((v-min)/(max-min))*(h-pad*2);
    return [x,y];
  });
  // smooth bezier
  const path=pts.reduce((acc,p,i,arr)=>{
    if(i===0) return `M ${p[0]} ${p[1]}`;
    const prev=arr[i-1];
    const cx=(prev[0]+p[0])/2;
    return acc+` C ${cx} ${prev[1]}, ${cx} ${p[1]}, ${p[0]} ${p[1]}`;
  },'');
  const area=path+` L ${pts[pts.length-1][0]} ${h-pad} L ${pts[0][0]} ${h-pad} Z`;
  document.getElementById('linePath').setAttribute('d',path);
  document.getElementById('areaPath').setAttribute('d',area);
  // points
  const ptsG=document.getElementById('chartPoints');
  ptsG.innerHTML='';
  pts.forEach((p,i)=>{
    const c=document.createElementNS('http://www.w3.org/2000/svg','circle');
    c.setAttribute('cx',p[0]); c.setAttribute('cy',p[1]);
    c.setAttribute('r',i===pts.length-1?6:3);
    c.setAttribute('fill',i===pts.length-1?'#f4c95d':'#19f5a3');
    c.setAttribute('opacity','0');
    ptsG.appendChild(c);
    gsap.to(c,{attr:{opacity:1},duration:.4,delay:0.2+i*0.08,ease:'power2.out'});
  });
}

/* ============ TABS ============ */
const tabs=document.querySelectorAll('.tab-pill');
tabs.forEach(t=>{
  t.addEventListener('click', ()=>{
    tabs.forEach(x=>x.classList.remove('active'));
    t.classList.add('active');
    const id=t.dataset.tab;
    document.querySelectorAll('.tab-section').forEach(s=>s.classList.remove('active'));
    const sec=document.querySelector(`[data-section=\"${id}\"]`);
    sec.classList.add('active');
    // stagger reveal
    const els=sec.querySelectorAll('.b-1,.b-2,.b-3,.b-4,.reveal');
    gsap.fromTo(els,{opacity:0,y:24,scale:.98},{opacity:1,y:0,scale:1,duration:.7,stagger:0.06,ease:'power3.out'});
    window.scrollTo({top: 380, behavior:'smooth'});
    // Reinit canvases on demand
    if(id==='hama') initScanner();
    if(id==='petani') initPhoneTilt();
  });
});

/* ============ THREE.JS MAP ============ */
let mapRenderer, mapScene, mapCamera, mapAnimating=true;
function initMap(){
  const canvas=document.getElementById('mapCanvas');
  if(!canvas) return;
  const w=canvas.clientWidth, h=canvas.clientHeight||520;
  mapRenderer=new THREE.WebGLRenderer({canvas,antialias:true,alpha:true});
  mapRenderer.setPixelRatio(Math.min(window.devicePixelRatio,2));
  mapRenderer.setSize(w,h,false);
  mapScene=new THREE.Scene();
  mapCamera=new THREE.PerspectiveCamera(45,w/h,0.1,500);
  mapCamera.position.set(0,55,80);
  mapCamera.lookAt(0,0,0);

  // Particle topography grid
  const sizeX=80, sizeZ=80, segs=72;
  const geo=new THREE.PlaneGeometry(sizeX,sizeZ,segs,segs);
  geo.rotateX(-Math.PI/2);
  const positions=geo.attributes.position;
  // generate pseudo topography heights
  function noise(x,z){
    return Math.sin(x*0.12)*Math.cos(z*0.1)*4
         + Math.sin(x*0.05+z*0.07)*3
         + Math.cos(z*0.2)*1.5;
  }
  for(let i=0;i<positions.count;i++){
    const x=positions.getX(i), z=positions.getZ(i);
    positions.setY(i, noise(x,z));
  }
  geo.computeVertexNormals();

  // wireframe-like material via points
  const ptsGeo=new THREE.BufferGeometry();
  ptsGeo.setAttribute('position', positions);
  const colors=[];
  for(let i=0;i<positions.count;i++){
    const y=positions.getY(i);
    const t=(y+5)/10;
    colors.push(0.1, 0.6+t*0.4, 0.4+t*0.2);
  }
  ptsGeo.setAttribute('color', new THREE.Float32BufferAttribute(colors,3));
  const ptsMat=new THREE.PointsMaterial({size:0.35, vertexColors:true, transparent:true, opacity:0.85});
  const pts=new THREE.Points(ptsGeo, ptsMat);
  mapScene.add(pts);

  // Subtle ground plane outline grid
  const gridHelper=new THREE.GridHelper(80, 24, 0x0bbd7c, 0x0a2a1c);
  gridHelper.position.y=-5; gridHelper.material.opacity=0.18; gridHelper.material.transparent=true;
  mapScene.add(gridHelper);

  // Kabupaten orbs (approx relative positions on Sumsel)
  const kab=[
    {n:'Palembang',x:8,z:-12,s:1.3,c:0x19f5a3,v:100},
    {n:'Banyuasin',x:-2,z:-18,s:1.1,c:0xf4c95d,v:78},
    {n:'Muba',x:-12,z:-24,s:1.1,c:0xff5577,v:23},
    {n:'PALI',x:-10,z:-2,s:0.9,c:0xff5577,v:18},
    {n:'Muara Enim',x:0,z:8,s:1.0,c:0x19f5a3,v:92},
    {n:'OKU Selatan',x:14,z:18,s:0.9,c:0x19f5a3,v:88},
    {n:'OKU Timur',x:22,z:6,s:0.95,c:0xf4c95d,v:61},
    {n:'Lahat',x:-14,z:10,s:1.0,c:0x19f5a3,v:87},
    {n:'Prabumulih',x:6,z:0,s:0.85,c:0x19f5a3,v:95},
  ];
  const orbs=[];
  kab.forEach(k=>{
    const oGeo=new THREE.SphereGeometry(0.7*k.s, 24,24);
    const oMat=new THREE.MeshBasicMaterial({color:k.c, transparent:true, opacity:0.95});
    const o=new THREE.Mesh(oGeo,oMat);
    o.position.set(k.x, noise(k.x,k.z)+2.6, k.z);
    mapScene.add(o);
    // halo
    const haloGeo=new THREE.SphereGeometry(1.8*k.s, 20,20);
    const haloMat=new THREE.MeshBasicMaterial({color:k.c, transparent:true, opacity:0.12});
    const halo=new THREE.Mesh(haloGeo,haloMat);
    halo.position.copy(o.position);
    mapScene.add(halo);
    // pillar
    const pillarGeo=new THREE.CylinderGeometry(0.05,0.05, o.position.y+5,8);
    const pillarMat=new THREE.MeshBasicMaterial({color:k.c, transparent:true, opacity:0.45});
    const pillar=new THREE.Mesh(pillarGeo,pillarMat);
    pillar.position.set(k.x,(o.position.y+5)/2-5,k.z);
    mapScene.add(pillar);
    orbs.push({mesh:o,halo,baseY:o.position.y,k});
  });

  // Connecting curved laser lines from Palembang hub
  const hub=orbs[0].mesh.position;
  const linesGroup=new THREE.Group();
  orbs.slice(1).forEach((ob,idx)=>{
    const p0=hub.clone();
    const p2=ob.mesh.position.clone();
    const mid=p0.clone().lerp(p2,0.5);
    mid.y+=8 + Math.random()*4;
    const curve=new THREE.QuadraticBezierCurve3(p0, mid, p2);
    const points=curve.getPoints(60);
    const lGeo=new THREE.BufferGeometry().setFromPoints(points);
    const lMat=new THREE.LineBasicMaterial({color:ob.k.c, transparent:true, opacity:0.4});
    const line=new THREE.Line(lGeo,lMat);
    linesGroup.add(line);
    // moving light
    const dotGeo=new THREE.SphereGeometry(0.18,8,8);
    const dotMat=new THREE.MeshBasicMaterial({color:0xffffff});
    const dot=new THREE.Mesh(dotGeo,dotMat);
    dot.userData={curve,t:Math.random(), speed:0.0035+Math.random()*0.004};
    linesGroup.add(dot);
  });
  mapScene.add(linesGroup);

  // Drag rotation
  let dragging=false, lastX=0, lastY=0, rotY=0, rotX=-0.25;
  canvas.addEventListener('mousedown', e=>{ dragging=true; lastX=e.clientX; lastY=e.clientY; });
  window.addEventListener('mouseup', ()=> dragging=false );
  window.addEventListener('mousemove', e=>{
    if(!dragging) return;
    rotY += (e.clientX-lastX)*0.005;
    rotX += (e.clientY-lastY)*0.003;
    rotX = Math.max(-0.9, Math.min(0.2, rotX));
    lastX=e.clientX; lastY=e.clientY;
  });
  canvas.addEventListener('wheel', e=>{
    e.preventDefault();
    mapCamera.position.z = Math.max(40, Math.min(140, mapCamera.position.z + e.deltaY*0.06));
  },{passive:false});

  // Resize
  const onResize=()=>{
    const W=canvas.clientWidth, H=canvas.clientHeight||520;
    mapRenderer.setSize(W,H,false);
    mapCamera.aspect=W/H; mapCamera.updateProjectionMatrix();
  };
  window.addEventListener('resize', onResize);

  let t0=performance.now();
  function loop(){
    if(!mapAnimating) return;
    const t=(performance.now()-t0)*0.001;
    // auto + drag rotation
    mapScene.rotation.y = rotY + t*0.04;
    mapScene.rotation.x = rotX;
    // pulse orbs
    orbs.forEach((o,i)=>{
      const s=1+Math.sin(t*2+i)*0.12;
      o.mesh.scale.setScalar(s);
      o.halo.scale.setScalar(1+Math.sin(t*1.5+i)*0.25);
      o.halo.material.opacity = 0.08 + 0.06*Math.sin(t*2+i);
    });
    // moving lights along curves
    linesGroup.children.forEach(child=>{
      if(child.userData && child.userData.curve){
        child.userData.t += child.userData.speed;
        if(child.userData.t>1) child.userData.t=0;
        const p=child.userData.curve.getPoint(child.userData.t);
        child.position.copy(p);
      }
    });
    mapRenderer.render(mapScene,mapCamera);
    requestAnimationFrame(loop);
  }
  loop();
}
// init map after intro
setTimeout(initMap, 600);

/* ============ THREE.JS SCANNER ============ */
let scInit=false;
function initScanner(){
  if(scInit) return; scInit=true;
  const canvas=document.getElementById('scannerCanvas');
  if(!canvas) return;
  const w=canvas.clientWidth, h=canvas.clientHeight||340;
  const renderer=new THREE.WebGLRenderer({canvas,antialias:true,alpha:true});
  renderer.setPixelRatio(Math.min(window.devicePixelRatio,2));
  renderer.setSize(w,h,false);
  const scene=new THREE.Scene();
  const cam=new THREE.PerspectiveCamera(45,w/h,0.1,200);
  cam.position.set(0,0,8);

  // Leaf hologram (icosahedron wireframe + plane)
  const group=new THREE.Group();
  const geo=new THREE.IcosahedronGeometry(2.2, 1);
  const wMat=new THREE.MeshBasicMaterial({color:0x19f5a3, wireframe:true, transparent:true, opacity:0.55});
  const m=new THREE.Mesh(geo, wMat);
  group.add(m);
  // inner glow sphere
  const sGeo=new THREE.SphereGeometry(1.4,32,32);
  const sMat=new THREE.MeshBasicMaterial({color:0x0bbd7c, transparent:true, opacity:0.18});
  group.add(new THREE.Mesh(sGeo,sMat));

  // rotating frame
  const ring1=new THREE.Mesh(new THREE.TorusGeometry(3,0.025,16,80), new THREE.MeshBasicMaterial({color:0xf4c95d}));
  const ring2=new THREE.Mesh(new THREE.TorusGeometry(2.6,0.02,16,80), new THREE.MeshBasicMaterial({color:0x19f5a3}));
  ring2.rotation.x=Math.PI/2;
  group.add(ring1); group.add(ring2);

  // particles
  const pCount=400;
  const pGeo=new THREE.BufferGeometry();
  const pos=new Float32Array(pCount*3);
  for(let i=0;i<pCount;i++){
    const r=2.2+Math.random()*1.6;
    const th=Math.random()*Math.PI*2;
    const ph=Math.acos(2*Math.random()-1);
    pos[i*3]=r*Math.sin(ph)*Math.cos(th);
    pos[i*3+1]=r*Math.sin(ph)*Math.sin(th);
    pos[i*3+2]=r*Math.cos(ph);
  }
  pGeo.setAttribute('position', new THREE.BufferAttribute(pos,3));
  const pMat=new THREE.PointsMaterial({color:0x19f5a3,size:0.04,transparent:true,opacity:0.8});
  group.add(new THREE.Points(pGeo,pMat));

  scene.add(group);

  const onResize=()=>{
    const W=canvas.clientWidth, H=canvas.clientHeight||340;
    renderer.setSize(W,H,false);
    cam.aspect=W/H; cam.updateProjectionMatrix();
  };
  window.addEventListener('resize', onResize);

  function loop(){
    group.rotation.y += 0.012;
    group.rotation.x = Math.sin(performance.now()*0.0008)*0.4;
    ring1.rotation.z += 0.02;
    ring2.rotation.z -= 0.014;
    renderer.render(scene,cam);
    requestAnimationFrame(loop);
  }
  loop();
}

/* ============ PHONE TILT ============ */
let phoneInit=false;
function initPhoneTilt(){
  if(phoneInit) return; phoneInit=true;
  const wrap=document.getElementById('phoneWrap');
  const phone=document.getElementById('phone3D');
  if(!wrap||!phone) return;
  // floating
  gsap.to(phone,{y:-12,duration:2.4,yoyo:true,repeat:-1,ease:'sine.inOut'});
  wrap.addEventListener('mousemove', e=>{
    const r=wrap.getBoundingClientRect();
    const px=(e.clientX-r.left)/r.width - 0.5;
    const py=(e.clientY-r.top)/r.height - 0.5;
    gsap.to(phone,{rotationY:px*22, rotationX:-py*18, duration:.5, ease:'power3.out', transformPerspective:1200});
  });
  wrap.addEventListener('mouseleave', ()=>{
    gsap.to(phone,{rotationY:0,rotationX:0,duration:.8,ease:'elastic.out(1,0.4)'});
  });
}

/* Init phone on first load too (since petani tab may not be open) */
setTimeout(initPhoneTilt, 1200);

</script>
</body>
</html>
"
Observation: Create successful: /app/semendo_dashboard.html
