## Generieke onderwerpen
 
### Identificatie van objecten
Deze paragraaf beschrijft de algemene Ontwerpprincipes en uitgangspunten die betrekking hebben op identificatie van objecten.

Aan elk object wordt een uniek objectnummer (objectidentificatie, afgekort als **UOI**) toegekend. Zolang het object bestaat, mag deze identificatie niet veranderen. De objectidentificatie moet uniek, betekenisloos, permanent en overal geldig (systeemonafhankelijk) zijn. 

 

#### Opbouw objectidentificatie
Bij de opbouw van de objectidentificatie worden de volgende Ontwerpprincipes gehanteerd.

Ontwerpprincipe: 

**De huidige wijze van objectidentificatie van NEN3610 wordt gehanteerd want de SOR conformeert zich aan de NEN3610-norm**

In NEN3610 wordt over het ID het volgende gesteld. Binnen de ‘digitale ruimte’ moeten objecten uniek identificeerbaar zijn. De objectidentificatie is de pointer naar het informatie-object. Als men het over het informatie-object met een bepaalde identificatie heeft (of er naar verwijst) dan wil men zeker weten dat daadwerkelijk dat ene object wordt bedoeld en niet dat men er meerdere ‘terugkrijgt’. Belangrijk is ook om duidelijk te hebben wat de ‘digitale ruimte’ is. Er wordt mee bedoeld de ruimte waarin digitale objecten gezamenlijk voor kunnen komen. Dus in principe de ruimte waarin je informatie met elkaar uitwisselt of deelt.


Ontwerpprincipe: 

**De identificatie voor alle objecten is betekenisloos**

Van belang is dat de objectidentificatie niet betekenisvol geïnterpreteerd mag worden. 


Ontwerpprincipe: 

**De opbouw voor alle objecten is gelijk**

Voor alle objecten in de SOR wordt dezelfde opbouw en toekenning van een objectidentificatie toegepast.
De opbouw van de identificatiecode wordt op dit moment onderzocht in het externe project Regie Op Bouwgegevens (Unique Object Identifier, UOI). In fase 1 van dit project is een 0.8-versie van de UOI beschreven (
https://www.geobasisregistraties.nl/documenten/rapport/2020/12/01/rapport-regie-op-bouwgegevens-uoi-2020-onderzoeksfase ).
In de start van fase 2 zal een UOI-versie 1.0 opgesteld worden die als basis kan dienen voor de identificatie van de objecten in de samenhangende objectenregistratie. Daarnaast wordt onderzocht, en beproefd in een aantal use cases of de waarde van de UOI ook buiten het domein van de samenhangende objectenregistratie bruikbaar is.

#### Identiteit

**UNICITEIT**

Ontwerpprincipe: 

**Een objectidentificatie binnen Nederland is volledig uniek**

We willen zeker weten dat we in tijd en ruimte het over hetzelfde object in de SOR hebben. De objectidentificatie moet daarom uniek zijn.
Ontwerpprincipe: een identificatie wordt mondiaal uniek gemaakt door er de landcode aan toe te voegen
Dit is conform de identificatie in NEN3610.


**HANTEERBAARHEID**

Ontwerpprincipe: 

**Een objectidentificatie in de SOR is machineleesbaar bedoeld en niet mensleesbaar**

De objectidentificatie van de SOR is bedoeld om in het kader van interoperabiliteit te gebruiken bij het volledig geautomatiseerd relaties bevragen tussen verschillende datasets.

**IMPLEMENTATIE-VRIJ**

Ontwerpprincipe: 

**Een objectidentificatie van de SOR kent een functionele versie**

De SOR kent een functionele objectidentificatie. De functionele objectidentificatie is systeem (implementatie) onafhankelijk. 

Ontwerpprincipe: 

**Een functionele objectidentificatie kan een of meer technische identificaties hebben**

De technische objectidentificatie is de toepassing van de functionele identificatie in een technische omgeving. In de technische uitwerking kunnen aan de functionele identificatie een of meer technische identificaties worden gerelateerd die eenduidig met die ene functionele identificatie verbonden zijn, bijvoorbeeld GML,API of URI. Objecten geïmplementeerd in verschillende technische omgevingen moeten middels hun functionele identificatie aan elkaar te relateren zijn. Bijvoorbeeld: een object dat zowel in XML als in JSON als in LD is geïmplementeerd moet herkenbaar zijn als voorkomens van eenzelfde object.

**SAMENHANG**

Ontwerpprincipe: 

**Samenhang faciliteren van de koppeling tussen sectorale identificaties (interne ID) en de objectidentificatie in de SOR (externe ID)**

Sectorregistraties kennen vaak hun eigen identificatie. Er zal gefaciliteerd moeten worden dat bij de objecten in de sectorregistraties de objectidentificaties van de SOR-objecten worden vastgelegd. De informatie die in de sector opgeslagen is daarmee te ontsluiten op basis van de SOR-objectidentificatie

Ontwerpprincipe: 

**Samenhang faciliteren van huidige basisregistratie-identificaties en de objectidentificatie van de SOR**

De objecten in de huidige basisregistraties hebben een verplichte unieke identificatie, die in veel aanpalende sectorregistraties wordt gebruikt. Gedurende een nader te bepalen (transitie-)periode zal de samenhang moeten worden bijgehouden tussen de identificatie van de SOR en die van de objecten waaruit SOR-objecten zijn ontstaan.

#### Tijd

**PERSISTENT IN DE TIJD**

Ontwerpprincipe: 

**Een objectidentificatie mag niet veranderen in de levensloop van het object zodat tijdreizen maximaal wordt gefaciliteerd**

De objectidentificatie van een object in de SOR moet persistent zijn over de levensloop van dat object, zodat altijd duidelijk is welk object het betreft, ook als het object inmiddels is gesloopt.

**FILIATIE (AFKOMST/OVERGANG)** 

Ontwerpprincipe: 

**Het moet mogelijk zijn om de afkomst van een object na te gaan door de relatie vast te leggen met het object / de objecten waaruit een object is ontstaan**

Dit is bedoeld om tijdreizen optimaal te ondersteunen. Objecten kunnen zijn ontstaan door samenvoeging of splitsing van andere objecten. Op een bepaald moment in de tijd bestond het specifieke object wellicht nog niet, maar wel een voorouder van dit object.

Ontwerpprincipe: 

**Het moet mogelijk zijn om de overgang van een object na te gaan door de relatie vast te leggen met het object / de objecten waarin een object is overgegaan**

Dit is bedoeld om tijdreizen optimaal te ondersteunen. Objecten kunnen zijn overgegaan in andere objecten door samenvoeging of splitsing. Op een bepaald moment in de tijd bestaat het specifieke object wellicht niet meer, maar wel mogelijk een afstammeling van dit object.


**LEVENSLOOP** 


Ontwerpprincipe: 

**De levensloop van een object, met een unieke objectidentificatie, begint in de samenhangende objectenregistratie**

In het eerder genoemde externe project Regie Op Bouwgegevens (UOI) zal onderzocht worden of er eerder behoefte is aan identificatiecodes, dan dat deze in de SOR ontstaan.

Ontwerpprincipe: 

**De levensloop van een object, met een unieke objectidentificatie, eindigt in de samenhangende objectenregistratie**


#### Uitgifte

Ontwerpprincipe: 

**Uitgifte van dubbele objectidentificaties mag niet voorkomen** 

Er moet een methodiek worden ontwikkeld om uit te sluiten dat dubbele objectidentificaties worden uitgegeven. Tevens moet er direct op getoetst worden bij de voorbereiding van een uitgifte van een identificatie of deze al bestaat om latere schade te voorkomen.

Ontwerpprincipe: 

**Een objectidentificatie wordt toegekend aan een object in de SOR zodra er voor het eerst in de SOR iets over dit object wordt geregistreerd**

Vanwege de eis van persistentie moet de uitgifte van de objectidentificatie direct worden gedaan bij welke registratie van een gegeven en welk moment in de tijdslijn van een object dan ook.

Ontwerpprincipe: 

**Indien uitgifte van de identificatie aan een object eerder plaats vindt dan het object in de SOR ontstaat neemt de SOR deze identificatie over**

Een object kan eerder ontstaan (bijvoorbeeld in een sectorregistratie) dan in de SOR. Een object krijgt daar een unieke sectorregistratie-identificatie. Indien een UOI-codestelsel (unique object identifier) in Nederland ingevoerd wordt krijgt dit object mogelijk wel bij ontstaan direct een UOI mee. Indien dit object, voorzien van een UOI, wordt aangeboden aan de SOR, wordt deze UOI-identificatie in de SOR overgenomen. Indien er geen sprake is van een UOI-code stelsel in Nederland, krijgt het object pas in de SOR een unieke objectidentificatie. Om interoperabiliteit te borgen zal de sector op hetzelfde object ook de identificatie van het object in de SOR op moeten nemen. 


### Aspecten van geometrie

Opname van geometrie van (vrijwel) alle objecten in de registratie is van essentieel belang voor het goed kunnen functioneren van een geo-basisregistratie. Met geometrie wordt daarbij expliciet bedoeld een geo-gerefereerde vastlegging van een object. Met geo-gerefereerde vastlegging wordt bedoeld dat de geometrie is beschreven in de vorm van coördinaten die onderdeel uitmaken van een referentie coördinatenstelsel. 

Hierbij kan de wijze van vastlegging verschillen voor de diverse objecttypen. Sommige objecttypen zullen worden vastgelegd in de vorm van 3D volumes. Andere objecttypen als vlakken al dan niet met een bepaalde hoogteligging. Voor bepaalde objecten met een minimale omvang kan ook geometrische vastlegging in de vorm van een enkel coördinatendrietal (x, y en z) worden vastgelegd (puntobject). 

Speciale aandacht vraagt het geometrisch voorkomen van netwerken. Aan deze geometrie worden nadere eisen gesteld (zoals een eis dat het netwerk zich moet bevinden binnen de contouren van de bijbehorende reële objecten). Ook worden bij dit soort objecten deels ook andere benaderingen gekozen voor het bepalen van de positie op een netwerk (zoals lineair referencing). Daarnaast wordt er in de verdere uitwerking ook nog aandacht besteed aan andere wijzen van vastlegging van de locatie van objecten. Denk hierbij onder meer aan bouwlagen.

#### Coördinaatreferentiesysteem 

Ontwerpprincipe:

**In de SOR worden de regels voor het gebruik van coördinaatreferentiesystemen gevolgd**

Het gaat hierbij in elk geval om de volgende regel:

- Iedere geometrie moet zijn voorzien van een verwijzing naar het coördinaatreferentiesysteem waarin de coördinaten van de geometrie zijn beschreven..

Ontwerpprincipe:

**Het RD-NAP-coördinaatreferentiesysteem wordt gehanteerd als coördinaatreferentiesysteem**

Het RD-stelsel is gedefinieerd ten opzichte van het ETRS89. 
 Hiervoor geldt dat de gebruikte horizontale datum Bessel 1841 is en het
 coördinaatsysteem de stereografische projectie. Als verticale datum wordt
 het NAP-vlak gebruikt. RDNAPTRANS™ is de officiële en nauwkeurige transformatie tussen het coördinatensysteem van de Rijksdriehoeksmeting (RD) en het Normaal Amsterdams Peil (NAP) enerzijds en het European Terrestrial Reference System 1989 (ETRS89) anderzijds. 



<div class='note'>
 **Aanbeveling:** 

 Controleer bij transformaties naar ETRS89-coördinaten of de gebruikte software de correcte transformatieprocedure heeft geïmplementeerd. In veel GIS software zijn oudere RDNAPTRANS™ procedures (ouder dan de 2018-versie) vaak niet correct geïmplementeerd, wat kan leiden tot onnauwkeurige transformaties. 
 Hanteer hierbij de richtlijnen op https://www.nsgi.nl/geodetische-infrastructuur/producten/coordinatentransformatie.
</div>


**Coördinaten**

Coördinaten opgenomen bij een geometrie worden standaard uitgewisseld met een getalsnauwkeurigheid van 1 mm of het equivalent daarvan in graden. Voor RD en NAP  komt dat overeen met de volgende nauwkeurigheden:

- RD in meters 3 decimalen (1 mm);
- NAP-hoogte in meters 3 decimalen (1 mm);
- Alles wat nauwkeuriger is wordt afgerond op deze nauwkeurigheid van 3 decimalen. Afronding is volgens de volgende regel:
0.0015 -> 0.002; 0.0014 -> 0.001.


#### Geometrie

Geometrie is in de SOR een eigenschap van een object en representeert de locatie van een object. Er is één uitzondering in de SOR: Nummeraanduiding, deze heeft geen eigenschap geometrie.

De SOR zal structureel hoogte informatie zal gaan bevatten. Aanduidingen die daarvoor worden gebruikt worden zijn 3D of 2,5D geometrie. Een geometrie wordt geacht een 3D of 2,5D geometrie te zijn, wanneer deze in een drie dimensionale ruimte wordt vastgelegd (dus met x,y en z coördinaten). Indirecte beschrijvingen van 3D (middels het vastleggen van beschrijvende eigenschappen als Hoogte of Relatieve hoogteligging in combinatie met een 2D geometrie) vallen niet onder de noemer 3D geometrie.

2,5D geometrie is een uitbreiding op 2D geometrie door aan elke coördinaat een hoogte (z-waarde) toe te voegen. Dit wordt veel gebruikt om de “golvende” vorm van het aardoppervlak vast te leggen.


![terreinmodel](media/terreinmodel.png)

3D geometrie is een uitbreiding op 2,5D geometrie door objecten met volumes vast te leggen. Deze volumes kunnen open of gesloten zijn. Bij open volumes kun je door het volume heen bewegen (bijvoorbeeld een weg door een tunnel).

Ontwerpprincipe:

**De SOR kent voor alle reële objecten een 2,5D geometrie en voor enkele specifiek benoemde reële objecten een 3D geometrie.**

Voor bijna alle reële objecttypen volstaat een 2,5D geometrie. Voor enkele reële objecttypen volstaat een 2,5D geometrie niet en nemen we in de SOR een 3D geometrie op.

Ontwerpprincipe:

**De SOR kent voor alle functionele ruimten een 2D geometrie, behalve voor functionele gebouwobjecten die kennen een 2,5D geometrie.**

Voor functionele objecttypen volstaat een 2D geometrie, door het leggen van een relatie met een reëel object, kan voor een functioneel object hoogte informatie worden afgeleid. 
Functionele gebouwobjecten zijn een uitzondering omdat deze zich in een 3D volume (het gebouw) bevinden op hoogte.

Ontwerpprincipe:

**De SOR kent voor alle registratieve en geografische ruimten een 2D geometrie.**


#### Aboslute en relatieve hoogten

**De SOR hanteert absolute en relatieve hoogten**

Absolute hoogten zijn z-coördinaten uitgedrukt t.o.v. NAP en worden gebruikt voor geo-gerefereerde geometrieën. Elk ingewonnen punt in een geometrie heeft zijn eigen z-coördinaat.

Relatieve hoogten zijn gehele getallen die de hoogten van gehele objecten ten opzichte van elkaar uitdrukken.

*Referentielaag*

Met de relatieve hoogte waarde “nul” wordt een referentielaag bedoeld waarin veruit de meeste objectgeometrieën voorkomen. Dit kan het maaiveld zijn, maar daarbij moet duidelijk gespecificeerd zijn wat het maaiveld is. In de praktijk blijken er vanuit verschillende perspectieven andere behoeften zijn voor wat betreft maaiveld. Andere benaderingen zijn ook mogelijk, zoals bijv. een bovenaanzicht. Voor de SOR moet één benadering worden gekozen.

**De reële objecttypen in de SOR bedekken met hun geometrie in de referentielaag het volledige gebied**

Er zal op een locatie in de werkelijkheid altijd bodem, water, begroeiing of constructies aanwezig zijn. Derhalve kan er uit de geometrische representaties een volledig dekkend topografisch kaartbeeld als inforamtieproduct worden opgebouwd.








#### Geometrie-type

Er wordt hierbij verwezen naar de Simple Features, zoals vastgelegd in ISO19125 en OGC 06-103r4 OpenGIS® Implementation Standard for Geographic information - Simple feature access - Part 1: Common architecture
Voor ISO19125 zie: https://www.iso.org/standard/40114.html

#### Topologie
    
<div class='note'>
    **Deze tekst wordt nog herzien**

    Ontwerpprincipe: 

    **Nen3610 doet geen uitspraken over topologie, voor de SOR van DisGeo gelden wel topologische regels**

    Ontwerpprincipe: 

    **In de SOR wordt gewerkt met een referentielaag**

    Er is sprake van een referentielaag op het Nederlandse Grondgebied ten opzichte waarvan andere objecten kunnen worden gepositioneerd. Deze laag werd voorheen als ‘maaiveld’ aangeduid. Maar deze term is niet scherp genoeg omdat deze vanuit verschillende thema’s anders wordt bekeken.

    Deze referentielaag wordt 
    - In geval van reële objecttypen volledig bedekt door objecten uit de objecttypen water, begroeiing (inclusief onbegroeid) en constructies
        -	Hierbij sluiten de objecten  op elkaar aan volgens topologische regels, maar overlap is vooralsnog mogelijk. 
        -	Door deze werkwijze wordt de complexiteit van de topologie sterk gereduceerd ten opzichte van de huidige situatie in de BGT
    - In geval van functionele objecttypen NIET volledig bedekt omdat daar geen noodzaak voor is.

    Hier is sprake van een andere benadering dan bij de BGT gebruikelijk is. Bij de BGT hebben alle vlakobjecten op de referentielaag een rol in het opdelen van de referentielaag. Dit geeft bij het beheer van de BGT veel extra werk, omdat als een aangrenzend object zelfs maar een tussenpunt in de geometrie krijgt, het aanpalende object ook moet worden aangepast. Bij de nieuwe benadering kunnen geregistreerde objecten elkaar als gevolg van bewerkingen geometrisch gaan overlappen. Dat kan verwarring geven over wat de werkelijke grens is tussen objecten.

    Ontwerpprincipe: 

    **In geval van nadere benoemde registratieve objecttypen is er sprake van een topologisch aaneengesloten situatie die echter niet het totale Nederlandse grondgebied hoeft te bedekken**

    - Voorbeeld: de gemeentelijke indeling van Nederland is een topologisch aaneengesloten verzameling van objecten die zich echter niet uitstrekt tot het continentale plat.
</div>



#### Lineair referencing

De Lineair Referencing Methode (LRM) gebruiken we om het lokaliseren van veranderingen in de verbindingskenmerken vast te leggen als er geen dringende reden is om de structuur van het netwerk te verstoren door verder op te knippen. Dus een methode waarbij administratief wordt aangegeven vanwaar een verandering geldt: bv. vanaf 200 meter van af start verbinding geldt een toegestane snelheid van 70 km/h. 

lineair referencing wordt door Inspire geadviseerd:

![requirement inspire](media/inspire_lrm1.png) 

Dit figuur laat de werking van linear referencing zien :


![lineair referencing](media/inspire_lrm2.png)

Let op: als iets in de werkelijkheid zowel een reel voorkomen heeft als een functie, dan moet de geometrie van het functionele object afgeleid worden van het reële, ook als dit via lineair referencing wordt vastgelegd. 



#### Generalisatie 

*Van grootschalig (schaal 1:1.000) naar kleinschalig (1:10.000 tot 1:1.000.000)*

Bij de uitwerking van de inhoud van de samenhangende objectenregistratie wordt voor de verschillende objecttypen bepaald wat de kleinste geometrische/cartografische eenheid is die nog van belang is voor meerdere gebruikers van de registratie. Dit detailniveau bepaalt daarmee wat voor het betreffende gedeelte van de samenhangende objectenregistratie de kleinste bouwsteen vormt. Bv. objecttype Streek (nauwkeurigheid meter tot hectometer) heeft een heel ander detailniveau dan objecttype Weg of Gebouw (nauwkeurigheid centimeter tot decimeter).

Uit de grootschalige SOR worden [informatieproducten](#model-van-begrippen-en-informatieproducten) samengesteld op kleinere schalen, van schaal 1 op 10.000 tot 1 op 1.000.000. Dit zijn cartografische informatieproducten (data of visualisatie). Deze informatieproducten worden geautomatiseerd met een landelijk uniform proces samengesteld (automatische generalisatie).

In deze paragraaf worden op een generiek niveau ontwerpprincipes hiervoor benoemd. 
Hierbij worden de volgende begrippen gehanteerd:

**cartografisch object** 

Een object wat voor visualisatie (op een of meer schaalniveaus) wordt aangemaakt en in dat kader een tijdelijk karakter heeft, wat verbonden is met die specifieke versie op 1 of meer schaalniveaus en van die visualisatie, hoe lang die visualisatie ook beschikbaar is.

**generaliseren (van data of voor visualisatie)**

 Dit betreft de geometrie van objecten (of op attribuutniveau)  zinvol weglaten, vereenvoudigen, verplaatsen, vergroten, symboliseren en/of aggregeren 

**aggregeren**

Dit betreft het zinvol samenvoegen van objecten tot een nieuw object (zowel op dataniveau als cartografisch niveau). Aggregeren kan daarmee ook een aspect van generaliseren zijn.


**Generaliseren**

Uit eerdere consultaties blijkt dat gebruikers geen data-analyses doen op basis van afgeleide kaartschalen. Hooguit voor aanpassen van visualisatie, symbolen en voor een eenmalige actie waarbij de identificatie niet nodig is. 
Daarom:
1.	Is er geen noodzaak voor gegeneraliseerde data-objecttypen  
2.	Zijn cartografische objecttypen voldoende zonder (complexe) afstemmingsrelaties, dat wil zeggen dat bijvoorbeeld aggregatie-relaties eenmalig zijn en niet worden bewaard.
3.	Is er geen noodzaak voor unieke universele persistente identificatie van gegeneraliseerde objecten, er wordt geen identificatie bewaard. 


Ontwerpprincipe:

**Objecttypen worden enkel en alleen op het voor de SOR meest gedetailleerde noodzakelijke niveau vastgelegd (de kleinste eenheden).**

Dit detailniveau kan per objecttype verschillen. Voor met name geografische objecttypen is vaak een minder gedetailleerd niveau noodzakelijk. Denk bijvoorbeeld aan de begrenzing van een streek als de 'Utrechtse Heuvelrug' of het Continentaal Plat.


Ontwerpprincipe:

**Gegeneraliseerde data objecttypen worden niet opgenomen in de SOR. Ze kunnen wel onderdeel zijn van de informatieproducten van DiSGeo.**

Ontwerpprincipe:

**Cartografische objecttypen worden niet opgenomen in de SOR. Ze kunnen wel als onderdeel van de informatieproducten van DisGeo worden opgenomen**

Cartografische objecten zijn voor gebruikers van belang omdat ze dan hun eigen visualisatie kunnen gebruiken. Deze kunnen op basis van de objecten uit de SOR worden gegenereerd (veelal door generalisatie en/of aggregatie) en in producten van DisGeo worden opgenomen.

Voor cartografische objecten geldt dat er een eigen tijdelijke identificatie aan wordt toegevoegd zodat de gebruiker het object kan identificeren voor bijvoorbeeld een terugmelding. Deze identificatie wordt echter niet bewaard. Omdat de identificatie niet wordt bewaard is een eigen levensloop niet aan de orde. Omdat de identificatie niet wordt bewaard is een relatie naar de basisobjecten waaruit ze zijn ontstaan ook niet aan de orde. Dit ligt in lijn met de stelling dat we niet van een minder (lager) naar een meer (hoger) gedetailleerd niveau terug kunnen gaan. Als het wenselijk is kunnen ten dienste van gebruikers in de producten geometrieën op een lager detailniveau worden aangeboden die gebaseerd zijn op geometrieën van onderliggende basisobjecten op een hoger detailniveau.

**Kwaliteit**

Ontwerpprincipe: 

**De kwaliteit van de objecten en de bijbehorende gegevens worden in die mate geborgd dat geautomatiseerde generalisatie probleemloos kan verlopen**

Als dit principe wordt gevolgd, wordt daarmee voorkomen dat bij generalisatie extra handwerk nodig is om het gewenste resultaat te bereiken.

Hiermee wordt concreet bedoeld:
-	Dataobjecten moeten op het basisniveau landelijk uniform en homogeen en aaneensluitend zijn
-	Dit moet nader uitgewerkt worden in de informatiemodellering en in de eisen aan de inwinningsregels. Er moet hier één consistent systeem voor zijn en ook de implementatie moet consistent zijn
-	Objecten op verschillende relatieve hoogteniveaus moeten goed op elkaar aansluiten waar ze elkaar raken en consistent zijn binnen één specifieke schaal



**Terugmeldingen op gegeneraliseerde objecten**

Omdat gegeneraliseerde objecten geen deel uit zullen maken van de SOR, wordt hier vast voor deze groep een aandachtspunt gegeven: Er kunnen wel terugmeldingen zijn op gegeneraliseerde cartografische objecten, maar deze hoeven niet door te werken naar de SOR data objecten.  Deze terugmeldingen moeten altijd eerst beoordeeld worden waarbij geconstateerd wordt dat

-	Of de terugmelding de generalisatie betreft en niet doorgezet hoeft te worden naar de bronhouders van de onderliggende data
-	of de terugmelding de data betreft en wordt toegewezen aan geselecteerde betrokken bronhouders van de dataobjecten uit de SOR
Afhankelijk van de situatie hanteren we een van beide mogelijkheden, want een eindgebruiker ziet de producten en moet op basis daarvan een terugmelding kunnen doen. Deze kan niet 1 op 1 worden doorgezet naar alle onderliggende dataobjecten op het hoogste detailniveau, want dat is mogelijk helemaal niet aan de orde en dan zouden objecten op het hoogste detailniveau onnodig belast worden met terugmeldingen. Een beoordeling door een behandelaar of door artificiële intelligentie is daarom een belangrijke tussenstap.








### Netwerken

In de samenhangende objectenregistratie worden twee transportnetwerken onderscheiden: wegen en spoor. Netwerken zijn een verdere uitwerking van de virtuele objecten transportvoorzieningen in het basismodel NEN3610. En zijn in de SOR opgenomen om functionele eigenschappen te kunnen registreren en om als basis kunnen dienen voor routeringsvraagstukken.

De structuur van een netwerk kenmerkt zich door knopen en verbindingen. De wijze van beschrijven van de structuur is voor alle netwerken hetzelfde. In generieke zin zouden alle netwerken als één geheel kunnen worden beschreven. De netwerken zijn immers ook onderling verbonden. Echter de inhoud verschilt dermate dat het vanuit beheer- en bruikbaarheid praktischer is om de netwerken los van elkaar te beschrijven.


#### Elementen van een netwerk: knopen en verbindingen

Een netwerk bestaat uit knopen en verbindingen. Een knoop is een keuzepunt. Een verbinding geeft de relatie aan tussen twee knopen.  Bijvoorbeeld voor een weggebruiker. Een verbinding verbindt twee direct aanliggende keuzepunten. 

Een knoop en verbinding hebben eigenschappen waarmee een knoop of verbinding beschreven kan worden. Administratieve eigenschappen zoals een straatnaam worden vooral gebruikt voor locatiebepaling. Voor routering zijn eigenschappen die een voorwaarde beschrijven belangrijk om te bepalen hoe een route over het netwerk loopt. Voor wegen zijn bijvoorbeeld rijrichtingen en maximum snelheden dergelijke eigenschappen. 

#### Een netwerk is gerelateerd aan de reële infrastructuur

Een transportnetwerk beschrijft de functionele inrichting van de reële infrastructuur en is daarmee onlosmakelijk mee verbonden. Bij nieuwe aanleg van infrastructuur is het functioneel ontwerp (het netwerk) de basis voor de aanleg van reële infrastructuur. 

Een netwerk heeft vanuit zichzelf geen geometrie in de fysieke werkelijkheid, voor de beschrijving en positionering van transportnetwerken wordt een geometrie toegevoegd en/of wordt verwezen naar de geometrie van de reële infrastructuur.

Indien een geometrie wordt toegevoegd aan een knoop of verbinding dan ligt deze op het gerelateerde reële object.


#### Detaillering waar nodig
Een netwerk is te beschrijven in verschillende niveaus van detail. Of detaillering nodig is hangt van de informatiebehoefte af. De transportnetwerken in de SOR kunnen dus een verschillend detail niveau hebben. Detailniveau van netwerken is niet per definitie hetzelfde als een schaalniveau zoals die gebruikt wordt voor kaarten.

Het detailniveau van een netwerk wordt bepaald door wat nodig is om het netwerk te kunnen beschrijven.
Een wegennetwerk kent functioneel gezien drie niveaus: een weg, een rijbaan en rijstrook niveau. Een eigenschap bepaalt het niveau van detail. Een straatnaam geldt voor de weg en daarmee ook voor de rijbanen en rijstroken die bij die weg behoren. Een busstrook wordt gedefinieerd op strook niveau en een busbaan op baan niveau. 

#### Eigenschappen van knopen en verbindingen

Ontwerpprincipe:

**Eigenschappen van verbindingen die niet voor de hele verbinding gelden worden vastgelegd met lineair referencing.**

Eigenschappen kunnen meerdere malen van waarde veranderen langs een verbinding. Bijvoorbeeld als de straatnaam wijzigt bij het passeren van de gemeente- of woonplaatsgrens. Of als de snelheid op een provinciale weg vlak voor een kruising wordt teruggebracht naar 50 km/h. Als er geen dwingende reden is om de structuur van het netwerk te verstoren door een verbinding op te knippen, worden de eigenschappen bij een verbinding vastgelegd met de methode van lineair referencing. Lineair referencing is een methode waarbij administratief wordt aangegeven bij een verbinding waar op de verbinding een verandering van een bepaalde eigenschap plaatsvindt. Bij de beschrijving van de objecten in dit document is dit bij de eigenschap van het kenmerk aangegeven door de afkorting LR.
Indien een eigenschap meerdere waarden kan bevatten zonder dat er sprake is van een afhankelijkheid van een locatie, dan wordt dit bij de eigenschap aangegeven door de afkorting MV (meervoudig). Bijvoorbeeld als er meerdere soorten modaliteiten zijn toegestaan op een verbinding of knoop.

#### Relaties bij netwerken


Een netwerk kent verschillende type relaties:
Relaties die binnen het netwerk gelegd worden en relaties die met objecten gelegd worden die geen onderdeel zijn van het netwerk, maar wel van belang zijn voor het netwerk.

Relaties die binnen het netwerk gelegd worden zijn onderdeel van het netwerk. Bijvoorbeeld een rijbaan die bestaat uit een aantal rijstroken of ventweg en de bijbehorende hoofdrijbaan.

Er zijn objecten die van belang zijn voor het netwerk maar die niet worden opgenomen als onderdeel van het netwerk. Parkeervakken langs een verbindingen worden wel gerelateerd aan het netwerk omdat dan bekend is bij welke verbinding een parkeervak hoort, maar maken er geen onderdeel uit. Dat wil zeggen dat er geen knoop wordt geïntroduceerd op een parkeervak alsof het een doodlopende weg is.

Binnen netwerk wordt onderscheid gemaakt naar verbindingen tussen knopen en verbindingen waarover een voertuig/weggebruiker/trein zich kan verplaatsen en tussen (netwerk) objecten die een logische samenhang kennen. Deze laatste categorie wordt een hyperverbinding genoemd.




### Meta-informatie en bronverwijzing

#### Relevante aspecten meta-informatie

Meta-informatie is een breed begrip dat door Wikipedia als volgt wordt omschreven: "Meta-informatie bevat alle informatie die ertoe bijdraagt gegevens tot informatie te verheffen. Anders gezegd: omdat meta-informatie gegevens in een bepaalde context zet, is meta-informatie de factor die gegevens tot informatie verheft.

Onder meta-informatie kan zowel de expliciet beschrijvende als de impliciet aanwezige informatie over structuur, betekenis, onderlinge relaties, locatie, status, eigenaarschap, enz. van gegevens worden verstaan. Ook alle informatie over de applicaties en processen die de gegevens manipuleren, valt onder de noemer meta-informatie."

In dit document kijken we met name naar dat deel van de meta-informatie die inhoudelijk van belang is voor gebruikers van de gegevens uit de objectenregistratie en voor de bijhouding van de gegevens door bronhouders.

Immers meta-informatie is essentieel voor de gebruiker van gegevens om te beoordelen of het gegeven in de objectenregistratie geschikt is voor het doel waarvoor de gegevens gebruikt worden. Een oppervlakte van een woning die 25 jaar geleden voor het laatst gecontroleerd is, kan geschikt zijn voor het bepalen van een algemeen kengetal over de totale omvang van de woningvoorraad in een gemeente, maar is ongeschikt voor het opleggen van een belastingaanslag aan de eigenaar van die woning.

Aan de andere kant is meta-informatie essentieel voor de bronhouders van de gegevens, omdat ze de noodzakelijke stuurinformatie bieden over de wijze waarop invulling wordt gegeven aan de verantwoordelijkheid om de gegevens actueel te houden en over de werkzaamheden die de komende periode gedaan moeten worden. Metagegevens zijn daarmee voor de bronhouders van betekenis voor beheersing van hun bijhoudingsproces. Ook deze metagegevens gericht op de bijhoudingsprocessen maken een inherent onderdeel uit van de objectenregistratie.

Alle meta-informatie die niet de inhoud van de gegevens betreft, laten we in dit document buiten beschouwing. Dat gedeelte van de meta-informatie is niet relevant voor het uitwerken van het informatiemodel voor de SOR. De niet-inhoudelijke aspecten van de meta-informatie worden opgepakt in het kader van de architectuur en de uitwerking daarvan. Bijvoorbeeld praktische aspecten omtrent beschikbaarheid, inclusief aandachtspunten als kosten, technische specificaties voor bevraging en ander services, url of andere toegangsinformatie.

De voor de bronhouders en gebruikers van de SOR relevante inhoudelijke meta-informatie wordt in de context van dit document onderverdeeld in de volgende aspecten:
-	Definities (op niveau van objecten en attributen)
-	Tijdsaspecten (historie en levensfase)
-	Bronverwijzing
-	Autorisatie
-	Kwaliteitseisen
-	Kwaliteit
-	Status


1.	De formele definitie van objecten (objecttypen) en eigenschappen (attribuuttypen) die worden geregistreerd in de SOR moet voor bronhouder en gebruiker helder aangeven wat de betekenis is van een bepaald gegeven, maar ook over welke reële objecten bijvoorbeeld wel en welke niet geregistreerd worden in de SOR.

2.	Alle meta-informatie die een tijdsaspect heeft (historie, levensfase) komt in de volgende paragraaf van dit document afzonderlijk aan de orde.

3.	Bronverwijzing betreft aan de ene kant de formele onderbouwing van gegevens, bijvoorbeeld in de vorm van formele brondocumenten, zoals vergunningen en besluiten, maar aan de andere kant ook de meer technische bron van de gegevens, zoals plaatsbepalingspunten en indirect luchtfoto's, metingen en BIM-modellen. De plaatsbepalingspunten zijn daarmee een bijzondere vorm van bronverwijzing in het kader van de geometrie binnen de SOR.     Zowel de bronverwijzing naar de praktische bronnen (luchtfoto's etc.) als naar de formele brondocumenten (vergunningen, huisnummerbesluiten) gebeurt zoveel mogelijk door het vastleggen van de url van de vindplaats van de desbetreffende bron. Op deze manier is de vindbaarheid van de bron optimaal gewaarborgd, mits ook het beheer van deze digitale brondocumenten zorgvuldig is ingeregeld. Een ander aspect van de bronverwijzing is de vastlegging van de reden van wijziging van een attribuut. Voor de SOR wordt voorgesteld het uitgangspunt te hanteren dat bij elke wijziging van een attribuut ook een reden wordt geregistreerd. Deze verplichting vereenvoudigt bijvoorbeeld het afhandelen van terugmeldingen. De bronhouder weet dan altijd waarom het gegeven geregistreerd is. Het is aan te bevelen om "reden van wijziging" vast te leggen aan de hand van een waardelijst, waarbij wellicht bij sommige "gebeurtenissen" sprake kan zijn van een combinatie van redenen uit deze waardelijst. Een correctie is ook een in deze waardelijst op te nemen "gebeurtenis". 

Alleen in uitzonderingsgevallen is het nodig om de "reden van wijziging" vast te leggen in de vorm van een formeel brondocument. Alleen wanneer er sprake is van een bestaand brondocument (zoals een vergunning) heeft een verwijzing naar dit formele document toegevoegde waarde. In de SOR kunnen verplichtingen tot het opstellen van brondocumenten, uitsluitend om daarmee een "reden van wijziging" als metagegeven te kunnen vastleggen, dan vervallen.

4.	Het aspect autorisaties betreft de formele voorschriften over bronhouders en afnemers. Hieronder vallen bijvoorbeeld de gebruiksautorisaties en daarmee de mate van openbaarheid. Het uitgangspunt van de SOR is dat alle gegevens als open data beschikbaar zijn. Daarbij is het aspect van gebruikersautorisaties minder relevant.
Naast gebruikersautorisatie is ook mutatieautorisatie gewenst, zodat bekend is wie bepaalde mutaties mag aanbrengen. Daarmee is ook duidelijk waar men moet zijn bij een vraag over een waarde van een gegeven. Default is dat de bronhouder van het desbetreffende objecttype/object, maar bij uitzondering kan dat een andere partij zijn en die moet daar dan wel voor zijn geautoriseerd en dat moet vastgelegd kunnen worden op attribuutniveau.

Bij geometrie kan het noodzakelijk zijn dat de bronhouder van een bepaald object ook aangrenzende objecten die in beheer zijn van andere bronhouders meeneemt in de mutatie van de geometrie. Anders is een dekkende geometrie niet te realiseren. Je moet dan de mogelijkheid hebben de geometrie van een object van een andere bronhouder te muteren, maar dan moet ook vastgelegd worden dat deze wijziging afkomstig is van een wijziging door deze andere bronhouder. De situaties waarin dit aan de orde is komen tot uitdrukking in paragraaf [Topologie](#topologie).

5.	De meta-informatie over de geldende kwaliteitseisen beschrijft de normkwaliteit die van belang is voor bronhouders voor de inrichting van de bijhoudingsprocessen en voor de gebruikers voor het beoordelen of de gegevens geschikt zijn voor de toepassing waarvoor men de SOR wil gebruiken. Deze meta-informatie kan de vorm hebben van kwantitatieve eisen aan de nauwkeurigheid (bijvoorbeeld de eis aan de gebruiksoppervlakte in de BAG), kwantitatieve eisen aan de frequentie van controle (bijvoorbeeld kenmerk moet tenminste eenmaal per vijf jaar worden gecontroleerd) of eisen aan de wijze van inwinning.

De gewenste controlefrequentie kan sterk verschillen per objecttype/attribuuttype. De begrenzing van een woonplaats zal immers in de werkelijkheid minder aan verandering onderhevig zijn dan de geometrie van de achtergevel van een woning.

6.	De meta-informatie over de precisie en betrouwbaarheid van de gegevens worden breed gezien als de belangrijkste metagegevens. Er bestaat echter nog geen gezamenlijk beeld hoe deze precisie en betrouwbaarheid objectief en kwantitatief op een doelmatige wijze bepaald en geregistreerd kan worden.

Tot de gewenste meta-informatie over kwaliteit hoort in ieder geval wijze van inwinning (controle) en controledatum die wel eenvoudig geregistreerd kunnen worden. Voor het vastleggen van de precisie van gegevens (met name geometrie) lijkt het vastleggen van de bereikte precisie in de vorm van een klasse van nauwkeurigheid een haalbare optie. De geometrie van een zandweg valt dan in een minder nauwkeurige klasse dan de geometrie van een pand. De zorgen over de uitvoerbaarheid van het bijhouden van deze meta-informatie zullen moeten worden weggenomen door de functionaliteit van de bijhoudingssoftware. De bijhoudingssystemen zouden dan bijvoorbeeld in één keer voor alle objecten in een gecontroleerd gebied deze metagegevens moeten kunnen registreren. Het vastleggen van een controledatum, verhoogt de betrouwbaarheid, ook al is er aan de vastlegging van het object niets gewijzigd. Je laat daarmee zien aan de gebruikers dat de waarde van een gegeven nog steeds actueel is en een (aangrenzende) bronhouder in dat gebied kan zien dat object al bekeken is. 

7.	Meta-informatie over de status van de gegevens is bijvoorbeeld om te beoordelen of een (overheids-) gebruikers van de registratie verplicht is de desbetreffende gegevens te gebruiken. Bijvoorbeeld wanneer een attribuut de status "inOnderzoek" heeft vervalt de gebruiksplicht. Daarnaast zal de SOR bestaan uit verplichte inhoud en optionele inhoud. De status "optioneel" zal dan ook betekenen dat het gebruiken van die gegevens niet verplicht is.

De status "inOnderzoek" is inmiddels binnen de basisregistraties voldoende bekend. Deze status hangt samen met formele terugmeldingen door gebruikers. Daarnaast valt te overwegen om op een vergelijkbare manier een status te kunnen aangeven voor "inBewerking" (bijvoorbeeld wanneer de gemeente zelf met de inmeting van een gegeven bezig is), voor "inDiscussie" (bij bijvoorbeeld een metingsverschil tussen twee aangrenzende bronhouders), "reactieBelanghebbende" (wanneer in het kader van "Regie op gegevens" een betrokkene suggesties heeft gedaan voor aanpassingen).

Voor de meta-informatie over "inOnderzoek" is het ook nuttig om apart te kunnen raadplegen dat een terugmelding is onderzocht en afgewezen. Het kan handig zijn (voor zowel een eventuele terugmelder als de bronhouder die moet onderzoeken) te weten dat er een melding is geweest, maar dat onderzoek heeft opgeleverd dat die melding onterecht was. Dat scheelt mogelijk bij een volgende melding, ook een in de directe nabijheid. Deze behoefte aan een metagegeven moet wel gezien worden in het licht van het vastleggen van de historie van terugmeldingen.

#### Specificeren meta-informatie in informatiemodel
De specificaties van het informatiemodel voor de SOR zullen uiteindelijk een deel van de in de inleiding beschreven meta-informatie geven. De informatiemodellering voor de SOR wordt gedaan conform het MIM (Metamodel voor informatiemodellering). Dit metamodel borgt dat diverse genoemde aspecten van de meta-informatie aandacht krijgen in het informatiemodel. Andere aspecten van de meta-informatie zullen bij het opstellen van de specificaties van het informatiemodel wel aparte aandacht moeten krijgen.

Bij het uiteindelijk formuleren van het informatiemodel voor de SOR worden de definitieve keuze gemaakt welke metagegevens geregistreerd worden per objecttype, per attribuuttype, per object, respectievelijk per attribuut.

 
Ontwerpprincipe 

**De metagegevens per objecttype en per attribuuttype vormen een integraal onderdeel van de SOR**

Om recht te doen aan dit Ontwerpprincipe zodat deze metagegevens net zo toegankelijk zijn als de gegevensverzameling zelf en er virtueel één geheel mee vormen, zodat bijvoorbeeld de kwaliteit van de data soepel en geautomatiseerd zonder extra handelingen met de normkwaliteit kan worden vergeleken" is het belangrijk dat de specificaties van dit informatiemodel optimaal ontsloten zijn en direct gerelateerd zijn aan de registratie zelf.

**Per objecttype** wordt in het informatiemodel de volgende meta-informatie vastgelegd:

-	Definitie van objecttype.

-	Autorisatie wat betreft gebruik en beheer. Als default zijn alle objecten in de SOR als open data voor iedereen beschikbaar. Uitzonderingen hierop worden in het informatiemodel expliciet benoemd. 

Daarnaast wordt in het informatiemodel vastgelegd wie de bronhouder is voor een objecttype. Het is mogelijk dat in het informatiemodel wordt gespecificeerd dat er verschillende (categorieën) bronhouders zijn voor één objecttype. De bronhouder is de partij die objecten kan opvoeren en afvoeren.

-	Op het terrein van de kwaliteitseisen wordt de populatie die wordt opgenomen in de SOR beschreven om bijvoorbeeld helder te maken dat niet alle bomen in de SOR worden opgenomen. Aanvullend zal een eis over binnen welke termijn (aantal dagen/maanden) na realisatie/ontstaan van een object, dit object beschikbaar moet zijn in de SOR, gespecificeerd moeten worden.
-	Per objecttype wordt aangegeven of het objecttype behoort tot de verplichte inhoud van de SOR of optioneel is.


**Per attribuuttype** wordt in het informatiemodel de volgende meta-informatie vastgelegd:
-	Definitie van attribuuttype.

-	Autorisatie wat betreft gebruik en beheer wanneer deze afwijken van de autorisatie voor het objecttype. Het is bijvoorbeeld mogelijk dat in de SOR voor een bepaald attribuut een andere bronhouder (attribuuthouder) wordt aangewezen.

-	De kwaliteitseisen per attribuuttype vormen een belangrijk deel van de specificaties van een attribuuttype binnen het informatiemodel. Voorbeelden van relevante kwaliteitseisen per attribuuttype zijn kwantitatieve eisen aan de precisie (vergelijk de eis aan de nauwkeurigheid van de gebruiksoppervlakte in de BAG); eisen aan de wijze van inwinning van het attribuut (bijvoorbeeld de eis dat de geometrie op basis van een luchtfoto ingewonnen moet worden); eisen aan de minimale controlefrequentie (bijvoorbeeld de eis dat tenminste eenmaal per vijf jaar de juistheid van de objecttypering gecontroleerd moet worden).

Bij de geometrie kan sprake zijn van specifieke kwaliteitseisen die voortkomen uit de samenhang met de geometrie van andere objecten. Bijvoorbeeld de eis dat een punt valt binnen de vlakgeometrie van een gerelateerd object, of dat een vlak (naadloos) moet aansluiten op een naastgelegen vlak of moet vallen binnen een ander vlak (bijvoorbeeld de geometrie van de gemeentegrens. Deze kwaliteitseis is relevant voor bronhouders, omdat zij bij de inwinning en controle rekening kunnen houden met deze eisen. Zie hiervoor verder paragraaf [Topologie](#topologie).


-	Per attribuuttype wordt aangegeven of het attribuuttype behoort tot de verplichte inhoud van de SOR of optioneel is.


Naast deze meta-informatie die in het informatiemodel zelf wordt vastgelegd, specificeert het informatiemodel ook welke metagegevens per object en/of per attribuut in de registratie worden opgenomen. 

#### Registeren metagegevens per object
Per object worden de volgende metagegevens vastgelegd:

-	Bronverwijzing: Bij alle objecten wordt vastgelegd de wijziging op grond waarvan het betreffende object in de registratie is opgenomen (of is beëindigd) aan de hand van een waardelijst. Mogelijk "gebeurtenissen" op deze waardelijst zijn bijvoorbeeld "verlenen vergunning", constatering in luchtfoto", "onderzoek terugmelding", etc.).

Afhankelijk van de achtergrond van het opvoeren of beëindigen van een object in de registratie wordt (indien dit in het informatiemodel is gespecificeerd) een verwijzing opgenomen naar een bron(document). Dit kan een formeel document zijn, zoals een vergunning, maar ook bijvoorbeeld plaatsbepalingspunten of een BIM.

-	In het kader van de autorisatie kan per object vastgelegd worden wie de verantwoordelijke bronhouder is. Dat kan bijvoorbeeld de aanduiding zijn welke gemeente verantwoordelijk is voor het bijhouden van het betreffende object. Of dit relevant is en op welke wijze de verantwoordelijke bronhouder wordt geregistreerd, wordt gespecificeerd in het informatiemodel. Ook kan er sprake zijn van het vastleggen van specifieke gebruiksautorisaties (bijvoorbeeld specifieke/militaire objecten die niet openbaar zijn). Of dit aan de orde is, wordt ook gespecificeerd in het informatiemodel. 

-	De metagegevens over kwaliteit en status worden in de SOR in beginsel op het niveau van de afzonderlijke attributen vastgelegd. Natuurlijk kunnen deze metagegevens betrekking hebben op alle attributen van het object (bijvoorbeeld het object met alle attributen is voor het laatst op 14-09-2020 gecontroleerd of alle attributen staan in onderzoek in verband met een terugmelding).

Naast de genoemde metagegevens die gericht zijn op zowel gebruikers als bronhouders, hebben bronhouders aangegeven behoefte te hebben aan een aantekenveld op objectniveau. Dit aantekenveld is met name van belang om als bronhouder onderling aandachtspunten te kunnen uitwisselen. Dat kan zijn verschillende medewerkers van formeel dezelfde bronhouder (verschillende afdelingen van een gemeente die betrokken zijn bij het beheer van de SOR), maar ook formeel verschillende bronhouders, bijvoorbeeld bij grenslijnen tussen objecten in beheer bij ProRail en bij de gemeente.

#### Registreren metagegevens per attribuut
Per attribuut worden de volgende metagegevens vastgelegd:

-   Bronverwijzing: Bij alle attributen wordt vastgelegd de wijziging op grond waarvan het betreffende attribuut (wijziging van een attribuut) in de registratie is opgenomen aan de hand van een waardelijst. Mogelijk "gebeurtenissen" op deze waardelijst zijn bijvoorbeeld "verlenen vergunning", constatering in luchtfoto", "onderzoek terugmelding", etc.). 
-   Bronverwijzing: bij 3D-geometrie wordt vastgelegd hoe deze tot stand is gekomen, bijvoorbeeld door post-processing, door 3D inwinning of anders.
Afhankelijk van de achtergrond van het opvoeren of wijzigen van een attribuut in de registratie wordt (indien dit in het informatiemodel is gespecificeerd) een verwijzing opgenomen naar een bron(document). Dit kan een formeel document zijn, zoals een vergunning, maar ook bijvoorbeeld plaatsbepalingspunten of een BIM.
Bij het attribuut geometrie kan ook sprake zijn van een bronverwijzing naar een plaatsbepalingspunt (zie paragraaf [Meta-gegevens over herkomst en kwaliteit](#meta-gegevens-over-herkomst-en-kwaliteit)).

-   In het kader van de autorisatie kan eventueel per attribuut vastgelegd worden wie de verantwoordelijke bronhouder is, wanneer dit een ander is dan de bronhouder voor het object. Of dit relevant is en op welke wijze de verantwoordelijke bronhouder wordt geregistreerd, wordt gespecificeerd in het informatiemodel. Ook kan er sprake zijn van het vastleggen van specifieke gebruiksautorisaties (bijvoorbeeld specifieke attributen die niet openbaar zijn). Of dit aan de orde is, wordt ook gespecificeerd in het informatiemodel.

Een bijzonder aandachtspunt betreft het vastleggen van de verantwoordelijk bronhouder van geometrie, wanneer dit (vlak)geometrie betreft die (verplicht) aansluit op vlakgeometrie in beheer bij een andere bronhouder. Zie verder paragraaf [Topologie](#topologie).
	
-   Tot de basis metagegevens per attribuut op het aspect van kwaliteit behoren: wijze van inwinning (aan de hand van waardelijst) en uitvoerder inwinning, wijze en moment van controle en uitvoerder controle. Voor de geometrie wordt dit aangevuld met een aanduiding van de klasse van nauwkeurigheid van de geregistreerde geometrie.

-   De status inOnderzoek wordt per attribuut geregistreerd. Op overeenkomstige wijze wordt ook de status "inBewerking" (wanneer de bronhouder zelf gestart is met een onderzoek), en "reactieBelanghebbende" (wanneer een belanghebbende gereageerd heeft in het kader van regie op gegevens). Bij geometrie wordt in overweging gegeven een status "inDiscussie" mogelijk te maken voor gevallen waarin verschillende bronhouders een andere meetuitkomst hebben bij een gezamenlijke grenslijn tussen twee vlakken.



#### Meta-gegevens over herkomst en kwaliteit

In een basisregistratie is het van belang om expliciet informatie over de kwaliteit en herkomst van de geregistreerde gegevens vast te leggen. Dit als verantwoording voor het opnemen, wijzigen of beëindigen van één of meer gegevens in de registratie. Gegevens over kwaliteit en herkomst zijn meta-gegevens over de basisgegevens.

Informatie over de herkomst is belangrijk voor een gebruiker om te weten van welke bronhouder het gegeven afkomstig is. Een bronhouder is een bestuursorgaan of rechtspersoon aan wie bij deze wet de verantwoordelijkheid voor het bijhouden van gegevens is opgedragen. Bronhouder dient de gegevens met de bij wetgeving vastgestelde kwaliteitseisen bij te houden. Gegevens kunnen hiermee als authentiek worden aangemerkt, en een gebruiker mag/kan er dan vanuit gaan dat het gegeven juist is. Bij gerede twijfel over de juistheid kan een gebruiker een terugmelding op het gegeven doen, zodat de bronhouder een onderzoek kan starten.

Een Plaatsbepalingspunt is een punt dat is ingemeten en vervolgens gebruikt is bij en onderdeel uitmaakt van de begrenzing (geometrie) van reële objecten. Bij een plaatsbepalingspunt worden naast de coördinaten (X,Y,Z) van het ingemeten punt zelf, onder meer gegevens over de nauwkeurigheid, inwinningsdatum en inwinnende instantie (bronhouder/gegevensmuteerder) opgenomen. Van plaatsbepalingspunten worden dus zelf metagegevens over kwaliteit en herkomst vastgelegd. Door andere objecten te relateren aan deze plaatsbepalingspunten wordt ook informatie vastgelegd over kwaliteit en herkomst van de geometrie van die objecten.

Voor plaatsbepalingspunten geldt dat:
- alleen van reële objecten plaatsbepalingspunten worden vastgelegd. 
- plaatsbepalingspunten alleen worden opgenomen van coördinaten die daadwerkelijk ingewonnen zijn middels terreinbezoek (terrestrisch), laserscanning (laser), luchtfoto’s of panoramabeelden.  
- plaatsbepalingspunten alleen worden opgenomen voor reële objecten waarvan de grens in het terrein goed is aan te wijzen (ofwel goed idealiseerbaar). Bij niet-goed idealiseerbare objecten is de ‘startwaarde’ van de nauwkeurigheid namelijk al dusdanig hoog dat het geen zin heeft om hier de onnauwkeurigheid van meting. Uitgangspunt is dat bronhouder deze gegevens binnen een bepaalde nauwkeurigheid inwint.
- coördinaten die zijn gegenereerd/afgeleid bijvoorbeeld bij het ‘verstroken’ van een cirkelboog  geen plaatsbepalingspunten hebben.
- van de toekomstige geometrie (planinformatie)  geen plaatsbepalingspunten worden vastgelegd.
- functionele, registratieve en geografische ruimten  geen plaatsbepalingspunten hebben. 


In de SOR worden 

1. 	Meta-gegevens over kwaliteit en herkomst vastgelegd voor 

- goed-idealiseerbare reële objecten middels plaatsbepalingspunten zoals hiervoor beschreven.
- overige reële objecten middels één meta-gegeven bij de geometrie met een aanduiding voor de gemiddelde/mediane/minimale/maximale nauwkeurigheid
- registratieve ruimten middels een brondocument 
- geografische ruimten middels een nader te bepalen bronverwijzing
- functionele ruimten middels een nader te bepalen bronverwijzing

2.	Meta-gegevens over kwaliteit en herkomst worden expliciet gekoppeld  aan de basisgegevens. De aanbeveling is om op te nemen bij

- reële objecten:  de (relatie met) plaatsbepalingspunten , zodat kenbaar is wat de kwaliteit en herkomst is van individuele punten in de geometrie. 
- bij registratieve ruimten de unieke aanduiding van het brondocument 
- bij geografische ruimten een unieke aanduiding van een nader te bepalen bronverwijzing
- bij functionele ruimten een unieke aanduiding van een nader te bepalen bronverwijzing

3.	Plaatsbepalingspunten vastgelegd met de volgende kenmerken:

- Unieke aanduiding
- Coördinaten/puntgeometrie in X,Y,Z. 
- Nauwkeurigheid
- Inwinnende instantie
- Inwinningsdatum


    
*Geometrie en topologie*

Alle objecten hebben een geometrische representatie. De nauwkeurigheid/kwaliteit van de geometrie wordt voor goed-idealiseerbare reële objecten beschreven middels plaatsbepalingspunten en voor niet-goed idealiseerbare objecten middels één meta-object voor de kwaliteit/herkomst. Voorwaarde is dat plaatsbepalingspunten samenvallen met de coördinaten in de objectgeometrie (zie paragraaf [Topologie](#topologie)).

<aside class='example'>
Voorbeelden:
    Casus: Van een gebouw wordt een 3D geometrische representatie gerealiseerd.

    Aanname: bij een gebouw is het mogelijk om zowel geometrie voor grondvlak, bovenaanzicht en 3D op te nemen (dus drie attribuutvelden voor geometrie bij gebouw).

    Voorbeeld  1)	Geometrie grondvlak en geometrie bovenaanzicht hebben Plaatsbepalingspunten. Grondvlak na terrestrisch meten en bovenaanzicht uit fotogrammetrisch meten. De uit grondvlak en bovenaanzicht afgeleide 3D geometrie heeft dan geen eigen Plaatsbepalingspunten.

    Voorbeeld 2)	Via laseraltimetrie: 3D Een gebouw wordt met laseraltimetrie ingewonnen. Alle geometrie-attributen hebben Plaatsbepalingspunten met inwinningsmethode laseraltimetrie. Ontbrekende/geconstrueerde hoekpunten (bijvoorbeeld door ontbreken van een punt als gevolg van een luifel o.i.d.) hebben geen Plaatsbepalingspunten.
</aside>

#### Verdere aandachtspunten meta-informatie

In het voorgaande is een eerste schets gegeven van het onderwerp meta-informatie in de SOR. Bij de verdere uitwerking van het informatiemodel zal daaraan nog een verdere invulling worden gegeven. Een aantal te maken keuzen zijn daarbij afhankelijk van besluiten die nog moeten worden genomen over onder meer de toewijzing van verantwoordelijkheden, de omgang met brondocumenten en de concreet te stellen kwaliteitseisen. Voor deze verdere uitwerking worden nog een aantal aandachtspunten meegegeven:

- Meta-informatie makkelijk kunnen registreren met ondersteuning vanuit de systemen. Dit betekent bijvoorbeeld dat het eenvoudig moet zijn om metagegevens over te nemen naar andere objecten (bijvoorbeeld alle gebouwen binnen een luchtfoto de status "gecontroleerd" te geven),
- Zo effectief en efficiënt mogelijk met tools in de systemen om metagegevens eenvoudig vast te leggen en te controleren op consistentie.
- Niet onnodig muteren (met name van geometrie). Dit kan bijvoorbeeld door alleen het relevante object te muteren en niet gelijk de aangrenzende objecten in de omgeving ook muteren. Het zorgdragen van consistentie van de geometrie is hierbij een aandachtspunt (zie paragraaf [Topologie](#topologie)).
- Zoveel mogelijk werken met domeintabellen in de metadata. Voorbeeld bij inwinning kunnen kiezen uit b.v. terrestrisch, digitalisering, constructie. fotokartering. Dit geldt ook voor "wijze van controle".
- De ervaring uit de BAG leert dat het opvoeren van brondocumenten een zeer tijdrovende bezigheid is met de vraag of het heeft voldaan aan haar doel. Daarom wordt alleen met formele brondocumenten gewerkt als deze om andere reden al bestaan (zoals vergunningen). In andere gevallen wordt volstaan met het gebruik van bijvoorbeeld plaatsbepalingspunten of een luchtfoto als bronverwijzing, dan wel een beschrijving van de herkomst van het gegeven. Dan kan volstaan worden met de aanduiding dat het object geconstateerd is in het veld, zonder de verplicht om een "proces verbaal van constatering" op te maken.


### Historie

#### Uitgangspunten voor historiemodel 

Het globaal semantisch historiemodel voor de samenhangende objectenregistratie is gebaseerd op de volgende uitgangspunten:
-	zo eenvoudig mogelijk. Dus geen registratie en bijhouding van data die niet strikt noodzakelijk zijn voor het beoogde tijdreizen, voor doelmatig beheer door de bronhouder en voor consistentiecontrole op elk willekeurig moment in de tijd. Zo eenvoudig mogelijk betekent ook zo gestandaardiseerd mogelijk. Het model moet geschikt zijn voor alle verschillende objecttypen die binnen de SOR een plek kunnen krijgen en bij voorkeur ook voor andere (basis)registraties. Maximaal aansluiten op bestaande standaarden en ervaringen hoort hier dus ook bij;
-	een eenduidig model. Dat wil zeggen voor alle attributen binnen de Samenhangende objectenregistratie hetzelfde model en dus geen onderscheid tussen geometrie en administratieve gegevens;
-	Stevige basis gelegen in een internationaal perspectief in combinatie met geldende Nederlandse standaarden. Dus zoveel mogelijk conform internationaal breed omarmde uitgangspunten en best practices, die ook teruggevonden worden in bestaande Nederlandse standaarden. Vanuit deze basis is het historiemodel gebaseerd op twee tijdlijnen (tijdlijn geldigheid en tijdlijn registratie);
-	tijdreizen in het verleden en in de toekomst. Voor het vastleggen van tijdlijnen in de toekomst wordt dezelfde systematiek gebruikt als voor tijdlijnen in het verleden. Natuurlijk is deze werkwijze alleen mogelijk wanneer tijdlijnen in de toekomst relatief eenvoudig bijgesteld kunnen worden. Natuurlijk kent alleen de tijdlijn geldigheid data in de toekomst. De tijdlijn registratie is gebaseerd op het moment van registreren en deze wordt in beginsel bepaald door de computerklok;
-	maximale ondersteuning door techniek. De bronhouder moet weinig inspanningen hoeven te doen om de tijdlijnen vast te leggen. Dat hangt deels samen met bepaalde definities (beginGeldigheid van geometrie gemeten in een luchtfoto zal gelijk zijn aan de datum waarop de foto gemaakt is, zonder verplichting tot nader onderzoek, wanneer de werkelijke beginGeldigheid niet blijkt uit andere processen. Ook de te bieden functionaliteit om te bewaken of toekomstmutaties niet ten onrechte in de registratie de status "actuele werkelijkheid" krijgen, door het voortschrijden van de tijd, is daarbij een belangrijke randvoorwaarde.

Het globaal semantisch historiemodel laat zich het best beschrijven vanuit het perspectief van de gebruiker/afnemer. Het model geeft daarmee aan op welke wijze de gebruiker met de gegevens in de SOR een tijdreis kan maken

#### Tijdlijn geldigheid en tijdlijn registratie
Het historiemodel is gebaseerd op twee tijdlijnen, namelijk de tijdlijn geldigheid en de tijdlijn registratie. Daarmee adviseren de experts om de in Nederlandse standaarden veel gebruikte benamingen voor de twee tijdlijnen (materiële en formele historie) niet te gebruiken, omdat tijdens het onderzoek dat aan dit advies ten grondslag ligt, is gebleken dat de begrippen materiële en formele historie in verschillende standaarden en verschillende praktijktoepassingen anders gedefinieerd en toegepast worden.
Hoewel de benaming van de gebruikte tijdlijnen daarmee afwijkt van de bestaande standaarden en praktijktoepassingen zullen de voor deze tijdlijnen gebruikte attributen wel door iedereen worden herkend. Dit zijn voor de tijdlijn geldigheid beginGeldigheid en eindGeldigheid (aangevuld met ingangsdatumObject en einddatumObject voor de bestaansperiode (levensduur) van het object).
Voor de tijdlijn registratie is dit het attribuut tijdstipRegistratie. tijdstipRegistratie betreft de tijdstempel die door de computerklok wordt geplaatst op het moment dat het desbetreffende gegeven (attribuut) beschikbaar wordt gesteld voor de gebruiker.

Het begrip tijdlijn geldigheid suggereert mogelijk dat deze tijdlijn betrekking heeft op formele besluiten etc. De tijdlijn geldigheid heeft ook betrekking op feitelijke kenmerken van fysieke objecten. Deze tijdlijn geeft dan aan of een object op een bepaald moment de desbetreffende geregistreerde eigenschap heeft. Daarom zou gekozen kunnen worden voor alternatieve begrippen zoals tijdlijn bestaan of tijdlijn aanwezigheid. In dit conceptueel model is echter vooralsnog gekozen om ook voor fysieke kenmerken van fysieke objecten het begrip tijdlijn geldigheid te gebruiken, vooral ook omdat dit aansluit op de begrippen beginGeldigheid en eindGeldigheid die in diverse informatiemodellen al worden gebruikt. 

De tijdlijn registratie geldt hierbij als aanvulling op de tijdlijn geldigheid. Met andere woorden er zijn geen attributen waarvoor wel de tijdlijn registratie wordt bijgehouden, maar niet de tijdlijn geldigheid.

De tijdlijn registratie gebruikt uitsluitend het attribuut tijdstipRegistratie. Immers het gaat om het vastleggen van het moment (timestamp van de computer) waarop het betreffende attribuut is geregistreerd, zodat deze beschikbaar kwam voor gebruik. Het in de praktijk ook gebruikte attribuut eindeRegistratie wordt in dit semantisch model niet gebruikt. De beoogde computer timestamp betreft het moment van registratie, waarbij het gegeven beschikbaar komt voor de afnemers.

Deze keuze betekent een wijziging in de wijze van vastlegging van tijdlijnen voor de basisregistraties met hoofdzakelijk geometrie (BGT en BRT), Maar deze keuze is noodzakelijk om een eenduidig historiemodel te kunnen hanteren binnen de gehele samenhangende objectenregistratie. Door de wijze waarop de tijdlijn geldigheid wordt toegepast zal deze omschakeling niet veel consequenties hebben. Bijvoorbeeld geometrie die volledig wordt ontleend aan een opname (bijvoorbeeld luchtfoto) zal als beginGeldigheid (tijdlijn geldigheid) de datum van de luchtfoto krijgen, omdat de feitelijke ingangsdatum niet nauwkeuriger kan worden ingeschat. Wanneer de uit dezelfde foto gemeten geometrie echter betrekking heeft op de contouren van een gebouw, dan zal de beginGeldigheid van de geometrie gelijk zijn aan de beginGeldigheid van de overige attributen van dat gebouw "bij ingebruikname". 

#### Toekomstmutaties
BeginGeldigheid en ook eindGeldigheid kunnen in de toekomst liggen. Hiervoor gelden geen formele beperkingen. Natuurlijk is van de aard van de gebeurtenis afhankelijk of inderdaad een toekomstmutatie voorzien kan worden en met welke nauwkeurigheid deze voorzien kan worden. Wanneer iemand een bouwvergunning krijgt, kan voorzien worden dat dit object in de toekomst ook gerealiseerd zal worden. De datum vanaf wanneer daadwerkelijk sprake zal zijn van een "bestaand object" kan echter niet exact voorzien worden. Een inschatting van deze datum zal de basis vormen voor de tijdlijn geldigheid in de toekomst. Een besluit om met ingang van een bepaalde datum een straatnaam te wijzigen kan wel met een exacte in de toekomst gelegen datum worden geregistreerd. Wij gaan ervan uit dat er adequate voorzieningen worden gerealiseerd die bronhouders ondersteunen om te voorkomen dat voorziene wijzigingen in de toekomst ineens als de bestaande realiteit worden gezien, uitsluitend door verloop van de tijd.
Deze voorziening kan bijvoorbeeld bestaan uit een overzicht van de wijzigingen die in de loop van de komende week/maand de "actuele" situatie gaan worden, omdat de geregistreerde beginGeldigheid ligt in die periode van een week/maand. De bronhouder kan dan of de geregistreerde beginGeldigheid naar verder in de toekomst schuiven op basis van een nadere inschatting van het moment van realiseren of kan constateren dat inderdaad in die periode sprake is van een zodanige wijziging in de "werkelijkheid" dat de geregistreerde "toekomstmutatie" inderdaad in die periode de "werkelijkheid" wordt.

Bij de registratie zijn toekomstmutaties mogelijk. Maar het registreren van toekomstmutaties is niet "de regel". Veel mutaties in de SOR worden aangebracht op basis van "constateringen" en deze worden dan dus vastgelegd met een beginGeldigheid in het verleden, bijvoorbeeld de datum van de luchtfoto waaraan de constatering wordt ontleend.

#### Levensduur
Hoewel het vastleggen van de levensduur van een object (ingangsdatumObject en einddatumObject) redundant is, omdat deze levensduur altijd afgeleid kan worden uit de tijdlijn geldigheid, wordt in het historiemodel ervan uit gegaan dat de levensduur afzonderlijk wordt geregistreerd. De ingangsdatumObject zal gelijk zijn aan de oudste beginGeldigheid voor een status "bestaand/geldig" van het betreffende object. Een gebruiker kan deze ingangsdatumObject eventueel zelf afleiden uit de tijdlijn geldigheid, maar er wordt voor gekozen om, parallel aan de registratie van geboortedatum en overlijdensdatum bij personen, de ingangsdatumObject en einddatumObject wel afzonderlijk in de registratie (of in ieder geval in de informatieproducten) op te nemen.

Gezien deze definitie van ingangsdatumObject kan een object dus al geregistreerd worden (tijdstipRegistratie) vóór deze ingangsdatumObject. Deze registratie van het object heeft in die periode dus betrekking op een status die overeenkomst met een "ontwerp/planfase" (zie hierna de paragraaf over Levensfasen).

#### Toepassing van historie
Het hierboven geschetste model wordt verplicht voor alle onderdelen van de SOR. Afnemers kunnen daarbij per attribuut informatie krijgen over beide tijdlijnen. Deze metagegevens over de beide tijdlijnen zullen echter niet voor alle in de SOR geregistreerde attributen beschikbaar zijn. In het voor de SOR op te stellen informatiemodel zal worden vastgelegd voor welke attributen de tijdlijn geldigheid zal worden bijgehouden en voor welke attributen de tijdlijn geldigheid plus de tijdlijn registratie zal worden bijgehouden. Het aanduiden van het relevant zijn van deze tijdlijnen voor een bepaald attribuut kan in het informatiemodel eenvoudig gebeuren, wanneer dat informatiemodel conform het Metamodel voor informatiemodellen (MIM 1.1) wordt opgesteld (Binnen het MIM 1.1 worden nog wel de begrippen materiële en formele historie gebruikt).

Er zou bijvoorbeeld bij een bepaald attribuut afgezien kunnen worden van het vastleggen van deze tijdlijnen, wanneer geen enkele gebruiker nu of in de toekomst behoefte heeft aan deze tijdlijnen voor het desbetreffende attribuut. Een voorbeeld hiervan zou kunnen zijn de registratie van de toegang tot een verblijfsobject. Dit kenmerk van een verblijfsobject is vooral van belang om hulpdiensten te ondersteunen bij het zo snel mogelijk binnenkomen van een verblijfsobject. Dit is uitsluitend relevant in de actuele situatie. Het in de SOR opnemen van een tijdlijn voor het attribuut toegang is daarom mogelijk niet relevant is, omdat geen enkele afnemer geïnteresseerd is in het feit dat in het verleden de toegang tot dit verblijfsobject elders was. Aan de andere kant kan ook de principiële keuze gemaakt worden dat gegevens in een basisregistratie "niet weggegooid worden". Dat uitgangspunt zou betekenen dat voor alle attributen in de SOR zowel de tijdlijn geldigheid als de tijdlijn registratie verplicht zouden zijn.

Tijdlijnen per attribuut gelden daarbij op semantisch niveau en moeten beschikbaar zijn in de informatieproducten voor gebruikers. Dit model geeft geen richtlijnen over de wijze waarop dit uiteindelijk in de registratie geïmplementeerd gaat worden.

Net als in het informatiemodel per attribuut kan worden vastgelegd of en zo ja welke historie geregistreerd wordt, wordt in het informatiemodel ook gedefinieerd of voor een bepaald objecttype de levensduur (ingangsdatumObject en einddatumObject) wordt vastgelegd. Ook hier hanteren we het uitgangspunt dat in beginsel voor alle objecttypen deze ingangsdatumObject en einddatumObject relevant zijn.

<aside class='example'>
*Nieuwbouwwoning*
Op 1 juli 2020 wordt een bouwvergunning verleend voor een nieuwbouwwoning. Deze wordt direct geregistreerd met alle relevante kenmerken (type woning, gebruiksdoel, gebruiksoppervlakte, bouwjaar, (voorlopige) geometrie).
Verwacht wordt dat de woning per 1 juli 2021 in gebruik genomen zal worden.
Alle kenmerken van deze woning worden geregistreerd met beginGeldigheid 1-7-2020 en tijdstipRegistratie (de computer timestamp op 3-7-2020, wanneer de gegevens worden ingevoerd). De status "Bouw gepland" krijgt naast de beginGeldigheid 1-7-2020 direct een eindGeldigheid 1-7-2021. Met beginGeldigheid 1-7-2021 wordt namelijk de status "Bestaand" geregistreerd.

Op 1 april 2021 constateert de afdeling VTH dat er (eindelijk) begonnen is met de bouw. Dit wordt direct opgenomen in de registratie. Dat betekent dat de status "Bouw gepland" als eindGeldigheid 1-4-2021 krijgt en er een status "In aanbouw" wordt toegevoegd met beginGeldigheid 1-4-2021. Omdat er sprake moet zijn van een consistente tijdlijn zou deze status dan eindGeldigheid 1-7-2021 moeten krijgen om aan te sluiten op de beginGeldigheid van de status "Bestaand". Omdat het onwaarschijnlijk is dat de bouw binnen drie maanden gereed is, krijgt de status "In aanbouw" als einddatum 1-12-2021 en wordt ook beginGeldigheid voor de status "Bestaand" gecorrigeerd naar deze datum.
Op 23-11-2021 geeft het systeem een melding of het klopt dat binnen een week deze woning in gebruik genomen kan gaan worden. De afdeling VTH constateert dat de woning nog niet gereed is en dat het nog zeker twee maanden gaat duren voordat de woning in gebruik genomen kan worden. De eindGeldigheid voor "In aanbouw" en beginGeldigheid voor "Bestaand" wordt verschoven naar 1-2-2022. Hiermee is voor de afdeling WOZ/Belastingen gelijk helder dat sprake is van een woning in aanbouw op 1 januari.

Op 27-1-2022 ontvangt de gemeente een melding dat de woning gereed is. Voor de laatste maal wordt eindGeldigheid voor "in aanbouw" en beginGeldigheid voor "in gebruik" gecorrigeerd.

Op 15-2-2022 worden er luchtfoto's gevlogen die in maart worden uitgewerkt. De gemeente ontleent hieraan de definitieve geometrie van de woning. Deze wordt geregistreerd met beginGeldigheid 27-1-2022, omdat dit ook de datum is waarop de woning de status "Bestaand" heeft gekregen. (De vanuit dezelfde foto ingewonnen geometrie van de singel voor deze woning krijgt als beginGeldigheid 15-2-2022, de datum van de foto.)

</aside>

#### Levensfasen 

**Beschrijving levensfasen**

Om het tijdreizen voor alle gebruikers begrijpelijk en ook flexibel te maken, wordt in de samenhangende objectenregistratie ook gewerkt met levensfasen (statussen) van objecten. Dit heeft te maken met het feit dat bij het tijdreizen in de registratie niet alle gebruikers dezelfde wensen hebben. Bij bijvoorbeeld het raadplegen van de "actuele" situatie in het kader van calamiteiten is alleen relevant wat er ook daadwerkelijk aan objecten aanwezig is (inclusief objecten "In aanbouw"). Maar voor andere werkprocessen zoals vergunningverlening zal men ook willen zien welke objecten in ontwerp of planning zijn.


Objecten kunnen zich in verschillende fasen van ontwikkeling bevinden. Zo’n fase van ontwikkeling van een object duiden we aan met het begrip levensfase. De verschillende levensfasen van een object tezamen vormen de levenscyclus van een object. Welke levensfasen worden onderscheiden is afhankelijk van het specifieke objecttype. In de samenhangende objectenregistratie komen vier soorten objecttypen voor: reële objecttypen, functionele ruimten, registratieve ruimten en geografische ruimten. Elk van deze soorten objecttypen kent dezelfde indeling in hoofdfasen en meestal dezelfde indeling in levensfasen.. Voor de meeste objecttypen van een bepaald soort objecttype zullen de statussen die het object in principe kan aannemen dan ook allemaal gelijk zijn, omdat deze in de regel voortvloeien uit de aard van het soort objecttype. Zo kan een object dat administratief wordt gevormd nooit een status “in aanbouw” kennen. Genuanceerde verschillen worden daarbij niet doorvertaald naar specifieke benamingen van statussen. Voor elk specifiek objecttype moet in de verdere uitwerking van de registratieregels later worden bepaald welke (combinatie van) statuswaarden een verplicht karakter hebben en hoe de statuswaarden moeten worden toegepast.

De levensfase waarin een object zich bevindt kan op twee manieren worden bezien. De eerste is door als de levensfase van een object te zien de feitelijke status van het object in de “echte” werkelijkheid. De tweede manier is de levensfase te beschouwen als de status die het object volgens de bronhouder heeft (gebaseerd op verzamelde informatie vanuit onder meer inwinningsprocessen). Omdat het praktisch gezien onmogelijk is om altijd de feitelijke status van een object te kennen, leggen we in de registratie de veronderstelde status vast en borgen we door een afsprakenstelsel dat deze status zo dicht mogelijk blijft aansluiten op de feitelijke status in de werkelijkheid. De indeling en definities van de verschillende statussen van de levensfasen die hierna zijn opgenomen moeten dan ook worden gezien als registratieve statussen in de context van bijhoudingsprocessen, waarvoor het ook noodzakelijk is statussen te registreren die in de “echte” werkelijkheid nog niet of niet meer zichtbaar zijn.
De hiervoor beschreven benadering leidt tot de volgende levensfasen die objecttypen kunnen aannemen.

*Reële objecten*

|Waarde	|Beschrijving|
|---|---|
|Ontwerp	|Object dat zich in de schets-, ontwerp- of planfase bevindt|
|Bouw gepland	|Object dat nog niet is gebouwd of aangelegd maar waarvoor de voor de bouw of aanleg noodzakelijke ruimtelijke procedures zijn afgerond|
|In aanbouw	|Object waarvan de feitelijke bouw, verbouw of aanleg is aangevangen|
|Bestaand	|Object dat in gebruik is genomen of als gebruiksgereed kan worden beschouwd dan wel buiten gebruik is gesteld|
|Verbouw gepland	|Object dat nog geschikt is voor oorspronkelijk gebruik, maar waarvan de voor de verbouw of wijziging noodzakelijke ruimtelijke procedures zijn afgerond, en de verbouwing of wijziging nog niet is voltooid|
|Sloop gepland	|Object waarvoor de voor de sloop of verwijdering noodzakelijke ruimtelijke procedures zijn afgerond|
|Gesloopt	|Object waarvan de feitelijke sloop of verwijdering is afgerond|
|Afgevoerd	|Object dat ten onrechte is opgevoerd in de registratie of waarvan is vastgesteld dat het ontwerp of een geplande bouw of aanleg niet heeft geleid tot een feitelijke realisatie van het object|

De statussen “in aanbouw”, “bestaand” en “gesloopt” zijn de statussen die behoren bij de levenscyclus van dit object in de “echte” werkelijkheid. De overige statussen zijn toegevoegd om het registratieproces en gebruikersprocessen te ondersteunen. In welke mate statussen moeten worden vastgelegd zal in de registratieregels worden opgenomen.

*Functionele ruimten*

|Waarde	|Beschrijving|
|---|---|
|Ontwerp	|Object dat zich in de schets- of ontwerpfase bevindt|
|In voorbereiding	|Gevormd object waarvan de voor vervulling van de functie noodzakelijke reële objecten nog niet gereed zijn|
|Bestaand	|Object dat geschikt is om zijn functie te vervullen|
|Onbeschikbaar	|Object dat niet geschikt is om zijn functie te vervullen|
|Opgeheven	|Object dat is opgeheven|
|Afgevoerd	|Object dat ten onrechte is opgevoerd in de registratie of waarvan is vastgesteld dat het ontwerp niet heeft geleid tot de feitelijke vorming van het object|

*Registratieve ruimten*

|Waarde	|Beschrijving|
|---|---|
|Ontwerp	|Object waarvan de vaststelling wordt voorbereid|
|Vastgesteld	|Object dat door het bevoegd gezag is benoemd of afgebakend op grond van wet- of regelgeving|
|Ingetrokken	|Object dat door het bevoegd gezag is ingetrokken op grond van wet- of regelgeving|
|Afgevoerd	|Object dat ten onrechte is opgevoerd in de registratie of waarvan de voorbereiding niet heeft geleid tot vaststelling|

Toelichting: De statussen “vastgesteld” en “ingetrokken” zijn de statussen die behoren bij de formele levenscyclus van dit object. De statussen “ontwerp” en “afgevoerd” zijn toegevoegd om het registratieproces te ondersteunen.

*Geografische ruimten*

|Waarde	|Beschrijving|
|---|---|
|Ontwerp	|Object waarvan de vorming wordt voorbereid|
|Bestaand	|Object dat als zodanig wordt onderscheiden|
|Opgeheven	|Object dat niet langer als zodanig wordt aangemerkt|
|Afgevoerd	|Object dat ten onrechte is opgevoerd in de registratie of waarvan de voorbereiding niet heeft geleid tot een in de registratie te onderscheiden object|


De levensfase van een object wordt in de registratie vastgelegd als de eigenschap “status” van het object.
De verbetering (inmeten) van geometrie van een object wordt ten opzichte van bestaande basisregistraties niet langer opgevat als een statusverandering maar als een kwaliteitsverandering. Deze laatste wordt geregistreerd door de opname van meta-informatie.


**Twee levensfasen op hetzelfde moment**

In de regel zal een object op enig moment in de tijd zich bevinden in één levensfase. Wanneer met de bouw van een woning wordt gestart, gaat het object over van de levensfase (status) "Bouw gepland" naar de fase "In aanbouw". Dat sluit allemaal aan bij het werken met een eenduidige tijdlijn geldigheid.

In deze tijdlijn geldigheid kunnen ook toekomstmutaties worden geregistreerd. Bij het registreren van een bouwvergunning kan ook gelijk worden geregistreerd op welk moment in de toekomst deze woning bijvoorbeeld de fase "Bestaand" zal bereiken (dat komt overeen met de werkwijze dat nu in de BAG op het moment van registratie van de vergunning ook het bouwjaar wordt geregistreerd).

Het slechts kunnen registreren van één levensfase (samenhangend met de kenmerken van het object die behoren bij die levensfase) op enig moment op de tijdlijn geldigheid knelt echter wanneer er sprake is van een bestaand object (levensfase Bestaand), waarbij ook sprake is van een planfase voor bijvoorbeeld een verbouwing ("Verbouw gepland).

Dit kan worden geïllustreerd aan de hand van het voorbeeld van een school die momenteel als school in gebruik is, maar die na het lopende schooljaar verbouwd zal worden tot een woning. Wanneer in de loop van het schooljaar de bouwvergunning wordt verleend voor deze verbouwing, dan wordt volgens het huidige historiemodel van de BAG direct de registratie aangepast. Raadplegen van de actualiteit levert dan op dat sprake is van een woning, terwijl de situatie "in gebruik" nog betrekking heeft op een school met leerlingen.
Toepassing van deze aanpak zou kunnen betekenen dat we de beoogde verbouwing niet registreren met beginGeldigheid het moment van verstrekken van de vergunning, maar met het verwachte moment van verbouwing (bijvoorbeeld aanstaande september). Bij die werkwijze kunnen we echter nog niet vastleggen dat op dit moment al sprake is van een verleende vergunning, terwijl je dat wel zou doen, wanneer sprake zou zijn van een nieuwbouwwoning.


Daarom wordt het in dit soort situaties (voor een "Bestaand" gebouw is een vergunning verleend voor verbouw, voor een "Bestaande" weg bestaat het ontwerp voor uitbreiding) in het informatiemodel voor de SOR mogelijk gemaakt dat op dezelfde locatie een tweede object (bijvoorbeeld gebouw of verblijfsobject of wegvak) wordt geregistreerd. Deze werkwijze komt overeen met de huidige werkwijze voor plantopografie binnen IMGeo. Dit nieuw object wordt wel gerelateerd (filiatie) aan het bestaande object waarop het plan betrekking heeft (en vice versa). De registratie van dit tweede object geschiedt verder alsof sprake is van een nieuwbouwsituatie. Echter zodra dit object gericht op een verbouwing ook daadwerkelijk de fase "Bestaand" bereikt, wordt het nieuw opgevoerde object "beëindigd" en wordt de feitelijk situatie weer opgenomen in de tijdlijn geldigheid van het oorspronkelijke object dat vanaf dat moment daadwerkelijk in verbouw is (status "In aanbouw"). Het gerelateerde object dat is gebruikt voor de registratie van deze "planfase" wordt beëindigd en blijft door de relatie vindbaar vanuit het hoofdobject om de informatie over deze planfase te kunnen blijven raadplegen. Deze filiatie in het kader van "twee levensfasen op hetzelfde moment" is overigens de enige vorm van filiatie die in de SOR wordt opgenomen.

<aside class='example'>
Enkele voorbeelden ter illustratie:

Bij een “kleine” verbouwing (wel met vergunning) is een afzonderlijk gerelateerd "planobject" niet nodig. De cyclus van levensfase kan gewoon zijn:

        Bestaand – verbouw gepland – bestaand

Immers de definitie van “verbouw gepland” laat zien dat de verbouwing nog niet is afgerond, maar betekent tevens dat het object nog wel geschikt is voor gebruik. Bijvoorbeeld er is een vergunning verleend voor de verbouw van een woning, terwijl tijdens deze verbouwing men gewoon blijft wonen in deze woning.

Als er sprake is van een “grotere” verbouwing dan zal er een periode zijn dat het object niet meer geschikt is voor gebruik. In die situatie zou je dan hebben:

        Bestaand – verbouw gepland – in aanbouw  – bestaand

Deze wijze van registratie is bijvoorbeeld aan de orde wanneer de nieuwe “bestaande situatie” een duidelijke voortzetting is van de oorspronkelijke situatie, zoals een kantoor dat wordt gestript, gemoderniseerd en weer als kantoor in gebruik wordt genomen.

De SOR registreert alleen een extra gerelateerd "planobject", wanneer de nieuwe bestaande situatie echt afwijkend is (bijvoorbeeld ander gebruiksdoel en/of andere typering en/of sterk afwijkende geometrie).

Dit "planobject" kan bijvoorbeeld worden opgevoerd met de status “Ontwerp”. Op dat moment gebeurt er nog niets met het oorspronkelijke object in de registratie. Alleen wordt het "planobject" wel gerelateerd aan het bestaande object.

Wanneer het "planobject" de status “Bouw gepland” krijgt, krijgt het gerelateerde bestaande object de status “Verbouw gepland”. Daarmee is helder dat het bestaande object nog steeds geschikt is voor gebruik (en dus mogelijk in gebruik is) volgens oorspronkelijke functie. Zodra met de verbouw wordt begonnen en het bestaande object niet meer geschikt is voor gebruik (volgens de oorspronkelijke functie), wordt het gerelateerde "planobject" beëindigd en krijgt het bestaande object de status “In aanbouw”. Gezien de definitie van “In aanbouw” betekent deze status mogelijk ook "in verbouw". Dat is in dit geval de situatie, zoals bijvoorbeeld kan worden afgeleid uit het bouwjaar dat ver terug ligt in het verleden.
</aside>





