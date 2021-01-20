## Reele objecten

<div class='note'>
    De typering is in deze fase van het traject vooral bedoeld om een eerste indruk te geven van de richting waarin de inhoud van de samenhangende objectenregistratie zich beweegt. Typeringen kunnen nog wijzigen in het nog op te stellen informatiemodel van de samenhangende objectenregistratie.
</div>

 

### Water



#### Watervlakte

Dit SOR-begrip maakt onderdeel uit van de NEN 3610-hoofdklasse "Water"
 

**Definitie**

| Naam  | Watervlakte  |
|---|---|
| Definitie | Een verlaging in het aardoppervlak van natuurlijke of kunstmatige oorsprong, die permanent of periodiek water bevat|
|Herkomst definitie  | AQUO lex    |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *watervlakte* en *zee* zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een watervlakte|Ja |
|Geometrie|De geometrische representatie van de randen van een watervlakte|Ja (vlak)|
|Status   | De fase van de levenscyclus waarin de watervlakte zich bevindt|Ja   |
|Type watervlakte|De aanduiding van het soort watervlakte|Nee|



**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|gepland|
|bestaand|
|verwijderd|
|niet gerealiseerd|
|Ten onrechte|

*type watervlakte*

|Waarde Type watervlakte| Beschrijving   |
|---|---|
|zee|Uitgestrekt oppervlak zout water|
|meer|Watervlakte (meestal zoet) die op natuurlijke wijze dan wel door menselijk ingrijpen (ingraving of afsluiting) is ontstaan|
|plas|Waterpartij, ontstaan door de winning van delfstoffen in dagbouw, die in contact staat met de vrije grondwaterspiegel|
|ven|Een natuurlijk ontstaan meer op heidegrond|
|vijver|Gegraven waterpartij, aangelegd in stedelijke omgeving of in een parklandschap|





#### Waterloop

Dit SOR-begrip maakt onderdeel uit van de NEN 3610-hoofdklasse "Water"

 

**Definitie**

| Naam  | Waterloop  |
|---|---|
| Definitie | Een langgerekte verlaging in het terrein van natuurlijke of kunstmatige oorsprong die permanent of periodiek stromend water bevat|
|Herkomst definitie  | AQUO lex    |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier grotendeels de bestaande populatie *waterloop* en *greppel/droge sloot* zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een waterloop|Ja |
|Geometrie|De geometrische representatie van de randen van een waterloop|Ja (vlak)|
|Status   |  De fase van de levenscyclus waarin de waterloop zich bevindt|Ja   |
|Type waterloop|De aanduiding van het soort waterloop|Nee|
|Watervoerend | De aanduiding of de waterloop wel of geen water bevat| Ja|


**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|gepland|
|bestaand|
|verwijderd|
|niet gerealiseerd|
|Ten onrechte|

*type waterloop*

|Waarde Type waterloop| Beschrijving   |
|---|---|
|rivier|Het water, dat ten atmosferische neerslag op hellende terreinen valt, vloeit, voor zover het niet verdampt of door planten wordt opgenomen, tezamen tot een waterloop en stroomt naar laaggelegen streken. Zulk een natuurlijke afvloeiing heet een rivier|
|sloot|Een waterloop van beperkte breedte die stilstaand of langzaam stromend water bevat , welke is aangelegd met als doel het beheersen van het waterpeil|
|kanaal|Een gegraven grote waterloop die dient voor scheepvaart en/of watertransport|
|beek|Een natuurlijke smalle waterloop zonder getij, die veelal doorwaadbaar is en afwatert op een rivier|
|gracht|Een gracht is een gegraven greppel met water, die hoofdzakelijk voorkomt in oude steden|


#### Bron

Dit SOR-begrip maakt onderdeel uit van de NEN 3610-hoofdklasse "Water"

 

**Definitie**

| Naam  | Bron  |
|---|---|
| Definitie | Grondwater dat op natuurlijke wijze uit het aardoppervlak tevoorschijn komt|
|Herkomst definitie  | IMGeo 2.2   |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *waterloop; Type bron*  zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een bron|Ja |
|Geometrie|De geometrische representatie van de randen van een bron|Ja (vlak)|
|Status   | De fase van de levenscyclus waarin de bron zich bevindt|Ja   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|hoort bij|watervlakte|ja|
|hoort bij|waterloop|ja|

**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|gepland|
|bestaand|
|verwijderd|
|niet gerealiseerd|
|Ten onrechte|

#### Getijdengebied

Dit SOR-begrip maakt onderdeel uit van de NEN 3610-hoofdklasse "Water"

 

**Definitie**

| Naam  | Getijdengebied  |
|---|---|
| Definitie | Geheel of gedeeltelijk droogvallende gronden die buitendijks gelegen zijn|
|Herkomst definitie  | Basisregistratie Topografie: Catalogus en Productspecificaties (versie 1.2.0.1)   |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *ondersteunend waterdeel; Type slik* en *begroeide terreindelen; Type kwelder* zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een getijdengebied|Ja |
|Geometrie|De geometrische representatie van de randen van een getijdengebied|Ja (vlak)|
|Status   | De fase van de levenscyclus waarin het getijdengebied zich bevindt|Ja   |
|Type getijdengebied|De aanduiding van het soort getijdengebied|Nee|


**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|gepland|
|bestaand|
|verwijderd|
|niet gerealiseerd|
|Ten onrechte|

.

|Waarde Type getijdengebied| Beschrijving   |
|---|---|
|slik|Buitendijks aangeslibde, onbegroeide grond die bij vrijwel elk hoogwater onderloopt|
|schor|Buitendijks aangeslibd land, dat bij gewone vloed niet meer onderloopt en doorgaans begroeid is|


### Bodem


#### Onbegroeide grond

Dit SOR-begrip maakt onderdeel uit van de NEN 3610-hoofdklasse "Bodem"


**Definitie**

| Naam  | Onbegroeide grond |
|---|---|
| Definitie |bodem die het bovenste deel van het natuurlijke aardoppervlak betreft|
| Herkomst definitie  | Gebaseerd op definitie van bodem in concept NEN3610 2020|
| Verplicht  | Ja  |
| Gevolgen afbakening  | Het betreft hier ten opzichte van de bestaande basisregistraties een nieuw objecttype, grotendeels het bestaande fysieke voorkomen  type *onverhard* van wegen en terreinen in de basisregistratie grootschalige topografie|
| Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van onbegroeide grond|Ja |
|Geometrie| De geometrische representatie van de randen van onbegroeide grond|Ja (vlak)|
|Status   | De fase van de levenscyclus waarin het betreffende stuk onbegroeide grond zich bevindt|Ja   |


**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland|	
|Bestaand|	
|Verwijderd|
|Niet gerealiseerd|
|Ten onrechte|



### Onbepaald terreindeel

Dit SOR-begrip maakt onderdeel uit van de NEN 3610-hoofdklasse "Bodem"

 

**Definitie**

| Naam  | Onbepaald terreindeel  |
|---|---|
| Definitie | Bodem die fysiek begrensd en zichtbaar is en bij een gebouw hoort, dat niet nader wordt ingewonnen en dat bestaat uit een mengvorm van begroeiing, verharding en/of water|
|Herkomst definitie  | Gebaseerd op definitie van erf in BGT    |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *Erf* zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting| In plaats van onbepaald terreindeel kan ter plaatse ook de Reële topografie worden ingewonnen (vrijwillig)|

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een onbepaald terreindeel|Ja |
|Geometrie|De geometrische representatie van de randen van een onbepaald terreindeel|Ja (vlak)|
|Status   |De fase van de levenscyclus waarin het betreffende onbepaalde terreindeel zich bevindt|Ja   |



**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland|	
|Bestaand|	
|Verwijderd|
|Niet gerealiseerd|
|Ten onrechte|



### Begroeiing



#### Bos

Dit SOR-begrip maakt onderdeel uit van de NEN 3610-hoofdklasse "Begroeiing"


**Definitie**

| Naam  | Bos |
|---|---|
| Definitie |Begroeiing die een dusdanige aantal bomen betreft dat deze een min of meer gesloten geheel vormen of, na volgroeiing van de bomen, zullen vormen|
| Herkomst definitie  | Gebaseerd op de definities van bos in de BGT 1.2 |
| Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier grotendeels de bestaande populatie fysiek voorkomen *loofbos, naaldbos en gemengdbos* van *begroeid terreindeel* zoals deze is opgenomen in de basisregistratie grootschalige topografie|
| Toelichting| |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   | De unieke aanduiding van een bos|Ja |
|Geometrie| De geometrische representatie van de randen van een bos|Ja (vlak)|
|Status   | De fase van de levenscyclus waarin het betreffende bos zich bevindt|Ja   |
|Type bos| De aanduiding van het soort bos|Ja|


**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland|	
|Bestaand|	
|Verwijderd|	
|Niet gerealiseerd|	
|Ten onrechte|	

.

|Waarde Type bos| Beschrijving   |
|---|---|
| loofbos |Terrein begroeid met een dusdanige aantal loofbomen dat deze een min of meer gesloten geheel vormen of, na volgroeiing van de bomen, zullen vormen| 
| naaldbos | Terrein begroeid met een dusdanige aantal naaldbomen dat deze een min of meer gesloten geheel vormen of, na volgroeiing van de bomen, zullen vormen| 
| gemengd bos | Terrein begroeid met een dusdanig aantal naald- en loofbomen dat deze een min of meer gesloten geheel vormen of, na volgroeiing van de bomen, zullen vormen|  
 

####    Gras- en kruidachtigen

Dit SOR-begrip maakt onderdeel uit van de NEN 3610-hoofdklasse "Begroeiing"


**Definitie**

| Naam  |    Gras- en kruidachtigen |
|---|---|
| Definitie |Begroeiing die een laagblijvende, aaneengesloten gras- en/of kruidachtige vegetatie betreft|    
|Herkomst definitie  | IMBOR 2020 |
|Verplicht  | ja  |
|Gevolgen afbakening  | Het betreft hier grotendeels de bestaande populatie fysiek voorkomen *gras- en kruidachtigen*,*grasland agrarisch* en *grasland overig* zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting| | 

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   | De unieke aanduiding van gras- en kruidachtigen|Ja |
|Geometrie| De geometrische representatie van de randen van veld met gras- en kruidachtigen|Ja (vlak)|
|Status   | De fase van de levenscyclus waarin het betreffende veld met gras- en kruidachtigen zich bevindt|Ja   |


**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland|	
|Bestaand|	
|Verwijderd|	
|Niet gerealiseerd|	
|Ten onrechte|	



####  Struiken

Dit SOR-begrip maakt onderdeel uit van de NEN 3610-hoofdklasse "Begroeiing"


**Definitie**

| Naam  | Struiken |
|---|---|
| Definitie |Begroeiing die lage, houtachtige, overblijvende planten betreft, gekenmerkt door verschillende vertakkingen dicht bij de wortel en eventueel aanwezigheid van enkele verspreid staande stammen|   
|Herkomst definitie  |  BGT 1.2 |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie fysiek voorkomen *struiken*  zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting| | 

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   | De unieke aanduiding van struiken|Ja |
|Geometrie| De geometrische representatie van de randen van struiken|Ja (vlak)|
|Status   | De fase van de levenscyclus waarin de betreffende struiken zich bevinden|Ja   |


**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland|	
|Bestaand|	
|Verwijderd|	
|Niet gerealiseerd|	
|Ten onrechte|	





#### Gewas




Dit SOR-begrip maakt onderdeel uit van de NEN 3610-hoofdklasse "Begroeiing"


**Definitie**

| Naam  | Gewas  |
|---|---|
| Gewas |Begroeiing die gewassen betreft die in een teelt-roulatieschema zijn opgenomen|
|Herkomst definitie  | Definitie gebaseerd op bouwland in de BGT 1.2 |
|Verplicht  | ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie fysiek voorkomen *bouwland* zoals deze is opgenomen in de basisregistratie grootschalige topografie. BRT-object "Braakliggend" wordt voor zover het landbouwgrond betreft opgenomen in Gewas|
|Toelichting| Kan tijdelijk zonder gewas zijn of braak liggen|

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   | De unieke aanduiding van een Gewas|Ja |
|Geometrie| De geometrische representatie van de randen van een Gewas|Ja (vlak)|
|Status   | De fase van de levenscyclus waarin het betreffende gewas zich bevindt|Ja   |

**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland|	
|Bestaand|	
|Verwijderd|
|Niet gerealiseerd|
|Ten onrechte|


####    Fruit- of kweekbomen

Dit SOR-begrip maakt onderdeel uit van de NEN 3610-hoofdklasse "Begroeiing"


**Definitie**

| Naam  | Fruit- of kweekbomen |
|---|---|
| Definitie |Begroeiing die het kweken van meerjarige siergewassen en bomen betreft ten behoeve van een later gebruik elders of voor het kweken van fruit|
|Herkomst definitie  | nieuw |
|Verplicht  | ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie fysiek voorkomen *fruitteelt* en *boomteelt* zoals deze is opgenomen in de basisregistratie grootschalige topografie. En de *Boomkwekerij*, *Fruitkwekerij* en *Boomgaard* zoals deze is opgenomen in de basisregistratie topografie. De hier bedoelde kwekerijen onderscheiden zich van kwekerijen van potplanten door de langdurige stand/teelt van gewassen|
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   | De unieke aanduiding van fruit- of kweekbomen|Ja |
|Geometrie| De geometrische representatie van de randen van fruit- of kweekbomen|Ja (vlak)|
|Status   | De fase van de levenscyclus waarin de betreffende fruit- of kweekbomen zich bevinden|Ja   |
|Type fruit- of kweekbomen| De aanduiding van het soort fruit- of kweekbomen|Ja|



**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland|	
|Bestaand|	
|Verwijderd|	
|Niet gerealiseerd|	
|Ten onrechte|	

.

|Waarde Type fruit- of kweekbomen| Beschrijving   |
|---|---|
| laagstam boomgaarden |Terreindeel begroeid met laagstamfruitbomen|
| hoogstam boomgaarden |Terreindeel begroeid met hoogstamfruitbomen|
| wijngaarden|Terreindeel begroeid met druivenstokken voor wijnbouw|
| klein fruit |Terreindeel begroeid met heesters voor zachtfruit zoals bessen of frambozen|
| boomkwekerij |Terrein, overwegend in gebruik t.b.v. het opkweken van bomen (inclusief coniferen en sparren) en struiken, waarbij de hoogte van de aanplant niet van belang is|


#### Natuurlijk groen 

Dit SOR-begrip maakt onderdeel uit van de NEN 3610-hoofdklasse "Begroeiing"

MOERAS

Dit SOR-begrip maakt onderdeel uit van de NEN 3610-hoofdklasse "Begroeiing"

**Definitie**

| Naam  | Moeras |
|---|---|
| Definitie | Begroeiing die vegetatie in stilstaand water van geringe diepte zonder merkbare toe- of afvloeiing betreft |
|Herkomst definitie  | BGT 1.2    |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *moeras*  zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een Moeras|Ja |
|Geometrie|De geometrische representatie van de randen van een moeras|Ja (vlak)|
|Status   |  De fase van de levenscyclus waarin het moeras zich bevindt|Ja   |


**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|gepland|
|bestaand|
|verwijderd|
|niet gerealiseerd|
|Ten onrechte|

RIETLAND

Dit SOR-begrip maakt onderdeel uit van de NEN 3610-hoofdklasse "Begroeiing"

**Definitie**

| Naam  | Rietland |
|---|---|
| Definitie |Begroeiing die overwegend riet betreft|
|Herkomst definitie  | BGT 1.2    |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *rietland*  zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een Rietland|Ja |
|Geometrie|De geometrische representatie van de randen van een rietland|Ja (vlak)|
|Status   |  De fase van de levenscyclus waarin het rietland zich bevindt|Ja   |


**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|gepland|
|bestaand|
|verwijderd|
|niet gerealiseerd|
|Ten onrechte|

HEIDE

Dit SOR-begrip maakt onderdeel uit van de NEN 3610-hoofdklasse "Begroeiing"

**Definitie**

| Naam  | Heide |
|---|---|
| Definitie | Begroeiing die overwegend heide en heideachtige vegetaties betreft|
|Herkomst definitie  | BGT 1.2    |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *heide*  zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een Heide|Ja |
|Geometrie|De geometrische representatie van de randen van een heide|Ja (vlak)|
|Status   |  De fase van de levenscyclus waarin de heide zich bevindt|Ja   |


**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|gepland|
|bestaand|
|verwijderd|
|niet gerealiseerd|
|Ten onrechte|

DUIN

Dit SOR-begrip maakt onderdeel uit van de NEN 3610-hoofdklasse "Begroeiing"

**Definitie**

| Naam  | Duin |
|---|---|
| Definitie |Begroeiing die een verhoging of heuvel van zand of fijne losse aarde en verpulverd gesteente opgeworpen door wind of door stromend water betreft|
|Herkomst definitie  | BGT 1.2    |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *duin*  zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een Duin|Ja |
|Geometrie|De geometrische representatie van de randen van een duin|Ja (vlak)|
|Status   |  De fase van de levenscyclus waarin het duin zich bevindt|Ja   |


**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|gepland|
|bestaand|
|verwijderd|
|niet gerealiseerd|
|Ten onrechte|


#### Landschapselement

Dit SOR-begrip maakt onderdeel uit van de NEN 3610-hoofdklasse "Begroeiing"

BOMENRIJ

Dit SOR-begrip maakt onderdeel uit van de NEN 3610-hoofdklasse "Begroeiing"

**Definitie**

| Naam  | Bomenrij |
|---|---|
| Definitie | Begroeiing die een Opgaande rijvormige begroeiing van bomen zonder ondergroei van struiken betreft|
|Herkomst definitie  | BGT 1.2    |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *bomenrij*  zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een Bomenrij|Ja |
|Geometrie|De geometrische representatie van de randen van een bomenrij|Ja (vlak)|
|Status   |  De fase van de levenscyclus waarin de bomenrij zich bevindt|Ja   |


**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|gepland|
|bestaand|
|verwijderd|
|niet gerealiseerd|
|Ten onrechte|

HOUTSINGEL

Dit SOR-begrip maakt onderdeel uit van de NEN 3610-hoofdklasse "Begroeiing"

**Definitie**

| Naam  | Houtsingel |
|---|---|
| Definitie |Begroeiing die een opgaande rijvormige begroeiing van bomen (enkelvoudige/meervoudige stammen) mét ondergroei van struiken betreft|
|Herkomst definitie  | BGT 1.2    |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *houtwal*  zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een Houtsingel|Ja |
|Geometrie|De geometrische representatie van de randen van een houtsingel|Ja (vlak)|
|Status   |  De fase van de levenscyclus waarin de houtsingel zich bevindt|Ja   |


**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|gepland|
|bestaand|
|verwijderd|
|niet gerealiseerd|
|Ten onrechte|

HAAG

Dit SOR-begrip maakt onderdeel uit van de NEN 3610-hoofdklasse "Begroeiing"

**Definitie**

| Naam  | Haag |
|---|---|
| Definitie | Begroeiing die een rijvormige afscheiding van zeer beperkte breedte bestaande uit aangeplante aaneengesloten struiken betreft|
|Herkomst definitie  | BGT 1.2    |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *haag*  zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een Haag|Ja |
|Geometrie|De geometrische representatie van de randen van een haag|Ja (vlak)|
|Status   |  De fase van de levenscyclus waarin de haag zich bevindt|Ja   |


**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|gepland|
|bestaand|
|verwijderd|
|niet gerealiseerd|
|Ten onrechte|


#### Boom

Dit SOR-begrip maakt onderdeel uit van de NEN 3610-hoofdklasse "Begroeiing"


**Definitie**

| Naam  | Boom |
|---|---|
| Definitie | Begroeiing die een markante boom die geen onderdeel uitmaakt van bos of struiken betreft|
|Herkomst definitie  | IMGeo 2.2 |
|Verplicht  | nee  |
|Gevolgen afbakening  | nieuw object  |
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een boom|Ja |
|Geometrie| De geometrische representatie van een boom|Ja (punt)|
|Status   | De fase van de levenscyclus waarin de betreffende boom zich bevindt|Ja   |
|Soortnaam| De soortnaam o.b.v. ‘Naamlijst van houtige gewassen en vaste planten’,  internationaal erkend als standaard| Ja|




**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland|	
|Bestaand|	
|Verwijderd|
|Niet gerealiseerd|
|Ten onrechte|

.

|Waarde soortnaam|
|---|
|Betreffende soortnaam uit ‘Naamlijst van houtige gewassen en vaste planten’|


### Gebouw



#### Gebouw

Dit SOR-begrip maakt onderdeel uit van de NEN 3610-hoofdklasse "Gebouw"

**Definitie**

| Naam  | Gebouw  |
|---|---|
| Definitie | Overdekte en geheel of gedeeltelijk met wanden omsloten constructief zelfstandige eenheid die bedoeld is voor het in een afgeschermde omgeving onderbrengen van mensen, dieren of voorwerpen of voor de productie van goederen|
|Herkomst definitie  |Gebaseerd op definitie “pand” in artikel 1 Wet basisregistratie adressen en gebouwen en de INSPIRE richtlijn |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier grotendeels de bestaande populatie panden zoals deze is opgenomen in de basisregistratie adressen en gebouwen en de basisregistratie grootschalige topografie |
|Toelichting| *volgt later* |



**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een gebouw|Ja |
|Geometrie |De geometrische representatie van de randen van een gebouw   |Ja (3D)|
|Typering|Het doel waarvoor een gebouw gebruikt wordt|Ja|
|Aard|De fysieke verschijningsvorm van een gebouw  |Ja|
|Oorspronkelijk bouwjaar | De aanduiding van het jaar waarin een gebouw oorspronkelijk als bouwkundig gereed is of zal worden opgeleverd|Ja|
|Naam| Een breed geaccepteerde benaming van een gebouw zoals deze door de eigenaar is toegekend of zoals deze in de volksmond bekend staat| Nee|
|Status   |De fase van de levenscyclus waarin het gebouw zich bevindt    |Ja   |


**Domeinwaarden**

<div class='note'>
    De definitieve lijst met TYPE en AARD zal op een later moment worden opgeleverd. Het is daarbij de bedoeling dat deze lijst aansluit op de bij de WOZ in ontwikkeling zijnde lijst met domeinwaarden voor WOZ-deelobjecten. Ook moet nog een nadere uitlijning op typeringen vanuit de BRT.next plaatsvinden. Onderstaande domeinwaarden zijn uitsluitend voorbeelden van enkele waarschijnlijke typeringen om een indruk te geven van het soort waarden dat hier zal worden opgenomen.
</div>


|Waarde Typering|	Beschrijving|
|---|---|
|Woning	||
|Bedrijf||	


*aard*

|Waarde Aard|	Beschrijving|
|---|---|
|Vrijstaand gebouw||	
|Aangrenzende gelijksoortige gebouwen||	
|Onderdeel heterogeen gebouwblok||

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland|	
|Bestaand|	
|Bouwvergunning verleend|	
|Sloopvergunning verleend|	
|In aanbouw|
|In verbouw|	
|Gesloopt|	
|Niet gerealiseerd|
|Ten onrechte|



#### Bouwlaag

Dit SOR-begrip maakt onderdeel uit van de NEN 3610-hoofdklasse "Gebouw"

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
|Identificatie   |De unieke aanduiding van een Bouwlaag|Ja |
|Geometrie |De geometrische representatie van de randen van een Bouwlaag  |Ja (2,5D)|
|Bouwlaagnummer |Het niveau waarop de bouwlaag zich bevindt|Ja|
|Status   |De fase van de levenscyclus waarin een Bouwlaag zich bevindt   |Ja   |


**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|Ligt in|Gebouw| Ja|

**Domeinwaarden**


*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland|	
|Bouwvergunning verleend|	
|Sloopvergunning verleend|	
|In aanbouw|	
|Bestaand|	
|In verbouw|	
|Gesloopt|	
|Niet gerealiseerd|	
|Ten onrechte opgevoerd|	


#### Ruimte

Dit SOR-begrip maakt onderdeel uit van de NEN 3610-hoofdklasse "Gebouw"

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
|Identificatie   |De unieke aanduiding van een Ruimte|Ja |
|Geometrie |De geometrische representatie van de randen van een Ruimte   |Ja (2,5D)|
|Bouwlaagnummer |De bouwlaag waarop de ruimte zich bevindt|Ja|
|Oppervlakte| De gebruiksoppervlakte van de ruimte| Nee |
|Typering|Het doel waarvoor een ruimte gebruikt wordt| Ja|
|Status   |De fase van de levenscyclus waarin een Ruimte zich bevindt   |Ja   |


**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|Ligt op|Bouwlaag| Ja|

**Domeinwaarden**

<div class='note'>
De definitieve lijst met TYPE zal op een later moment worden opgeleverd. Het is daarbij de bedoeling dat deze lijst aansluit op de begrippen zoals deze in BIM modellen voor de bouw worden gehanteerd. Onderstaande domeinwaarden zijn uitsluitend voorbeelden van enkele waarschijnlijke typeringen om een indruk te geven van het soort waarden dat hier zal worden opgenomen.
</div>


|Waarde Typering|	Beschrijving|
|---|---|
|Woonkamer	||
|Keuken||	




*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland|	
|Bestaand|	
|Verwijderd|
|Niet gerealiseerd|
|Ten onrechte opgevoerd|
|Bouwvergunning verleend|	
|Sloopvergunning verleend|	
|In aanbouw|	
|In verbouw|	
|Gesloopt|



#### Gebouwcomponent

Dit SOR-begrip maakt onderdeel uit van de NEN 3610-hoofdklasse "Gebouw"

**Definitie**

| Naam  | Gebouwcomponent  |
|---|---|
| Definitie | Een component aan de buitenzijde van een gebouw, die het aanzicht van het gebouw mede bepaalt |
|Herkomst definitie  |IMGeo 2.2|
|Verplicht  | Deels (nog nader te bepalen welke onderdelen) |
|Gevolgen afbakening  |Het betreft hier grotendeels de bestaande populatie van *gebouwinstallatie* zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting| *volgt later* |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een gebouwcomponent|Ja |
|Geometrie |De geometrische representatie van de randen van een gebouwcomponent   |Ja (1,5D of 2,5D)|
|Aard|Het soort gebouwcomponent|Ja |
|Bijbehorend object |Het object waarbij de betreffende gebouwcomponent behoort|Ja|
|Status   |De fase van de levenscyclus waarin de betreffende gebouwcomponent zich bevindt   |Ja   |


**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|Hoort bij|Verblijfsobject|Ja|
|Hoort bij|Gebouw|Ja|

**Domeinwaarden**

<div class='note'>
    De definitieve lijst met AARD zal op een later moment worden opgeleverd. Het is daarbij de bedoeling dat deze lijst aansluit op de begrippen zoals deze elders worden gehanteerd. Onderstaande domeinwaarden zijn uitsluitend voorbeelden van enkele waarschijnlijke typeringen om een indruk te geven van het soort waarden dat hier zal worden opgenomen.

</div>


| Waarde Aard| Beschrijving   |
|---|---|
|dakkapel |Een uitbouw van het schuine dakvlak|
|luifel|Afdak aangebracht aan de gevel van een pand, eventueel rustend op kolommen|
|bordes|Een verhard oppervlak, eventueel verhoogd en/of uitgevoerd met treden, grenzen aan een pand en primair bedoeld voor gebruik door voetgangers|
|toegangstrap|Niet afsluitbare trap (of trappenhuis) die toegang biedt aan een gebouw|



*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland|	
|Bestaand|	
|Verwijderd|
|Niet gerealiseerd|
|Ten onrechte opgevoerd|
|Bouwvergunning verleend|	
|Sloopvergunning verleend|	
|In aanbouw|	
|In verbouw|	
|Gesloopt|	



#### Toegangsdeur

Dit SOR-begrip maakt onderdeel uit van de NEN 3610-hoofdklasse "Gebouw"

**Definitie**

| Naam  | Toegangsdeur |
|---|---|
| Definitie | Deur of andere voorziening die vanaf de openbare weg, een erf of een gedeelde verkeersruimte toegang geeft tot een object|
|Herkomst definitie  |Begrip sluit aan bij het begrip Deur (IfcDoor) uit de concepten rondom Bouwwerkinformatiemodellen (BIM)|
|Verplicht  | Deels (nog nader te bepalen welke onderdelen) |
|Gevolgen afbakening  | Het betreft hier ten opzichte van de bestaande basisregistraties grotendeels een nieuw objecttype|
|Toelichting| *volgt later* |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een toegangsdeur|Ja |
|Geometrie |De geometrische representatie van een Toegangsdeur   |Ja (1,5D)|
|Toegangssoort|De plaats waarvan de toegangsdeur toegang geeft|Ja|
|Gebruiksaard|De aard van gebruik van de  toegangsdeur|Ja|
|Bijbehorend object |Het object waarin de betreffende toegangsdeur zich bevindt|Ja|
|Status   |De fase van de levenscyclus waarin de betreffende toegangsdeur zich bevindt   |Ja   |


**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|Hoort bij|Verblijfsobject| Ja|
|Hoort bij|Gebouw| Ja|

**Domeinwaarden**

*toegangssoort*

| Waarde Toegangssoort| Beschrijving   |
|---|---|
|directe toegang vanaf eigen terrein|de toegangsdeur bevindt zich op een erf, in een tuin of een andere specifiek terrein dat behoort bij het gebouw |
|directe toegang vanaf openbare weg|de toegangsdeur bevindt zich direct aan een voor iedereen toegankelijke weg |
|toegang vanaf gemeenschappelijke verkeersruimte |de toegangsdeur bevindt zich aan een inpandige ruimte die bedoeld is voor verplaatsingen door een gebouw door de verschillende gebruikers van dit gebouw  |

*gebruiksaard*

| Waarde Gebruiksaard| Beschrijving   |
|---|---|
|Personen|de toegangsdeur is primair bedoeld voor toegang tot een object door personen |
|Auto|de toegangsdeur is primair bedoeld voor toegang tot een object door voertuigen |
|Vracht|de toegangsdeur is primair bedoeld voor toegang tot een object door vracht zonder gebruik van een voertuig|


*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland|	
|Bestaand|	
|Verwijderd|
|Niet gerealiseerd|
|Ten onrechte opgevoerd|

#### Open bouwwerk


Dit SOR-begrip maakt onderdeel uit van de NEN 3610-hoofdklasse "Constructie"

**Definitie**

| Naam  | Open bouwwerk |
|---|---|
| Definitie | Constructie die een afzonderlijk staande overdekking is en rust op kolommen met één of meerder open gevels en is bedoeld voor het beschutten of stallen van objecten of voertuigen |
|Herkomst definitie  |Gebaseerd op definities “open loods” en “overkapping” uit de gegevenscatalogus BGT|
|Verplicht  | Ja |
|Gevolgen afbakening  |Het betreft hier grotendeels de bestaande populatie open loodsen en overkappingen zoals deze is opgenomen in de basisregistratie adressen en gebouwen en de basisregistratie grootschalige topografie |
|Toelichting| *volgt later* |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een open bouwwerk|Ja |
|Geometrie |De geometrische representatie van de randen van een open bouwwerk   |Ja (3D)|
|typering| Het soort open bouwwerk|
|Status   |De fase van de levenscyclus waarin het betreffende open bouwwerk zich bevindt   |Ja   |




**Domeinwaarden**

*typering*

|Waarde typering| Beschrijving|
|---|---|
|overkapping|Een afzonderlijk staande overdekking rustend op kolommen|
|open loods|Niet verplaatsbaar licht gebouw met een open gevel, bestemd als berg- of werkplaats of als tijdelijk onderdak voor andere doeleinden|
|parkeergarage|Een open constructie die geheel of gedeeltelijk in gebruik is als voorziening voor het parkeren van motorvoertuigen|


*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland|	
|Bestaand|	
|Verwijderd|
|Niet gerealiseerd|
|Ten onrechte opgevoerd|


### Verharding


Dit SOR-begrip maakt onderdeel uit van de NEN 3610-hoofdklasse "Verharding"

 

**Definitie**

| Naam  | Verharding |
|---|---|
| Definitie |Oppervlak, dat door egaliseren, verstevigen en/of verruwen voor het beoogde gebruik geschikt gemaakt is, bestaande uit in één of meer lagen over een ondergrond of onderliggende constructie aangelegd materiaal|
|Herkomst definitie  | concept NEN3610-2020  |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier een selectie van de bestaande populatie fysieke voorkomen van *wegdelen*, *ondersteunende wegdelen* en *onbegroeide terreindelen* zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting| Een verhardingsvlak bestaat uit één Type verharding. Het gaat hierbij over het Type verharding waarmee het vlak overwegend is bedekt|

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een verharding|Ja |
|Geometrie|De geometrische representatie van de randen van een verhardingsvlak|Ja (vlak, 2.5D)|
|Status   | De fase van de levenscyclus waarin het betreffende verhardingsvlak zich bevindt|Ja   |
|Type verharding|De aanduiding van het soort verharding|Ja|



**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland|	
|Bestaand|	
|Verwijderd|
|Niet gerealiseerd|
|Ten onrechte|

*type verharding*

|Waarde Type verharding| Beschrijving   |
|---|---|
| Asfaltverharding|Gesloten verharding bestaande uit asfaltbeton of andere met bitumen gebonden materialen|
| Betonverharding |Gesloten verharding bestaande uit gewapend of ongewapend beton|
| Elementenverharding|Open verharding opgebouwd uit losse elementen die in meer of mindere mate met elkaar verbonden zijn|
| Halfverharding|Open verharding bestaande uit onsamenhangend materiaal dat meer draagkracht levert dan de originele grond|
| Kunststofverharding|Synthetisch vervaardigd materiaal dat als verharding dient|
| Onverhard| Onverhard oppervlakte bestaande uit natuurlijke materialen, voorzien van een fundering|


### Kunstwerk
#### Overbrugging

Dit SOR-begrip maakt onderdeel uit van de NEN 3610-hoofdklasse "Kunstwerk"

**Definitie**

| Naam  | Overbrugging  |
|---|---|
| Definitie | Kunstwerk dat een beweegbare of vaste verbinding tussen twee punten betreft, die door water, een weg of anderszins  gescheiden zijn,  bestaande uit een brugdek/-bak met landhoofden en veelal gesteund door pijlers|
|Herkomst definitie  | nieuw  |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier grotendeels de bestaande populatie  *overbruggingsdelen; hoort bij Type overbrugging* zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van overbrugging|Ja |
|Geometrie|De geometrische representatie van de randen van een overbrugging|Ja (vlak, 2.5D)|
|Status   | De fase van de levenscyclus waarin de betreffende overbrugging zich bevindt|Ja   |
|Type overbrugging|De aanduiding van het soort overbrugging|Ja|
|Naam| Een breed geaccepteerde benaming van een overbrugging zoals deze door de eigenaar is toegekend of zoals deze in de volksmond bekend staat| Nee|
| Beperkingen | Verkeerskundige beperkingen die voor het betreffende kunstwerk gelden| Ja|
| Beweegbaar |De aanduiding of overbrugging beweegbaar is (open en dicht kan) |Ja|



**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland|	
|Bestaand|	
|Verwijderd|
|Niet gerealiseerd|
|Ten onrechte|

*type overbrugging* 

|Waarde Type overbrugging| Beschrijving   |
|---|---|
| brug |Overbruggingsconstructie over een watervlakte of waterloop, bedoelt voor verkeer|
| aquaduct |Overbruggingsconstructie waarmee een watergang door een bakvormige constructie over een weg, een spoorweg, een andere watergang, een leiding of een terrein wordt geleid|
| viaduct |Overbruggingsconstructie over een weg, spoorweg of terreinverdieping, bedoelt voor verkeer|
| ecoduct |Overbruggingsconstructie over een weg of spoorweg,  bedoelt voor het passeren van dieren|
| flyover|Kunstwerk in de vorm van een viaduct dat deel uitmaakt van een verkeersbaan en waarmee een verkeersstroom over twee of meer ongelijkvloerse verkeersstromen wordt geleid.*bestaande definitie niet consistent*   |
| overkluizing |Een civieltechnisch kunstwerk waarmee een weg, een plein of een waterloop (kruiselings) wordt overwelft, waarbij het dek meestal niet uitsluitend uit een pad of weg bestaat|

.

|Waarde Beperking| Beschrijving   |
|---|---|
| doorrijhoogte | Maximale doorrijhoogte tussen het wegdek en de constructie boven het wegdek geldend op een weg, rijbaan of rijstrook (afhankelijk van de type verbinding)|
| doorrijbreedte| Maximale doorrijbreedte tussen de dichtstbij gelegen objecten aan weerszijden van de weg, rijbaan, rijstrook(afhankelijk van de type verbinding)|
| toegestane massa|Toegestane massa op een kunstwerk/verharding|
| toegestane lengte|Toegestane lengte op een locatie van de weg, rijbaan, rijstrook (afhankelijk van de type verbinding)|
| doorvaarhoogte |De hoogte die beschikbaar is tussen water en de constructies welke boven het water aanwezig zijn|


#### Kunstwerkdeel

Dit SOR-begrip maakt onderdeel uit van de NEN 3610-hoofdklasse "Kunstwerk"

 

**Definitie**

| Naam  |Kunstwerkdeel  |
|---|---|
| Definitie |  Kunstwerk dat een onderdeel van een civieltechnisch werk voor de infrastructuur van wegen, water, spoorbanen, waterkeringen en/of leidingen betreft|
|Herkomst definitie  | BGT 1.2  |
|Verplicht  | ja  |
|Gevolgen afbakening  | Het betreft hier grotendeels de bestaande populatie  *overbruggingsdelen, Type overbruggingsdeel* zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een kunstwerkdeel|Ja |
|Geometrie|De geometrische representatie van de randen van een kunstwerkdeel|Ja (vlak, 2.5D|
|Status   |  De fase van de levenscyclus waarin het betreffende kunstwerkdeel zich bevindt|Ja   |
|Type kunstwerkdeel| De aanduiding van het soort kunstwerkdeel|ja|


**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
| hoort bij | kunstwerk, type overbrugging | ja|
| hoort bij | kunstwerk, type sluis | ja|

**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland|	
|Bestaand|	
|Verwijderd|
|Niet gerealiseerd|
|Ten onrechte|

*Type kunstwerkdeel*

|Waarde Type kunstwerkdeel| Beschrijving   |
|---|---|
| dek |Direct door het verkeer belaste deel van de bovenbouw van de brug|
| landhoofd |Ondersteuningsconstructie ter plaatse van een overgang van de aardebaan naar een kunstwerk|
| pijler |Ondersteuningsconstructie van bruggen en soortgelijke kunstwerken|
| sloof |Deel van de pijler voor de overdracht van krachten naar de ondergrond of de fundering|
| pyloon |Boven de bovenbouw uitstekende draagconstructie voor tuien (kabels)|
| sluisdeur |Beweegbare deur die wordt toegepast bij (hoog)waterkeringen en sluizen om het niveauverschil aan beide zijden in stand te houden|
| kolk |Deel van de sluis waarin de te schutten schepen afmeren en op een hoger of lager niveau worden gebracht|
| vuilvang | Een voorziening om de waterloop dan wel één of meerdere objecten benedenstrooms te vrijwaren van drijvend vuil en dergelijke|


#### Ondertunneling


Dit SOR-begrip maakt onderdeel uit van de NEN 3610-hoofdklasse "Kunstwerk"

 

**Definitie**

| Naam  | Ondertunneling  |
|---|---|
| Definitie | Kunstwerk dat een ondergrondse of onder water gelegen verbinding tussen twee punten, aan beide einden voorzien van een open bakconstructie betreft|
|Herkomst definitie  | nieuw |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier grotendeels de bestaande populatie  *tunneldelen* zoals deze is opgenomen in de basisregistratie grootschalige topografie. En van *kunstwerkdelen van Type duiker* indien opgenomen in het IMGeo deel van de basisregistratie grootschalige topografie|
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een ondertunneling|Ja |
|Geometrie|De geometrische representatie van de randen van een ondertunneling|Ja (vlak, 2.5D)|
|Status   | De fase van de levenscyclus waarin de betreffende ondertunneling zich bevindt|Ja   |
|Type ondertunneling| De aanduiding van het soort ondertunneling|Ja|
|Naam| Een breed geaccepteerde benaming van een ondertunneling zoals deze door de eigenaar is toegekend of zoals deze in de volksmond bekend staat| Nee|
| Beperkingen | Verkeerskundige beperkingen die voor het betreffende kunstwerk gelden| Ja|



**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland|	
|Bestaand|	
|Verwijderd|
|Niet gerealiseerd|
|Ten onrechte|

*type ondertunneling*

|Waarde Type ondertunneling| Beschrijving   |
|---|---|
| tunnel |Kokervormig kunstwerk onder een of meer wegen, spoorwegen, waterwegen en/of andere hindernissen, als ondergrondse doorgang voor verkeer, leidingen of dieren|
| duiker |Kunstwerk voor de waterhuishouding, bestaande uit een gesloten kokervormige constructie met een in- en uitstroomopening, die niet de gehele waterbreedte beslaand, aangebracht onder een weg of spoorweg of in een dam of ander terreindeel en de bodem van de waterloop onderbreekt|

.

|Waarde Beperking| Beschrijving   |
|---|---|
| doorrijhoogte | Maximale doorrijhoogte tussen het wegdek en de constructie boven het wegdek geldend op een weg, rijbaan of rijstrook (afhankelijk van de type verbinding)|
| doorrijbreedte| Maximale doorrijbreedte tussen de dichtstbij gelegen objecten aan weerszijden van de weg, rijbaan, rijstrook(afhankelijk van de type verbinding)|
| toegestane massa|Toegestane massa op een kunstwerk/verharding|
| toegestane lengte|Toegestane lengte op een locatie van de weg, rijbaan, rijstrook (afhankelijk van de type verbinding)|


#### Kerende kunstwerken


Dit SOR-begrip maakt onderdeel uit van de NEN 3610-hoofdklasse "Kunstwerk"

**Definitie**

| Naam  | Kerende kunstwerken  |
|---|---|
| Definitie | Kunstwerk dat kerende functie heeft|
|Herkomst definitie  | nieuw  |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier grotendeels de bestaande populatie  zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van kerende kunstwerken|Ja |
|Geometrie|De geometrische representatie van de randen van het betreffende kunstwerk|Ja (vlak, 2.5D)|
|Status   | De fase van de levenscyclus waarin het betreffende kunstwerk zich bevindt|Ja   |
|Type kerend kunstwerk| De aanduiding van het soort kunstwerk|Ja|
|Naam| Een breed geaccepteerde benaming van een overbrugging zoals deze door de eigenaar is toegekend of zoals deze in de volksmond bekend staat| Nee|


**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
| heeft mogelijk een functie| kering| Ja|


**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland|	
|Bestaand|	
|Verwijderd|
|Niet gerealiseerd|
|Ten onrechte|

*type kerend kunstwerk*

|Waarde type kerend kunstwerk| Beschrijving   |
|---|---|
| keermuur |muur die door vorm, gewicht en fundering zonder verankering de grond keert|
| kademuur |Grondkerende constructie tegen afkalving van de walkant, in de vorm van een verticale wand ter scheiding van land en water, opgebouwd uit een muur van gemetselde stenen of gestort beton|
| damwand |Grondkerende of waterkerende constructie bestaande uit (nagenoeg) verticaal in de grond aangebrachte elementen die door middel van een langsprofiel in elkaar grijpen|
| walbescherming |Een nagenoeg verticale wand tot kering van grond om afkalving van water te voorkomen, niet zijnde een kademuur|
| schot|Permanente afscheiding, verticaal in het water geplaatst, bedoeld om het waterpeil van het aan beide zijden aanwezige water te regelen|
| stuw |Een vaste of beweegbare constructie in het water die dient om de waterstand bovenstrooms en/of benedenstrooms van de constructie te regelen  |
| sluis |Een kunstmatige, afsluitbare waterkering die een scheepvaartverbinding tussen twee wateren met verschillende waterpeilen mogelijk maakt|
| coupure |Een onderbreking in een waterkering voor de doorvoer van een weg of spoorweg, die bij extreme waterstanden afsluitbaar is|
| dijk|Een dijk is een aangelegde waterkering, die het achterliggende land beschermt tegen overstromingen|



#### Overige kunstwerken


Dit SOR-begrip maakt onderdeel uit van de NEN 3610-hoofdklasse "Kunstwerk"

**Definitie**

| Naam  | Overige kunstwerken  |
|---|---|
| Definitie | Kunstwerk dat een civiel-technisch werk betreft voor de infrastructuur van wegen, water, spoorbanen, waterkeringen en/of leidingen|
|Herkomst definitie  | NEN3610 |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier grotendeels de bestaande populatie  zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van overige kunstwerken|Ja |
|Geometrie|De geometrische representatie van de randen van het betreffende kunstwerk|Ja (vlak, 2.5D)|
|Status   | De fase van de levenscyclus waarin het betreffende kunstwerk zich bevindt|Ja   |
|Type overig kunstwerk| De aanduiding van het soort kunstwerk|Ja|
|Naam| Een breed geaccepteerde benaming van een kunstwerk zoals deze door de eigenaar is toegekend of zoals deze in de volksmond bekend staat| Nee|




**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland|	
|Bestaand|	
|Verwijderd|
|Niet gerealiseerd|
|Ten onrechte|

*type overig kunstwerk*

|Waarde type overig kunstwerk| Beschrijving   |
|---|---|
| gemaal | Een kunstwerk in principe bedoeld om water van een laag peil naar een hoog peil te brengen|
| bezinkbak| Een gesloten reservoir waarin het afvalwater tijdelijk wordt opgevangen met een slibreinigende voorziening|
| strekdam | Dam in de richting van de loop van de rivier of kanaal, ter beveiliging van de oevers of brugpijlers of ter beheersing van de rivier|
| steiger |Vaste (niet drijvende) waterbouwkundige constructie, verbonden met de wal, voor het aanleggen van schepen en bedoeld om deze schepen vanaf de wal te laden en te lossen|
| vispassage |Een waterbouwkundig constructie dat tot doel heeft vissen toegang te bieden tot een door een kunstwerk onbereikbaar geworden achterland|
| bodemval |Sprong in de bodem van een waterloop|
| ponton |Vastliggend drijflichaam, dat dienst doet als aanlegplaats van vaartuigen of daartoe toegang geeft|
| voorde |Een doorwaadbare, doorgaans verharde, plaats in de waterloop, die dient voor de oversteek van die waterloop|





### Overige constructies



#### Muur
  

Dit SOR-begrip maakt onderdeel uit van de NEN 3610-hoofdklasse "Constructie"

 


**Definitie**

| Naam  | Muur |
|---|---|
| Definitie |Constructie die een relatief smal, rechtopstaand bouwwerk betreft|
|Herkomst definitie  |Basisregistratie Topografie: Catalogus en Productspecificaties (versie 1.2.0.1)|
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier grotendeels de bestaande populatie  *scheidingen, Type muur* zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|   |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
| Identificatie   |De unieke aanduiding van een muur|Ja |
| Geometrie|De geometrische representatie van een muur|Ja (lijn) Nee (vlak)|
| Status   |De fase van de levenscyclus waarin het betreffende muur zich bevindt|Ja   |





**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland|	
|Bestaand|	
|Verwijderd|
|Niet gerealiseerd|
|Ten onrechte|


#### Omheining


Dit SOR-begrip maakt onderdeel uit van de NEN 3610-hoofdklasse "Constructie"

 

**Definitie**

| Naam  | Omheining |
|---|---|
| Definitie | Kunstmatige verticale constructie die bedoeld is om de toegang tot een gebied te weren|
|Herkomst definitie  |nieuw|
|Verplicht  | *staat ter discussie* |
|Gevolgen afbakening  | Het betreft hier grotendeels de bestaande populatie  *scheidingen, Type hek en Type draadraster, faunaraster* zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting| *volgt later*  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een omheining|Ja |
|Geometrie|De geometrische representatie van een omheining|Ja (lijn)|
|Status   | De fase van de levenscyclus waarin de betreffende omheining zich bevindt|Ja   |


**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.


|Waarde Status| 
|---|
|Gepland|	
|Bestaand|	
|Verwijderd|
|Niet gerealiseerd|
|Ten onrechte|


#### Scherm
  

Dit SOR-begrip maakt onderdeel uit van de NEN 3610-hoofdklasse "Constructie"

 

**Definitie**

| Naam  | Scherm |
|---|---|
| Definitie |Constructie die lineair is en specifiek bedoeld om te reduceren|
|Herkomst definitie  |nieuw|
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier grotendeels de bestaande populatie  *scheidingen, Type geluidscherm* zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een scherm|Ja |
|Geometrie|De geometrische representatie van een scherm|Ja (lijn)|
|Status   |De fase van de levenscyclus waarin het betreffende scherm zich bevindt|Ja   |




**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland|	
|Bestaand|	
|Verwijderd|
|Niet gerealiseerd|
|Ten onrechte|



#### Afvalcontainer

Dit SOR-begrip maakt onderdeel uit van de NEN 3610-hoofdklasse "Constructie"

 

**Definitie**

| Naam  | Afvalcontainer  |
|---|---|
| Definitie | Constructie die een permanent karakter heeft en dient om iets in te bergen of te verzamelen|
|Herkomst definitie  | IMGeo 2.2  |
|Verplicht  | Nee  |
|Gevolgen afbakening  | Het betreft hier een subset van de bestaande populatie *bak* zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een afvalcontainer|Ja |
|Geometrie|De geometrische representatie van de locatie van een afvalcontainer|Ja (punt)|
|Status   | De fase van de levenscyclus waarin de afvalcontainer zich bevindt|Ja   |



**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland|	
|Bestaand|	
|Verwijderd|
|Niet gerealiseerd|
|Ten onrechte|



#### Bassin

Dit SOR-begrip maakt onderdeel uit van de NEN 3610-hoofdklasse "Constructie"

 

**Definitie**

| Naam  | Bassin  |
|---|---|
| Definitie | Constructie met een bekkken emt een ondoorlaatbare bodem waarin weater opgeslagen kan worden|
|Herkomst definitie  |... |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier het bassin als type overig bouwwerk zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een bassin|Ja |
|Geometrie|De geometrische representatie van de locatie van een bassin|Ja (vlak)|
|Status   | De fase van de levenscyclus waarin het bassin zich bevindt|Ja   |



**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland|	
|Bestaand|	
|Verwijderd|
|Niet gerealiseerd|
|Ten onrechte|


#### Opslagtank

Dit SOR-begrip maakt onderdeel uit van de NEN 3610-hoofdklasse "Constructie"

 

**Definitie**

| Naam  | Opslagtank  |
|---|---|
| Definitie | Constructie die een reservoir  betreft dat bovengronds is en vaak afgesloten en bestemd is voor gassen, energie of vloeistoffen|
|Herkomst definitie  | IMGeo 2.2  |
|Verplicht  | Nee  |
|Gevolgen afbakening  | Het betreft hier de opsalgtank als type overig bouwwerk zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een opslagtank|Ja |
|Geometrie|De geometrische representatie van de locatie van een opslagtank|Ja (vlak)|
|Status   | De fase van de levenscyclus waarin de opslagtank zich bevindt|Ja   |



**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland|	
|Bestaand|	
|Verwijderd|
|Niet gerealiseerd|
|Ten onrechte|

#### Putdeksel

Dit SOR-begrip maakt onderdeel uit van de NEN 3610-hoofdklasse "Constructie"

 

**Definitie**

| Naam  | Putdeksel  |
|---|---|
| Definitie | Het afsluitende deel van een gegraven, koker of lijnvormige constructie waarin zich (vloei)stoffen kunnen bevinden|
|Herkomst definitie  |   Afgeleid van de definitie van een put in IMGeo 2.2 |
|Verplicht  | Nee  |
|Gevolgen afbakening  | Het betreft hier een samenvoeging van de bestaande populatie *put* en van een subset van de bestaande populatie *weginrichtingselementen* zoals deze zijn opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een putdeksel|Ja |
|Geometrie|De geometrische representatie van de ligging van de putdeksel|Ja (punt, lijn, vlak)|
|Status   | De fase van de levenscyclus waarin de putdeksel zich bevindt|Ja   |
|Type deksel|De aanduiding van het soort deksel |Ja|




**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland|	
|Bestaand|	
|Verwijderd|
|Niet gerealiseerd|
|Ten onrechte|





#### Geleider

Dit SOR-begrip maakt onderdeel uit van de NEN 3610-hoofdklasse "Constructie"
 

**Definitie**

| Naam  | Geleider  |
|---|---|
| Definitie | Constructie die is bedoeld voor de fysieke (be)geleiding van voer-, vaartuigen|
|Herkomst definitie  | nieuw    |
|Verplicht  | Nee  |
|Gevolgen afbakening  | Het betreft hier een samenvoeging van een subset van de bestaande populaties *waterinrichtingselementen* en *weginrichtingselementen* zoals deze zijn opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een geleider|Ja |
|Geometrie|De geometrische representatie van de ligging van de geleider|Ja (lijn, vlak)|
|Status   |  De fase van de levenscyclus waarin de geleider zich bevindt|Ja   |
|Type geleider|De aanduiding van het soort geleider|Nee|





**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland|	
|Bestaand|	
|Verwijderd|
|Niet gerealiseerd|
|Ten onrechte|

.


#### Installatie

Dit SOR-begrip maakt onderdeel uit van de NEN 3610-hoofdklasse "Constructie"

 

**Definitie**

| Naam  | Installatie  |
|---|---|
| Definitie | Constructie die een technisch samenhangend systeem betreft dat een bepaald doel dient|
|Herkomst definitie  | Gebaseerd op installatie in IMGeo 2.2  |
|Verplicht  | Nader te bepalen  |
|Gevolgen afbakening  | Het betreft hier de bestaande populaties  *installatie* zoals deze zijn opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een installatie|Ja |
|Geometrie|De geometrische representatie van de ligging van de installatie of van de randen van de installatie|Ja (punt, lijn, vlak)|
|Status   |  De fase van de levenscyclus waarin de installatie zich bevindt|Ja   |
|Type installatie| De aanduiding van het soort installatie|Ja|


**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|hoort bij|gebouw|ja|
|hoort bij|verblijfsobject|ja|





**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland|	
|Bestaand|	
|Verwijderd|
|Niet gerealiseerd|
|Ten onrechte|

.

|Waarde Type installatie| Beschrijving   |
|---|---|
|**verplicht**||
|sirene|*nog toevoegen*|
|verkeerslicht|*nog toevoegen*|
|openbare verlichting|*nog toevoegen*|
|kast|Constructie met een permanent karakter dat dient om iets in te bergen en te beschermen|
|**vrijwillig**||
|pomp|Technische inrichting om vloeistoffen en/of gassen te verplaatsen|
|zonnepanelen| Een installatie om zonne-energie om te zetten in energie |
|lift| Een installatie gericht op het verticaal vervoeren van personen en goederen|
|windturbine|Turbine waarin winddruk omgezet wordt in mechanische energie|
|oplaadpunt| Systeem voor opladen van elektrische auto's |




#### Mast

Dit SOR-begrip maakt onderdeel uit van de NEN 3610-hoofdklasse "Constructie"

 

**Definitie**

| Naam  | Mast  |
|---|---|
| Definitie | Constructie die een hoge draagconstructie betreft voor een installatie of het transport van energie en elektromagnetische straling |
|Herkomst definitie  |  nieuw   |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier een samenvoeging van een subset van de bestaande populaties *gebouwen*, *kunstwerkdelen* en *mast* zoals deze zijn opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een mast|Ja |
|Geometrie|De geometrische representatie van de ligging van de mast of van de randen van de mast|Ja (punt, lijn, vlak)|
|Status   | De fase van de levenscyclus waarin de mast zich bevindt|Ja   |
|Type mast|De aanduiding van het soort mast |Ja|




**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland|	
|Bestaand|	
|Verwijderd|
|Niet gerealiseerd|
|Ten onrechte|




#### Straatmeubilair

Dit SOR-begrip maakt onderdeel uit van de NEN 3610-hoofdklasse "Constructie"

 

**Definitie**

| Naam  | Straatmeubilair  |
|---|---|
| Definitie | Constructie die ter inrichting van de openbare ruimte is bedoeld|
|Herkomst definitie  |  IMGeo 2.2  |
|Verplicht  | Nee  |
|Gevolgen afbakening  | Het betreft hier een subset van de bestaande populaties *bak*, *paal* en *straatmeubilair* zoals deze zijn opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van straatmeubilair|Ja |
|Geometrie|De geometrische representatie van de locatie van het straatmeubilair|Ja (punt)|
|Status   | De fase van de levenscyclus waarin het straatmeubilair zich bevindt|Ja   |
|Type straatmeubilair|De aanduiding van het soort straatmeubilair |Nee|




**Domeinwaarden**

<div class='note'>
    Het voorstel is om onderstaande typeringen van straatmeubilair in principe **niet** meer op te nemen in de SOR. 
    
    De onderstaande typeringen zijn vanuit de BGT overgenomen. De verwachting is dat niet alle typeringen terug zullen keren in de SOR. In de volgende fase zal worden bepaald welke typen straatmeubilair dit betreft.
</div>



*type straatmeubilair*

|Waarde Type straatmeubilair| Beschrijving   |
|---|---|
|afvalbak|Bak of korf in de openbare ruimte met een permanent karakter; bedoeld voor het verzamelen van (meestal los) afval|
|bloembak|Bak in de openbare ruimte met een permanent karakter, waarin planten of struiken zijn geplant|
|zand-/zoutbak|Een bak met strooisel ten behoeve van gladheidsbestrijding|
|poller|Een inzinkbare paal die door een elektrische of hydraulische aandrijving uit een wegdek omhoog wordt gestuurd en die dient om het autoverkeer te reguleren|
|abri|Overdekte wachtplaats voor passagiers van het openbaar vervoer|
|brievenbus|Uitpandige kast waar post in kan worden gedeponeerd ter bezorging|
|fietsenrek|Een duurzaam verankerd rek in de openbare ruimte voor het stallen van (brom)fietsen|
|kunstobject|Een object dat als kunst gezien wordt en een bepaalde schoonheid heeft, niet door de natuur gemaakt|
|openbaar toilet|Voor mensen bedoeld toilet niet zijnde een pand, langs de openbare weg|
|slagboom|Boom of balk om de weg of een gedeelte hiervan af te sluiten|
|speelvoorziening|Aard en nagelvast met de grond verbonden constructie in de openbare ruimte, bedoeld als speelmateriaal voor kinderen|
|telefooncel|Niet-inpandige ruimte in openbaar gebied louter bestemd voor telefoneren|
|bank|Aaneengesloten zitplaats voor verscheidene personen, bedoeld voor openbaar gebruik en geplaatst in de openbare ruimte (vnl. in parken, plantsoenen, bossen en langs wegen)|
|picknicktafel|Een tafel met vaak daaraan gemonteerde zitbanken of stoelen die kan gebruikt worden om te picknicken|
|fontein|Een fontein is een natuurlijke of kunstmatige installatie die water spuit|
|lichtpunt|Een lichtpunt is een voorziening die licht uitzendt niet verbonden met een mast die het maaiveld raakt|
|parkeerbeugel|Een omklapbare beugel voor het afschermen van een parkeerplaats|
|betaalautomaat|Een apparaat dat betaalkaarten en/of contant geld accepteert om betalingen uit te voeren|
|fietsenkluis|Een kluis om een fiets in te bewaren, meestal ter voorkoming van diefstal of beschadiging|
|herdenkingsmonument|In het terrein aangelegd object ter herdenking van personen of evenementen|

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland|	
|Bestaand|	
|Verwijderd|
|Niet gerealiseerd|
|Ten onrechte|





#### Bunker

Dit SOR-begrip maakt onderdeel uit van de NEN 3610-hoofdklasse "Constructie"

 

**Definitie**

| Naam  | Bunker  |
|---|---|
| Definitie | Constructie die een van oorsprong militair verdedigingswerk betreft dat een zekere mate van bescherming bood tegen beschietingen en bombardementen|
|Herkomst definitie  | IMGeo 2.2    |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *bunker* zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een bunker|Ja |
|Geometrie|De geometrische representatie van de randen van een bunker|Ja (vlak)|
|Status   | De fase van de levenscyclus waarin de betreffende bunker zich bevindt|Ja   |





**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland|	
|Bestaand|	
|Verwijderd|
|Niet gerealiseerd|
|Ten onrechte|




