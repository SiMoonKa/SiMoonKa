## Simona Fichtnerová

Full-stack vývojářka. Navrhla, naprogramovala a sama provozuji **[Enynku](https://enynka.cz)** - českou platformu pro beauty profesionály s online rezervacemi, předplatným a platbami. **Od září 2026 běží naostro se skutečnými uživateli.**

Za půl roku od prázdného repozitáře do produkce: **1 200+ commitů**, kompletní vývoj, nasazení i provoz.

### Co jsem v Enynce postavila

- **Rezervace** - kalendář, kapacity, potvrzování, storno, ochrana proti dvojí rezervaci, minimální předstih
- **Platby** - Stripe (předplatné i jednorázové), webhooky, PDF faktury
- **Bezpečnost** - NextAuth, role, 2FA (TOTP), rate limiting přes Redis, CAPTCHA spouštěná podle rizika (OWASP)
- **Integrace** - ARES (ověření IČO), e-maily, CDN pro fotky
- **Automatizace** - 17 naplánovaných úloh: připomínky, expirace, úklid dat podle GDPR, hlídání domény a certifikátu
- **CS/EN** včetně českého skloňování (5. pád)

### Jak pracuji

- **Testy jako pojistka** - 1 400+ unit testů (Vitest) a 94 E2E scénářů (Playwright) na desktopu i mobilu. Každá změna jde přes pull request a CI v GitHub Actions.
- **Provoz** - Sentry, hlídání dostupnosti, denní zálohy s ověřenou obnovou. Nasazuji i několikrát denně.
- **Bezpečnost od začátku** - při auditech jsem našla a opravila např. stored XSS přes podvrženou příponu souboru nebo API, které vracelo víc údajů, než mělo.
- **AI jako kolega** - denně pracuji s Claude Code. Rozhoduji ale já a všechno, co jde do produkce, kontroluji a testuji.
- **Produkt, ne jen kód** - obchodní podmínky, GDPR, fakturace i DPH jsem řešila sama, takže chápu, proč se co staví.

### Technologie

`TypeScript` `Next.js 15` `React 19` `Node.js` `PostgreSQL` `Prisma` `Redis` `Tailwind CSS` `NextAuth` `Zod` `Stripe` `Vitest` `Playwright` `Docker` `GitHub Actions` `Railway` `Sentry`

Kód Enynky je soukromý, ale aplikaci si můžete vyzkoušet na **[enynka.cz](https://enynka.cz)** a ráda ukážu, jak funguje uvnitř. Ukázku mého kódu najdete v repozitáři **[cesky-vokativ](https://github.com/SiMoonKa/cesky-vokativ)**.

### Vzdělání

Vibecoding Akademie I. (10/2026, [ověřit certifikát](https://www.vibecoding-akademie.cz/certifikat/VC-7V3AX4)) a Vibecoding Basecamp (03/2026, [ověřit](https://www.vibecoding-akademie.cz/certifikat/VC-QE2RHZ)). Předtím 18 let v kvalitě a auditech v automotive (interní auditor ISO 9001 / IATF 16949).

### Hledám práci

Full-stack nebo frontend vývojářka, ideálně na dálku, na částečný úvazek nebo spolupráci na IČO.

- Web: [enynka.cz](https://enynka.cz)
- E-mail: fichtnerova.s@seznam.cz
- LinkedIn: [simona-fichtnerova](https://www.linkedin.com/in/simona-fichtnerova)
