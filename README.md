# Interactieve Video Editor - NIEUWE FEATURES! 🎉

## ✨ Wat is er nieuw?

### 1. Custom Feedback per Vraag
Je kunt nu **zelf de feedback teksten instellen** voor elke vraag:
- **Correct feedback**: Wat zie je bij een goed antwoord?
- **Incorrect feedback**: Wat zie je bij een fout antwoord?

**Voorbeelden:**
- Correct: "Uitstekend! Je begrijpt het concept!" 
- Incorrect: "Niet helemaal, kijk nog eens naar minuut 2:30"

### 2. Preview Functie 🎬
Test je interactieve video **direct in de browser** voordat je exporteert!
- Klik op "▶️ Preview Interactieve Video"
- Test alle vragen en feedback
- Bekijk je score
- Opnieuw proberen of sluiten

## 🚀 Hoe gebruik je dit?

### Stap 1: Upload Video
1. Klik op "📹 Selecteer Video"
2. Kies een video bestand
3. De video wordt geladen en je ziet de informatie

### Stap 2: Voeg Vragen Toe
Voor elke vraag vul je in:
1. **Tijdstempel** - Wanneer moet de vraag verschijnen? (in seconden)
2. **Vraag** - De vraag zelf
3. **Feedback bij correct** - Wat zie je bij een goed antwoord?
4. **Feedback bij fout** - Wat zie je bij een fout antwoord?
5. **Antwoorden** - 2-4 antwoordopties
6. **Vink het juiste antwoord aan**
7. Klik "➕ Vraag Toevoegen"

**Voorbeeld:**
```
Tijdstempel: 45
Vraag: Wat is de hoofdfunctie van mitochondriën?
Correct feedback: Perfect! Je hebt goed opgelet bij de uitleg over celbiologie.
Incorrect feedback: Kijk nog eens terug naar 0:30 waar we dit bespreken.

Antwoorden:
☑️ Energie productie (ATP)
○ DNA replicatie
○ Eiwit synthese
○ Cel divisie
```

### Stap 3: Preview Je Video
1. Klik op "▶️ Preview Interactieve Video" 
2. De video start in een volledig scherm modal
3. Test alle vragen:
   - Video pauzeert automatisch bij vragen
   - Selecteer een antwoord
   - Klik "Controleer"
   - Zie je custom feedback!
   - Klik "Ga Verder"
4. Aan het einde zie je je score
5. Probeer opnieuw of sluit de preview

### Stap 4: Exporteer
1. Als alles goed is, klik "💾 Download ZIP"
2. Je krijgt een ZIP met:
   - index.html (de interactieve player)
   - video.xxx (je video)
   - data.json (vragen en feedback)
3. Upload naar Rise 360 of LMS

## 📝 Tips voor Goede Feedback

### Correcte Antwoorden:
- ✅ "Uitstekend! Dit toont aan dat je het principe begrijpt"
- ✅ "Perfect! Je hebt de kernpunten goed onthouden"
- ✅ "Goed gedaan! Dit is inderdaad de beste aanpak"

### Foute Antwoorden:
- ✅ "Niet helemaal. Kijk nog eens naar het voorbeeld op 2:15"
- ✅ "Bijna! Let op het verschil tussen X en Y"
- ✅ "Probeer opnieuw. Hint: denk aan wat we zeiden over..."

### Feedback Best Practices:
1. **Wees specifiek** - Verwijs naar momenten in de video
2. **Wees positief** - Ook bij foute antwoorden
3. **Geef hints** - Help de leerder zonder direct het antwoord te geven
4. **Varieer** - Gebruik verschillende feedback teksten voor verschillende vragen

## 🎯 Workflow voor Ontwikkelaars

### Ontwikkel → Test → Exporteer
1. **Ontwikkel**: Maak je vragen met custom feedback
2. **Test**: Gebruik Preview om alles te testen
3. **Itereer**: Pas feedback aan waar nodig
4. **Exporteer**: Als alles perfect is, download de ZIP
5. **Implementeer**: Upload naar Rise 360 of LMS

### Test Checklist:
- [ ] Verschijnen vragen op de juiste momenten?
- [ ] Is de feedback duidelijk en behulpzaam?
- [ ] Werken alle antwoorden correct?
- [ ] Is de score berekening correct?
- [ ] Ziet het eindscherm er goed uit?

## 🆕 Versie Verschillen

### Versie 1.0 (Origineel):
- Vaste feedback teksten
- Geen preview
- Direct exporteren

### Versie 2.0 (Nieuw):
- ✨ Custom feedback per vraag
- ✨ Preview functie
- ✨ Betere workflow

## 💡 Voorbeelden van Gebruik

### Voorbeeld 1: Training Video
```
Vraag: "Wat is de eerste stap bij het oplossen van een klacht?"
Correct: "Precies! Actief luisteren is de basis van goede klantenservice."
Incorrect: "Vergeet niet: we beginnen altijd met luisteren. Zie 1:20 voor meer uitleg."
```

### Voorbeeld 2: Product Demo
```
Vraag: "Welke knop gebruik je om een nieuw project te starten?"
Correct: "Top! Je hebt de interface goed begrepen."
Incorrect: "Kijk nog eens naar het dashboard dat we net lieten zien."
```

### Voorbeeld 3: Compliance Training
```
Vraag: "Is deze situatie volgens de regels toegestaan?"
Correct: "Correct! Je hebt de regelgeving goed toegepast."
Incorrect: "Let op artikel 3.2 dat we bespraken in het begin van de video."
```

## 🔧 Technische Details

### Bestanden Nodig:
- **editor.html** - De editor tool (upload dit naar GitHub)
- **player.html** - De player template (upload dit ook naar GitHub)

### Browser Vereisten:
- Moderne browser (Chrome, Firefox, Edge, Safari)
- JavaScript enabled
- Geen plugins nodig

### Bestandsformaten:
- Video: MP4, WebM, OGG
- Export: ZIP bestand
- Max aanbevolen: 500MB voor Rise 360

## ❓ Veelgestelde Vragen

**Q: Kan ik verschillende feedback geven per fout antwoord?**
A: Momenteel is de feedback per vraag (1x correct, 1x incorrect). Alle foute antwoorden krijgen dezelfde incorrecte feedback.

**Q: Werkt de preview ook zonder internet?**
A: Ja! De preview werkt volledig lokaal in je browser.

**Q: Kan ik de feedback later nog aanpassen?**
A: Helaas niet in de editor. Je moet de vraag verwijderen en opnieuw toevoegen met nieuwe feedback.

**Q: Hoeveel vragen kan ik toevoegen?**
A: Technisch onbeperkt, maar houd het praktisch. 5-10 vragen per video is ideaal.

**Q: Werkt dit ook in Rise 360?**
A: Ja! Upload het geëxporteerde ZIP in een Rise 360 Code Block.

## 🎉 Veel Succes!

Je hebt nu alle tools om professionele interactieve video's te maken met custom feedback en preview functionaliteit. 

**Happy creating!** 🚀
