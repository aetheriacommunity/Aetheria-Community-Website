#!/bin/bash
# setup_minecraft_site.sh
# Script untuk Termux: membuat website tema Minecraft Roleplay Server sederhana
# Cara pakai:
# 1) di Termux: termux-setup-storage  (hanya pertama kali jika perlu akses storage)
# 2) simpan file ini, lalu: chmod +x setup_minecraft_site.sh
# 3) jalankan: ./setup_minecraft_site.sh
# 4) masuk ke folder ~/minecraft_site dan jalankan: ./start_server.sh

set -e

PROJECT_DIR="$HOME/minecraft_site"
echo "Membuat folder project di: $PROJECT_DIR"

# update dan install minimal (opsional)
echo "Mengupdate package dan install python git (opsional, mungkin sudah ada)..."
pkg update -y >/dev/null 2>&1 || true
pkg install -y python git >/dev/null 2>&1 || true

# buat folder
mkdir -p "$PROJECT_DIR"
cd "$PROJECT_DIR"

# buat index.html
cat > index.html <<'HTML'
<!doctype html>
<html lang="id">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>MyRP - Minecraft Roleplay Server</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header class="site-header">
    <div class="wrap">
      <h1 class="logo">MyRP <span class="sub">Minecraft Roleplay</span></h1>
      <nav class="nav">
        <a href="#home">Home</a>
        <a href="#info">Info Server</a>
        <a href="#rules">Rules</a>
        <a href="#ranks">Ranks</a>
        <a href="#staff">Staff</a>
      </nav>
    </div>
  </header>

  <main>
    <section id="home" class="hero">
      <div class="wrap hero-inner">
        <h2>Selamat datang di <strong>MyRP</strong></h2>
        <p>Server roleplay Minecraft dengan economy, jobs, dan cerita seru. Bergabung & mainkan peranmu!</p>
        <div class="cta">
          <div class="server-ip">IP: <strong>play.myrp.example</strong></div>
          <a href="#info" class="button">Info Server</a>
        </div>
      </div>
    </section>

    <section id="info" class="section">
      <div class="wrap">
        <h3>Informasi Server</h3>
        <ul class="info-list">
          <li><strong>Mode:</strong> Roleplay / Survival</li>
          <li><strong>Versi:</strong> 1.20+ (Spigot / Paper)</li>
          <li><strong>Fitur:</strong> Jobs, Economy, RP Quests, Custom Items</li>
          <li><strong>Website:</strong> <a href="#">https://example.com</a></li>
        </ul>
      </div>
    </section>

    <section id="rules" class="section alt">
      <div class="wrap">
        <h3>Rules (Aturan Utama)</h3>
        <ol>
          <li>Hormati pemain lain — no griefing tanpa izin.</li>
          <li>Tidak melakukan hacking/cheat/exploit.</li>
          <li>Roleplay sesuai lore server saat mode RP aktif.</li>
          <li>Ikuti instruksi staff.</li>
        </ol>
      </div>
    </section>

    <section id="ranks" class="section">
      <div class="wrap">
        <h3>Ranks & Benefit</h3>
        <div class="cards">
          <div class="card"><h4>Player</h4><p>Default player.</p></div>
          <div class="card"><h4>VIP</h4><p>Teleport, home, akses item tertentu.</p></div>
          <div class="card"><h4>Staff</h4><p>Moderator dan Admin.</p></div>
        </div>
      </div>
    </section>

    <section id="staff" class="section alt">
      <div class="wrap">
        <h3>Staff</h3>
        <ul class="staff-list">
          <li>HeadAdmin: <strong>AdminName</strong></li>
          <li>Moderator: <strong>Mod1</strong>, <strong>Mod2</strong></li>
        </ul>
      </div>
    </section>

    <section id="apply" class="section contact">
      <div class="wrap">
        <h3>Ingin Bergabung & Apply Staff?</h3>
        <p>Isi form di Discord kami: <a href="#">discord.gg/yourserver</a></p>
      </div>
    </section>
  </main>

  <footer class="site-footer">
    <div class="wrap">
      <p>&copy; <span id="year"></span> MyRP — Minecraft Roleplay Server</p>
    </div>
  </footer>

<script>
document.getElementById('year').textContent = new Date().getFullYear();
</script>
</body>
</html>
HTML

# buat style.css
cat > style.css <<'CSS'
/* Simple Minecraft-ish theme (pixel-ish, earthy colors) */
:root{
  --bg:#0b0b0b;
  --accent:#6b8e23;
  --accent-2:#b8860b;
  --muted:#cfcfcf;
  --card:#111;
}
*{box-sizing:border-box}
body{
  margin:0;
  font-family: system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
  background:linear-gradient(180deg,#071016 0%, #0b0b0b 100%);
  color:var(--muted);
  -webkit-font-smoothing:antialiased;
}
.wrap{max-width:1000px;margin:0 auto;padding:20px;}
.site-header{background:linear-gradient(90deg,#0f1a12, #152214);border-bottom:4px solid rgba(0,0,0,0.4)}
.site-header .wrap{display:flex;align-items:center;justify-content:space-between}
.logo{font-size:20px;margin:0;color:var(--accent-2)}
.logo .sub{display:block;font-size:12px;color:var(--muted)}
.nav a{margin-left:12px;color:var(--muted);text-decoration:none;font-weight:600}
.hero{padding:40px 0;background-image:url('');background-size:cover}
.hero-inner{display:flex;flex-direction:column;gap:12px}
.hero h2{font-size:28px;margin:0;color:#fff}
.hero p{max-width:600px}
.cta{display:flex;align-items:center;gap:16px;margin-top:8px}
.server-ip{background:#0f2b0f;padding:8px 12px;border-radius:6px;color:#b7e3a1;font-weight:700}
.button{background:var(--accent);padding:10px 14px;border-radius:6px;color:#041; text-decoration:none;font-weight:700}
.section{padding:30px 0}
.section.alt{background:linear-gradient(180deg,#060604,#081006)}
.info-list{list-style:none;padding:0}
.cards{display:flex;gap:12px;flex-wrap:wrap}
.card{background:var(--card);padding:14px;border-radius:8px;min-width:150px}
.staff-list{list-style:none;padding:0}
.site-footer{border-top:1px solid rgba(255,255,255,0.03);padding:14px 0;margin-top:20px;text-align:center;color:#999}
@media (max-width:700px){
  .site-header .wrap{flex-direction:column;gap:10px;align-items:flex-start}
  .cards{flex-direction:column}
}
CSS

# buat start_server.sh
cat > start_server.sh <<'BASH'
#!/bin/bash
# start_server.sh - jalankan web server simple
PORT=8080
echo "Menjalankan website di http://localhost:$PORT"
python3 -m http.server $PORT
BASH
chmod +x start_server.sh

# buat README
cat > README.txt <<'TXT'
MyRP - Minecraft Roleplay Static Website (Termux)
-------------------------------------------------
Folder: ~/minecraft_site

Perintah penting:
 - Jalankan website: ./start_server.sh
 - Edit konten: buka index.html & style.css pakai editor (nano, vim)
 - Ganti IP server: cari "play.myrp.example" di index.html dan ubah
 - Tambah gambar: letakkan file di folder 'assets' (buat folder assets) dan refer di HTML.

Catatan:
 - Jika mau diakses dari jaringan lain (HP ke PC), gunakan alamat IP lokal HP (cek with `ip addr`), dan sesuaikan firewall/router.
 - Untuk publik: gunakan layanan tunneling (ngrok / serveo) atau host file di VPS.
TXT

echo "Selesai. Project dibuat di: $PROJECT_DIR"
echo "Jalankan: cd $PROJECT_DIR && ./start_server.sh"
