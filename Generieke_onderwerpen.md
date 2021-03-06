## Generieke onderwerpen
 
### Identificatie van objecten

Aan elk object wordt een uniek objectnummer (objectidentificatie) toegekend. Zolang het object bestaat, mag deze identificatie niet veranderen. De objectidentificatie moet uniek, betekenisloos, permanent en overal geldig (systeemonafhankelijk) zijn. 

 

#### Opbouw objectidentificatie
Bij de opbouw van de objectidentificatie worden de volgende Ontwerpprincipes gehanteerd.

Ontwerpprincipe: 

**De huidige wijze van objectidentificatie van NEN 3610 wordt gehanteerd want de SOR conformeert zich aan de NEN 3610-norm**

 NEN 3610 eist dat objecten uniek identificeerbaar zijn. De identificatie is de pointer naar het object. Als men het over het object met een bepaalde identificatie heeft (of er naar verwijst) dan wil men zeker weten dat daadwerkelijk dat ene object wordt bedoeld en niet dat men er meerdere ‘terugkrijgt’. 


Ontwerpprincipe: 

**De objectidentificatie voor alle objecten is betekenisloos**

Van belang is dat de objectidentificatie niet betekenisvol geïnterpreteerd mag worden. 


Ontwerpprincipe: 

**De opbouw van de objectidentificatie voor alle objecten is gelijk**

Voor alle objecten in de SOR wordt dezelfde opbouw en toekenning van een objectidentificatie toegepast. De opbouw van de identificatiecode is onderzocht in het externe project Regie Op Bouwgegevens (Unique Object Identifier, UOI) en in een rapport gepubliceerd (
https://www.geobasisregistraties.nl/documenten/rapport/2020/12/01/rapport-regie-op-bouwgegevens-uoi-2020-onderzoeksfase ).
Dit onderzoek, en de uitkomsten uit het vervolgonderzoek medio 2021, kunnen als basis dienen voor het bepalen van de identificatie van de objecten in de samenhangende objectenregistratie.




#### Identiteit

**UNICITEIT**

Ontwerpprincipe: 

**Een objectidentificatie binnen Nederland is volledig uniek**

We willen zeker weten dat we in tijd en ruimte het over hetzelfde object in de SOR hebben. De objectidentificatie moet daarom uniek zijn.
Ontwerpprincipe: een identificatie wordt mondiaal uniek gemaakt door er de landcode aan toe te voegen
Dit is conform de identificatie in NEN 3610.


**HANTEERBAARHEID**

Ontwerpprincipe: 

**Een objectidentificatie in de SOR is machineleesbaar bedoeld**

De objectidentificatie van de SOR is bedoeld om in het kader van interoperabiliteit te gebruiken bij het volledig geautomatiseerd relaties bevragen tussen verschillende datasets.

**IMPLEMENTATIE-VRIJ**

Ontwerpprincipe: 

**De SOR kent een functionele objectidentificatie**

De SOR kent een functionele objectidentificatie. De functionele objectidentificatie is systeem (implementatie) onafhankelijk. 

Ontwerpprincipe: 

**Een functionele objectidentificatie kan een of meer technische identificaties hebben**

De technische objectidentificatie is de toepassing van de functionele identificatie in een technische omgeving. In de technische uitwerking kunnen aan de functionele identificatie een of meer technische identificaties worden gerelateerd die eenduidig met die ene functionele identificatie verbonden zijn, bijvoorbeeld GML,API of URI. Objecten geïmplementeerd in verschillende technische omgevingen moeten middels hun functionele identificatie aan elkaar te relateren zijn. Bijvoorbeeld: een object dat zowel in XML als in JSON als in LD is geïmplementeerd moet herkenbaar zijn als voorkomens van eenzelfde object.

**SAMENHANG**


Ontwerpprincipe: 

**Samenhang faciliteren van huidige basisregistratie-identificaties en de objectidentificatie van de SOR**

De objecten in de huidige basisregistraties hebben een verplichte unieke identificatie, die in veel aanpalende sectorregistraties wordt gebruikt. Gedurende een nader te bepalen (transitie-)periode zal de samenhang moeten worden bijgehouden tussen de identificatie van de SOR en die van de objecten waaruit SOR-objecten zijn ontstaan.

#### Tijd

**PERSISTENT IN DE TIJD**

Ontwerpprincipe: 

**Een objectidentificatie mag niet veranderen in de levensloop van het object zodat tijdreizen maximaal wordt gefaciliteerd**

De objectidentificatie van een object in de SOR moet persistent zijn over de levensloop van dat object, zodat altijd duidelijk is welk object het betreft, ook als het object inmiddels is gesloopt.

**LEVENSLOOP** 


Ontwerpprincipe: 

**De levensloop van een object, met een unieke objectidentificatie, begint in de samenhangende objectenregistratie**

Ontwerpprincipe: 

**De levensloop van een object, met een unieke objectidentificatie, eindigt in de samenhangende objectenregistratie**


#### Uitgifte

Ontwerpprincipe: 

**Uitgifte van dubbele objectidentificaties mag niet voorkomen** 

Er moet een methodiek worden ontwikkeld om uit te sluiten dat dubbele objectidentificaties worden uitgegeven. Tevens moet er direct op getoetst worden bij de voorbereiding van een uitgifte van een identificatie of deze al bestaat om latere schade te voorkomen.

Ontwerpprincipe: 

**Een objectidentificatie wordt toegekend aan een object in de SOR zodra er voor het eerst in de SOR iets over dit object wordt geregistreerd**

Vanwege de eis van persistentie moet de uitgifte van de objectidentificatie direct worden gedaan bij welke registratie van een gegeven en welk moment in de tijdslijn van een object dan ook.


### Aspecten van geometrie

#### Geometrie

In het conceptueel model voor de SOR staan de verschillende begrippen (soorten geo-objecten) die we willen onderscheiden centraal. Deze begrippen worden daarbij nadrukkelijk los gezien van hetgeen in informatieproducten aan gebruikers kan worden getoond in de vorm van onder meer kaartproducten (zie paragraaf [Model van begrippen en informatieproducten](#model-van-begrippen-en-informatieproducten)). Deze benadering heeft ook gevolgen voor de wijze waarop in het conceptueel model wordt omgegaan met geometrie. 

In plaats van uit te gaan van bestaande principes als topologisch sluitende geometrie op maaiveldniveau, wordt in dit conceptueel model gestart vanuit het definiëren van relevante geo-objecten. Geo-objecten worden daarbij gezien als een abstractie van een fenomeen in de werkelijkheid, dat direct of indirect is geassocieerd met een locatie relatief ten opzichte van de aarde. Dit laatste leggen we vast in een coördinaatreferentiesysteem. Voor het scherp kunnen afbakenen van objecten is van belang dat eerst wordt vastgesteld welke objecten we willen kunnen onderscheiden. 

Voor reële objecten wordt daarvoor bepaald welke fenomenen we in de 3D werkelijkheid aantreffen (“waar we ons hoofd tegen kunnen stoten”) en hoe we dat als abstractie willen begrenzen. Dit bepaalt de definitie van een begrip. Vervolgens kan worden vastgesteld hoe verschillende fenomenen zich ten opzichte van elkaar verhouden. Dit bepaalt de relaties die er kunnen bestaan tussen verschillende begrippen. Hierbij kan worden gedacht aan relaties als “ligt bovenop”, “ligt naast” of “is gelegen in”. Tenslotte kan aan de hand van gebruikersbehoeften worden bepaald in hoeverre een fenomeen in de werkelijkheid als abstractie moet worden beschouwd als een volume (3D), een vlak op hoogte (2,5D) of een vlak. Dit bepaalt de geometrische beschrijving van het object.

Geometrie wordt hierbij in de SOR vastgelegd als een eigenschap van een object en representeert daarmee de locatie van een object. Er is één uitzondering in de SOR: alleen nummeraanduiding heeft via het genummerde object een ligging en heeft daarmee geen eigenschap geometrie. Voor de vastlegging van geometrie in de vorm van geometrie-typen wordt verwezen naar de Simple Features, zoals vastgelegd in ISO19125 en OGC 06-103r4 OpenGIS® Implementation Standard for Geographic information - Simple feature access - Part 1: Common architecture Voor ISO19125 zie: https://www.iso.org/standard/40114.html.

Bij het vertalen van de fenomenen in de werkelijkheid naar abstracties in de vorm van begrippen, is vastgesteld dat er vanuit het beoogde gebruik behoefte bestaat om veel fenomenen te beschouwen als volume (3D) of een vlak op hoogte (2,5D). Een geometrie wordt geacht een 3D of 2,5D geometrie te zijn, wanneer deze in absolute zin in een drie dimensionale ruimte wordt vastgelegd (dus met x,y en z coördinaten voor elk vastgelegd punt in een geometrie). Indirecte beschrijvingen van 3D (middels het vastleggen van beschrijvende eigenschappen als Hoogte of Relatieve hoogteligging in combinatie met een 2D geometrie) vallen niet onder de noemer 3D geometrie. Relatieve hoogteliggingen kunnen zo nodig ten behoeve van informatieproducten worden afgeleid.

2,5D geometrie is een uitbreiding op 2D geometrie door aan elke vastgelegde coördinaat een absolute hoogte (z-waarde) toe te voegen. Volumes als geometrietype vormen geen onderdeel van de 2,5D geometrie. 
In het vervolgtraject wordt nader uitgewerkt hoe een golvend oppervlak wordt opgebouwd.


![terreinmodel](media/terreinmodel.png)


3D geometrie is een uitbreiding op 2,5D geometrie door objecten met volumes vast te leggen. Deze volumes kunnen open of gesloten zijn. Bij open volumes kun je door het volume heen bewegen (bijvoorbeeld een weg door een tunnel).
De mate waarin er behoefte bestaat fenomenen te beschouwen als 2D, 2,5D of 3D abstracties verschilt voor de in het conceptueel model onderscheiden hoofdtypen (zie voor een uitwerking van deze hoofdtypen de beschrijving in hoofdstuk [samenhang](#samenhang)).

Ontwerpprincipe:

**De SOR kent voor alle reële objecten een 2,5D geometrie en voor enkele specifiek benoemde reële objecten een 3D geometrie**

Voor bijna alle reële objecttypen volstaat een 2,5D geometrie. Voor enkele reële objecttypen volstaat vanuit het gebruik een 2,5D geometrie niet en nemen we in de SOR een 3D geometrie op.

Ontwerpprincipe

**De SOR kent voor alle functionele ruimten een 2D geometrie en voor de functionele gebouwobjecten een 2,5D geometrie**

Voor functionele ruimten volstaat in de regel een 2D geometrie. Door het leggen van een relatie met een reëel object, kan voor een functioneel object zo nodig hoogte informatie worden afgeleid. Functionele gebouwobjecten zijn een uitzondering. Dit zijn vlakken op hoogte die zich in een 3D volume (het gebouw) bevinden.


#### Coördinaatreferentiesysteem

Ontwerpprincipe:

**In de SOR worden de regels uit NEN 3610 voor het gebruik van coördinaatreferentiesystemen gevolgd**

Het gaat hierbij in elk geval om de volgende regel:

- Iedere geometrie moet zijn voorzien van een verwijzing naar het coördinaatreferentiesysteem waarin de coördinaten van de geometrie zijn beschreven.

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



Coördinaten opgenomen bij een geometrie worden standaard uitgewisseld met een getalsnauwkeurigheid van 1 mm of het equivalent daarvan in graden. Voor RD en NAP  komt dat overeen met de volgende nauwkeurigheden:

- RD in meters 3 decimalen (1 mm);
- NAP-hoogte in meters 3 decimalen (1 mm);
- Alles wat nauwkeuriger is wordt afgerond op deze nauwkeurigheid van 3 decimalen. Afronding is volgens de volgende regel: 0.0015 -> 0.002; 0.0014 -> 0.001.

#### Topologie

In dit conceptueel model worden primair de begrippen gedefinieerd die moeten worden onderscheiden, de relaties beschreven die er tussen deze begrippen bestaan en vastgelegd in hoeverre deze begrippen dan als 2D, 2,5D of 3D in de registratie zouden moeten worden beschreven. De vertaling hiervan naar inwin-instructies (wat wordt er wel en wat wordt er niet meegenomen als onderdeel van de geometrie van het object) en de eisen die gesteld moeten worden aan geometrische consistentie (zoals topologie-regels) moeten hieraan volgend zijn. Voor de nadere invulling daarvan is een belangrijk verschil ten opzichte van de huidige situatie dat het hanteren van een 3D abstractie van de werkelijkheid leidt tot andere en meer complexere relaties tussen objecten. 

Het begrip maaiveld als een referentielaag (met de relatieve hoogte waarde “nul”) waarin veruit de meeste objectgeometrieën voorkomen, wordt hierbij minder relevant. In de praktijk blijken er vanuit verschillende perspectieven namelijk andere behoeften te zijn voor wat betreft maaiveld. Het is belangrijker om ervoor te zorgen dat objecten die zich in de werkelijkheid op een bepaalde wijze tot elkaar verhouden (bijvoorbeeld een verharding ligt bovenop een overbrugging) ook in de registratie op deze wijze tot elkaar verhouden (bijvoorbeeld dat uit de z-coördinaten van de verharding en de overbrugging blijkt dat de verharding bovenop de overbrugging ligt). De exacte uitwerking van deze relaties in topologie-regels zal later in het traject verder worden uitgewerkt. Daarnaast is het van belang dat er op elke fysieke locatie in de werkelijkheid (elke x,y-coördinaat) altijd tenminste een reëel object aanwezig is (water, begroeiing, gebouw, verharding, kunstwerk, constructies of onbepaald terrein).


Ontwerpprincipe:

**De reële objecten in de SOR bedekken met hun x,y geometrie het volledige grondgebied van Nederland**

Het bovenaanzicht van alle vastgelegde geometrieën van reële objecten bedekt dus heel Nederland. Daarbij blijven er geen gaten over waar geen objecten zijn opgenomen. Hiermee kan er uit de geometrische representaties een volledig dekkend topografisch kaartbeeld als informatieproduct worden opgebouwd. De exacte vertaling van de eis dat er geen gaten mogen bestaan naar gedetailleerde topologie-regels zal later in het traject verder worden uitgewerkt.


Ontwerpprincipe:

**Geometrieën van objecten kunnen boven elkaar liggen**

Uit de hiervoor beschreven benadering volgt dat objecten die zich in de werkelijkheid boven elkaar bevinden, ook in de registratie als boven elkaar liggende objecten zijn opgenomen. Denk bijvoorbeeld aan een stuk verharding dat op een brug ligt, waarbij de brug zich op zijn beurt weer boven water bevindt. Wanneer de hierbij behorende vastgelegde geometrieën middels een bovenaanzicht bekeken worden, zullen deze elkaar overlappen. Vanuit andere aanzichten zal blijken dat deze geometrieën boven elkaar liggen. De keuze van een aanzicht is in de SOR niet bepalend voor de vastlegging, maar de aanleiding voor de ontwikkeling van specifieke informatieproducten.


Ontwerpprincipe:

**Geometrieën van objecten kunnen elkaar uitsluiten**

In de 3D werkelijkheid sluiten twee reële objecten elkaar altijd uit. In een registratie kan ervoor gekozen worden dat de vastgelegde geometrieën van deze objecten elkaar moeten uitsluiten. Voor de SOR zal later uitgewerkt worden voor welke geometrieën van welke objecttypen dit zal worden afgedwongen. Daarbij zal een vertaling plaatsvinden van de eis dat objecten die in de werkelijkheid op elkaar aansluiten ook in de registratie op hun begrenzing exact op elkaar aansluiten (in zowel horizontale vlakken als verticale vlakken en dus nadrukkelijk in drie dimensies).

De bovenstaande principes kunnen ook van toepassing zijn voor specifieke verzamelingen van  functionele ruimten en registratieve- en geografische ruimten. Denk hierbij aan de verzameling van gemeenten waarvan de grenzen precies op elkaar moeten aansluiten.

Tussen verzamelingen kunnen ook topologieregels gelden. Bijvoorbeeld bij netwerken. Aan deze geometrie kunnen eisen worden gesteld in relatie tot reële objecten (zoals een eis dat de netwerkgeometrie zich moet bevinden binnen de contouren van de bijbehorende reële objecten).


Ontwerpprincipe:

**Functionele ruimten zijn niet landsdekkend en mogen elkaar overlappen**

Functionele ruimten zijn niet landsdekkend. Dit betekent dat functionele ruimten het grondgebied van Nederland niet voor 100% bedekken. Functionele ruimten die onder een verschillend begrip vallen mogen elkaar overlappen en er mogen gaten voorkomen. 


Ontwerpprincipe:

**De SOR kent voor alle registratieve en geografische ruimten een 2D geometrie**

Voor registratieve en geografische ruimten volstaat op basis van de bekende gebruiksbehoeften een 2D geometrie.


Ontwerpprincipe:

**Geografische ruimten zijn niet landsdekkend en mogen elkaar overlappen**

Geografische ruimten zijn niet landsdekkend. Dit betekent dat geografische ruimten het grondgebied van Nederland niet voor 100% bedekken. Geografische ruimten die onder een verschillend begrip vallen mogen elkaar bovendien overlappen en er mogen gaten voorkomen.

#### Generalisatie

Bij de uitwerking van de inhoud van de samenhangende objectenregistratie wordt voor de verschillende objecttypen bepaald wat de kleinste geometrische/cartografische eenheid is die nog van belang is voor meerdere gebruikers van de registratie. Dit detailniveau bepaalt daarmee wat voor het betreffende gedeelte van de samenhangende objectenregistratie de kleinste bouwsteen vormt. Het objecttype streek (nauwkeurigheid meter tot hectometer) heeft bijvoorbeeld een heel ander detailniveau dan het objecttype weg of gebouw (nauwkeurigheid centimeter tot decimeter).

Uit de SOR worden [informatieproducten](#model-van-begrippen-en-informatieproducten) samengesteld op zowel grotere schalen (schaal 1:1.000) als kleinere schalen (van schaal 1 op 10.000 tot 1 op 1.000.000). Dit zijn cartografische informatieproducten (data of visualisatie). De kleinschalige informatieproducten worden geautomatiseerd met een landelijk uniform proces samengesteld (automatische generalisatie). In deze context worden de volgende begrippen gehanteerd: 

**cartografisch object** 

Object wat voor visualisatie (op een of meer schaalniveaus) wordt aangemaakt en in dat kader een tijdelijk karakter heeft, wat verbonden is met die specifieke versie op 1 of meer schaalniveaus en van die visualisatie, hoe lang die visualisatie ook beschikbaar is.

**generaliseren (van data of voor visualisatie)**

Het zinvol weglaten, vereenvoudigen, verplaatsen, vergroten, symboliseren en/of aggregeren van de geometrie van objecten (of op attribuutniveau).

**aggregeren**

Het zinvol samenvoegen van objecten tot een nieuw object (zowel op dataniveau als cartografisch niveau); aggregeren kan daarmee ook een aspect van generaliseren zijn.

Uit eerdere consultaties blijkt dat gebruikers geen data-analyses doen op basis van afgeleide kaartschalen. Hooguit voor het aanpassen van visualisatie, symbolen en voor een eenmalige actie waarbij de identificatie niet nodig is. Daarom: 
1.	Is er geen noodzaak voor gegeneraliseerde data-objecttypen 
2.	Zijn cartografische objecttypen voldoende zonder (complexe) afstemmingsrelaties, dat wil zeggen dat bijvoorbeeld aggregatie-relaties eenmalig zijn en niet worden bewaard
3.	Is er geen noodzaak voor unieke universele persistente identificatie van gegeneraliseerde objecten (er wordt geen identificatie bewaard) 

In deze paragraaf worden op een generiek niveau ontwerpprincipes hiervoor benoemd.

Ontwerpprincipe:

**Objecttypen worden enkel en alleen op het voor de SOR meest gedetailleerde noodzakelijke niveau vastgelegd (de kleinste eenheden)**

Dit detailniveau kan per objecttype verschillen. Voor met name geografische objecttypen is vaak een minder gedetailleerd niveau noodzakelijk. Denk bijvoorbeeld aan de begrenzing van een streek als de 'Utrechtse Heuvelrug' of het Continentaal Plat.

Ontwerpprincipe:

**Gegeneraliseerde data objecttypen worden niet opgenomen in de SOR. Ze kunnen wel onderdeel zijn van informatieproducten**

Ontwerpprincipe:

**Cartografische objecttypen worden niet opgenomen in de SOR. Ze kunnen wel onderdeel zijn van informatieproducten**

Cartografische objecten zijn voor gebruikers van belang omdat ze dan hun eigen visualisatie kunnen gebruiken. Deze kunnen op basis van de objecten uit de SOR worden gegenereerd (veelal door generalisatie en/of aggregatie) en in informatieproducten worden opgenomen.

Voor cartografische objecten geldt dat hieraan een eigen tijdelijke identificatie wordt toegevoegd zodat de gebruiker het object kan identificeren voor bijvoorbeeld een terugmelding. Deze identificatie wordt echter niet bewaard. Omdat de identificatie niet wordt bewaard is een eigen levensloop niet aan de orde. Omdat de identificatie niet wordt bewaard is een relatie naar de basisobjecten waaruit ze zijn ontstaan ook niet aan de orde. Dit ligt in lijn met het uitgangspunt dat we niet van een minder (lager) naar een meer (hoger) gedetailleerd niveau terug kunnen gaan. Als het wenselijk is kunnen ten dienste van gebruikers in de producten geometrieën op een lager detailniveau worden aangeboden die gebaseerd zijn op geometrieën van onderliggende basisobjecten op een hoger detailniveau.

Ontwerpprincipe: 

**De kwaliteit van de objecten en de bijbehorende gegevens worden in die mate geborgd dat geautomatiseerde generalisatie probleemloos kan verlopen**

Als dit principe wordt gevolgd, wordt daarmee voorkomen dat bij generalisatie extra handwerk nodig is om het gewenste resultaat te bereiken. Hiermee wordt concreet bedoeld:
- Objecten moeten landelijk uniform, homogeen en een topologisch aaneensluitende geometrie hebben
- Dit moet nader uitgewerkt worden in de informatiemodellering en in de eisen aan de inwinningsregels, hetgeen leidt tot één consistent systeem met een consistente implementatie
- Objecten op verschillende hoogten moeten goed op elkaar aansluiten waar ze elkaar raken en consistent zijn binnen één specifieke schaal

Omdat gegeneraliseerde objecten geen deel uit zullen maken van de SOR, vragen terugmeldingen op gegeneraliseerde cartografische objecten om een specifieke beoordeling (door bijvoorbeeld een behandelaar of door artificiële intelligentie):
- als de terugmelding de generalisatie betreft hoeft deze niet doorgezet te worden naar de bronhouders van de onderliggende data
- als de terugmelding de data betreft dan moet deze worden doorgezet aan de betrokken bronhouders van de objecten uit de SOR

#### Lineair referencing

Bij netwerken worden andere benaderingen gekozen voor het bepalen van de positie op een netwerk. De Lineair Referencing Methode (LRM) gebruiken we om de locatie van veranderingen in de verbindingskenmerken vast te leggen als er geen dringende reden is om de structuur van het netwerk te verstoren door deze verder op te knippen. Het is dus een methode waarbij administratief wordt aangegeven vanaf waar een verandering geldt: bijvoorbeeld vanaf 200 meter vanaf de start van de verbinding geldt een toegestane snelheid van 70 km/h. Lineair referencing wordt ook door Inspire geadviseerd:

![requirement inspire](media/inspire_lrm1.png) 

De volgende figuur laat de werking van linear referencing zien, waarbij het principe wordt geïllustreerd dat wijzigingen in verbindingskenmerken van toepassing zijn vanaf een bepaald punt op het netwerk:

![lineair referencing](media/inspire_lrm2.png)



### Netwerken

In de samenhangende objectenregistratie worden twee transportnetwerken onderscheiden: wegen en spoorwegen. Netwerken zijn een verdere uitwerking van de virtuele objecten transportruimten in het basismodel NEN 3610. En zijn in de SOR opgenomen om functionele eigenschappen te kunnen registreren en om als basis kunnen dienen voor routeringsvraagstukken.

De structuur van een netwerk kenmerkt zich door knopen en verbindingen. De wijze van beschrijven van de structuur is voor alle netwerken hetzelfde. In generieke zin zouden alle netwerken als één geheel kunnen worden beschreven. De netwerken zijn immers ook onderling verbonden. Echter de inhoud verschilt dermate dat het vanuit beheer- en bruikbaarheid praktischer is om de netwerken los van elkaar te beschrijven.


#### Elementen van een netwerk: knopen en verbindingen

Een netwerk bestaat uit knopen en verbindingen. Een knoop is een keuzepunt. Een verbinding geeft de relatie aan tussen twee knopen.  Bijvoorbeeld voor een weggebruiker. Een verbinding verbindt twee direct aanliggende keuzepunten. 

Een knoop en verbinding hebben eigenschappen waarmee een knoop of verbinding beschreven kan worden. Administratieve eigenschappen zoals een straatnaam worden vooral gebruikt voor locatiebepaling. Voor routering zijn eigenschappen die een voorwaarde beschrijven belangrijk om te bepalen hoe een route over het netwerk loopt. Voor wegen zijn bijvoorbeeld rijrichtingen en maximum snelheden dergelijke eigenschappen. 

#### Een netwerk is gerelateerd aan de reële infrastructuur

Een transportnetwerk beschrijft de functionele inrichting van de reële infrastructuur en is daarmee onlosmakelijk mee verbonden. Bij nieuwe aanleg van infrastructuur is het functioneel ontwerp (het netwerk) de basis voor de aanleg van reële infrastructuur. 

Een netwerk heeft vanuit zichzelf geen geometrie in de fysieke werkelijkheid, voor de beschrijving en positionering van transportnetwerken wordt een geometrie toegevoegd en/of wordt verwezen naar de geometrie van de reële infrastructuur.

Ontwerpprincipe:

**Knopen en verbindingen bevinden zich binnen de contouren van de bijbehorende reële objecten.**



#### Detaillering waar nodig

Ontwerpprincipe:

**In de SOR wordt minimaal weg- en baan niveau opgenomen van het wegennetwerk. Strookniveau wordt opgenomen als dit nodig is om het netwerk te kunnen beschrijven.**

Een netwerk is te beschrijven in verschillende niveaus van detail. Of detaillering nodig is hangt van de informatiebehoefte af. De transportnetwerken in de SOR kunnen dus een verschillend detail niveau hebben. Detailniveau van netwerken is niet per definitie hetzelfde als een schaalniveau zoals die gebruikt wordt voor kaarten.

Het detailniveau van een netwerk wordt bepaald door wat nodig is om het netwerk te kunnen beschrijven.
Een wegennetwerk kent functioneel gezien drie niveaus: een weg, een rijbaan en rijstrook niveau. Een eigenschap bepaalt het niveau van detail. Een straatnaam geldt voor de weg en daarmee ook voor de rijbanen en rijstroken die bij die weg behoren. Een busstrook wordt gedefinieerd op strook niveau en een busbaan op baan niveau. 

#### Eigenschappen van knopen en verbindingen

Ontwerpprincipe:

**Eigenschappen van verbindingen die niet voor de hele verbinding gelden worden vastgelegd met lineair referencing.**

Eigenschappen kunnen meerdere malen van waarde veranderen langs een verbinding. Bijvoorbeeld als de straatnaam wijzigt bij het passeren van de gemeente- of woonplaatsgrens. Of als de snelheid op een provinciale weg vlak voor een kruising wordt teruggebracht naar 50 km/h. Als er geen dwingende reden is om de structuur van het netwerk te verstoren door een verbinding op te knippen, worden de eigenschappen bij een verbinding vastgelegd met de methode van lineair referencing. Lineair referencing is een methode waarbij administratief wordt aangegeven bij een verbinding waar op de verbinding een verandering van een bepaalde eigenschap plaatsvindt. Bij de beschrijving van de objecten in dit document is dit bij de eigenschap van het kenmerk aangegeven door de afkorting LR.
Indien een eigenschap meerdere waarden kan bevatten zonder dat er sprake is van een afhankelijkheid van een locatie, dan wordt dit bij de eigenschap aangegeven door de afkorting MV (meervoudig). Bijvoorbeeld als er meerdere routenummers voorkomen op een verbinding.

#### Relaties bij netwerken


Een netwerk kent verschillende type relaties:
Relaties die binnen het netwerk gelegd worden en relaties die met objecten gelegd worden die geen onderdeel zijn van het netwerk, maar wel van belang zijn voor het netwerk.

Relaties die binnen het netwerk gelegd worden zijn onderdeel van het netwerk. Bijvoorbeeld een rijbaan die bestaat uit een aantal rijstroken of ventweg en de bijbehorende hoofdrijbaan.

Er zijn objecten die van belang zijn voor het netwerk maar die niet worden opgenomen als onderdeel van het netwerk. Parkeervakken langs een verbindingen worden wel gerelateerd aan het netwerk omdat dan bekend is bij welke verbinding een parkeervak hoort, maar maken er geen onderdeel uit. Dat wil zeggen dat er geen knoop wordt geïntroduceerd op een parkeervak alsof het een doodlopende weg is.

Binnen een netwerk wordt onderscheid gemaakt naar verbindingen tussen knopen, verbindingen waarover een voertuig/weggebruiker/trein zich kan verplaatsen en verbindingen tussen (netwerk-)objecten die een logische samenhang kennen. Deze laatste categorie verbindingen wordt een hyperverbinding genoemd.




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

2.	Alle meta-informatie die een tijdsaspect heeft (historie, levensfase) komt in de  paragraaf  [Historie](#historie) afzonderlijk aan de orde.

3.	Bronverwijzing betreft aan de ene kant de formele onderbouwing van gegevens, bijvoorbeeld in de vorm van formele brondocumenten, zoals vergunningen en besluiten, maar aan de andere kant ook de meer technische bron van de gegevens, zoals plaatsbepalingspunten en indirect luchtfoto's, metingen en BIM-modellen. De plaatsbepalingspunten zijn daarmee een bijzondere vorm van bronverwijzing in het kader van de geometrie binnen de SOR.     Zowel de bronverwijzing naar de praktische bronnen (luchtfoto's etc.) als naar de formele brondocumenten (vergunningen, huisnummerbesluiten) gebeurt zoveel mogelijk door het vastleggen van de url van de vindplaats van de desbetreffende bron. Op deze manier is de vindbaarheid van de bron optimaal gewaarborgd, mits ook het beheer van deze digitale brondocumenten zorgvuldig is ingeregeld. Een ander aspect van de bronverwijzing is de vastlegging van de reden van wijziging van een attribuut. Voor de SOR wordt voorgesteld het uitgangspunt te hanteren dat bij elke wijziging van een attribuut ook een reden wordt geregistreerd. Deze verplichting vereenvoudigt bijvoorbeeld het afhandelen van terugmeldingen. De bronhouder weet dan altijd waarom het gegeven geregistreerd is. Het is aan te bevelen om "reden van wijziging" vast te leggen aan de hand van een te benoemen redenen, waarbij wellicht bij sommige "gebeurtenissen" sprake kan zijn van een combinatie van redenen. Een correctie is ook een voorbeeld van een "gebeurtenis". 

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

-	Bronverwijzing: Bij alle objecten wordt vastgelegd de wijziging op grond waarvan het betreffende object in de registratie is opgenomen (of is beëindigd). Mogelijke "gebeurtenissen" worden zoveel mogelijk gestandaardiseerd en zijn bijvoorbeeld "verlenen vergunning", constatering in luchtfoto", "onderzoek terugmelding", etc.).

Afhankelijk van de achtergrond van het opvoeren of beëindigen van een object in de registratie wordt (indien dit in het informatiemodel is gespecificeerd) een verwijzing opgenomen naar een bron(document). Dit kan een formeel document zijn, zoals een vergunning, maar ook bijvoorbeeld plaatsbepalingspunten of een BIM.

-	In het kader van de autorisatie kan per object vastgelegd worden wie de verantwoordelijke bronhouder is. Dat kan bijvoorbeeld de aanduiding zijn welke gemeente verantwoordelijk is voor het bijhouden van het betreffende object. Of dit relevant is en op welke wijze de verantwoordelijke bronhouder wordt geregistreerd, wordt later gespecificeerd. Ook kan er sprake zijn van het vastleggen van specifieke gebruiksautorisaties (bijvoorbeeld specifieke/militaire objecten die niet openbaar zijn). Of dit aan de orde is, wordt later gespecificeerd. 

-	De metagegevens over kwaliteit en status worden in de SOR in beginsel op het niveau van de afzonderlijke attributen vastgelegd. Natuurlijk kunnen deze metagegevens betrekking hebben op alle attributen van het object (bijvoorbeeld het object met alle attributen is voor het laatst op 14-09-2020 gecontroleerd of alle attributen staan in onderzoek in verband met een terugmelding).

Naast de genoemde metagegevens die gericht zijn op zowel gebruikers als bronhouders, hebben bronhouders aangegeven behoefte te hebben aan een aantekenveld op objectniveau. Dit aantekenveld is met name van belang om als bronhouder onderling aandachtspunten te kunnen uitwisselen. Dat kan zijn verschillende medewerkers van formeel dezelfde bronhouder (verschillende afdelingen van een gemeente die betrokken zijn bij het beheer van de SOR), maar ook formeel verschillende bronhouders, bijvoorbeeld bij grenslijnen tussen objecten in beheer bij ProRail en bij de gemeente.

#### Registreren metagegevens per attribuut
Per attribuut worden de volgende metagegevens vastgelegd:

-   Bronverwijzing: Bij alle attributen wordt vastgelegd de wijziging op grond waarvan het betreffende attribuut (wijziging van een attribuut) in de registratie is opgenomen. Mogelijke "gebeurtenissen" worden zoveel mogelijk gestandaardiseerd en zijn bijvoorbeeld "verlenen vergunning", constatering in luchtfoto", "onderzoek terugmelding", etc.). 
-   Bronverwijzing: bij 3D-geometrie wordt vastgelegd hoe deze tot stand is gekomen, bijvoorbeeld door post-processing, door 3D inwinning of anders.
Afhankelijk van de achtergrond van het opvoeren of wijzigen van een attribuut in de registratie wordt (indien dit in het informatiemodel is gespecificeerd) een verwijzing opgenomen naar een bron(document). Dit kan een formeel document zijn, zoals een vergunning, maar ook bijvoorbeeld plaatsbepalingspunten of een BIM.
Bij het attribuut geometrie kan ook sprake zijn van een bronverwijzing naar een plaatsbepalingspunt (zie paragraaf [Meta-gegevens over herkomst en kwaliteit](#meta-gegevens-over-herkomst-en-kwaliteit)).

-   In het kader van de autorisatie kan eventueel per attribuut vastgelegd worden wie de verantwoordelijke bronhouder is, wanneer dit een ander is dan de bronhouder voor het object. Of dit relevant is en op welke wijze de verantwoordelijke bronhouder wordt geregistreerd, wordt later gespecificeerd. Ook kan er sprake zijn van het vastleggen van specifieke gebruiksautorisaties (bijvoorbeeld specifieke attributen die niet openbaar zijn). Of dit aan de orde is, wordt later gespecificeerd.

Een bijzonder aandachtspunt betreft het vastleggen van de verantwoordelijk bronhouder van geometrie, wanneer dit (vlak)geometrie betreft die (verplicht) aansluit op vlakgeometrie in beheer bij een andere bronhouder. Zie verder paragraaf [Topologie](#topologie).
	
-   Tot de basis metagegevens per attribuut op het aspect van kwaliteit behoren: wijze van inwinning en uitvoerder inwinning, wijze en moment van controle en uitvoerder controle. Voor de geometrie wordt dit aangevuld met een aanduiding van de klasse van nauwkeurigheid van de geregistreerde geometrie.

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
- Het werken met formele brondocumenten is een belangrijk aspect van een basisregistratie waar de herkomst van gegevens naspeurbaar moet zijn. Deze formele brondocumenten worden voor die gegevens gehanteerd waarvoor ze voorhanden zijn (zoals vergunningen). De SOR bevat ook gegevens waarvoor dergelijke formele brondocumenten niet nodig zijn. In die gevallen wordt volstaan met het gebruik van bijvoorbeeld plaatsbepalingspunten of een luchtfoto als bronverwijzing, dan wel een beschrijving van de herkomst van het gegeven. Dan kan volstaan worden met de aanduiding dat het object geconstateerd is in het veld, zonder de verplichting om een "proces verbaal van constatering" op te maken.


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

De tijdlijn registratie gebruikt uitsluitend het attribuut tijdstipRegistratie. Immers het gaat om het vastleggen van het moment (timestamp van de computer) waarop het betreffende attribuut is geregistreerd, zodat deze beschikbaar kwam voor gebruik. Het in de praktijk ook gebruikte attribuut eindeRegistratie wordt in dit semantisch model niet gebruikt. De beoogde computer timestamp betreft het moment van registratie, waarbij het gegeven beschikbaar komt voor de gebruikers.

Deze keuze betekent een wijziging in de wijze van vastlegging van tijdlijnen voor de basisregistraties met hoofdzakelijk geometrie (BGT en BRT), Maar deze keuze is noodzakelijk om een eenduidig historiemodel te kunnen hanteren binnen de gehele samenhangende objectenregistratie. Door de wijze waarop de tijdlijn geldigheid wordt toegepast zal deze omschakeling niet veel consequenties hebben. Bijvoorbeeld geometrie die volledig wordt ontleend aan een opname (bijvoorbeeld luchtfoto) zal als beginGeldigheid (tijdlijn geldigheid) de datum van de luchtfoto krijgen, omdat de feitelijke ingangsdatum niet nauwkeuriger kan worden ingeschat. Wanneer de uit dezelfde foto gemeten geometrie echter betrekking heeft op de contouren van een gebouw, dan zal de beginGeldigheid van de geometrie gelijk zijn aan de beginGeldigheid van de overige attributen van dat gebouw "bij ingebruikname". 

#### Toekomstmutaties
BeginGeldigheid en ook eindGeldigheid kunnen in de toekomst liggen. Hiervoor gelden geen formele beperkingen. Natuurlijk is van de aard van de gebeurtenis afhankelijk of inderdaad een toekomstmutatie voorzien kan worden en met welke nauwkeurigheid deze voorzien kan worden. Wanneer iemand een bouwvergunning krijgt, kan voorzien worden dat dit object in de toekomst ook gerealiseerd zal worden. De datum vanaf wanneer daadwerkelijk sprake zal zijn van een "bestaand object" kan echter niet exact voorzien worden. Een inschatting van deze datum zal de basis vormen voor de tijdlijn geldigheid in de toekomst. Een besluit om met ingang van een bepaalde datum een straatnaam te wijzigen kan wel met een exacte in de toekomst gelegen datum worden geregistreerd. Wij gaan ervan uit dat er adequate voorzieningen worden gerealiseerd die bronhouders ondersteunen om te voorkomen dat voorziene wijzigingen in de toekomst ineens als de bestaande realiteit worden gezien, uitsluitend door verloop van de tijd.
Deze voorziening kan bijvoorbeeld bestaan uit een overzicht van de wijzigingen die in de loop van de komende week/maand de "actuele" situatie gaan worden, omdat de geregistreerde beginGeldigheid ligt in die periode van een week/maand. De bronhouder kan dan of de geregistreerde beginGeldigheid naar verder in de toekomst schuiven op basis van een nadere inschatting van het moment van realiseren of kan constateren dat inderdaad in die periode sprake is van een zodanige wijziging in de "werkelijkheid" dat de geregistreerde "toekomstmutatie" inderdaad in die periode de "werkelijkheid" wordt.

Bij de registratie zijn toekomstmutaties mogelijk. Maar het registreren van toekomstmutaties is niet "de regel". Veel mutaties in de SOR worden aangebracht op basis van "constateringen" en deze worden dan dus vastgelegd met een beginGeldigheid in het verleden, bijvoorbeeld de datum van de luchtfoto waaraan de constatering wordt ontleend. Bij de verdere uitwerking in registratievoorschriften zal nog worden bepaald in welke gevallen en op welke wijze toekomstige gegevens zullen worden opgenomen.

#### Levensduur
Hoewel het vastleggen van de levensduur van een object (ingangsdatumObject en einddatumObject) redundant is, omdat deze levensduur altijd afgeleid kan worden uit de tijdlijn geldigheid, wordt in het historiemodel ervan uit gegaan dat de levensduur afzonderlijk wordt geregistreerd. De ingangsdatumObject zal gelijk zijn aan de oudste beginGeldigheid voor een status "bestaand/geldig" van het betreffende object. Een gebruiker kan deze ingangsdatumObject eventueel zelf afleiden uit de tijdlijn geldigheid, maar er wordt voor gekozen om, parallel aan de registratie van geboortedatum en overlijdensdatum bij personen, de ingangsdatumObject en einddatumObject wel afzonderlijk in de registratie (of in ieder geval in de informatieproducten) op te nemen.

Gezien deze definitie van ingangsdatumObject kan een object dus al geregistreerd worden (tijdstipRegistratie) vóór deze ingangsdatumObject. Deze registratie van het object heeft in die periode dus betrekking op een status die overeenkomst met een "ontwerp/planfase" (zie de paragraaf over [Levensfasen](#levensfasen)).

#### Toepassing van historie
Het hierboven geschetste model wordt verplicht voor alle onderdelen van de SOR. Gebruikers kunnen daarbij per attribuut informatie krijgen over beide tijdlijnen. Deze metagegevens over de beide tijdlijnen zullen echter niet voor alle in de SOR geregistreerde attributen beschikbaar zijn. In het voor de SOR op te stellen informatiemodel zal worden vastgelegd voor welke attributen de tijdlijn geldigheid zal worden bijgehouden en voor welke attributen de tijdlijn geldigheid plus de tijdlijn registratie zal worden bijgehouden. Het aanduiden van het relevant zijn van deze tijdlijnen voor een bepaald attribuut kan in het informatiemodel eenvoudig gebeuren, wanneer dat informatiemodel conform het Metamodel voor informatiemodellen (MIM 1.1) wordt opgesteld (Binnen het MIM 1.1 worden nog wel de begrippen materiële en formele historie gebruikt).

Er zou bijvoorbeeld bij een bepaald attribuut afgezien kunnen worden van het vastleggen van deze tijdlijnen, wanneer geen enkele gebruiker nu of in de toekomst behoefte heeft aan deze tijdlijnen voor het desbetreffende attribuut. Een voorbeeld hiervan zou kunnen zijn de registratie van de toegang tot een verblijfsobject. Dit kenmerk van een verblijfsobject is vooral van belang om hulpdiensten te ondersteunen bij het zo snel mogelijk binnenkomen van een verblijfsobject. Dit is uitsluitend relevant in de actuele situatie. Het in de SOR opnemen van een tijdlijn voor het attribuut toegang is daarom mogelijk niet relevant is, omdat geen enkele gebruiker geïnteresseerd is in het feit dat in het verleden de toegang tot dit verblijfsobject elders was. Aan de andere kant kan ook de principiële keuze gemaakt worden dat gegevens in een basisregistratie "niet weggegooid worden". Dat uitgangspunt zou betekenen dat voor alle attributen in de SOR zowel de tijdlijn geldigheid als de tijdlijn registratie verplicht zouden zijn.

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


Objecten kunnen zich in verschillende fasen van ontwikkeling bevinden. Zo’n fase van ontwikkeling van een object duiden we aan met het begrip levensfase. De verschillende levensfasen van een object tezamen vormen de levenscyclus van een object. Welke levensfasen worden onderscheiden is afhankelijk van het specifieke objecttype. In de samenhangende objectenregistratie komen vier soorten objecttypen voor: reële objecttypen, functionele ruimten, registratieve ruimten en geografische ruimten. Elk van deze soorten objecttypen kent dezelfde indeling in hoofdfasen en meestal dezelfde indeling in levensfasen. Voor de meeste objecttypen van een bepaald soort objecttype zullen de statussen die het object in principe kan aannemen dan ook allemaal gelijk zijn, omdat deze in de regel voortvloeien uit de aard van het soort objecttype. Zo kan een object dat administratief wordt gevormd nooit een status “in aanbouw” kennen. Genuanceerde verschillen worden daarbij niet doorvertaald naar specifieke benamingen van statussen. Voor elk specifiek objecttype moet in de verdere uitwerking van de registratieregels later worden bepaald welke (combinatie van) statuswaarden een verplicht karakter hebben en hoe de statuswaarden moeten worden toegepast. Dat betekent dat niet alle statuswaarden bij alle objecttypen zullen worden toegepast.

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
|In Sloop | Object waarvan een langdurig slooptraject is aangevangen|
|Gesloopt	|Object waarvan de feitelijke sloop of verwijdering is afgerond|
|Afgevoerd	|Object dat ten onrechte is opgevoerd in de registratie of waarvan is vastgesteld dat het ontwerp of een geplande bouw of aanleg niet heeft geleid tot een feitelijke realisatie van het object|

De statussen “in aanbouw”, “bestaand” en “gesloopt” zijn de statussen die behoren bij de levenscyclus van dit object in de “echte” werkelijkheid. De overige statussen zijn toegevoegd om het registratieproces en gebruikersprocessen te ondersteunen. In welke mate statussen moeten worden vastgelegd zal in de registratieregels worden opgenomen.

*Functionele ruimten*

|Waarde	|Beschrijving|
|---|---|
|Ontwerp	|Object dat zich in de schets- of ontwerpfase bevindt|
|In voorbereiding	|Gevormd object waarvan de voor vervulling van de functie noodzakelijke reële objecten nog niet gereed zijn|
|Bestaand	|Object dat geschikt is om zijn functie te vervullen|
|Onbruikbaar	|Object dat niet geschikt is om zijn functie te vervullen|
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

In de regel zal een object op enig moment in de tijd zich bevinden in één levensfase. Wanneer met de bouw van een woning wordt gestart, gaat het object over van de levensfase (status) "Bouw gepland" naar de fase "In aanbouw". Dat sluit allemaal aan bij het werken met een eenduidige tijdlijn geldigheid. In deze tijdlijn geldigheid kunnen indien gewenst ook toekomstmutaties worden geregistreerd. Bij het registreren van een bouwvergunning kan dan bijvoorbeeld ook gelijk worden geregistreerd op welk moment in de toekomst deze woning de fase "Bestaand" zal bereiken (dat komt overeen met de werkwijze dat nu in de BAG op het moment van registratie van de vergunning ook het bouwjaar wordt geregistreerd). In dat geval blijft sprake van een eenduidige tijdlijn geldigheid waarbij een object zich op enig moment in de tijd altijd bevindt in één levensfase

Het slechts kunnen registreren van één levensfase (samenhangend met de kenmerken van het object die behoren bij die levensfase) op enig moment op de tijdlijn geldigheid kan echter knellen wanneer er sprake is van een bestaand object (levensfase “Bestaand”), waarbij er gelijktijdig ook sprake is van een planfase voor bijvoorbeeld een verbouwing (“Verbouw gepland”) aan hetzelfde object. Dit kan worden geïllustreerd aan de hand van het voorbeeld van een school die momenteel als school in gebruik is, maar die na het lopende schooljaar verbouwd zal worden tot een woning. Wanneer in de loop van het schooljaar de bouwvergunning wordt verleend voor deze verbouwing, dan wordt dit volgens het huidige historiemodel van de BAG direct in de registratie aangepast. Raadplegen van de actualiteit levert dan op dat sprake is van een woning, terwijl de feitelijke situatie "in gebruik" nog betrekking heeft op een school met leerlingen. Deze situatie is niet gewenst. 

Toepassing van de hiervoor beschreven systematiek van een eenduidige tijdlijn geldigheid biedt in principe de mogelijkheid om de beoogde verbouwing niet te registreren met als beginGeldigheid het moment van verstrekken van de vergunning, maar met het verwachte moment van verbouwing (bijvoorbeeld aanstaande september). Met deze werkwijze kunnen we echter niet direct vastleggen dat op dit moment al sprake is van een verleende vergunning, terwijl je dat wel zou doen wanneer sprake zou zijn van een nieuwbouwwoning. In dat laatste geval zal er in de registratie immers sprake zijn van de aanwezigheid van een tweetal afzonderlijke objecten (met een eigen unieke objectidentificatie) op dezelfde locatie waarbij het ene object een levensfase “Bestaand” heeft en het andere object een levensfase “Bouw gepland” kent. Deze situatie van twee verschillende levensfasen voor één object op hetzelfde moment doet zich dan ook alleen voor in situaties waarin er geen sprake is van een echt afwijkende nieuwe situatie.

Voor de geschetste uitzonderingssituaties waarin sprake is van het gelijktijdig voorkomen van twee levensfasen op hetzelfde moment (voor een "Bestaand" gebouw is een vergunning verleend voor verbouw) zal binnen het informatiemodel voor de SOR nog een oplossing worden uitgewerkt. Het gaat hier om situaties waarbij de nieuwe bestaande situatie echt afwijkend is (bijvoorbeeld ander gebruiksdoel en/of andere typering en/of sterk afwijkende geometrie). Een belangrijk uitgangspunt hierbij is dat de complexiteit van de oplossing in verhouding moet zijn tot de mate waarin deze situatie zich voordoet. Om die reden is reeds geconstateerd dat een oplossing niet moet worden gezocht in het tijdelijk mogelijk maken van een tweede object op dezelfde locatie dat door middel van filiatie wordt gerelateerd aan het bestaande object waarop het plan betrekking heeft (deze werkwijze komt overeen met de huidige werkwijze voor plantopografie binnen IMGeo). Uniforme toepassing hiervan in een informatiemodel leidt namelijk tot een complexe opbouw van het historiemodel voor alle objecttypen, terwijl de situatie in principe slechts in een beperkt aantal situaties aan de orde is. Een oplossingsrichting die in elk geval nog nader zal worden verkend is de vastlegging van een tweede levensfase in een afzonderlijk attribuut (maar dan uitsluitend daar waar dit relevant is) in combinatie met de mogelijkheden die worden geboden door de vastlegging van meta-informatie op het niveau van een object of een attribuut. Het resultaat van de uitwerking zal worden meegenomen in het informatiemodel.

<aside class='example'>
Enkele voorbeelden ter illustratie:

Bij een “kleine” verbouwing (wel met vergunning) is de cyclus van levensfasen:

Bestaand – verbouw gepland – bestaand

Immers de definitie van “verbouw gepland” laat zien dat de verbouwing nog niet is afgerond, maar betekent tevens dat het object nog wel geschikt is voor gebruik. Er is bijvoorbeeld een vergunning verleend voor de verbouw van een woning, terwijl tijdens deze verbouwing men gewoon blijft wonen in deze woning. In dit voorbeeld zal het verblijfsobject dat binnen dit gebouw is afgebakend in deze periode geen wijzigingen kennen. Het verblijfsobject (bestaand) blijft immers al die tijd geschikt om zijn functie te vervullen.

Als er sprake is van een “grotere” verbouwing dan zal er een periode zijn dat het object niet meer geschikt is voor gebruik. In die situatie zou je dan hebben:

Bestaand – verbouw gepland – in aanbouw – bestaand

Deze wijze van registratie is bijvoorbeeld aan de orde wanneer de nieuwe “bestaande situatie” een duidelijke voortzetting is van de oorspronkelijke situatie, zoals een kantoor dat wordt gestript, gemoderniseerd en weer als kantoor in gebruik wordt genomen. Ook in dit voorbeeld kan sprake zijn van één verblijfsobject binnen dit gebouw. In de periode dat het gebouw de status heeft "in aanbouw" zal dit verblijfsobject echter niet geschikt zijn om zijn functie vervullen en is de status "in voorbereiding" beter van toepassing.

Bij de transitie van een bestaand kantoorgebouw of een bestaand schoolgebouw zal het gebouw (reëel object) een doorlopende tijdlijn geldigheid hebben, maar zullen er wel nieuwe verblijfsobjecten worden gevormd en bestaande verblijfsobjecten beëindigd. Bij een dergelijke ingrijpende transitie zal het gebouw dan ook de volgende levensfasen kennen:

Bestaand – verbouw gepland – in aanbouw – bestaand

Naar verwachting gelijktijdig met de wijziging van "bestaand" naar "verbouw gepland" zullen ook voor de te realiseren woningen nieuwe verblijfsobjecten geregistreerd kunnen worden met de levensfase "in voorbereiding". Deze nieuwe verblijfsobjecten krijgen de status "bestaand" op het moment waarop ook het gebouw weer in deze levensfase wordt geregistreerd. Het bestaande verblijfsobject voor het kantoor of de school blijft de status "bestaand” houden tot het moment waarop daadwerkelijk met de verbouw wordt begonnen (dus gelijktijdig met het registreren van de status "in aanbouw" bij het gebouw). Het verblijfsobject komt dan in de levensfase "opgeheven".
</aside>

Een oplossing zal nog moeten worden gevonden voor de gevallen waarin de nieuwe bestaande situatie echt afwijkend is (bijvoorbeeld ander gebruiksdoel en/of andere typering en/of sterk afwijkende geometrie), terwijl geen sprake is van het vormen van bijvoorbeeld nieuwe verblijfsobjecten. Hierbij is het de bedoeling dat er op het moment van bijvoorbeeld vergunningverlening voor de verbouw nog niets gebeurt met de registratie van het oorspronkelijke object. Wel zal bepaalde informatie over het "planobject" vastgelegd moeten kunnen worden in de registratie. Welke informatie dit betreft en in welke gevallen dit noodzakelijk is zal in de verdere uitwerking nader worden bepaald.


**Filiatie**

In de SOR wordt bij objecten niet de afkomst van een object bijgehouden door de relatie vast te leggen met een object / de objecten waaruit een object is ontstaan of door de relatie vast te leggen met een object / de objecten waarin een object is overgegaan. Dergelijke filiatie (afkomst / overgang van objecten) maakt dus geen onderdeel uit van het model van de SOR. In die situaties waarin de samenhang relevant is tussen objecten die verdwijnen en objecten die ontstaan, zullen gebruikers wel kunnen worden voorzien van de benodigde informatie om de verwerking van de hierbij behorende mutaties op de juiste wijze te kunnen uitvoeren.

Op dit moment is de behoefte bekend aan dergelijke informatie in het geval van samenvoeging en splitsing van verblijfsobjecten. Daar waar dergelijke informatie op dit moment niet kan worden afgeleid uit de BAG, kan deze in het geval van de SOR echter worden samengesteld op basis van gegevens die reeds in het model zijn voorzien (combinatie van 2,5D vlakgeometrie van de oude situatie, 2,5D vlakgeometrie van de nieuwe situatie en de vastlegging van een aanduiding als “splitsing verblijfsobject” of “samenvoeging verblijfsobject” in de meta-informatie). 
