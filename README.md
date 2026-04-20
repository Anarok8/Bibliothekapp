📚 Library TalesLibrary Tales ist eine liebevoll gestaltete, blitzschnelle Web-App zur Verwaltung der familieneigenen Kinderbibliothek. Sie ist speziell für das iPad optimiert und funktioniert als "Single-File-App" komplett im Browser, ohne dass ein Backend oder eine externe Datenbank benötigt wird.Alle Daten, Bilder und Sprachaufnahmen bleiben zu 100 % lokal und privat auf dem Gerät!

🌱 Hinweis: Dieses Projekt befindet sich aktuell noch in den Kinderschuhen und wird als Herzensprojekt stetig weiterentwickelt. Feedback und neue Ideen sind jederzeit willkommen!

✨ Features
📦 Privat & Lokal: Keine Cloud, keine Abos, kein Tracking. Die App speichert alle Daten lokal im Browser deines iPads (IndexedDB).
📷 ISBN-Scanner: Neue Bücher blitzschnell per Kamera-Barcode-Scan hinzufügen. Die Metadaten und Cover werden automatisch über Google Books / Open Library geladen.
👨‍👩‍👧‍👦 Familien-Profile: Lege Lese-Profile für alle Familienmitglieder an. Verleihe Bücher oder halte fest, wer welches Buch gerade liest.
🏆 Lese-Statistiken: Tracke Lesestatus ("Neu", "Liest", "Fertig"), sammle wöchentliche "Reading-Streaks" und markiere Lieblingsbücher mit Sternen.
🎙️ Sprachnotizen: Kinder können ihre Gedanken und Geschichten zu einem Buch direkt in der App als Audio-Memo aufnehmen und speichern.
🎨 Modernes Design: Ein kindgerechtes, aber hochmodernes UI mit Bento-Grids, "Squircles" (weichen Abrundungen), sanften Animationen und einem Konfetti-Regen beim Auslesen eines Buches.
📱 PWA-Ready: Lässt sich über Safari via "Zum Home-Bildschirm" wie eine native, echte App installieren (ohne störende Browser-Leisten).
🛠️ Technologie-StackDas Besondere an Library Tales: Die komplette App besteht aus einer einzigen Datei (index.html).Frontend: HTML5, Tailwind CSS (via CDN)Logik: Vanilla JavaScript (ES6+)Datenbank: IndexedDB (Version 4, inklusive Blob-Storage für Audio-Aufnahmen und komprimierte Bilder)Scanner: html5-qrcode (via CDN)Audio: Web Audio API & MediaRecorder API
🚀 Installation & NutzungDie App muss nicht klassisch "installiert" werden. Du kannst sie einfach über GitHub Pages hosten:Lade die index.html in ein öffentliches GitHub-Repository hoch.Aktiviere GitHub Pages in den Repository-Einstellungen (auf den main Branch setzen).Öffne den generierten Link (z.B. https://dein-name.github.io/library-tales/) im Safari-Browser auf deinem iPad.Tippe in Safari auf das Teilen-Symbol und wähle "Zum Home-Bildschirm".Fertig! Du kannst die App nun im Vollbildmodus über das App-Icon auf deinem iPad starten.💾 Backups & SynchronisationDa Library Tales keine Cloud-Datenbank nutzt, gibt es ein integriertes Backup-System:Unter 
⚙️ Einstellungen kannst du deine gesamte Bibliothek (inklusive aller Bücher, Personen, Lesestatus und Sprachaufnahmen) als .json-Datei exportieren.Speichere diese Datei z.B. in deinem iCloud Drive.Auf einem anderen Gerät kannst du diese Datei einfach wieder importieren.
🔒 DatenschutzLibrary Tales sammelt keine Telemetriedaten.Die Kamera wird ausschließlich lokal im Browser genutzt, um Barcodes auszulesen. Es werden keine Videodaten an Server gesendet.Sprachaufnahmen werden über das Mikrofon des Geräts aufgenommen und als lokaler Blob in der IndexedDB deines Browsers gespeichert.Externe Anfragen finden lediglich statt, um Buchcover und Metadaten (Titel, Autor) anhand einer gescannten ISBN von Google Books oder Open Library abzurufen.

Gestaltet mit ❤️ für kleine und große Leseratten.
