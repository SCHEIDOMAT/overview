# 👨‍⚖️ SCHEIDOMAT – Die digitale Scheidungsplattform

Willkommen beim **SCHEIDOMAT**, der modernen Weblösung zur rechtssicheren, effizienten und verbindlichen Abwicklung von Scheidungsverfahren. Diese Plattform wurde gemeinsam mit juristischen Experten entwickelt und vereint Benutzerfreundlichkeit, Datenschutz und professionelle Kommunikation zwischen Mandanten und Kanzlei.

---

## 🎯 Zielsetzung

> *“Automatisierung trifft auf Rechtsklarheit”*
> **SCHEIDOMAT** bietet eine elegante, durchdachte Plattform für Anwälte, die ihren Mandanten eine digitale Scheidung mit allen rechtlichen Formalitäten anbieten wollen – kontaktlos, effizient und DSGVO-konform.

---

## 🧩 Features (geplant und umgesetzt)

* ⚙️ **Individuelle Mandatsformulare** – dynamisch generiert
* 📨 **Mandanten-Kommunikation** – verschlüsselt und revisionssicher
* 📄 **Upload legaler Dokumente** (z. B. Ehevertrag, Geburtsurkunden)
* 📆 **Fallübersicht und Timeline-Tracking** für Mandanten
* 🧾 **Automatisierte Dokumentenvorbereitung** (PDF-Export)
* 💬 **Chatfunktion** mit Kanzlei-Team (optional)
* 🔐 **Mandanten-Loginbereich** mit Statusanzeige

---

## 🧱 Tech-Stack

| Layer             | Technologie                               |
| ----------------- | ----------------------------------------- |
| Frontend          | Tailwind CSS, HTML5, Alpine.js (optional) |
| Backend           | Django (REST + Admin)                     |
| Authentifizierung | Django Allauth / JWT                      |
| PDF-Generierung   | WeasyPrint / ReportLab                    |
| Deployment        | Docker + Plesk / Vercel / Netlify         |
| Hosting           | Plesk, GitHub Pages (Frontend-only)       |

---

## 📂 Projektstruktur (Ausschnitt)

```
scheidomat/
├── backend/
│   ├── scheidomat_core/      # Django-Projektkern
│   ├── mandanten/            # App zur Mandantenverwaltung
│   ├── scheidungsprozess/    # Ablauf & Statusmodelle
│   └── templates/            # HTML-Templates für Admin/Frontend
├── frontend/
│   └── tailwind/             # Tailwind UI Templates
├── media/                    # Hochgeladene Dokumente
├── docker-compose.yml        # Containerverwaltung
└── README.md
```

---

## 📜 Lizenzierung

**SCHEIDOMAT** wird exklusiv an Anwaltskanzleien lizenziert.
Interessierte Kanzleien wenden sich bitte über das Kontaktformular der offiziellen Projektseite oder direkt per Mail an den Vertrieb.

🛡️ **Code-Lizenz:** Eigenentwickelte Komponenten unterliegen dem Urheberrecht.
📄 **Nutzungsrechte:** Exklusivlizenz für Initiatoren und Vertriebspartner.

---

## 🤝 Mitwirken

Die Plattform wird weiterentwickelt. Feedback von Jurist\:innen, Kanzlei-IT und Mandanten ist willkommen.
➡️ Pull Requests und Issues gerne über [GitHub](https://github.com/SCHEIDOMAT) einreichen.

---

## 👤 Autor & Initiator

**Technische Entwicklung & Konzeption:** [Obscuras Media Agency](https://github.com/obscuras)
**Juristische Initiative:** RA Gaussmann, Kanzlei Gaussmann & Partner

---

## 📧 Kontakt

📮 **E-Mail:** [kontakt@scheidomat.de](mailto:kontakt@scheidomat.de) *(Platzhalter)*
🌐 **Web:** [www.scheidomat.de](http://www.scheidomat.de) *(in Entwicklung)*

---

Danke für dein Interesse am SCHEIDOMAT – wir digitalisieren die Justiz, Schritt für Schritt. ⚖️✨
