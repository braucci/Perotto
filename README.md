# Sfida al Calcolatore

Riproposizione, come webapp in un unico file HTML, del gioco matematico della
Olivetti Programma 101: giocatore e calcolatore sommano a turno un numero da 1 a 6
per raggiungere esattamente un obiettivo, senza poter ripetere l'ultimo numero
dell'avversario né il suo complementare a 7.

Grafica a tabellone ferroviario (palette Solari), nessuna dipendenza oltre ai font.

## Uso
Apri `index.html` nel browser (anche sul telefono). Scegli l'obiettivo, chi inizia
e il livello dell'avversario, poi «Nuova partita». Tasti 1–6 anche da tastiera.

## Struttura
- `Core` — motore di gioco puro (mosse lecite, analisi delle posizioni, scelta della mossa), con test automatici all'avvio
- il resto del file — interfaccia e animazione delle palette

Licenza MIT — B. Raucci
