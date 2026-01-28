# Aikido Techniken Lern-App

Progressive Web App zum Lernen von Aikido-Techniken nach DAB-Prüfungsordnung.

🌐 **Live-App:** https://jorgekrey-aikikai.github.io/Aikido-DAB/

## Features

✅ Karteikarten-System mit Aufdeckfunktion  
✅ Filter nach Gürtelfarben (Gelb/Orange/Grün/Blau/Braun)  
✅ 3-Stufen-Bewertung: "Kann ich" / "Geht so" / "Katastrophe"  
✅ **Shuffle-Modus** – Zufällige Reihenfolge zum besseren Lernen  
✅ **Prüfungsmodus** – Realistische Simulation mit Auswertung  
✅ **Übungshistorie** – Warnung bei >30 Tagen ohne Übung  
✅ Direkte YouTube-Links mit Zeitmarkern  
✅ Fortschritt wird lokal gespeichert  
✅ Handy-optimiert & offline-fähig  

## Nutzung

### Lernen
1. Wähle Gürtelfarbe
2. **🔀 Shuffle** für zufällige Reihenfolge
3. Technik antippen → Lösung erscheint
4. Bewerte dein Können (✓ / ~ / ✗)
5. Videos bei Bedarf anschauen

### Prüfungsvorbereitung
1. Gürtelfarbe wählen
2. **📝 Prüfung** aktivieren
3. Alle Techniken durchgehen
4. Am Ende: Ergebnis mit Prozent-Score

### Als App auf dem Handy
**Chrome (Android):**
- Menü → "Zum Startbildschirm hinzufügen"
- Icon erscheint, öffnet wie native App

**Safari (iOS):**
- Teilen → "Zum Home-Bildschirm"

## Technische Details

- Reine HTML/CSS/JavaScript
- Keine Installation erforderlich
- Daten: CSV (Tab-separated)
- Speicher: localStorage (bleibt im Browser)
- Open Source

## Datenstruktur

Die `techniken.csv` muss folgende Spalten haben (Tab-getrennt):

1. Technik
2. Variation
3. Angriff, japanischer Name
4. Angriff, deutsche Beschreibung
5. Farbprüfung
6. Karl Ruben (Aikikai) – Video-URL
7. The Art of Aikido – Video-URL

## Updates

**Daten aktualisieren:**
1. Excel/CSV bearbeiten
2. Auf GitHub: `techniken.csv` ersetzen
3. Nach 1-2 Minuten live

**App aktualisieren:**
1. `index.html` bearbeiten
2. Auf GitHub hochladen
3. GitHub Pages aktualisiert automatisch

---

**Erstellt für:** Deutscher Aikido Bund (DAB) Prüfungen  
**Lizenz:** Open Source  
**Kontakt:** [Dein Aikido-Verein]
