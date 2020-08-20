## Fysieke objecttypen

In dit hoofdstuk is een eerste aanzet opgenomen tot nadere typering van de verschillende fysieke objecttypen in de samenhangende objectenregistratie. Deze aanzet is primair gebaseerd op de ook nu reeds in de bestaande basisregistraties gehanteerde typeringen. Vanwege een strikte scheiding tussen fysieke objecttypen en functionele objecttypen zijn op deze typeringen soms beperkte aanpassingen doorgevoerd. Ook zijn enkele eerste wijzigingen voorgesteld die het gevolg zijn van het in hoofdstuk 2 genoemde uitgangspunt over heldere definiëring. Tenslotte is daar waar mogelijk reeds bekeken in hoeverre aanpalende sectorale typeringen aanleiding kunnen geven tot een aangescherpte typering. 

Deze typering is in deze fase van het traject vooral bedoeld om een eerste indruk te geven van de richting waarin de inhoud van de samenhangende objectenregistratie zich beweegt. Samen met experts vanuit de verschillende domeinen en gebruikers zal in het vervolg nog nader onderzoek noodzakelijk zijn om tot definitieve typeringen met bijbehorende definities te komen. Ook zal daarbij nog moeten worden bepaald in hoeverre het nu opgenomen onderscheid tussen de verplichte classificatie en de vrijwillige classificatie aanpassing behoeft. Hierbij is het uiteindelijk de bedoeling om te komen tot een “uitklapmodel” van typeringen, waarbij gedetailleerde typeringen (in de samenhangende objectenregistratie, maar bij voorkeur ook in sectorale registraties) altijd een nadere uitwerking vormen van één bepaalde hoofdtypering (in de samenhangende objectenregistratie).

### Bodem

#### Bodem

| klasse  | naam  |
|---|---|
|SOR-begrip   | Bodem |
| onderdeel van NEN3610-objecttype |  Bodem  |

ontwerpprincipe: *nog bediscussieren in de werkgroep Inhoud*

**Definitie**

| Naam  | bodem |
|---|---|
| Definitie |Bovenste deel van het natuurlijke aardoppervlak.|
|Herkomst definitie  |concept NEN3610 2020|
|Verplicht  | Ja  |
|Toelichting| *volgt later*  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip bodem|Ja |
|Geometrie-type|vlak|Ja|
|Afbakening   |  bodem niet verharding of begroeiing. Het gaat hierbij over het type  waarmee het vlak overwegend is bedekt. Voor minimale stukjes, 5m2, met ander type hoeft geen apart vlak te worden gevormd.|Ja   |
|Status   |   |Ja   |
|type bodem|aanduiding soort bodem|Ja|
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |

**Domeinwaarden**

|Waarde type bodem| Beschrijving   |Herkomst|
|---|---|---|
|   Zand|Type gedetailleerd van verhardingsobject, onverhard  waarvan het oppervlak (deklaag) bestaat uit zand.|IMBOR2020|
| 	Zwarte grond|Type gedetailleerd van verhardingsobject, waarvan het oppervlak bestaat uit zwarte grond.|IMBOR2020|
| 	Open grond|Type gedetailleerd van verhardingsobject, onverhard waarvan het oppervlak bestaat uit open grond, niet zijnde zand of zwarte grond.|IMBOR2020|


### Water

#### Watervlakte
| klasse  | naam  |
|---|---|
|SOR-begrip   | Watervlakte  |
| onderdeel van NEN3610-objecttype |Water  |

ontwerpprincipe: 

**Definitie**

| Naam  | Watervlakte  |
|---|---|
| Definitie | Een verlaging in het aardoppervlak van natuurlijke of kunstmatige oorsprong, die permanent of periodiek water bevat. |
|Herkomst definitie  | AQUO lex    |
|Verplicht  | Ja  |
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip watervlakte |Ja |
|Geometrie-type|vlak|Ja|
|Afbakening   |   |Ja   |
|Status   |   |Ja   |
|type watervlakte|aanduiding soort watervlakte|Nee|
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|bron|hoort bij|watervlakte|

**Domeinwaarden**

|Waarde Status| Beschrijving   |
|---|---|

.

|Waarde type watervlakte| Beschrijving   |Herkomst|
|---|---|---|
|zee|Uitgestrekt oppervlak zout water. |IMGeo 2.1.1|
|meer|*geen onderscheidende definitie gevonden*||
|plas|*geen onderscheidende definitie gevonden*||
|ven|*geen onderscheidende definitie gevonden*||
|vijver|*geen onderscheidende definitie gevonden*||


#### Waterloop
| klasse  | naam  |
|---|---|
|SOR-begrip   | Waterloop  |
| onderdeel van NEN3610-objecttype |Water  |

ontwerpprincipe: 

**Definitie**

| Naam  | Waterloop  |
|---|---|
| Definitie | Een langgerekte verlaging in het terrein van natuurlijke of kunstmatige oorsprong die permanent of periodiek stromend water bevat.  |
|Herkomst definitie  | AQUO lex    |
|Verplicht  | Ja  |
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip waterloop |Ja |
|Geometrie-type|vlak|Ja|
|Afbakening   |   |Ja   |
|Status   |   |Ja   |
|type waterloop|aanduiding soort waterloop|Nee|
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|

**Domeinwaarden**

|Waarde Status| Beschrijving   |
|---|---|

.

|Waarde type waterloop| Beschrijving   |Herkomst|
|---|---|---|
|rivier|Het water, dat ten atmosferische neerslag op hellende terreinen valt, vloeit, voor zover het niet verdampt of door planten wordt opgenomen, tezamen tot een waterloop en stroomt naar laaggelegen streken. Zulk een natuurlijke afvloeiing heet een rivier.|IMGeo 2.1.1|
|sloot|Een waterloop van beperkte breedte die stilstaand of langzaam stromend water bevat , welke is aangelegd met als doel het beheersen van het waterpeil.|IMGeo 2.1.1|
|kanaal|Een gegraven grote waterloop die dient voor scheepvaart en/of watertransport.|IMGeo 2.1.1|
|beek|Een natuurlijke smalle waterloop zonder getij, die veelal doorwaadbaar is en afwatert op een rivier.|IMGeo 2.1.1|
|gracht|Een gracht is een gegraven greppel met water, die hoofdzakelijk voorkomt in oude steden.|IMGeo 2.1.1|


#### Bron
| klasse  | naam  |
|---|---|
|SOR-begrip   | Bron  |
| onderdeel van NEN3610-objecttype |Water  |

ontwerpprincipe: 

**Definitie**

| Naam  | Bron  |
|---|---|
| Definitie | Grondwater dat op natuurlijke wijze uit het aardoppervlak tevoorschijn komt.|
|Herkomst definitie  | IMGeo 2.1.1   |
|Verplicht  | Ja  |
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip bron |Ja |
|Geometrie-type|vlak|Ja|
|Afbakening   |   |Ja   |
|Status   |   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|bron|hoort bij|watervlakte|
|bron|hoort bij|waterloop|

**Domeinwaarden**

|Waarde Status| Beschrijving   |
|---|---|
|||


#### Getijdengebied
| klasse  | naam  |
|---|---|
|SOR-begrip   | Getijdengebied  |
| onderdeel van NEN3610-objecttype |Water  |

ontwerpprincipe: 

**Definitie**

| Naam  | Getijdengebied  |
|---|---|
| Definitie | Geheel of gedeeltelijk droogvallende gronden, buitendijks gelegen.  |
|Herkomst definitie  | Basisregistratie Topografie: Catalogus en Productspecificaties (versie 1.2.0.1)   |
|Verplicht  | Ja  |
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip getijdengebied |Ja |
|Geometrie-type|vlak|Ja|
|Afbakening   |  |Ja   |
|Status   |   |Ja   |
|type getijdengebied|aanduiding soort getijdengebied|Nee|
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |


**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|


**Domeinwaarden**

|Waarde Status| Beschrijving   |
|---|---|
|||

x

|Waarde type getijdengebied| Beschrijving   |Herkomst|
|---|---|---|
|slik|Buitendijks aangeslibde, onbegroeide grond die bij vrijwel elk hoogwater onderloopt. |IMGeo 2.1.1|
|schor|Buitendijks aangeslibd land, dat bij gewone vloed niet meer onderloopt en doorgaans begroeid is. |AQUO lex|
|kwelder|*synoniem van schor? en komt ook terug als functioneel object?*||


### Begroeiing

 
#### Loofbos


| klasse  | naam  |
|---|---|
|SOR-begrip   | Loofbos  |
| onderdeel van NEN3610-objecttype |Groen  |


**Definitie**

| Naam  | Loofbos |
|---|---|
| Definitie |Terreindeel begroeid met een dusdanige aantal loofbomen dat deze een min of meer gesloten geheel vormen of, na volgroeiing van de bomen, zullen vormen.  |
|Herkomst definitie  | BGT  |
|Verplicht  | Ja  |
|Toelichting| |

 
####    gemengd bos


| klasse  | naam  |
|---|---|
|SOR-begrip   |    gemengd bos  |
| onderdeel van NEN3610-objecttype |Groen  |


**Definitie**

| Naam  |    gemengd bos |
|---|---|
| Definitie |Terreindeel begroeid met een dusdanig aantal naald- en loofbomen dat deze een min of meer gesloten geheel vormen of, na volgroeiing van de bomen, zullen vormen.  |   
|Herkomst definitie  | BGT  |
|Verplicht  | ja  |
|Toelichting| | 

#### naaldbos


| klasse  | naam  |
|---|---|
|SOR-begrip   | naaldbos  |
| onderdeel van NEN3610-objecttype |Groen  |


**Definitie**

| Naam  | naaldbos |
|---|---|
| Definitie |Terreindeel begroeid met een dusdanige aantal naaldbomen dat deze een min of meer gesloten geheel vormen of, na volgroeiing van de bomen, zullen vormen. | 
|Herkomst definitie  | BGT  |
|Verplicht  | ja  |
|Toelichting| | 

####    griend en hakhout  


| klasse  | naam  |
|---|---|
|SOR-begrip   |    griend en hakhout    |
| onderdeel van NEN3610-objecttype |Groen  |


**Definitie**

| Naam  |   griend en hakhout   |
|---|---|
| Definitie |Terreindeel met opgaande begroeiing van loofbomen, in een dicht groeiverband, en die periodiek wordt ingekort.   |   
|Herkomst definitie  | IMGEO 2.0  |
|Verplicht  | Nee  |
|Toelichting| | 


####    gras- en kruidachtigen


| klasse  | naam  |
|---|---|
|SOR-begrip   |    gras- en kruidachtigen  |
| onderdeel van NEN3610-objecttype |Groen  |


**Definitie**

| Naam  |    gras- en kruidachtigen |
|---|---|
| Definitie |(Grond met) een laagblijvende, aaneengesloten gras- en/of kruidachtige vegetatie.     
|Herkomst definitie  | CROW |
|Verplicht  | ja  |
|Toelichting| | 


####  struiken


| klasse  | naam  |
|---|---|
|SOR-begrip   | struiken  |
| onderdeel van NEN3610-objecttype |Groen  |


**Definitie**

| Naam  | struiken |
|---|---|
| Definitie |Terreindeel bedekt met lage, houtachtige, overblijvende planten gekenmerkt door verschillende vertakkingen dicht bij de wortel en eventueel aanwezigheid van enkele verspreid staande stammen.   |    |
|Verplicht  | ja  |
|Toelichting| | 


##### heesters 


| klasse  | naam  |
|---|---|
|SOR-begrip   | heesters   |
| onderdeel van NEN3610-objecttype |Groen  |


**Definitie**

| Naam  | heesters  |
|---|---|
| Definitie |Beplanting van houtige gewassen die struikvormend zijn en die al dan niet een  gesloten geheel vormen. Het accent ligt op de sierwaarde, de beplanting kan uit één soort of uit meerdere soorten bestaan. Onder de heesters kan een houtachtige of kruidachtige onderbegroeiing aanwezig zijn. Het oppervlak met struikachtige gewassen is meer dan 50% van de totale oppervlakte van het vak.  |  
|Verplicht  | Nee  |
|Toelichting| | 


##### bosplantsoen 


| klasse  | naam  |
|---|---|
|SOR-begrip   | bosplantsoen   |
| onderdeel van NEN3610-objecttype |Groen  |


**Definitie**

| Naam  | bosplantsoen  |
|---|---|
| Definitie |Opgaande beplanting van houtachtige gewassen die struikvormend en/of boomvormend zijn. De soorten zijn als bosplantsoen opgekweekt en aangeplant.De beplanting kan open of  gesloten zijn en bestaat vaak uit inheemse soorten. Onderscheidt zich van heesters omdat de sierkenmerken niet voorop staan.   |    
|Herkomst definitie  | CROW |
|Verplicht  | Nee  |
|Toelichting| | 

##### planten


| klasse  | naam  |
|---|---|
|SOR-begrip   | planten  |
| onderdeel van NEN3610-objecttype |Groen  |


**Definitie**

| Naam  | planten |
|---|---|
| Definitie |*niet ingevuld**  |    |
|Verplicht  | Nee  |
|Toelichting| | 


##### struikrozen


| klasse  | naam  |
|---|---|
|SOR-begrip   | struikrozen  |
| onderdeel van NEN3610-objecttype |Groen  |


**Definitie**

| Naam  | struikrozen |
|---|---|
| Definitie |*niet ingevuld*  |    |
|Verplicht  | Nee  |
|Toelichting| | 

##### bodembedekkers


| klasse  | naam  |
|---|---|
|SOR-begrip   | bodembedekkers  |
| onderdeel van NEN3610-objecttype |Groen  |


**Definitie**

| Naam  | bodembedekkers |
|---|---|
| Definitie |*niet ingevuld*  |    |
|Verplicht  | Nee  |
|Toelichting| |


#### haag

| klasse  | naam  |
|---|---|
|SOR-begrip   | haag |
| onderdeel van NEN3610-objecttype |Groen |


**Definitie**

| Naam  | haag  |
|---|---|
| Definitie |Een rijvormige afscheiding van zeer beperkte breedte bestaande uit aangeplante aaneengesloten struiken.   |
|Herkomst definitie  | IMGeo   |
|Verplicht  | ja  |
|Toelichting|  |


#### bomenrij

| klasse  | naam  |
|---|---|
|SOR-begrip   | bomenrij |
| onderdeel van NEN3610-objecttype |Groen |


**Definitie**

| Naam  | bomenrij |
|---|---|
| Definitie |opgaande begroeiing van bomen zonder struiken  |
|Herkomst definitie  |   |
|Verplicht  | ja  |
|Toelichting|  |

#### houtsingel

| klasse  | naam  |
|---|---|
|SOR-begrip   | houtsingel |
| onderdeel van NEN3610-objecttype |Groen |


**Definitie**

| Naam  | houtsingel |
|---|---|
| Definitie |opgaande begroeiing van  bomen (enkelvoudige/meervoudige stammen) en struiken  |
|Herkomst definitie  |   |
|Verplicht  | ja  |
|Toelichting|  |

#### moeras

| klasse  | naam  |
|---|---|
|SOR-begrip   | moeras |
| onderdeel van NEN3610-objecttype |Groen |


**Definitie**

| Naam  | moeras |
|---|---|
| Definitie |Terreindeel met moerasvegetatie in stilstaand water van geringe diepte zonder merkbare toe- of afvloeiing.  |
|Herkomst definitie  | bron: BGT |
|Verplicht  | ja  |
|Toelichting|  |

#### heide

| klasse  | naam  |
|---|---|
|SOR-begrip   | heide |
| onderdeel van NEN3610-objecttype |Groen |


**Definitie**

| Naam  | heide |
|---|---|
| Definitie |Terreindeel overwegend begroeid met heide en heideachtige vegetaties.  |
|Herkomst definitie  |BGT|
|Verplicht  | ja  |
|Toelichting|  |

#### rietland

| klasse  | naam  |
|---|---|
|SOR-begrip   | rietland |
| onderdeel van NEN3610-objecttype |Groen |


**Definitie**

| Naam  | rietland |
|---|---|
| Definitie |Terreindeel overwegend begroeid met rietvegetatie.  |
|Herkomst definitie  | BGT  |
|Verplicht  | ja  |
|Toelichting|  |



#### bouwland 

| klasse  | naam  |
|---|---|
|SOR-begrip   | bouwland  |
| onderdeel van NEN3610-objecttype |Groen |


**Definitie**

| Naam  | bouwland  |
|---|---|
| Definitie |TTerreindeel in gebruik als akker, met gewassen die in een teelt roulatieschema zijn opgenomen. Kan tijdelijk zonder gewas zijn of braak liggen. |
|Herkomst definitie  | BGT  |
|Verplicht  | ja  |
|Toelichting|  |



####    fruit- bomenteelt

| klasse  | naam  |
|---|---|
|SOR-begrip   | fruit- bomenteelt |
| onderdeel van NEN3610-objecttype |Groen |


**Definitie**

| Naam  | fruit- bomenteelt |
|---|---|
| Definitie |Terreindeel begroeid met fruitbomen in de vorm van hoogstam en laagstamboomgaard, druiven of kleinfruit. en Grond in gebruik voor het kweken van jonge siergewassen, bomen enz. ten behoeve van een later gebruik elders.   |
|Herkomst definitie  | BT / CROW  |
|Verplicht  | ja  |
|Toelichting|  |

#####    laagstam boomgaarden 

| klasse  | naam  |
|---|---|
|SOR-begrip   |    laagstam boomgaarden  |
| onderdeel van NEN3610-objecttype |Groen |


**Definitie**

| Naam  |    laagstam boomgaarden  |
|---|---|
| Definitie |Terreindeel begroeid met laagstamfruitbomen.   |
|Herkomst definitie  | IMGEO 2.0  |
|Verplicht  | nee  |
|Toelichting|  |

#####    hoogstam boomgaarden

| klasse  | naam  |
|---|---|
|SOR-begrip   |    hoogstam boomgaarden |
| onderdeel van NEN3610-objecttype |Groen |


**Definitie**

| Naam  |    hoogstam boomgaarden |
|---|---|
| Definitie |Terreindeel begroeid met hoogstamfruitbomen.   |
|Herkomst definitie  | IMGEO 2.0   |
|Verplicht  | nee  |
|Toelichting|  |

##### wijngaarden  

| klasse  | naam  |
|---|---|
|SOR-begrip   | wijngaarden   |
| onderdeel van NEN3610-objecttype |Groen |


**Definitie**

| Naam  | wijngaarden   |
|---|---|
| Definitie |Terreindeel begroeid met druivenstokken voor wijnbouw.  |
|Herkomst definitie  |IMGEO 2.0    |
|Verplicht  | nee  |
|Toelichting|  |

#####    klein fruit

| klasse  | naam  |
|---|---|
|SOR-begrip   |    klein fruit |
| onderdeel van NEN3610-objecttype |Groen |


**Definitie**

| Naam  |    klein fruit |
|---|---|
| Definitie |Terreindeel begroeid met heesters voor zachtfruit zoals bessen of frambozen.   |
|Herkomst definitie  | IMGEO 2.0   |
|Verplicht  | nee  |
|Toelichting|  |

##### boomkwekerij 

| klasse  | naam  |
|---|---|
|SOR-begrip   | boomkwekerij  |
| onderdeel van NEN3610-objecttype |Groen |


**Definitie**

| Naam  | boomkwekerij  |
|---|---|
| Definitie |Terrein, overwegend in gebruik t.b.v. het opkweken van bomen (inclusief coniferen en sparren) en struiken, waarbij de hoogte van de aanplant niet van belang is.  |
|Herkomst definitie  |   |
|Verplicht  | nee  |
|Toelichting|  |



#### OUD Groenobject

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


### Constructie; Gebouw

#### Gebouw

| klasse  | naam  |
|---|---|
|SOR-begrip   | Gebouw  |
| onderdeel van NEN3610-objecttype |Gebouw  |

**Definitie**

| Naam  | Gebouw  |
|---|---|
| Definitie | Overdekte en geheel of gedeeltelijk met wanden omsloten constructief zelfstandige eenheid bedoeld voor het in een afgeschermde omgeving onderbrengen van mensen, dieren of voorwerpen of voor de productie van goederen. |
|Herkomst definitie  |Gebaseerd op definitie “pand” in artikel 1 Wet basisregistratie adressen en gebouwen en de INSPIRE richtlijn |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier grotendeels de bestaande populatie panden zoals deze is opgenomen in de basisregistratie adressen en gebouwen en de basisregistratie grootschalige topografie |
|Toelichting| *volgt later* |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een Gebouw  |Ja |
|Geometrie |De geometrische representatie van de randen van een gebouw *nader te preciseren op basis van generieke uitspraken over de vastlegging van geometrie*  |Ja|
|Typering |Het doel waarvoor een gebouw gebruikt wordt  |Ja|
|Aard|De fysieke verschijningsvorm van een gebouw
*nader te bepalen of  deze typering ook een antwoord geeft op de vraag in welke hoogteklasse een gebouw is gelegen, welke soortnaam het betreft en van welk fysiek voorkomen sprake is*   |Ja|
|Oorspronkelijk bouwjaar | DDe aanduiding van het jaar waarin een gebouw oorspronkelijk als bouwkundig gereed is of zal worden opgeleverd|Ja|
|Naam| Een breed geaccepteerde benaming van een gebouw zoals deze door de eigenaar is toegekend of zoals deze in de volksmond bekend staat| Nee|
|Toegangsdeur| NTB ||
|Aantal bouwlagen | NTB||
|Status   |De fase van de levenscyclus waarin het gebouw zich bevindt    |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
||||

**Domeinwaarden**

| Waarde Typering| Beschrijving   |
|---|---|
|Woning| |
| Bedrijf ||
|||
| ... |*aanvullingen BRT en Bgt??* |

| Waarde Status | Beschrijving   |
|---|---|
|Gepland||
|Bouwvergunning verleend||
|Sloopvergunning verleend||
|In aanbouw||
|Bestaand||
|In verbouw||
|Gesloopt||
|Niet gerealiseerd||
|Ten onrechte||


#### Bouwlaag


| klasse  | naam  |
|---|---|
|SOR-begrip   | Bouwlaag  |
| onderdeel van NEN3610-objecttype |Gebouw  |

**Definitie**

| Naam  | Bouwlaag  |
|---|---|
| Definitie | De verzameling van ruimten die zijn gelegen op hetzelfde niveau binnen een gebouw |
|Herkomst definitie  |Gebaseerd op de definitie van het begrip Bouwlaag (IfcBuildingStorey) uit de concepten rondom Bouwwerkinformatiemodellen (BIM)|
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier ten opzichte van de bestaande basisregistraties een nieuw objecttype |
|Toelichting| *volgt later* |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een Bouwlaag  |Ja |
|Geometrie |De geometrische representatie van de randen van een Bouwlaag *nader te preciseren op basis van generieke uitspraken over de vastlegging van geometrie*  |Ja|
|Bowlaagnummer |Het niveau waarop de bouwlaag zich bevindt|Ja|
|Oppervlakte| NTB||
|Status   |De fase van de levenscyclus waarin een Bouwlaag zich bevindt   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|Bouwlaag|Ligt in|Gebouw|

**Domeinwaarden**


| Waarde Status | Beschrijving   |
|---|---|
|Gepland||
|Bouwvergunning verleend||
|Sloopvergunning verleend||
|In aanbouw||
|Bestaand||
|In verbouw||
|Gesloopt||
|Niet gerealiseerd||
|Ten onrechte||

#### Ruimte


| klasse  | naam  |
|---|---|
|SOR-begrip   | Ruimte  |
| onderdeel van NEN3610-objecttype |Gebouw  |

**Definitie**

| Naam  | Ruimte  |
|---|---|
| Definitie | Een voor mensen toegankelijk deel van een gebouw, dat ten minste aan de onderzijde en/of de bovenzijde wordt begrensd door een scheidingsconstructie en dat een netto-hoogte heeft van tenminste 1,5 m|
|Herkomst definitie  |Ontleend aan NEN 2580 en aansluitend op het begrip Ruimte (IfcSpace) uit de concepten rondom Bouwwerkinformatiemodellen (BIM)|
|Verplicht  | Nee  |
|Gevolgen afbakening  | Het betreft hier ten opzichte van de bestaande basisregistraties een nieuw objecttype |
|Toelichting| *volgt later* |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een Ruimte  |Ja |
|Geometrie |De geometrische representatie van de randen van een Ruimte *nader te preciseren op basis van generieke uitspraken over de vastlegging |van geometrie*  |Ja|
|Typering|Het doel waarvoor een ruimte gebruikt wordt|Ja|
|Bouwlaagnummer |De bouwlaag waarop de ruimte zich bevindt|Ja|
|Oppervlakte| NTB||
|Status   |De fase van de levenscyclus waarin een Ruimte zich bevindt   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|Ruimte|Ligt op|Bouwlaag|

**Domeinwaarden**

| Waarde Typering| Beschrijving   |
|---|---|
|Woonkamer| |
|Keuken ||
|||
| ... |*lijst vanuit BIM checken* |

| Waarde Status | Beschrijving   |
|---|---|
|Gepland||
|Bouwvergunning verleend||
|Sloopvergunning verleend||
|In aanbouw||
|Bestaand||
|In verbouw||
|Gesloopt||
|Niet gerealiseerd||
|Ten onrechte||

#### Installatie



| klasse  | naam  |
|---|---|
|SOR-begrip   | Installatie  |
| onderdeel van NEN3610-objecttype |Gebouw  |

**Definitie**

| Naam  | Installatie  |
|---|---|
| Definitie | Geheel van een relevantie installatie of andere voorziening in of aan en ten dienste van het Gebouw|
|Herkomst definitie  |Gebaseerd op de GebouwInstallatie uit NEN 2580/ Bouwbesluit/ INSPIRE, IFC-elementen uit de concepten rondom Bouwwerkinformatiemodellen (BIM) en enkele aspecten van  fysieke deelobjecten uit de WOZ|
|Verplicht  | Nee  *nader te bepalen* |
|Gevolgen afbakening  | Het betreft hier ten opzichte van de bestaande basisregistraties grotendeels een nieuw objecttype. *Nog nader bepaald zal worden hoe we een en ander afstemmen op het BGT objecttype gebouwdeel en op het feit dat installaties ook bij andere objecten dan gebouwen kunnen behoren*|
|Toelichting| *volgt later* |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een Installatie  |Ja |
|Geometrie |De geometrische representatie van de randen van een Installatie *nader te preciseren op basis van generieke uitspraken over de vastlegging van geometrie*  |Ja|
|Aard|Het doort installatie|Ja|
|Bijbehorend object |Het object waarbij de betreffende installatie behoort|Ja|
|Status   |De fase van de levenscyclus waarin de betreffende installatie zich bevindt   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|Installatie|Hoort bij|Verblijfsobject|
|Installatie|Hoort bij|Gebouw|

**Domeinwaarden**

| Waarde Aard| Beschrijving   |
|---|---|
|zonnepanelen < 5 kWp| |
|zonnepanelen > 5 kWp| |
|dakkapel ||
|lift||
| ... |*lijst vanuit elders checken* |

| Waarde Status | Beschrijving   |
|---|---|
|Gepland||
|Bouwvergunning verleend||
|Sloopvergunning verleend||
|In aanbouw||
|Bestaand||
|In verbouw||
|Gesloopt||
|Niet gerealiseerd||
|Ten onrechte||

#### Toegangsdeur


| klasse  | naam  |
|---|---|
|SOR-begrip   | Toegangsdeur  |
| onderdeel van NEN3610-objecttype |Gebouw  |

**Definitie**

| Naam  | Toegangsdeur |
|---|---|
| Definitie | Deur of andere voorziening die vanaf de openbare weg, een erf of een gedeelde verkeersruimte toegang geeft tot een object|
|Herkomst definitie  |Begrip sluit aan bij het begrip Deur (IfcDoor) uit de concepten rondom Bouwwerkinformatiemodellen (BIM)|
|Verplicht  | Nee  *nader te bepalen* |
|Gevolgen afbakening  | Het betreft hier ten opzichte van de bestaande basisregistraties grotendeels een nieuw objecttype.  *Bekeken zal nog moeten worden in hoeverre we dit objecttype ook willen relateren aan objecten als kunstwerken en andere constructies.*|
|Toelichting| *volgt later* |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een Toegangsdeur  |Ja |
|Geometrie |De geometrische representatie van een Toegangsdeur *nader te preciseren op basis van generieke uitspraken over de vastlegging van geometrie*  |Ja|
|Aard|De plaats waarvan de toegangsdeur toegang geeft|Ja|
|Tyoe|het soort toegangsdeur|Ja|
|Bijbehorend object |Het object waarin de betreffende toegangsdeur zich bevindt|Ja|
|Status   |De fase van de levenscyclus waarin de betreffende Toegangsdeur zich bevindt   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|Toegangsdeur|Hoort bij|Verblijfsobject|
|Toegangsdeur|Hoort bij|Gebouw|

**Domeinwaarden**

| Waarde Aard| Beschrijving   |
|---|---|
|directe toegang vanaf eigen terrein| |
|directe toegang vanaf openbare weg| |
|toegang vanaf gemeenschappelijke verkeersruimte ||

| Waarde Type| Beschrijving   |
|---|---|
|Personen| |
|Auto| |
|Vracht||

| Waarde Status | Beschrijving   |
|---|---|
|Gepland||
|Bestaand||
|Verwijderd|
|Niet gerealiseerd||
|Ten onrechte||




### *Bouwwerkconstructie*
| klasse  | naam  |
|---|---|
|SOR-begrip   | constructie  |
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




### Constructie; Verharding
#### Verharding

| klasse  | naam  |
|---|---|
|SOR-begrip   | Verharding  |
| onderdeel van NEN3610-objecttype |Verharding |

ontwerpprincipe: 

**Definitie**

| Naam  | Verharding |
|---|---|
| Definitie |Een door egaliseren, verstevigen en/of verruwen voor het beoogde gebruik geschikt gemaakt oppervlak, bestaande uit in één of meer lagen over een ondergrond of onderliggende constructie aangelegd materiaal. |
|Herkomst definitie  | concept NEN3610-2020  |
|Verplicht  | Ja  |
|Toelichting| *volgt later*  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip verharding |Ja |
|Geometrie-type|vlak|Ja|
|Afbakening   |  Een verhardingsvlak bestaat uit één type verharding. Het gaat hierbij over het type verharding waarmee het vlak overwegend is bedekt. Voor minimale stukjes, 5m2, met andere verharding hoeft geen apart vlak te worden gevormd.|Ja   |
|Status   |   |Ja   |
|type verharding|aanduiding soort verharding|Ja|
|type verharding plus|aanduiding soort verharding|Nee|
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

.

|Waarde type verharding| Beschrijving   |Herkomst|
|---|---|---|
|asfaltverharding|Gesloten verharding bestaande uit asfaltbeton of andere met bitumen gebonden materialen.|IMBOR2020|
| betonverharding |Gesloten verharding bestaande uit gewapend of ongewapend beton. |IMBOR2020|
|elementenverharding|de bestrating is in tegenstelling tot een gesloten verharding opgebouwd uit losse elementen die in meer of mindere mate met elkaar verbonden zijn.|IMBOR2020|
|halfverharding|een halfverharding bestaat uit onsamenhangend materiaal dat meer draagkracht levert dan de originele grond.|IMBOR2020|
|kunststofverharding|Synthetisch vervaardigd materiaal dat als verharding dient, zoals kunstgras of kunststof toplagen.|IMBOR2020|
|onverhard|een object zonder specifieke verharding, bestaande uit natuurlijke materialen.|IMBOR2020|  

.

|Waarde type verharding plus| Beschrijving   |Herkomst|
|---|---|---|
|**asfaltverharding**||| 
|   Zoab en open deklagen|*geen definitie opgenomen in IMBOR*|IMBOR2020|
|   Oppervlakbehandelingen|Verharding bestaand uit op het wegoppervlak aangebrachte laag bindmiddel die wordt afgestrooid met steenslag of fijn grind.|IMBOR2020|
|   Dichte deklagen|*geen definitie opgenomen in IMBOR*|IMBOR2020|
|**betonverharding**|||
|   Ongewapend verdeuveld beton|Ongewapend verdeuveld beton is de formele benaming. In de CROW Systematiek Wegbeheer wordt dit ‘verdeuveld’ genoemd.|IMBOR2020|
| 	Gewapend beton|*geen definitie opgenomen in IMBOR*|IMBOR2020|
| 	Oppervlakbehandelingen|Verharding bestaand uit op het wegoppervlak aangebrachte laag bindmiddel die wordt afgestrooid met steenslag of fijn grind.|IMBOR2020|
| 	Ongewapend nietverdeuveld beton|Ongewapend nietverdeuveld beton is de formele benaming. In de CROW Systematiek Wegbeheer wordt dit ‘onverdeuveld’ genoemd.|IMBOR2020|
|**elementenverharding**|||
|   Natuursteen|Type gedetailleerd van verhardingsobject, elementenverharding, verharding bestaande uit elementen van natuursteen.|IMBOR2020|
| 	Straatbaksteen|Type gedetailleerd van verhardingsobject, elementenverharding, straatbaksteen is de formele benaming uit NEN-EN1344. In de CROW Systematiek Wegbeheer wordt dit ‘gebakken klinkers’ genoemd.|IMBOR2020|
| 	Glas|Type gedetailleerd van verhardingsobject, elementenverharding bestaande uit glaselementen.|IMBOR2020|
| 	Betonstraatstenen|Type gedetailleerd van verhardingsobject, elementenverharding, verharding gemaakt van betonstraatstenen. Straatsteen die als goedkope vervanging van de gebakken klinkers is ontwikkeld.|IMBOR2020|
| 	Tegels|Type gedetailleerd van verhardingsobject, elementenverharding, bestrating van tegels, een platte vaak vierkante betonnen steen.|IMBOR2020|
| 	Hout|Type gedetailleerd van verhardingsobject, elementenverharding, verharding bestaande uit houten elementen.|IMBOR2020|
| 	Betonelement|Geprepareerde elementen van beton (bijvoorbeeld stelconplaten).|IMBOR2020|
| 	Metaal|Type gedetailleerd van verhardingsobject, elementenverharding, verharding bestaande uit metalen elementen.|IMBOR2020|
| 	Sierbestrating|Type gedetailleerd van verhardingsobject, elementenverharding, bestrating uitgevoerd in verschillende bestratingsverbanden en -materialen, of in een sierverband, die vooral wordt toegepast uit esthetische overwegingen.|IMBOR2020|
|**Halfverharding**|||
|   Samenhangend|Type gedetailleerd van verhardingsobject, halfverharding, waarvan het oppervlak bestaat uit samenhangend materiaal.|IMBOR2020|
| 	Los|Type gedetailleerd van verhardingsobject, halfverharding: vlak gevuld met losgestort materiaal|IMBOR2020|
|**Kunststofverharding**|||
|	Kunststof vloer|*geen definitie opgenomen in IMBOR*|IMBOR2020|
|   Kunstgras|Kunstgras is een als gras aanziend of aandoend, kunstmatig product van uiteenlopend, synthetisch materiaal.|IMBOR2020|


### Constructie; Kunstwerk
#### Overbrugging

| klasse  | naam  |
|---|---|
|SOR-begrip   | Overbrugging |
| onderdeel van NEN3610-objecttype | Kunstwerk  |

ontwerpprincipe: 

**Definitie**

| Naam  | Overbrugging  |
|---|---|
| Definitie | Een beweegbare of vaste verbinding tussen twee punten, die door water, een weg of anderszins  gescheiden zijn,  bestaande uit een brugdek/-bak met landhoofden en veelal gesteund door pijlers. |
|Herkomst definitie  |  |
|Verplicht  | Ja  |
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip overbrugging |Ja |
|Geometrie-type|**????**|Ja|
|Afbakening   |  |  |
|Status   |   |Ja   |
|type overbrugging|aanduiding soort overbrugging|Nee|
|beweegbaar||Ja|
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|kunstwerkdeel|hoort bij|overbrugging|
|*sluis|bestaat uit|sluisdeur en kolk*|

**Domeinwaarden**

|Waarde Status| Beschrijving   |
|---|---|
|||
.
|Waarde type overbrugging| Beschrijving   |Herkomst|
|---|---|---|
| brug |Overbruggingsconstructie over een watervlakte of waterloop, bedoelt voor verkeer.||
| aquaduct |Overbruggingsconstructie waarmee een watergang door een bakvormige constructie over een weg, een spoorweg, een andere watergang, een leiding of een terrein wordt geleid.   ||
| viaduct |Overbruggingsconstructie over een weg, spoorweg of terreinverdieping, bedoelt voor verkeer.   ||
| ecoduct |Overbruggingsconstructie over een weg of spoorweg,  bedoelt voor het passeren van dieren.   ||
| flyover|Kunstwerk in de vorm van een viaduct dat deel uitmaakt van een verkeersbaan en waarmee een verkeersstroom over twee of meer ongelijkvloerse verkeersstromen wordt geleid.*bestaande definitie niet consistent*   ||
| overkluizing |Een civieltechnisch kunstwerk waarmee een weg, een plein of een waterloop (kruiselings) wordt overwelft, waarbij het dek meestal niet uitsluitend uit een pad of weg bestaat.   ||

#### Ondertunneling

| klasse  | naam  |
|---|---|
|SOR-begrip   | Ondertunneling |
| onderdeel van NEN3610-objecttype | Kunstwerk  |

ontwerpprincipe: 

**Definitie**

| Naam  | Ondertunneling  |
|---|---|
| Definitie |  |
|Herkomst definitie  |  |
|Verplicht  | Ja  |
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip ondertunneling|Ja |
|Geometrie-type|**????**|Ja|
|Afbakening   |  |  |
|Status   |   |Ja   |
|type ondertunneling|aanduiding soort ondertunneling|Nee|
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|

**Domeinwaarden**

|Waarde Status| Beschrijving   |
|---|---|
|||
.
|Waarde type ondertunneling| Beschrijving   |Herkomst|
|---|---|---|
| tunnel |Kokervormig kunstwerk onder een of meer wegen, spoorwegen, waterwegen en/of andere hindernissen, als ondergrondse doorgang voor verkeer, leidingen of dieren.   ||
| duiker |Kunstwerk voor de waterhuishouding, bestaande uit een gesloten kokervormige constructie met een in- en uitstroomopening, die niet de gehele waterbreedte beslaand, aangebracht onder een weg of spoorweg of in een dam of ander terreindeel en de bodem van de waterloop onderbreekt.   ||

#### Gemaal

| klasse  | naam  |
|---|---|
|SOR-begrip   | Gemaal |
| onderdeel van NEN3610-objecttype | Kunstwerk  |

ontwerpprincipe: 

**Definitie**

| Naam  | Gemaal  |
|---|---|
| Definitie | Een kunstwerk in principe bedoeld om water van een laag peil naar een hoog peil te brengen.  |
|Herkomst definitie  |  |
|Verplicht  | Nee  |
|Toelichting|  |

#### sluis
| sluis |Een kunstmatige, afsluitbare waterkering die een scheepvaartverbinding tussen twee wateren met verschillende waterpeilen mogelijk maakt.   |
#### strekdam
| strekdam |Dam in de richting van de loop van de rivier of kanaal, ter beveiliging van de oevers of brugpijlers of ter beheersing van de rivier.   ||
#### steiger
| steiger |Vaste (niet drijvende) waterbouwkundige constructie, verbonden met de wal, voor het aanleggen van schepen en bedoeld om deze schepen vanaf de wal te laden en te lossen.   ||
#### stuw
| stuw |xxEen vaste of beweegbare constructie in het water die dient om de waterstand bovenstrooms en/of benedenstrooms van de constructie te regelenx   ||
#### keermuur
| keermuur |muur die door vorm, gewicht en fundering zonder verankering de grond keert.   ||
#### faunavoorziening
| faunavoorziening |Voorziening bij een infrastructureel werk om de uit dat werk voortvloeiende negatieve gevolgen voor de fauna zoveel mogelijk te voorkomen of te beperken   ||
#### vispassage
| vispassage |Een waterbouwkundig constructie dat tot doel heeft vissen toegang te bieden tot een door een kunstwerk onbereikbaar geworden achterland.   ||
#### bodemval
| bodemval |Sprong in de bodem van een waterloop.    ||
#### coupure
| coupure |Een onderbreking in een waterkering voor de doorvoer van een weg of spoorweg, die bij extreme waterstanden afsluitbaar is.||
#### ponton
| ponton |Vastliggend drijflichaam, dat dienst doet als aanlegplaats van vaartuigen of daartoe toegang geeft.   ||
#### voorde
| voorde |Een doorwaadbare, doorgaans verharde, plaats in de waterloop, die dient voor de oversteek van die waterloop.    ||
#### kademuur
| *kademuur* |Grondkerende constructie tegen afkalving van de walkant, in de vorm van een verticale wand ter scheiding van land en water, opgebouwd uit een muur van gemetselde stenen of gestort beton. *staat ter discussie - scheiding fysiek (muur) en functie (kering)*    ||
#### damwand
| *damwand* |Grondkerende of waterkerende constructie bestaande uit (nagenoeg) verticaal in de grond aangebrachte elementen die door middel van een langsprofiel in elkaar grijpen. *staat ter discussie - scheiding fysiek (wand) en functie (kering)*  |
#### walbescherming
| *walbescherming* |Een nagenoeg verticale wand tot kering van grond om afkalving van water te voorkomen, niet zijnde een kademuur.*staat ter discussie - scheiding fysiek (wand) en functie (kering)*   |
#### schot
|schot|||
#### dijk
|dijk|*is toch een functie en geen kunstwerk?*||
#### stormvloedkering
|stormvloedkering|||


#### Kunstwerkdeel
| klasse  | naam  |
|---|---|
|SOR-begrip   | Kunstwerkdeel |
| onderdeel van NEN3610-objecttype |Kunstwerk  |

ontwerpprincipe: 

**Definitie**

| Naam  | Kunstwerkdeel  |
|---|---|
| Definitie |  Onderdeel van een civiel-technisch werk voor de infrastructuur van wegen, water, spoorbanen, waterkeringen en/of leidingen. |
|Herkomst definitie  |  BGT 1.1.1  |
|Verplicht  | nee  |
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip kunstwerkdeel |Ja |
|Geometrie-type|**????**|Ja|
|Afbakening   |  |  |
|Status   |   |Ja   |
|type kunstwerkdeel|aanduiding soort kunstwerkdeel|nee|
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
| kunstwerkdeel | hoort bij | kunstwerk |

**Domeinwaarden**

|Waarde Status| Beschrijving   |
|---|---|
|||
.
|Waarde type kunstwerkdeel| Beschrijving   |Herkomst|
|---|---|---|
| dek |Direct door het verkeer belaste deel van de bovenbouw van de brug.   ||
| landhoofd |Ondersteuningsconstructie ter plaatse van een overgang van de aardebaan naar een kunstwerk.   ||
| pijler |Ondersteuningsconstructie van bruggen en soortgelijke kunstwerken.   ||
| sloof |Deel van de pijler voor de overdracht van krachten naar de ondergrond of de fundering.   ||
| pyloon |Boven de bovenbouw uitstekende draagconstructie voor tuien (kabels).   ||
|---|---|---|
| sluisdeur |||
| kolk |||


### Constructie; Overige

#### Muur
  
| klasse  | naam  |
|---|---|
|SOR-begrip   | Muur |
| onderdeel van NEN3610-objecttype | Constructie |

ontwerpprincipe: 


**Definitie**

| Naam  | Muur |
|---|---|
| Definitie |Relatief smal, rechtopstaand bouwwerk.|
|Herkomst definitie  |Basisregistratie Topografie: Catalogus en Productspecificaties (versie 1.2.0.1)|
|Verplicht  | Ja  |
|Toelichting| *volgt later*  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip muur|Ja |
|Geometrie-type|lijn|Ja|
|Geometrie-type|vlak|Nee|
|Afbakening   |  | |
|Status   |   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |

#### Hek
  
| klasse  | naam  |
|---|---|
|SOR-begrip   | Hek |
| onderdeel van NEN3610-objecttype | Constructie |

ontwerpprincipe: 


**Definitie**

| Naam  | Hek |
|---|---|
| Definitie | Een hekwerk of schutting om een gebied af te scheiden of de toegang te beheren.|
|Herkomst definitie  |nieuw|
|Verplicht  | *staat ter discussie* |
|Toelichting| *volgt later*  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip hek|Ja |
|Geometrie-type|lijn|Ja|
|Afbakening   |  | |
|Status   |   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |

#### Raster
  
| klasse  | naam  |
|---|---|
|SOR-begrip   | Raster |
| onderdeel van NEN3610-objecttype | Constructie |

ontwerpprincipe: 


**Definitie**

| Naam  | Raster |
|---|---|
| Definitie |Kunstmatige terreinafscheiding, in de vorm van een overwegend houten, metalen of kunststoffen rechtopstaande palen met daartussen gaas of één of meerdere draden.|
|Herkomst definitie  |Gegevenscatalogus IMGeo 2.1.1 *deels aangepast*|
|Verplicht  | nee  |
|Toelichting| *volgt later*  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip raster|Ja |
|Geometrie-type|lijn|Ja|
|Afbakening   |  | |
|Status   |   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |

#### Scherm
  
| klasse  | naam  |
|---|---|
|SOR-begrip   | Scherm |
| onderdeel van NEN3610-objecttype | Constructie |

ontwerpprincipe: 


**Definitie**

| Naam  | Scherm |
|---|---|
| Definitie |Een lineaire constructie, typisch bedoeld om te reduceren. |
|Herkomst definitie  |nieuw|
|Verplicht  | Ja  |
|Toelichting| *volgt later*  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip scherm|Ja |
|Geometrie-type|lijn|Ja|
|Afbakening   |  | |
|Status   |   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |





