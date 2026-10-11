# Ricarica Solare BYD – Llíria

Applicazione web per pianificare la ricarica dell'auto BYD ATTO 2 con fotovoltaico e batteria domestica.

## Funzioni principali
- PWA installabile su Android/iPhone
- Icona batteria dedicata per la schermata iniziale
- Calcolo automatico della perdita fissa e della potenza alla batteria in base alla corrente selezionata
- Posizione preimpostata su Llíria (Valencia) con dati solari caricati da Open-Meteo
- Simulazione oraria del bilancio fotovoltaico e batteria domestica

## Esecuzione locale
Apri `index.html` nel browser oppure usa un server statico leggero, ad esempio:

```bash
python -m http.server 8000
```

Poi visita `http://localhost:8000`.

## Installazione mobile
Su Android la pagina può essere installata tramite il prompt "Installa app" se il browser lo supporta. Su iPhone la procedura è tramite "Aggiungi alla schermata iniziale" del browser.
