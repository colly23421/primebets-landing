# PrimeBets Landing Page 🎯

## 📋 O projekcie
Nowoczesny landing page dla PrimeBets - responsywna strona z animacjami i wysoką wydajnością.

## 🚀 Technologie
- HTML5
- CSS3 (z animacjami)
- Vanilla JavaScript
- Vercel (hosting)
- GitHub Actions (CI/CD)

## 🛠️ Instalacja lokalna

```bash
# Klonowanie repozytorium
git clone https://github.com/YOUR_USERNAME/primebets-landing.git
cd primebets-landing

# Instalacja Vercel CLI (opcjonalnie)
npm i -g vercel

# Uruchomienie lokalnie
vercel dev
# lub po prostu otwórz index.html w przeglądarce
```

## 📦 Struktura projektu

```
primebets-landing/
├── api/                 # Serverless functions
│   ├── contact.js      # Obsługa formularza
│   └── newsletter.js   # Newsletter
├── public/             # Zasoby statyczne
│   └── images/        # Obrazy i ikony
├── src/               # Kod źródłowy (opcjonalnie)
├── index.html         # Główny plik HTML
├── style.css          # Style
├── script.js          # JavaScript
├── vercel.json        # Konfiguracja Vercel
└── README.md          # Dokumentacja
```

## 🌐 Deployment

### Automatyczny deploy (zalecany)
Każdy push do brancha `main` automatycznie deployuje zmiany na Vercel.

### Manualny deploy
```bash
# Deploy do preview
vercel

# Deploy do produkcji
vercel --prod
```

## 🔧 Konfiguracja DNS

Domena: `primebets.pl`

### Rekordy DNS (Aftermarket):
```
A     @     76.223.126.88
A     @     76.223.126.99
CNAME www   cname.vercel-dns.com
```

## 📧 Kontakt
- Email: info@primebets.pl
- Website: [primebets.pl](https://primebets.pl)

## 📝 Zmienne środowiskowe

Utwórz plik `.env.local` (nie commituj!):
```
SMTP_HOST=mail.primebets.pl
SMTP_USER=noreply@primebets.pl
SMTP_PASS=your_password
GOOGLE_ANALYTICS_ID=G-XXXXXXXXXX
```

## 🔐 Bezpieczeństwo
- Wszystkie zmienne środowiskowe w Vercel Dashboard
- HTTPS wymuszony
- Headers bezpieczeństwa w `vercel.json`
- Rate limiting na API

## 📊 Monitoring
- Vercel Analytics
- Google Analytics
- Web Vitals

## 📄 Licencja
© 2024 PrimeBets. All rights reserved.

---
**Status:** 🟢 Active | **Vercel:** [![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/YOUR_USERNAME/primebets-landing)
