[Italiano](https://github.com/LorenzoAlgeri/LorenzoAlgeri/blob/main/README.it.md)

# Lorenzo Algeri

I'm a 23 year old full-stack developer in Milan. At work I do IT support, and I build the internal tools on my own with Claude Code: a revenue tool, a booking app, digital business cards. I also build personal projects and projects for clients. Next I want to work in a team that builds agents and developer tools, close to the people who use them.

Each repo below is a cut-down copy of something I built, and you can run it in 5 minutes.

## Things I built with Claude

- [email-triage-eval](https://github.com/LorenzoAlgeri/email-triage-eval): Claude reads the emails of a shared inbox and plain Python rules decide who handles them. The original got 8 out of 8 on emails the prompt had never seen. That is only 8 emails, and the dataset is not published.
- [docs-index-for-agents](https://github.com/LorenzoAlgeri/docs-index-for-agents): an index the agent reads before opening any file, plus a script that checks it. On my folders it covered 88% of the files on 20 Nov 2026. The rest had slipped out of the indexes, so the rule "update the index when you change docs" doesn't hold on its own.
- [excel-parity-check](https://github.com/LorenzoAlgeri/excel-parity-check): recalculates a generated Excel file and compares it with the database. In the real tool it found 48 unexplained cells that the old checks had passed. I haven't measured the time it saves or the errors it keeps out of production.
- [safe-sheet-sync](https://github.com/LorenzoAlgeri/safe-sheet-sync): syncs a spreadsheet into a record store with a dry run, updates that never erase data and a restore from saved versions. In the original app, the first import overwrote 6 of 6 existing cards, and all 6 came back from the version history. This copy hasn't been run side by side with the original.

## What I use

TypeScript, React, Next.js, Tailwind, shadcn/ui, Supabase, Drizzle ORM, NestJS, Turborepo, Python. Claude Code with skills, subagents, hooks and MCP servers.

## Contact

[LinkedIn](https://www.linkedin.com/in/lorenzo-algeri-240143194)
