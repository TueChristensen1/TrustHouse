# TrustHouse

## Projektets idé og business case

I det følgende beskrives projektets inceptionfase med inspiration fra Sommerville (2016) og Kruchten (2003). Projektet tager udgangspunkt i idéen om **TrustHouse**, en digital platform inspireret af tjenester som Trustpilot og Tripadvisor, men målrettet boligmarkedet. Platformen er udviklet med formålet om at give brugere mulighed for at anmelde og bedømme boliger, boligselskaber, lejlighedskomplekser og boligområder i Aalborg.

### Idé

Idéen bag TrustHouse udspringer af et ønske om at skabe større gennemsigtighed på boligmarkedet gennem brugergenereret viden og erfaring. Platformen skal fungere som et forum, hvor nuværende og tidligere beboere kan dele deres oplevelser af et bestemt sted, så potentielle tilflyttere får adgang til informationer, der ofte er vanskelige at finde gennem traditionelle kanaler såsom boligannoncer, boligadministrationsselskaber og ejendomsmæglere.

### Business case

Business casen bygger på et identificeret behov blandt boligsøgende, som ofte mangler indsigt i væsentlige forhold ved en bolig, før de flytter ind. Det gælder eksempelvis støjniveau, boligkvalitet, vedligeholdelse, materialevalg, naboskab, tryghed og lokalområdets karakter.

TrustHouse søger at imødekomme dette behov ved at fungere som en digital “nabo”, hvor brugernes anmeldelser og vurderinger kan bidrage til et mere nuanceret beslutningsgrundlag. Platformen er således tænkt som et beslutningsstøttende værktøj, der kan understøtte et mere informeret boligvalg.

### Afgrænsning

I den indledende brainstormfase arbejdede gruppen med en ambition om at udvikle TrustHouse som en fuldt funktionel platform med brugeroprettelse, søgefunktioner, anmeldelsessystem og dynamisk visning af boligdata. Efterhånden som projektet tog form, blev denne ambition dog justeret til en mere realistisk løsning, der i højere grad afspejlede eksamensopgavens omfang, tidsmæssige rammer og gruppens tekniske kompetencer.

Det endelige system består derfor af en statisk HTML- og CSS-prototype, der demonstrerer konceptet gennem udvalgte boligcases med tilhørende anmeldelser, ratings og informationssider. Fokus har ikke været på implementering af backend-funktionalitet, databaser eller JavaScript. I stedet har fokus været på design, informationsarkitektur, brugerflow, projektstyring, versionsstyring og dokumentation.

Projektet har derfor bevæget sig fra en overordnet abstraktion om en komplet digital platform til en konkret og realiserbar prototype. Resultatet er et designforslag til et IT-system, der illustrerer konceptets centrale funktioner og demonstrerer, hvordan TrustHouse kan bidrage til mere gennemsigtighed på boligmarkedet.

## Planlægning af projektet

Som en del af inceptionfasen blev Boehms W5HH-principper anvendt til at planlægge projektet og skabe et indledende strukturelt overblik over projektets mål, organisering og gennemførelse.

W5HH-principperne blev løbende genbesøgt gennem udviklingsforløbet. I takt med projektets udvikling blev analysen revideret og justeret, og nye refleksioner blev tilføjet for at sikre, at planlægningen fortsat afspejlede projektets aktuelle proces.

## Hvad vi konkret har lavet

Vi har oprettet et fælles GitHub-repository med navnet `trusthouse`. Repository’et bruges til at samle både kode og dokumentation.

Hjemmesiden består af en række statiske HTML-sider samt to CSS-filer:

- `index.html`
- `om.html`
- `soeg.html`
- `boligomraade.html`
- `kompleks.html`
- `toprated.html`
- `anmeldelse.html`
- `faq.html`
- `kontakt.html`
- `style.css`
- `frontpage.css`

Vi har derudover arbejdet med branches, commits, push, pull requests og merge. Det betyder, at vi ikke kun har lavet en hjemmeside, men også har arbejdet med en struktureret udviklingsproces, hvor ændringer laves i separate branches og først flettes ind i `main`, når de er gennemgået af den anden person.

## Beskrivelse af de enkelte sider

### Forside — `index.html`

Forsiden fungerer som indgangen til TrustHouse. Den præsenterer platformens formål og forklarer, at TrustHouse hjælper brugere med at få indsigt i boligområder og lejlighedskomplekser gennem anmeldelser og ratings.

Forsiden er gjort mere visuel med grønne farver, informationsbokse og en tydelig call-to-action, der leder brugeren videre til søgesiden. Forsiden bruger både `style.css` og `frontpage.css`, hvor `frontpage.css` er lavet specifikt til at forbedre forsidens visuelle udtryk.

### Om-side — `om.html`

Om-siden beskriver idéen bag TrustHouse og forklarer, hvorfor platformen kan være relevant for boligsøgende. Siden fungerer som en introduktion til projektets formål og problemstilling.

### Søgeside — `soeg.html`

Søgesiden viser, hvordan en bruger i en færdig version ville kunne søge efter boligområder eller lejlighedskomplekser. Da projektet er statisk, fungerer søgefeltet ikke teknisk, men siden viser en prototype med eksempelresultater.

### Boligområde-side — `boligomraade.html`

Denne side viser en eksempelprofil for et boligområde. Siden indeholder områdebeskrivelse, TrustScore og vurderinger af blandt andet tryghed, støjniveau, vedligeholdelse og beliggenhed.

### Kompleks-side — `kompleks.html`

Kompleks-siden viser en profil for et konkret lejlighedskompleks. Hvor boligområde-siden fokuserer på et større område, fokuserer denne side på en specifik ejendom. Siden indeholder information om boligtype, faciliteter, TrustScore og eksempelanmeldelse.

### Topratede områder — `toprated.html`

Denne side viser en statisk oversigt over bedst vurderede boligområder og lejlighedskomplekser. Formålet er at vise, hvordan TrustHouse kan give brugeren et hurtigt overblik over steder med høje vurderinger.

### Anmeldelsesside — `anmeldelse.html`

Anmeldelsessiden viser en formular, hvor brugere i en færdig version ville kunne skrive en anmeldelse. Formularen indeholder felter til boligområde, rating, kategori og anmeldelsestekst. Da prototypen er statisk, bliver data ikke gemt eller sendt.

### FAQ-side — `faq.html`

FAQ-siden indeholder ofte stillede spørgsmål om TrustHouse. Siden forklarer blandt andet, hvad TrustHouse er, hvordan anmeldelserne fungerer i prototypen, og hvilke informationer brugeren kan finde.

### Kontakt-side — `kontakt.html`

Kontakt-siden viser en simpel prototype på en kontaktside med kontaktoplysninger. Siden demonstrerer, hvordan brugeren i en færdig version ville kunne finde kontaktinformation eller sende en besked.

## Use case diagram

Use case diagrammet viser de centrale interaktioner mellem brugerne og TrustHouse. Diagrammet illustrerer blandt andet, hvordan en boligsøgende bruger kan søge efter boligområder, se boligprofiler og læse anmeldelser, mens en beboer/anmelder kan skrive en anmeldelse i en potentiel færdig version af systemet. Derudover er der gjort tanker omkring et eventuelt boligselskab, der kan integreres i systemet. Diagrammet kan ses i vores repo som PNG. 

## Activity diagram

Activity diagrammet viser....


## Arbejdsmetode: mellem plan-driven udvikling og Scrum-tilgang

I projektet har vi arbejdet med en kombination af plan-driven udvikling og Scrum-inspireret arbejdsform.

Med udgangspunkt i Sommervilles kapitel 2 kan vores proces forstås som relativt plan-driven, fordi vi på forhånd har defineret projektets overordnede idé, sider, struktur og afleveringskrav. Vi har ikke haft adgang til rigtige slutbrugere, som løbende kunne teste løsningen og give feedback. Derfor har processen ikke været fuldt agil i klassisk forstand.

På den baggrund minder dele af processen om en waterfall-lignende tilgang, hvor vi først har defineret idé og krav, derefter udviklet hjemmesidens sider, og til sidst arbejder med dokumentation, test og aflevering.

Samtidig har vi dog forsøgt at arbejde Scrum-inspireret, som beskrevet i Sommervilles kapitel 3. Vi har opdelt arbejdet i mindre sprints, brugt GitHub Projects som Scrum/Kanban-board og arbejdet med løbende opgaver, branches, pull requests og reviews. På den måde har vi forsøgt at skabe en iterativ arbejdsform, hvor projektet gradvist forbedres.

Vi kan derfor ikke sige, at vi arbejder fuldt agilt, da vi mangler en reel slutkunde eller brugergruppe at teste løsningen på. Ideelt set ville incremental development være oplagt til TrustHouse, fordi platformen kunne udvikles og forbedres gennem feedback fra faktiske boligsøgende. I dette projekt har vi i stedet brugt Scrum-principperne som en praktisk projektstyringsramme.

## GitHub Projects som styringsværktøj

Vi bruger GitHub Projects til planlægning og styring af projektet. Her har vi oprettet et board, der fungerer som både roadmap og Scrum/Kanban-board.

Boardet er opdelt i følgende kolonner:

- **To do**
- **In Progress**
- **Done**

**To do** indeholder alle opgaver, der skal eller kan løses i projektet. **In Progress** viser de opgaver, der er i gang. **Done** indeholder de opgaver, der er færdige og merged til `main`.

Roadmap og Scrum-board findes under GitHub Projects og bruges som dokumentation for projektets fremdrift.

## Rollefordeling

Da gruppen består af to personer, har vi fordelt rollerne fleksibelt. Begge har fungeret som udviklere, men vi har samtidig fordelt ansvar for bestemte opgaver.

### Projektmedlem 1

Projektmedlem 1 har haft ansvar for:

- Opsætning af repository
- Første version af `index.html`
- Udvikling af udvalgte undersider
- Arbejde med CSS og visuel forbedring af forsiden
- Review og merge af pull requests
- Bidrag til projektbeskrivelse og dokumentation

### Projektmedlem 2

Projektmedlem 2 har haft ansvar for:

- Udvikling af udvalgte undersider
- Tilføjelse af `frontpage.css`
- Ændringer i `index.html`
- Oprettelse af branches og pull requests
- Bidrag til GitHub Projects
- Review og merge af pull requests

### Fælles ansvar

Begge gruppemedlemmer har ansvar for:

- At hente nyeste version fra `main`, før der arbejdes videre
- At oprette branches til nye opgaver
- At lave tydelige commits
- At oprette pull requests
- At reviewe hinandens arbejde
- At holde GitHub Projects opdateret
- At sikre, at dokumentationen passer til det faktiske projekt
- Udarbejdelse af denne `README.md`
- Udarbejdelse af UML-diagrammer

## Branch-struktur og GitHub workflow

Vi arbejder ud fra en simpel GitHub-proces, hvor `main` altid skal indeholde den stabile version af projektet. Nye sider og ændringer udvikles derfor i separate branches.

Vores workflow er:

1. Skift til `main`
2. Hent nyeste version med `Fetch origin` og `Pull origin`
3. Opret en ny branch
4. Lav ændringer i VS Code
5. Test ændringer lokalt i browseren
6. Commit ændringer i GitHub Desktop
7. Push branch til GitHub
8. Opret pull request
9. Det andet gruppemedlem reviewer ændringen
10. Pull request merges til `main`
11. Begge henter den opdaterede `main`

Denne proces hjælper os med at undgå, at vi begge arbejder direkte på `main`, og den sikrer, at ændringer bliver gennemgået, før de bliver en del af projektets stabile version.

## Sprintplan og roadmap

Projektet er opdelt i sprints. Sprintene bruges til at skabe overblik over, hvad der skal laves hvornår, og hvordan projektet bevæger sig fra idé til færdig prototype.

### Sprint 1: Projektstart og opsætning

**Formål:**  
At etablere projektets tekniske grundlag og sikre, at begge kan arbejde med GitHub.

**Opgaver:**

- Oprette GitHub-repository
- Klone repository i GitHub Desktop
- Åbne projektet i Visual Studio Code
- Lave første version af `index.html`
- Lave første CSS-fil, `style.css`
- Lave om-side
- Lave kontakt-side
- Lave første commit og push

### Sprint 2: Grundlæggende sider

**Formål:**  
At opbygge hjemmesidens centrale informationssider.

**Opgaver:**

- Udvikle `soeg.html`
- Udvikle `anmeldelse.html`
- Udvikle `faq.html`
- Arbejde med branches og pull requests

### Sprint 3: Boligcases og vurderingssider

**Formål:**  
At gøre TrustHouse-konceptet tydeligt gennem cases, ratings og anmeldelser.

**Opgaver:**

- Udvikle `boligomraade.html`
- Udvikle `kompleks.html`
- Udvikle `toprated.html`
- Lave `frontpage.css`
- Opdatere navigation på alle sider
- Tilføje TrustScore-eksempler
- Tilføje eksempelanmeldelser

**Leverance:**  
En komplet statisk HTML-prototype med mindst 8 HTML-sider.

### Sprint 4: Dokumentation og aflevering

**Formål:**  
At færdiggøre dokumentation og sikre, at projektet er klar til aflevering og eksamen.

**Opgaver:**

- Skrive `README.md`
- Opdatere projektbeskrivelse
- Opdatere projektplan og roadmap
- Opdatere roller og arbejdsfordeling
- Dokumentere GitHub workflow
- Lave UML-diagrammer
- Opdatere GitHub Projects
- Forberede retrospective til eksamen
- Teste alle sider og links
- Sikre, at `main` indeholder den endelige version

## Retrospective og eksamen

Retrospective inddrages primært til eksamen. Her vil vi reflektere over, hvordan samarbejdet fungerede, hvordan vi brugte GitHub, hvordan Scrum-inspirationen fungerede i praksis, og hvilke begrænsninger der var ved vores proces.

Indledningsvist i projektet lavede vi denne README-fil i Google Docs, som vi delte med hinanden. Her skrev vi foreløbige tanker og planer for projektet, som efterfølgende blev mere udførlige med beskrivelser af udviklingsprocessen, designet og koden. Først derefter blev indholdet sat ind i GitHub. Gruppen vurderede, at fordi GitHub var et nyt værktøj, havde vi brug for en mere tryg måde at samle tekst og noter på, før dokumentationen blev flyttet over i repository’et.

Set i bakspejlet ville vi fremover i højere grad bruge GitHub direkte fra starten og dermed undgå det dobbeltarbejde, der har været i den nuværende proces.

Et centralt refleksionspunkt er, at vi har arbejdet med Scrum-lignende elementer som sprints, board og løbende opgaver, men uden en egentlig slutkunde eller brugergruppe. Derfor har projektet ikke været fuldt agilt. Til gengæld har vi fået erfaring med at strukturere et mindre udviklingsprojekt, bruge versionsstyring og omsætte en idé til en konkret prototype.

### Brugerinddragelse og videreudvikling

I forhold til prototyping ville brugerinddragelse være relevant i en videreudvikling af TrustHouse. Her kunne potentielle brugere, eksempelvis nuværende og kommende beboere i Aalborg, inddrages for at teste, om løsningen opfylder de behov, vi har antaget eksisterer.

Brugerinddragelse ville også kunne kvalificere og validere vores use case diagram. Det nuværende use case diagram er baseret på vores egne antagelser, men gennem brugerinddragelse kunne diagrammet i højere grad afspejle faktiske brugeres interaktion med systemet.

Derudover ville brugerindsigt kunne gøre gruppen bedre i stand til at arbejde mere Lean-inspireret, fordi fokus i højere grad ville blive rettet mod kunden og den værdi, systemet skaber. Ved at observere brugernes interaktion med systemet ville det være muligt at identificere, hvor der skabes værdi, og hvor der ikke gør. Dette kunne bidrage til at præcisere og strømline det videre udviklingsarbejde.

I en videreudvikling ville det også være oplagt at udvide systemet med en database, så TrustHouse ikke kun fungerer som en statisk prototype, men som et interaktivt og dynamisk system. Her ville brugere kunne skrive anmeldelser, som bliver gemt og vist på platformen.

## Foreløbig konklusion på arbejdsprocessen

Arbejdet med TrustHouse har givet os erfaring med både teknisk udvikling og projektstyring. Selvom hjemmesiden er en statisk prototype, har processen krævet planlægning, rollefordeling og versionsstyring.

Projektet viser, hvordan en idé kan udvikles fra en ambitiøs business case til et realistisk produkt inden for en given ramme. Ved at arbejde med GitHub, branches, pull requests og GitHub Projects har vi fået praktisk erfaring med samarbejde i et udviklingsprojekt.

Samtidig viser projektet, at der er forskel på at arbejde inspireret af Scrum og at arbejde fuldt agilt. Vores proces har været Scrum-inspireret, men også præget af en plan-driven tilgang, fordi vi har arbejdet ud fra faste krav, uden løbende brugerfeedback og med en konkret afleveringsdeadline.