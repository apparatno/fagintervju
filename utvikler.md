# Fagintervju utvikler

## Introduksjon

I Apparat er vi så åpne og gjennomsiktige som mulig og det ønsker vi skal gjenspeiles helt fra starten av. Derfor legger vi her ut listen av spørsmål og snakkepunkter vi bruker
når vi har fagintervju, sånn at du kan lese deg opp på forhånd eller følge med underveis.

Det er viktig å bemerke at vi ikke går slavisk igjennom disse punktene fra A til Å, dokumentet er heller som en meny vi tar utgangspunkt i for å drive samtalen videre og hjelper
oss å holder styr på hva vi har og ikke har snakket om enda. Vi plukker ulike temaer og punkter ut i fra kandidatens bakgrunn og svar underveis i samtalen.

## 1.1 Tidsplan

**30 minutter fagprat**

- Fokus på å få i gang samtale der kandidat prater selvgående, fremfor "krysseksaminering" (spesielt for nyutdannede).
- Generelle spørsmål for alle kandidater, backend og frontend-spørsmål avhengig av type kandidat.

## 1.3 Generelle spørsmål

- Fortell om prosjekter/oppgaver du har vært involvert i, ref. CV (nyutdannede kan bruke skoleprosjekter)
- Rolle i nevnte prosjekter?
- Teknologier brukt i prosjekter?
- Om du får velge fra øverste hylle, hvilke teknologier kunne du tenkt deg å jobbe med?

### 1.3.1 Faginteresse

- Holder du deg oppdatert innenfor fag (teknologi, rammeverk, språk, arkitektur)?
- Leser du fagbøker eller blogger? Twitter?
- Har du en GitHub-konto? Hobbyprosjekter?
- Programmerer du på fritiden?
- Har du bidratt i noen open-source-prosjekter? (registrere bugs, sende inn pull requests)

### 1.3.2 Trivsel i arbeidet

- Individuelt arbeid vs. samarbeid med andre
- Store prosjekt: Abstrahert arbeid på avgrensa fagområde
- Små prosjekt: Mer delaktig i alle delene og fagområder

### 1.3.3 Metodikk

- Pragmatisk vs. perfeksjonistisk tilnærming til løsninger. Hvor godt er godt nok?
- Agile metoder i prosjektgjennomføring?
  - SCRUM, Kanban
  - Code review
  - QA
- Hva var du fornøyd med/ikke fornøyd med i nevnte prosjektene med tanke på gjennomføring?
- Hva ser du på som gode programmeringsvaner?
  - TDD
  - Unit-testing
  - Kodekommentarer
  - Refaktorering/optimalisering
  - Kodeanalyseverktøy
- Hva betyr «definition of done» for deg i sammenheng med IT-prosjekter?
- Kildekontrollsystemer?
  - Gode/dårlige ting med disse?

### 1.3.4 Arkitektur

- Har du hatt en rolle i forhold til arkitekturmessige valg/anbefalinger for en løsning/applikasjon?
- Har du interesse for planlegging og skissering av løsninger og integrasjoner mellom systemer eller foretrekker du å få ferdige oppgaver?
- Observerte du noen arkitekturmessig dårlige valg i nevnte prosjekt?

## 1.4 Backend-spørsmål (for backend-orienterte kandidater)

- Erfaring med relevante teknologier for backend-utvikling
- Tjenesteorientert arkitektur? REST? SOAP? gRPC?
  - HTTP Request/Response modell
- Språk? (Java, .NET/C#, NodeJS, C++, PHP)
  - Funksjonelle språk?
  - Hvilket språk er du mest komfortabel med?
- Skytjenester? (Azure, AWS, Google Cloud)?
  - VMWare
  - Automatisering (Terraform, Vagrant, Chef, Puppet)?
- Containers? Docker?
  - Kubernetes? Swarm?

### 1.4.1 Sikkerhet

- Har du implementert noen sikkerhetsmekanismer selv eller gjort konkrete tiltak?
- Websikkerhet: [CORS](https://developer.mozilla.org/en-US/docs/Glossary/CORS), [CSP](https://developer.mozilla.org/en-US/docs/Web/HTTP/CSP), [HSTS](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Strict-Transport-Security), TLS, Cookies (secure flag)
- Kjennskap til [OWASP Top 10](https://owasp.org/www-project-top-ten/)
- Vanlige sårbarheter: SQL Injection, Clickjacking, Cookie hijacking
- **Autentisering, OpenID Connect, OAuth2, JWT**
-

### 1.4.2 Design Patterns

- Creational Patterns (opprettelse av objekter)
  - Hvordan implementere Singleton Pattern?
- Structural Patterns (forhold mellom objekter)
- Behavioral Patterns (kommunikasjon mellom objekter)
- (Observer, State, Strategy etc.) Rammeverk?

### 1.4.3 Continuous Integration og Continuous Deployment

- Hva er CI? Hvorfor?
- Hva er CD?
- Verktøy?
  - TeamCity
  - Jenkins
  - Octopus Deploy
- Online verktøy: GitHub Actions, TravisCI, CircleCI

### 1.4.4 Dependency Injection

- Hva er DI? Hvilke fordeler gir det?
- Interfaces og separation of concerns
- Loosely Coupled Bindings

## 1.5 Frontend-spørsmål (for frontend/fullstack-orienterte kandidater)

### 1.5.1 Generelt

- Webteknologi generelt (CSS, HTML, JavaScript, HTTP (request/response))
- Verktøy
  - Kommandolinje?
  - Kjent med utviklerverktøy i nettleser?
- Device-testing?
- SEO?
- Workflow
  - Skisse (Sketch/Photoshop) -> HTML/CSS -> Impl?
  - Samarbeid med UX person?
  - Direkte prototyping i HTML/CSS? Styleguide?

### 1.5.2 JavaScript

- "Pure JS" - Klarer kandidaten seg uten biblioteker og rammeverk? Når bruke / ikke bruke?
- Biblioteker/rammeverk? (Angular, React, Vue, JQuery...)
- Moderne JavaScript? (ES6/2015, 20xx, Babel, transpilering, polyfills)
- Linting? (ESLint? JSHint?)
- Tooling, module bundling og bygg (npm, Grunt/Gulp/Webpack/Rollup)
- Testing/TDD (Karma, Mocha/Chai, Jasmine, Jest)
  - Mocking/stubbing (Sinon.JS)
- XHR/AJAX, REST-APIer, JSON
- Progressive web apps ([https://developers.google.com/web/progressive-web-apps/](https://developers.google.com/web/progressive-web-apps/))

### 1.5.3 CSS

- CSS3? CSS-animasjoner?
- Responsive design?
- Rammeverk? (Bootstrap, ZURB Foundation, ++). Fordeler og ulemper?
- CSS layout, grid-systemer? Flexbox?
- Preprosessering? (SASS/LESS)
- Progressive enhancement?
- Web fonts? Ikon-fonter? SVG?
- CSS-arkitektur?
  - OOCSS (Object Oriented CSS)
    - BEM (Block Element Modifier)
- CSS-organisering?
  - SMACSS (Scalable and Modular Architecture for CSS)

### 1.5.4 HTML

- HTML5?
- Universell utforming, WAI-ARIA? WCAG?
- DOM?

# Vedlegg

- [Design Patterns](./design_patterns.md)
