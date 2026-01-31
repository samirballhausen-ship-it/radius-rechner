# Bilder ersetzen - Anleitung

Die 3 Fotos, die du mir geschickt hast, müssen jetzt hochgeladen werden:

## Schritt-für-Schritt:

1. **Die 3 Fotos speichern:**
   - Foto 1 (1.54 Linie mit Lineal) → speichern als `step1.jpg`
   - Foto 2 (Rote Linie = Linie A) → speichern als `step2a.jpg`
   - Foto 3 (Rote + Blaue Linie) → speichern als `step2b.jpg`

2. **In den Ordner kopieren:**
   ```bash
   cp PFAD/ZU/step1.jpg /c/Users/samir/radius-projekt/images/
   cp PFAD/ZU/step2a.jpg /c/Users/samir/radius-projekt/images/
   cp PFAD/ZU/step2b.jpg /c/Users/samir/radius-projekt/images/
   ```

3. **Pushen:**
   ```bash
   cd /c/Users/samir/radius-projekt
   git add images/
   git commit -m "Add real photos"
   git push
   ```

## ODER: Automatisch aus Screenshots erstellen

Wenn du die Originale nicht mehr hast, kann ich sie aus dem Plan-Bild erstellen.
