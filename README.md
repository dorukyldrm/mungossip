<div align="center">

  <h1>MunGossip ✉️</h1>

  <p><strong>Digital Gossip Chamber & Smart Board Presentation System for MUN Conferences</strong></p>
  <p><em>Model United Nations Konferansları İçin Dijital Dedikodu Sandığı ve Akıllı Tahta Sunum Platformu</em></p>

  <br />

  <p>
    <a href="#-english"><strong>🇬🇧 English</strong></a> &nbsp;|&nbsp; 
    <a href="#-türkçe"><strong>🇹🇷 Türkçe</strong></a> &nbsp;|&nbsp; 
    <a href="#-tech-stack--architecture"><strong>🛠️ Tech Stack</strong></a>
  </p>

  <br />

  <p>
    <img src="https://img.shields.io/badge/Live_Platform-mungossip.com-050a14?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Live Platform" />
    <img src="https://img.shields.io/badge/Stack-Next.js_16_|_React_19-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Tech Stack" />
    <img src="https://img.shields.io/badge/Privacy-100%25_Zero--Registration-047857?style=for-the-badge&logo=shield&logoColor=white" alt="Privacy" />
    <img src="https://img.shields.io/badge/Moderation-Dual--Screen_Cockpit-f59e0b?style=for-the-badge&logo=smartphone&logoColor=white" alt="Dual-Screen Moderation" />
  </p>

</div>

---

<a id="-english"></a>
## 🇬🇧 English

### What is MunGossip?
In Model United Nations (MUN) conferences, delegates spend hours debating global crisis resolutions under strict formal protocol. However, the heartbeat of every MUN conference is the beloved **Gossip Box** tradition during closing sessions.

Traditional paper boxes get misplaced, handwritten notes are illegible on projection screens, and social media group chats risk exposing personal accounts or inviting unwanted external trolls.

**MunGossip** transforms this legacy tradition into a secure, zero-registration, projector-ready smart board presentation platform powered by dual-screen phone moderation.

### Key Features
- 📺 **Smart Board Presentation Chamber:** Launch an interactive lobby in seconds and project a dynamic QR code onto the committee screen.
- 📱 **Dual-Screen Phone Cockpit (Pre-Screening Moderation):** Incoming notes never appear on the big screen unvetted. Session chairs review pending notes on their phone via `/archive` > *Mektup Yetkilisi* before approving them to the big screen.
- 🔒 **Zero-Registration Privacy:** Delegates scan the QR code and join instantly. No emails, phone numbers, or passwords required. Choose a diplomatic avatar and temporary session nickname.
- ⚡ **Anti-Troll & Passcode Security:** Secured with dynamic passcodes, session lifecycle timeouts, and instant 1-click room locking (`is_locked`) to prevent unauthorized external access.
- 🗳️ **Live Floor Reactions:** Delegates vote live on the floor with **"Katılıyorum" (Agree)** or **"Katılmıyorum" (Disagree)** reactions directly from their mobile phones.
- 🌍 **Free Country Guessing Game:** Committees can guess which country authored or targeted the note. The true author's country remains an unsolved mystery for pure entertainment.

---

<a id="-türkçe"></a>
## 🇹🇷 Türkçe

### MunGossip Nedir?
Model United Nations (MUN) konferanslarında delegeler saatlerce resmi BM protokolüyle dünya meselelerini tartışırlar. Ancak her MUN konferansını unutulmaz kılan asıl ruh, oturum sonlarında açılan geleneksel **Gossip Box (Dedikodu Kutusu)** geleneğidir.

Geleneksel kağıt kutular kaybolur, okunaksız el yazıları tahtada anlaşılamaz ve WhatsApp/Telegram grupları kişisel hesapların ifşa olmasına ya da dışarıdan yetkisiz kişilerin sızmasına sebep olur.

**MunGossip**, bu köklü geleneği kayıtsız, şifreli ve çift ekranlı telefon moderasyonuyla yönetilen akıllı tahta sunum platformuna dönüştürür.

### Öne Çıkan Özellikler
- 📺 **Akıllı Tahta Sunum Ekranı:** Saniyeler içinde lobi başlatın ve şifreli QR kodu salondaki akıllı tahtaya yansıtın.
- 📱 **Çift Ekranlı Telefon Moderasyonu (Mektup Yetkilisi):** Gelen mektuplar doğrudan tahtada gözükmez. Komite başkanı telefonundan `/archive` > *Mektup Yetkilisi* ekranına girerek mektupları tahtaya yansımadan önce denetler, zararlı içerikleri anında imha eder.
- 🔒 **Kayıtsız Tam Anonimlik:** Delegeler e-posta, telefon veya şifre girmeden QR kod ile odaya katılır. Diplomatik simgesini ve oturum takma adını belirler.
- ⚡ **Dış Müdahalelere Karşı Koruma:** Şifreli geçiş anahtarı, 5 saatlik oturum süresi ve tek dokunuşla salon dondurma (`is_locked`) yetkisiyle dışarıdan trol sızması %100 önlenir.
- 🗳️ **Canlı Salon Oylaması:** Delegeler telefondan **"Katılıyorum"** veya **"Katılmıyorum"** seçenekleriyle salondaki iddialara anında reaksiyon verir.
- 🌍 **Serbest Ülke Tahmini Oyunu:** Salondaki delegeler mektubun kaynağı olan ülkeyi tahmin etmek için yarışır. Gerçek ülke hiçbir zaman açıklanmaz; tam anonimlik ve eğlence korunur.

---

<a id="-tech-stack--architecture"></a>
## 🛠️ Tech Stack & Architecture

- **Frontend:** Next.js 16 (App Router), React 19, TypeScript
- **Styling:** Tailwind CSS v4, Fluid Typography (`clamp`), Custom Editorial Theme Tokens
- **Realtime & Database:** Supabase Postgres, Realtime WebSockets, Row Level Security (RLS)
- **Audio & Animations:** Framer Motion, Web Audio API Sound Design
- **Icons & Assets:** Lucide React, Apple CDN High-Res Flags (`AppleFlag.tsx`)

---

## 🚀 Local Development Setup

```bash
# 1. Clone the repository
git clone https://github.com/dorukyldrm/mungossipbox.git
cd mungossipbox

# 2. Install dependencies (npm only)
npm install

# 3. Start development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

---

<div align="center">
  <p>Powered by the privacy infrastructure and editorial standards of <a href="https://www.theregretwall.com">theregretwall.com</a></p>
  <p>© 2026 MunGossip. All rights reserved.</p>
</div>
