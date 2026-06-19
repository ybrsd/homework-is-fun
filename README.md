# 🐾 Homework is Fun! — Huiswerk Dashboard

Een persoonlijk huiswerk-oefentool gebouwd voor Flo & Maxine (groep 5 & 6) én een uitgebreide versie voor alle groepen. De app genereert automatisch oefenvragen per vak via de Anthropic (Claude) API.

---

## 🚀 Hoe werkt het?

1. Open het gewenste dashboard in een browser (Chrome werkt het best)
2. Klik op ⚙️ **Instellingen** rechtsboven
3. Voer je Anthropic API-sleutel in (zie hieronder)
4. Kies een groep, vak, onderwerp en moeilijkheidsgraad
5. Klik op ✨ **Genereer huiswerk**

---

## 📁 Bestanden

| Bestand | Omschrijving | URL |
|---|---|---|
| `huiswerk-dashboard.html` | Dashboard voor **Flo & Maxine** (groep 5 & 6) | [Open](https://ybrsd.github.io/homework-is-fun/huiswerk-dashboard.html) |
| `huiswerk-dashboard-new.html` | Uitgebreid dashboard voor **alle groepen** | [Open](https://ybrsd.github.io/homework-is-fun/huiswerk-dashboard-new.html) |
| `README.md` | Dit bestand | — |

---

## 🔑 API-sleutel

De app gebruikt de Anthropic Claude API om vragen te genereren. Je hebt hiervoor een eigen API-sleutel nodig.

- Sleutel aanmaken via: [console.anthropic.com](https://console.anthropic.com/settings/keys)
- De sleutel wordt alleen **lokaal in de browser** opgeslagen (localStorage) — hij staat nergens online
- Stel een uitgavenlimiet in via de Anthropic console (bijv. €5/maand) om verrassingen te voorkomen

---

## 📚 Vakken

De app dekt de volgende vakken (SLO kerndoelen):

- Rekenen
- Taal
- Spelling
- Begrijpend lezen
- Topografie
- Engels
- Geschiedenis
- Natuur & Milieu
- Frans
- Dictee (met audio! 🎧)
- Logisch denken
- Sociaal & Emotioneel

Plus een speciale 🌴 **Vakantie modus** met 50 gemixte vragen per vakantie thema.

---

## 🏆 Scores

- Scores worden automatisch opgeslagen in de browser (localStorage)
- Scorebord is te bekijken via de 🏆 **Scores** knop rechtsboven
- Scores worden bijgehouden **per speler, per vak en per maand**
- Voortgangsbalken tonen score per vak in groen/geel/rood
- Beloningen/badges worden automatisch verdiend op basis van aantal oefeningen
- De twee dashboards slaan scores **volledig gescheiden** op

---

## 🤖 Technische details

| Onderdeel | Detail |
|---|---|
| Model | claude-opus-4-5 |
| API | Anthropic /v1/messages |
| Opslag | Browser localStorage (geen database) |
| Installatie | Geen — gewoon het HTML-bestand openen |

---

## 🔧 Aanpassingen maken

Wil je iets veranderen aan de app? Open een nieuw gesprek in [Claude.ai](https://claude.ai), plak de code uit het gewenste HTML-bestand erin, en beschrijf wat je wilt aanpassen. Sla daarna de nieuwe versie op en upload hem hier naar GitHub ter vervanging van het oude bestand.

---

Gebouwd met ❤️ voor Flo & Maxine
