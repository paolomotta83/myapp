# I miei artefatti

- `index.html`: pagina elenco (menu a scomparsa + tendina info)
- una cartella per app, ognuna con il proprio `index.html` e la nota ARTEFATTO
- `_note/NOTE-ARTEFATTI.md`: copia di tutte le note (la cartella `_note` è ignorata dall'elenco)

## Aggiungere un artefatto
1. Crea una nuova cartella nella root (es. `mia-app/`)
2. Metti dentro `index.html` con questa nota nell'`<head>`:

```
<!-- ARTEFATTO
Nome: Mia app
Icona: 🧩
Scopo: A cosa serve, in una frase.
Funzioni:
- prima funzione
- seconda funzione
Ultima modifica: 2026-11-22 18:30 - cosa hai cambiato
-->
```
3. Carica su GitHub: l'elenco si aggiorna da solo.

Le cartelle che iniziano con `.` o `_` e `assets` vengono ignorate.
