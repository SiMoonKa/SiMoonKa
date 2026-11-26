## Simona Fichtnerová

Stavím a řídím týmy AI agentů. Každý agent má jednu roli, jasné hranice a nad sebou kontrolu. Já zadávám, kontroluji a schvaluji.

### Jak pracuji s agenty
- **Role místo jednoho univerzálního agenta** - kritik (fakta a pravidla textu), tester (funkce na mobilu, počet kliků), bezpečák (knihovny, chyby, klíče), údržbář (zálohy, plánované úlohy, expirace), měřič (co přivedlo lidi). Čtou a hlásí, nic sami nemění.
- **Víc agentů najednou bez kolizí** - každý v cloudu na vlastní větvi `agent/<úkol>`, smí měnit jen svou zónu souborů, odevzdá pull request. Kontrola, pak spojení do vývojové větve, na veřejnost až po schválení. Pravidla mají agenti zapsaná v repozitáři a čtou si je sami.
- **Poučení se zapisuje** - když agent začal ze staré verze a jeho změna šla do konfliktu, převedla jsem ji ručně a doplnila pravidlo „vždy začni z aktuální větve“.
- **Člověk rozhoduje** - nic nejde ven bez mého schválení.

### Automatizace
- **n8n** - propojení RSS, Gemini, e-mailu a Google Sheets, upozornění na chybu workflow
- **Plánované úlohy v cloudu** - týdenní kontrola dostupnosti, certifikátu a knihoven s upozorněním do mobilu

### Pojistky
Automatické testy (Vitest, Playwright), CI v GitHub Actions, pre-commit kontroly, zálohy s ověřenou obnovou.

### Technologie
`Claude Code` `n8n` `Gemini` `TypeScript` `Next.js` `React` `Node.js` `PostgreSQL` `Python` `Vitest` `Playwright` `Docker` `GitHub Actions`

### Předtím
18 let v kvalitě a auditech v automotive.

### Hledám práci
AI automatizace a agenti, na dálku, na zkrácený úvazek nebo na IČO. E-mail: fichtnerova.s@seznam.cz · [LinkedIn](https://www.linkedin.com/in/simona-fichtnerova)
