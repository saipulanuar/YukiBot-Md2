<p align="center">
<img src="https://github.com/saipulanuar/Api-Github/blob/main/img1.png" alt="YukiBot-Md2" width="100"/>


</p>
<p align="center">
<a href="#"><img title="KING OF BEAR MULTI DEVICE" src="https://img.shields.io/badge/KING OF BEAR MULTI DEVICE-green?colorA=%23ff0000&colorB=%23017e40&style=for-the-badge"></a>
</p>
<p align="center">
<a href="https://github.com/DikaArdnt"><img title="Author" src="https://img.shields.io/badge/Author-Dika-red.svg?style=for-the-badge&logo=github"></a>
<a href="https://github.com/saipulanuar/YukiBot-Md2"><img title="Recode" src="https://img.shields.io/badge/Recode-KingOfBear-red.svg?style=for-the-badge&logo=github"></a>
</p>
<p align="center">
<a href="https://github.com/saipulanuar/followers"><img title="Followers" src="https://img.shields.io/github/followers/saipulanuar?color=red&style=flat-square"></a>
<a href="https://github.com/saipulanuar/YukiBot-Md2/stargazers/"><img title="Stars" src="https://img.shields.io/github/stars/saipulanuar/YukiBot-Md2?color=blue&style=flat-square"></a>
<a href="https://github.com/saipulanuar/YukiBot-Md2/network/members"><img title="Forks" src="https://img.shields.io/github/forks/saipulanuar/YukiBot-Md2?color=red&style=flat-square"></a>
<a href="https://github.com/saipulanuar/YukiBot-Md2/watchers"><img title="Watching" src="https://img.shields.io/github/watchers/saipulanuar/YukiBot-Md2?label=Watchers&color=blue&style=flat-square"></a>
<a href="https://github.com/saipulanuar/YukiBot-Md2"><img title="Open Source" src="https://badges.frapsoft.com/os/v2/open-source.svg?v=103"></a>
<a href="https://github.com/saipulanuar/YukiBot-Md2/"><img title="Size" src="https://img.shields.io/github/repo-size/saipulanuar/YukiBot-Md2?style=flat-square&color=green"></a>
<a href="https://hits.seeyoufarm.com"><img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fsaipulanuar%2FYukiBot-Md2&count_bg=%2379C83D&title_bg=%23555555&icon=probot.svg&icon_color=%2300FF6D&title=hits&edge_flat=false"/></a>
<a href="https://github.com/saipulanuar/YukiBot-Md2/graphs/commit-activity"><img height="20" src="https://img.shields.io/badge/Maintained%3F-yes-green.svg"></a>&nbsp;&nbsp;
</p>

<p align="center">
  <a href="https://github.com/saipulanuar/YukiBot-Md2#requirements">Requirements</a> •
  <a href="https://github.com/saipulanuar/YukiBot-Md2#instalasi">Installation</a> •
  <a href="https://github.com/saipulanuar/YukiBot-Md2#thanks-to">Thanks to</a> •
  <a href="https://github.com/saipulanuar/YukiBot-Md2#Official-Group"> Official Group Bot</a> •
  <a href="https://github.com/saipulanuar/YukiBot-Md2#donate">Donate</a>
</p>
</div>


---

## Information
> YukiBot-Md2 adalah bot yang awalnya memakai base dari [Chikabot](https://github.com/rashidsiregar28/chikabot/blob/main/README.md), sekarang pindah base [Hisoka-Morou](https://github.com/DikaArdnt/Hisoka-Morou). YukiBot-Md2 is a bot whatsapp using a Baileys library.
> Jika kamu menemukan semacam bug, harap untuk dimaklumi sementara

## Bugs and Tester
* Jika kamu menemukan bug jangan lupa buka Issues
* Info Lebih Lanjut, Chat [Owner-KingOfBear](https://wa.me/6288279268363)

# Requirements
* [Node.js](https://nodejs.org/en/)
* [Git](https://git-scm.com/downloads)
* [FFmpeg](https://github.com/BtbN/FFmpeg-Builds/releases/download/autobuild-2020-12-08-13-03/ffmpeg-n4.3.1-26-gca55240b8c-win64-gpl-4.3.zip) (for sticker command)

# Instalasi
## Heroku Buildpack
```bash
heroku/nodejs
https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest
https://github.com/clhuang/heroku-buildpack-webp-binaries.git
```
## For Termux
```ts
termux-setup-storage
apt update && apt upgrade
pkg install nodejs git ffmpeg libwebp imagemagick
git clone https://github.com/saipulanuar/YukiBot-Md2.git
cd YukiBot-Md2
pkg install yarn
yarn install
npm i -g typescript
tsc -p ./node_modules/@adiwajshing/baileys-md/
rm -rf session.json
rm -rf store.json
npm start
```

## Edit file
`./settings.js`
```ts
global.autoread = false // auto read pesan / message
global.autorecording = true //status auto merekam ( auto record )
global.autoketik = false //status auto mengetik (auto typing)
global.available = false //status online (online)

// Other
global.botname = "YukiBot-Md2ོ"
global.ownername= "ᴹᴿ᭄ KingOfBearོ ×፝֟͜×"
global.myweb ="https://apikey-bear3.herokuapp.com/"
global.youtube = "https://apikey-bear3.herokuapp.com/"
global.github = "https://saipulanuar.github.io/"
global.email = "drakipul1016@gmail.com"
global.region = "Indonesia"
global.ownernomer = "6288279268363"
global.ownernomerr = "+6288279268363"
global.thumbnail = "./image/lol.jpg"
global.donasi = "./image/donasi.jpg"
global.background_welcome="https://telegra.ph/file/90a931648de597820bc08.jpg" // maks size 30kb, agar welcome image nya tdk delay
global.owner = ["6288279268363","6288279268363","6288279268363"] //ganti agar fitur owner bisa di gunakan
global.packname = '© YukiBot-Md2ོ' //sticker wm
global.author = 'Di Buat Oleh KingOfBear' //sticker wm
global.sessionName = 'session'
```

## Installing the FFmpeg for Windows
* Unduh salah satu versi FFmpeg yang tersedia dengan mengklik [di sini](https://www.gyan.dev/ffmpeg/builds/).
* Extract file ke `C:\` path.
* Ganti nama folder yang telah di-extract menjadi `ffmpeg`.
* Run Command Prompt as Administrator.
* Jalankan perintah berikut::
```cmd
> setx /m PATH "C:\ffmpeg\bin;%PATH%"
```
Jika berhasil, akan memberikanmu pesan seperti: `SUCCESS: specified value was saved`.
* Sekarang setelah Anda menginstal FFmpeg, verifikasi bahwa itu berhasil dengan menjalankan perintah ini untuk melihat versi:
```cmd
> ffmpeg -version
```

## Donate
- [Saweria](https://saweria.co/raraharsita2)


# Thanks to
<a href="https://github.com/DikaArdnt"><img src="https://github.com/DikaArdnt.png?size=100" width="100" height="100"></a> | [![NURUTOMO](https://github.com/Nurutomo.png?size=100)](https://github.com/Nurutomo) 
---|---
[Dika](https://github.com/DikaArdnt)  | [Nurutomo](https://github.com/Nurutomo)
Owner Hisoka-Morou | Constributor |
<a href="https://github.com/MhankBarBar"><img src="https://github.com/MhankBarBar.png?size=100" width="100" height="100"></a> | [![FATIH](https://github.com/fatiharridho.png?size=100)](https://github.com/fatiharridho) 
[Mhankbarbar](https://github.com/MhankBarBar)  | [Fatih A.](https://github.com/fatiharridho)
Constributor | For Help |
<a href="https://github.com/FERDIZ-afk"><img src="https://github.com/FERDIZ-afk.png?size=100" width="100" height="100"></a> | [![RASHID](http://github.com/rashidsiregar28.png?size=100)](http://github.com/rashidsiregar28) 
[Ferdiz](https://github.com/FERDIZ-afk)  | [Rashid](https://github.com/rashidsiregar28)
For Help | Owner Chikabot |
<a href="https://github.com/adiwajshing"><img src="https://github.com/adiwajshing.png?size=100" width="100" height="100"></a> | [![ZEEONE](http://github.com/saipulanuar.png?size=100)](http://github.com/saipulanuar) 
[Adiwajshing](https://github.com/adiwajshing) | [saipulanuar](https://saipulanuar.github.io)
Owner of Baileys | Owner of Api KingOfBear |

