# Micro Hobbies - Assets

Willkommen im offiziellen Asset-Repository für die **Micro Hobbies** App! 

Dieses Repository dient als schnelles und kostenloses Content Delivery Network (CDN) für die Vektorgrafiken (SVGs) der App. Anstatt Bilder lokal in der App zu speichern, lädt die Micro Hobbies App diese Grafiken dynamisch zur Laufzeit herunter. Das hält die App-Größe extrem klein und ermöglicht Updates der Icons, ohne dass ein neues App-Release im Store notwendig ist.

## So funktioniert's (Für Entwickler)

Wenn ein neues Hobby in die Firebase-Datenbank (Firestore) eingetragen wird, muss das entsprechende Icon zuerst hier hochgeladen werden.

1. Lade die `.svg` Datei in dieses Repository hoch.
2. Klicke auf die hochgeladene Datei und wähle **"Raw"**.
3. Kopiere die URL aus dem Browser (beginnt mit `https://cdn.jsdelivr.net/gh/...`).
4. Füge diese URL in der Firestore-Datenbank in das Feld `svgUrl` ein.

## Struktur
Aktuell liegen alle Dateien direkt im Hauptverzeichnis (Root), um die URL-Struktur so simpel wie möglich zu halten.

---
*Erstellt für das Micro Hobbies Flutter-Projekt.*
