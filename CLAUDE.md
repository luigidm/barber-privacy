# CLAUDE.md: barber-privacy

Repository **pubblico** delle informative privacy delle app dei saloni (GitHub Pages, una cartella per salone: `mario/`).
Lingua: italiano. Niente dati riservati qui. Istruzioni per un nuovo salone nel `README.md`.
- `mario/`: informativa privacy (URL nel tenant `privacyUrl` e sugli store) + `logo.jpg` (logo su nero per la pagina di conferma).
- `mario/assistenza/`: pagina di assistenza (URL di assistenza dell'App Store, link per eliminare l'account senza l'app richiesto da Google Play).
- `confermato/index.html`: pagina "Email confermata" comune a tutte le app (Site URL di Supabase Auth); con `?app=<nome>`
  mostra logo e "Torna all'app" (oggetto `APPS`), gestisce il link scaduto (`#error=`). Nuova app = riga in `APPS` + `logo.jpg`.
- Manuale completo del progetto: `barber-salon-mario/MANUALE.md`.

## Regola universale (vale per tutti i progetti di Luigi De Martino)
- Commit **a nome di Luigi De Martino** (`git config user.name "Luigi De Martino"`, `user.email "l.demartino18@gmail.com"`).
- **Nessuna** riga `Co-Authored-By`, `Claude-Session` o "Generated with Claude Code" in commit, PR o file.
