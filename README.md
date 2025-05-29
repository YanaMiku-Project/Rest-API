# 🌐 YanaMiku API

**YanaMiku API** adalah REST API publik yang menyediakan berbagai layanan mulai dari pencarian informasi, alat bantu, manipulasi gambar, hingga layanan AI. Dirancang untuk kemudahan integrasi dengan berbagai aplikasi, bot, maupun proyek pribadi Anda.

🔗 **Base URL**: `https://api-yanamiku.vercel.app/api/yanamiku`

## 🚀 Cara Penggunaan

Semua endpoint menggunakan metode `GET`. Untuk menggunakan endpoint, cukup tambahkan parameter `type` sesuai dengan jenis layanan yang ingin digunakan.

**Contoh:**

```
GET https://api-yanamiku.vercel.app/api/yanamiku?type=duckduckgo
```

---

## 📚 Daftar Endpoint

### 🔍 Pencarian

* `duckduckgo`
* `ocr`
* `pinterest`
* `github`
* `wikipedia`
* `urban`
* `giphy`
* `unsplash`
* `appvn`
* `apkfab`
* `playstore`
* `playstore2`
* `playstore3`
* `happymod`
* `halodoc`
* `chord`
* `appstore`
* `apkid`
* `weather`
* `googleimage`
* `google`
* `google2`
* `apkpure`
* `an1`
* `apkmody`
* `steam`
* `semoji`
* `soundcloud`
* `cuaca`
* `spotify`
* `lyric`
* `whatanime`

### 💬 Quote Acak

* `senja`
* `charanime`

### 🛠️ Tools

* `blurimage`
* `ttsgoogle`
* `text2qr`
* `translate`
* `tts`

### ℹ️ Informasi

* `cektghnpln`
* `countryinfo`
* `resep`
* `liburnasional`
* `jadwaltv`
* `bmkg`

### 🎨 Maker

* `brat`, `carbon`, `xnxxcanvas`, `welcome1` - `welcome5`, `ship`, `profile`, `levelup`, `goodbye1` - `goodbye5`
* `sandsummer`, `makingneon`, `royaltext`, `deletingtext`, `flag3dtext`, `flagtext`, `pixelglitch`
* `advancedglow`, `lionlogo`, `writetext`, `glitchtext`

### 📰 Berita

* `antara`

### 🤖 AI Tools

* `remini`, `remini2`, `delwatermark`, `faceswap`, `upscale`, `removebg`, `tololi`, `toanime`, `photoeditor`
* `negrocoklat`, `negrohitam`, `negronerd`, `negropiggy`, `negrocarbon`, `negrobotak`

### 🖼️ Gambar Acak

* `malaysia`, `vietnam`, `korea`, `thailand`, `japan`, `indonesia`, `china`, `cat`

### 🔎 Stalker

* `nickml`, `githubstalk`

### 🎌 Anime Actions

* `waifu`, `neko`, `shinobu`, `megumin`, `bully`, `cuddle`, `cry`, `hug`, `awoo`, `kiss`, `lick`, `pat`
* `smug`, `bonk`, `yeet`, `blush`, `smile`, `wave`, `highfive`, `handhold`, `nom`, `bite`, `glomp`, `slap`
* `kill`, `kick`, `happy`, `wink`, `poke`, `dance`, `cringe`

### 📥 Downloader

* `gitclone`, `tiktok`, `mediafire`, `googledrive`, `facebook`, `douyin`

---

## ⚙️ Contoh Implementasi

```bash
curl "https://api-yanamiku.vercel.app/api/yanamiku?type=duckduckgo&query=openai"
```

---

## ❗ Catatan

* Semua endpoint bersifat **publik** tanpa autentikasi.
* Mohon gunakan dengan **bijak** dan tidak untuk keperluan **spam**.
* Response bisa berbeda tergantung parameter dan ketersediaan data eksternal.

---

## 🧑‍💻 Kontribusi

Proyek ini masih dalam pengembangan aktif. Masukan dan kontribusi sangat diterima!

---

## 📄 Lisensi

© 2025 YanaMiku. All rights reserved.
