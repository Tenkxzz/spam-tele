# ⚠️ DISCLAIMER  
Project ini dibuat untuk **tujuan eksperimen & pembelajaran**.  
Bukan untuk spam, flood, harassment, atau penyalahgunaan layanan **Telegram**.

Segala penyalahgunaan di luar tujuan edukasi **bukan tanggung jawab author**.

---

## 🚀 Fitur
- 🤖 Telegram Bot berbasis **Python**
- ⚡ Pengiriman pesan **single chat & multi chat**
- 🧵 Multi-threaded (ThreadPoolExecutor)
- 🎨 Tampilan terminal **pretty & berwarna**
- 📊 Statistik real-time:
  - Total terkirim
  - Success / Failed
  - Speed (msg/sec)
- ⛔ Bisa dihentikan kapan saja (**Ctrl + C**)
- 📂 Dukungan file `chats.txt`
- 🧪 Test koneksi otomatis ke chat target
- 📱 Support **Termux & Linux**

---

## 📸 Screenshots
![alt text](https://github.com/Tenkxzz/spam-tele/blob/main/images/main_menu.jpg?raw=true)

---

## ⚠️ Catatan Penting
- Gunakan hanya pada:
  - Chat pribadi sendiri
  - Group testing
- Patuhi **Telegram Bot API & ToS**

---

## 👤 Author
- Nama: **Tenz**
- Jenis Project: **spam tele v1**
- Tujuan: **Pembelajaran & Eksperimen Teknis**

---

## 🔥 Join Community
Gabung ke channel WhatsApp untuk:
- Update project & tools terbaru
- Sharing Termux, Python & automation
- Diskusi santai & ngoding

📱 https://tinyurl.com/2cxmlqtl  

> Channel ini komunitas, **bukan layanan resmi Telegram**.

---

## 🚀 Instalasi (Termux only)

```bash

pkg update

pkg upgrade

pkg install python

pkg install python-cryptography -y

pkg install clang make openssl libffi

pip install pycryptodome

pkg install git

git clone https://github.com/Tenkxzz/spam-tele.git

cd spam-tele

pip install requests colorama

python main.py
