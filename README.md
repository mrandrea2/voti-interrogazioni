# Voti interrogazioni · Liceo Galilei

Toolkit per assegnare il voto delle interrogazioni orali di Scienze motorie e sportive (prof. Andrea Bertelli).

- Griglia: A, B, C (tre domande, 0–2), D linguaggio (0,5–2), E collegamenti (0,5–2). Voto = somma, minimo 2.
- 5 studenti già pronti, se ne possono aggiungere altri.
- Registro: copia per Excel/registro, CSV, stampa/PDF; archivio delle interrogazioni.
- Dati solo nel browser (localStorage), nessun server, nessun cookie. Funziona anche offline.

Sito statico: `index.html`, nessuna build.

## Elenchi delle classi
- Pagina Registro → «Importa da Excel» (colonne Cognome e Nome; la classe è letta dal nome del foglio o del file) oppure «Incolla un elenco».
- Oppure un link `…/#classi=<base64>`: il frammento dopo # non arriva al server; gli elenchi vengono salvati solo nel browser.
- «Scegli gli interrogati» mostra la classe (già interrogati con il voto); «Estrai a caso» riempie i posti liberi con chi non è ancora stato interrogato.
- I nomi degli studenti NON sono nel codice (repository pubblico).
