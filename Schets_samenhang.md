## Schets samenhang

### SOR-begrippen, objecttypen, en typeringen

In het informatiemodel voor de samenhangende objectenregistratie wordt zoveel mogelijk gebruik gemaakt van terminologie die aansluit op de wijze waarop hiermee wordt omgegaan in de hier relevante afsprakenstelsel voor informatiemodellering. Het gaat daarbij onder meer om het Metamodel Informatiemodellering (MIM) en de Nederlandse Technische Afspraak (NTA) 8035 over semantische Gegevensmodellering en -Integratie in de Gebouwde Omgeving. Dit betekent onder meer dat er wordt gesproken over objecttypen en de eigenschappen daarvan in plaats van over objecten en gegevens. De termen objecten en gegevens worden gebruikt om specifieke exemplaren van objecttypen en eigenschappen aan te duiden.

In deze fase van conceptuele modellering is het van belang dat de focus is gericht op het scherp benoemen van begrippen die we in het kader van de registratie willen hanteren. Van de begrippen die betrekking hebben op objecten zal een aantal daarvan in een volgende fase ook daadwerkelijk in het informatiemodel worden opgenomen als een objecttype. Van een groot aantal andere begrippen zal waarschijnlijk worden vastgesteld dat in de modellering beter gekozen kan worden voor een verzamel-objecttype waarvan de verschillende begrippen in de vorm van een typering van dit verzamel-objecttype terugkeren. In deze fase is het daarom ten aanzien van objecten wenselijk vooralsnog te spreken van SOR-begrippen en nog niet van SOR-objecttypen. In de volgende hoofdstukken wordt daarom gesproken van SOR-begrippen.

Het is voor de overzichtelijkheid echter ook niet wenselijk om in deze fase te volstaan met het uitsluitend opnemen van een lange lijst met relevante SOR-begrippen. Enige ordening daarin bevordert het overzicht en stelt anderen in staat om de samenhang tussen de verschillende begrippen beter te beoordelen. Om die reden is ervoor gekozen om in de volgende hoofdstukken de SOR-begrippen op één van de volgende twee wijzen te beschrijven:

-   In de vorm van een omschrijving die sterk aansluit op de omschrijving die in het vervolg voor objecttypen zal worden opgesteld. Dit betekent onder meer dat bij deze SOR-begrippen is aangegeven welke eigenschappen van belang zijn en welke waarden deze eigenschappen kunnen aannamen. Deze wijze van beschrijving is vooral gekozen voor SOR-begrippen waarvan in de bestaande basisregistraties reeds verschillende eigenschappen zijn opgenomen.
-   In de vorm van een typering van een meer generiek begrip dat is omschreven op een wijze als objecttypen zullen worden beschreven. In dat geval fungeert het “verzamel-objecttype” in deze fase met name als een kapstok om verschillende SOR-begrippen enigszins te ordenen. De SOR-begrippen zelf staan dan genoemd als de verschillende waarden die de eigenschap typering van het “verzamel-objecttype” kan aannemen.

Benadrukt wordt dat deze wijze van beschrijven niet betekent dat de nu opgenomen ordening van SOR-begrippen ook daadwerkelijk leidt tot de opgenomen verdeling in objecttypen en typeringen van verzamel-objecttypen. Deze keuze zal in de volgende fase van modellering worden gemaakt op basis van andere criteria (zoals de mate waarin de eigenschappen van verschillende SOR-begrippen ook daadwerkelijk overeen komen en de uiteindelijke keuzen ten aanzien van welke eigenschappen in de registratie zullen worden bijgehouden).

### Nieuwe versie van NEN 3610 als kader

Het informatiemodel voor de samenhangende objectenregistratie zal zodanig worden opgesteld dat deze volledig aansluit op de nieuwe versie van het basismodel geo-informatie (“NEN 3610”). Dit basismodel geo-informatie wordt namelijk tegelijkertijd met het opstellen van het informatiemodel voor de samenhangende objectenregistratie vernieuwd. Hiermee ontstaat de mogelijkheid om begrippen in beide modellen over en weer zoveel mogelijk op elkaar af te stemmen. De resultaten van deze afstemming zijn verwerkt in de volgende hoofdstukken. Bij de afronding van beide modellen zal blijvende afstemming worden bewaakt. Dat kan betekenen dat in beide modellen in een latere fase nog kleine wijzigingen zullen worden aangebracht.

In de volgende hoofdstukken is daarom telkens aangegeven hoe SOR-begrippen zich verhouden tot objectentypen uit het vernieuwde basismodel geo-informatie. In enkele gevallen betekent dit dat de SOR-begrippen hetzelfde zijn als objecttypen uit het vernieuwde basismodel geo-informatie. In andere gevallen zijn de SOR-begrippen een verbijzondering van objecttypen uit het vernieuwde basismodel geo-informatie. Hierbij is uitgegaan van de versie van het nieuwe basismodel geo-informatie zoals deze in juli 2020 beschikbaar was. Daarin wordt het volgende semantische model onderscheiden:
 

![semantisch model NEN3610](media/Semantisch_model_NEN3610_v5.png)

  

De daarin opgenomen begrippen waren ten tijde van het opstellen van dit conceptueel model als volgt (voorlopig) gedefinieerd:

| Begrip  | Definitie  |
|---|---|
|Geo-object| Abstractie van een fenomeen in de werkelijkheid, dat direct of indirect is geassocieerd met een locatie relatief ten opzichte van de aarde.|
|**Reëel object**|	Geo-object waarvan het fenomeen in de werkelijkheid tastbaar, zichtbaar en begrensd aanwezig is.|
|Bodem|	Bovenste deel van het natuurlijke aardoppervlak.|
|Water|	Oppervlak permanent bedekt met water of waarvan wordt geaccepteerd dat deze met water bedekt kan worden.|
|Begroeiing|	Planten die op natuurlijke wijze zijn ontstaan of door mensen zijn aangeplant.|
|Constructie|	Gebouwd object dat direct of indirect met de grond is verbonden en bedoeld is om ter plaatse te functioneren.|
|Gebouw|	Overdekte en geheel of gedeeltelijk met wanden omsloten constructief zelfstandige eenheid bedoeld voor het in een afgeschermde omgeving onderbrengen van mensen, dieren of voorwerpen of voor de productie van goederen.|
|Kunstwerk|	Civiel-technisch werk voor de infrastructuur van wegen, water, spoorbanen, waterkeringen en/of leidingen.|
|Verharding|	Een door egaliseren, verstevigen en/of verruwen voor het beoogde gebruik geschikt gemaakte oppervlak, bestaande uit in één of meer lagen over een ondergrond of onderliggende constructie aangelegd materiaal.|
|Leiding|	Een geheel van geleiders of ruimte welke voorzien zijn van één ommanteling en bestemd is voor transport van materie, data of energie.|
|**Virtueel object**|	Geo-object waarvan geen tastbaar, zichtbaar en begrensd fenomeen in de werkelijkheid aanwezig is, maar die slechts in abstracte en/of geregistreerde vorm bestaat.|
|Functioneel object|	Object met een specifieke functie.|
|Transport voorziening|	Natuurlijke of aangelegde transportlijnen of verbindingen met knooppunten waarlangs stromen zich verplaatsen.|
|Weg|	Transport voorziening voor wegverkeer.|
|Vaarweg|	Transport voorziening voor scheepvaart.|
|Spoorweg|	Transport voorziening voor voertuigen die zich over rails verplaatsen.|
|Waterelement	|Transport voorziening voor water.|
|Registratief object|	Op basis van wet- of regelgeving afgebakend object dat als eenheid geldt van politiek/bestuurlijke verantwoordelijkheid of voor bedrijfsvoering.|
|Geografisch gebied|	Gebied dat bekend staat onder een vanuit de historie of in in de volksmond bekende benaming of een fysisch-geografische samenhang kent.|
|Juridisch werkingsgebied| Gebied waar een juridisch instrument beleid of regelgeving toepast.|

### Aansluiting sectormodellen

Het is belangrijk dat de verschillende sectorale informatiemodellen zoveel mogelijk aangesloten kunnen worden op het informatiemodel van de samenhangende objectenregistratie. Bij het opstellen van het conceptueel informatiemodel is daarom zoveel mogelijk beoordeeld in hoeverre een dergelijke aansluiting te realiseren is. Soms betekent dat een aanpassing van begrippen zoals deze in de huidige basisregistraties voorkomen, soms zal dit betekenen dat op termijn aanpassingen in de sectormodellen doorgevoerd moeten worden.

Hierbij is als grondgedachte gehanteerd dat gestreefd moet worden naar een “uitklapmodel”. Hiermee wordt bedoeld dat in de samenhangende objectenregistratie begrippen op een zodanig abstractieniveau worden opgenomen dat zij weliswaar voldoende concreet zijn om in de uitvoeringspraktijk herkenbaar te zijn, maar dat zij niet zo concreet zijn dat er sprake is van een mate van detail die passender is voor de opname in een sectorale registratie. De in de samenhangende objectenregistratie opgenomen begrippen moeten daarbij kunnen fungeren als een verzamelklasse van begrippen die in een sectoraal model zijn opgenomen. Bij begrippen kan het daarbij zowel gaan om objecttypen als om typeringen van objecttypen.

<aside class='example'>
 In de samenhangende objectenregistratie wordt opgenomen dat het “type verharding” van een verhardingsobject de waarde “betonverharding” kan aannemen. In het informatiemodel voor het beheren van de openbare ruimte (IMBOR) is opgenomen dat deze typering van betonverharding nader kan worden verfijnd in onder meer “Ongewapend verdeuveld beton “ en “Gewapend beton”. Deze typeringen sluiten als een “uitklapmodel” op elkaar aan. Als in een lokale wegbeheer-registratie een verharding is opgenomen van het type “Gewapend beton”, zal deze verharding in de samenhangende objectenregistratie worden aangetroffen als een verharding van een type “betonverharding”.
</aside>


Deze benadering betekent ook dat ervoor is gekozen om in de eerste opzet van het conceptueel model een aantal gedetailleerde objecttypen of typeringen van objecttypen niet langer als zodanig op te nemen. Deze begrippen zijn dan samengevoegd tot een minder gedetailleerd begrip dat weliswaar nog steeds de essentie aangeeft van het betreffende object, maar dat een mindere mate van detaillering geeft dan in de huidige registratie. Het gaat hierbij overigens veelal om begrippen die in de huidige uitvoeringspraktijk niet of slechts zeer beperkt worden toegepast. Indien het gewenst is wel gedetailleerde informatie over deze objecten te verkrijgen, zal deze moeten worden afgenomen vanuit een sectorale registratie (indien aanwezig).



### Overzicht van de SOR-begrippen

De verschillende SOR-begrippen kunnen schematisch in een onderlinge samenhang worden vertoond. Dat leidt tot de volgende verdere uitwerking van het eerder opgestelde inhoudelijk denkraam:


![denkraamSOR](media/denkraam_sor_nieuw.png)


In de volgende hoofdstukken wordt achtereenvolgens ingegaan op de reële objecttypen, de functionele objecttypen, de registratieve objecttypen en de geografische objecttypen. 