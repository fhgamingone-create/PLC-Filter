PLC Filter iPhone PWA

Dateien:
- index.html
- manifest.webmanifest
- service-worker.js
- icon-192.png
- icon-512.png
- apple-touch-icon.png

Wichtig:
Diese App muss über HTTPS geöffnet werden, damit sie auf dem iPhone als PWA
zum Home-Bildschirm hinzugefügt werden kann und der Offline-Modus funktioniert.

Einfachste Veröffentlichung:
1. Den Inhalt dieses Ordners bei einem statischen Webhost hochladen, z. B. Netlify Drop oder GitHub Pages.
2. Die erzeugte https://... Adresse in Safari auf dem iPhone öffnen.
3. In Safari auf Teilen tippen.
4. "Zum Home-Bildschirm" auswählen.
5. Danach startet "PLC Filter" wie eine eigene App.

Datenspeicherung:
- Die Datensätze liegen lokal im Browser/App-Speicher des iPhones.
- CSV-Export erzeugt eine PLC-Filter.csv.
- CSV-Import kann eine PC-CSV wieder einlesen.
- Durch Löschen der Website-Daten auf dem iPhone können lokale Datensätze verloren gehen.
  Daher regelmäßig CSV exportieren.
