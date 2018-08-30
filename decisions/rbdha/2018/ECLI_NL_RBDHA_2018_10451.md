---
ecli: "ECLI:NL:RBDHA:2018:10451"
court: "Rechtbank Den Haag"
court_code: "RBDHA"
docket: "09/767144-16"
decided: "2018-08-30"
published: "2018-08-31"
type: "uitspraak"
procedure: "Eerste aanleg - meervoudig"
subject: "Strafrecht"
source_url: "https://uitspraken.rechtspraak.nl/details?id=ECLI:NL:RBDHA:2018:10451"
published_in: ["Rechtspraak.nl", "NJFS 209/46"]
---

# ECLI:NL:RBDHA:2018:10451 Rechtbank Den Haag , 30-08-2018 / 09/767144-16

## Inhoudsindicatie

Computervredebreuk. Om van wederrechtelijk binnendringen te kunnen spreken is een minimale vorm van beveiliging vereist, ofwel een kenbare drempel zodat onbevoegden zich niet zomaar de toegang kunnen verschaffen. Daarvan in casu sprake, omdat het door verdachte opgevraagde script met het commando “disallow” was afgeschermd en bij opvraging daarvan de invoer van een geldig ID was vereist. Gebruik van valse signalen. Beroep op rechtvaardigingsgrond “ethisch hacken” faalt. Wel maatschappelijk belang gediend, maar verder gegaan dan noodzakelijk door de hele database binnen te halen en ten onrechte meteen naar de media gestapt i.p.v. eerst gemeld aan organisatie zelf. Volgt toepassing van art. 9a Sr.

## Uitspraak

Rechtbank DEN HAAG

Strafrecht

Meervoudige strafkamer

Parketnummer:	09/767144-16

Datum uitspraak:	30 augustus 2018

Tegenspraak

(Promisvonnis)

De rechtbank Den Haag heeft op de grondslag van de tenlastelegging en naar aanleiding van het onderzoek ter terechtzitting het navolgende vonnis gewezen in de zaak van de officier van justitie tegen de verdachte:

[verdachte]
,

geboren op [geboortedatum] te [geboorteplaats] ,

wonende te [adres 1] .

1
Het onderzoek ter terechtzitting

Het onderzoek is gehouden op de terechtzittingen van 14 mei 2018 (regie) en 16 augustus 2018.

De rechtbank heeft kennis genomen van de vordering van de officier van justitie mr. J.E. Hartjes en van hetgeen door de verdachte en zijn raadsman mr. C. Scheurwater naar voren is gebracht.

2
De tenlastelegging

Aan de verdachte is - na wijziging van de tenlastelegging ter terechtzitting - ten laste gelegd dat:

hij in of omstreeks de periode van 7 oktober 2015 tot en met 17 november 2015

te 's-Gravenhage, althans in Nederland, opzettelijk en wederrechtelijk in een

of meer (delen van) geautomatiseerde werken, te weten in (een deel van) de webserver(s) van [benadeelde] of ineen deel daarvan, is binnengedrongen, waarbij hij de beveiliging heeft

doorbroken en/of met behulp van een of meer valse sleutels en/of signalen en/of door het aannemen van een of meer valse hoedanigheden en/of door een technische

ingreep, te weten door onbevoegd gebruik te maken van een of meerdere  ID's (middels een script), en/of (vervolgens) gegevens, die waren opgeslagen, werden verwerkt of werden overgedragen door middel van dat/die geautomatiseerd( e) werk(en) waarin verdachte zich wederrechtelijk bevond,

voor zichzelf of een ander heeft overgenomen, afgetapt of opgenomen.

3
Bewijsoverwegingen

3.1

InleidingOp 4 november 2015 berichtte technologiewebsite Tweakers.net onder de kop “Lek gaf toegang tot gegevens 80.000 ‘vrienden’ [benadeelde] ” dat een deel van het klantenbestand van het [benadeelde] (hierna: [benadeelde] ) voor iedereen met basiskennis van HTML toegankelijk was. Dit klantenbestand bevatte onder meer zogeheten NAW-gegevens (naam, adres, woonplaats), bankrekeningnummers, e-mailadressen en opmerkingen over betaalgedrag van “vrienden” van [benadeelde] . Volgens Tweakers.net was dit bestand eenvoudig voor een ieder te benaderen: het stond vermeld in het bestand robots.txt, waarmee aan zoekmachines wordt aangegeven welk gedeelte van een site niet geïndexeerd mag worden.

Op 17 november 2015 heeft [naam 1] , programmamanager ICT bij [benadeelde] , namens [benadeelde] aangifte gedaan. [naam 1] heeft verklaard dat hij op 4 november 2015 werd gebeld door een medewerker van Tweakers.net met de mededeling dat [benadeelde] gehackt was. Hierop heeft [benadeelde] het bedrijf Fox-IT ingeschakeld om dit te onderzoeken. Fox-IT heeft op 15 november 2015 een rapport uitgebracht waarin volgens [naam 1] staat dat [benadeelde] inderdaad gehackt is. Dit rapport heeft [naam 1] aan de politie overgelegd.

In het rapport van Fox-IT staan de volgende onderzoeksbevindingen. Op de webserver van [benadeelde] ( [benadeelde] ) bevindt zich het bestand robots.txt, dat voor een ieder toegankelijk is. Aanwezigheid van een dergelijk bestand is op webservers gebruikelijk. Het wordt door de beheerder gebruikt om spiders van zoekmachines te instrueren om bepaalde inhoud op de server wel of niet te indexeren. In het geval van [benadeelde] openbaarde het bestand robots.txt het bestaan van het script pictura.php op de webserver van [benadeelde] . Met dit script is het mogelijk om individuele ‘records’ uit de database van [benadeelde] op te halen. Hiertoe moet in de bevraging van het script een ‘ID’ van het record worden meegegeven. Wordt geen ID meegegeven, dan wordt een invulveld getoond waar een ID kan worden ingevuld. Het script wordt normaal gesproken alleen door [benadeelde] gebruikt vanaf een strikte set aan IP-adressen, maar het script is wel bereikbaar en bruikbaar vanaf het gehele internet.

Fox-IT heeft het onderzoek vervolgens toegespitst op de logbestanden van de webserver van [benadeelde] . Hierin is vastgelegd op welk moment en vanaf welk IP-adres bestanden en scripts op de webserver van [benadeelde] zijn opgevraagd. Vanaf het [IP-adres] , dat toebehoort aan Ziggo, wordt op 7 oktober 2015 om 0:06:56 uur het bestand robots.txt opgevraagd. Vervolgens wordt om 0:08:22 uur het script pictura.php opgevraagd. Seconden later wordt meerdere keren geprobeerd een record op te vragen uit de database via het script pictura.php. Eerst door invoer van een woord in het invulveld dat verschijnt na het opvragen van pictura.php: “drie”, “rollema”. Daarna door invoer van een getal: 24, 658 en 2253. Twee minuten later worden vanaf het [IP-adres] , dat toebehoort aan een Amerikaanse aanbieder van webhostingdiensten, 63 records opgevraagd uit de database door middel van het script pictura.php. Opvalt dat hierbij dezelfde user agent wordt gebruikt als de gebruiker van [IP-adres] heeft gebruikt. Dezelfde nacht, tussen 1:27:20 en 1:28:42 uur, worden er vanaf het [IP-adres] bevragingen van de database gedaan door middel van het script pictura.php. Er worden steeds oplopende ID’s ingevuld, totdat een te hoog getal (124.123) wordt ingevuld en geen record meer wordt geretourneerd uit de database. Vervolgens worden weer steeds lagere ID’s ingevuld, totdat weer wel een record wordt geretourneerd (109.000). Daarna wordt weer een hoger ID ingevuld (110.000). Het lijkt er volgens de onderzoeker van Fox-IT op dat de gebruiker van dit IP-adres probeert te achterhalen wat het hoogste ID is waarbij het script nog een record retourneert uit de database. Vervolgens, vanaf 1:29:25 uur, worden er vanaf het [IP-adres] 110.000 opeenvolgende records opgevraagd uit de database met ID’s van 1 tot 110.000. De laatste bevraging is op 8 oktober 2015, om 2:32:38 uur. Dit IP-adres behoort toe aan Amazon Web Services, dat clouddiensten aanbiedt.

Via een vordering verstrekking gebruikersgegevens is achterhaald dat het [IP-adres] op de betreffende data toegekend was aan [naam 2] , wonende te [adres 2] . Dit bleek het woonadres te zijn van de verdachte.

De verdachte heeft ter terechtzitting verklaard dat hij onderzoek deed naar de structuur en beveiliging van verschillende sites in de archiefsector. De site van [benadeelde] trok zijn aandacht, omdat deze niet was beveiligd met het HTTPS-protocol. Hij benaderde via zijn internetbrowser het bestand [benadeelde] . In dit bestand trof hij de regel “disallow: / pictura.php # toegang tot de vriendendatabase” aan. Het commando “disallow” betekent volgens de verdachte dat de eigenaar van de website zoekmachines vraagt om de locatie die daarop volgt niet te indexeren. Vervolgens heeft de verdachte pictura.php opgevraagd. Bij het opvragen daarvan kreeg hij de melding “ongeldig ID” te zien, met daarbij een invulveld. Vervolgens heeft hij een willekeurig ID ingevoerd. Toen zag hij dat er een record werd geretourneerd, met daarin persoonsgegevens van een hem onbekende persoon. Hij heeft daarna nog andere ID’s ingevoerd, en weer werden er records met persoonsgegevens geretourneerd. Het zou kunnen dat hij ook nog records heeft opgevraagd vanaf de [IP-adres] en [IP-adres] . Vervolgens heeft hij een script geschreven dat geautomatiseerd ID’s van 1 tot 110.000 invoerde en de geretourneerde records opsloeg. Dit script heeft hij aangezet vanaf een server die hij huurde bij Amazon. Toen het script klaar was, had hij 80.000 records tot zijn beschikking. Deze bleken namen, adressen, bankgegevens en betalingsgegevens te bevatten. Vervolgens heeft hij het datalek gemeld bij Tweakers.net, De Volkskrant en Trouw via het online klokkenluidersplatform PubLeaks.

3.2

Het standpunt van de officier van justitie

De officier van justitie heeft gevorderd dat het ten laste gelegde feit wettig en overtuigend bewezen wordt verklaard. Volgens de officier van justitie is de verdachte de webserver van [benadeelde] wederrechtelijk binnengedrongen. Het gedeelte van de server waartoe de verdachte zich toegang heeft verschaft, was beveiligd doordat een hindernis was opgeworpen om toegang te verkrijgen, namelijk het moeten invoeren van een geldig ID. De wet stelt geen eisen aan de deugdelijkheid van een beveiliging. Door een willekeurig ID in te vullen heeft de verdachte een sleutel gebruikt die werkte, maar die niet voor gebruik door hem bestemd was. Dit kan ook bestempeld worden als het aannemen van een valse hoedanigheid, namelijk de hoedanigheid van rechthebbende op dat ID. Verder kan het gebruik van een script gezien worden als technische ingreep, aldus de officier van justitie.

3.3

Het standpunt van de verdediging

De raadsman heeft vrijspraak bepleit, omdat er geen sprake is van wederrechtelijk binnendringen. De raadsman heeft hiertoe aangevoerd dat er geen sprake was van een (reële) beveiliging, dus dat deze ook niet doorbroken is door de verdachte. Ook heeft de verdachte op geen enkele wijze het technisch functioneren van de server beïnvloed of gemanipuleerd, zodat niet gesproken kan worden van een technische ingreep. Evenmin is er sprake van een valse sleutel of een vals signaal, omdat de verdachte een geldig en werkend ID heeft ingevoerd. Verder heeft de verdachte zich niet voorgedaan als een geautoriseerd persoon en heeft hij enkel informatie opgevraagd die bij bepaalde ID’s hoorde, maar heeft hij niet gezegd dat hij (rechthebbende van) een ID was. Er is dus ook geen sprake van een valse hoedanigheid, aldus de raadsman.

3.4

De beoordeling van de tenlastelegging

Op grond van de verklaring van de verdachte ter terechtzitting en de onderzoeksbevindingen van Fox-IT stelt de rechtbank vast dat de verdachte zich, na op de hoogte te zijn geraakt van het bestaan van pictura.php, op 7 en 8 oktober 2015 door de invoer van ID’s – eerst met de hand, daarna met een door hem geschreven script – toegang heeft verschaft tot in ieder geval 80.000 records uit de database van [benadeelde] , en deze vervolgens voor zichzelf heeft overgenomen. Dit heeft niet ter discussie gestaan. Wel ter discussie staat de vraag hoe dit handelen juridisch gekwalificeerd moet worden. De rechtbank dient vast te stellen of sprake is van wederrechtelijk binnendringen en zo ja, al dan niet door een technische ingreep, met behulp van valse signalen of een valse sleutel, of door het aannemen van een valse hoedanigheid.

Wederrechtelijk binnendringen?

Van wederrechtelijk binnendringen in een geautomatiseerd werk is sprake als men zich de toegang verschaft tot dat werk tegen de onmiskenbare wil van de rechthebbende. Die wil kan blijken uit woorden en daden, maar in ieder geval moet die blijken uit enige beveiliging van dat werk, ofwel een kenbare drempel zodat onbevoegden zich niet zomaar de toegang daartoe kunnen verschaffen. De beveiliging hoeft niet adequaat te zijn; een minimale beveiliging is voldoende. Het gaat erom dat degene die het werk binnendringt, doelbewust enige inspanning moet hebben gedaan om de beveiliging te doorbreken.

Nadat de verdachte het bestand robots.txt van de webserver van [benadeelde] had opgevraagd, heeft hij in dat bestand de regel “disallow: / pictura.php # toegang tot de vriendendatabase” zien staan. Zoals de verdachte zelf heeft verklaard en ook blijkt uit het rapport van Fox-IT, heeft de beheerder van de webserver van [benadeelde] met die regel een instructie (“disallow”) gegeven aan spiders van zoekmachines om het script pictura.php niet te indexeren. De beheerder wilde dus niet dat pictura.php via zoekresultaten in een zoekmachine zou kunnen worden gevonden en opgevraagd. Met andere woorden: hij heeft pictura.php onvindbaar willen maken. Daaruit kan worden afgeleid dat de beheerder wilde dat pictura.php slechts zou kunnen worden opgevraagd op een door [benadeelde] te bepalen wijze. Dat en waarom de beheerder dat wilde, moet voor een ieder die kennis nam van de inhoud van het bestand robots.txt – en dus ook voor de verdachte – duidelijk zijn geweest. Enerzijds door het commando “disallow”, anderzijds door de toevoeging “toegang tot de vriendendatabase”. Uit die toevoeging blijkt immers dat het gaat om een database met daarin de (persoons)gegevens van de “vrienden” van [benadeelde] , waarvan het voor de hand ligt dat de beheerder die niet met derden wilde delen. Desondanks heeft de verdachte pictura.php opgevraagd, waarna hem door middel van een invulveld werd gevraagd om een ID in te voeren. Eerst heeft de verdachte lukraak woorden ingevoerd, en toen dat geen geldige ID’s bleken te zijn, heeft hij een willekeurig getal ingevoerd, waarna er een record met persoonsgegevens werd geretourneerd. Na het opvragen van pictura.php werden er dus niet metéén persoonsgegevens getoond, maar moest eerst een geldig ID worden ingevoerd. Wat een geldig ID was, was niet kenbaar; de verdachte heeft hiernaar kennelijk een paar keer moeten raden, voordat hij – bij toeval – een geldig ID invoerde. Hiermee moet voor de verdachte nogmaals duidelijk zijn geweest dat het niet de bedoeling van de beheerder was dat pictura.php en de achterliggende database door derden werd opgevraagd. Wie immers een ID moet invoeren om gegevens te kunnen raadplegen, terwijl hem dat ID niet door een rechthebbende is verstrekt en hij daarnaar dus moet raden, moet begrijpen dat de raadpleging van die gegevens niet voor hem is bedoeld.

De rechtbank ziet in het voorgaande – in juridische zin – een minimale vorm van beveiliging, namelijk een kenbare drempel zodat onbevoegden zich niet zomaar de toegang tot pictura.php en de achterliggende database konden verschaffen. Enerzijds door het afschermen van pictura.php met het commando “disallow”, anderzijds door bij opvraging daarvan de invoer van een geldig ID te vereisen. Door pictura.php toch op te vragen en vervolgens een willekeurig getal in te voeren als ID, waarna hem een record werd geretourneerd, heeft de verdachte zich toegang verschaft tot een deel van de webserver van [benadeelde] tegen de onmiskenbare wil van de rechthebbende. De verdachte heeft aldus doelbewust enige inspanning gedaan om de beveiliging te doorbreken. Hiermee is sprake van wederrechtelijk binnendringen in een geautomatiseerd werk.

Op welke wijze is binnengedrongen?

De rechtbank merkt het handelen van de verdachte aan als binnendringen met behulp van valse signalen. Van valse signalen is sprake als “enig teken” wordt gegeven dat bij de ontvanger een gevolg bewerkstelligt dat gebaseerd is op (geprogrammeerde) veronderstellingen die onjuist blijken te zijn, terwijl degene die het teken geeft, weet dat hij met dat teken dat gevolg uitlokt. Hierbij kan worden gedacht aan de veronderstellingen die programmeurs hadden en rechthebbenden koesteren over het gebruik dat van de geprogrammeerde mogelijkheden van hun systeem wordt gemaakt. Van onbehoorlijk gebruik, gebruik waarvoor zij het systeem niet hebben ontworpen of bestemd, zijn zij niet uitgegaan. Zoals hiervoor is overwogen, was het de kenbare bedoeling van de beheerder van de webserver van [benadeelde] dat pictura.php en de achterliggende database niet door derden zouden worden geraadpleegd. De webserver is zo ontworpen, dat een record werd geretourneerd aan wie pictura.php opvroeg en daarna een geldig ID invoerde. De veronderstelling van de beheerder daarbij was dat alleen rechthebbenden dat konden en zouden doen. Door als niet-rechthebbende het pictura.php script op te vragen en een geldig ID in te voeren – en daarmee de webserver “enig teken” te geven –, heeft verdachte een gevolg uitgelokt – het retourneren van een record aan een niet-rechthebbende – waartoe de webserver weliswaar de mogelijkheid bood, maar waarmee de beheerder geen rekening had gehouden. Daarmee is sprake van het geven van valse signalen.

Anders dan de officier van justitie, merkt de rechtbank het handelen van de verdachte niet aan als binnendringen met een valse sleutel, of door het aannemen van een valse hoedanigheid. Daarvan zou sprake kunnen zijn geweest, als de verdachte zich de toegang tot de database had verschaft na zich te hebben geautoriseerd met een niet voor hem bestemd wachtwoord of zich zou hebben voorgedaan als een rechthebbende gebruiker door de invoer van een niet aan hem toegekende inlognaam. Die situaties hebben zich echter niet voorgedaan: het invoeren van een ID is niet te beschouwen als een vorm van autorisatie of als een manier om in te loggen, maar is slechts een manier om een record op te vragen uit de database. Het invoeren van een ID is dan ook niet te vergelijken met het invoeren van een wachtwoord of een inlognaam.

Ook is geen sprake van het gebruik van een technische ingreep. Daaronder moet worden verstaan een ingreep waarmee wordt beoogd het technisch functioneren van een geautomatiseerd werk te veranderen. Dat doet zich hier niet voor. De verdachte maakte juist (op een oneigenlijke wijze) gebruik van de functionaliteiten van de webserver van [benadeelde] en heeft met zijn handelen het functioneren van die webserver niet veranderd.

Conclusie

De rechtbank acht wettig en overtuigend bewezen dat de verdachte met behulp van valse signalen wederrechtelijk is binnengedrongen in een deel van de webserver van [benadeelde] en gegevens die daarop waren opgeslagen voor zichzelf heeft overgenomen.

3.5

De bewezenverklaring

De rechtbank verklaart ten laste van de verdachte bewezen dat:

hij in de periode van 7 oktober 2015 tot en met 8 oktober 2015 te 's-Gravenhage opzettelijk en wederrechtelijk in een geautomatiseerd werk, te weten in een deel van de webserver van [benadeelde] , is binnengedrongen, waarbij hij de beveiliging heeft doorbroken met behulp van valse signalen, te weten door onbevoegd gebruik te maken van ID's (middels een script), en (vervolgens) gegevens, die waren opgeslagen door middel van dat geautomatiseerde werk waarin verdachte zich wederrechtelijk bevond, voor zichzelf heeft overgenomen.

Voor zover in de tenlastelegging type- en taalfouten voorkomen, zijn deze in de bewezenverklaring gecursiveerd verbeterd. Blijkens het verhandelde ter terechtzitting is de verdachte daardoor niet in de verdediging geschaad.

4
De strafbaarheid van het bewezenverklaarde

4.1

Het standpunt van de verdediging

De raadsman heeft betoogd dat sprake is van de rechtvaardigingsgrond ethisch hacken. De verdachte heeft met zijn handelen een maatschappelijk belang gediend, namelijk de beveiliging van persoonsgegevens. Hij is daarbij binnen de grenzen van proportionaliteit en subsidiariteit gebleven, aldus de raadsman.

4.2

Het standpunt van de officier van justitie

De officier van justitie heeft gesteld dat de verdachte niet heeft voldaan aan de vereisten voor een geslaagd beroep op de rechtvaardigingsgrond ethisch hacken. Zo heeft de verdachte het door hem geconstateerde datalek niet (eerst) gemeld aan [benadeelde] zelf, en heeft hij de kwetsbaarheid in de webserver verder uitgenut dan strikt noodzakelijk door herhaaldelijk records op te vragen en deze ook te kopiëren.

4.3

Het oordeel van de rechtbank

De rechtvaardigingsgrond waarop de verdediging een beroep heeft gedaan, komt neer op een beroep op het ontbreken van de materiële wederrechtelijkheid. Een geslaagd beroep daarop ontneemt de strafbaarheid aan handelen dat formeel in strijd met de wet is, omdat dat handelen gerechtvaardigd is door hogere belangen. Bij de beoordeling van de vraag of daar in een concreet geval sprake van is, zijn drie factoren van belang. In de eerste plaats dient te worden beoordeeld of het handelen van de verdachte een wezenlijk maatschappelijk belang heeft gediend. Indien deze vraag bevestigend wordt beantwoord, dient te worden beoordeeld of het handelen van de verdachte proportioneel was, dat wil zeggen of het niet verder ging dan noodzakelijk was om het daarmee beoogde doel te bereiken. Indien ook die vraag bevestigend wordt beantwoord, dient tot slot te worden beoordeeld of het handelen van de verdachte subsidiair was, dat wil zeggen of de verdachte het daarmee beoogde doel niet op een andere, minder ingrijpende manier had kunnen bereiken.

Wezenlijk maatschappelijk belang gediend?

De verdachte heeft verklaard dat hij gebreken in de beveiliging van vertrouwelijke persoons- en betalingsgegevens heeft willen aantonen. Door het handelen van de verdachte is aan het licht gekomen dat de webserver van [benadeelde] kwetsbaar was en daardoor de persoons- en betalingsgegevens van 80.000 personen door onbevoegden te raadplegen waren, waarna [benadeelde] maatregelen heeft getroffen om die kwetsbaarheid te dichten. Daarmee heeft het handelen van de verdachte op zichzelf bezien een niet onbelangrijke bijdrage geleverd aan de beveiliging van privacygevoelige gegevens van 80.000 personen, wat de rechtbank aanmerkt als het dienen van een wezenlijk maatschappelijk belang.

Proportioneel gehandeld?

Nadat de verdachte door middel van de handmatige invoer van ID’s enkele records met persoonsgegevens had opgevraagd, heeft hij een script geschreven en uitgevoerd waarmee hij de volledige vriendendatabase van [benadeelde] heeft opgevraagd én overgenomen. De verdachte heeft hierover desgevraagd verklaard dat het binnenhalen van de gehele database nodig was om de omvang van het datalek en de aard van de gelekte gegevens te kunnen beoordelen. De rechtbank is echter van oordeel dat het handelen van de verdachte veel verder is gegaan dan noodzakelijk was om het door hem beoogde doel te bereiken. Toen hij erin was geslaagd om handmatig enkele records op te vragen, had de verdachte ermee kunnen volstaan dat aan [benadeelde] te melden. Het was immers niet aan hem, maar in de eerste plaats aan [benadeelde] zelf, om de omvang van het lek te achterhalen. Zelfs als daaraan voorbij wordt gegaan, dan nog kan niet worden staande gehouden dat het nodig was voor de verdachte om via het script de gehele database binnen te halen. Ook zonder dat script had hij zich immers een beeld kunnen vormen van de omvang van het lek, doordat hij met het handmatig invoeren van steeds hogere ID’s al had achterhaald wat het hoogste ID is waarbij het script nog een record retourneerde uit de database. Het handelen van de verdachte was dus niet proportioneel.

Subsidiair gehandeld?

De verdachte heeft zijn bevindingen niet gemeld bij [benadeelde] , maar anoniem bij verschillende media via een klokkenluidersplatform. Desgevraagd heeft hij verklaard dat hij zo heeft gehandeld, omdat hij er op grond van zijn eerdere ervaringen met [benadeelde] van uit was gegaan dat [benadeelde] zijn melding niet serieus zou oppakken. Bovendien hoopte de verdachte dat ook de rest van de archiefsector ervan zou kunnen leren als er over het datalek gepubliceerd zou worden in de media. De rechtbank is evenwel van oordeel dat de verdachte niet [benadeelde] had mogen passeren. Uitgangspunt is dat een datalek eerst gemeld wordt bij de desbetreffende instantie. De verdachte had er niet op voorhand van uit mogen gaan dat een melding bij [benadeelde] niet serieus zou worden genomen. Zeker niet nu dit lek – zoals de verdachte ter zitting heeft verklaard – van een andere orde was dan eerder door hem aan [benadeelde] gemelde lekken. Zou zijn gebleken dat [benadeelde] niet adequaat had gehandeld naar aanleiding van zijn melding, dan had de verdachte daarna alsnog een andere weg kunnen bewandelen. Ook zijn stelling dat publicatie in de media nodig was ter lering van de archiefsector, volgt de rechtbank niet. Niet aannemelijk is geworden dat het datalek bij [benadeelde] méér was dan een geïsoleerd incident en duidde op een bredere misstand in de archiefsector die publiekelijk aan de kaak moest worden gesteld.  De verdachte heeft met zijn handelen dus ook de grenzen van subsidiariteit overschreden.

Conclusie

Het handelen van de verdachte kan niet worden gerechtvaardigd door hogere belangen. Het beroep op de rechtvaardigingsgrond faalt. Ook overigens zijn geen feiten of omstandigheden aannemelijk geworden die de strafbaarheid van het feit uitsluiten. Het bewezenverklaarde is dan ook strafbaar en levert het in het dictum genoemde feit op.

5
De strafbaarheid van de verdachte

De verdachte is eveneens strafbaar, omdat er geen feiten of omstandigheden aannemelijk zijn geworden die zijn strafbaarheid uitsluiten.

6
De strafoplegging

6.1

De vordering van de officier van justitie

De officier van justitie heeft gevorderd dat wordt veroordeeld tot een werkstraf van 120 uren waarvan 60 uren voorwaardelijk met een proeftijd van twee jaren.

6.2

Het standpunt van de verdediging

Voor het geval de rechtbank aan strafoplegging zou toekomen, heeft de raadsman verzocht toepassing te geven aan artikel 9a van het Wetboek van Strafrecht en aan verdachte geen straf of maatregel op te leggen.

6.3

Het oordeel van de rechtbank

De verdachte heeft zich schuldig gemaakt aan computervredebreuk door met behulp van valse signalen binnen te dringen in een webserver en een groot aantal persoonsgegevens over te nemen van die server. De verdachte wilde de door hem ontdekte tekortkomingen in de beveiliging van die server verder bekend maken en heeft zijn bevindingen gemeld aan verschillende media. Hoewel de verdachte gemeend heeft een misstand aan de kaak te moeten stellen, is hij daarin veel verder gegaan dan nodig was. Met zijn handelen heeft de verdachte inbreuk gemaakt op het recht van de eigenaar op het ongestoorde gebruik van zijn webserver.

Daar staat tegenover dat de verdachte geen kwade bedoelingen heeft gehad, hij de door hem verkregen persoonsgegevens niet voor eigen gewin heeft aangewend en met zijn handelen op zichzelf genomen een maatschappelijk belang heeft gediend, namelijk de beveiliging van persoonsgegevens. Daarnaast heeft de verdachte vanaf het begin van het opsporingsonderzoek openheid van zaken gegeven.

De rechtbank houdt er verder ten gunste van de verdachte rekening mee dat de behandeling van zijn strafzaak de redelijke termijn heeft overschreden. Dat betekent dat de verdachte te lang in onzekerheid heeft moeten verkeren over de afloop van de zaak. Ter zitting heeft de verdachte verklaard dat hij daarvan in persoonlijk en zakelijk opzicht nadelige gevolgen heeft ondervonden. Ook heeft hij verteld over de grote impact die de doorzoeking van zijn woning en zijn aanhouding op hem en zijn gezin hebben gehad.

De rechtbank heeft acht geslagen op het uittreksel uit het Justitiële Documentatieregister d.d. 23 juli 2018 betreffende de verdachte. Daaruit blijkt dat de verdachte niet eerder, en ook na het onderhavige feit niet meer, in aanraking is gekomen met politie en justitie.

Gelet op al het voorgaande acht de rechtbank oplegging van een sanctie passend noch geboden. Zij zal daarom toepassing geven aan artikel 9a van het Wetboek van Strafrecht en bepalen dat aan de verdachte geen straf of maatregel wordt opgelegd.

7
De vordering van de benadeelde partij

7.1

Inleiding

[benadeelde] heeft zich gevoegd als benadeelde partij met een vordering tot schadevergoeding tot een bedrag van € 20.252,12, bestaande uit materiële schade, te vermeerderen met de wettelijke rente daarover vanaf 7 oktober 2015.

7.2

Het standpunt van de officier van justitie

De officier van justitie heeft zich gerefereerd aan het oordeel van de rechtbank.

7.3

Het standpunt van de verdediging

De raadsman heeft primair bepleit de vordering af te wijzen en subsidiair de benadeelde partij niet-ontvankelijk te verklaren in de vordering in verband met een onevenredige belasting van het strafgeding.

7.3

Het oordeel van de rechtbank

De vordering is complex van aard en is door de verdediging gemotiveerd betwist. Een goede beoordeling van de vordering vergt een nadere wisseling van standpunten, waarvoor het strafgeding zich in beginsel niet leent. Behandeling van de vordering zou een onevenredige belasting van het strafgeding opleveren. De rechtbank zal de benadeelde partij daarom niet-ontvankelijk verklaren in de vordering en bepalen dat zij de vordering slechts bij de burgerlijke rechter kan aanbrengen.

Dit brengt mee dat de benadeelde partij dient te worden veroordeeld in de kosten die de verdachte tot aan deze uitspraak in verband met zijn verdediging tegen die vordering heeft moeten maken, welke kosten de rechtbank begroot op nihil.

8
De beslissing

De rechtbank:

verklaart wettig en overtuigend bewezen dat de verdachte het ten laste gelegde feit heeft begaan, zoals hierboven onder 3.5 bewezen is verklaard en dat het bewezenverklaarde uitmaakt:

computervredebreuk, terwijl de dader vervolgens gegevens die zijn opgeslagen door middel van het geautomatiseerd werk waarin hij zich wederrechtelijk bevindt, voor zichzelf of een ander overneemt;

verklaart het bewezen verklaarde en de verdachte deswege strafbaar;

verklaart niet bewezen hetgeen aan de verdachte meer of anders is tenlastegelegd dan hierboven is bewezen verklaard en spreekt de verdachte daarvan vrij;

bepaalt dat ter zake van het bewezenverklaarde geen straf of maatregel wordt opgelegd;

bepaalt dat de benadeelde partij, [benadeelde] , niet-ontvankelijk is in de vordering en dat de benadeelde partij de vordering slechts bij de burgerlijke rechter kan aanbrengen;

veroordeelt de benadeelde partij in de kosten door de verdachte ter verdediging tegen die vordering gemaakt, begroot op nihil.

Dit vonnis is gewezen door

mr.	B.W. Mulder,							voorzitter,

mr.	S.W.E. de Ruiter,						rechter,

mr.	W.N.L. Donker,						rechter,

in tegenwoordigheid van mr. M. van Haalem,				griffier,

en uitgesproken ter openbare terechtzitting van deze rechtbank van 30 augustus 2018.

Wanneer hierna wordt verwezen naar een proces-verbaal, wordt - tenzij anders vermeld - bedoeld een ambtsedig proces-verbaal, opgemaakt in de wettelijke vorm door (een) daartoe bevoegde opsporingsambtena(a)r(en). Waar wordt verwezen naar dossierpagina’s, betreft dit de pagina’s van het proces-verbaal met het nummer PL1500-2015335252, van de politie eenheid Den Haag, district Den Haag-West, districtsrecherche Den Haag-West, met bijlagen (doorgenummerd p. 1 t/m 89).

Proces-verbaal van aangifte van [naam 1] namens [benadeelde] , p.31-33.

Een geschrift, te weten het rapport van Fox-IT genaamd “ [naam 4] ” d.d. 16 november 2015, opgesteld door [naam 3] , p. 39-57.

Proces-verbaal van aanvraag doorzoeking ter inbeslagneming, p. 62-64.

De verklaring van verdachte ter terechtzitting d.d. 16 augustus 2018.

De rechtbank leidt dit af uit de geschiedenis van de totstandkoming van de strafbaarstelling van computervredebreuk: Kamerstukken II 1989-90, 21 551, nr. 3, p. 16-17, Kamerstukken II 1990-91, 21 551, nr. 6, p. 28-29 en Kamerstukken II 1991-92, 21 551, nr. 11, p. 18.

Kamerstukken II 1990-91, 21 551, nr. 7, p. 4-5.

Vgl. de conclusie van advocaat-generaal mr. Knigge van 28 september 2010, ECLI:NL:PHR:2011:BN9287, overweging 65.
