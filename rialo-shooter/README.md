📄 Buat file rialo-shooter/README.md

Isi:

# 🎮 Rialo Shooter

**Rialo Shooter** adalah mini-game tembak-menembak top-down bertema **Rialo**  
dengan karakter hero, musuh skeleton, dan boss kepiting berlogo Rialo.

## 🚀 Fitur
- 🎨 Pixel-art karakter Hero, Skeleton, dan Boss
- 💥 Efek **ledakan** saat musuh & boss mati
- 🔊 **Musik latar** (`music.mp3`) dan efek suara tembakan
- 🕹️ Kontrol keyboard (WASD / panah) + tombol virtual di layar
- ❤️ HP bar, Level, Score
- ⚡ Power-ups dan mode Game Over dengan tombol **Try Again** dan **Back to Menu**
- 🌐 Siap deploy ke **GitHub Pages**
- 📲 Mendukung **PWA (Progressive Web App)** & Service Worker

## 📂 Struktur Folder


rialo-shooter/
├── bg-game.png # background arena game
├── bg-menu.png # background menu
├── boss.png # sprite boss kepiting
├── hero1.png
├── hero2.png
├── hero3.png # sprite hero
├── selection.png # sprite skeleton
├── music.mp3 # musik latar
├── sw.js # service worker untuk PWA
├── manifest.json # manifest untuk PWA
├── index.html # halaman utama game
└── README.md # deskripsi folder ini


## ▶️ Cara Menjalankan Secara Lokal
1. Clone repo ini:
   ```bash
   git clone https://github.com/Fatkhl/rialo-demo-dapp.git
   cd rialo-demo-dapp/rialo-shooter


Jalankan server lokal:

npx serve .


Buka di browser:

http://localhost:3000


Pilih hero → mainkan game.

🌐 Jalankan di GitHub Pages

Jika repo di-deploy ke Pages:

https://fatkhl.github.io/rialo-demo-dapp/rialo-shooter/index.html

📝 Commit README.md

Dari root repo di Codespaces:

cd /workspaces/codespaces-blank
echo "<isi README di atas>" > rialo-shooter/README.md

git add rialo-shooter/README.md
git commit -m "docs: add README for rialo-shooter game"
git push origin main
