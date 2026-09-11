# Hike – ohne PC zur APK

## 1. GitHub im Browser
Auf dem Android-Handy github.com öffnen und ein kostenloses Konto erstellen/anmelden.

## 2. Neues Repository
`+` → New repository → Name: `hike-lernen-mit-keno` → Public oder Private → Create repository.

## 3. Dateien hochladen
Im Repository: Add file → Upload files.
Die Dateien aus diesem Projekt müssen mit ihrer Ordnerstruktur hochgeladen werden.
Wichtig: Eine ZIP-Datei allein reicht für GitHub Actions nicht aus; GitHub muss die Projektdateien sehen.

## 4. Build starten
Nach dem Upload: Actions → „Hike APK bauen“ → Run workflow.

## 5. APK holen
Nach erfolgreichem Lauf den Workflow öffnen → Artifacts → `Hike-Lernen-mit-Keno-APK`.
Die enthaltene `app-debug.apk` auf das Handy herunterladen und öffnen.

## Hinweis
Android kann beim ersten Installieren fragen, ob Installationen aus dieser Quelle erlaubt werden dürfen. Nur dann erlauben, wenn du der Quelle vertraust.
