# Note ARTEFATTO

Copia delle note già inserite nell'head di ogni app. Data e ora sono quelle del caricamento dei file: correggile con la data reale dell'ultima modifica.

## agenda/index.html

```
<!-- ARTEFATTO
Nome: Agenda
Icona: 🗓️
Scopo: Organizzare attività e impegni con to do e calendario.
Funzioni:
- Scheda to do: elenco spuntabile a scorrimento, casella di testo in basso per scrivere
- Attività con data e ora in campi separati e non vincolanti: senza data nessuna scadenza
- Matita accanto a ogni attività per richiamarla e modificarla
- Agenda mensile con vista giorni, settimane, mesi o anni
- Pallino rosso sui giorni con attività da fare o in scadenza
- Dati salvati sul dispositivo (localStorage)
Ultima modifica: 2026-11-22 11:53 - versione inserita nel sito
-->
```

## qrcode/index.html

```
<!-- ARTEFATTO
Nome: Generatore QR
Icona: ▦
Scopo: Creare un QR code che inserisce nome utente e password in automatico.
Funzioni:
- Campi Nome utente e Password: il QR codifica nome + TAB + password + INVIO
- Testo sinistra e Testo destra, in verticale ai lati del QR
- Genera QR, con bordo rosso sui campi vuoti
- Condividi, salva come JPG e stampa
- Carattere corsivo "Great Vibes" per la scritta in alto (richiede internet per font e libreria QR)
Ultima modifica: 2026-11-22 11:53 - versione inserita nel sito
-->
```

## scheda-palestra/index.html

```
<!-- ARTEFATTO
Nome: Scheda palestra
Icona: 🏋️
Scopo: Seguire l'allenamento in palestra e registrare i progressi.
Funzioni:
- Scheda a 4 giorni: Upper Body A, Lower Body A, Upper Body B, Lower Body B
- Riscaldamento, esercizi con ripetizioni, stretching
- Sezioni Alimentazione e Monitoraggio
- Carica workout e azzera i valori di un giorno
- Ricerca rapida degli esercizi su Google, Instagram e YouTube
- Dati salvati sul dispositivo (localStorage)
Ultima modifica: 2026-11-22 11:53 - versione inserita nel sito
-->
```

## turni/index.html

```
<!-- ARTEFATTO
Nome: Turni
Icona: 📅
Scopo: Gestire turni e reperibilità a calendario, con ore e statistiche.
Funzioni:
- Selettori turno M, P, R, F/A e reperibilità Gr, Nr, GNR
- Reperibilità in rosso sul numero del giorno; orario modificabile per ogni singolo turno
- Riga fissa con THT (ore turni), THR (ore reperibilità) e THG (altre attività)
- Calcolatore con statistiche mensili su reperibilità e weekend impegnati
- Upload e download di file .mpt con tutte le attività
- Dati salvati sul dispositivo (localStorage)
Ultima modifica: 2026-11-22 11:53 - versione inserita nel sito
-->
```

## turni-schede/index.html

```
<!-- ARTEFATTO
Nome: Turni reparto
Icona: 👥
Scopo: Turni dell'intero reparto: una scheda per persona.
Funzioni:
- Una scheda per persona, con i turni di quella persona
- Area laterale a scomparsa per scegliere, rinominare ed eliminare le schede (con conferma)
- File unico con tutte le schede: upload e download, le schede mancanti si creano da sole
- Pulsante analisi statistica
- Stesse funzioni dell'app Turni dentro ogni scheda
- Dati salvati sul dispositivo (localStorage)
Ultima modifica: 2026-11-22 11:53 - versione inserita nel sito
-->
```

## turnipro/index.html

```
<!-- ARTEFATTO
Nome: TurniPro (anteprima)
Icona: ☁️
Scopo: Anteprima dell'app Turni con login Google e salvataggio online.
Funzioni:
- Stesse funzioni dell'app Turni
- Pulsanti Accedi con Google ed Esci
- Nell'anteprima login e salvataggio online sono simulati: manca ancora il collegamento reale a Firebase (piano Spark)
Ultima modifica: 2026-11-22 11:53 - versione anteprima inserita nel sito
-->
```

## appartamento-3d/index.html

```
<!-- ARTEFATTO
Nome: Appartamento, modello 3D
Icona: 🏠
Scopo: Visualizzare in 3D la pianta dell'appartamento al piano secondo.
Funzioni:
- Modello 3D con muri, aperture, terrazzi e arredi
- Viste: 3D libero, isometrica da sud-est, nord-est, nord-ovest e sud-ovest, dall'alto
- Trascina per ruotare, pizzica o scorri per zoomare, indicatore del nord
- Pianta in scala 1:200 su foglio A4
- Richiede internet per la libreria Three.js
Ultima modifica: 2026-11-22 11:53 - versione inserita nel sito
-->
```
