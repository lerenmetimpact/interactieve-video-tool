# Interactieve Video Editor

Versie 1.0 - Maak interactieve video's met meerkeuze vragen

## 📋 Wat is dit?

Een tool waarmee je eenvoudig interactieve video's kunt maken met meerkeuze vragen. Perfect voor e-learning content in Rise 360 of andere LMS systemen.

## 🚀 Hoe gebruik je deze tool?

### Stap 1: Maak een GitHub account (als je die nog niet hebt)
1. Ga naar https://github.com
2. Klik op "Sign up" en maak een gratis account aan

### Stap 2: Maak een nieuwe repository
1. Klik op het **+** icoon rechtsboven en kies "New repository"
2. Geef je repository een naam, bijvoorbeeld: `interactive-video-tool`
3. Kies "Public" (gratis)
4. Vink **"Add a README file"** aan
5. Klik op "Create repository"

### Stap 3: Upload de bestanden
1. In je nieuwe repository, klik op "Add file" > "Upload files"
2. Sleep **editor.html** naar de upload zone
3. Klik op "Commit changes"

### Stap 4: Activeer GitHub Pages
1. Ga naar "Settings" in je repository
2. Klik op "Pages" in het menu links
3. Bij "Source" kies: **main** branch
4. Klik op "Save"
5. Wacht 1-2 minuten

### Stap 5: Open je tool!
Je tool is nu live op:
```
https://jouwnaam.github.io/interactive-video-tool/editor.html
```

Vervang `jouwnaam` met je GitHub gebruikersnaam en `interactive-video-tool` met de naam van je repository.

## 📖 Hoe maak je een interactieve video?

### 1. Upload je video
- Klik op "Upload Video"
- Kies een MP4, WebM of OGG bestand
- De video wordt direct in de preview geladen

**Let op:** Houd je video onder de 500 MB voor beste prestaties in Rise 360.

### 2. Voeg vragen toe
Voor elke vraag:
1. **Tijdstempel**: Op welk moment (in seconden) moet de vraag verschijnen?
   - Bijvoorbeeld: `30` voor 30 seconden, of `90` voor 1:30
2. **Vraag**: Typ je vraag
3. **Antwoorden**: Vul 2-4 antwoorden in
4. **Juiste antwoord**: Vink het correcte antwoord aan
5. Klik op "Vraag Toevoegen"

### 3. Download je interactieve video
1. Klik op "Download Interactieve Video (ZIP)"
2. Je krijgt een ZIP-bestand met:
   - `index.html` - De interactieve video player
   - `video.xxx` - Je video bestand
   - `data.json` - De vragen en antwoorden

### 4. Gebruik in Rise 360
1. Open Rise 360
2. Voeg een "Code Block" toe
3. Upload het ZIP-bestand
4. Of: pak het ZIP uit en upload alleen de bestanden

### 5. Gebruik in een LMS
1. Pak het ZIP bestand uit
2. Upload alle bestanden naar je LMS
3. Link naar `index.html`

## 🎯 Wat kan de tool?

### ✅ Wel mogelijk:
- Meerkeuze vragen toevoegen op elk moment in de video
- 2-4 antwoordopties per vraag
- Automatisch pauzeren bij vragen
- Feedback op antwoorden (goed/fout)
- Score bijhouden
- Eindscherm met resultaat
- Video opnieuw bekijken

### ❌ Nog niet mogelijk (komt later):
- Meerkeuze vinkvragen (meerdere antwoorden)
- Hotspot vragen
- Open vragen
- Video's opslaan in de tool

## 💡 Tips

### Video optimaliseren voor Rise 360
- Gebruik MP4 formaat
- Houd de bestandsgrootte onder 500 MB
- Gebruik H.264 codec voor beste compatibiliteit

### Goede vragen maken
- Plaats vragen op logische momenten
- Geef duidelijke feedback bij foute antwoorden
- Test je video voordat je hem publiceert

### Video's comprimeren
Als je video te groot is, gebruik dan:
- HandBrake (gratis, voor Mac/Windows/Linux)
- Online compressors zoals CloudConvert
- Kies een lagere resolutie (720p is vaak voldoende)

## 🔧 Technische details

### Browser vereisten
- Moderne browser (Chrome, Firefox, Safari, Edge)
- JavaScript enabled
- Geen extra plugins nodig

### Bestandsformaten
- **Video**: MP4, WebM, OGG
- **Export**: ZIP bestand
- **Data**: JSON formaat

### Waar wordt data opgeslagen?
- Nergens! Alles gebeurt in je browser
- Je video wordt NIET geüpload naar een server
- Alleen het ZIP-bestand dat je download bevat je video

## 🐛 Problemen oplossen

### De tool laadt niet
- Controleer of GitHub Pages correct is geactiveerd
- Wacht 2-3 minuten na het activeren
- Ververs de pagina (Ctrl+F5 / Cmd+Shift+R)

### Video speelt niet af
- Controleer of je browser het video formaat ondersteunt
- Probeer een MP4 bestand
- Check of de video niet corrupt is

### Export werkt niet
- Controleer of je minimaal 1 vraag hebt toegevoegd
- Probeer een kleinere video (< 500 MB)
- Test in een andere browser

### In Rise 360 werkt het niet
- Pak het ZIP bestand eerst uit
- Upload alle bestanden individueel
- Zorg dat `index.html`, `video.xxx` en `data.json` in dezelfde map staan

## 📝 Licentie

Dit project is volledig gratis te gebruiken voor educatieve doeleinden.

## 🎉 Volgende versies

In toekomstige versies komen:
- Meerkeuze vinkvragen (meerdere correcte antwoorden)
- Hotspot vragen (klikbare gebieden in de video)
- Thema's en styling opties
- Video timestamp preview

## 💬 Vragen of feedback?

Heb je vragen of suggesties? Gebruik het "Issues" tabblad in je GitHub repository om notities te maken voor jezelf.

---

**Veel plezier met het maken van interactieve video's!** 🎬✨
