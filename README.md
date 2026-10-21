# Privatlivspolitik for LUMMI-appen

Den gældende privatlivspolitik udgives med GitHub Pages: https://lummi-systems.github.io/privatlivspolitik/

Politikken står i `index.md`. Hver ændring committes, så Git-historikken viser alle tidligere versioner.

## Sådan opdateres politikken

1. Ret teksten i `index.md`.
2. Hæv versionsnummeret og opdatér "Gældende fra" og "Senest opdateret" øverst i `index.md` (format `dd-MM-yyyy`).
3. Tilføj en linje i tabellen i `versionshistorik.md`.
4. Commit med en besked, der beskriver ændringen, og push til `main`. GitHub Pages bygger siden automatisk.

## GitHub Pages

Settings → Pages → Build and deployment → Source: "Deploy from a branch", branch `main`, mappe `/ (root)`.
