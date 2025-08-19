<!DOCTYPE html><html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Top Up Free Fire 🇮🇩 — Luar Angkasa</title>
  <meta name="description" content="Website top up Free Fire dengan tema luar angkasa. Pilih paket diamond, metode pembayaran DANA / QRIS, dan konfirmasi via WhatsApp."/>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@300;400;600;800&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#050714;         /* deep space */
      --card:#0b0f24cc;     /* translucent card */
      --accent:#7c5cff;     /* neon purple */
      --accent-2:#00e5ff;   /* neon cyan */
      --text:#e8ecff;       /* near-white */
      --muted:#aab2d5;      /* muted text */
      --success:#2de39c;
      --danger:#ff5d7a;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0; font-family:'Outfit',system-ui,-apple-system,Segoe UI,Roboto,Helvetica,Arial,sans-serif; color:var(--text);
      background: radial-gradient(1200px 800px at 80% -10%, #1a1f46 0%, transparent 60%),
                  radial-gradient(800px 600px at -20% 110%, #07122b 0%, transparent 60%),
                  linear-gradient(180deg, #050814 0%, #04060f 100%);
      overflow-x:hidden;
    }/* Starfield */
.stars, .stars2, .stars3{ position:fixed; top:0; left:0; width:100%; height:100%; display:block; z-index:-3; }
.stars{ background:transparent url('data:image/svg+xml;utf8,\
  <svg xmlns="http://www.w3.org/2000/svg" width="3" height="3"><circle cx="1.5" cy="1.5" r="1.5" fill="white" opacity="0.6"/></svg>') repeat; animation: drift 300s linear infinite; background-size:3px 3px; opacity:.5 }
.stars2{ background:transparent url('data:image/svg+xml;utf8,\
  <svg xmlns="http://www.w3.org/2000/svg" width="2" height="2"><circle cx="1" cy="1" r="1" fill="white" opacity="0.8"/></svg>') repeat; animation: drift 180s linear infinite reverse; background-size:2px 2px; opacity:.4 }
.stars3{ background:transparent url('data:image/svg+xml;utf8,\
  <svg xmlns="http://www.w3.org/2000/svg" width="1" height="1"><circle cx="0.5" cy="0.5" r="0.5" fill="white" opacity="1"/></svg>') repeat; animation: drift 120s linear infinite; background-size:1px 1px; opacity:.3 }
@keyframes drift { from{ background-position:0 0 } to{ background-position: -2000px 2000px } }

.container{ max-width:980px; margin:0 auto; padding:32px 20px 64px; }
header{ display:flex; align-items:center; justify-content:center; gap:12px; margin:24px 0 18px }
.logo{ width:44px; height:44px; display:grid; place-items:center; border-radius:12px; background:conic-gradient(from 200deg, var(--accent), var(--accent-2)); box-shadow:0 0 20px #7c5cff55, 0 0 40px #00e5ff33 }
.title{ font-size:clamp(22px, 4vw, 36px); font-weight:800; letter-spacing:.3px; text-align:center }
.subtitle{ text-align:center; color:var(--muted); margin-top:-2px }

.grid{ display:grid; grid-template-columns:1fr; gap:16px; margin-top:28px }
@media(min-width:880px){ .grid{ grid-template-columns:1.1fr .9fr } }

.card{ background:var(--card); border:1px solid #1c244a; box-shadow:0 10px 30px #00000055, inset 0 1px 0 #2a3976; border-radius:20px; padding:18px }
.card h2{ margin:4px 0 14px; font-size:18px; font-weight:700 }

label{ display:block; font-size:14px; color:var(--muted); margin:10px 0 6px }
input[type="text"], select{ width:100%; padding:14px 14px; border-radius:14px; background:#0a1130; border:1px solid #24326a; color:var(--text); outline:none; transition:.2s; }
input[type="text"]:focus, select:focus{ border-color:var(--accent); box-shadow:0 0 0 4px #7c5cff30 }

.radio-group{ display:flex; gap:10px; flex-wrap:wrap }
.radio{ position:relative }
.radio input{ position:absolute; inset:0; opacity:0; }
.radio label{
  display:flex; align-items:center; gap:10px; padding:12px 14px; border-radius:14px; border:1px solid #24326a; background:#0a1130; cursor:pointer; user-select:none; transition:.2s;
}
.radio input:checked + label{ border-color:var(--accent-2); box-shadow:0 0 18px #00e5ff33, inset 0 1px 0 #2a3976 }

.packages{ display:grid; grid-template-columns:1fr; gap:10px }
@media(min-width:560px){ .packages{ grid-template-columns:1fr 1fr } }
.pkg{ background:#0a1130; border:1px solid #24326a; border-radius:16px; padding:12px 14px; cursor:pointer; transition:.2s; display:flex; justify-content:space-between; align-items:center }
.pkg:hover{ transform:translateY(-1px); border-color:#2f43a5 }
.pkg input{ display:none }
.pkg.active{ border-color:var(--accent); box-shadow:0 0 18px #7c5cff33, inset 0 1px 0 #2a3976 }
.pkg .left{ display:flex; align-items:center; gap:10px }
.pill{ font-size:11px; padding:4px 8px; border-radius:999px; border:1px solid #2f43a5; color:#c8d1ff }

.cta{
  margin-top:18px; width:100%; padding:14px 18px; border-radius:16px; background:linear-gradient(90deg, var(--accent), var(--accent-2));
  color:#041028; font-weight:800; border:none; cursor:pointer; box-shadow:0 8px 30px #00e5ff44, 0 3px 10px #7c5cff55; transition:transform .08s ease;
}
.cta:active{ transform:translateY(1px) }

.note{ color:var(--muted); font-size:12px; margin-top:8px }

.preview{ font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace; background:#070d26; border:1px dashed #2c3a74; border-radius:16px; padding:14px; font-size:13px; white-space:pre-wrap; min-height:110px }

footer{ text-align:center; color:#8191d6; font-size:12px; margin-top:24px }
.credits a{ color:#9fb4ff; text-decoration:none }

  </style>
</head>
<body>
  <div class="stars"></div>
  <div class="stars2"></div>
  <div class="stars3"></div>  <div class="container">
    <header>
      <div class="logo">🚀</div>
      <div>
        <div class="title">Top Up Free Fire 🇮🇩</div>
        <div class="subtitle">Tema Luar Angkasa — cepat, aman, bintang-bintang jadi saksi ✨</div>
      </div>
    </header><div class="grid">
  <!-- FORM CARD -->
  <section class="card">
    <h2>Formulir</h2>

    <label for="ffid">Masukkan ID Free Fire</label>
    <input id="ffid" type="text" placeholder="Masukkan ID Free Fire Anda" autocomplete="off" />

    <label style="margin-top:14px">Pilih Paket Diamond</label>
    <div id="packages" class="packages"></div>
    <div class="note">Pilihan: Rp 1.000 = 5💎 • Rp 2.000 = 10💎 • Rp 4.000 = 20💎 • Rp 10.000 = 70💎 • Rp 14.000 = 90💎 • Rp 17.500 = 120💎 • Rp 50.000 = 355💎 • Rp 69.000 = 500💎</div>

    <label style="margin-top:14px">Metode Pembayaran</label>
    <div class="radio-group">
      <div class="radio">
        <input type="radio" id="pay-dana" name="payment" value="DANA" checked>
        <label for="pay-dana">💙 DANA</label>
      </div>
      <div class="radio">
        <input type="radio" id="pay-qris" name="payment" value="QRIS Allpay">
        <label for="pay-qris">⚡ QRIS Allpay</label>
      </div>
    </div>

    <button id="confirm" class="cta">Konfirmasi & Kirim WhatsApp</button>
    <div class="note">Dengan klik konfirmasi, Anda akan diarahkan ke WhatsApp admin untuk menyelesaikan pembayaran.</div>
  </section>

  <!-- PREVIEW CARD -->
  <section class="card">
    <h2>Pratinjau Pesan WhatsApp</h2>
    <div id="preview" class="preview">Isikan ID, pilih paket & metode pembayaran untuk melihat pratinjau pesan.</div>
    <footer class="credits" style="margin-top:10px">ID tujuan WhatsApp: <strong>085189283822</strong> (otomatis terkonversi ke format internasional).</footer>
  </section>
</div>

<footer style="margin-top:34px">© <span id="year"></span> Top Up FF • Galaksi Diskon • Made with ❤️ in Space</footer>

  </div>  <script>
    // Data paket
    const PACKS = [
      { price: 1000, diamonds: 5 },
      { price: 2000, diamonds: 10 },
      { price: 4000, diamonds: 20 },
      { price: 10000, diamonds: 70 },
      { price: 14000, diamonds: 90 },
      { price: 17500, diamonds: 120 },
      { price: 50000, diamonds: 355 },
      { price: 69000, diamonds: 500 },
    ];

    const phoneLocal = '085189283822';
    const phoneIntl = phoneLocal.replace(/^0/, '62'); // 62 untuk Indonesia

    // Utils
    const rupiah = (n) => new Intl.NumberFormat('id-ID', { style: 'currency', currency: 'IDR', maximumFractionDigits: 0 }).format(n);

    const packagesEl = document.getElementById('packages');
    const previewEl = document.getElementById('preview');
    const ffidEl = document.getElementById('ffid');

    let selectedIndex = null;

    function renderPackages(){
      packagesEl.innerHTML = '';
      PACKS.forEach((p, i) => {
        const wrapper = document.createElement('div');
        wrapper.className = 'pkg';
        wrapper.role = 'button';
        wrapper.tabIndex = 0;
        wrapper.dataset.index = i;
        wrapper.innerHTML = `
          <div class="left"><span>💎 ${p.diamonds}</span><span class="pill">${rupiah(p.price)}</span></div>
          <div class="right">${i === selectedIndex ? '✅' : '🛒'}</div>
        `;
        wrapper.addEventListener('click', () => selectPackage(i));
        wrapper.addEventListener('keydown', (e) => { if(e.key==='Enter' || e.key===' '){ e.preventDefault(); selectPackage(i);} });
        packagesEl.appendChild(wrapper);
      });
      highlightSelected();
      updatePreview();
    }

    function selectPackage(i){
      selectedIndex = i;
      highlightSelected();
      updatePreview();
    }

    function highlightSelected(){
      Array.from(packagesEl.children).forEach((el, idx) => {
        el.classList.toggle('active', idx === selectedIndex);
        const right = el.querySelector('.right');
        if(right) right.textContent = idx === selectedIndex ? '✅' : '🛒';
      });
    }

    function getPayment(){
      const el = document.querySelector('input[name="payment"]:checked');
      return el ? el.value : '';
    }

    function buildMessage(){
      const id = ffidEl.value.trim();
      const pack = selectedIndex != null ? PACKS[selectedIndex] : null;
      const pay = getPayment();
      const lines = [
        'Top Up Free Fire 🇮🇩',
        '========================',
        `ID: ${id || '(belum diisi)'}`,
        `Paket: ${pack ? pack.diamonds + '💎 (' + rupiah(pack.price) + ')' : '(belum dipilih)'} ,`,
        `Metode Pembayaran: ${pay || '(belum dipilih)'}`,
        '',
        'Mohon diproses ya kak 🙏'
      ];
      return lines.join('\n');
    }

    function updatePreview(){
      previewEl.textContent = buildMessage();
    }

    ffidEl.addEventListener('input', updatePreview);
    document.querySelectorAll('input[name="payment"]').forEach(r => r.addEventListener('change', updatePreview));

    // Confirm -> WhatsApp
    document.getElementById('confirm').addEventListener('click', () => {
      const id = ffidEl.value.trim();
      if(!id){
        alert('Harap isi ID Free Fire terlebih dahulu.');
        ffidEl.focus();
        return;
      }
      if(selectedIndex === null){
        alert('Harap pilih paket diamond.');
        return;
      }
      const text = buildMessage();
      const url = `https://wa.me/${phoneIntl}?text=${encodeURIComponent(text)}`;
      window.location.href = url;
    });

    // Init
    renderPackages();
    document.getElementById('year').textContent = new Date().getFullYear();
  </script></body>
</html>
