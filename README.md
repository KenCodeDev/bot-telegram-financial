<div align="center">

# 💰 Bot Telegram Financial

### Manage Your Finance Directly Through Telegram

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1200&center=true&vCenter=true&width=800&lines=Track+Income+and+Expenses;Manage+Your+Finance+with+Telegram;Simple+%7C+Fast+%7C+Open+Source;Powered+by+Node.js" alt="Typing SVG" />

<br>

![Node.js](https://img.shields.io/badge/Node.js-v24+-339933?style=for-the-badge\&logo=node.js\&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram-Bot-26A5E4?style=for-the-badge\&logo=telegram\&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20%7C%20Android-blue?style=for-the-badge)
![Open Source](https://img.shields.io/badge/Open%20Source-Yes-success?style=for-the-badge)

### 🇮🇩 Bahasa Indonesia • 🇺🇸 English

</div>

---

## ✨ Features

* 💰 Record financial transactions
* 📈 Track income and expenses
* 📊 Financial reports
* 🤖 Fully integrated with Telegram
* ⚡ Easy setup and deployment
* 🌐 Open source and customizable

---

## 📚 Documentation

* [🇮🇩 Indonesia](#-indonesia)
* [🇺🇸 English](#-english)

---

# 🇮🇩 Indonesia

## Persyaratan

Pastikan **Node.js** sudah terinstall pada perangkat kamu.

### Download Node.js

**Windows x64**

https://nodejs.org/dist/v24.16.0/node-v24.16.0-x64.msi

---

## Membuat Bot Telegram

### 1. Cari BotFather

Cari username **@BotFather** di Telegram.

![BotFather](https://files.catbox.moe/n3jxzc.png)

---

### 2. Jalankan BotFather

Tekan tombol **START**.

> Jika tombol START tidak muncul, silakan abaikan langkah ini dan lanjutkan ke langkah berikutnya.

![Start](https://files.catbox.moe/k6wfi4.png)

---

### 3. Buat Bot Baru

Ketik dan kirim:

```text
/newbot
```

![New Bot](https://files.catbox.moe/14yf08.png)

---

### 4. Tentukan Nama dan Username

Masukkan:

* Nama bot
* Username bot

**Username harus diakhiri dengan kata `bot`.**

Contoh:

```text
Nama Bot     : Financial Assistant
Username Bot : financialassistantbot
```

> Jika username sudah digunakan, pilih username lain.

![Username](https://files.catbox.moe/xlj4o2.png)

---

### 5. Simpan Bot Token

Setelah bot berhasil dibuat, BotFather akan memberikan token.

Salin token tersebut karena akan digunakan pada file `.env`.

![Token](https://files.catbox.moe/xzy8z6.png)

---

# Menjalankan Bot

> **Catatan**
>
> Pastikan kamu memiliki tempat untuk menjalankan bot:
>
> * PC/Desktop pribadi
> * VPS/Server
>
> Jika belum memiliki server, kamu bisa menyewa server harian di **RevsCloud** dengan minimal masa sewa **3 hari**. Harga mulai dari sekitar **Rp5.000 untuk 3 hari**.

---

## 1. Download Repository

### Download ZIP

```text
https://github.com/KenCodeDev/bot-telegram-financial/archive/refs/tags/v1.0.0.zip
```

### Git Clone

```bash
git clone https://github.com/KenCodeDev/bot-telegram-financial.git
```

---

## 2. Ekstrak File

Jika menggunakan ZIP, ekstrak file terlebih dahulu.

---

## 3. Konfigurasi Token

Buka file `.env`.

Masukkan token bot pada bagian:

```env
BOT_TOKEN=TOKEN_BOT_KAMU
```

---

## 4. Buka Terminal

Masuk ke folder project dan buka:

* Command Prompt
* PowerShell
* Windows Terminal

---

## 5. Install Dependency

```bash
npm install
```

Tunggu hingga proses selesai.

---

## 6. Jalankan Bot

```bash
node .
```

---

## Troubleshooting

### Error: node tidak dikenali

Contoh:

```text
'node' is not recognized as an internal or external command
```

Penyebab:

* Node.js belum terinstall
* Komputer belum direstart setelah instalasi Node.js

Solusi:

1. Install Node.js
2. Restart komputer
3. Jalankan kembali:

```bash
node .
```

---

## 🎉 Selesai

Jika seluruh langkah telah dilakukan dengan benar, bot Telegram kamu akan berjalan dan siap digunakan.

---

# 🇺🇸 English

## Requirements

Make sure **Node.js** is installed on your device.

### Download Node.js

**Windows x64**

https://nodejs.org/dist/v24.16.0/node-v24.16.0-x64.msi

---

## Creating a Telegram Bot

### 1. Find BotFather

Search for **@BotFather** on Telegram.

![BotFather](https://files.catbox.moe/n3jxzc.png)

---

### 2. Start BotFather

Press the **START** button.

> If the START button is not available, simply skip this step.

![Start](https://files.catbox.moe/k6wfi4.png)

---

### 3. Create a New Bot

Send:

```text
/newbot
```

![New Bot](https://files.catbox.moe/14yf08.png)

---

### 4. Choose a Name and Username

Enter:

* Bot name
* Bot username

**The username must end with `bot`.**

Example:

```text
Bot Name     : Financial Assistant
Bot Username : financialassistantbot
```

> If the username is already taken, choose another one.

![Username](https://files.catbox.moe/xlj4o2.png)

---

### 5. Save the Bot Token

BotFather will provide a token after the bot is created.

Copy the token because it will be required in the `.env` file.

![Token](https://files.catbox.moe/xzy8z6.png)

---

# Running the Bot

> **Note**
>
> Make sure you have a place to run your bot:
>
> * Personal PC/Desktop
> * VPS/Server
>
> If you don't have a server, you can rent a daily VPS from **RevsCloud** with a minimum rental period of **3 days**. Prices start from approximately **IDR 5,000 for 3 days**.

---

## 1. Download the Repository

### ZIP Download

```text
https://github.com/KenCodeDev/bot-telegram-financial/archive/refs/tags/v1.0.0.zip
```

### Git Clone

```bash
git clone https://github.com/KenCodeDev/bot-telegram-financial.git
```

---

## 2. Extract Files

If you downloaded the ZIP version, extract it first.

---

## 3. Configure Token

Open the `.env` file.

Insert your token:

```env
BOT_TOKEN=YOUR_BOT_TOKEN
```

---

## 4. Open Terminal

Navigate to the project directory and open:

* Command Prompt
* PowerShell
* Terminal

---

## 5. Install Dependencies

```bash
npm install
```

Wait until all dependencies are installed.

---

## 6. Start the Bot

```bash
node .
```

---

## Troubleshooting

### Error: node is not recognized

Example:

```text
'node' is not recognized as an internal or external command
```

Cause:

* Node.js is not installed
* The computer has not been restarted after installation

Solution:

1. Install Node.js
2. Restart your computer
3. Run:

```bash
node .
```

---

## 🎉 Done

If everything was completed correctly, your Telegram bot should now be running and ready to use.
