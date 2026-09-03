# NODO

Prototipo digitale giocabile di **NODO**, un gioco competitivo di associazione, costruzione e conquista di una rete di concetti.

## Come si gioca

I giocatori partono da un Tema centrale (es. TEMPO) e costruiscono insieme una mappa di parole collegate tra loro. Quella stessa mappa è anche un territorio da controllare: ad ogni turno si sceglie tra

- **Espandi** — associazione libera: aggiungi un nuovo Nodo collegato a uno esistente, diventa subito tuo.
- **Conquista** — associazione vincolata: ricevi due possibili relazioni semantiche (causa, opposto, fa parte di...), ne scegli una e dimostri che collega un tuo Nodo a un Nodo avversario. Se gli altri giocatori approvano, il Nodo passa sotto il tuo controllo.

Alla fine della partita vince chi controlla più Nodi.

Questo prototipo è pensato per essere giocato **pass-and-play**: un solo dispositivo passato tra i giocatori a turno, seduti allo stesso tavolo. Include timer opzionale per dare ritmo al tavolo, salvataggio automatico della partita in corso e varianti di regola configurabili in fase di setup (dimensione griglia, regola di adiacenza per la conquista).

## Giocare online

Se questa repository ha GitHub Pages attivo, il prototipo è giocabile direttamente dal browser, nessuna installazione richiesta.

## File

- `index.html` — l'intero prototipo (interfaccia, regole e logica di gioco), autosufficiente in un unico file.

## Stato del progetto

Prototipo V1 in fase di playtest — le regole non sono definitive. Feedback e osservazioni di gioco sono benvenuti tramite le Issue di questa repository.

## Licenza

© 2026 Michela Toschi — Tutti i diritti riservati. Vedi [LICENSE](LICENSE). La repository è visibile pubblicamente per permettere il playtest, ma non è open source: nessuna parte del gioco o del codice può essere riusata senza permesso.
