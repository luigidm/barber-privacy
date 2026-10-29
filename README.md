# barber-privacy

Informative privacy delle app di prenotazione dei saloni, pubblicate con GitHub Pages
(Settings → Pages → Deploy from a branch → `main` / root).

- Una cartella per salone con `index.md` (es. `mario/` → `https://<utente>.github.io/barber-privacy/mario/`).
- Nuovo salone: copiare `mario/index.md` in una cartella nuova, cambiare la sezione 1 (titolare), i tempi di
  conservazione (`retention_days` del salone) e togliere le funzioni spente; aggiungere la riga in `index.md`.
- L'indirizzo della pagina va nel tenant dell'app (`privacyUrl`) e nella scheda degli store.
- Repository **pubblico** di proposito (GitHub Pages gratis): niente dati riservati qui.
- `confermato/` = pagina aperta dal link di conferma dell'email, comune a tutte le app (Site URL di Supabase Auth).
  Con `?app=<nome>` (tenant `confirmUrl`) mostra logo e pulsante "Torna all'app": nuova app = riga in `APPS` di
  `confermato/index.html` + `logo.jpg` nella sua cartella (logo su nero, ~560 px).

