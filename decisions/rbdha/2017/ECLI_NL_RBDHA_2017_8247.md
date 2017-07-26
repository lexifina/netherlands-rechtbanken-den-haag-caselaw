---
ecli: "ECLI:NL:RBDHA:2017:8247"
court: "Rechtbank Den Haag"
court_code: "RBDHA"
docket: "C/09/474893 / HA ZA 14-1150"
decided: "2017-07-26"
published: "2017-07-24"
type: "uitspraak"
procedure: "Bodemzaak"
subject: "Civiel recht; Intellectueel-eigendomsrecht"
source_url: "https://uitspraken.rechtspraak.nl/details?id=ECLI:NL:RBDHA:2017:8247"
published_in: ["Rechtspraak.nl"]
---

# ECLI:NL:RBDHA:2017:8247 Rechtbank Den Haag , 26-07-2017 / C/09/474893 / HA ZA 14-1150

## Inhoudsindicatie

Octrooi-inbreukzaak over interactieve beeldschermen. Vervolg op ECLI:NL:RBDHA:2016:452. Inbreuk op octrooi EP 335 aangenomen. Geen toepassing stand van de techniek.

ECLI:NL:RBDHA:2016:452

## Uitspraak

vonnis

RECHTBANK DEN HAAG

Team handel

Zittingsplaats Den Haag

zaaknummer / rolnummer: C/09/474893 / HA ZA 14-1150

Vonnis van 26 juli 2017

in de zaak van

de vennootschap naar vreemd recht

SMART TECHNOLOGIES ULC,

gevestigd te Calgary, Canada,

eiseres,

advocaat mr. P.L. Reeskamp te Amsterdam,

tegen

de besloten vennootschap met beperkte aansprakelijkheid

CTOUCH EUROPE B.V.,

gevestigd te Eindhoven,

gedaagde,

advocaat mr. E.J. Louwers te Eindhoven.

Partijen zullen hierna Smart en CTouch genoemd worden.

1
De procedure

1.1.

Het verloop van de procedure blijkt uit:

het tussenvonnis van deze rechtbank van 20 januari 2016,

de akte na tussenvonnis van 17 februari 2016 van CTouch, met productie 12 (kostenoverzicht),

de akte houdende reactie tussenvonnis van 16 maart 2016 van Smart, met productie 34 (kostenoverzicht).

1.2.

Ten slotte is vonnis nader bepaald op heden.

2
De verdere beoordeling

2.1.

De rechtbank volhardt bij hetgeen in het tussenvonnis is overwogen. Voor wat betreft het door CTouch gevoerde verweer dat zij stand van de techniek toepast zijn partijen daarbij in de gelegenheid gesteld een toelichting te geven. Dat verweer wordt verworpen, waartoe als volgt wordt overwogen.

2.2.

Ondanks de haar toegestane akte heeft CTouch nog immer onvoldoende onderbouwd gesteld dat zij US 4,144,449 (Funk, productie 26 Smart ) dan wel US 4,507,557 (Tsikos, productie 27 Smart) toepast. Smart voert terecht aan dat, anders dan bij EP 1 420 335 B1 (hierna ook: EP 335) en het systeem van CTouch (zoals in het tussenvonnis al was vastgesteld), in geen van beide publicaties beide edges van de pointer worden bepaald met behulp van triangulatie. Enkel het middelpunt wordt bepaald via triangulatie. Dat verschil is niet slechts theoretisch, maar heeft ook een voordeel. Door beide edges te trianguleren aan de hand van de schaduwen op twee imagers, kan een beter onderscheid worden gemaakt in grootte van het object. Smart heeft dit toegelicht aan de hand van de volgende, door haar aangepaste, figuur 1 van Tsikos:

Te zien is dat zowel het “nearby object” als het “far distance object” dezelfde schaduw werpen op DRAM imager 36 als object 26, terwijl hun werkelijke groottes aanzienlijk verschillen. In het systeem van Tsikos kan daarin geen onderscheid worden gemaakt, althans is dat onvoldoende door CTouch toegelicht. Tsikos beschrijft dat aan de hand van één objectschaduw op één DRAM imager het systeem de logische beslissing neemt om het signaal als ruis te beschouwen of als een werkelijke touch. Tsikos leert niet, althans niet duidelijk en ondubbelzinnig, die beslissing te nemen aan de hand van twee schaduwen op twee imagers en triangulatie van de edges. Bij Tsikos wordt het midden van de pointer, mits de schaduw voldoende groot is, als gezegd wel getrianguleerd. De korte beschrijving van figuur 6 van Tsikos in kolom 7, regels 3-11, licht dit een en ander toe:

"FIG. 6 illustrates the operation of the shadow filtering system of FIG. 5. As shown, the control unit detects a first shadow 72 with a width A1 less than the minimum width B1. This shadow is ignored. The system then encounters a second shadow 74, having a width A1

greater than the minimum width B1. In this case, the system determines the address of the center point X=X1+1/2(X2-X1) and this address is passed to the ROM 68 to find the coordinate X by table look-up."

Te lezen is dat (i) het systeem een signaal negeert als de schaduw niet boven minimum breedte B1 komt en (ii) vervolgens van het middelpunt de coördinaten worden bepaald. Dit betekent dat grote objecten ten onrechte kunnen worden weggefilterd (omdat deze veraf van de imager staan) en te kleine juist weer worden meegenomen (omdat deze toevallig dicht bij de imager staan). Ofschoon het systeem van Tsikos met deze toelichting nogal foutgevoelig lijkt, is daaruit niet voldoende duidelijk en ondubbelzinnig de oplossing van EP 335 (en het CTouch-systeem) af te leiden, namelijk om elke edge apart te bepalen via triangulatie met twee imagers en zo een accuratere schatting van de grootte van de pointer te maken.

2.3.

Hoewel het hier bepaald geen rocket-science betreft, heeft CTouch toch werkelijk te weinig aangevoerd om aan te kunnen nemen dat hetgeen zij doet niet inventief is ten opzichte van Tsikos. Dit geldt te minder nu CTouch haar eigen systeem in haar laatste akte inventief noemt ten opzichte van EP 335 (nr. 53). Met dit laatste is niet te rijmen haar stelling dat zij niets anders dan de stand van de techniek toepast. Funk ligt overigens nog weer verder af omdat daarin de grootte van het object P niet gedetecteerd wordt, laat staan gebruikt.

2.4.

Voor zover CTouch thans haar “Gillette”-verweer ook baseert op (de aanvraag voor) EP 1 739 528 (hierna: EP 528) faalt dit. Niet alleen gaat dit haar aanvankelijke stelling waarin het verweer was gebaseerd op toepassing van Tsikos of Funk te buiten, het miskent ook dat EP 528 ziet op de kalibratie van het systeem, terwijl EP 335 ziet op het gewone gebruik. Bovendien wordt in EP 528 niets gezegd over de grootte van de pointer of triangulatie van beide edges. De rechtbank had in het tussenvonnis overigens slechts verwezen naar (de aanvraag voor) EP 528 omdat Smart leek te beweren dat het kenmerkende verschil tussen Tsikos en het CTouch-systeem de toepassing van CMOS-camera’s was in plaats van CRT-techniek (r.o. 4.50, eerste drie gedachtestreepjes). Smart heeft de verdere verschillen inmiddels duidelijker uiteen gezet.

2.5.

In haar akte na het tussenvonnis stelt CTouch thans voor het eerst in de procedure dat EP 335 ongeldig (niet nieuw noch inventief) zou zijn ten opzichte van Tsikos, Funk en EP 528. Smart voert terecht aan dat dit verweer tardief is. Al deze documenten waren CTouch al geruime tijd voorafgaand aan de procedure bekend en ook al bij eerste akte door Smart in het geding gebracht. Het is in strijd met de goede procesorde om dusdanig laat een beroep op ongeldigheid te doen. Overigens gaan de argumenten om de hiervoor geschetste redenen niet op.

2.6.

Voor zover CTouch uit r.o. 4.47 van het tussenvonnis afleidt dat de rechtbank equivalente inbreuk zou hebben aangenomen ter zake het kenmerk van triangulatie (en voor equivalentie geen ruimte zou zijn), berust dat op een onjuiste lezing. In r.o. 4.46 wordt immers juist overwogen dat een gemiddelde vakman de wijze van bepaling in het CTouch-systeem zal zien als een wijze van trianguleren. In r.o. 4.47 wordt daaraan toegevoegd dat die interpretatie van het kenmerk past binnen het in artikel 1 van het Protocol tot uitleg van artikel 69 EOV te houden midden (vgl. HR 4 april 2014, Medinol v Abbott, ECLI:NL:HR:2014:816, zie met name r.o. 3.4.1-3.5.2). Het gaat hier zodoende om letterlijke voldoening aan dat kenmerk.

Slotsom

2.7.

De slotsom van het voorgaande en het tussenvonnis is dat de vorderingen gebaseerd op EP 528 moeten worden afgewezen omdat van inbreuk geen sprake is. Voor wat betreft conclusie 1 van EP 335 liggen zij echter voor toewijzing gereed met inachtneming van het volgende.

2.8.

Het verweer van CTouch dat er door Smart geen grondslag zou zijn aangevoerd voor de vorderingen wordt gepasseerd. Voldoende duidelijk was – ook kennelijk voor CTouch, gelet op het door haar gevoerde verweer – dat de grondslag octrooi-inbreuk was. Daarvoor waren in de dagvaarding ook voldoende feiten gesteld. Ten aanzien van de Laser-lijn heeft CTouch slechts aangevoerd dat Smart geen bewijs van inbreuk heeft overgelegd maar die inbreuk als zodanig niet ontkend (anders dan – zo begrijpt de rechtbank – verwijzing naar haar hiervoor reeds besproken inbreukverweren, die voor EP 335 worden verworpen). Het verwijt treft echter doel waar het de Lexinus lijn betreft. Daarvan is geen inbreukanalyse door Smart gemaakt, terwijl de inbreuk wel wordt betwist en door CTouch (onder meer) is gesteld dat dit systeem niet met optische camera’s werkt (pleitnota nr. 19). Gegeven de vastgestelde inbreuk door CTouch op conclusie 1 van EP 335, is door Smart geen specifiek belang aangevoerd bij beoordeling van de vraag of tevens sprake is van inbreuk op EP 335 volgens conclusies 6, 7, 13 en 19 zodat het verbod in zoverre wordt afgewezen.

2.9.

Smart heeft voldoende belang bij de gevorderde opgaves (onder meer om de winst te kunnen berekenen), winstafdracht en schade op te maken bij staat. Dat de winstopgave vergezeld dient te worden door een verklaring van een registeraccountant zal worden afgewezen omdat een dergelijke verklaring volgens vaste jurisprudentie niet mogelijk is. Voldoende aannemelijk is geworden dat Smart door de vastgestelde inbreuk mogelijk enige schade heeft geleden, die eventueel kan worden begroot aan de hand van de daarmee door CTouch gerealiseerde winst. De vordering tot schadevergoeding op te maken bij staat is derhalve voor toewijzing vatbaar. De rechtbank overweegt verder – onder verwijzing naar HR 14 april 2000, NJ 2000, 489, ECLI:NL:HR:2000:AA5519 – dat schade en winstafdracht niet onbeperkt kunnen cumuleren. Een redelijke uitleg van art. 70 ROW 1995 brengt met zich dat niet meer dan een bedrag gelijk aan het grootste van de totaalbedragen gevorderd aan winstafdracht respectievelijk schade bestaande uit gederfde winst kan worden toegewezen. Uit die twee gevorderde posten kan Smart dus na afloop van de schadestaatprocedure de grootste kiezen. Cumulatie van winstafdracht met eventuele overige schadeposten (vermindering exclusiviteit van de merken en bijvoorbeeld buitengerechtelijke kosten) is wel mogelijk.

2.10.

Evenzo is er voldoende belang bij de gevorderde rectificatie. Weliswaar heeft CTouch aangevoerd dat deze vordering disproportioneel is maar tegenover het evidente belang aan de zijde van Smart heeft zij geen (specifiek) belang gesteld. Wel zal een en ander worden aangepast omdat slechts inbreuk op EP 335 is aangenomen en vertoning op de website van de rectificatietekst gedurende drie maanden niet proportioneel voorkomt.

2.11.

Om executieproblemen te voorkomen en gelet op het tijdsverloop zal enige tijd tot nakoming worden gegund. Bovendien zullen de dwangsommen worden gematigd en gemaximeerd.

2.12.

Toepassing van 28 lid 4 Rv is niet nodig omdat in dit eindvonnis geen gegevens zijn opgenomen afkomstig van bijlage D van het rapport Van Oeffelt.

2.13.

Partijen zijn over en weer in het ongelijk gesteld zodat de proceskosten zullen worden gecompenseerd.

3

3.	De beslissing

De rechtbank:

3.1.

verklaart voor recht dat CTouch inbreuk heeft gemaakt op het Nederlandse deel van het Europese octrooi EP 1 420 335 volgens conclusie 1;

3.2.

verbiedt CTouch binnen 2 weken na betekening van dit vonnis in Nederland inbreuk te maken op het Nederlandse deel van het Europese octrooi EP 1 420 335 volgens conclusie 1, meer in het bijzonder verbiedt CTouch met het oog op de verkoop in Nederland inbreukmakende producten uit de volgende lijnen:

-	de Laser line

-	de Leddura line

-	de Leddura XT line (uitgezonderd de 84 inch 32 p versie)

te vervaardigen, gebruiken, in het verkeer te brengen of verder te verkopen, te leveren of anderszins te verhandelen, of voor die doeleinden aan te bieden, in te voeren, of in voorraad te hebben voor een of ander;

3.3.

beveelt CTouch binnen vier weken na betekening van dit vonnis, een specificatie te doen toekomen aan de raadsman van Smart (mr. P.L. Reeskamp te Amsterdam) van de winst die zij heeft gemaakt met de verkoop van de inbreukmakende producten sinds 19 januari 2014 door middel van overlegging van een verklaring met een specificatie van het bedrag van de behaalde winst, welke verklaring een volledige specificatie dient te bevatten van:

a) de namen en adressen van alle klanten/distributeurs in Nederland aan wie zij inbreukmakende producten heeft verkocht;

b) het aantal inbreukmakende producten dat in Nederland is verkocht, met alle bijbehorende ondersteunende documentatie waaruit dit aantal blijkt;

c) het aantal, de verkoop /leveringsdatum en de ontvangen verkoopprijs met betrekking tot alle inbreukmakende producten die zijn verkocht in Nederland, met alle bijbehorende documentatie waaruit dit blijkt, daaronder begrepen alle facturen;

d) het aantal inbreukmakende producten op voorraad in Nederland op het moment van betekening, tezamen met bewijsmateriaal waaruit dit blijkt;

e) de precieze methode voor berekening van de winst, waarbij een specificatie dient te worden overgelegd van het type en de omvang van de kostenposten die bij de berekening van de winst in mindering zijn gebracht;

3.4.

gebiedt CTouch om binnen een periode van twee weken na betekening van dit vonnis al haar commerciële afnemers van inbreukmakende producten schriftelijk, met gebruikmaking van uitsluitend de volgende tekst, goed leesbaar, op briefpapier van CTouch, zonder toevoegingen of weglatingen, te berichten:

“Geachte […],

Wij zijn verplicht u te informeren dat de Rechtbank Den Haag bij vonnis van 26 juli 2017 heeft beslist dat onze producten

-   de Laser line

-	de Leddura line

-	de Leddura XT line (uitgezonderd de 84 inch 32 p versie)

inbreuk maken op de octrooirechten van Smart Technologies ULC. betreffende (conclusie 1 van) EP 1 420 335 en niet langer mogen worden verkocht in Nederland.

[naam en handtekening]”

3.5.

CTouch te gebieden om binnen een periode van twee weken na betekening van dit vonnis op haar website www.ctouch.nl op de eerst zichtbare pagina (de homepage), in een tekstvak van minimaal 650 x 350 pixels, weer te geven en gedurende een maand weergegeven te houden, uitsluitend de volgende tekst, goed leesbaar, zonder toevoegingen of weglatingen:

“Wij zijn verplicht u te informeren dat de Rechtbank Den Haag bij vonnis van 26 juli 2017 heeft beslist dat onze producten

-   de Laser line

-	de Leddura line

-	de Leddura XT line (uitgezonderd de 84 inch 32 p versie)

inbreuk maken op de octrooirechten van Smart Technologies ULC betreffende (conclusie 1 van) EP 1 420 335 en niet langer mogen worden verkocht in Nederland.”

3.6.

veroordeelt CTouch tot betaling van een dwangsom aan Smart ten bedrage van € 10.000 (tienduizend euro) per overtreding van een of meer van bovenstaande bevelen dan wel - ter keuze van Smart - € 2.500 (vijfentwintighonderd euro) per product of per dag dat CTouch handelt in strijd met een of meer van bovenstaande bevelen, een en ander tot een maximum van € 300.000 is bereikt;

3.7.

veroordeelt CTouch om aan Smart de winst af te dragen welke zij heeft genoten ten gevolge van de inbreuk met betrekking tot alle inbreukmakende producten die zij heeft verkocht in Nederland na 19 januari 2014, een en ander vermeerderd met de wettelijke rente tot aan de datum van volledige voldoening;

3.8.

veroordeelt CTouch om aan Smart de schade te vergoeden die zij heeft geleden als gevolg van de inbreuk(en) voor zover deze hebben plaatsgevonden na 19 januari 2014, op te maken bij staat en te vereffenen volgens de wet in een afzonderlijke schadestaatprocedure als bedoeld in artikel 612 Rv, een en ander vermeerderd met de wettelijke rente tot aan de datum van volledige voldoening;

3.9.

compenseert de kosten van het geding in die zin dat beide partijen hun eigen kosten dragen;

3.10.

verklaart dit vonnis voor zover mogelijk uitvoerbaar bij voorraad;

3.11.

wijst af het meer of anders gevorderde.

Dit vonnis is gewezen door mr. E.F. Brinkman, mr. J.Th. van Walderveen en mr. ir. J.H.F. de Vries en in het openbaar uitgesproken door de voorzitter op 26 juli 2017, in tegenwoordigheid van de griffier.

Verdrag inzake de verlening van Europese octrooien (Europees octrooiverdrag)

Rijksoctrooiwet 1995

Wetboek van Burgerlijke rechtsvordering
