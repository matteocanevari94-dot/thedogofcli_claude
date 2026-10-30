# thedogofcli_claude

Questo repository contiene solo le **release** di thedogofcli_claude (mod per Claude Code): i pacchetti da installare e i file per verificarli. Non contiene sorgenti.

Le installazioni esistenti si aggiornano da sole all'avvio. Per una prima installazione scarica dall'ultima release:

- **Windows 11**: `thedogofcli_claude-VERSIONE-windows11.zip`, estrai tutto e apri **Installa Windows.cmd**;
- **Debian**: `thedogofcli_claude-VERSIONE-debian.tar.gz`, estrai e lancia `sh install.sh` con il tuo utente.

Ogni pacchetto ha accanto il suo `.sha256` e una firma `.sig` (RSA-3072, SHA-256). L'aggiornamento automatico installa un pacchetto solo se checksum, firma e manifesto interno sono validi.
