# Choices, Choices - Justify Your Tech-stack

In deze deeltaak onderzoek je een nieuwe tech-stack en presenteer je het onderzoek.

## Context
Deze deeltaak hoort bij sprint 15 "choices, choices". Dit is een opdracht die je individueel uitvoert.

In de workshop S15W1-02-Hoe-Kies-Je-Een-Tech-Stack wordt behandeld hoe je een verantwoorde keuze voor een Tech-stack kan maken.

## Doel van deze opdracht

Je leert hoe je systematisch onderzoek doet naar een passende tech-stack voor een opdracht én hoe je deze keuze kunt onderbouwen en presenteren.

## Werkwijze

Deze opdracht gaat over [analyseren](#analyseren) van de DLC en is best uitgebreid. Zorg dat je genoeg tijd inruimt voor het uitvoeren van deze deeltaak!

### Analyseren

Afgelopen sprints heb je websites gebouwd met tooling: Prismic.io, HyGraph, Sveltekit, GitHub en Netlify. Zo’n serie tools die met elkaar werken noemen we vaak een *tech-stack*. In deze leertaak onderzoek je wat de voor- en nadelen van een specifieke tech-stack zijn. Het staat je vrij een keuze te maken, voor de hand liggende keuzes voor frameworks zijn: Vue, React, Angular, Nuxt of Next maar iets totaal anders mag ook. Het enige dat is uitgesloten is de tech-stack waar je al mee gewerkt hebt. Elk framework heeft specifieke backend systemen waar het goed mee samenwerkt, denk aan: Prismic.io, Supabase, Hygraph, Firebase etcetera. Daarnaast kan je ook specifieke tools voor specifieke doeleinden gebruiken, bijvoorbeeld: three.js of Babylon.js voor 3d animatie, d3.js voor datavisualisaties. Kortom, keuze te over. Een overzicht van alle mogelijke keuzes vind je op [https://jamstack.org/](https://jamstack.org/) onder de kopjes Headless CMS en Site Generator.

Bij het onderzoeken van een mogelijke tech-stack is het belangrijk de belanghebbenden - in het engels *stakeholders* - goed in acht te nemen. Bij het werken met de tech-stack komen immers meerdere partijen samen. Jouw organisatie die als ontwikkelaar van een systeem ingehuurd wordt, de gebruiker die uiteindelijk met het systeem moet gaan werken én (medewerkers van) de opdrachtgever die het systeem gaat beheren.

Jouw keuze voor een tech-stack heeft enorme impact op alledrie deze partijen en een verkeerde keuze kan een onbruikbaar systeem opleveren, iets wat we natuurlijk ten allen tijden willen voorkomen. Daarom is het verstandig bij het onderzoeken van een mogelijke tech-stack verschillende invalshoeken te gebruiken.

In jouw onderzoek ga je van de drie eerdergenoemde invalshoeken uit bij het onderzoeken van de gebruikservaring:
- [User eXperience (UX)](#1-user-experience)
- [Developer eXperience (DX)](#2-developer-experience)
- [Content management eXperience (CX)](#3-content-management-experience)

Begin met het op een rij zetten van een tech-stack, je kunt hierbij hulp vragen aan je docenten of mede-studenten. Voel je vrij om iets te kiezen waar je nog geen ervaring mee hebt, we gaan immers onderzoeken! 

N.B.: Wellicht helpt het je om een paar van de [bronnen](#bronnen) door te lezen om grip te krijgen op waar we het over hebben. Dat gaat je helpen bij het uitvoeren van onderstaande opdrachten.

#### 1. User eXperience

Voor de UX is het belangrijk te weten wie de gebruikers zijn van de website, wat voor apparaten zij gebruiken en of ze bv snel internet hebben of juist niet. Als je het antwoord op bovenstaande vragen hebt onderzoek je wat voor type pagina jouw tech-stack genereert. Is het heel zwaar op 3d animatie? Vraagt de frontend veel javascript rekenkracht? Is er veel netwerkverkeer bij het gebruik van jouw toepassing? Kan het omgaan met het wegvallen van het internet of is er een continue verbinding nodig?

Denk aan de door jou in het verleden bij FDND opgedane kennis omtrent UX bij het uitvoeren van dit onderzoek.

##### Aanpak
1. Onderzoek jouw tech-stack op user experience. Bijvoorbeeld door het doen van een snelle WCAG audit met lighthouse of Axe. Houdt je eerdere ervaring bij FDND met betrekking tot UX in het achterhoofd.
2. Documenteer je bevindingen in de wiki! 

#### 2. Developer eXperience

De ontwikkelervaring of *developer experience* wordt bepaald aan de hand van een aantal criteria.

De basis van de ontwikkelervaring ligt in de **functie** van een ontwikkeltool. Een mooie interface of een marketingverhaal doen niet zo veel als de functionaliteit slecht is. Als het niet werkt, is er geen DX.

Naast dat de tool moet werken, is het belangrijk dat de tool goede performance heeft en **betrouwbaar** is. Elk softwareproduct heeft bugs, maar hoe daar mee om gegaan wordt is belangrijk. Is er een groot ontwikkelteam en zijn er regelmatig updates en releases dan verhoogt dat de ontwikkelervaring.

**Gemak** gaat bij DX niet alleen over het gebruiken van de tool zelf maar ook over documentatie, communities, knowledge bases, shortcuts, snippets, filters, etcetera. Al deze dingen dragen bij aan ontwikkelervaring.

Tenslotte is een **heldere interface** (bijv. API) waar je tegen aan programmeert van onschatbare waarde. Als je niet weet wat je kunt verwachten werk je niet lekker. Helderheid vergroot de ontwikkelervaring.

##### Aanpak

1. Onderzoek jouw tech-stack op developer experience. Het beste is een klein project met de tech-stack proberen te realiseren, bijvoorbeeld een oude leertaak.
2. Documenteer je bevindingen in de wiki! Bijvoorbeeld door genoemde punten te beschrijven: functies, betrouwbaarheid, gemak en helderheid.

#### 3. Content Management eXperience

Het CMS gaat gebruikt worden door de opdrachtgevers of andere content beheerders. Of de beheerders jouw CMS kunnen gebruiken hangt af van het gebruiksgemak en de benodigde technische capaciteit. Als je een ingewikkeld GraphQL systeem gebruikt met onderlinge afhankelijkheden moet een CM-team best tech-savvy zijn, bij een tool als prismic valt dat heel erg mee (zeker als je user-levels gebruikt!).

Wat voor eisen stelt jouw tech-stack aan de beheerder van het systeem? Hebben ze genoeg aan domein-kennis van hun eigen bedrijf of moeten ze een deel van jouw skills als frontend designer/developer omarmen voor ze iets kunnen toevoegen of aanpassen?

##### Aanpak

1. Onderzoek jouw tech-stack op content management experience. De opleiding naast ons (Smart Media Production) gaat over content-beheer. Misschien kan je een van hun studenten interviewen over wat ze prettig vinden. Je kunt zelfs vragen of ze in een door jouw opgezet systeem content toe te voegen en of ze dat prettig vinden..
2. Documenteer je bevindingen in de wiki! 

#### 4. Presentatie

Het hele onderzoek is te substantieel om te presenteren. Voeg daarom de conclusie en een paar *key-insights* uit elk van bovenstaande stappen samen een presentatie. Maak een korte presentatie in bijvoorbeeld powerpoint, waarin je in maximaal 5 slides (zonder introsheet en agenda) jouw bevindingen presenteert. Zorg er voor dat jouw presentatie te begrijpen is voor iemand die weet wat het frontend vakgebied inhoudt. Je presenteert dus niet aan leken.

##### Aanpak

1. Maak een mooie introsheet
2. Laat een slide over voor de agenda
3. Vertaal de conclusie en belangrijkste inzichten met betrekking tot de gebruikservaring (UX) naar één slide, gebruik zo weinig mogelijk tekst maar probeer dingen visueel te maken. Hint: Denk terug aan de lessen van Charley!
4. Vertaal de conclusie en belangrijkste inzichten met betrekking tot de ontwikkelervaring (DX) naar één slide, gebruik zo weinig mogelijk tekst maar probeer dingen visueel te maken.
4. Vertaal de conclusie en belangrijkste inzichten met betrekking tot de content management ervaring (CMX) naar één slide, gebruik zo weinig mogelijk tekst maar probeer dingen visueel te maken.
5. Vul de agenda aan met de titels van je dia’s…
6. Presenteer in de squad!

### Bronnen
Hier wat bronnen die je kunnen helpen bij het structureren van je onderzoek:

- https://medium.com/swlh/what-is-dx-developer-experience-401a0e44a9d9
- https://www.softermii.com/blog/10-tips-in-choosing-the-best-tech-stack-for-your-web-application
- https://symfony.com/ten-criteria
- https://www.velvetech.com/blog/choosing-project-tech-stack-basic-principles/
- https://tray.io/blog/align-revenue-ops-tech-stack

## Definition of Done

Deze opdracht is done als:

- [ ] Je hebt een tech-stack onderzocht op basis van User experience, Developer experience en Content management experience.
- [ ] Je onderbouwt in welke omgeving deze tech-stack het beste tot haar recht komt. IOW, welke voorwaarden stelt deze tech-stack aan gebruikers, developers en content managers.
- [ ] Je presenteert jouw bevindingen aan een specialistisch publiek. Je gebruikt daarbij gepaste presentatiemiddelen.




