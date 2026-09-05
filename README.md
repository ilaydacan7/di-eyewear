# 🕶️ D&I Eyewear

Modern ve responsive bir **gözlük e-ticaret web uygulaması**.

Frontend tarafında **Vite + TypeScript**, backend tarafında **Node.js + Express** ve veritabanı olarak **PostgreSQL** kullanılmıştır.

## ✨ Özellikler

* 👤 Kullanıcı kayıt, giriş ve şifre sıfırlama
* 🛒 Ürün listeleme ve sepet yönetimi
* 📦 Sipariş ve hesap yönetimi
* ❤️ Favoriler
* 🔐 Admin paneli
* 📝 Ürün ve içerik yönetimi
* 📧 E-posta işlemleri

## 🛠️ Teknolojiler

**Frontend:** TypeScript, Vite, React, HTML, CSS
**Backend:** Node.js, Express.js, REST API
**Database:** PostgreSQL
**Tools:** Git, GitHub, dotenv, Nodemailer

## 🏗️ Mimari

```text
Frontend
   ↓
REST API
   ↓
Node.js + Express
   ↓
PostgreSQL
```

## 📁 Proje Yapısı

```text
src/          → Frontend
public/       → Görseller ve statik dosyalar
backend/      → Express API
.env.example  → Environment değişkenleri
```

## ⚙️ Kurulum

```bash
git clone https://github.com/ilaydacan7/G-zl-k-sitesi.git
cd G-zl-k-sitesi
npm install
```

`.env.example` dosyasını `.env` olarak oluşturup gerekli değişkenleri doldurun.

```bash
npm run dev:all
```

## 🔐 Güvenlik

* Environment variables ile hassas bilgilerin korunması
* Admin session güvenliği
* CORS yapılandırması
* Veritabanı bağlantısının güvenli şekilde yönetilmesi

## 👩‍💻 Developer

**İlayda Can**
Software Engineering Student | Full-Stack / Backend / QA

[GitHub](https://github.com/ilaydacan7)

