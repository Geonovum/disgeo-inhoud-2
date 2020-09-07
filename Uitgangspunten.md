## Uitgangspunten 

### Inleiding

In de beleidsvisie (schetsontwerp) zijn een groot aantal uitgangspunten opgenomen voor de verdere uitwerking van een samenhangende objectenregistratie. Alle uitgangspunten uit de beleidsvisie blijven onverminderd van toepassing. Een deel van deze uitgangspunten is min of meer direct toepasbaar bij de verdere uitwerking van de inhoud van de samenhangende objectenregistratie. Een ander gedeelte is in het kader van de ontwikkeling van een conceptueel denkkader (hoofdlijnenrapport) verder uitgewerkt. 

In dit hoofdstuk is een samenhangende beschrijving opgenomen van zowel de eerdere uitgangspunten als van de verdere concretisering van enkele daarvan. Een aantal van deze uitgangspunten worden in het conceptueel model verder uitgewerkt. De uitgangspunten zijn niet alleen gehanteerd bij de verdere uitwerking van dit conceptueel model, maar worden ook in de volgende fase van het uitwerken van een informatiemodel toegepast. De uitgangspunten hebben in principe geen betrekking op andere registraties dan de objectenregistratie. Het gesprek daarover vindt plaats aan andere tafels. Alle uitgangspunten hebben betrekking op de uiteindelijke situatie.



### Algemene uitgangspunten

#### Standaardisatie

Ontwerpprincipe:

In de SOR zijn uitsluitend gestandaardiseerde objecttypen en eigenschappen opgenomen.

De inhoud van de objectenregistratie is volledig beschreven in de vorm van een standaard. In de registratie komen dus geen objecttypen voor die niet voldoen aan deze standaard. Ook worden in de objectenregistratie uitsluitend gestandaardiseerde eigenschappen van deze objecttypen opgenomen.

Onderdeel van deze standaardisatie is dat van de verschillende objecttypen en eigenschappen ook de beoogde kwaliteit is beschreven. Van de objecttypen is dus opgenomen welke eisen er worden gesteld aan de volledigheid en actualiteit van de in de registratie opgenomen objecten. Van de eigenschappen van de objecttypen is vastgelegd wat de beoogde actualiteit en nauwkeurigheid van de in de registratie opgenomen gegevens is.

#### Definiëring

ontwerpprincipe:

Definities van zowel objecttypen als eigenschappen van objecttypen zijn scherp afgebakend, niet multi-interpretabel en sluiten waar mogelijk aan op bestaande definities.

Het is van groot belang dat de basis van een informatiemodel voor een samenhangende objectenregistratie wordt gevormd door een aantal onderling goed afgestemde en heldere definities. In de bestaande basisregistraties is daarvan momenteel niet altijd sprake. Hierdoor wordt de onderlinge koppelbaarheid van gegevens beperkt en laat de uniformiteit van de opgenomen gegevens (door interpretatieverschillen of in de definities opgenomen vrijheidsgraden) nogal eens te wensen over. Bij de verdere uitwerking van de inhoud van een samenhangende objectenregistratie worden bestaande definities daarom zodanig uitgebreid en geharmoniseerd dat: 
- een scherp afgebakende en duidelijke definitie van objecttypen en eigenschappen ontstaat;
- definities elkaar semantisch niet overlappen;
- er niet langer gebruik wordt gemaakt van verzamelclassificaties;
- een optimale aansluiting op overkoepelende modellen en sectorale modellen wordt gerealiseerd, zoals NEN 3610 (Basismodel Geo-informatie) en NEN 2660 (Ordeningsregels voor gegevens in de bouw - Termen, definities en algemene regels)

### Flexibiliteit

Ontwerpprincipe:

Objecttypen en eigenschappen van objecttypen worden zodanig in de SOR opgenomen dat uitbreiding en inkrimping van het aantal objecttypen en eigenschappen en het aanpassen van de kwalificatie van objecttypen en eigenschappen als verplicht of vrijwillig binnen het informatiemodel eenvoudig mogelijk is.

Het moet mogelijk zijn om de inhoud van de samenhangende objectenregistratie relatief eenvoudig aan te kunnen passen. Dit begint met een informatiemodel dat dergelijke aanpassingen kan faciliteren. Dat betekent dat bijvoorbeeld het onderscheid tussen verplichte en vrijwillige objecten in de registratie niet diepgaand in het uitgewerkte informatiemodel moet worden verankerd. Of aanpassing ook daadwerkelijk zal plaatsvinden is uiteraard afhankelijk van de afspraken die er worden gemaakt over de wijze waarop besluitvorming over wijzigingen plaatsvindt en hoe er wordt omgegaan met de gevolgen daarvan voor bronhouders en gebruikers. Bij het doorvoeren van dit soort wijzigingen moeten er altijd heldere transitieafspraken worden gemaakt.





### Uitgangspunten structuur

#### Onderscheid verplicht en vrijwillig

Ontwerpprincipe:

Objecttypen en eigenschappen van objecttypen moeten in de SOR worden opgenomen als deze in het kader van de SOR als wettelijk verplicht zijn aangemerkt en mogen in de registratie worden opgenomen als deze als vrijwillig zijn aangemerkt in het kader van de SOR.

![onderscheid verplicht en vrijwillig](media/verplicht_vrijwillig.png)


De grondgedachte van de samenhangende objectenregistratie is dat deze bestaat uit:

- verplichte en gestandaardiseerde objecttypen en eigenschappen (het formele basisregistratie gedeelte)
- vrijwillige maar wel gestandaardiseerde objecttypen en eigenschappen

Hierbij is het belangrijk dat opname van vrijwillige objecten en gegevens door een bronhouder ook betekent dat deze gegevens blijvend worden bijgehouden. Voor alle opgenomen objecten en gegevens (zowel in het verplichte als het vrijwillige gedeelte) gelden dus blijvend de bijhoudingsregels die behoren bij het betreffende objecttype en eigenschappen. Bij de verdere uitwerking van de organisatie van de samenhangende objectenregistratie zullen afspraken moeten worden gemaakt over de omgang met in de registratie opgenomen objecten en gegevens die blijvend niet aan de bijhoudingsregels voldoen.

Voor het basisregistratie gedeelte gelden de 12 eisen die aan basisregistraties worden gesteld (https://www.digitaleoverheid.nl/overzicht-van-alle-onderwerpen/gegevens/naar-een-gegevenslandschap/themas/twaalf-eisen-stelsel-van-basisregistraties/) en waarvan voor de verdere uitwerking van de inhoud van de samenhangende objectenregistratie met name de eisen 6 (er is duidelijkheid over inhoud en bereik van de registratie) en 11 (de positie van de basisregistratie binnen het stelsel van basisregistraties is duidelijk en de relaties met de basisregistraties zijn beschreven) van belang zijn.

Dit betekent dus dat gebruikers van het verplichte gedeelte van de samenhangende objectenregistratie zekerheid hebben over de volledigheid van de daarin opgenomen objecten en gegevens. Omdat bronhouders de keuze hebben om objecten of gegevens al dan niet op te nemen in het vrijwillige gedeelte van de objectenregistratie, hebben gebruikers van de samenhangende objectenregistratie die zekerheid niet bij de vrijwillig op te nemen objecten en gegevens. In de communicatie rondom de informatieproducten van de samenhangende objectenregistratie zal dit principe en de mate waarin verschillende bronhouders al dan geen gebruik maken van het vrijwillige gedeelte duidelijk gecommuniceerd moeten worden.

#### Onderscheid fysiek en functioneel

Ontwerpprincipe:

In de SOR wordt een expliciet onderscheid gemaakt tussen fysieke en functionele objecttypen.

Bij de uitwerking van de SOR wordt een scheiding aangebracht tussen fysieke objecttypen en functionele objecttypen. De aanleiding is dat definities van functionele objecttypen sterk samenhangen met specifieke gebruikstoepassingen of afsprakenkaders. Fysieke objecttypen worden altijd gedefinieerd door hetgeen in het terrein zichtbaar is. Door in de SOR een strikte scheiding aan te brengen tussen fysieke objecttypen en functionele objecttypen, kunnen duidelijkere regels worden opgesteld over onder meer samenhang en overlap van verschillende objecttypen. Daar waar dat de in de huidige registraties vaak niet mogelijk is, wordt het in de SOR bijvoorbeeld mogelijk dat er meerdere functionele indelingen op één fysieke locatie voorkomen. Hiermee vergroten we de flexibiliteit en de gebruiksmogelijkheden van de SOR enorm. Functionele en fysieke objecttypen worden hierbij altijd als aparte objecttypen gedefinieerd, als de begrenzing ervan kan verschillen.

#### Kleinste semantische eenheden

Ontwerpprincipe: 

Het objectenmodel van de SOR wordt opgebouwd vanuit de kleinste semantische eenheden die het minimum detailniveau aangeven waarvan is vastgesteld dat deze van waarde zijn voor meerdere gebruikers van de registratie.

Bij de uitwerking van de inhoud van de samenhangende objectenregistratie wordt voor de verschillende objecttypen bepaald wat de kleinste semantische eenheid is die nog van belang is voor meerdere gebruikers van de registratie. Dit minimum detailniveau bepaalt daarmee wat voor het betreffende gedeelte van de samenhangende objectenregistratie de kleinste bouwsteen vormt. Op het moment dat bepaalde gebruikers binnen deze kleinste semantische eenheid voor eigen gebruik nog een nadere detaillering wil aanbrengen, dan zal de gebruiker dat als onderdeel van de eigen sectorale registratie zelf nader moeten vormgeven. Hierbij kan bijvoorbeeld worden gedacht aan het nader detailleren van een groenobject in verschillende beplantingsvakken als onderdeel van het werkproces voor het beheren van de openbare ruimte.

Een onderwerp dat in het kader van dit uitgangspunt in het vervolgtraject nog nader zal moeten worden uitgewerkt is de vraag op welke wijze binnen het conceptueel model zal worden omgegaan met objecten die het gevolg zijn van aggregatie. Hierbij kan bijvoorbeeld worden gedacht aan de momenteel in de BRT voorkomende objecttype “gebouw” dat ontstaat door aggregatie van het in de BAG en de BGT voorkomende objecttype “pand”. Hierbij is in het kader van de SOR het uitgangspunt dat gegevens worden ingewonnen met een mate van detail die behoort bij een schaalniveau 1 : 1000. Geaggregeerde objecten moeten dus op basis van deze gegevens kunnen worden gevormd.

Vragen die daarbij eveneens zullen moeten worden beantwoord is in hoeverre geaggregeerde objecten ook terug te herleiden moeten zijn tot de verschillende oorspronkelijke objecten en wat er wordt voorgeschreven voor verplicht gebruik bij geaggregeerde objecten (het algoritme of een vastlegging van de uitkomst van dit algoritme).

#### Volledige levensloop

Ontwerpprincipe:

Objecten worden in de SOR opgenomen op het moment dat deze volgens de voor het betreffende objecttype gedefinieerde criteria ontstaan en blijven daarna altijd in de registratie aanwezig, waarbij voor elk objecttype is vastgelegd welke levensfasen in de vastlegging van een object worden onderscheiden.

Met dit uitgangspunt wordt beoogd dat de volledige levensloop van een object geregistreerd wordt. Deze levensloop begint op het gedefinieerde ontstaansmoment, dat per objecttype kan verschillen. Zo is voor bepaalde objecttypen een planstatus relevant, terwijl dit voor andere objecttypen minder relevant lijkt. De objecten blijven daarna altijd in de registratie aanwezig. Door middel van een vastlegging van de levensfase van een object kan worden bepaald of een object ook nog als zodanig bestaat. Objecten worden daarbij niet afgevoerd, maar historisch gemaakt. Belangrijk is dus dat gedurende de gehele levensloop sprake is van hetzelfde unieke object (met dezelfde identificatiecode).

In de samenhangende objectenregistratie betekent dit ook dat er eensluidende uitgangspunten moeten worden vastgesteld over het te hanteren historiemodel. Het gaat daarbij onder meer om de wijze waarop wordt omgegaan met de modellering van de formele en materiele historie.



###	Inhoudelijke uitgangspunten

#### Unieke identificatie

Ontwerpprincipe: 	

Elk object in de SOR wordt voorzien van een unieke identificatiecode die gedurende de gehele levensloop van een object ongewijzigd blijft .

Elk object in de registratie wordt voorzien van een unieke identificatiecode. Deze identificatiecode maakt het mogelijk om andere gegevens te koppelen aan het betreffende object. Hiervoor is het van belang dat de identificatiecode van een object gedurende de gehele levensloop van een object hetzelfde blijft. Een object blijft op deze wijze voor de gebruiker van de gegevens over het object herkenbaar. Mocht het desalniettemin noodzakelijk zijn wijzigingen aan te brengen in identificatiecodes van objecten, dan zal minimaal moeten worden geborgd dat de oude identificatiecodes gedurende een geruime tijd behouden blijven, om gebruikers de overgang naar de nieuwe identificatiecodes zorgvuldig te laten uitvoeren.

#### Typering

Ontwerpprincipe:

Van elk object in de SOR is helder wat de typering is van het betreffende object.

Elk object in de registratie zal altijd moeten worden gekarakteriseerd als een bepaald type object. In het informatiemodel zal daarom moeten worden geborgd dat deze typering is vast te stellen. Dat kan in de verdere uitwerking op twee manieren worden vormgegeven. De eerste manier is via de objecttypenaam. Uit de definitie van het betreffende objecttype volgt dan expliciet wat voor soort object het betreft. Een voorbeeld hiervan zou een objecttype “abri” zijn. Wat voor soort object het betreft kan ook worden vastgelegd door het registreren van een typering als eigenschap van het objecttype. In hetzelfde voorbeeld zou “abri” dan een van de typeringen kunnen zijn die kan worden toegekend aan een objecttype “straatmeubilair”. Op welke wijze typeringen worden opgenomen is afhankelijk van de keuzen die worden gemaakt rondom bepaalde groepen van objecten.

#### Geometrie

Ontwerpprincipe:

Van elk objecttype in de SOR wordt minimaal als eigenschap vastgelegd wat het geometrisch voorkomen is van een object in de registratie conform hetgeen daarover voor het betreffende objecttype is bepaald, waarbij de vastlegging hiervan zodanig wordt vormgegeven dat de driedimensionale (3D) beschrijving van een object kan worden opgenomen.

Opname van geometrie van alle objecten in de registratie is van essentieel belang voor het goed kunnen functioneren van een geo-basisregistratie. Met geometrie wordt daarbij expliciet bedoeld een geo-gerefereerde vastlegging van de begrenzing van een object.  Met geo-gerefereerde vastlegging wordt bedoeld dat de geometrie is beschreven in de vorm van coördinaten die onderdeel uitmaken van een referentie coördinatenstelsel (zoals het RD stelsel of ETRS89). De registratie wordt daarbij direct voorbereid op 3D vastlegging van objecten.

Hierbij kan de wijze van vastlegging verschillen voor de diverse objecttypen. Sommige objecttypen zullen worden vastgelegd in de vorm van 3D volumes. Andere objecttypen als vlakken met een bepaalde hoogteligging. Voor bepaalde objecten met een minimale omvang kan ook geometrische vastlegging in de vorm van een enkel coördinatendrietal (x, y en z) worden vastgelegd (puntobject). 

Speciale aandacht vraagt het geometrisch voorkomen van netwerken. Aan deze geometrie zullen in de regel nadere eisen worden gesteld (zoals een eis dat het netwerk zich moet bevinden binnen de contouren van de bijbehorende fysieke objecten). Ook worden bij dit soort objecten soms ook andere benaderingen gekozen voor het bepalen van de positie op een netwerk (zoals lineair referencing). Daarnaast zal er in de verdere uitwerking ook nog aandacht moeten worden besteed aan andere wijzen van vastlegging van de locatie van objecten. Denk hierbij onder meer aan hectometerpaaltjes, verdiepingsnummers en bouwlagen.


#### Metagegevens

Van elk object in de SOR wordt meta-informatie opgenomen conform hetgeen daarover voor het betreffende objecttype is bepaald.

Bij meta-informatie gaat het onder meer over informatie over de kwaliteit, ontstaansmoment en versie van het object. Voor het vastleggen van meta-informatie zullen nog nadere afspraken moeten worden ontwikkeld, waarbij het uitgangspunt is dat zoveel mogelijk wordt aangesloten op hiervoor bestaande standaarden. Deze zullen worden toegespitst op de verschillende soorten objecttypen. In de huidige basisregistraties wordt aan dit aspect op verschillende wijzen invulling gegeven. In de BAG wordt gewerkt met verwijzingen naar brondocumenten, in de BGT wordt hieraan op dit moment invulling gegeven met de opname van plaatsbepalingspunten en in de WOZ wordt hiervoor specifieke kwaliteitsinformatie aan de registratie toegevoegd.



#### Aanvullende eigenschappen

Ontwerpprincipe:

In de SOR kunnen van bepaalde objecttypen aanvullende eigenschappen worden vastgelegd, als deze van belang zijn voor meerdere gebruikers vanuit verschillende gebruikersdomeinen.

De samenhangende objectenregistratie heeft primair het karakter van een basisregistratie. Dat betekent dat in de registratie van objecttypen alleen eigenschappen worden vastgelegd die in verschillende overheidsdomeinen worden gebruikt. Hierbij kunnen er tussen verschillende objecttypen grote verschillen bestaan tussen het aantal eigenschappen dat dit betreft. Bij het objecttype ‘pand’ worden bijvoorbeeld aanzienlijk meer eigenschappen vastgelegd dan bij een objecttype ‘tunneldeel’.



### Grondgebied NL

In de samenhangende objectenregistratie worden die objecten opgenomen die zich bevinden binnen het grondgebied van Nederland. In de volgende ontwerpprincipes is dit nader aangeduid:

Ontwerpprincipe : *De samenhangende objectenregistratie registreert in navolging van de BAG en de BGT de objecten die gelegen zijn op het Europese grondgebied van het Koninkrijk der Nederlanden inclusief de daarbij behorende territoriale wateren*

Ontwerpprincipe :  *De samenhangende objectenregistratie wordt uitgebreid met het continentaal plat, zodat objecten in dat gebied ook kunnen worden geregistreerd, zoals windmolens*

De begrenzingen van het continentaal  plat worden meegenomen bij de registratieve objecttypen.


Ontwerpprincipe : *De samenhangende objectenregistratie kan op termijn mogelijk worden uitgebreid met overzeese gebiedsdelen van het koninkrijk.* 
Het informatiemodel moet daar op zijn voorbereid.


Ontwerpprincipe : *Objecten in de exclaves van het Koninkrijk België op het Nederlandse grondgebied (Baarle Hertog) worden in de samenhangende objectenregistratie opgenomen. De bijhouding daarvan is niet verplicht maar vrijwillig.*


### Ondergrondse delen

ontwerpprincipe: *In de huidige scope van de SOR worden uitsluitend objecttypen opgenomen die primair bovengronds zijn gelegen en ondergrondse objecttypen die geschikt zijn voor het vervoer van personen als onderdeel van infrastructurele voorzieningen en voor het verbinden van twee bovengrondse waterobjecten en die voor een mens toegankelijk zijn.*

Waar komen we ondergrondse delen tegen?
- Gebouw
- Netwerk; Spoor (trein, metro, tram), weg, water
- Tunneldeel
- Kunstwerk (met ondergrondse ruimten)
- Kunstwerk; duiker
- Bak; Afval apart plaats

Wat beschouwen we niet als ondergrondse delen voor de SOR:
- Put(deksel) niet ondergronds
- Ondergrondse objecten die al in een andere registratie zijn opgenomen, zoals kabels en leidingen, niet gesprongen explosieven, archeologische vindplaatsen, ed.
- Oude funderingen, wrakken, et cetera, die achter zijn gebleven in de grond, zijn geen onderdeel van SOR, hebben namelijk geen link met bovengronds objecttype uit de SOR en zijn ook niet bedoeld als onderdeel van infarstructurele voorzieningen.
- Wegfundering is wel ondergronds maar is niet toegankelijk. Hiervan worden sectoraal gegevens vastgelegd. 


Aandachtspunten:
- In de SOR komen ondergrondse delen vooral voor bij gebouwen en bij kunstwerken.
- Parkeergarages en metrostations zijn ondergrondse gebouwen.
- Metrobuizen zijn een soort tunnels.
- Afval apart plaats (=ondergrondse afval container) is een object dat bovengronds toegankelijk is

### Regels voor opzet en definities

We toetsen de opzet en definities aan een aantal regels om te bepalen hoe goed de opzet/een definitie is. Hoe meer aan deze regels wordt voldaan, hoe groter de kans dat de definities bruikbaar zijn om mede daarmee een  een samenhangend informatiemodel creëren. 

Het lukt niet altijd een definitie aan alle regels te laten voldoen. Dat heeft veelal te maken met de leesbaarheid van de definitie. Een definitie kan te abstract worden of grammaticaal te ingewikkeld worden voor een lezer om te begrijpen wat er bedoeld wordt. Daarom zijn de regels voor definities slechts indicatief bedoeld. Het zijn hulpmiddelen om te komen tot een goede definitie, maar er kan bewust van worden afgeweken. Probeer dat wel zo min mogelijk te doen. 

#### Regels ten aanzien van opzet

We werken met concepten. Dit zijn objecttypen, eigenschappen en relaties. Bij inhoudelijke inrichting volgen we het mechanisme van de internationale standaarden. (bouw standaarden met standaarden. Bv DublinCore, SKOS, W3C) 

De objecttypen hebben onderlinge relaties. Die relaties worden expliciet benoemd. De meest relevante/voorkomende relatietypen m.b.t. de SOR zijn: 

- Taxonomie: De specialisatie of nadere typering van algemenere objecttypen. Bijvoorbeeld een eik is een type boom, wordt ook wel subtypering genoemd. 

- Compositie: Objecten bestaan uit onderdelen, welke op hun beurt ook objecten zijn. Bijvoorbeeld, een tak is een onderdeel van een boom. 

Er is strikt onderscheid tussen fysieke objecten en functionele, registratieve, geografische objecttypen. Fysieke objecten zijn in de werkelijkheid zichtbare en tastbare objecten. De andere typen zijn virtuele, thematische objecten. Bijvoorbeeld, een gemeentegrens bestaat alleen op de kaart of in een registratie. Het bord dat in de werkelijkheid de grens markeert is een fysiek object. 

#### Regels ten aanzien van definities

Een definitie: 

-	beschrijft één begrip

-	overlapt inhoudelijk niet andere definities (met uitzondering wanneer het ene objecttype een subtype is van het andere) 

-	voegt een onderscheidend kenmerk toe t.o.v. het algemenere supertype, wat bepalend is voor de nadere (sub-)typering. (Een beweegbare brug (subtype) is een brug (supertype) die open kan worden gezet (het onderscheidende kenmerk)) 

-	is gebaseerd op de betekenis van een objecttype en niet op zijn afbakening of geometrische weergave. (een oever wordt niet bepaald door zijn breedte of talud of topologische weergave in een kaart, maar door zijn functie bijv. m.b.t. waterbeheersing) 

-	is gebaseerd op de betekenis van een object en niet op opname eisen (er kan besloten worden om een object o.b.v. zijn omvang wel of niet in te winnen, maar dat is geen onderdeel van de definitie) 

-	is specifiek en bevat derhalve geen indicatieve termen als “vaak”, “veelal, “in principe”, “zoals” etc. 

-	bij fysieke objecten beschrijft het totstandkomingsproces, de samenstelling en bij gemaakte objecten het (gebruiks-)doel 

-	van fysieke objecttypen bevat geen delen die te maken heeft met functionele, registratieve, geografische aspecten 

-	van fysieke objecten bevat geen voorbeelden (van voorkomens, materialen, samenstelling etc.) 

-	van functionele, registratieve, geografische objecttypen bevat geen delen die te maken hebben met aspecten van fysieke objecten
