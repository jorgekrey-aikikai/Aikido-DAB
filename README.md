# Aikido Techniken Lern-App

Progressive Web App zum Lernen von Aikido-Techniken mit Karteikarten-System.

## Features

- ✅ Karteikarten-System (klicken zum Aufdecken)
- ✅ Filter nach Gürtelfarben (Gelb/Orange/Grün/Blau/Braun)
- ✅ 3-Stufen-Bewertung: "Kann ich" / "Geht so" / "Katastrophe"
- ✅ Fortschritt wird lokal im Browser gespeichert
- ✅ Direkte Video-Links mit Zeitmarkern
- ✅ Handy-optimiert
- ✅ Funktioniert offline nach erstem Laden

## Installation auf GitHub Pages

### 1. GitHub Repository erstellen
1. Gehe zu https://github.com und logge dich ein
2. Klicke auf "New repository"
3. Name: z.B. `aikido-techniken`
4. Wähle "Public"
5. Klicke "Create repository"

### 2. Dateien hochladen
1. Im neuen Repository: Klicke "uploading an existing file"
2. Ziehe diese Dateien rein:
   - `index.html`
   - `techniken.csv`
3. Klicke "Commit changes"

### 3. GitHub Pages aktivieren
1. Gehe zu Repository → Settings → Pages
2. Bei "Source": Wähle "main" Branch
3. Klicke "Save"
4. Nach 1-2 Minuten ist die App online unter:
   `https://DEINNAME.github.io/aikido-techniken`

## Installation auf deiner Aikido-Website

### Variante A: Als Unterseite
1. Lade `index.html` und `techniken.csv` auf deinen Webserver
2. Speichere beide Dateien im gleichen Ordnung (z.B. `/techniken/`)
3. Fertig: `deine-aikido-seite.de/techniken/`

### Variante B: Als iFrame einbinden
Füge auf einer bestehenden Seite ein:
```html
<iframe src="/techniken/index.html" style="width:100%; height:800px; border:none;"></iframe>
```

## Updates durchführen

### Excel → CSV konvertieren
1. Öffne deine Excel-Datei
2. "Datei" → "Speichern unter"
3. Format: "CSV UTF-8 (durch Trennzeichen getrennt) (.csv)"
4. Speichern

### CSV auf GitHub hochladen
1. Gehe zu deinem GitHub Repository
2. Klicke auf `techniken.csv`
3. Klicke auf das Stift-Symbol (Edit)
4. Kopiere Inhalt der neuen CSV rein
5. Klicke "Commit changes"
6. Nach 1-2 Minuten ist die App aktualisiert

### Alternative: Excel direkt nutzen
Du kannst auch die Excel-Datei direkt konvertieren:
1. Öffne https://products.aspose.app/cells/de/conversion/xlsx-to-csv
2. Lade deine Excel hoch
3. Konvertiere zu CSV (Tab-delimited)
4. Lade die CSV-Datei auf GitHub hoch

## Nutzung

### Am Handy
1. Öffne die App im Browser
2. Optional: "Zum Startbildschirm hinzufügen" (funktioniert wie native App)

### Lernen
1. Wähle Gürtelfarbe oder "Alle"
2. Klicke auf Karte → zeigt Lösung (deutsche Beschreibung + Videos)
3. Bewerte dein Können:
   - ✓ Kann ich (grün)
   - ~ Geht so (orange)  
   - ✗ Katastrophe (rot)
4. Fortschritt wird gespeichert

### Statistik
Oben siehst du:
- Anzahl gefilterter Techniken
- Anzahl "Kann ich" / "Geht so" / "Katastrophe"

## Technische Details

- Reine HTML/CSS/JavaScript (keine Installation nötig)
- Daten: CSV (Tab-separated)
- Speicher: localStorage (bleibt im Browser gespeichert)
- Funktioniert auf: Desktop, Tablet, Smartphone

## Struktur der CSV-Datei

Die CSV muss folgende Spalten haben (Tab-getrennt):
1. Technik
2. Variation
3. Angriff, japanischer Name
4. Angriff, deutsche Beschreibung
5. Farbprüfung
6. Karl Ruben (Aikikai) [Video-URL]
7. The Art of Aikido [Video-URL]

## Support

Bei Fragen oder Problemen: Melde dich!
