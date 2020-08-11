## Fysieke objecttypen

In dit hoofdstuk is een eerste aanzet opgenomen tot nadere typering van de verschillende fysieke objecttypen in de samenhangende objectenregistratie. Deze aanzet is primair gebaseerd op de ook nu reeds in de bestaande basisregistraties gehanteerde typeringen. Vanwege een strikte scheiding tussen fysieke objecttypen en functionele objecttypen zijn op deze typeringen soms beperkte aanpassingen doorgevoerd. Ook zijn enkele eerste wijzigingen voorgesteld die het gevolg zijn van het in hoofdstuk 2 genoemde uitgangspunt over heldere definiëring. Tenslotte is daar waar mogelijk reeds bekeken in hoeverre aanpalende sectorale typeringen aanleiding kunnen geven tot een aangescherpte typering. 

Deze typering is in deze fase van het traject vooral bedoeld om een eerste indruk te geven van de richting waarin de inhoud van de samenhangende objectenregistratie zich beweegt. Samen met experts vanuit de verschillende domeinen en gebruikers zal in het vervolg nog nader onderzoek noodzakelijk zijn om tot definitieve typeringen met bijbehorende definities te komen. Ook zal daarbij nog moeten worden bepaald in hoeverre het nu opgenomen onderscheid tussen de verplichte classificatie en de vrijwillige classificatie aanpassing behoeft. Hierbij is het uiteindelijk de bedoeling om te komen tot een “uitklapmodel” van typeringen, waarbij gedetailleerde typeringen (in de samenhangende objectenregistratie, maar bij voorkeur ook in sectorale registraties) altijd een nadere uitwerking vormen van één bepaalde hoofdtypering (in de samenhangende objectenregistratie).

### GRIJS 
#### Verharding

| klasse  | naam  |
|---|---|
|SOR-objecttype   | verharding  |
| onderdeel van NEN3610-objecttype |verharding |


ontwerpprincipe: 


**Definitie**

| Naam  | verharding |
|---|---|
| Definitie |Een door egaliseren, verstevigen en/of verruwen voor het beoogde gebruik geschikt gemaakt oppervlak, bestaande uit in één of meer lagen over een ondergrond of onderliggende constructie aangelegd materiaal. |
|Herkomst definitie  | concept NEN3610-2020  |
|Verplicht  | Ja  |
|Toelichting| *volgt later*  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-objecttype verharding |Ja |
|Geometrie-type|vlak|Ja|
|Afbakening   |  Een verhardingsvlak bestaat uit één type verharding. Het gaat hierbij over het type verharding waarmee het vlak overwegend is bedekt. Voor minimale stukjes, 5m2, met andere verharding hoeft geen apart vlak te worden gevormd.|Ja   |
|Status   |   |Ja   |
|type verharding|aanduiding soort verharding|Ja|
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |


**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
| | | |


**Domeinwaarden**


|Waarde Status| Beschrijving   |
|---|---|
|Aangewezen||
| Ingetrokken | 

|Waarde Type| Beschrijving   |herkomst|
|---|---|---|
|asfaltverharding|Gesloten verharding bestaande uit asfaltbeton of andere met bitumen gebonden materialen.|IMBOR2020|
| betonverharding |Gesloten verharding bestaande uit gewapend of ongewapend beton. |IMBOR2020|
|elementenverharding|de bestrating is in tegenstelling tot een gesloten verharding opgebouwd uit losse elementen die in meer of mindere mate met elkaar verbonden zijn.|IMBOR2020|
|halfverharding|een halfverharding bestaat uit onsamenhangend materiaal dat meer draagkracht levert dan de originele grond.|IMBOR2020|
|kunststofverharding|Synthetisch vervaardigd materiaal dat als verharding dient, zoals kunstgras of kunststof toplagen.|IMBOR2020|
|onverhard|een object zonder specifieke verharding, bestaande uit natuurlijke materialen.|IMBOR2020|

**hieronder het oude materiaal van verhardingsoject - nog opschonen**

| klasse  | naam  |
|---|---|
|SOR-objecttype   | verhardingsobject  |
| onderdeel van NEN3610-objecttype | verharding  |


Voor het objecttype ‘verhardingsobject’ is de typering overgenomen uit IMBOR 2020. Dit leidt tot de volgende mogelijke typeringen:

|classificatie (verplicht)	| Plus classificatie (vrijwillig)|
|---------------------------|--------------------------------|
|Fysiek voorkomen:| |	 
|Asfaltverharding	|Zoab en open deklagen|
|| 	Oppervlakbehandelingen|
|| 	Dichte deklagen|
|Betonverharding|Ongewapend verdeuveld beton|
|| 	Gewapend beton|
|| 	Oppervlakbehandelingen|
|| 	Ongewapend nietverdeuveld beton|
|Elementenverharding| Natuursteen|
|| 	Straatbaksteen|
|| 	Glas|
|| 	Betonstraatstenen|
|| 	Tegels|
|| 	Hout|
|| 	Betonelement|
|| 	Metaal|
|| 	Sierbestrating|
|Halfverharding|Samenhangend|
|| 	Los|
|Kunststofverharding|	Kunststof vloer|
| |Kunstgras|
|Onverhard	|Zand|
|| 	Zwarte grond|
|| 	Open grond|

### GROEN


### BLAUW



#### GEBOUWEN








### Onbepaald terreindeel
| klasse  | naam  |
|---|---|
|SOR-objecttype   | onbepaald terreindeel  |
| onderdeel van NEN3610-objecttype | Bodem  |

Het objecttype ‘Onbepaald terreindeel’ is een nieuw objecttype. Voorgesteld wordt om de volgende typering op te nemen:

|classificatie (verplicht)	| Plus classificatie (vrijwillig)|
|---------------------------|--------------------------------|
|Fysiek voorkomen:| |	 
|Onbekend||	

### Groenobject

| klasse  | naam  |
|---|---|
|SOR-objecttype   | groenobject |
| onderdeel van NEN3610-objecttype | **Bodem en/of Begroeiing**  |

Voor het objecttype ‘groenobject’ is de typering overgenomen uit de huidige BGT|IMGeo 2.1.1. Verwacht wordt dat een uitbreiding van typeringen bij groenvoorziening voor hagen en boomspiegels noodzakelijk is. Hiervoor is nadere afstemming met IMBOR 2020 nodig. Dit leidt tot de volgende typeringen voor het objecttype ‘groenobject’:

|classificatie (verplicht)	| Plus classificatie (vrijwillig)|
|---------------------------|--------------------------------|
|Fysiek voorkomen:| |	 
|Boomteelt	 ||
|Bouwland	|Braakliggend|
|| 	Tuinachtige grond|
|| 	Tuinbouwgrond|
|| 	Bollenteelt|
|| 	Vollegrondsteelt|
|| 	Akkerbouw|
|Duin	|Gesloten duinvegetatie|
|| 	Open duinvegetatie|
|Fruitteelt	|Laagstam boomgaarden|
|| 	Klein fruit|
|| 	Hoogstam boomgaarden|
|| 	Wijngaarden|
|Grasland agrarisch	|Weide|
||Grasland overig	|Helmgras|
|| 	Schraalgrasland|
|| 	Ruig gras|
|| 	Natuurlijke grasvegetatie|
|Gemengd bos||
|Graft	 ||
|Heide	|Droge heide|
|| 	Natte heide|
|Houtwal	 ||
|Kwelder	 ||
|Loofbos	|Griend en hakhout|
|Moeras	|Moerasvegetatie|
|Naaldbos	 ||
|Rietland	|Rietvegetatie|
|| 	Plasberm|
|Slik	 ||
|Steilwand	 ||
|Struiken	 ||
|Zandvlakte	|Zandverstuiving|
|| 	Strand en strandwal|
|groenvoorziening	|bosplantsoen|
|| 	gras- en kruidachtigen|
|| 	planten|
|| 	struikrozen|
|| 	heesters|
|| 	bodembedekkers|


### Waterobject
| klasse  | naam  |
|---|---|
|SOR-objecttype   | waterobject |
| onderdeel van NEN3610-objecttype |water |


Voor het objecttype ‘waterobject’ is de typering uit de huidige BGT|IMGeo 2.1.1 aangescherpt conform eerder gestelde uitgangspunten. Hierdoor is er geen sprake meer van multitypering van watervlakten. Daarnaast is ervoor gekozen om de typering ‘zee’ onder ‘watervlakte’ te plaatsen, Dit heeft als consequentie dat zee op basis van het huidige model van het verplichte deel naar het vrijwillige deel opschuift. Bij de verdere uitwerking zal worden bekeken op welke wijze hiermee kan worden omgegaan. 

|classificatie (verplicht)	| Plus classificatie (vrijwillig)|
|---------------------------|--------------------------------|
|Type:| |	 
|waterloop	|rivier|
|| 	sloot|
|| 	kanaal|
|| 	beek|
|| 	gracht|
|| 	bron|
|watervlakte	|zee|
|| 	meer|
|| 	plas|
|| 	ven|
|| 	vijver|
|greppel/droge sloot	 ||


### Bebouwing
| klasse  | naam  |
|---|---|
|SOR-objecttype   | bebouwing  |
| onderdeel van NEN3610-objecttype | gebouw  |

De typering behorende bij de aan gebouwen gerelateerde fysieke objecttypen zal in het vervolgtraject nader worden onderzocht.

### Kunstwerkdeel
| klasse  | naam  |
|---|---|
|SOR-objecttype   | kunstwerkdeel  |
| onderdeel van NEN3610-objecttype | kunstwerk  |

De typering behorende bij kunstwerkdeel is overgenomen uit de huidige BGT|IMGeo 2.1.1 aangevuld met de objecttyperingen zoals in het voorstel voor IMGeo 2.2 zijn opgenomen. Uitgezonderd is de groeiplaatsinrichting omdat hiervoor afstemming met IMBOR2020 nodig is.



|classificatie (verplicht)	| Plus classificatie (vrijwillig)|
|---------------------------|--------------------------------|
|Type:| |	 	 
|hoogspanningsmast	 ||
|gemaal	 ||
|Perron	 ||
|sluisdeur	 ||
|strekdam	 ||
|Steiger	 ||
|Stuw	 ||
|*Niet BGT*	|keermuur|
|*Niet BGT*	|overkluizing|
|*Niet BGT*	|duiker|
|*Niet BGT*	|faunavoorziening|
|*Niet BGT*	|vispassage|
|*Niet BGT*	|bodemval|
|*Niet BGT*	|coupure|
|*Niet BGT*	|ponton|
|*Niet BGT*	|voorde|
|*Niet BGT*	|hellingbaan|
|*Niet BGT*	|vlonder|

### Tunneldeel

| klasse  | naam  |
|---|---|
|SOR-objecttype   | tunneldeel  |
| onderdeel van NEN3610-objecttype | kunstwerk  |

De typering behorende bij tunneldeel is overgenomen uit de huidige BGT|IMGeo 2.1.1. In het voorstel voor IMGeo 2.2 zijn voor het tunneldeel geen aanvullingen opgenomen.

|classificatie (verplicht)	| Plus classificatie (vrijwillig)|
|---------------------------|--------------------------------|
|Tunneldeel| |	 

### Overbruggingsdeel
| klasse  | naam  |
|---|---|
|SOR-objecttype   |overbruggingsdeel   |
| onderdeel van NEN3610-objecttype | kunstwerk  |

De typering behorende bij overbruggingsdeel is overgenomen uit de huidige BGT|IMGeo 2.1.1. In het voorstel voor IMGeo 2.2 zijn voor het overbruggingsdeel geen aanvullingen opgenomen.

|classificatie (verplicht)	| Plus classificatie (vrijwillig)|
|---------------------------|--------------------------------|
|overbruggingsdeel|Hoort bij type overbrugging: |	
||	brug|
|| 	aquaduct|
|| 	viaduct|
|| 	ecoduct|
|| 	fly-over|
||| 	 
|| 	Type Overbruggingsdeel
|| 	dek|
|| 	landhoofd|
|| 	pijler|
|| 	sloof|
|| 	pyloon|


### Bouwwerkconstructie
| klasse  | naam  |
|---|---|
|SOR-objecttype   | constructie  |
| onderdeel van NEN3610-objecttype | constructie  |

De typering behorende bij Constructie is overgenomen uit de huidige BGT|IMGeo 2.1.1 en aangevuld met de objecttyperingen zoals in het voorstel voor IMGeo 2.2 zijn opgenomen.

*voorheen werd dit **overige bouwwerken** genoemd* 

|classificatie (verplicht)	| Plus classificatie (vrijwillig)|
|---------------------------|--------------------------------|
|Type:| |	
|bezinkbak	 ||
|lage trafo	 ||
|Bassin	 ||
|*Niet BGT*	|sleufsilo|
|*Niet BGT*	|infiltratiereservoir|

### Scheiding
| klasse  | naam  |
|---|---|
|SOR-objecttype   | scheiding  |
| onderdeel van NEN3610-objecttype | **constructie** |

De typering behorende bij scheiding is overgenomen uit de huidige BGT|IMGeo 2.1.1. In het voorstel voor IMGeo 2.2 zijn voor scheiding geen aanvullingen opgenomen.

|classificatie (verplicht)	| Plus classificatie (vrijwillig)|
|---------------------------|--------------------------------|
|Type:| |		 
|Muur	 |
|Kademuur	 |
|damwand	 |
|geluidsscherm	 |
|walbescherming	 |
|Hek	 |
|*Niet BGT*	|draadraster|
|*Niet BGT*	|faunaraster|

### Overige scheidingen
| klasse  | naam  |
|---|---|
|SOR-objecttype   | overige scheidingen  |
| onderdeel van NEN3610-objecttype | **constructie**  |


