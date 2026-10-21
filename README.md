# 🏔️ Reis 2027: Lago di Ledro (Italië) vs. Meer van Bled (Slovenië)

Een interactieve, luxueus vormgegeven reisbrochure en vergelijkingsplatform voor onze zomervakantie van **12 t/m 20 juli 2027 (8 nachten)** voor 4 personen.

In deze applicatie kun je direct schakelen tussen de twee topbestemmingen én een complete head-to-head prijs- en comfortvergelijking bekijken!

---

## 🌟 Wat kun je in de Web-App bekijken?

Bovenaan de pagina vind je een interactieve schakelaar waarmee je direct tussen 3 weergaves wisselt:

1. 🇮🇹 **Lago di Ledro & Gardameer (Italië):**
   - Verblijf in **Hotel Lido Ledro** direct aan het bergmeer.
   - 6 geïntegreerde 4K-referentievideo's (hotel, Strada del Ponale, Monte Baldo kabelbaan, suppen).
   - Volledig 8-daags reisschema, wandelroutes en gastronomische tips (houtovenpizza, Carne Salada, Val Concei).
   - Reizen met de **eigen auto** via Füssen/Fernpass met 2 tussenstops in Beieren/Tirol en Speyer (ca. € 180 p.p. transport).
2. 🇸🇮 **Meer van Bled & Julische Alpen (Slovenië):**
   - Verblijf in **Lake Bled Apartments** aan de rustige Veslaška Promenada (Zaka Bay) met privébalkon en eilandzicht.
   - 4 geïntegreerde 4K-referentievideo's (Bled in 4K, Vintgar-kloof, Vogel kabelbaan 1.535m, Ljubljana).
   - Volledig 8-daags reisschema, Pletna-boottochten, Bohinjmeer en de originele *Blejska kremšnita*.
   - Reizen per **vlucht vanaf Zaventem naar Ljubljana (1u35m) + privé-luchthaventransfer** in 25 min naar het hotel (ca. € 240 p.p. transport, géén huurauto en géén parkeerkosten!).
3. ⚖️ **Head-to-Head Vergelijkingsdashboard:**
   - Volledige prijstabel (transport, vignetten, transfers, parkeergeld en verblijf).
   - Vergelijking van reiscomfort (2 dagen ontspannen roadtrippen vs. 1u35 vliegen).
   - Plus- en minpunten per bestemming.
   - Stem-knop om je voorkeur aan te geven!

---

## 🚀 Lokaal Openen & Bekijken

Dubbelklik simpelweg op `index.html` of open het bestand in je browser (Chrome, Edge, Firefox, Safari).

Of start een lokale server via PowerShell:
```powershell
python -m http.server 8080
```
Surf vervolgens naar `http://localhost:8080`.

---

## 🔀 Git Branches

Voor het gemak zijn de individuele reisversies ook nog apart opgeslagen op hun eigen branches:
- `git checkout main`: De verenigde app met de interactieve schakelaar en prijsvergelijking.
- `git checkout ledro`: De stand-alone brochure voor Lago di Ledro (Italië).
- `git checkout bled`: De stand-alone brochure voor Meer van Bled (Slovenië).
