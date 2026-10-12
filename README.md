<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="theme-color" content="#167447">
<meta name="description" content="SehatHarian: panduan kebugaran, pola makan, tidur, dan kebiasaan sehat yang disesuaikan dengan kelompok usia.">
<title>SehatHarian | Mulai dari Kebiasaan Kecil</title>
<style>
:root{--green:#167447;--green2:#23965d;--mint:#eaf7ef;--pale:#f5fbf6;--ink:#183b2c;--muted:#61776b;--line:#d9eadf;--white:#fff;--shadow:0 12px 32px rgba(22,116,71,.09);--radius:20px}
*{box-sizing:border-box}html{scroll-behavior:smooth}body{margin:0;background:#f7fbf8;color:var(--ink);font:16px/1.6 system-ui,-apple-system,BlinkMacSystemFont,"Segoe UI",sans-serif}a{color:inherit}button,select,input{font:inherit}button{cursor:pointer}.container{width:min(1120px,92%);margin:auto}
header{position:sticky;top:0;z-index:10;background:rgba(255,255,255,.94);backdrop-filter:blur(12px);border-bottom:1px solid var(--line)}
.nav{min-height:72px;display:flex;align-items:center;justify-content:space-between;gap:20px}.brand{display:flex;align-items:center;gap:10px;font-size:1.3rem;font-weight:850;color:var(--green);text-decoration:none}.brand-mark{width:38px;height:38px;border-radius:14px;background:var(--mint);display:grid;place-items:center;font-size:1.35rem}.navlinks{display:flex;align-items:center;gap:22px}.navlinks a{text-decoration:none;color:#3e5d4b;font-size:.93rem;font-weight:650}.navlinks a:hover{color:var(--green)}.menu-btn{display:none;border:1px solid var(--line);background:white;border-radius:10px;padding:8px 12px;color:var(--green)}
.btn{display:inline-flex;justify-content:center;align-items:center;gap:8px;padding:12px 18px;border:0;border-radius:999px;background:var(--green);color:white;font-weight:750;text-decoration:none;box-shadow:0 5px 14px #16744722;transition:.2s}.btn:hover{background:#105c38;transform:translateY(-1px)}.btn.secondary{background:#e7f5eb;color:var(--green);box-shadow:none}.btn.small{padding:8px 13px;font-size:.9rem}
.hero{padding:46px 0 28px}.hero-panel{display:grid;grid-template-columns:1.05fr .95fr;align-items:center;overflow:hidden;background:linear-gradient(120deg,#e9f8ed,#d8f0df);border-radius:28px;box-shadow:var(--shadow);min-height:360px}.hero-copy{padding:clamp(28px,5vw,58px)}.eyebrow{display:inline-flex;gap:7px;align-items:center;background:#fff9;color:var(--green);border:1px solid #cde7d5;padding:6px 12px;border-radius:999px;font-size:.85rem;font-weight:750}.hero h1{font-size:clamp(2.2rem,4vw,3.7rem);line-height:1.08;letter-spacing:-.04em;margin:18px 0}.hero h1 span{color:var(--green)}.hero p{color:#456654;max-width:510px}.hero-art{height:100%;min-height:300px;display:grid;place-items:center;position:relative;background:radial-gradient(ellipse at 55% 48%,#fff 0,#e2f4e6 46%,#c8e8d0 100%)}.sun{position:absolute;width:180px;height:180px;border-radius:50%;background:#f5d98a;right:13%;top:12%;opacity:.8}.hill{position:absolute;bottom:-50px;width:120%;height:190px;border-radius:50% 50% 0 0;background:#9ed5a9;transform:rotate(-8deg)}.hill.h2{bottom:-90px;background:#4b9d6b;transform:rotate(8deg)}.person{position:relative;z-index:2;font-size:clamp(6rem,12vw,10rem);filter:drop-shadow(0 10px 6px #215f3922);transform:translateY(-10px)}.leaf{position:absolute;z-index:3;font-size:2.4rem}.leaf.l1{left:14%;top:24%}.leaf.l2{right:14%;bottom:22%}
.section{padding:32px 0}.section-head{display:flex;align-items:end;justify-content:space-between;gap:16px;margin-bottom:20px}.section h2{font-size:clamp(1.55rem,3vw,2rem);letter-spacing:-.025em;margin:0 0 5px}.section-head p,.sub{margin:0;color:var(--muted)}.grid{display:grid;gap:18px}.grid.four{grid-template-columns:repeat(4,1fr)}.grid.three{grid-template-columns:repeat(3,1fr)}.grid.two{grid-template-columns:repeat(2,1fr)}
.card{background:white;border:1px solid var(--line);border-radius:var(--radius);padding:22px;box-shadow:var(--shadow)}.card h3{margin:10px 0 5px;font-size:1.08rem}.card p{color:var(--muted);margin:0}.icon{width:48px;height:48px;display:grid;place-items:center;border-radius:16px;background:var(--mint);font-size:1.45rem}.age-card{cursor:pointer;transition:.2s;border:2px solid transparent}.age-card:hover,.age-card.active{border-color:#54ae76;transform:translateY(-2px)}.age-card.active{background:#f1fbf3}.age-range{display:inline-block;margin-top:12px;color:var(--green);font-weight:750;font-size:.85rem}
.toolbar{display:flex;flex-wrap:wrap;gap:10px;align-items:center}.pill{border:1px solid var(--line);background:white;color:var(--muted);padding:9px 14px;border-radius:999px;font-weight:700}.pill.active{background:var(--green);color:white;border-color:var(--green)}
.workout-card{padding:0;overflow:hidden}.workout-art{height:130px;display:grid;place-items:center;background:linear-gradient(135deg,#d8f2df,#edf9ef);font-size:3.5rem}.workout-body{padding:18px}.meta{font-size:.85rem;color:var(--green);font-weight:750}.workout-body p{margin:8px 0 15px}
.meal-card{overflow:hidden;padding:0}.meal-art{height:100px;display:grid;place-items:center;font-size:3.4rem;background:#fff3d9}.meal-body{padding:17px}.meal-body p{margin:4px 0 14px}
.sleep-row{display:flex;gap:14px;align-items:flex-start;padding:14px 0;border-bottom:1px solid var(--line)}.sleep-row:last-child{border-bottom:0}.check{accent-color:var(--green);width:19px;height:19px;margin-top:3px}
.tracker-layout{display:grid;grid-template-columns:1.15fr .85fr;gap:18px}.habit-list{display:grid;gap:10px;margin-top:16px}.habit{display:flex;align-items:center;gap:12px;background:#f8fcf9;border:1px solid var(--line);border-radius:13px;padding:12px}.habit label{flex:1;cursor:pointer}.habit small{display:block;color:var(--muted)}.progress-ring{width:140px;height:140px;border-radius:50%;display:grid;place-items:center;margin:15px auto;background:conic-gradient(var(--green) var(--progress,0%),#e4f0e7 0)}.progress-ring-inner{width:108px;height:108px;background:white;border-radius:50%;display:grid;place-items:center;text-align:center}.progress-ring strong{font-size:1.6rem;display:block}.water-controls{display:flex;gap:8px;align-items:center;margin-top:12px}.water-count{font-weight:800;color:var(--green)}
.notice{background:#fff9e9;border:1px solid #f1dfac;border-radius:14px;padding:15px 17px;color:#6b5722;font-size:.92rem}.tip-card{background:linear-gradient(130deg,#eaf8ed,#fff);border:1px solid var(--line);border-radius:var(--radius);padding:24px}.tip-card p{color:#506c5b}.tag{display:inline-block;background:#e6f5eb;color:var(--green);border-radius:8px;padding:4px 8px;font-size:.78rem;font-weight:750}
footer{margin-top:35px;background:#e4f3e8;padding:30px 0;color:#456654}.footer-row{display:flex;justify-content:space-between;gap:20px;flex-wrap:wrap}.footer-row p{margin:6px 0}.tiny{font-size:.82rem;color:var(--muted)}.hidden{display:none!important}
select{border:1px solid var(--line);border-radius:12px;background:white;padding:10px 12px;color:var(--ink);max-width:100%}
:focus-visible{outline:3px solid #f0bc4e;outline-offset:3px}
@media(max-width:850px){.navlinks{display:none;position:absolute;top:71px;left:0;right:0;padding:18px 4%;background:white;border-bottom:1px solid var(--line);flex-direction:column;align-items:flex-start}.navlinks.open{display:flex}.menu-btn{display:block}.nav>.btn{display:none}.hero-panel{grid-template-columns:1fr}.hero-art{min-height:240px}.grid.four{grid-template-columns:repeat(2,1fr)}.grid.three{grid-template-columns:repeat(2,1fr)}.tracker-layout{grid-template-columns:1fr}}
@media(max-width:540px){.grid.four,.grid.three,.grid.two{grid-template-columns:1fr}.section{padding:24px 0}.hero{padding-top:22px}.hero-copy{padding:26px}.hero-art{min-height:210px}.section-head{align-items:flex-start;flex-direction:column}.card{padding:18px}.workout-card,.meal-card{padding:0}.workout-body,.meal-body{padding:16px}.tracker-layout{gap:12px}}
@media(prefers-reduced-motion:reduce){*{scroll-behavior:auto!important;transition:none!important}}
</style>
</head>
<body>
<header>
 <div class="container nav">
  <a class="brand" href="#beranda" aria-label="SehatHarian beranda"><span class="brand-mark">🌿</span>SehatHarian</a>
  <nav class="navlinks" id="navlinks" aria-label="Navigasi utama">
   <a href="#beranda">Beranda</a><a href="#workout">Workout</a><a href="#makan">Pola Makan</a><a href="#tidur">Pola Tidur</a><a href="#kesehatan">Kesehatan</a><a href="#tracker">Tracker</a>
  </nav>
  <button class="menu-btn" id="menuBtn" aria-expanded="false" aria-controls="navlinks">☰ Menu</button>
  <a class="btn small" href="#tracker">Mulai Hari Ini ↗</a>
 </div>
</header>
<main>
<section class="hero" id="beranda"><div class="container hero-panel">
 <div class="hero-copy">
  <span class="eyebrow">🌱 Kebiasaan kecil, dampak berarti</span>
  <h1>Hidup sehat dimulai dari <span>langkah kecil.</span></h1>
  <p>Panduan praktis untuk bergerak, makan seimbang, tidur cukup, dan merawat diri. Pilih kebiasaan yang sesuai usia dan kemampuanmu.</p>
  <a class="btn" href="#usia">Temukan panduanmu <span aria-hidden="true">→</span></a>
  <p class="tiny" style="margin-top:14px">Tidak perlu sempurna. Konsisten dan aman lebih penting.</p>
 </div>
 <div class="hero-art" aria-label="Ilustrasi alam yang menenangkan"><div class="sun"></div><span class="leaf l1">🌿</span><span class="person">🧘</span><span class="leaf l2">🍃</span><div class="hill"></div><div class="hill h2"></div></div>
</div></section>

<section class="section" id="usia"><div class="container">
 <div class="section-head"><div><h2>Panduan sesuai usia</h2><p>Kebutuhan setiap tahap hidup berbeda. Pilih kelompok usia untuk melihat pengingat yang relevan.</p></div><span class="tag" id="ageStatus">Panduan umum</span></div>
 <div class="grid four" id="ageGrid">
  <button class="card age-card" data-age="anak" aria-pressed="false" style="text-align:left"><span class="icon">🧒</span><h3>Anak-anak</h3><p>Aktif bermain, makan beragam, dan tidur teratur.</p><span class="age-range">6–12 tahun</span></button>
  <button class="card age-card" data-age="remaja" aria-pressed="false" style="text-align:left"><span class="icon">🎒</span><h3>Remaja</h3><p>Dukung pertumbuhan, belajar, dan kesehatan mental.</p><span class="age-range">13–18 tahun</span></button>
  <button class="card age-card" data-age="dewasa" aria-pressed="false" style="text-align:left"><span class="icon">🚶</span><h3>Dewasa</h3><p>Seimbangkan aktivitas, kerja, dan pemulihan.</p><span class="age-range">19–59 tahun</span></button>
  <button class="card age-card" data-age="lansia" aria-pressed="false" style="text-align:left"><span class="icon">🌳</span><h3>Lansia</h3><p>Jaga mobilitas, keseimbangan, dan koneksi sosial.</p><span class="age-range">60+ tahun</span></button>
 </div>
 <div class="tip-card" style="margin-top:16px" aria-live="polite"><h3 id="ageTitle">Mulai dari dasar yang bisa dilakukan</h3><p id="ageAdvice">Bergerak sesuai kemampuan, makan beragam, tidur teratur, dan berkonsultasi dengan tenaga kesehatan untuk kebutuhan khusus.</p></div>
</div></section>

<section class="section" id="workout"><div class="container">
 <div class="section-head"><div><h2>Gerak & workout</h2><p>Pilih aktivitas berdasarkan kemampuan. Berhenti jika terasa sakit, pusing, atau sesak tidak biasa.</p></div></div>
 <div class="toolbar" role="group" aria-label="Filter tingkat latihan">
  <button class="pill active" data-level="semua">Semua</button><button class="pill" data-level="pemula">Pemula</button><button class="pill" data-level="ringan">Ringan</button><button class="pill" data-level="fleksibilitas">Peregangan</button>
 </div>
 <div class="grid three" id="workoutGrid" style="margin-top:16px">
  <article class="card workout-card" data-kind="pemula"><div class="workout-art">🚶</div><div class="workout-body"><span class="meta">PEMULA · 10–20 MENIT</span><h3>Jalan santai</h3><p>Mulai dengan kecepatan nyaman, di tempat yang aman dan rata.</p><button class="btn secondary small detail-btn" data-detail="Jalan santai">Lihat panduan</button></div></article>
  <article class="card workout-card" data-kind="ringan"><div class="workout-art">🪑</div><div class="workout-body"><span class="meta">RINGAN · 5–10 MENIT</span><h3>Gerak di kursi</h3><p>Gerakkan bahu, pergelangan kaki, dan kaki sambil duduk stabil.</p><button class="btn secondary small detail-btn" data-detail="Gerak di kursi">Lihat panduan</button></div></article>
  <article class="card workout-card" data-kind="fleksibilitas"><div class="workout-art">🧘</div><div class="workout-body"><span class="meta">PEREGANGAN · 5–10 MENIT</span><h3>Peregangan lembut</h3><p>Lakukan perlahan tanpa memantul atau memaksakan rentang gerak.</p><button class="btn secondary small detail-btn" data-detail="Peregangan lembut">Lihat panduan</button></div></article>
 </div>
 <div id="workoutDetail" class="tip-card hidden" style="margin-top:16px" aria-live="polite"></div>
 <p class="tiny" style="margin-top:12px">Anak dan remaja sebaiknya banyak bergerak lewat aktivitas yang menyenangkan. Orang dewasa umumnya dianjurkan melakukan aktivitas aerobik rutin dan latihan penguatan. Sesuaikan dengan kondisi tubuh dan panduan tenaga kesehatan.</p>
</div></section>

<section class="section" id="makan"><div class="container">
 <div class="section-head"><div><h2>Pola makan seimbang</h2><p>Utamakan variasi dan keteraturan, bukan aturan makan yang ekstrem.</p></div></div>
 <div class="grid three">
  <article class="card meal-card"><div class="meal-art">🍳</div><div class="meal-body"><span class="tag">Ide sarapan</span><h3>Mulai dengan energi</h3><p>Contoh: telur atau tempe, nasi/roti/oat, serta buah.</p></div></article>
  <article class="card meal-card"><div class="meal-art" style="background:#e9f5dd">🥗</div><div class="meal-body"><span class="tag">Ide makan siang</span><h3>Beragam dan seimbang</h3><p>Contoh: sumber karbohidrat, lauk berprotein, sayur, dan air putih.</p></div></article>
  <article class="card meal-card"><div class="meal-art" style="background:#fff0e3">🍲</div><div class="meal-body"><span class="tag">Ide makan malam</span><h3>Makan dengan nyaman</h3><p>Sesuaikan porsi dengan rasa lapar, kebutuhan, budaya, dan ketersediaan makanan.</p></div></article>
 </div>
 <div class="notice" style="margin-top:16px"><strong>Catatan:</strong> kebutuhan gizi berbeda menurut usia, aktivitas, kondisi kesehatan, dan tahap pertumbuhan. Tidak ada satu menu yang cocok untuk semua orang. Untuk alergi, kondisi medis, atau masalah makan, mintalah saran tenaga kesehatan atau ahli gizi.</div>
</div></section>

<section class="section" id="tidur"><div class="container">
 <div class="section-head"><div><h2>Istirahat yang berkualitas</h2><p>Jadwal tidur yang teratur membantu tubuh dan pikiran pulih.</p></div></div>
 <div class="grid two">
  <div class="card"><h3>Durasi tidur yang umumnya dianjurkan</h3>
   <div class="sleep-row"><span class="icon">🧒</span><div><strong>Anak usia sekolah (6–12)</strong><p>9–12 jam per malam</p></div></div>
   <div class="sleep-row"><span class="icon">🎒</span><div><strong>Remaja (13–18)</strong><p>8–10 jam per malam</p></div></div>
   <div class="sleep-row"><span class="icon">🧑</span><div><strong>Dewasa (18–60)</strong><p>Umumnya 7 jam atau lebih</p></div></div>
   <div class="sleep-row"><span class="icon">🌳</span><div><strong>Dewasa lebih tua (61+)</strong><p>Kebutuhan bisa bervariasi; jaga jadwal tidur teratur</p></div></div>
  </div>
  <div class="card"><h3>Rutinitas sebelum tidur</h3>
   <div class="sleep-row"><input class="check" type="checkbox" id="sleep1"><label for="sleep1">Redupkan layar dan lampu menjelang tidur.</label></div>
   <div class="sleep-row"><input class="check" type="checkbox" id="sleep2"><label for="sleep2">Buat kamar nyaman, tenang, dan cukup gelap.</label></div>
   <div class="sleep-row"><input class="check" type="checkbox" id="sleep3"><label for="sleep3">Usahakan jam tidur dan bangun konsisten.</label></div>
   <div class="sleep-row"><input class="check" type="checkbox" id="sleep4"><label for="sleep4">Hindari kafein dekat waktu tidur jika mengganggu.</label></div>
  </div>
 </div>
 <p class="tiny" style="margin-top:12px">Angka ini adalah panduan umum, bukan diagnosis. Jika gangguan tidur berlangsung lama atau mengganggu aktivitas, diskusikan dengan tenaga kesehatan.</p>
</div></section>

<section class="section" id="kesehatan"><div class="container">
 <div class="section-head"><div><h2>Rawat diri setiap hari</h2><p>Hal sederhana yang membantu menjaga kesehatan secara menyeluruh.</p></div></div>
 <div class="grid four">
  <div class="card"><span class="icon">🧼</span><h3>Kebersihan diri</h3><p>Cuci tangan, jaga kebersihan gigi, dan rawat tubuh.</p></div>
  <div class="card"><span class="icon">🧠</span><h3>Kesehatan mental</h3><p>Beristirahat, terhubung dengan orang tepercaya, dan bicarakan beban yang terasa berat.</p></div>
  <div class="card"><span class="icon">🩺</span><h3>Pencegahan</h3><p>Ikuti imunisasi dan pemeriksaan kesehatan sesuai anjuran setempat.</p></div>
  <div class="card"><span class="icon">🌤️</span><h3>Seimbang</h3><p>Ambil jeda dari layar dan luangkan waktu di luar dengan aman.</p></div>
 </div>
</div></section>

<section class="section" id="tracker"><div class="container">
 <div class="section-head"><div><h2>Tracker kebiasaan harian</h2><p>Checklist ini tersimpan di browser perangkat ini. Tidak dikirim ke server.</p></div><button class="btn secondary small" id="resetBtn">Atur ulang hari ini</button></div>
 <div class="tracker-layout">
  <div class="card"><div class="section-head" style="margin-bottom:0"><div><h3>Checklist hari ini</h3><p class="tiny" id="todayLabel"></p></div><span class="tag" id="doneLabel">0 selesai</span></div>
   <div class="habit-list" id="habitList">
    <div class="habit"><input class="check habit-check" type="checkbox" id="h1"><label for="h1"><strong>Bergerak</strong><small>Aktivitas sesuai kemampuan</small></label></div>
    <div class="habit"><input class="check habit-check" type="checkbox" id="h2"><label for="h2"><strong>Makan beragam</strong><small>Usahakan makanan bervariasi</small></label></div>
    <div class="habit"><input class="check habit-check" type="checkbox" id="h3"><label for="h3"><strong>Minum secara teratur</strong><small>Ikuti kebutuhan tubuh dan saran medis</small></label></div>
    <div class="habit"><input class="check habit-check" type="checkbox" id="h4"><label for="h4"><strong>Jeda dan rawat pikiran</strong><small>Ambil jeda atau hubungi orang tepercaya</small></label></div>
    <div class="habit"><input class="check habit-check" type="checkbox" id="h5"><label for="h5"><strong>Rutinitas tidur</strong><small>Siapkan waktu istirahat yang cukup</small></label></div>
   </div>
  </div>
  <div class="card"><h3>Progres harian</h3><div class="progress-ring" id="progressRing" role="img" aria-label="Progres 0 persen"><div class="progress-ring-inner"><div><strong id="progressText">0%</strong><span class="tiny">selesai</span></div></div></div><p class="sub" style="text-align:center" id="progressMessage">Setiap kebiasaan kecil berarti.</p>
   <div style="border-top:1px solid var(--line);margin-top:18px;padding-top:16px"><strong>Catatan minum</strong><p class="tiny">Hitung gelas yang kamu minum. Ini hanya pengingat, bukan target medis.</p><div class="water-controls"><button class="btn secondary small" id="waterMinus" aria-label="Kurangi satu gelas">−</button><span class="water-count" id="waterCount">0 gelas</span><button class="btn secondary small" id="waterPlus" aria-label="Tambah satu gelas">+ Tambah gelas</button></div></div>
  </div>
 </div>
 <p class="tiny" style="margin-top:12px">Tracker ini untuk refleksi kebiasaan, bukan alat diagnosis atau pengukuran kesehatan.</p>
</div></section>

<section class="section" id="sumber"><div class="container"><div class="section-head"><div><h2>Gunakan informasi dengan bijak</h2><p>Materi edukasi umum, bukan pengganti nasihat medis pribadi.</p></div></div>
 <div class="grid two">
  <div class="card"><h3>Jika kamu punya kondi
