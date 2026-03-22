# 📚 Lernhub

Persönliche Sammlung interaktiver Lernübersichten für die Schule — gehostet via GitHub Pages, zugänglich von jedem Gerät.

## Fächer

Mathematik · Physik · Geschichte · Musik · Deutsch · Biologie · Religion · Astronomie · Englisch · Informatik · GRW

## Neue Übersicht hinzufügen

1. HTML-Datei in den passenden Fachordner legen (z.B. `mathe/quadratische-gleichungen.html`)
2. Pushen — fertig

GitHub Actions aktualisiert die Startseite automatisch. Das Datum wird aus dem Commit-Datum gelesen, der Titel aus dem Dateinamen.

## Einrichtung

### GitHub Pages
Settings → Pages → Branch: `main`, Ordner: `/ (root)` → Save

### GitHub Actions (einmalig)
Settings → Actions → General → Workflow permissions → **Read and write permissions** → Save

## Struktur

```
lernhub/
├── .github/workflows/update-index.yml  ← Auto-Update Workflow
├── generate-index.js                   ← Build-Script
├── index.html                          ← Startseite (auto-generiert)
├── mathe/
├── physik/
├── geschichte/
├── musik/
├── deutsch/
├── biologie/
├── religion/
├── astronomie/
├── englisch/
├── informatik/
└── grw/
```
