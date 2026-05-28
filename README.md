# 🐾 Homework is Fun! — Huiswerk Dashboard voor Flo & Maxine

Een persoonlijk huiswerk-oefentool voor groep 5 en 6, gebouwd voor Flo en Maxine. De app genereert automatisch oefenvragen per vak via de Anthropic (Claude) API.

---

## 🚀 Hoe werkt het?

1. Open `huiswerk-dashboard.html` in een browser (Chrome werkt het best)
2. Klik op **⚙️ Instellingen** rechtsboven
3. Voer je Anthropic API-sleutel in (zie hieronder)
4. Kies een groep, vak, onderwerp en moeilijkheidsgraad
5. Klik op **✨ Genereer huiswerk**

---

## 🔑 API-sleutel

De app gebruikt de Anthropic Claude API om vragen te genereren. Je hebt hiervoor een eigen API-sleutel nodig.

- Sleutel aanmaken via: [console.anthropic.com](https://console.anthropic.com/settings/keys)
- De sleutel wordt **alleen lokaal in de browser opgeslagen** (localStorage) — hij staat nergens online
- Stel een uitgavenlimiet in via de Anthropic console (bijv. €5/maand) om verrassingen te voorkomen

---

## 📚 Vakken

De app dekt de volgende vakken voor groep 5 en 6 (SLO kerndoelen):

- Rekenen
- Taal
- Spelling
- Begrijpend lezen
- Topografie
- Engels
- Geschiedenis
- Natuur & Milieu
- Frans
- Dictee (met audio!)
- Logisch denken
- Sociaal & Emotioneel

Plus een speciale **Vakantie modus** met 50 gemixte vragen per vakantie thema.

---

## 🏆 Scores

- Scores worden automatisch opgeslagen in de browser (localStorage)
- Scorebord is te bekijken via de **🏆 Scores** knop rechtsboven
- Scores worden bijgehouden per speler (Flo / Maxine), per vak en per maand
- Beloningen/badges worden automatisch verdiend op basis van aantal oefeningen

---

## 🤖 Technische details

| Onderdeel | Detail |
|-----------|--------|
| Model | `claude-haiku-4-5-20251001` |
| API | Anthropic `/v1/messages` |
| Opslag | Browser localStorage (geen database) |
| Installatie | Geen — gewoon het HTML-bestand openen |

---

## 🔧 Aanpassingen maken

Wil je iets veranderen aan de app? Open een nieuw gesprek in Claude.ai, plak de code uit `huiswerk-dashboard.html` erin, en beschrijf wat je wilt aanpassen. Sla daarna de nieuwe versie op en upload hem hier naar GitHub ter vervanging van het oude bestand.

---

## 📁 Bestanden

| Bestand | Omschrijving |
|---------|--------------|
| `huiswerk-dashboard.html` | De volledige app (één bestand) |
| `README.md` | Dit bestand |

---

*Gebouwd met ❤️ voor Flo & Maxine*
