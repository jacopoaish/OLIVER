# Oliver Guacamayo

Tutor di inglese con cui si parla a voce. Il nome viene dal guacamayo, il pappagallo ara: l'uccello che parla. Oliver risponde come una persona vera, corregge spiegando la regola e la "trappola italiana", insegna pronuncia, abilità di conversazione e concetti di PNL, e ricorda i progressi da una sessione all'altra.

Il corso strutturato (test, livelli, ripasso) è un'app separata, **Oliver Tero**: https://claude.ai/artifact/JKnwbfHjyAXpiYZbiq75vV

App pubblicata (privata, apribile dal proprio account claude.ai): https://claude.ai/artifact/KbYTP7WGnfzG3F1VNB9q3D

## Cosa fa

- **Sessioni a voce**: tocchi il microfono, parli in inglese, Oliver risponde e legge ad alta voce la risposta.
- **Correzioni che insegnano**: per ogni errore mostra la frase sbagliata, quella giusta, la regola e perché un italiano tende a sbagliarla (massimo 2 per turno; modalità *strict* e *flow* disponibili).
- **Spiegazioni**: i pulsanti "Perché?" e "In italiano" chiedono una mini-lezione o la spiegazione in italiano.
- **Pronuncia, conversazione, PNL**: ogni tanto Oliver aggiunge un consiglio di articolazione (con IPA), una tecnica di conversazione o uno schema di PNL legato a quello che hai detto.
- **Modalità**: conversazione libera, role play, dibattito, racconto, grammatica, drill sugli errori, laboratorio PNL.
- **Report di fine sessione**: cosa hai fatto bene, errori, regole del giorno, parole nuove, focus per la prossima volta e profilo aggiornato.
- **Memoria**: il profilo (errori ricorrenti, regole da ripassare, parole in corso) viene usato in automatico all'inizio della sessione successiva.
- **Quaderno**: archivio di errori, regole, parole (con pronuncia) e storico delle sessioni.

## Come funziona

`index.html` è un'unica pagina pubblicata come Artifact su claude.ai e usa le funzioni della piattaforma:

| Funzione | Uso |
| --- | --- |
| `sample` | risposte di Oliver e report, sull'account Claude di chi usa l'app |
| `dictation` | dettatura vocale in inglese (Chrome / app desktop) |
| `tts` | voce di Oliver (in alternativa la sintesi vocale del browser) |
| `db` + `user` | profilo e sessioni salvati in privato per ogni utente |

Sui dispositivi dove la dettatura non è disponibile (Safari, app mobile) si scrive oppure si usa il microfono della tastiera. Nella pagina Profilo c'è anche il prompt completo di Oliver, da copiare nella modalità vocale dell'app Claude.

Per aggiornare l'app: modificare `index.html` e ripubblicarlo sullo stesso Artifact.
