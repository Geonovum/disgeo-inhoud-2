## Uitgangspunten 

### Inleiding

In de beleidsvisie (schetsontwerp) (https://www.geobasisregistraties.nl/basisregistraties/documenten/beleidsnota/2019/11/29/beleidsvisie-samenhangende-objectenregistratie) zijn een groot aantal uitgangspunten opgenomen voor de verdere uitwerking van een samenhangende objectenregistratie. Alle uitgangspunten uit de beleidsvisie blijven onverminderd van toepassing. Een deel van deze uitgangspunten is min of meer direct toepasbaar bij de verdere uitwerking van de inhoud van de samenhangende objectenregistratie. Een ander gedeelte is in het kader van de ontwikkeling van een conceptueel denkkader (hoofdlijnenrapport) (https://docs.geostandaarden.nl/disgeo/hiso/) verder uitgewerkt. 

In dit hoofdstuk is een samenhangende beschrijving opgenomen van zowel de eerdere uitgangspunten als van de verdere concretisering van enkele daarvan. Een aantal van deze uitgangspunten worden in het conceptueel model verder uitgewerkt. De uitgangspunten zijn niet alleen gehanteerd bij de verdere uitwerking van dit conceptueel model, maar worden ook in de volgende fase van het uitwerken van een informatiemodel toegepast. De uitgangspunten hebben in principe geen betrekking op andere registraties dan de objectenregistratie. Het gesprek daarover vindt plaats aan andere tafels. 

Alle uitgangspunten hebben betrekking op de uiteindelijke situatie. Het conceptueel model beschrijft nadrukkelijk niet de transitie vanuit de huidige (basis)registraties naar een samenhangende objectenregistratie. In het besluitvormingsproces zal deze transitie en stapsgewijze migratie van inhoud en voorzieningen (onder architectuur), inclusief de kosten en baten voor bronhouders en gebruikers, nadrukkelijk de aandacht krijgen en uitgewerkt worden in een roadmap. Dit valt echter buiten de scope van dit conceptueel inhoudelijk model.

### Algemene uitgangspunten

#### Standaardisatie

Ontwerpprincipe:

**In de SOR zijn uitsluitend gestandaardiseerde objecttypen en eigenschappen opgenomen.**

De inhoud van de objectenregistratie is volledig beschreven in de vorm van een standaard. In de registratie komen dus geen objecttypen voor die niet voldoen aan deze standaard. Ook worden in de objectenregistratie uitsluitend gestandaardiseerde eigenschappen van deze objecttypen opgenomen.

Onderdeel van deze standaardisatie is dat van de verschillende objecttypen en eigenschappen ook de beoogde kwaliteit is beschreven. Van de objecttypen is dus opgenomen welke eisen er worden gesteld aan de volledigheid en actualiteit van de in de registratie opgenomen objecten. Van de eigenschappen van de objecttypen is vastgelegd wat de beoogde actualiteit en nauwkeurigheid van de in de registratie opgenomen gegevens is. Deze kwaliteitseisen zijn geen onderwerp van dit voorliggende conceptuele model, maar zullen op een later moment in aparte documenten, zoals de Catalogus voor de samenhangende objectenregistratie, vastgelegd worden.

#### Definiëring

Ontwerpprincipe:

**Definities van zowel objecttypen als eigenschappen van objecttypen zijn scherp afgebakend, niet multi-interpretabel en sluiten waar mogelijk aan op bestaande definities.**

Het is van groot belang dat de basis van een informatiemodel voor een samenhangende objectenregistratie wordt gevormd door een aantal onderling goed afgestemde en heldere definities. In de bestaande basisregistraties is daarvan momenteel niet altijd sprake. Hierdoor wordt de onderlinge koppelbaarheid van gegevens beperkt en laat de uniformiteit van de opgenomen gegevens (door interpretatieverschillen of in de definities opgenomen vrijheidsgraden) nogal eens te wensen over. In de samenhangende objectenregistratie worden bestaande definities daarom zodanig uitgebreid en geharmoniseerd dat: 
- een scherp afgebakende en duidelijke definitie van objecttypen en eigenschappen ontstaat;
- definities elkaar semantisch niet overlappen;
- er niet langer gebruik wordt gemaakt van verzamelclassificaties (een objecttype dat in naamgeving en definitie verschillende elkaar uitsluitende classificaties bevat en daarom niet eenduidig is);
- een optimale aansluiting op overkoepelende en sectorale modellen wordt gerealiseerd, zoals het Metamodel voor Informatiemodellering (MIM), NEN 3610 (Basismodel voor geo-informatie), NEN 2660 (Ordeningsregels voor gegevens in de bouw – Termen, definities en algemene regels) en waar mogelijk de NTA 8035 (Semantische gegevensmodellering in de gebouwde omgeving).


#### Flexibiliteit

Ontwerpprincipe:

**Objecttypen en eigenschappen van objecttypen worden zodanig in de SOR opgenomen dat uitbreiding en inkrimping van het aantal objecttypen en eigenschappen en het aanpassen van de kwalificatie van objecttypen en eigenschappen als verplicht of vrijwillig binnen het informatiemodel eenvoudig mogelijk is.**

Het moet mogelijk zijn om de inhoud van de samenhangende objectenregistratie relatief eenvoudig aan te kunnen passen. Dit begint met een informatiemodel dat dergelijke aanpassingen kan faciliteren. Dat betekent dat bijvoorbeeld het onderscheid tussen verplichte en vrijwillige objecten in de registratie niet diepgaand in het uitgewerkte informatiemodel moet worden verankerd. Of aanpassing ook daadwerkelijk zal plaatsvinden is uiteraard afhankelijk van de afspraken die er worden gemaakt over de wijze waarop besluitvorming over wijzigingen plaatsvindt en hoe er wordt omgegaan met de gevolgen daarvan voor bronhouders en gebruikers. Bij het doorvoeren van dit soort wijzigingen moeten er altijd heldere transitieafspraken worden gemaakt.


### Uitgangspunten reikwijdte 

#### Sector overstijgend

Ontwerpprincipe:

**In de SOR worden uitsluitend objecttypen en eigenschappen van objecttypen opgenomen die van belang zijn voor gebruik in verschillende overheidsdomeinen.**

Met dit uitgangspunt wordt invulling gegeven aan de ook nu al bestaande eisen die worden gesteld aan basisregistraties. De objectenregistratie fungeert daarbij als een onderdeel van het fundament voor een gegevenslandschap waarin aanvullend op dit fundament in sectorale en lokale registraties aanvullende objecttypen en eigenschappen worden geregistreerd. De samenhangende objectenregistratie fungeert daarmee dus als een verbindende schakel tussen de verschillende specifieke eigenschappen die van deze objecttypen zijn geregistreerd in de verschillende sectorale registraties. Daarnaast bevordert de samenhangende objectenregistratie indirect ook de samenhang met in die sectorale registraties opgenomen specifieke objecttypen en eigenschappen daarvan. Deze brugfunctie van de samenhangende objectenregistratie is daarmee essentieel voor het integraal kunnen gebruiken van gegevens.

Om te bepalen welke objecttypen en eigenschappen van objecttypen worden opgenomen in de SOR, en welke in sectorregistraties thuishoren zijn er criteria opgesteld. Twee hoofdcriteria voor opname van gegevens in de SOR zijn: er wordt niet meer detail opgenomen in de basisregistratie dan nodig is én de objecttypen en eigenschappen zijn voor gebruikers in meerdere sectoren relevant. Daarnaast zijn objecttypen in de SOR een verbijzondering van de concepten in NEN 3610, herkenbaar voor gebruikers en eenvoudig vast te stellen door de bronhouders. De objecttypen hebben allemaal één of geen niveau van hoofdclassificatie, waarbij het aantal typeringen ook kan afhangen van het soort objecttype (bij registratieve gebieden is er bijvoorbeeld in principe geen typering). De objecttypen kunnen nog één of meerdere detailclassificaties hebben, maar deze vloeien dan voort uit specifieke afspraken en moeten altijd meerdere gebruikers (binnen de overheid) kennen. Detailclassificaties kunnen in het vrijwillige deel van de SOR opgenomen worden als gevolg van een transitie (eerst niet verplicht, later wel, ter beperking van de transitielast) of een wens om gegevens kwijt te kunnen (bijvoorbeeld ruimte in het gebouwendeel). Als het objecttype of eigenschap nodig is voor één specifieke taak komt het niet in de basisregistratie, tenzij het voor efficiency redenen niet handig is om een aparte sectorregistratie voor aan te leggen (noemer: sectoraal gegeven in de basisregistratie) en er specifieke afspraken over governance en financiering zijn gemaakt.

Dit uitgangspunt betekent praktisch onder meer dat specifieke zoneringen en werkingsgebieden (zoals deze bijvoorbeeld voortvloeien vanuit de Omgevingswet) niet worden opgenomen in de SOR, maar “achterblijven” in sectorale registraties.

#### Primair bovengronds

Ontwerpprincipe:

**In de SOR worden uitsluitend objecttypen opgenomen die primair bovengronds zijn gelegen en ondergrondse objecttypen die geschikt zijn voor het vervoer van personen als onderdeel van infrastructurele voorzieningen of voor het verbinden van twee bovengrondse waterobjecten en die voor mensen toegankelijk zijn.**

De scope van de samenhangende objectenregistratie is in eerste instantie beperkt tot de bovengrond en de ondergrondse delen van objecttypen die ook in het terrein zichtbaar zijn. Bij dit laatste kan worden gedacht aan de ondergrondse delen van gebouwen en kunstwerken, parkeergarages en metrostations (zoals deze ook opgenomen worden in de BAG). Maar er kan ook worden gedacht aan bakken (zoals de bak waarin het ondergrondse gedeelte van een afvalcontainer zich bevindt). Daarnaast worden enkele objecttypen uit de BGT die daarin op een ander niveau zijn gepositioneerd ook in de scope van de samenhangende objectenregistratie betrokken. Het gaat daarbij met name om tunneldelen (voor spoor- en wegverbindingen) en duikers. Het tweede gedeelte van de formulering richt zich daarop.

Deze afbakening van de scope is een afgeleide van de wens om tot een helder en beheersbaar transitietraject te komen. Het ook opnemen van ondergrondse objecten in de SOR, zoals leidingnetwerken of de verschillende objecttypen die thans worden opgenomen in de Basisregistratie Ondergrond (BRO), zou op dit moment leiden tot een aanzienlijk hogere complexiteit. Ook specifieke ondergrondse objecten als niet gesprongen explosieven, archeologische vindplaatsen en in de grond achtergebleven oude funderingen en wrakken maken geen onderdeel uit van de SOR. Dit neemt niet weg dat opname van ondergrondse objecten in de toekomst niet wordt uitgesloten. Het model van de registratie is zodanig opgezet dat op termijn ook ondergrondse objecten in de registratie kunnen worden opgenomen. Deze opname zou in de loop van de tijd ook gefaseerd kunnen plaatsvinden.

#### Grondgebied Nederland

Ontwerpprincipe:

**In de SOR worden uitsluitend objecten opgenomen die gelegen zijn binnen het grondgebied van Nederland.**

De genoemde scope is met name van belang voor het bepalen van hetgeen voor bepaalde soorten objecten als grondgebiedsdekkend moet worden beschouwd. Hierbij kan er een onderscheid bestaan voor verschillende soorten objecten. 

Op dit moment wordt daarbij primair de lijn gevolgd, zoals deze ook wordt gevolgd in het kader van de BAG en de BGT. Deze beperken zich tot het Europese grondgebied van het Koninkrijk der Nederlanden inclusief de daarbij behorende territoriale wateren. Een uitzondering hierop betreft de exclaves van het Koninkrijk België op het Nederlandse grondgebied (Baarle Hertog). Ook objecten in deze exclaves worden in de samenhangende objectenregistratie opgenomen. De scope van de samenhangende objectenregistratie wordt voor sommige soorten objecten uitgebreid met het continentaal plat. Hierdoor ontstaat de mogelijkheid om zich daar bevindende objecten (zoals windturbines) op te nemen in de registratie.

Op een later moment zal het ministerie van BZK nog een afzonderlijk besluit nemen over de vraag in hoeverre de samenhangende objectenregistratie zich ook zal uitstrekken tot het grondgebied van de bijzondere Nederlandse gemeenten (BES-eilanden) en de andere overzeese koninkrijksdelen. Het informatiemodel zal zodanig moeten worden opgezet dat deze uitbreiding mogelijk is.


### Uitgangspunten structuur

#### Onderscheid verplicht en vrijwillig

Ontwerpprincipe:

**Objecttypen en eigenschappen van objecttypen moeten in de SOR worden opgenomen als deze in het kader van de SOR als wettelijk verplicht zijn aangemerkt en mogen in de registratie worden opgenomen als deze als vrijwillig zijn aangemerkt in het kader van de SOR.**

![onderscheid verplicht en vrijwillig](media/verplicht_vrijwillig.png)


De grondgedachte van de samenhangende objectenregistratie is dat deze bestaat uit:

- verplichte en gestandaardiseerde objecttypen en eigenschappen (het formele basisregistratie gedeelte)
- vrijwillige maar wel gestandaardiseerde objecttypen en eigenschappen

Vrijwillige eigenschappen kunnen ook aan 3D zijn gerelateerd.

Hierbij is het belangrijk dat opname van vrijwillige objecten en eigenschappen door een bronhouder ook betekent dat deze gegevens blijvend worden bijgehouden en dat dit bovendien gebeurt voor het volledige bijhoudingsgebied van de bronhouder (behalve als er sprake is van tijdelijke voor een  transitie relevante gegevens). Voor alle opgenomen objecten en eigenschappen (zowel in het verplichte als het vrijwillige gedeelte) gelden dus blijvend de bijhoudingsregels die behoren bij het betreffende objecttype en eigenschappen. Bij de verdere uitwerking van de organisatie van de samenhangende objectenregistratie zullen afspraken moeten worden gemaakt over de omgang met in de registratie opgenomen objecten en eigenschappen die blijvend niet aan de bijhoudingsregels voldoen.

Voor het basisregistratie gedeelte gelden de 12 eisen die aan basisregistraties worden gesteld (https://www.digitaleoverheid.nl/overzicht-van-alle-onderwerpen/gegevens/naar-een-gegevenslandschap/themas/twaalf-eisen-stelsel-van-basisregistraties/) en waarvan voor de verdere uitwerking van de inhoud van de samenhangende objectenregistratie met name de eisen 6 (er is duidelijkheid over inhoud en bereik van de registratie) en 11 (de positie van de basisregistratie binnen het stelsel van basisregistraties is duidelijk en de relaties met de basisregistraties zijn beschreven) van belang zijn.

Dit betekent dus dat gebruikers van het verplichte gedeelte van de samenhangende objectenregistratie zekerheid hebben over de volledigheid van de daarin opgenomen objecten en gegevens. Omdat bronhouders de keuze hebben om objecten of gegevens al dan niet op te nemen in het vrijwillige gedeelte van de objectenregistratie, hebben gebruikers van de samenhangende objectenregistratie die zekerheid niet bij de vrijwillig op te nemen objecten en gegevens. In de communicatie rondom de informatieproducten van de samenhangende objectenregistratie zal dit principe en de mate waarin verschillende bronhouders al dan geen gebruik maken van het vrijwillige gedeelte duidelijk gecommuniceerd moeten worden.

#### Onderscheid reële en functionele objecttypen

Ontwerpprincipe:

**In de SOR wordt een expliciet onderscheid gemaakt tussen reële en functionele objecttypen.**

Bij de uitwerking van de SOR wordt een scheiding aangebracht tussen reële (voorheen vaak aangeduid als fysieke) objecttypen en functionele objecttypen. De aanleiding is dat definities van functionele objecttypen sterk samenhangen met specifieke gebruikstoepassingen of afsprakenkaders. Reële objecttypen worden altijd gedefinieerd door hetgeen in het terrein zichtbaar is. Door in de SOR een strikte scheiding aan te brengen tussen reële objecttypen en functionele objecttypen, kunnen duidelijkere regels worden opgesteld over onder meer samenhang en overlap van verschillende objecttypen. Daar waar dat de in de huidige registraties vaak niet mogelijk is, wordt het in de SOR bijvoorbeeld mogelijk dat er meerdere functionele indelingen op één reële locatie voorkomen. Hiermee vergroten we de flexibiliteit en de gebruiksmogelijkheden van de SOR enorm. Functionele en reële objecttypen worden hierbij altijd als aparte objecttypen gedefinieerd, als de begrenzing ervan kan verschillen.
Bij het onderdeel  [Verblijfsobject](#verblijfsobject) wordt bij de eigenschappen van Feitelijk gebruik een beperkte uitzondering gemaakt op de strikte scheiding fysiek / functioneel op basis van het brede maatschappelijke gebruik dat er bestaat bij een aantal opgenomen typeringen. In de classificatie zijn bij enkele typeringen ook fysieke verschijningsvormen onderdeel van de classificatie. Deze keuze kan tijdens de informatiemodellering of het opstellen van de afbakeningsregels bij een beter alternatief mogelijk worden herzien. Dit uitgangspunt wordt verder uitgewerkt in hoofdstuk [Samenhang](#samenhang).

#### Kleinste semantische eenheden

Ontwerpprincipe: 

**Het objectenmodel van de SOR wordt opgebouwd vanuit de kleinste semantische eenheden die het minimum detailniveau aangeven waarvan is vastgesteld dat deze van waarde zijn voor meerdere gebruikers van de registratie.**

Bij de uitwerking van de inhoud van de samenhangende objectenregistratie wordt voor de verschillende objecttypen bepaald wat de kleinste semantische eenheid is die nog van belang is voor meerdere gebruikers van de registratie. Dit minimum detailniveau bepaalt daarmee wat voor het betreffende gedeelte van de samenhangende objectenregistratie de kleinste bouwsteen vormt. Op het moment dat bepaalde gebruikers binnen deze kleinste semantische eenheid voor eigen gebruik nog een nadere detaillering wil aanbrengen, dan zal de gebruiker dat als onderdeel van de eigen sectorale registratie zelf nader moeten vormgeven. Hierbij kan bijvoorbeeld worden gedacht aan het nader detailleren van een groenobject in verschillende beplantingsvakken als onderdeel van het werkproces voor het beheren van de openbare ruimte. Deze nadere detaillering kan (administratief) gekoppeld worden aan de objecttypen van de SOR door het gebruik van identificerende codes.

#### Volledige levensloop

Ontwerpprincipe:

**Objecten worden in de SOR opgenomen op het moment dat deze volgens de voor het betreffende objecttype gedefinieerde criteria ontstaan en blijven daarna altijd in de registratie aanwezig, waarbij voor elk objecttype is vastgelegd welke levensfasen in de vastlegging van een object worden onderscheiden.**

Met dit uitgangspunt wordt beoogd dat de volledige levensloop van een object geregistreerd wordt. Deze levensloop begint op het gedefinieerde ontstaansmoment, dat per objecttype kan verschillen. Zo is voor bepaalde objecttypen een planstatus relevant, terwijl dit voor andere objecttypen minder relevant lijkt. De objecten blijven daarna altijd in de registratie aanwezig. Door middel van een vastlegging van de levensfase van een object kan worden bepaald of een object ook nog als zodanig bestaat. Objecten worden daarbij niet afgevoerd, maar historisch gemaakt. Belangrijk is dus dat gedurende de gehele levensloop sprake is van hetzelfde unieke object (met dezelfde identificatiecode). Indien het noodzakelijk is een dubbele levensfase van een object vast te leggen, kan hiervoor een afzonderlijk object worden gecreëerd waarvan de levensfase en identificatiecode aan een reeds bestaand object kunnen worden gekoppeld (zie paragraaf [Levensfasen](#levensfasen)).


###	Inhoudelijke uitgangspunten

#### Unieke identificatie

Ontwerpprincipe: 	

**Elk object in de SOR wordt voorzien van een unieke identificatiecode die gedurende de gehele levensloop van een object ongewijzigd blijft .**

Elk object in de registratie wordt voorzien van een unieke identificatiecode. Deze identificatiecode maakt het mogelijk om andere gegevens te koppelen aan het betreffende object. Hiervoor is het van belang dat de identificatiecode van een object gedurende de gehele levensloop van een object hetzelfde blijft. Een object blijft op deze wijze voor de gebruiker van de gegevens over het object herkenbaar. Mocht het desalniettemin noodzakelijk zijn wijzigingen aan te brengen in identificatiecodes van objecten, dan zal minimaal moeten worden geborgd dat de oude identificatiecodes gedurende een geruime tijd behouden blijven, om gebruikers de overgang naar de nieuwe identificatiecodes zorgvuldig te laten uitvoeren. In paragraaf [Identificatie van objecten](#identificatie-van-objecten) wordt dit uitgangspunt verder uitgewerkt.

#### Typering

Ontwerpprincipe:

**Van elk object in de SOR is helder wat de typering is van het betreffende object.**

Elk object in de registratie zal altijd moeten worden gekarakteriseerd als een bepaald type object. In het informatiemodel zal daarom moeten worden geborgd dat deze typering is vast te stellen. Dat kan in de verdere uitwerking op twee manieren worden vormgegeven. De eerste manier is via de objecttypenaam. Uit de definitie van het betreffende objecttype volgt dan expliciet wat voor soort object het betreft. Een voorbeeld hiervan zou een objecttype “abri” zijn. Wat voor soort object het betreft kan ook worden vastgelegd door het registreren van een typering als eigenschap van het objecttype. In hetzelfde voorbeeld zou “abri” dan een van de typeringen kunnen zijn die kan worden toegekend aan een objecttype “straatmeubilair”. Op welke wijze typeringen worden opgenomen is afhankelijk van de keuzen die worden gemaakt rondom bepaalde groepen van objecten. In paragraaf [Begrippen in de SOR](#begrippen-in-de-sor) wordt dit uitgangspunt verder uitgewerkt.

#### Geometrie

Ontwerpprincipe:

**Van elk objecttype in de SOR wordt minimaal als eigenschap vastgelegd wat het geometrisch voorkomen is van een object in de registratie conform hetgeen daarover voor het betreffende objecttype is bepaald, waarbij de vastlegging hiervan zodanig wordt vormgegeven dat de driedimensionale (3D) beschrijving van een object kan worden opgenomen.**

Opname van geometrie van alle objecten in de registratie is van essentieel belang voor het goed kunnen functioneren van een geo-basisregistratie. Met geometrie wordt daarbij expliciet bedoeld een geo-gerefereerde vastlegging van de begrenzing van een object.  Met geo-gerefereerde vastlegging wordt bedoeld dat de geometrie is beschreven in de vorm van coördinaten die onderdeel uitmaken van een referentie coördinatenstelsel (zoals het RD stelsel of ETRS89). De registratie wordt daarbij direct voorbereid op 3D vastlegging van objecten.

Hierbij kan de wijze van vastlegging verschillen voor de diverse objecttypen. Sommige objecttypen zullen worden vastgelegd in de vorm van 3D volumes. Andere objecttypen als vlakken met een bepaalde hoogteligging. Voor bepaalde objecten met een minimale omvang kan ook geometrische vastlegging in de vorm van een enkel coördinatendrietal (x, y en z) worden vastgelegd (puntobject). Tenslotte wordt er rekening mee gehouden dat bij bepaalde objecttypen meerdere 3D geometrische representaties (zoals verschillende levels of detail) kunnen worden opgenomen.

Speciale aandacht vraagt het geometrisch voorkomen van netwerken. Aan deze geometrie zullen in de regel nadere eisen worden gesteld (zoals een eis dat het netwerk zich moet bevinden binnen de contouren van de bijbehorende reële objecten). Ook worden bij dit soort objecten soms ook andere benaderingen gekozen voor het bepalen van de positie op een netwerk (zoals lineair referencing). In paragraaf [Aspecten van geometrie](#aspecten-van-geometrie) wordt dit uitgangspunt verder uitgewerkt.

De SOR is primair een geometrische gegevensverzameling en kaartbeelden kunnen daar als product van worden afgeleid. Hierbij is voor geometrie aansluiting op Simple Features (ISO19125) voorgeschreven. 
De SOR hanteert altijd expliciete geometrie en geen impliciete geometrie (zoals geparametriseerde geometriebeschrijvingen die in CAD/BIM voorkomen). Hiermee kunnen namelijk betere analyses en kwaliteitscontroles (zoals topologische controles) worden uitgevoerd en  2D geometrie worden ‘opgetrokken’ naar 3D geometrie.

#### Meta-informatie

ontwerpprincipe:

**Van elk object in de SOR wordt meta-informatie opgenomen conform hetgeen daarover voor het betreffende objecttype is bepaald.**

Bij meta-informatie gaat het onder meer over informatie over de kwaliteit, ontstaansmoment en versie van het object. In de huidige basisregistraties wordt aan dit aspect op verschillende wijzen invulling gegeven. In de BAG wordt gewerkt met verwijzingen naar brondocumenten, in de BGT wordt hieraan op dit moment invulling gegeven met de opname van plaatsbepalingspunten en in de WOZ wordt hiervoor specifieke kwaliteitsinformatie aan de registratie toegevoegd.

Voor het vastleggen van meta-informatie wordt zoveel mogelijk aangesloten op hiervoor bestaande standaarden. Dit uitgangspunt is verder uitgewerkt in paragraaf [Meta-informatie en bronverwijzing](#meta-informatie-en-bronverwijzing). Metagegevens kunnen ook informatie over de totstandkoming van 3D geometrie bevatten. Is deze afgeleid van andere gegevens of is deze in 3D ingewonnen?. Ook zal uit een LOD(-beschrijving) van geometrie duidelijk moeten worden in hoeverre bijvoorbeeld een dak plat is omdat deze in werkelijkheid plat is en dus zo in de gegevensverzameling is opgenomen of omdat er sprake is van een LOD1 representatie.


#### Aanvullende eigenschappen

Ontwerpprincipe:

**In de SOR kunnen van bepaalde objecttypen aanvullende eigenschappen worden vastgelegd, als deze van belang zijn voor meerdere gebruikers vanuit verschillende gebruikersdomeinen.**

De samenhangende objectenregistratie heeft primair het karakter van een basisregistratie. Dat betekent dat in de registratie van objecttypen alleen eigenschappen worden vastgelegd die in verschillende overheidsdomeinen worden gebruikt. Hierbij kunnen er tussen verschillende objecttypen grote verschillen bestaan tussen het aantal eigenschappen dat dit betreft. Bij het objecttype ‘pand’ worden bijvoorbeeld aanzienlijk meer eigenschappen vastgelegd dan bij een objecttype ‘tunneldeel’.





