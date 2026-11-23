[English](https://github.com/LorenzoAlgeri/LorenzoAlgeri#readme)

# Lorenzo Algeri

Ho 23 anni e faccio lo sviluppatore full-stack a Milano. Al lavoro faccio assistenza IT e costruisco da solo gli strumenti interni con Claude Code: un gestionale dei ricavi, un'app di prenotazione, i biglietti da visita digitali. In più faccio progetti miei e per clienti. Il prossimo passo che vorrei è lavorare in un team che costruisce agenti e strumenti per sviluppatori, a contatto con chi li usa.

Ogni repository qui sotto è una copia ridotta di qualcosa che ho costruito, e si prova in 5 minuti.

## Cosa ho costruito con Claude

- [email-triage-eval](https://github.com/LorenzoAlgeri/email-triage-eval): Claude legge le email di una casella condivisa e delle regole in Python decidono a chi vanno. L'originale ha fatto 8 su 8 sulle email che il prompt non aveva mai visto. Sono solo 8, e il dataset non è pubblicato.
- [docs-index-for-agents](https://github.com/LorenzoAlgeri/docs-index-for-agents): un indice che l'agente legge prima di aprire qualsiasi file, con uno script che lo controlla. Il 20 novembre 2026 sulle mie cartelle copriva l'88% dei file. Gli altri erano rimasti fuori dagli indici: la regola "aggiorna l'indice quando cambi la documentazione" da sola non tiene.
- [excel-parity-check](https://github.com/LorenzoAlgeri/excel-parity-check): ricalcola un file Excel generato e lo confronta con il database. Nello strumento originale ha trovato 48 celle inspiegate che i controlli di prima lasciavano passare. Quanto tempo fa risparmiare e quanti errori ferma prima della produzione non l'ho misurato.
- [safe-sheet-sync](https://github.com/LorenzoAlgeri/safe-sheet-sync): sincronizza un foglio di calcolo con un archivio di record, con un dry run, aggiornamenti che non cancellano mai dati e il ripristino dalle versioni salvate. Nell'app originale il primo import ha sovrascritto 6 biglietti esistenti su 6, e sono tornati tutti e 6 dalla cronologia delle versioni. Questa copia non l'ho mai fatta girare fianco a fianco con l'originale.

## Cosa uso

TypeScript, React, Next.js, Tailwind, shadcn/ui, Supabase, Drizzle ORM, NestJS, Turborepo, Python. Claude Code con skill, subagenti, hook e server MCP.

## Contatti

[LinkedIn](https://www.linkedin.com/in/lorenzo-algeri-240143194)
