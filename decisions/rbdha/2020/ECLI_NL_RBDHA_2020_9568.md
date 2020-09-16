---
ecli: "ECLI:NL:RBDHA:2020:9568"
court: "Rechtbank Den Haag"
court_code: "RBDHA"
docket: "C/09/592547 / KG ZA 20-390"
decided: "2020-09-16"
published: "2020-09-30"
type: "uitspraak"
procedure: "Kort geding"
subject: "Civiel recht; Intellectueel-eigendomsrecht"
source_url: "https://uitspraken.rechtspraak.nl/details?id=ECLI:NL:RBDHA:2020:9568"
published_in: ["Rechtspraak.nl"]
---

# ECLI:NL:RBDHA:2020:9568 Rechtbank Den Haag , 16-09-2020 / C/09/592547 / KG ZA 20-390

## Inhoudsindicatie

Kort geding - Auteursrecht - Roostersoftware voor onderwijsinstellingen met databases - spoedeisend belang

## Uitspraak

vonnis

RECHTBANK DEN HAAG

Team handel

zaaknummer / rolnummer: C/09/592547 / KG ZA 20-390

Vonnis in kort geding van 16 september 2020

in de zaak van

de rechtspersoon naar vreemd recht

SCIENTIA LTD,

te Cambridge, Verenigd Koninkrijk,

eiseres,

advocaat mr. W. van Angeren te Amsterdam,

tegen

1
de vennootschap onder firma EVEOH,

te Den Haag,

2.	[gedaagde2],

te [woonplaats 1],

3.	[gedaagde3],

te [woonplaats 2],

gedaagden,

advocaat mr. M.R.S. Bacon te Amsterdam.

Partijen zullen hierna Scientia en Eveoh c.s. genoemd worden en gedaagden ook afzonderlijk Eveoh, [gedaagde2] en [gedaagde3]. De zaak is voor Scientia inhoudelijk behandeld door mr. Van Angeren voornoemd, tezamen met mr. H.J. Pot en mr. L.A. Sweering, eveneens advocaten te Amsterdam. Voor Eveoh c.s. is de zaak inhoudelijk behandeld door mr. Bacon voornoemd, tezamen met mr. A.P. Meijboom, eveneens advocaat te Amsterdam.

1
De procedure

1.1.

Het verloop van de procedure blijkt uit:

de dagvaarding van 13 mei 2020, met producties 1 tot en met 14;

de conclusie van antwoord, ingekomen op 11 juni 2020, met producties 1 tot en met 38;

de conclusie van repliek, ingekomen op 18 juni 2020, met producties 15 tot en met 21;

de conclusie van dupliek, ingekomen op 26 juni 2020, met producties 39 tot en met 41;

de digitale mondelinge behandeling via Skype-verbinding op 21 augustus 2020 waaraan partijen en hun advocaten hebben deelgenomen.

1.2.

Vonnis is bepaald op heden.

2
De feiten

Scientia

2.1.

Scientia is een wereldwijde leverancier van roostersoftware voor universiteiten en hogescholen (hierna: onderwijsinstellingen).

2.2.

De belangrijkste softwareproducten van Scientia zijn (de pakketten) Syllabus Plus en Exam Scheduler.

2.3.

Met Syllabus Plus worden onderwijsinstellingen in staat gesteld lesroosters op te stellen. Syllabus Plus maakt gebruik van een database waarin alle data zijn opgenomen waarmee de lesroosters gegenereerd kunnen worden: de Scientia database (hierna: de SDB). Om individuele roosters ter beschikking te stellen aan medewerkers van de onderwijsinstellingen en studenten, bijvoorbeeld via een applicatie op hun mobiele telefoon of tablet, is software nodig die geen onderdeel uitmaakt van het Syllabus Plus-pakket. Scientia biedt onderwijsinstellingen daartoe de softwareapplicatie Scientia Publish aan, waarmee data uit de SDB worden gehaald en individuele roosters beschikbaar kunnen worden gesteld.

2.4.

De structuur van de SDB is niet geschikt om management rapportages te genereren of interacties met applicaties van derden te ondersteunen. Voor dergelijk gebruik is een vertaalslag van de (data in de) SDB nodig. Ten behoeve van die vertaalslag kan met software, die onderdeel uitmaakt van het Syllabus Plus-pakket, een (of meer) Reporting Database(s) (de RDB) worden aangemaakt (door installatie van het programma Scientia Enterprise Reporting Solution of handmatig). Deze RDB is een lege database die bestaat uit vooraf gedefinieerde tabellen en op die tabellen gebaseerde, voorgeprogrammeerde views. Met het programma Scheduled Extract kan de vertaalslag van de data in de SDB worden uitgevoerd en opgeslagen in de aangemaakte RDB. Als de RDB gevuld is, bevat deze een set data die geschikt is om uit te lezen en te presenteren aan een eindgebruiker.

2.5.

Met Exam Scheduler kunnen onderwijsinstellingen examenroosters opstellen. Exam Scheduler maakt gebruik van de Exam Scheduler database (hierna: de ESDB). De ESDB bestaat net als de RDB uit tabellen die door views worden weergegeven en bevat data die relevant zijn voor het roosteren van examens.

Eveoh c.s.

2.6.

Eveoh is een in 2010 opgerichte vennootschap onder firma, waarvan [gedaagde2] en [gedaagde3] de beherend vennoten te zijn. Eveoh ontwikkelt, implementeert, integreert en host software ten behoeve van onderwijsinstellingen.

2.7.

Het belangrijkste product van Eveoh is MyTimetable software, waarmee onderwijsinstellingen  opgestelde roosters beschikbaar kunnen stellen aan hun medewerkers en studenten, bijvoorbeeld via hun mobiele telefoon of tablet. De MyTimetable software bestaat als een on premise-versie en als een software as a service-versie (de laatste versie hierna te noemen: de SaaS-versie). De meest recente versie van MyTimetable wordt enkel nog als SaaS-versie geleverd.

2.8.

Bij de aanprijzing van haar SaaS-services op haar website, maakt Eveoh melding van een twintigtal onderwijsinstellingen als afnemers, welke onderwijsinstellingen ook alle gebruik maken van Syllabus Plus voor het opstellen van lesroosters. Een aantal van deze instellingen maakt ook gebruik van Exam Scheduler voor het opstellen van de examenroosters.

2.9.

Bij de klanten van Eveoh die Syllabus Plus van Scientia afnemen, leest de MyTimetable server bij Eveoh de data van de RDB uit. Ten behoeve van het uitlezen van de data door de SaaS-versie van MyTimetable wordt een kopie van de RDB op de servers van Eveoh opgeslagen.

2.10.

Over de installatie van de SaaS-versie van MyTimetable voor Exam Scheduler op de servers van Eveoh, vermeldt een pagina van de website van Eveoh – voor zover van belang – het volgende:

2.11.

In opdracht van Eveoh is een rapport opgesteld door een ICT-specialist en een software architect (hierna: het Eveoh-rapport). In het rapport van 10 juni 2020 staat – voor zover nu van belang – het volgende:

Over Syllabus Plus:

“Wij hebben geconstateerd dat Eveoh exemplaren van de RDB (in database termen: instances) van haar klanten host als onderdeel van de koppeling van Syllabus Plus.”

Over Exam Scheduler:

“Wij hebben geconstateerd dat Eveoh voor de koppeling met Exam Scheduler alleen benodigde gegevens via een replicatie service van de klantlocatie overzet naar de Eveoh omgevingen. De structuur van deze database wordt dus niet gekopieerd.

(…)

Wij hebben onderzoek gedaan naar hoe de koppeling tussen de Exam Scheduler en MyTimeTable tot

stand komt. Dit gebeurt door een custom SQL Server Integration Services package, kortweg SSIS-package, aan de klantkant aan de Microsoft SQL Server omgeving toe te voegen die vervolgens de

replicatie van de benodigde gegevens voor haar rekening neemt op gestructureerde wijze. Via het SSIS-package worden alleen 17 resultaten van views gekopieerd naar de Eveoh servers, zie

screenshot.

(…)

Een beheerder van een klant heeft Eveoh bij zich uitgenodigd, ze zijn samen achter diens computer gaan zitten, de tabellenstructuur laten zien, en enkele tabellen aangewezen die hij graag in MYTT zou willen terugzien, zodat de examenroosters ook aan studenten ontsloten worden.

De klant gaf Eveoh ook documentatie mee ter ondersteuning (…)

Eveoh heeft toen met SSIS een script in elkaar geklikt (…)

Eveoh maakte het script “create_mat_views.sql” (…) om die views te “materialiseren”, wat feitelijk neerkomt op de uitkomst van die views opslaan in tabellen.

Bij Exam Scheduler is er geen “Scheduled Extract” die de data overzet naar een rapportagedatabase, maar lezen ze met voorgenoemd script de actuele inhoud van de werkdatabase uit. Omdat het niet zo veel data is, en niet zo vaak verandert als lesroosters, verversen ze deze tabellen elk uur in hun geheel. Die 17 gematerialiseerde tabellen worden gekopiëerd naar hun SaaS omgeving, en dienen daar als cache om te worden ingelezen in MYTT.”

Gesprekken over mogelijke samenwerking

2.12.

In 2013 en 2014 hebben Scientia en Eveoh gesproken over een mogelijke samenwerking. In dat kader zijn onder meer de volgende e-mails gewisseld.

2.12.1.

Op een e-mail van Scientia met de volgende inhoud:

“We hebben een nieuwe directeur business development (…) die ik over jullie MyTimetable verteld heb geüpdate. Hij zou graag met jullie willen praten over een mogelijke samenwerking.

Zouden jullie aanstaande vrijdag 12 april tijd hebben voor een conference call?”

heeft Eveoh op 7 april 2013 als volgt gereageerd:

“Ik wou je toevallig vandaag nog mailen over de nieuwe erdb, maar ik zie dat je de info daarover al bijgesloten hebt, dank! (…)

Vrijdag is prima, wij zijn de hele dag beschikbaar. (…)”

2.12.2.

Een e-mail van Scientia aan Eveoh van 20 april 2013, luidt:

“Thank you for our last meeting. As agreed, I enclose a copy of our NDA for you to sign and scan and send to me. Please replace the yellow highlighted ???? with correct details and remove highlights before you send back to me. Also, could you please provide a document with the following details:

About the The business

The market

The team profiles

The product/s

Infrastructure such as servers etc.

The technical architecture and programming language of all products

Global geographical market opportunities

Market segmentation

The revenue model

Competitors

Last 3 years accounts

Next 3 years financial projections

Exit strategy

Investment requirements

Product roadmap

Debtors and creditors

Assets

Please let me know when this information will be made available to me.

(…)

Director

Scientia Ltd”

2.12.3.

Op 10 september 2013 schrijft Scientia als volgt aan Eveoh:

“I hope this mail finds you well. Many thanks for your last mail which we have considered internally and after some deliberation decided not to pursue this further at this time due to other priorities and valuation. I would like to thank you and your colleague to assist us in this matter and I will keep in touch in case things change this side.”

2.12.4.

In een e-mail van 22 juli 2014 schrijft Eveoh het volgende aan Scientia:

“Bijgevoegd het document wat destijds naar [rechtbank: de voornaam van de directeur] is gegaan – alweer ruim een jaar oud, maar op zich nog redelijk up-to-date (the product roadmap voor MyTimetable is inmiddels een aardig stuk van uitgevoerd of in ieder geval uitgewerkt).

Daarnaast is er nog algemene informatie over MyTimetable meegestuurd, te vinden op https://files.eveoh.nl/mytimetable-booklet.pdf.

(…)”

2.12.5.

Op 21 augustus 2014 heeft Scientia een bezoek gebracht aan Eveoh, waarna zij aan Scientia schrijft:

“Many thanks again for visiting us this morning. I believe it was a productive meeting in terms of discussing both our products, and of course it was also nice to meet face-to-face. We still have a lot to discuss, but this morning’s meeting surely increased trust in a possible partnership. We are sure we could both benefit a lot form a partnership, and have good hopes that we can work out all the details together soon.

A quick recap of what we have discussed:

You will provide us with (technical) documentation on the message queue product, preferably with a working set up for us to look at. (…) will be available for our more technical questions.

Based on this, we will determine the impact of the message queue product on our development roadmap, and think of possible other opportunities here.

(…)”

2.12.6.

Op 2 september 2014 stuurt Scientia de volgende mail aan Eveoh:

“Thanks for the meeting it was really useful.

I would like to organise a technical session with (…) to explain how the message queue works and walk you through the components and answer any immediate questions that you have.”

Migratie Syllabus Plus omgeving UvA/HvA

2.13.

In de tweede helft van 2013 hebben Scientia en Eveoh ook contact gehad over de migratie van Syllabus Plus voor de Universiteit van Amsterdam (UvA) en de Hogeschool Amsterdam (HvA) van een omgeving bij een uitbesteder naar de eigen omgeving (on premise) van de UvA en HvA. De UvA en HvA maakten op dat moment ook al gebruik van MyTimetable.

2.14.

Per e-mail van 6 augustus 2013 heeft Eveoh in het kader van die migratie – voor zover van belang – het volgende aan een technisch consultant van Scientia geschreven, waarbij de rechtbank het antwoord dat vervolgens op 13 augustus 2013 door Scientia op één van die vragen is gegeven, ook heeft  opgenomen (onderstreept):

“Thanks again for the call today, your insights were very helpful. Here is a summary of the questions we still have at the moment, if you could look into these that would be great.

(…)

- (…) (…) already sent us the release notes for 3.1/3.2/3.10, but since we are coming from a very old version (at least at the UvA), any additional release notes from older versions are welcome.

- Can you figure out if the latest SDB is compatible with older Scheduled Extracts/ERDB’s (the latest version with A/B switching and without separate views)? Of course we rather update to the latest and greatest version, but we may need to keep the RDB at an older version for now, and need to know the impact of this on the other components.

- Are you aware of any customer that uses SQL Server replication to do (one-way read only) replication of the ERDB to a different location?

It’s one of the options to get the data to Eveoh MyTimetable that we are considering for the new architecture.

RP – we are not aware of any clients that use replication, but see no reason why it would not be successful.

The full technical design/architecture should be available next week, after discussion with the technical parties involved at the UvA. I will then send this document to you for review.

(…)”

2.15.

Eveoh heeft een systeemontwerp, gedateerd 15 augustus 2013, gemaakt, dat zij heeft gedeeld met dezelfde technisch consultant van Scientia. In dat systeemontwerp staat – voor zover hier van belang – het volgende:

Erasmus Universiteit Rotterdam

2.16.

Eveoh levert sinds 2015 de SaaS-versie van MyTimetable voor Syllabus Plus aan de Erasmus Universiteit Rotterdam (EUR), waarvoor met toestemming van Scientia een kopie van de RDB op de servers van Eveoh wordt opgeslagen.

Universiteit Utrecht

2.17.

Op 19 oktober 2017 heeft een medewerker van de Universiteit Utrecht over de koppeling tussen Syllabus Plus en MyTimetable het volgende aan een senior technisch consultant van Scientia geschreven:

“Hi (…),

We don’t use Publish. We use https://mytimetable.uu.nl to publish our timetables. MyTimetable is connected to S+ via scheduled extract. On the new test environment Scheduled Extract will have to be configured such that not only the local RDB’s are filled by Scheduled Extract, but also the MyTimetable RDb’s which are located in the MyTimetable datacentre.

(…)”

Sommatie

2.18.

Bij brief van 9 april 2020 heeft Scientia Eveoh gesommeerd om iedere inbreuk op de auteursrechten van Scientia, bestaande uit het verveelvoudigen van de structuur van de RDB en views uit de ESDB door middel van het aanbieden van MyTimetable voor Syllabus Plus en Exam Scheduler, te staken. Bij brief van 28 april 2020 heeft (de advocaat van) Eveoh laten weten aan die sommatie geen gehoor te zullen geven.

3
Het geschil

3.1.

Scientia vordert, na wijziging van eis, – verkort weergegeven – een verbod op inbreuk op de auteursrechten van Scientia en een bevel om het aanbieden van MyTimetable voor Exam Scheduler te staken en gestaakt te houden, alsook een bevel tot opgave van afnemers/verkrijgers van de SaaS-versie van MyTimetable en Exam Scheduler documentatie, een bevel ex artikel 843a Rv om afschrift te verschaffen van alle Exam Scheduler documentatie en correspondentie daarover die Eveoh in haar bezit heeft, met een bevel aan Eveoh c.s. tot vernietiging van de Exam Scheduler documentatie, een en ander op straffe van verbeurte van een dwangsom, en met hoofdelijke veroordeling van Eveoh c.s. in de proceskosten in de zin van artikel 1019h Rv, te vermeerderen met de wettelijke rente.

3.2.

Scientia voert daartoe het volgende aan.

3.2.1.

Eveoh maakt inbreuk op haar auteursrechten op de structuur van de RDB, door zonder toestemming van Scientia ten behoeve van de SaaS-versie van MyTimetable de structuur en onderdelen van de RDB te kopiëren naar de servers van Eveoh.

3.2.2.

Eveoh maakt tevens inbreuk op de auteursrechten van Scientia op Exam Scheduler en/of de ESDB. Bij de SaaS-versie van MyTimetable voor Exam Scheduler biedt Eveoh scripts aan waarmee Eveoh een selectie van de ESDB naar haar eigen server kopieert en waarvoor ze door Scientia voor Exam Scheduler ontwikkelde views gebruikt. In de dagvaarding heeft Scientia zich op het standpunt gesteld dat, nu het gaat om niet-gedocumenteerde views, het niet anders kan dan dat Eveoh beschikt over een kopie van de Exam Scheduler software, voor welk gebruik Scientia geen toestemming heeft gegeven, zodat om die reden sprake is van inbreuk op de auteursrechten van Scientia op Exam Scheduler en/of de ESDB. Nadat Eveoh bij conclusie van antwoord het Eveoh-rapport had overgelegd (zie 2.11), heeft Scientia haar eis gewijzigd en zich op het standpunt gesteld dat Eveoh inbreuk maakt op haar auteursrechten op (de ESDB van) Exam Scheduler door de bij een afnemer van Scientia bekeken views van de ESDB te hergebruiken in MyTimetable. Daarnaast wijst Scientia erop dat Eveoh van die afnemer een kopie van de Exam Scheduler documentatie heeft gekregen, ten behoeve van de ontwikkeling van MyTimetable, welk bezit en gebruik ook een inbreuk op haar auteursrechten oplevert.

3.2.3.

Omdat is gebleken dat Eveoh via een afnemer van Scientia toegang heeft gekregen tot de Exam Scheduler software en kopieën van de bij die software behorende documentatie, ten behoeve van de ontwikkeling van haar eigen software, heeft Scientia recht op inzage in bescheiden (waaronder correspondentie) waaruit blijkt welke afnemer Eveoh heeft voorzien van toegang tot Exam Scheduler en kopieën van de documentatie, en welke documentatie dat precies is geweest. Deze bescheiden betreffen een rechtsbetrekking waarbij Scientia partij is, aangezien Eveoh en de betreffende afnemer (mogelijk) inbreuk hebben gemaakt op de auteursrechten van Scientia en de afnemer mogelijk ook wanprestatie heeft gepleegd jegens Scientia. Scientia heeft er recht op en belang bij te weten wat de aard en omvang is van deze inbreuk en/of wanprestatie om zo nodig (nadere) rechtsmaatregelen te treffen tegen Eveoh en/of de betreffende afnemer.

3.2.4.

Scientia heeft ook belang bij toewijzing van de vorderingen tegen [gedaagde2] en [gedaagde3], aangezien Scientia zich zonder titel tegen de beherend vennoten slechts op het afgescheiden vermogen van Eveoh kan verhalen en niet op het vermogen van de vennoten.

3.3.

Eveoh c.s. voert verweer.

3.4.

Op de stellingen van partijen wordt hierna, voor zover van belang, nader ingegaan.

4
De beoordeling

Bevoegdheid

4.1.

De voorzieningenrechter is bevoegd kennis te nemen van de vorderingen, al omdat Eveoh c.s. deze bevoegdheid niet heeft bestreden.

Spoedeisend belang: kopiëren structuur RDB

4.2.

Eveoh c.s. betwist in de eerste plaats het spoedeisend belang van Scientia bij de door haar gevraagde vorderingen die zien op het kopiëren van de RDB. De voorzieningenrechter volgt Eveoh c.s. in haar in dit kader ingenomen standpunt dat Scientia niet voortvarend genoeg is opgetreden tegen de door haar gestelde auteursrechtinbreuk op de structuur van de RDB van Syllabus Plus. Daartoe is het volgende redengevend.

4.3.

Partijen bestaan al meerdere jaren naast elkaar op de markt van roostersoftware voor onderwijsinstellingen. Een flink aantal onderwijsinstellingen maakt zowel gebruik van de roostersoftware van Scientia als van MyTimetable. MyTimetable is niet alleen complementair aan de roostersoftware van Scientia, maar maakt voor het beschikbaar stellen van  individuele roosters ook gebruik van de met de roostersoftware van Scientia voor die onderwijsinstellingen gegenereerde roosters. Vast staat – en dat is ook bekend bij Scientia – dat MyTimetable alleen de door de software van Scientia gegenereerde roosters beschikbaar kan stellen, als een koppeling tot stand wordt gebracht met Syllabus Plus en Exam Scheduler. De voorzieningenrechter gaat er vanuit dat Scientia in het kader van de gesprekken over een mogelijke samenwerking in 2013/2014 ook inzicht heeft gekregen in het functioneren van MyTimetable in technische zin. Uit de onder 2.12 opgenomen correspondentie volgt immers dat in 2013 een Non Disclosure Agreement (NDA) is opgesteld, dat Eveoh toen ook op verzoek van Scientia een document met (technische) informatie over MyTimetable aan Scientia heeft verstrekt en dat in 2014 weer wordt gesproken over een ‘technical session’. Scientia mag in meerdere opzichten dus goed bekend worden verondersteld met de MyTimetable software.

4.4.

In dezelfde tijd als de gesprekken over een mogelijke samenwerking hebben plaatsgevonden, hebben partijen ook contact gehad over de migratie van Syllabus Plus voor de UvA/HvA van een omgeving bij een uitbesteder naar de eigen omgeving. Als het gaat  om de koppeling tussen MyTimetable en Syllabus Plus na die migratie, heeft Eveoh Scientia geïnformeerd over haar plan om die koppeling op een veranderde wijze vorm te geven. Na de e-mail van 6 augustus 2013 (beantwoord op 13 augustus 2013, zie 2.14) waarin Eveoh vraagt naar de mogelijkheid van repliceren van de RDB naar een andere locatie, heeft Eveoh een systeemontwerp opgesteld en (ook) gedeeld met Scientia. In dat systeemontwerp maakt Eveoh duidelijk dat zij graag zou zien dat een RDB wordt ‘gecreëerd’ op de MyTimetable server, waar de data van de ‘source’ RDB naar kunnen worden overgebracht. Een en ander mits dat gerealiseerd kan worden. Dat Eveoh daarin is geslaagd, weet Scientia in elk geval sinds 2015. Sinds dat jaar levert Eveoh immers de SaaS-versie van MyTimetable voor Syllabus Plus aan de EUR, waarvoor met toestemming van Scientia een kopie van de RDB op de servers van Eveoh wordt opgeslagen (zie 2.16).

4.5.

Voor zover Scientia uit de vormgeving van de koppeling bij de EUR al niet had kunnen afleiden dat die vormgeving hetzelfde zou zijn bij andere onderwijsinstellingen, zoals bijvoorbeeld bij de UvA/HvA volgens het systeemontwerp van 2013, mag zij in elk geval geacht worden dat na een bericht van de Universiteit Utrecht van 19 oktober 2017 te weten te zijn gekomen (zie 2.17). Waar zij ten aanzien van de kopie van de RDB op de servers van Eveoh in het geval van de EUR stelt dat de EUR een contractuele uitzonderingspositie had, zodat de wijze waarop bij de EUR MyTimetable aan Syllabus Plus was gekoppeld geen aanleiding gaf te vermoeden dat bij andere onderwijsinstellingen sprake was van dezelfde toepassing zonder haar toestemming, en daarmee van auteursrechtinbreuk, gaat dat argument na voornoemd bericht van de Universiteit Utrecht niet meer op. In dat bericht wordt duidelijk aan Scientia gemeld dat een RDB is/wordt aangemaakt op de servers van Eveoh, zodat Scientia in elk geval sinds dat bericht in 2017 bekend mag worden verondersteld met de wijze waarop de SaaS-versie van MyTimetable – ook bij andere onderwijsinstellingen dan de EUR – gebruik maakt van de RDB.

4.6.

Dat het bericht van 19 oktober 2017 is gestuurd aan een senior technical consultant van Scientia, zonder juridische kennis, zodat geen sprake kan zijn van wetenschap van de vennootschap, zoals Scientia (in algemene zin over alle correspondentie) aanvoert, overtuigt niet. In het licht van de hiervoor beoordeelde bekendheid van Scientia met de MyTimetable software, de kennis die Scientia al in 2013-2015 had opgedaan over het kopiëren van de RDB naar de servers van Eveoh en nu het gaat om producten waarvoor – kennelijk, gelet op alle correspondentie – gebruikelijk is dat (senior) technical consultants namens Scientia aanspreekpunt zijn, mag er vanuit worden gegaan dat die consultants worden geïnstrueerd en dat hun wetenschap gelijk kan worden gesteld aan de wetenschap van Scientia.

4.7.

Gezien deze feiten en omstandigheden kan niet worden aangenomen dat spoedeisend belang bestaat bij de gevorderde verbodsvoorziening met betrekking tot auteursrechtinbreuk op de structuur van de RDB, zodat het verbod en de andere vorderingen die op die gestelde inbreuk zien, zullen worden afgewezen.

De ESDB en Exam Scheduler documentatie

4.8.

Nadat bij conclusie van antwoord het Eveoh-rapport in het geding is gebracht, waarin wordt vermeld hoe de koppeling tussen de SaaS-versie van MyTimetable en Exam Scheduler tot stand wordt gebracht en hoe Eveoh aan de informatie over de views van de ESDB is gekomen, heeft Scientia bij conclusie van repliek (dat zou zonder de aangepaste behandeling vanwege het coronavirus eerst ter zitting zijn) de stelling verlaten dat Eveoh zonder toestemming van Scientia moet beschikken over een kopie van de Exam Scheduler software. Bij diezelfde conclusie heeft zij zich in plaats daarvan op het standpunt gesteld dat Eveoh inbreuk maakt op haar auteursrechten op de ESDB en op Exam Scheduler documentatie door bij een afnemer bekeken views van de ESDB te hergebruiken ten behoeve van MyTimetable en die documentatie in bezit en gebruik te hebben.

4.9.

Eveoh c.s. heeft bij conclusie van dupliek bestreden dat de ESDB auteursrechtelijk beschermd is en ook dat het enkele inzien van tabellen in Exam Scheduler bij een afnemer van Scientia, welke informatie Eveoh heeft verwerkt in een script om MyTimetable interoperabel te maken met Exam Scheduler, alsook  het van een onderwijsinstelling verkrijgen van documentatie van Scientia, valt onder de beschermde exploitatierechten (openbaar maken en verveelvoudigen van werken) van Scientia. Eveoh c.s. wijst er in de conclusie van dupliek verder op dat wat zij heeft gedaan (inzien bij de onderwijsinstelling om ervoor te zorgen dat MyTimetable in staat is roosterdata uit de ESDB op te halen), is toegestaan op grond van artikel 45m Aw.

4.10.

In het licht van dit verweer van Eveoh c.s. heeft Scientia voor nu onvoldoende onderbouwd, als al aangenomen zou worden dat (de views van) de ESDB een auteursrechtelijk beschermd werk is, dat en waarom het gebruiken van de bij een afnemer opgedane kennis over de tabellen/views van die ESDB bij het vervaardigen van voornoemd script, auteursrechtinbreuk oplevert. Scientia stelt zich niet (langer) op het standpunt dat Eveoh de views (direct) uit de Exam Scheduler software heeft gekopieerd. Op welke wijze voornoemd ‘hergebruik’, zoals Scientia het noemt, valt onder het verbod auteursrechtelijk beschermde werken te verveelvoudigen of openbaar te maken, heeft zij de voorzieningenrechter vooralsnog niet duidelijk kunnen maken. Daarbij komt dat Scientia niet meer heeft gereageerd op de verwijzing van Eveoh c.s. naar toegestane handelingen op grond van artikel 45m Aw.

4.11.

Het enkele gegeven dat Eveoh Exam Scheduler documentatie van een afnemer van Scientia heeft gekregen, is ook onvoldoende om de conclusie te rechtvaardigen dat Eveoh zich ten aanzien van die documentatie schuldig heeft gemaakt aan auteursrechtinbreuk.

4.12.

Het voorgaande leidt ertoe dat ook het gevorderde verbod en bevel met betrekking tot auteursrechtinbreuk op de ESDB van, en het aanbieden van MyTimetable voor, Exam Scheduler zal worden afgewezen, net als de daarbij horende nevenvorderingen.

Verzoek ex artikel 843a Rv

4.13.

Bij conclusie van dupliek heeft Eveoh c.s. aangegeven bij welke onderwijsinstelling zij mee heeft kunnen kijken in de tabellen van Exam Scheduler, zodat Scientia reeds over die informatie beschikt. In diezelfde conclusie heeft Eveoh c.s. ook aangegeven over welke documentatie zij beschikt (een databaseschema en zogenaamde release notes) en dat op haar servers geen informatie te vinden is van welke afnemer van Scientia zij die documentatie heeft gekregen. Scientia heeft daarna niet gesteld (waarom) nog belang te hebben bij de gevorderde inzage, zodat ook die vordering voor afwijzing gereed ligt.

Proceskosten

4.14.

Scientia zal als de in het ongelijk gestelde partij worden veroordeeld in de proceskosten. Eveoh c.s. heeft een proceskostenveroordeling op de voet van artikel 1019h Rv gevorderd en opgegeven dat haar advocaatkosten € 71.544,- bedragen. Daarnaast maakt zij aanspraak op vergoeding van de kosten van externe rapporten (€ 10.000,- voor het Eveoh-rapport en € 2.000,- voor een aanvullende rapportage van dezelfde deskundigen, alsmede € 1.534,99 voor een als productie GP33 overgelegde juridische opinie over de toepasselijkheid van click-wrap licenties in de verhouding Scientia/onderwijsinstellingen) en nakosten.

4.15.

De onderhavige zaak is een zaak betreffende de handhaving van intellectuele eigendomsrechten in de zin van artikel 1019 Rv. De gevorderde advocaatkosten zijn bestreden, in die zin dat Scientia onder verwijzing naar de Indicatietarieven in IE-zaken meent dat sprake is van een normaal kort geding en meent dat een bedrag van € 17.500,- voor de vergoeding van advocaatkosten redelijk en evenredig is. Scientia heeft de aanspraak van Eveoh c.s. op vergoeding van de kosten van de externe rapporten niet bestreden.

4.16.

Teneinde de redelijkheid en evenredigheid van de opgevoerde kosten te kunnen beoordelen, wordt inderdaad aansluiting gezocht bij de Indicatietarieven in IE-zaken (versie april 2017). De daarin vermelde tarieven worden geacht redelijk en evenredig te zijn. Onderhavige zaak valt naar voorlopig oordeel van de voorzieningenrechter onder de categorie normaal kort geding met een maximumtarief van € 15.000,-. Dit bedrag zal worden toegewezen; het meer gevorderde wordt afgewezen. In het gegeven dat vanwege het coronavirus de behandeling van dit kort geding anders is vormgegeven dan normaal, namelijk door in plaats van pleitnotities tijdens een fysieke mondelinge behandeling de gelegenheid te bieden een conclusie van repliek en dupliek te nemen, ziet de voorzieningenrechter geen aanleiding af te wijken van het maximumtarief voor een normaal kort geding. Het bedrag voor salaris advocaat van € 15.000,- wordt verhoogd met de kosten voor de externe rapporten van in totaal € 13.534,99 en met € 656,- aan griffierecht, waarmee het totaalbedrag uitkomt op € 29.190,99.

4.17.

De voorzieningenrechter zal de op de voet van artikel 1019h Rv gevorderde nakosten, waarvoor de kostenveroordeling ook een executoriale titel oplevert, niet reeds vooraf begroten, omdat Eveoh c.s. dat ook niet heeft gedaan en de voorzieningenrechter over onvoldoende gegevens beschikt om over de hoogte van die kosten te beslissen.

4.18.

Ter zitting heeft Scientia opgemerkt dat Eveoh c.s. een rechtsbijstandsverzekeraar heeft die de proceskosten van Eveoh c.s. vergoedt. Onduidelijk is welke conclusie Scientia daaraan wenst te verbinden. Het enkele feit dat Eveoh c.s. een rechtsbijstandsverzekering heeft afgesloten, neemt niet weg dat Scientia als de in het ongelijk gestelde partij gehouden is voornoemde proceskosten van Eveoh c.s. te vergoeden.

5
De beslissing

De voorzieningenrechter

5.1.

wijst de vorderingen af;

5.2.

veroordeelt Scientia in de proceskosten, tot dusver aan de zijde van Eveoh c.s. begroot op € 29.190,99;

5.3.

verklaart de proceskostenveroordeling uitvoerbaar bij voorraad.

Dit vonnis is gewezen door mr. M. Knijff en in het openbaar uitgesproken op 16 september 2020.

Volgens de uitleg van Scientia (dagvaarding onder randnummers 14 en 15): In de computerwetenschappen worden operaties op een database algemeen aangeduid als een query. Een veelgebruikte programmeertaal voor dergelijke queries is Structured Query Language (SQL). SQL queries kunnen gebruikt worden voor het aanmaken van databases en tabellen, het bijwerken van de data in een tabel, of het raadplegen van data. Bij complexere databases wordt vaak gebruik gemaakt van zogenaamde ‘views’. Een view in SQL kan wel worden omschreven als een virtuele tabel. Een view bevat zelf geen data, maar omvat een query die de data dynamisch uit een andere tabel ophaalt wanneer de view geraadpleegd wordt.

Wetboek van Burgerlijke Rechtsvordering

Auteurswet
