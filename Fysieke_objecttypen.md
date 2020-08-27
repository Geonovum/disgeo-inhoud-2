## Fysieke objecttypen

In dit hoofdstuk is een eerste aanzet opgenomen tot nadere Typering van de verschillende fysieke objecttypen in de samenhangende objectenregistratie. Deze aanzet is primair gebaseerd op de ook nu reeds in de bestaande basisregistraties gehanteerde Typeringen. Vanwege een strikte scheiding tussen fysieke objecttypen en functionele objecttypen zijn op deze Typeringen soms beperkte aanpassingen doorgevoerd. Ook zijn enkele eerste wijzigingen voorgesteld die het gevolg zijn van het in hoofdstuk 2 genoemde uitgangspunt over heldere definiëring. Tenslotte is daar waar mogelijk reeds bekeken in hoeverre aanpalende sectorale Typeringen aanleiding kunnen geven tot een aangescherpte Typering. 

Deze Typering is in deze fase van het traject vooral bedoeld om een eerste indruk te geven van de richting waarin de inhoud van de samenhangende objectenregistratie zich beweegt. Samen met experts vanuit de verschillende domeinen en gebruikers zal in het vervolg nog nader onderzoek noodzakelijk zijn om tot definitieve Typeringen met bijbehorende definities te komen. Ook zal daarbij nog moeten worden bepaald in hoeverre het nu opgenomen onderscheid tussen de verplichte classificatie en de vrijwillige classificatie aanpassing behoeft. Hierbij is het uiteindelijk de bedoeling om te komen tot een “uitklapmodel” van Typeringen, waarbij gedetailleerde Typeringen (in de samenhangende objectenregistratie, maar bij voorkeur ook in sectorale registraties) altijd een nadere uitwerking vormen van één bepaalde hoofdTypering (in de samenhangende objectenregistratie).

### Bodem

#### Bodem

| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Bodem |
| Onderdeel van NEN3610-objecttype |  Bodem  |

ontwerpprincipe: *nog bediscussieren in de werkgroep Inhoud*

> NOOT
> nog bediscussieren in de werkgroep Inhoud

**Definitie**

| Naam  | Bodem |
|---|---|
| Definitie |Bovenste deel van het natuurlijke aardoppervlak.|
| Herkomst definitie  |concept NEN3610 2020|
| Verplicht  | Ja  |
| Gevolgen afbakening  | Het betreft hier ten opzichte van de bestaande basisregistraties een nieuw objecttype, mogelijk het fysieke voorkomen van wegen en terreinen. |
| Toelichting| *volgt later* Het gaat hierbij over het Type  waarmee het vlak overwegend is bedekt. Voor minimale stukjes, 5m2, met ander Type hoeft geen apart vlak te worden gevormd. |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip bodem|Ja |
|Geometrie| |Ja (vlak)|
|Status   |   |Ja   |
|Type bodem|aanduiding soort bodem|Ja|
|Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
||||

**Domeinwaarden**

|Waarde Status| Beschrijving   |
|---|---|
|gepland||
|bestaand||
|verwijderd||
|niet gerealiseerd||
|ten onrechte||

.

|Waarde Type bodem| Beschrijving   |
|---|---|
|   Zand|Type gedetailleerd van verhardingsobject, onverhard  waarvan het oppervlak (deklaag) bestaat uit zand.|
| 	Zwarte grond|Type gedetailleerd van verhardingsobject, waarvan het oppervlak bestaat uit zwarte grond.|
| 	Open grond|Type gedetailleerd van verhardingsobject, onverhard waarvan het oppervlak bestaat uit open grond, niet zijnde zand of zwarte grond.|


### Water

#### Watervlakte
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Watervlakte  |
| Onderdeel van NEN3610-objecttype |Water  |

ontwerpprincipe: 

**Definitie**

| Naam  | Watervlakte  |
|---|---|
| Definitie | Een verlaging in het aardoppervlak van natuurlijke of kunstmatige oorsprong, die permanent of periodiek water bevat. |
|Herkomst definitie  | AQUO lex    |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *watervlakte* en *zee* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip watervlakte |Ja |
|Geometrie|De geometrische representatie van de randen van een watervlakte. *nader te preciseren op basis van generieke uitspraken over de vastlegging van geometrie* |Ja (vlak)|
|Status   |   |Ja   |
|Type watervlakte|aanduiding soort watervlakte|Nee|
|Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
||||

**Domeinwaarden**

|Waarde Status| Beschrijving   |
|---|---|
|gepland||
|bestaand||
|verwijderd||
|niet gerealiseerd||
|ten onrechte||

.

|Waarde Type watervlakte| Beschrijving   |
|---|---|---|
|zee|Uitgestrekt oppervlak zout water. |
|meer|*geen onderscheidende definitie gevonden*|
|plas|*geen onderscheidende definitie gevonden*|
|ven|*geen onderscheidende definitie gevonden*|
|vijver|*geen onderscheidende definitie gevonden*|


#### Waterloop
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Waterloop  |
| Onderdeel van NEN3610-objecttype |Water  |

ontwerpprincipe: 

**Definitie**

| Naam  | Waterloop  |
|---|---|
| Definitie | Een langgerekte verlaging in het terrein van natuurlijke of kunstmatige oorsprong die permanent of periodiek stromend water bevat.  |
|Herkomst definitie  | AQUO lex    |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier grotendeels de bestaande populatie *waterloop* en *greppel/droge sloot* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip waterloop |Ja |
|Geometrie|De geometrische representatie van de randen van een waterloop. *nader te preciseren op basis van generieke uitspraken over de vastlegging van geometrie*|Ja (vlak)|
|Status   |   |Ja   |
|Type waterloop|aanduiding soort waterloop|Nee|
|*watervoerend| aanduiding of de waterloop wel of geen water bevat | ja*|
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|

**Domeinwaarden**

|Waarde Status| Beschrijving   |
|---|---|
|gepland||
|bestaand||
|verwijderd||
|niet gerealiseerd||
|ten onrechte||

.

|Waarde Type waterloop| Beschrijving   |
|---|---|
|rivier|Het water, dat ten atmosferische neerslag op hellende terreinen valt, vloeit, voor zover het niet verdampt of door planten wordt opgenomen, tezamen tot een waterloop en stroomt naar laaggelegen streken. Zulk een natuurlijke afvloeiing heet een rivier.|
|sloot|Een waterloop van beperkte breedte die stilstaand of langzaam stromend water bevat , welke is aangelegd met als doel het beheersen van het waterpeil.|
|kanaal|Een gegraven grote waterloop die dient voor scheepvaart en/of watertransport.|
|beek|Een natuurlijke smalle waterloop zonder getij, die veelal doorwaadbaar is en afwatert op een rivier.|
|gracht|Een gracht is een gegraven greppel met water, die hoofdzakelijk voorkomt in oude steden.|


#### Bron
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Bron  |
| Onderdeel van NEN3610-objecttype |Water  |

ontwerpprincipe: 

**Definitie**

| Naam  | Bron  |
|---|---|
| Definitie | Grondwater dat op natuurlijke wijze uit het aardoppervlak tevoorschijn komt.|
|Herkomst definitie  | IMGeo 2.1.1   |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *waterloop; Type bron*  zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip bron |Ja |
|Geometrie|De geometrische representatie van de randen van een bron.  *nader te preciseren op basis van generieke uitspraken over de vastlegging van geometrie*|Ja (vlak)|
|Status   |   |Ja   |
|Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|hoort bij|watervlakte|ja|
|hoort bij|waterloop|ja|

**Domeinwaarden**

|Waarde Status| Beschrijving   |
|---|---|
|gepland||
|bestaand||
|verwijderd||
|niet gerealiseerd||
|ten onrechte||

#### Getijdengebied
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Getijdengebied  |
| Onderdeel van NEN3610-objecttype |Water  |

ontwerpprincipe: 

**Definitie**

| Naam  | Getijdengebied  |
|---|---|
| Definitie | Geheel of gedeeltelijk droogvallende gronden, buitendijks gelegen.  |
|Herkomst definitie  | Basisregistratie Topografie: Catalogus en Productspecificaties (versie 1.2.0.1)   |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *ondersteunend waterdeel; Type slik* en *begroeide terreindelen; Type kwelder* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip getijdengebied |Ja |
|Geometrie|De geometrische representatie van de randen van een getijdengebied. *nader te preciseren op basis van generieke uitspraken over de vastlegging van geometrie*|Ja (vlak)|
|Status   |   |Ja   |
|Type getijdengebied|aanduiding soort getijdengebied|Nee|
| Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |


**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|


**Domeinwaarden**

|Waarde Status| Beschrijving   |
|---|---|
|gepland||
|bestaand||
|verwijderd||
|niet gerealiseerd||
|ten onrechte||

.

|Waarde Type getijdengebied| Beschrijving   |
|---|---|
|slik|Buitendijks aangeslibde, onbegroeide grond die bij vrijwel elk hoogwater onderloopt. |
|schor|Buitendijks aangeslibd land, dat bij gewone vloed niet meer onderloopt en doorgaans begroeid is. |
|*kwelder|synoniem van schor? en komt ook terug als functioneel object?*||


### Begroeiing

#### Loofbos
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Loofbos  |
| Onderdeel van NEN3610-objecttype | Begroeiing |

**Definitie**

| Naam  | Loofbos |
|---|---|
| Definitie |Terreindeel begroeid met een dusdanige aantal loofbomen dat deze een min of meer gesloten geheel vormen of, na volgroeiing van de bomen, zullen vormen.  |
| Herkomst definitie  | BGT  |
| Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie fysiek voorkomen loofbos van *begroeid terreindeel* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
| Toelichting| |

#####    Griend en hakhout  
| Klasse  | Naam  |
|---|---|
| SOR-begrip   |    Griend en hakhout    |
| Onderdeel van NEN3610-objecttype |Begroeiing  |


**Definitie**

| Naam  |   Griend en hakhout   |
|---|---|
| Definitie |Terreindeel met opgaande begroeiing van loofbomen, in een dicht groeiverband, en die periodiek wordt ingekort.   |   
|Herkomst definitie  | IMGEO 2.0  |
|Verplicht  | Nee  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie fysiek voorkomen *griend en hakhout* bij *begroeid terreindeel* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting| | 

 
####    Gemengd bos
| Klasse  | Naam  |
|---|---|
| SOR-begrip   |    Gemengd bos  |
| Onderdeel van NEN3610-objecttype | Begroeiing  |


**Definitie**

| Naam  |    Gemengd bos |
|---|---|
| Definitie |Terreindeel begroeid met een dusdanig aantal naald- en loofbomen dat deze een min of meer gesloten geheel vormen of, na volgroeiing van de bomen, zullen vormen.  |   
|Herkomst definitie  | BGT  |
|Verplicht  | ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie fysiek voorkomen *gemengd bos* bij *begroeid terreindeel* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting| | 

#### Naaldbos
| Klasse  | Naam  |
|---|---|
|SOR-begrip   | Naaldbos  |
| Onderdeel van NEN3610-objecttype |Begroeiing  |


**Definitie**

| Naam  | Naaldbos |
|---|---|
| Definitie |Terreindeel begroeid met een dusdanige aantal naaldbomen dat deze een min of meer gesloten geheel vormen of, na volgroeiing van de bomen, zullen vormen. | 
|Herkomst definitie  | BGT  |
|Verplicht  | ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie fysiek voorkomen *naaldbos* bij *begroeid terreindeel* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting| | 



####    Gras- en kruidachtigen
| Klasse  | Naam  |
|---|---|
|SOR-begrip   |    Gras- en kruidachtigen  |
| Onderdeel van NEN3610-objecttype |Begroeiing  |


**Definitie**

| Naam  |    Gras- en kruidachtigen |
|---|---|
| Definitie |(Grond met) een laagblijvende, aaneengesloten gras- en/of kruidachtige vegetatie.     
|Herkomst definitie  | CROW |
|Verplicht  | ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie fysiek voorkomen *gras- en kruidachtigen* bij *begroeid terreindeel* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting| | 


####  Struiken
| Klasse  | Naam  |
|---|---|
|SOR-begrip   | Struiken  |
| Onderdeel van NEN3610-objecttype |Begroeiing  |


**Definitie**

| Naam  | Struiken |
|---|---|
| Definitie |Terreindeel bedekt met lage, houtachtige, overblijvende planten gekenmerkt door verschillende vertakkingen dicht bij de wortel en eventueel aanwezigheid van enkele verspreid staande stammen.   |    |
|Herkomst definitie  |   |
|Verplicht  | ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie fysiek voorkomen *struiken* bij *begroeid terreindeel* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting| | 


##### Heesters 
| Klasse  | Naam  |
|---|---|
|SOR-begrip   | Heesters   |
| Onderdeel van NEN3610-objecttype |Begroeiing  |


**Definitie**

| Naam  | Heesters  |
|---|---|
| Definitie |Beplanting van houtige gewassen die struikvormend zijn en die al dan niet een  gesloten geheel vormen. Het accent ligt op de sierwaarde, de beplanting kan uit één soort of uit meerdere soorten bestaan. Onder de heesters kan een houtachtige of kruidachtige onderbegroeiing aanwezig zijn. Het oppervlak met struikachtige gewassen is meer dan 50% van de totale oppervlakte van het vak.  | 
|Herkomst definitie  |   |
|Verplicht  | Nee  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie fysiek voorkomen *heesters* bij *begroeid terreindeel* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting| | 


##### Bosplantsoen 
| Klasse  | Naam  |
|---|---|
|SOR-begrip   | Bosplantsoen   |
| Onderdeel van NEN3610-objecttype |Begroeiing  |


**Definitie**

| Naam  | Bosplantsoen  |
|---|---|
| Definitie |Opgaande beplanting van houtachtige gewassen die struikvormend en/of boomvormend zijn. De soorten zijn als bosplantsoen opgekweekt en aangeplant.De beplanting kan open of  gesloten zijn en bestaat vaak uit inheemse soorten. Onderscheidt zich van heesters omdat de sierkenmerken niet voorop staan.   |    
|Herkomst definitie  | CROW |
|Verplicht  | Nee  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie fysiek voorkomen *bosplantsoen* bij *begroeid terreindeel* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting| | 

##### Planten
| Klasse  | Naam  |
|---|---|
|SOR-begrip   | Planten  |
| Onderdeel van NEN3610-objecttype |Begroeiing  |


**Definitie**

| Naam  | Planten |
|---|---|
| Definitie |*niet ingevuld*  |    |
|Herkomst definitie  |   |
|Verplicht  | Nee  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie fysiek voorkomen *planten* bij *begroeid terreindeel* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting| | 


##### Struikrozen
| Klasse  | Naam  |
|---|---|
|SOR-begrip   | Struikrozen  |
| Onderdeel van NEN3610-objecttype |Begroeiing  |


**Definitie**

| Naam  | Struikrozen |
|---|---|
| Definitie |*niet ingevuld*  |    |
|Herkomst definitie  |   |
|Verplicht  | Nee  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie fysiek voorkomen *struikrozen* bij *begroeid terreindeel* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting| | 

##### Bodembedekkers
| Klasse  | Naam  |
|---|---|
|SOR-begrip   | Bodembedekkers  |
| Onderdeel van NEN3610-objecttype |Begroeiing  |


**Definitie**

| Naam  | Bodembedekkers |
|---|---|
| Definitie |*niet ingevuld*  |    |
|Herkomst definitie  |   |
|Verplicht  | Nee  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie fysiek voorkomen *bodembedekkers* bij *begroeid terreindeel* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting| |


#### Haag
| Klasse  | Naam  |
|---|---|
|SOR-begrip   | Haag |
| Onderdeel van NEN3610-objecttype |Begroeiing |


**Definitie**

| Naam  | Haag  |
|---|---|
| Definitie |Een rijvormige afscheiding van zeer beperkte breedte bestaande uit aangeplante aaneengesloten struiken.   |
|Herkomst definitie  | IMGeo   |
|Verplicht  | ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie fysiek voorkomen *haag* bij *vegetatie object* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting|  |


#### Bomenrij
| Klasse  | Naam  |
|---|---|
|SOR-begrip   | Bomenrij |
| Onderdeel van NEN3610-objecttype |Begroeiing |


**Definitie**

| Naam  | Bomenrij |
|---|---|
| Definitie |opgaande begroeiing van bomen zonder struiken  |
|Herkomst definitie  |   |
|Verplicht  | ja  |
|Gevolgen afbakening  | nieuw object  |
|Toelichting|  |

#### Houtsingel
| Klasse  | Naam  |
|---|---|
|SOR-begrip   | Houtsingel |
| Onderdeel van NEN3610-objecttype |Begroeiing |


**Definitie**

| Naam  | Houtsingel |
|---|---|
| Definitie |opgaande begroeiing van  bomen (enkelvoudige/meervoudige stammen) en struiken  |
|Herkomst definitie  |   |
|Verplicht  | ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie fysiek voorkomen *houtsingel* bij *begroeid terreindeel* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting|  |

#### Moeras
| Klasse  | Naam  |
|---|---|
|SOR-begrip   | Moeras |
| Onderdeel van NEN3610-objecttype |Begroeiing |


**Definitie**

| Naam  | Moeras |
|---|---|
| Definitie |Terreindeel met moerasvegetatie in stilstaand water van geringe diepte zonder merkbare toe- of afvloeiing.  |
|Herkomst definitie  | bron: BGT |
|Verplicht  | ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie fysiek voorkomen *moeras* bij *begroeid terreindeel* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting|  |

#### Heide
| Klasse  | Naam  |
|---|---|
|SOR-begrip   | Heide |
| Onderdeel van NEN3610-objecttype |Begroeiing |


**Definitie**

| Naam  | Heide |
|---|---|
| Definitie |Terreindeel overwegend begroeid met heide en heideachtige vegetaties.  |
|Herkomst definitie  |BGT|
|Gevolgen afbakening  | Het betreft hier de bestaande populatie fysiek voorkomen *heide* bij *begroeid terreindeel* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Verplicht  | ja  |
|Toelichting|  |

#### Rietland

| Klasse  | Naam  |
|---|---|
|SOR-begrip   | Rietland |
| Onderdeel van NEN3610-objecttype |Begroeiing |


**Definitie**

| Naam  | Rietland |
|---|---|
| Definitie |Terreindeel overwegend begroeid met rietvegetatie.  |
|Herkomst definitie  | BGT  |
|Verplicht  | ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie fysiek voorkomen *rietland* bij *begroeid terreindeel* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting|  |



#### Bouwland 
| Klasse  | Naam  |
|---|---|
|SOR-begrip   | Bouwland  |
| Onderdeel van NEN3610-objecttype |Begroeiing |


**Definitie**

| Naam  | Bouwland  |
|---|---|
| Definitie |Terreindeel in gebruik als akker, met gewassen die in een teelt roulatieschema zijn opgenomen. Kan tijdelijk zonder gewas zijn of braak liggen. |
|Herkomst definitie  | BGT  |
|Verplicht  | ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie fysiek voorkomen *bouwland* bij *begroeid terreindeel* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting|  |



####    fruit- bomenteelt

| Klasse  | Naam  |
|---|---|
|SOR-begrip   | fruit- bomenteelt |
| Onderdeel van NEN3610-objecttype |Begroeiing |


**Definitie**

| Naam  | fruit- bomenteelt |
|---|---|
| Definitie |Terreindeel begroeid met fruitbomen in de vorm van hoogstam en laagstamboomgaard, druiven of kleinfruit. en Grond in gebruik voor het kweken van jonge siergewassen, bomen enz. ten behoeve van een later gebruik elders.   |
|Herkomst definitie  | BT / CROW  |
|Verplicht  | ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie fysiek voorkomen *fruitteelt* bij *begroeid terreindeel* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting|  |

#####    laagstam boomgaarden 

| Klasse  | Naam  |
|---|---|
|SOR-begrip   |    laagstam boomgaarden  |
| Onderdeel van NEN3610-objecttype |Begroeiing |


**Definitie**

| Naam  |    laagstam boomgaarden  |
|---|---|
| Definitie |Terreindeel begroeid met laagstamfruitbomen.   |
|Herkomst definitie  | IMGEO 2.0  |
|Verplicht  | nee  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie fysiek voorkomen *laagstam boomgaarden* bij *begroeid terreindeel* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting|  |

#####    hoogstam boomgaarden

| Klasse  | Naam  |
|---|---|
|SOR-begrip   |    hoogstam boomgaarden |
| Onderdeel van NEN3610-objecttype |Begroeiing |


**Definitie**

| Naam  |    hoogstam boomgaarden |
|---|---|
| Definitie |Terreindeel begroeid met hoogstamfruitbomen.   |
|Herkomst definitie  | IMGEO 2.0   |
|Verplicht  | nee  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie fysiek voorkomen *hoogstam boomgaarden* bij *begroeid terreindeel* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting|  |

##### wijngaarden  

| Klasse  | Naam  |
|---|---|
|SOR-begrip   | wijngaarden   |
| Onderdeel van NEN3610-objecttype |Begroeiing |


**Definitie**

| Naam  | wijngaarden   |
|---|---|
| Definitie |Terreindeel begroeid met druivenstokken voor wijnbouw.  |
|Herkomst definitie  |IMGEO 2.0    |
|Verplicht  | nee  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie fysiek voorkomen *wijngaarden* bij *begroeid terreindeel* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting|  |

#####    klein fruit

| Klasse  | Naam  |
|---|---|
|SOR-begrip   |    klein fruit |
| Onderdeel van NEN3610-objecttype |Begroeiing |


**Definitie**

| Naam  |    klein fruit |
|---|---|
| Definitie |Terreindeel begroeid met heesters voor zachtfruit zoals bessen of frambozen.   |
|Herkomst definitie  | IMGEO 2.0   |
|Verplicht  | nee  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie fysiek voorkomen *klein fruit* bij *begroeid terreindeel* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting|  |

##### boomkwekerij 

| Klasse  | Naam  |
|---|---|
|SOR-begrip   | boomkwekerij  |
| Onderdeel van NEN3610-objecttype |Begroeiing |


**Definitie**

| Naam  | boomkwekerij  |
|---|---|
| Definitie |Terrein, overwegend in gebruik t.b.v. het opkweken van bomen (inclusief coniferen en sparren) en struiken, waarbij de hoogte van de aanplant niet van belang is.  |
|Herkomst definitie  |   |
|Verplicht  | nee  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie fysiek voorkomen *boomteelt* bij *begroeid terreindeel* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting|  |




### Constructie; Gebouw

#### Gebouw

| Klasse  | Naam  |
|---|---|
|SOR-begrip   | Gebouw  |
| Onderdeel van NEN3610-objecttype |Gebouw  |

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
|Aard|De fysieke verschijningsvorm van een gebouw *nader te bepalen of  deze Typering ook een antwoord geeft op de vraag in welke hoogteKlasse een gebouw is gelegen, welke soortNaam het betreft en van welk fysiek voorkomen sprake is*   |Ja|
|Oorspronkelijk bouwjaar | De aanduiding van het jaar waarin een gebouw oorspronkelijk als bouwkundig gereed is of zal worden opgeleverd|Ja|
|Naam| Een breed geaccepteerde benaming van een gebouw zoals deze door de eigenaar is toegekend of zoals deze in de volksmond bekend staat| Nee|
|Toegangsdeur| NTB ||
|Aantal bouwlagen | NTB||
|Status   |De fase van de levenscyclus waarin het gebouw zich bevindt    |Ja   |
| Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
||||

**Domeinwaarden**

| Waarde Typering| Beschrijving   |
|---|---|
| Woning| |
| Bedrijf ||
| ... |*aanvullingen BRT en Bgt??* |

.

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


| Klasse  | Naam  |
|---|---|
|SOR-begrip   | Bouwlaag  |
| Onderdeel van NEN3610-objecttype |Gebouw  |

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
| Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|Ligt in|Gebouw| Ja|

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


| Klasse  | Naam  |
|---|---|
|SOR-begrip   | Ruimte  |
| Onderdeel van NEN3610-objecttype |Gebouw  |

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
|Geometrie |De geometrische representatie van de randen van een Ruimte *nader te preciseren op basis van generieke uitspraken over de vastlegging van geometrie*  |Ja|
|Typering|Het doel waarvoor een ruimte gebruikt wordt|Ja|
|Bouwlaagnummer |De bouwlaag waarop de ruimte zich bevindt|Ja|
|Oppervlakte| NTB||
|Status   |De fase van de levenscyclus waarin een Ruimte zich bevindt   |Ja   |
| Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|Ligt op|Bouwlaag| Ja|

**Domeinwaarden**

| Waarde Typering| Beschrijving   |
|---|---|
|Woonkamer| |
|Keuken ||
| ... |*lijst vanuit BIM checken* |

.

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



| Klasse  | Naam  |
|---|---|
|SOR-begrip   | Installatie  |
| Onderdeel van NEN3610-objecttype |Gebouw  |

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
| Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|Hoort bij|Verblijfsobject|Ja|
|Hoort bij|Gebouw|Ja|

**Domeinwaarden**

| Waarde Aard| Beschrijving   |
|---|---|
|zonnepanelen < 5 kWp| |
|zonnepanelen > 5 kWp| |
|dakkapel ||
|lift||
| ... |*lijst vanuit elders checken* |

.

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


| Klasse  | Naam  |
|---|---|
|SOR-begrip   | Toegangsdeur  |
| Onderdeel van NEN3610-objecttype |Gebouw  |

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
|Type|het soort toegangsdeur|Ja|
|Bijbehorend object |Het object waarin de betreffende toegangsdeur zich bevindt|Ja|
|Status   |De fase van de levenscyclus waarin de betreffende Toegangsdeur zich bevindt   |Ja   |
| Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|Hoort bij|Verblijfsobject| Ja|
|Hoort bij|Gebouw| Ja|

**Domeinwaarden**

| Waarde Aard| Beschrijving   |
|---|---|
|directe toegang vanaf eigen terrein| |
|directe toegang vanaf openbare weg| |
|toegang vanaf gemeenschappelijke verkeersruimte ||

.

| Waarde Type| Beschrijving   |
|---|---|
|Personen| |
|Auto| |
|Vracht||

.

| Waarde Status | Beschrijving   |
|---|---|
|Gepland||
|Bestaand||
|Verwijderd|
|Niet gerealiseerd||
|Ten onrechte||




### *Bouwwerkconstructie*
| Klasse  | Naam  |
|---|---|
|SOR-begrip   | constructie  |
| Onderdeel van NEN3610-objecttype | constructie  |

De Typering behorende bij Constructie is overgenomen uit de huidige BGT|IMGeo 2.1.1 en aangevuld met de objecttyperingen zoals in het voorstel voor IMGeo 2.2 zijn opgenomen.

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

| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Verharding  |
| Onderdeel van NEN3610-objecttype |Verharding |

ontwerpprincipe: 

**Definitie**

| Naam  | Verharding |
|---|---|
| Definitie |Een door egaliseren, verstevigen en/of verruwen voor het beoogde gebruik geschikt gemaakt oppervlak, bestaande uit in één of meer lagen over een ondergrond of onderliggende constructie aangelegd materiaal. |
|Herkomst definitie  | concept NEN3610-2020  |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier grotendeels de bestaande populatie fysieke voorkomen van *wegdelen*, *ondersteunende wegdelen* en *onbegroeide terreindelen* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting| *volgt later*  Een verhardingsvlak bestaat uit één Type verharding. Het gaat hierbij over het Type verharding waarmee het vlak overwegend is bedekt. Voor minimale stukjes, 5m2, met andere verharding hoeft geen apart vlak te worden gevormd.|

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip verharding |Ja |
|Geometrie|De geometrische representatie van de randen van een verhardingsvlak. *nader te preciseren op basis van generieke uitspraken over de vastlegging van geometrie*|Ja (vlak)|
|Status   |   |Ja   |
|Type verharding|aanduiding soort verharding|Ja|
|Type verharding plus|aanduiding soort verharding|Nee|
| Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
| | | |

**Domeinwaarden**

|Waarde Status| Beschrijving   |
|---|---|
|gepland||
|bestaand||
|verwijderd||
|niet gerealiseerd||
|ten onrechte||

.

|Waarde Type verharding| Beschrijving   |
|---|---|
|asfaltverharding|Gesloten verharding bestaande uit asfaltbeton of andere met bitumen gebonden materialen.|
| betonverharding |Gesloten verharding bestaande uit gewapend of ongewapend beton. |
|elementenverharding|Open verharding opgebouwd uit losse elementen die in meer of mindere mate met elkaar verbonden zijn.|
|halfverharding|Open verharding bestaande uit onsamenhangend materiaal dat meer draagkracht levert dan de originele grond.|
|kunststofverharding|Synthetisch vervaardigd materiaal dat als verharding dient.|

.

|Waarde Type verharding plus| Beschrijving   |
|---|---|---|
|**asfaltverharding**||
|   Zoab en open deklagen|*geen definitie opgenomen in IMBOR*|
|   Oppervlakbehandelingen|Verharding bestaand uit op het wegoppervlak aangebrachte laag bindmiddel die wordt afgestrooid met steenslag of fijn grind.|
|   Dichte deklagen|*geen definitie opgenomen in IMBOR*|
|**betonverharding**||
|   Ongewapend verdeuveld beton|Ongewapend verdeuveld beton is de formele benaming. In de CROW Systematiek Wegbeheer wordt dit ‘verdeuveld’ genoemd.|
| 	Gewapend beton|*geen definitie opgenomen in IMBOR*|
| 	Oppervlakbehandelingen|Verharding bestaand uit op het wegoppervlak aangebrachte laag bindmiddel die wordt afgestrooid met steenslag of fijn grind.|
| 	Ongewapend nietverdeuveld beton|Ongewapend nietverdeuveld beton is de formele benaming. In de CROW Systematiek Wegbeheer wordt dit ‘onverdeuveld’ genoemd.|
|**elementenverharding**||
|   Natuursteen|Verharding bestaande uit elementen van natuursteen.|
| 	Straatbaksteen|Straatbaksteen is de formele benaming uit NEN-EN1344. In de CROW Systematiek Wegbeheer wordt dit ‘gebakken klinkers’ genoemd.|
| 	Glas|Verharding bestaande uit glaselementen.|
| 	Betonstraatstenen|Verharding gemaakt van betonstraatstenen. Straatsteen die als goedkope vervanging van de gebakken klinkers is ontwikkeld.|
| 	Tegels|Verharding bestaande uit tegels, een platte vaak vierkante betonnen steen.|
| 	Hout|Verharding bestaande uit houten elementen.|
| 	Betonelement|Geprepareerde elementen van beton (bijvoorbeeld stelconplaten).|
| 	Metaal|Verharding bestaande uit metalen elementen.|
| 	Sierbestrating|Bestrating uitgevoerd in verschillende bestratingsverbanden en -materialen, of in een sierverband, die vooral wordt toegepast uit esthetische overwegingen.|
|**Halfverharding**||
|   Samenhangend|Verharding waarvan het oppervlak bestaat uit samenhangend materiaal.|
| 	Los|Verhardingsvlak gevuld met losgestort materiaal|
|**Kunststofverharding**||
|	Kunststof vloer|*geen definitie opgenomen in IMBOR*|
|   Kunstgras|Een als gras aanziend of aandoend, kunstmatig product van uiteenlopend, synthetisch materiaal.|


### Constructie; Kunstwerk
#### Overbrugging

| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Overbrugging |
| Onderdeel van NEN3610-objecttype | Kunstwerk  |

ontwerpprincipe: 

**Definitie**

| Naam  | Overbrugging  |
|---|---|
| Definitie | Een beweegbare of vaste verbinding tussen twee punten, die door water, een weg of anderszins  gescheiden zijn,  bestaande uit een brugdek/-bak met landhoofden en veelal gesteund door pijlers. |
|Herkomst definitie  |  |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier grotendeels de bestaande populatie  *overbruggingsdelen; hoort bij Type overbrugging* zoals deze is opgenomen in het IMGeo deel van de basisregistratie grootschalige topografie. |
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip overbrugging |Ja |
|Geometrie|De geometrische representatie van de randen van een overbrugging.  *nader te preciseren op basis van generieke uitspraken over de vastlegging van geometrie*|Ja|
|Status   |   |Ja   |
|Type overbrugging|aanduiding soort overbrugging|Nee|
|*Beweegbaar*|*aanduiding of overbrugging beweegbaar is (open en dicht kan)*|*Ja*|
| Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|


**Domeinwaarden**

|Waarde Status| Beschrijving   |
|---|---|
|gepland||
|bestaand||
|verwijderd||
|niet gerealiseerd||
|ten onrechte||

.

|Waarde Type overbrugging| Beschrijving   |
|---|---|
| brug |Overbruggingsconstructie over een watervlakte of waterloop, bedoelt voor verkeer.|
| aquaduct |Overbruggingsconstructie waarmee een watergang door een bakvormige constructie over een weg, een spoorweg, een andere watergang, een leiding of een terrein wordt geleid.   |
| viaduct |Overbruggingsconstructie over een weg, spoorweg of terreinverdieping, bedoelt voor verkeer.   |
| ecoduct |Overbruggingsconstructie over een weg of spoorweg,  bedoelt voor het passeren van dieren.   |
| flyover|Kunstwerk in de vorm van een viaduct dat deel uitmaakt van een verkeersbaan en waarmee een verkeersstroom over twee of meer ongelijkvloerse verkeersstromen wordt geleid.*bestaande definitie niet consistent*   |
| overkluizing |Een civieltechnisch kunstwerk waarmee een weg, een plein of een waterloop (kruiselings) wordt overwelft, waarbij het dek meestal niet uitsluitend uit een pad of weg bestaat.   |

#### Ondertunneling

| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Ondertunneling |
| Onderdeel van NEN3610-objecttype | Kunstwerk  |

ontwerpprincipe: 

**Definitie**

| Naam  | Ondertunneling  |
|---|---|
| Definitie |  |
|Herkomst definitie  |  |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier grotendeels de bestaande populatie  *tunneldelen* zoals deze is opgenomen in de basisregistratie grootschalige topografie. En van *kunstwerkdelen van Type duiker* indien opgenomen in het IMGeo deel van de basisregistratie grootschalige topografie. |
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip ondertunneling|Ja |
|Geometrie|De geometrische representatie van de randen van een ondertunneling.  *nader te preciseren op basis van generieke uitspraken over de vastlegging van geometrie*|Ja|
|Status   |   |Ja   |
|Type ondertunneling|aanduiding soort ondertunneling|Nee|
| Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|

**Domeinwaarden**

|Waarde Status| Beschrijving   |
|---|---|
|gepland||
|bestaand||
|verwijderd||
|niet gerealiseerd||
|ten onrechte||

.

|Waarde Type ondertunneling| Beschrijving   |
|---|---|
| tunnel |Kokervormig kunstwerk onder een of meer wegen, spoorwegen, waterwegen en/of andere hindernissen, als ondergrondse doorgang voor verkeer, leidingen of dieren.   |
| duiker |Kunstwerk voor de waterhuishouding, bestaande uit een gesloten kokervormige constructie met een in- en uitstroomopening, die niet de gehele waterbreedte beslaand, aangebracht onder een weg of spoorweg of in een dam of ander terreindeel en de bodem van de waterloop onderbreekt.   |

#### Gemaal

| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Gemaal |
| Onderdeel van NEN3610-objecttype | Kunstwerk  |

ontwerpprincipe: 

**Definitie**

| Naam  | Gemaal  |
|---|---|
| Definitie | Een kunstwerk in principe bedoeld om water van een laag peil naar een hoog peil te brengen.  |
|Herkomst definitie  |  |
|Verplicht  | Nee  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie  *kunstwerkdelen Type gemaal* zoals deze is opgenomen in de basisregistratie grootschalige topografie. |
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
|stormvloedkering|*is toch een functie en geen kunstwerk?*||


#### Overbruggingsdeel
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Overbruggingsdeel |
| Onderdeel van NEN3610-objecttype |Kunstwerk  |

ontwerpprincipe: 

**Definitie**

| Naam  |Overbruggingsdeel  |
|---|---|
| Definitie |  Onderdeel van een civiel-technisch werk voor de infrastructuur van wegen, water, spoorbanen, waterkeringen en/of leidingen. |
|Herkomst definitie  |  BGT 1.1.1  |
|Verplicht  | nee  |
|Gevolgen afbakening  | Het betreft hier grotendeels de bestaande populatie  *overbruggingsdelen, Type overbruggingsdeel* zoals deze is opgenomen in het IMGeo deel van de basisregistratie grootschalige topografie. |
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip overbruggingsdeel |Ja |
|Geometrie|De geometrische representatie van de randen van een overbruggingsdeel. *nader te preciseren op basis van generieke uitspraken over de vastlegging van geometrie*|Ja|
|Status   |   |Ja   |
|Type overbruggingsdeel|aanduiding soort overbruggingsdeel|nee|
| Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
| hoort bij | kunstwerk, type overbrugging | ja|

**Domeinwaarden**

|Waarde Status| Beschrijving   |
|---|---|
|gepland||
|bestaand||
|verwijderd||
|niet gerealiseerd||
|ten onrechte||

.

|Waarde Type kunstwerkdeel| Beschrijving   |
|---|---|
| dek |Direct door het verkeer belaste deel van de bovenbouw van de brug.   |
| landhoofd |Ondersteuningsconstructie ter plaatse van een overgang van de aardebaan naar een kunstwerk.   |
| pijler |Ondersteuningsconstructie van bruggen en soortgelijke kunstwerken.   |
| sloof |Deel van de pijler voor de overdracht van krachten naar de ondergrond of de fundering.   |
| pyloon |Boven de bovenbouw uitstekende draagconstructie voor tuien (kabels).   |


#### Sluisdeel
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Sluisdeel |
| Onderdeel van NEN3610-objecttype |Kunstwerk  |

ontwerpprincipe: 

**Definitie**

| Naam  | Sluisdeel |
|---|---|
| Definitie |  Onderdeel van een civiel-technisch werk voor de infrastructuur van wegen, water, spoorbanen, waterkeringen en/of leidingen. |
|Herkomst definitie  |  BGT 1.1.1  |
|Verplicht  | nee  |
|Gevolgen afbakening  | Het betreft hier grotendeels de bestaande populatie  *?* zoals deze is opgenomen in het IMGeo deel van de basisregistratie grootschalige topografie. |
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip sluisdeel |Ja |
|Geometrie|De geometrische representatie van de randen van een sluisdeel.  *nader te preciseren op basis van generieke uitspraken over de vastlegging van geometrie*|Ja|
|Status   |   |Ja   |
|Type Sluisdeel|aanduiding soort sluisdeel|nee|
| Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
| hoort bij | kunstwerk, type sluis | ja|

**Domeinwaarden**

|Waarde Status| Beschrijving   |
|---|---|
|gepland||
|bestaand||
|verwijderd||
|niet gerealiseerd||
|ten onrechte||

.

|Waarde Type kunstwerkdeel| Beschrijving   |
|---|---|
| sluisdeur ||
| kolk ||

### Constructie; Overige

#### Muur
  
| Klasse  | Naam  |
|---|---|
|SOR-begrip   | Muur |
| Onderdeel van NEN3610-objecttype | Constructie |

ontwerpprincipe: 


**Definitie**

| Naam  | Muur |
|---|---|
| Definitie |Relatief smal, rechtopstaand bouwwerk.|
|Herkomst definitie  |Basisregistratie Topografie: Catalogus en Productspecificaties (versie 1.2.0.1)|
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier grotendeels de bestaande populatie  *scheidingen, Type muur* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting| *volgt later*  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip muur|Ja |
|Geometrie|De geometrische representatie van een muur. *nader te preciseren op basis van generieke uitspraken over de vastlegging van geometrie*|Ja (lijn) Nee (vlak)|
|Afbakening   |  | |
|Status   |   |Ja   |
| Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|


**Domeinwaarden**

|Waarde Status| Beschrijving   |
|---|---|
|gepland||
|bestaand||
|verwijderd||
|niet gerealiseerd||
|ten onrechte||

#### Hek
  
| Klasse  | Naam  |
|---|---|
|SOR-begrip   | Hek |
| Onderdeel van NEN3610-objecttype | Constructie |

ontwerpprincipe: 


**Definitie**

| Naam  | Hek |
|---|---|
| Definitie | Een hekwerk of schutting om een gebied af te scheiden of de toegang te beheren.|
|Herkomst definitie  |nieuw|
|Verplicht  | *staat ter discussie* |
|Gevolgen afbakening  | Het betreft hier grotendeels de bestaande populatie  *scheidingen, Type hek* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting| *volgt later*  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip hek|Ja |
|Geometrie|De geometrische representatie van een hek. *nader te preciseren op basis van generieke uitspraken over de vastlegging van geometrie*|Ja (lijn)|
|Afbakening   |  | |
|Status   |   |Ja   |
| Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|


**Domeinwaarden**

|Waarde Status| Beschrijving   |
|---|---|
|gepland||
|bestaand||
|verwijderd||
|niet gerealiseerd||
|ten onrechte||

#### Raster
  
| Klasse  | Naam  |
|---|---|
|SOR-begrip   | Raster |
| Onderdeel van NEN3610-objecttype | Constructie |

ontwerpprincipe: 


**Definitie**

| Naam  | Raster |
|---|---|
| Definitie |Kunstmatige terreinafscheiding, in de vorm van een overwegend houten, metalen of kunststoffen rechtopstaande palen met daartussen gaas of één of meerdere draden.|
|Herkomst definitie  |Gegevenscatalogus IMGeo 2.1.1 *deels aangepast*|
|Verplicht  | nee  |
|Gevolgen afbakening  | Het betreft hier grotendeels de bestaande populatie  *scheidingen, Type draadraster, faunaraster* zoals deze is opgenomen in het IMGeo deel van de basisregistratie grootschalige topografie.  |
|Toelichting| *volgt later*  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip raster|Ja |
|Geometrie|De geometrische representatie van een raster. *nader te preciseren op basis van generieke uitspraken over de vastlegging van geometrie*|Ja (lijn)|
|Afbakening   |  | |
|Status   |   |Ja   |
| Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|


**Domeinwaarden**

|Waarde Status| Beschrijving   |
|---|---|
|gepland||
|bestaand||
|verwijderd||
|niet gerealiseerd||
|ten onrechte||

#### Scherm
  
| Klasse  | Naam  |
|---|---|
|SOR-begrip   | Scherm |
| Onderdeel van NEN3610-objecttype | Constructie |

ontwerpprincipe: 


**Definitie**

| Naam  | Scherm |
|---|---|
| Definitie |Een lineaire constructie, typisch bedoeld om te reduceren. |
|Herkomst definitie  |nieuw|
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier grotendeels de bestaande populatie  *scheidingen, Type geluidscherm* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting| *volgt later*  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip scherm|Ja |
|Geometrie|De geometrische representatie van een scherm.  *nader te preciseren op basis van generieke uitspraken over de vastlegging van geometrie*|Ja (lijn)|
|Afbakening   |  | |
|Status   |   |Ja   |
| Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|


**Domeinwaarden**

|Waarde Status| Beschrijving   |
|---|---|
|gepland||
|bestaand||
|verwijderd||
|niet gerealiseerd||
|ten onrechte||



