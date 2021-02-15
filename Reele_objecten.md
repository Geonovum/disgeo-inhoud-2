## Reele objecten

 

### Oppervlaktewater



#### Watervlakte

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Water"
 

**Definitie**

| Naam  | Watervlakte  |
|---|---|
| Definitie | Verlaging in het aardoppervlak van natuurlijke of kunstmatige oorsprong, die permanent of periodiek water bevat|
|Herkomst definitie  | AQUO lex    |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *watervlakte* en *zee* zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van een watervlakte|Ja |
|Geometrie|Geometrische representatie van een watervlakte|Ja (2,5D vlak)|
|Type watervlakte|Aanduiding van het soort watervlakte|Nee|
|Categorie | Geeft het belang van een watervlakte aan|
|Status   | Fase van de levenscyclus waarin een watervlakte zich bevindt|Ja   |


**Domeinwaarden**



*Type watervlakte*

|Waarde Type watervlakte| Beschrijving   |
|---|---|
|zee|Uitgestrekt oppervlak zout water|
|meer|Watervlakte (meestal zoet) die op natuurlijke wijze dan wel door menselijk ingrijpen (ingraving of afsluiting) is ontstaan|
|plas|Waterpartij, ontstaan door de winning van delfstoffen in dagbouw, die in contact staat met de vrije grondwaterspiegel|
|ven|Natuurlijk ontstaan meer op heidegrond|
|vijver|Gegraven waterpartij, aangelegd in stedelijke omgeving of in een parklandschap|

*Categorie*

|Waarde Categorie| Beschrijving   |
|---|---|
|Primair||
|Overig||

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd



#### Waterloop

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Water"

 

**Definitie**

| Naam  | Waterloop  |
|---|---|
| Definitie | Langgerekte verlaging in het aardoppervlak van natuurlijke of kunstmatige oorsprong die permanent of periodiek water bevat|
|Herkomst definitie  | AQUO lex    |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier grotendeels de bestaande populatie *waterloop* en *greppel/droge sloot* zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van een waterloop|Ja |
|Geometrie|Geometrische representatie van een waterloop|Ja (2,5D vlak)|
|Type waterloop|Aanduiding van het soort waterloop|Nee|
|Watervoerend | Aanduiding of de waterloop wel of geen water bevat| Ja|
|Categorie | Geeft het belang van een waterloop aan|
|Status   |  Fase van de levenscyclus waarin een waterloop zich bevindt|Ja   |


**Domeinwaarden**


*Type waterloop*

|Waarde Type waterloop| Beschrijving   |
|---|---|
|rivier|Water dat door atmosferische neerslag op hellende terreinen valt, vloeit, voor zover het niet verdampt of door planten wordt opgenomen, tezamen tot een waterloop en stroomt naar laaggelegen streken. Zulk een natuurlijke afvloeiing heet een rivier|
|sloot|Waterloop van beperkte breedte die stilstaand of langzaam stromend water bevat , welke is aangelegd met als doel het beheersen van het waterpeil|
|kanaal|Gegraven grote waterloop die dient voor scheepvaart en/of watertransport|
|beek|Natuurlijke smalle waterloop zonder getij, die veelal doorwaadbaar is en afwatert op een rivier|
|gracht|Gracht is een gegraven greppel met water, die hoofdzakelijk voorkomt in oude steden|

*Categorie*

|Waarde Categorie| Beschrijving   |
|---|---|
|Primair||
|Overig||


*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd



#### Bron

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Water"

 

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
|Identificatie   |Unieke aanduiding van een bron|Ja |
|Geometrie|Geometrische representatie van een bron|Ja (2,5D vlak)|
|Status   | Fase van de levenscyclus waarin een bron zich bevindt|Ja   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|is onderdeel van|watervlakte|ja|
|is onderdeel van|waterloop|ja|

**Domeinwaarden**

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd


#### Getijdengebied

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Water"

 

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
|Identificatie   |Unieke aanduiding van een getijdengebied|Ja |
|Geometrie|Geometrische representatie van een getijdengebied|Ja (2,5D vlak)|
|Type getijdengebied|Aanduiding van het soort getijdengebied|Nee|
|Status   | Fase van de levenscyclus waarin een getijdengebied zich bevindt|Ja   |

**Domeinwaarden**



*Type*

|Waarde Type getijdengebied| Beschrijving   |
|---|---|
|slik|Buitendijks aangeslibde, onbegroeide grond die bij vrijwel elk hoogwater onderloopt|
|schor|Buitendijks aangeslibd land, dat bij gewone vloed niet meer onderloopt en doorgaans begroeid is|

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd



### Begroeiing


#### Bos

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Begroeiing"


**Definitie**

| Naam  | Bos |
|---|---|
| Definitie |Begroeiing die een dusdanige aantal bomen betreft dat deze een min of meer gesloten geheel vormen of, na volgroeiing van de bomen, zullen vormen|
| Herkomst definitie  | Gebaseerd op de definities van bos in de BGT 1.2 en van Griend en Hakhout uit IMGeo 2.2 |
| Verplicht  | Ja, voor wat betreft loofbos, naaldbos en gemengd bos; Nee, voor wat betreft griend en hakhout |
|Gevolgen afbakening  | Het betreft hier grotendeels de bestaande populatie fysiek voorkomen *loofbos, naaldbos en gemengd bos* van *begroeid terreindeel* zoals deze is opgenomen in de basisregistratie grootschalige topografie aangevuld met fysiek voorkomen Griend en Hakhout zoals gedefinieerd in IMGeo 2.2 |
| Toelichting| De definitie van Bos laat voldoende ruimte voor plaatselijke aanwezigheid van struiken. De combinatie van reëel object Bos en bijvoorbeeld functioneel object Park en/of sectorregistraties (bv IMNA) kan voorzien in informatiebehoefte aan specifieke bostypen zoals 'bosplantsoen'.|

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   | Unieke aanduiding van een bos|Ja |
|Geometrie| Geometrische representatie van een bos|Ja (2,5D vlak)|
|Type bos| Aanduiding van het soort bos|Ja|
|Status   | Fase van de levenscyclus waarin een bos zich bevindt|Ja   |

**Domeinwaarden**

*Type*

|Waarde Type bos| Beschrijving   |
|---|---|
| loofbos |Terrein begroeid met een dusdanige aantal loofbomen dat deze een min of meer gesloten geheel vormen of, na volgroeiing van de bomen, zullen vormen| 
| naaldbos | Terrein begroeid met een dusdanige aantal naaldbomen dat deze een min of meer gesloten geheel vormen of, na volgroeiing van de bomen, zullen vormen| 
| gemengd bos | Terrein begroeid met een dusdanig aantal naald- en loofbomen dat deze een min of meer gesloten geheel vormen of, na volgroeiing van de bomen, zullen vormen|  
| griend en hakhout	| Vrijwillig te registreren terrein begroeid met loofbomen, in een dicht groeiverband die periodiek wordt ingekort|
 
*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd



####    Gras- en kruidachtigen

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Begroeiing"


**Definitie**

| Naam  |    Gras- en kruidachtigen |
|---|---|
| Definitie |Begroeiing die een laagblijvende, aaneengesloten gras- en/of kruidachtige vegetatie betreft|    
|Herkomst definitie  | IMBOR 2020 |
|Verplicht  | ja  |
|Gevolgen afbakening  | Het betreft hier grotendeels de bestaande populatie fysiek voorkomen *gras- en kruidachtigen*,*grasland agrarisch* en *grasland overig* zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting| Onderscheid in gras voor agrarisch gebruik, dan wel voor natuurlijk gebruik of 'overig ' gebruik is op basis van het nieuwe reëel object Gras- en kruidachtigen niet meer te zien. In sectormodel kan onderscheid gemaakt worden obv sector specifiek kenmerken. De combinatie van reëel object Gras- en kruidachtigen en  functioneel object Park of Sportterrein en/of sectorregistraties (bv IMNA, gewaspecelen, IMBOR) kan voorzien in informatiebehoefte aan specifieke grastypen zoals 'gazon', agrarisch/natuurlijk gras' of 'sportveld'.| 

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   | Unieke aanduiding van gras- en kruidachtigen|Ja |
|Geometrie| Geometrische representatie van veld met gras- en kruidachtigen|Ja (2,5D vlak)|
|Status   | Fase van de levenscyclus waarin een veld met gras- en kruidachtigen zich bevindt|Ja   |


**Domeinwaarden**

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd



####  Struiken

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Begroeiing"


**Definitie**

| Naam  | Struiken |
|---|---|
| Definitie |Begroeiing van bodembedekkers en/of houtachtige en/of meerstammige overblijvende planten, niet zijnde bomen of bos, niet zijnde gras- en kruidachtigen|   
|Herkomst definitie  |  BGT 1.2 |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie fysiek voorkomen *struiken*  zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting| Dit omvat alle begroeiing die niet valt onder de overige reële objecten onder Begroeiing| 

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   | Unieke aanduiding van struiken|Ja |
|Geometrie| Geometrische representatie van struiken|Ja (2,5D vlak)|
|Status   | Fase van de levenscyclus waarin struiken zich bevinden|Ja   |


**Domeinwaarden**

**Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd




#### Bouwland




Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Begroeiing"


**Definitie**

| Naam  | Bouwland  |
|---|---|
| Bouwland | Terrein in gebruik als akker, met gewassen die in een teelt-roulatieschema zijn opgenomen|
|Herkomst definitie  | Definitie gebaseerd op bouwland in de BGT 1.2 |
|Verplicht  | ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie fysiek voorkomen bouwland zoals deze is opgenomen in de basisregistratie grootschalige topografie. BRT-object "Braakliggend" wordt voor zover het landbouwgrond betreft ook in dit objecttype *Bouwland* opgenomen|
|Toelichting| Kan tijdelijk zonder gewas zijn of braak liggen|

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   | Unieke aanduiding van een bouwland|Ja |
|Geometrie| Geometrische representatie van bouwland|Ja (2,5D vlak)|
|Status   | Fase van de levenscyclus waarin een bouwland zich bevindt|Ja   |

**Domeinwaarden**

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd


#### Onbegroeide grond

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Begroeiing"


**Definitie**

| Naam  | Onbegroeide grond |
|---|---|
| Definitie |Terrein waar onbegroeide grond zichtbaar is|
| Herkomst definitie  | |
| Verplicht  | Ja  |
| Gevolgen afbakening  | Het betreft hier ten opzichte van de bestaande basisregistraties een nieuw objecttype, grotendeels het bestaande fysieke voorkomen  type *onverhard* van wegen en terreinen in de basisregistratie grootschalige topografie|
| Toelichting|Onbegroeide grond is grond, die niet bedekt is met enige vorm van begroeiing, constructie, water of verharding.  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van onbegroeide grond|Ja |
|Geometrie| Geometrische representatie van onbegroeide grond|Ja (2,5D vlak)|
|Status   | Fase van de levenscyclus waarin een stuk onbegroeide grond zich bevindt|Ja   |


**Domeinwaarden**

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd




####    Fruit- of kweekbomen

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Begroeiing"


**Definitie**

| Naam  | Fruit- of kweekbomen |
|---|---|
| Definitie |Begroeiing die het kweken van meerjarige siergewassen en bomen betreft ten behoeve van een later gebruik elders of voor het kweken van fruit|
|Herkomst definitie  | nieuw |
|Verplicht  | ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie fysiek voorkomen *fruitteelt* en *boomteelt* zoals deze is opgenomen in de basisregistratie grootschalige topografie. En de *Boomkwekerij*, *Fruitkwekerij* en *Boomgaard* zoals deze is opgenomen in de basisregistratie topografie. |
|Toelichting| De hier bedoelde kwekerijen onderscheiden zich van kwekerijen van potplanten door de langdurige stand/teelt van gewassen |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   | Unieke aanduiding van fruit- of kweekbomen|Ja |
|Geometrie| Geometrische representatie van fruit- of kweekbomen|Ja (2,5D vlak)|
|Type fruit- of kweekbomen| Aanduiding van het type fruit- of kweekbomen|Ja|
|Status   | Fase van de levenscyclus waarin fruit- of kweekbomen zich bevinden|Ja   |



**Domeinwaarden**

*Type* 

|Waarde Type fruit- of kweekbomen| Beschrijving   |
|---|---|
| laagstam boomgaarden |Terreindeel begroeid met laagstamfruitbomen|
| hoogstam boomgaarden |Terreindeel begroeid met hoogstamfruitbomen|
| wijngaarden|Terreindeel begroeid met druivenstokken voor wijnbouw|
| klein fruit |Terreindeel begroeid met heesters voor zacht fruit zoals bessen of frambozen|
| boomkwekerij |Terrein, overwegend in gebruik t.b.v. het opkweken van bomen (inclusief coniferen en sparren) en struiken, waarbij de hoogte van de aanplant niet van belang is|

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd


#### Natuurlijk groen 



MOERAS

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Begroeiing"

**Definitie**

| Naam  | Moeras |
|---|---|
| Definitie | Terreindeel met moerasvegetatie in stilstaand water van geringe diepte zonder merkbare toe- of afvloeiing. |
|Herkomst definitie  | BGT 1.2    |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *moeras*  zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|Het reëel object Moeras is opgenomen om de specifieke combinatie van water en kenmerkende moerasbegroeiing weer te geven ten behoeve van navigatie en toegankelijkheid. Deze gebieden kenmerken zich door een heel eigen verschijningsvorm, waarbinnen de begroeiing plaatselijk en tijdelijk kan veranderen, maar waar onderhoud gericht is op behoud van de typische verschijningsvorm van moerasland.  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van een Moeras|Ja |
|Geometrie|Geometrische representatie van een moeras|Ja (2,5D vlak)|
|Status   |  Fase van de levenscyclus waarin een moeras zich bevindt|Ja   |


**Domeinwaarden**

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd



RIETLAND

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Begroeiing"

**Definitie**

| Naam  | Rietland |
|---|---|
| Definitie |Terreindeel overwegend begroeid met rietvegetatie|
|Herkomst definitie  | BGT 1.2    |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *rietland*  zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting| Het reëel object Rietland is opgenomen om de specifieke combinatie van water en kenmerkende begroeiing weer te geven ten behoeve van navigatie en toegankelijkheid. Deze gebieden kenmerken zich door een heel eigen verschijningsvorm, waarbinnen de begroeiing plaatselijk en tijdelijk kan veranderen, maar waar onderhoud gericht is op behoud van de typische verschijningsvorm van rietland. |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van een Rietland|Ja |
|Geometrie|Geometrische representatie van een rietland|Ja (2,5D vlak)|
|Status   |  Fase van de levenscyclus waarin een rietland zich bevindt|Ja   |


**Domeinwaarden**

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd


HEIDE

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Begroeiing"

**Definitie**

| Naam  | Heide |
|---|---|
| Definitie | Terreindeel overwegend begroeid met heide en heideachtige vegetaties|
|Herkomst definitie  | BGT 1.2    |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *heide*  zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|Het reëel object Heide is opgenomen om de kenmerkende begroeiing weer te geven ten behoeve van navigatie en toegankelijkheid. Deze gebieden kenmerken zich door een heel eigen verschijningsvorm, waarbinnen de begroeiing plaatselijk en tijdelijk kan veranderen, maar waar onderhoud gericht is op behoud van de typische verschijningsvorm van heide  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van een heide|Ja |
|Geometrie|Geometrische representatie van een heide|Ja (2,5D vlak)|
|Status   |  Fase van de levenscyclus waarin een heide zich bevindt|Ja   |


**Domeinwaarden**

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd



#### Landschapselement


BOMENRIJ

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Begroeiing"

**Definitie**

| Naam  | Bomenrij |
|---|---|
| Definitie | Opgaande rijvormige begroeiing van bomen zonder ondergroei van struiken|
|Herkomst definitie  | BGT 1.2    |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *bomenrij*  zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting| Reëel object Bomenrij wordt net als Houtsingel en Haag opgenomen vanwege het landschappelijke belang van dit object. Het verschil tussen object Bomenrij en Houtsingel is de aanwezigheid van ondergroei van struiken in de Houtsingel en de afwezigheid daarvan in de Bomenrij. Het verschil tussen reëel object Bomenrij en Bos is dat de Bomenrij rijvormig is en dus een beperkte breedte heeft, terwijl het Bos breder is en eventueel ondergroei van struiken bevat. De aan- of afwezigheid van een aarden wal onder de bomenrij is buiten de definitie gelaten. In de specifieke informatiebehoefte aan Bomenrijen mét wallichaam kan worden voorzien door het reëel object Bomenrij te combineren met gegevens uit AHN |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van een Bomenrij|Ja |
|Geometrie|Geometrische representatie van een bomenrij|Ja (2,5D vlak)|
|Status   |  Fase van de levenscyclus waarin een bomenrij zich bevindt|Ja   |


**Domeinwaarden**

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd


HOUTSINGEL

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Begroeiing"

**Definitie**

| Naam  | Houtsingel |
|---|---|
| Definitie |Opgaande rijvormige begroeiing van bomen (enkelvoudige/meervoudige stammen) mét ondergroei van struiken|
|Herkomst definitie  | BGT 1.2    |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *houtwal*  zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting| Reëel object Houtsingel wordt net als Bomenrij en Haag opgenomen vanwege het landschappelijke belang van dit object. Het verschil tussen object Houtsingel en Bomenrij is de aanwezigheid van ondergroei van struiken in de Houtsingel en de afwezigheid daarvan in de Bomenrij. Het verschil tussen reëel object Houtsingel en Bos is dat de Houtsingel rijvormig is en dus een beperkte breedte heeft, terwijl het Bos breder is.  In de specifieke informatiebehoefte aan Houtsingels mét wallichaam kan worden voorzien door het reëel object Houtsingel te combineren met gegevens uit AHN. |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van een Houtsingel|Ja |
|Geometrie|Geometrische representatie van een houtsingel|Ja (2,5D vlak)|
|Status   |  Fase van de levenscyclus waarin een houtsingel zich bevindt|Ja   |


**Domeinwaarden**

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd


HAAG

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Begroeiing"

**Definitie**

| Naam  | Haag |
|---|---|
| Definitie | Rijvormige afscheiding van beperkte breedte bestaande uit aangeplante aaneengesloten struiken|
|Herkomst definitie  | BGT 1.2    |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *haag*  zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting| Reëel object Haag wordt net als Bomenrij en Houtsingel opgenomen vanwege het landschappelijke belang van dit object. Het object Haag onderscheidt zich van de objecten Houtsingel en Bomenrij door de afwezigheid van bomen. |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van een Haag|Ja |
|Geometrie|Geometrische representatie van een haag|Ja (2,5D vlak)|
|Status   |  Fase van de levenscyclus waarin een haag zich bevindt|Ja   |


**Domeinwaarden**

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd

TUUNWAL

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Begroeiing"

**Definitie**

| Naam  | Tuunwal |
|---|---|
| Definitie | Gestapelde grasplaggen op de scheiding tussen twee percelen|
|Herkomst definitie  | Nieuwe    |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft een nieuw op te nemen objecttype|
|Toelichting| Tuunwallen wijken duidelijk af van vegetatieve perceelsscheiding (heg, haag, bomenrij en houtsingel) en ook van de verschillende afscheidingen |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van een tuunwal|Ja |
|Geometrie|Geometrische representatie van een tuunwal|Ja (2,5D vlak)|
|Status   |  Fase van de levenscyclus waarin een tuunwal zich bevindt|Ja   |


**Domeinwaarden**

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd

#### Boom

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Begroeiing"


**Definitie**

| Naam  | Boom |
|---|---|
| Definitie | Solitaire boom die geen onderdeel uitmaakt van bos, bomenrij of houtsingel|
|Herkomst definitie  | IMGeo 2.2 |
|Verplicht  | nee  |
|Gevolgen afbakening  | nieuw object  |
|Toelichting| Reëel object Boom is opgenomen in het vrijwillige deel van de SOR, omdat verschillende organisaties uiteenlopende belangen hebben bij de registratie van bomen en omdat een eenduidige definitie van het object Boom nauwelijks is vast te stellen. |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van een boom|Ja |
|Geometrie| Geometrische representatie van een boom|Ja (2,5D punt)|
|Status   | Fase van de levenscyclus waarin een boom zich bevindt|Ja   |


**Domeinwaarden**


*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd



### Gebouw



#### Gebouw

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Gebouw"

**Definitie**

| Naam  | Gebouw  |
|---|---|
| Definitie | Overdekte en geheel of grotendeels met wanden omsloten constructief zelfstandige eenheid bedoeld voor het in een afgeschermde omgeving onderbrengen van mensen, dieren of voorwerpen of voor de productie van goederen|
|Herkomst definitie  |Gebaseerd op definitie “pand” in artikel 1 Wet basisregistratie adressen en gebouwen in de INSPIRE richtlijn |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier grotendeels de bestaande populatie panden zoals deze is opgenomen in de basisregistratie adressen en gebouwen en de basisregistratie grootschalige topografie. De bestaande definitie van het begrip pand is uitgebreid met een aantal elementen die zijn opgenomen in de INPIRE richtlijn. |
|Toelichting| In een later stadium zullen registratieregels worden opgesteld waarin een nadere invulling wordt gegeven aan de interpretatie die aan gebouw moet worden gegeven |



**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van een gebouw|Ja |
|Geometrie |Geometrische representatie van een gebouw   |Ja (3D)|
|Typering|Categorisering van een gebouw op basis van het constructief beoogde gebruik|Ja|
|Aard|Fysieke verschijningsvorm van een gebouw  |Ja|
|Oorspronkelijk bouwjaar | Aanduiding van het jaar waarin een gebouw oorspronkelijk als bouwkundig gereed is of zal worden opgeleverd|Ja|
|Naam| Breed geaccepteerde benaming van een gebouw zoals deze door de eigenaar is toegekend of zoals deze in de volksmond bekend staat| Nee|
|Status   |Fase van de levenscyclus waarin een gebouw zich bevindt    |Ja   |


**Domeinwaarden**


*Typering* 

|Waarde Typering|	Beschrijving|
|---|---|
|	|   |
|   |   |  	

Voorbeelden van gebouwen zijn flatgebouwen, kerkgebouwen, kastelen en watertorens. Ook alle kassen (met uitzondering van kleine hobby-kassen) worden aangemerkt als gebouwen, ongeacht de ondergrond van de kas.

*Aard*

|Waarde Aard|Beschrijving|
|---|---|
|Vrijstaand	|Gebouw dat niet is verbonden met een ander gebouw|
|Repeterend	|Gebouw dat onderdeel uitmaakt van een reeks aan elkaar verbonden gebouwen die als zodanig in één project zijn gerealiseerd|
|Heterogeen	|Gebouw dat onderdeel uitmaakt van een reeks aan elkaar verbonden gebouwen die onafhankelijk van elkaar zijn gerealiseerd|


*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd. De mate waarin alle genoemde statussen ook daadwerkelijk verplicht zullen worden en de regels omtrent interpretatie en overgang van statussen zullen in een later stadium nog gedetailleerder worden uitgewerkt in registratieregels.  Daarbij zal ook de aansluiting op de Omgevingswet verder worden aangescherpt. De status “in gebruik (niet ingemeten)” keert in de SOR niet als een afzonderlijke status terug. De mate waarin sprake is van definitieve geometrie zal door middel van meta-informatie bij de eigenschap geometrie worden vastgelegd.



#### Bouwlaag

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Gebouw"

**Definitie**

| Naam  | Bouwlaag  |
|---|---|
| Definitie | Verzameling van ruimten die zijn gelegen op hetzelfde niveau binnen een gebouw |
|Herkomst definitie  |Gebaseerd op de definitie van het begrip Bouwlaag (IfcBuildingStorey) uit de concepten rondom Bouwwerkinformatiemodellen (BIM)|
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier ten opzichte van de bestaande basisregistraties een nieuw objecttype |
|Toelichting| In een later stadium zullen registratieregels worden opgesteld waarin een nadere invulling wordt gegeven aan de interpretatie die aan bouwlaag moet worden gegeven|

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van een bouwlaag|Ja |
|Geometrie |Geometrische representatie van een bouwlaag  |Ja (2,5D)|
|Bouwlaagnummer |Niveau waarop een bouwlaag zich bevindt|Ja|
|Status   |Fase van de levenscyclus waarin een bouwlaag zich bevindt   |Ja   |


**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|Ligt in|Gebouw| Ja|

**Domeinwaarden**

*Bouwlaagnummer*

Voor de nummering van de bouwlaag geldt:
-	kelder = bouwlaagnummer -1
-	begane grond = bouwlaagnummer 0
-	eerste verdieping = bouwlaagnummer 1
-	tweede verdieping = bouwlaagnummer 2 


*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd. De mate waarin alle genoemde statussen ook daadwerkelijk verplicht zullen worden en de regels omtrent interpretatie en overgang van statussen zullen in een later stadium nog gedetailleerder worden uitgewerkt in registratieregels.  
	


#### Ruimte

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Gebouw"

**Definitie**

| Naam  | Ruimte  |
|---|---|
| Definitie | Voor mensen toegankelijk deel van een gebouw, dat ten minste aan de onderzijde en/of de bovenzijde wordt begrensd door een scheidingsconstructie en dat een netto-hoogte heeft van tenminste 1,5 m|
|Herkomst definitie  |Ontleend aan NEN 2580 en aansluitend op het begrip Ruimte (IfcSpace) uit de concepten rondom Bouwwerkinformatiemodellen (BIM)|
|Verplicht  | Nee  |
|Gevolgen afbakening  | Het betreft hier ten opzichte van de bestaande basisregistraties een nieuw objecttype |
|Toelichting| In een later stadium zullen registratieregels worden opgesteld waarin een nadere invulling wordt gegeven aan de interpretatie die aan ruimte moet worden gegeven |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van een ruimte|Ja |
|Geometrie |Geometrische representatie van een ruimte   |Ja (2,5D)|
|Bouwlaagnummer |Bouwlaag waarop een ruimte zich bevindt|Ja|
|Oppervlakte| Gebruiksoppervlakte van een ruimte| Nee |
|Typering|Categorisering van een ruimte op basis van het constructief beoogde gebruik| Ja|
|Status   |Fase van de levenscyclus waarin een ruimte zich bevindt   |Ja   |


**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|Ligt op|Bouwlaag| Ja|

**Domeinwaarden**

*Bouwlaagnummer*

Voor de nummering van de bouwlaag geldt:
-	kelder = bouwlaagnummer -1
-	begane grond = bouwlaagnummer 0
-	eerste verdieping = bouwlaagnummer 1
-	tweede verdieping = bouwlaagnummer 2


*Typering* 

|Waarde Typering|	Beschrijving|
|---|---|
|	|   |
|   |   |	


*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd. De mate waarin alle genoemde statussen ook daadwerkelijk verplicht zullen worden en de regels omtrent interpretatie en overgang van statussen zullen in een later stadium nog gedetailleerder worden uitgewerkt in registratieregels.  



#### Gebouwcomponent

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Gebouw"

**Definitie**

| Naam  | Gebouwcomponent  |
|---|---|
| Definitie | Component aan de buitenzijde van een gebouw, die het aanzicht van het gebouw mede bepaalt |
|Herkomst definitie  |IMGeo 2.2|
|Verplicht  | Deels (nog nader te bepalen welke onderdelen) |
|Gevolgen afbakening  |Het betreft hier grotendeels de bestaande populatie van *gebouwinstallatie* zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting| In een later stadium zullen inwinregels worden opgesteld die de minimale omvang van de vast te leggen objecten aangeeft. Ook zullen registratieregels worden opgesteld waarin een nadere invulling wordt gegeven aan de interpretatie die aan gebouwcomponenten moet worden gegeven |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van een gebouwcomponent|Ja |
|Geometrie |Geometrische representatie van een gebouwcomponent   |Ja (1D, 1,5D of 2,5D)|
|Aard|Soort gebouwcomponent|Ja |
|Bijbehorend object |Object waarbij een gebouwcomponent behoort|Ja|
|Status   |Fase van de levenscyclus waarin een gebouwcomponent zich bevindt   |Ja   |


**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|Hoort bij|Verblijfsobject|Ja|
|Hoort bij|Gebouw|Ja|

**Domeinwaarden**


*Aard*

| Waarde Aard| Beschrijving   |
|---|---|
|Dakkapel |Uitbouw van het schuine dakvlak|
|Afdak|Constructie aangebracht  en vast verbondenaan de gevel van een pand, gericht op beschutting tegen weersinvloeden |
|Bordes|Verhard oppervlak, eventueel verhoogd en/of uitgevoerd met treden, grenzen aan een pand en primair bedoeld voor gebruik door voetgangers|
|Toegangstrap|Buiten de gevel geplaatste trapconstructie die toegang biedt tot een gebouw en vast verbonden is met dat gebouw|

Voorbeelden van een afdak zijn: luifels en carports (die vast verbonden zijn met de gevel van een pand). Een afdak kan gedeeltelijk rusten op kolommen. Deze kolommen zijn dan echter uitsluitend ondersteunend aan de hangende hoofdconstructie.

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd. De mate waarin alle genoemde statussen ook daadwerkelijk verplicht zullen worden en de regels omtrent interpretatie en overgang van statussen zullen in een later stadium nog gedetailleerder worden uitgewerkt in registratieregels.  

#### Toegangsdeur

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Gebouw"

**Definitie**

| Naam  | Toegangsdeur |
|---|---|
| Definitie | Deur of andere voorziening die vanaf de openbare weg, een erf of een gedeelde verkeersruimte toegang geeft tot een object|
|Herkomst definitie  |Begrip sluit aan bij het begrip Deur (IfcDoor) uit de concepten rondom Bouwwerkinformatiemodellen (BIM)|
|Verplicht  | Deels (nog nader te bepalen welke onderdelen) |
|Gevolgen afbakening  | Het betreft hier ten opzichte van de bestaande basisregistraties grotendeels een nieuw objecttype|
|Toelichting| In een later stadium zullen registratieregels worden opgesteld waarin een nadere invulling wordt gegeven aan de interpretatie die aan toegangsdeur moet worden gegeven |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van een toegangsdeur|Ja |
|Geometrie |Geometrische representatie van een toegangsdeur   |Ja (1,5D)|
|Toegangssoort|Plaats waarvan een toegangsdeur toegang geeft|Ja|
|Gebruiksaard|Aard van gebruik van een toegangsdeur|Ja|
|Bijbehorend object |Object waarin een toegangsdeur zich bevindt|Ja|
|Status   |Fase van de levenscyclus waarin een toegangsdeur zich bevindt   |Ja   |


**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|Hoort bij|Verblijfsobject| Ja|
|Hoort bij|Gebouw| Ja|

**Domeinwaarden**

*Toegangssoort*

| Waarde Toegangssoort| Beschrijving   |
|---|---|
|Directe toegang vanaf eigen terrein|Toegangsdeur bevindt zich op een erf, in een tuin of een andere specifiek terrein dat behoort bij het gebouw |
|Directe toegang vanaf openbare weg|Toegangsdeur bevindt zich direct aan een voor iedereen toegankelijke weg |
|Toegang vanaf gemeenschappelijke verkeersruimte |Toegangsdeur bevindt zich aan een inpandige ruimte die bedoeld is voor verplaatsingen door een gebouw door de verschillende gebruikers van dit gebouw  |

*Gebruiksaard*

| Waarde Gebruiksaard| Beschrijving   |
|---|---|
|Personen|Toegangsdeur is primair bedoeld voor toegang tot een object door personen |
|Auto|Toegangsdeur is primair bedoeld voor toegang tot een object door voertuigen |
|Vracht|Toegangsdeur is primair bedoeld voor toegang tot een object door vracht zonder gebruik van een voertuig|

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd. De mate waarin alle genoemde statussen ook daadwerkelijk verplicht zullen worden en de regels omtrent interpretatie en overgang van statussen zullen in een later stadium nog gedetailleerder worden uitgewerkt in registratieregels.  


#### Open bouwwerk


Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Constructie"

**Definitie**

| Naam  | Open bouwwerk |
|---|---|
| Definitie | Afzonderlijk staande overdekking rustend op een constructie met kolommen met één of meerdere open gevels bedoeld voor het beschutten of stallen van mensen, dieren, objecten en/of voer- en vaartuigen |
|Herkomst definitie  |Gebaseerd op definities “open loods” en “overkapping” uit de gegevenscatalogus BGT|
|Verplicht  | Ja |
|Gevolgen afbakening  |Het betreft hier grotendeels de bestaande populatie open loodsen en overkappingen zoals deze is opgenomen in de basisregistratie adressen en gebouwen en de basisregistratie grootschalige topografie |
|Toelichting| In een later stadium zullen de inwinregels worden opgesteld die de minimale omvang van de vast te leggen objecten en de eventuele kolommen aangeeft. Ook zullen registratieregels worden opgesteld waarin een nadere invulling wordt gegeven aan de interpretatie die aan open bouwwerken moet worden gegeven |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van een open bouwwerk|Ja |
|Geometrie |Geometrische representatie van een open bouwwerk   |Ja (3D)|
|Typering| Soort open bouwwerk|Ja|
|Status   |Fase van de levenscyclus waarin een  open bouwwerk zich bevindt   |Ja   |




**Domeinwaarden**

*Typering*

|Waarde typering| Beschrijving|
|---|---|
|Overkapping|Afzonderlijk staande overdekking rustend op kolommen|
|Open loods|Niet verplaatsbaar licht gebouw met een open gevel, bestemd als berg- of werkplaats of als tijdelijk onderdak voor andere doeleinden|
|Parkeergarage|Open constructie die geheel of gedeeltelijk in gebruik is als voorziening voor het parkeren van voertuigen|

Voorbeelden van open bouwwerken met typering overkapping zijn: losstaande carports, buitenkeukens, open tuinhuizen en tribunes. Bij open loodsen gaat het onder meer om open frontstallen, dierenverblijven, hobbykassen en boothuizen. Parkeergarages die zich in een gebouw bevinden maken onderdeel uit van het gebouw. Parkeergarages die bestaan uit een open (staal) constructie behoren tot de open bouwwerken. Het kan daarbij zowel gaan om parkeergarages voor motorvoertuigen als grotere parkeervoorzieningen voor fietsers. 

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd. De mate waarin alle genoemde statussen ook daadwerkelijk verplicht zullen worden en de regels omtrent interpretatie en overgang van statussen zullen in een later stadium nog gedetailleerder worden uitgewerkt in registratieregels.  




### Verharding


Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Verharding"

 

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
|Identificatie   |Unieke aanduiding van een verharding|Ja |
|Geometrie|Geometrische representatie van een verhardingsvlak|Ja (vlak, 2.5D)|
|Type verharding|Aanduiding van het soort verharding|Ja|
|Status   | Fase van de levenscyclus waarin een verhardingsvlak zich bevindt|Ja   |


**Domeinwaarden**


*Type verharding*

|Waarde Type verharding| Beschrijving   |
|---|---|
| Asfaltverharding|Gesloten verharding bestaande uit asfaltbeton of andere met bitumen gebonden materialen|
| Betonverharding |Gesloten verharding bestaande uit gewapend of ongewapend beton|
| Elementenverharding|Open verharding opgebouwd uit losse elementen die in meer of mindere mate met elkaar verbonden zijn|
| Halfverharding|Open verharding bestaande uit onsamenhangend materiaal dat meer draagkracht levert dan de originele grond|
| Kunststofverharding|Verharding bestaande uit een synthetisch vervaardigd materiaal|
| Onverhard| Verharding met een vorm van natuurlijk fundament en een bovenlaag bestaande uit natuurlijke materialen met een onverhard karakter|

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd

 

### Kunstwerk
#### Overbrugging

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Kunstwerk"

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
|Identificatie   |Unieke aanduiding van overbrugging|Ja |
|Geometrie|Geometrische representatie van een overbrugging|Ja (vlak, 2.5D)|
|Type overbrugging|Aanduiding van het soort overbrugging|Ja|
|Naam| Breed geaccepteerde benaming van een overbrugging zoals deze door de eigenaar is toegekend of zoals deze in de volksmond bekend staat| Nee|
| Beweegbaar  |Aanduiding of overbrugging beweegbaar is (open en dicht kan) |Ja|
|Status   | Fase van de levenscyclus waarin een overbrugging zich bevindt|Ja   |



**Domeinwaarden**


*Type overbrugging* 

|Waarde Type overbrugging| Beschrijving   |
|---|---|
| brug |Overbruggingsconstructie over een watervlakte of waterloop, bedoeld voor verkeer|
| aquaduct |Overbruggingsconstructie waarmee een watergang door een bakvormige constructie over een weg, een spoorweg, een andere watergang, een leiding of een terrein wordt geleid|
| viaduct |Overbruggingsconstructie over een weg, spoorweg of terreinverdieping, bedoeld voor verkeer|
| ecoduct |Overbruggingsconstructie over een weg of spoorweg,  bedoeld voor het passeren van dieren|
| flyover|Kunstwerk in de vorm van een viaduct dat deel uitmaakt van een verkeersbaan en waarmee een verkeersstroom over twee of meer ongelijkvloerse verkeersstromen wordt geleid |
| overkluizing |Civieltechnisch kunstwerk waarmee een weg, een plein of een waterloop (kruiselings) wordt overwelfd, waarbij het dek meestal niet uitsluitend uit een pad of weg bestaat|

*Type beperking*

|Waarde Beperking| Beschrijving   |
|---|---|
| doorrijhoogte | Maximale doorrijhoogte tussen het wegdek en de constructie boven het wegdek geldend op een weg, rijbaan of rijstrook (afhankelijk van het type verbinding)|
| doorrijbreedte| Maximale doorrijbreedte tussen de dichtstbij gelegen objecten aan weerszijden van de weg, rijbaan, rijstrook(afhankelijk van het type verbinding)|
| toegestane massa|Toegestane massa op een kunstwerk/verharding|
| toegestane lengte|Toegestane lengte op een locatie van de weg, rijbaan, rijstrook (afhankelijk van het type verbinding)|
| doorvaarhoogte |Hoogte die beschikbaar is tussen water en de constructies welke boven het water aanwezig zijn|


*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd


#### Kunstwerkdeel

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Kunstwerk"

 

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
|Identificatie   |Unieke aanduiding van een kunstwerkdeel|Ja |
|Geometrie|Geometrische representatie van een kunstwerkdeel|Ja (vlak, 2.5D|
|Type kunstwerkdeel| Aanduiding van het soort kunstwerkdeel|ja|
|Status   |  Fase van de levenscyclus waarin een kunstwerkdeel zich bevindt|Ja   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
| is onderdeel van| kunstwerk, type overbrugging | ja|
| is onderdeel van | kunstwerk, type sluis | ja|

**Domeinwaarden**


*Type kunstwerkdeel*

|Waarde Type kunstwerkdeel| Beschrijving   | is onderdeel van|
|---|---|---|
| dek |Direct door het verkeer belaste deel van de bovenbouw van de brug| overbrugging|
| landhoofd |Ondersteuningsconstructie ter plaatse van een overgang van de aardebaan naar een kunstwerk|overbrugging|
| pijler |Ondersteuningsconstructie van bruggen en soortgelijke kunstwerken|overbrugging|
| sloof |Deel van de pijler voor de overdracht van krachten naar de ondergrond of de fundering|overbrugging|
| pyloon |Boven de bovenbouw uitstekende draagconstructie voor tuien (kabels)|overbrugging|
| sluisdeur |Beweegbare deur die wordt toegepast bij (hoog)waterkeringen en sluizen om het niveauverschil aan beide zijden in stand te houden| sluis|
| schutkolk |Deel van de sluis waarin de te schutten schepen afmeren en op een hoger of lager niveau worden gebracht|sluis|
| vuilvang | Voorziening om de waterloop dan wel één of meerdere objecten benedenstrooms te vrijwaren van drijvend vuil en dergelijke| |

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd


#### Ondertunneling


Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Kunstwerk"

 

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
|Identificatie   |Unieke aanduiding van een ondertunneling|Ja |
|Geometrie|Geometrische representatie van een ondertunneling|Ja (vlak, 2.5D)|
|Type ondertunneling| Aanduiding van het soort ondertunneling|Ja|
|Naam| Breed geaccepteerde benaming van een ondertunneling zoals deze door de eigenaar is toegekend of zoals deze in de volksmond bekend staat| Nee|
|Status   | Fase van de levenscyclus waarin een ondertunneling zich bevindt|Ja   |


**Domeinwaarden**


*Type ondertunneling*

|Waarde Type ondertunneling| Beschrijving   |
|---|---|
| tunnel |Kokervormig kunstwerk onder een of meer wegen, spoorwegen, waterwegen en/of andere hindernissen, als ondergrondse doorgang voor verkeer, leidingen of dieren|
| duiker |Kunstwerk voor de waterhuishouding, bestaande uit een gesloten kokervormige constructie met een in- en uitstroomopening, die niet de gehele waterbreedte beslaand, aangebracht onder een weg of spoorweg of in een dam of ander terreindeel en de bodem van de waterloop onderbreekt|

*Type beperking*

|Waarde Beperking| Beschrijving   |
|---|---|
| doorrijhoogte | Maximale doorrijhoogte tussen het wegdek en de constructie boven het wegdek geldend op een weg, rijbaan of rijstrook (afhankelijk van het type verbinding)|
| doorrijbreedte| Maximale doorrijbreedte tussen de dichtstbij gelegen objecten aan weerszijden van de weg, rijbaan, rijstrook(afhankelijk van het type verbinding)|
| toegestane massa|Toegestane massa op een kunstwerk/verharding|
| toegestane lengte|Toegestane lengte op een locatie van de weg, rijbaan, rijstrook (afhankelijk van het type verbinding)|

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd




#### Waterstaatkundig kunstwerk


Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Kunstwerk"

**Definitie**

| Naam  | Waterstaatkundig kunstwerk |
|---|---|
| Definitie | Kunstwerk dat kerende functie heeft|
|Herkomst definitie  | nieuw  |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier grotendeels de bestaande populatie zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting| De kerende functie kan worden vastgelegd middels de functionele ruimte "kering" van het type "water" |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van een waterstaatkundig kunstwerk|Ja |
|Geometrie|Geometrische representatie van een waterstaatkundig kunstwerk|Ja (vlak, 2.5D)|
|Type kerend kunstwerk| Aanduiding van het soort waterstaatkundig kunstwerk|Ja|
|Status   | Fase van de levenscyclus waarin een waterstaatkundig kunstwerk zich bevindt|Ja   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
| heeft mogelijk een functie| kering| Ja|


**Domeinwaarden**



*Type waterstaatkundig kunstwerk*

|Waarde type waterstaatkundig kunstwerk| Beschrijving   |
|---|---|
| keermuur |muur die door vorm, gewicht en fundering zonder verankering de grond keert|
| kademuur |Grondkerende constructie tegen afkalving van de walkant, in de vorm van een verticale wand ter scheiding van land en water, opgebouwd uit een muur van gemetselde stenen of gestort beton|
| damwand |Grondkerende of waterkerende constructie bestaande uit (nagenoeg) verticaal in de grond aangebrachte elementen die door middel van een langsprofiel in elkaar grijpen|
| walbescherming |Nagenoeg verticale wand tot kering van grond om afkalving van water te voorkomen, niet zijnde een kademuur|
| schot|Permanente afscheiding, verticaal in het water geplaatst, bedoeld om het waterpeil van het aan beide zijden aanwezige water te regelen|
| stuw |Vaste of beweegbare constructie in het water die dient om de waterstand bovenstrooms en/of benedenstrooms van de constructie te regelen  |
| sluis |Kunstmatige, afsluitbare waterkering die een scheepvaartverbinding tussen twee wateren met verschillende waterpeilen mogelijk maakt|
| coupure |Onderbreking in een waterkering voor de doorvoer van een weg of spoorweg, die bij extreme waterstanden afsluitbaar is|
| dijk|Aangelegde waterkering, die het achterliggende land beschermt tegen overstromingen|
| stormvloedkering|Keersluis die gesloten wordt bij zeer hoge buitenwaterstanden|
| gemaal | Kunstwerk in principe bedoeld om water van een laag peil naar een hoog peil te brengen|
| bezinkbak| Gesloten reservoir waarin het afvalwater tijdelijk wordt opgevangen met een slibreinigende voorziening|
| strekdam | Dam in de richting van de loop van de rivier of kanaal, ter beveiliging van de oevers of brugpijlers of ter beheersing van de rivier|
| steiger |Vaste (niet drijvende) waterbouwkundige constructie, verbonden met de wal, voor het aanleggen van schepen en bedoeld om deze schepen vanaf de wal te laden en te lossen|
| vispassage |Waterbouwkundig constructie dat tot doel heeft vissen toegang te bieden tot een door een kunstwerk onbereikbaar geworden achterland|
| bodemval |Sprong in de bodem van een waterloop|
| ponton |Vastliggend drijflichaam, dat dienst doet als aanlegplaats van vaartuigen of daartoe toegang geeft|
| voorde |Doorwaadbare, doorgaans verharde, plaats in de waterloop, die dient voor de oversteek van die waterloop|

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd








### Overige constructies



#### Muur
  

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Constructie"

 
**Definitie**

| Naam  | Muur |
|---|---|
| Definitie |Constructie die een relatief smal, rechtopstaand bouwwerk betreft||Herkomst definitie  |Gebaseerd op Basisregistratie Topografie: Catalogus en Productspecificaties (versie 1.2.0.1)|
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier grotendeels de bestaande populatie  *scheidingen, Type muur* zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|   |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
| Identificatie   |Unieke aanduiding van een muur|Ja |
| Geometrie|Geometrische representatie van een muur|Ja (2,5D lijn) Nee (2,5D vlak)|
|Status   | Fase van de levenscyclus waarin een muur zich bevindt|Ja   |

**Domeinwaarden**

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd



#### Omheining


Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Constructie"

 

**Definitie**

| Naam  | Omheining |
|---|---|
| Definitie | Kunstmatige verticale constructie die bedoeld is om de toegang tot een gebied te weren|
|Herkomst definitie  |nieuw|
|Verplicht  | Nee |
|Gevolgen afbakening  | Het betreft hier grotendeels de bestaande populatie  *scheidingen, Type hek en Type draadraster, faunaraster* zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van een omheining|Ja |
|Geometrie|Geometrische representatie van een omheining|Ja (2,5D lijn)|
|Status   | Fase van de levenscyclus waarin een omheining zich bevindt|Ja   |

**Domeinwaarden**

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd



#### Scherm
  

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Constructie"

 

**Definitie**

| Naam  | Scherm |
|---|---|
| Definitie |Lineaire constructie specifiek bedoeld om te reduceren|
|Herkomst definitie  |nieuw|
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier grotendeels de bestaande populatie  *scheidingen, Type geluidscherm* zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van een scherm|Ja |
|Geometrie|Geometrische representatie van een scherm|Ja (2,5D lijn)|
|Type scherm| Aanduiding van soort scherm |Ja| 
|Status   | Fase van de levenscyclus waarin een scherm zich bevindt|Ja   |

**Domeinwaarden**


*Type*

|Waarde Type Scherm| Beschrijving   |
|---|---|
|geluid|voorziening bedoeld om geluidshinder in de buitenlucht te verminderen|
|fijnstof|voorziening bedoeld om verspreiding van fijnstof te verminderen|


*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd




#### Afvalcontainer

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Constructie"

 

**Definitie**

| Naam  | Afvalcontainer  |
|---|---|
| Definitie | Constructie met een permanent karakter die dient om iets in te bergen of te verzamelen|
|Herkomst definitie  | Gebaseerd op IMGeo 2.2  |
|Verplicht  | Nee  |
|Gevolgen afbakening  | Het betreft hier een subset van de bestaande populatie *bak* zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van een afvalcontainer|Ja |
|Geometrie|Geometrische representatie van een afvalcontainer|Ja (2,5D punt) Nee (2,5D vlak)|
|Status   | Fase van de levenscyclus waarin een afvalcontainer zich bevindt|Ja   |

**Domeinwaarden**

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd





#### Bassin

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Constructie"

 

**Definitie**

| Naam  | Bassin  |
|---|---|
| Definitie | Constructie in de vorm van een bekken met een ondoorlaatbare bodem waarin water opgeslagen kan worden|
|Herkomst definitie  |gebaseerd op BGT 1.2 |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie overig bouwwerk, type bassin zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van een bassin|Ja |
|Geometrie|Geometrische representatie van een bassin|Ja (2,5D vlak)|
|Status   | Fase van de levenscyclus waarin een bassin zich bevindt|Ja   |

**Domeinwaarden**

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd



#### Opslagtank

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Constructie"

 

**Definitie**

| Naam  | Opslagtank  |
|---|---|
| Definitie | Constructie in de vorm van een bovengronds, afgesloten reservoir bestemd is voor gassen, energie of vloeistoffen|
|Herkomst definitie  | IMGeo 2.2  |
|Verplicht  | Nee  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie overig bouwwerk, type opslagtank zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van een opslagtank|Ja |
|Geometrie|Geometrische representatie van een opslagtank|Ja (2,5D vlak)|
|Status   | Fase van de levenscyclus waarin een opslagtank zich bevindt|Ja   |

**Domeinwaarden**

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd



#### Putdeksel

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Constructie"

 

**Definitie**

| Naam  | Putdeksel  |
|---|---|
| Definitie | Afsluitende deel van een toegang tot een ingegraven constructie  of netwerk|
|Herkomst definitie  |   Afgeleid van de definitie van een put in IMGeo 2.2 |
|Verplicht  | Ja (2,5D punt)  |
|Gevolgen afbakening  | Het betreft hier een samenvoeging van de bestaande populatie *put* en van een subset van de bestaande populatie *weginrichtingselementen* zoals deze zijn opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van een putdeksel|Ja |
|Geometrie|Geometrische representatie van een putdeksel|Ja (punt, lijn, vlak)|
|Status   | Fase van de levenscyclus waarin een putdeksel zich bevindt|Ja   |

**Domeinwaarden**

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd




#### Geleider

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Constructie"
 

**Definitie**

| Naam  | Geleider  |
|---|---|
| Definitie | Constructie bedoeld voor de fysieke (be-)geleiding van voer- of vaartuigen|
|Herkomst definitie  | nieuw    |
|Verplicht  | Nee  |
|Gevolgen afbakening  | Het betreft hier een samenvoeging van een subset van de bestaande populaties *waterinrichtingselementen* en *weginrichtingselementen* zoals deze zijn opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van een geleider|Ja |
|Geometrie|Geometrische representatie van de ligging van de geleider|Ja (lijn, vlak)|
|Status   | Fase van de levenscyclus waarin een geleider zich bevindt|Ja   |

**Domeinwaarden**

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd



#### Installatie

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Constructie"

 

**Definitie**

| Naam  | Installatie  |
|---|---|
| Definitie | Constructie die een technisch samenhangend systeem betreft dat een bepaald doel dient|
|Herkomst definitie  | Gebaseerd op installatie in IMGeo 2.2  |
|Verplicht  | Afhankelijk van type installatie|
|Gevolgen afbakening  | Het betreft hier de bestaande populaties  *installatie* zoals deze zijn opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|  |



**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van een installatie|Ja |
|Geometrie|Geometrische representatie van de installatie|Ja (punt, lijn, vlak)|
|Type installatie| Aanduiding van het soort installatie|Ja|
|Status   | Fase van de levenscyclus waarin een installatie zich bevindt|Ja   |


**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|hoort bij|gebouw|ja|



**Domeinwaarden**

*Type* 

|Waarde Type installatie| Beschrijving   |
|---|---|
|**verplicht**||
|sirene|Installatie welke geluiden van variabele toonhoogte kan voortbrengen met als functie waarschuwingsdoeleinden|
|verkeerslicht|Installatie bedoeld om het verkeer te regelen|
|openbare verlichting|Installatie bedoeld voor verlichten van de openbare ruimte|
|kast|Constructie met een permanent karakter dat dient om iets in te bergen en te beschermen|
|**vrijwillig**||
|pomp|Technische inrichting om vloeistoffen en/of gassen te verplaatsen|
|zonnepanelen| Installatie om zonne-energie om te zetten in energie |
|lift| Installatie gericht op het verticaal vervoeren van personen en goederen|
|windturbine|Turbine waarin winddruk omgezet wordt in mechanische energie|
|oplaadpunt| Systeem voor opladen van elektrische auto's |


*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd




#### Mast

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Constructie"

 

**Definitie**

| Naam  | Mast  |
|---|---|
| Definitie | Hoge draagconstructie voor een installatie of het transport van energie en elektromagnetische straling |
|Herkomst definitie  |  nieuw   |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier een samenvoeging van een subset van de bestaande populaties *overig bouwwerk, kunstwerkdeel en mast* zoals deze zijn opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van een mast|Ja |
|Geometrie|Geometrische representatie van de mast|Ja (punt, multipunt , lijn, vlak of multivlak )|
|Status   | Fase van de levenscyclus waarin een mast zich bevindt|Ja   |

**Domeinwaarden**

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd



#### Paal

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Constructie"

 

**Definitie**

| Naam  | Paal  |
|---|---|
| Definitie | Lage draagconstructie voor onder meer installaties of borden |
|Herkomst definitie  |  nieuw |
|Verplicht  | Nee  |
|Gevolgen afbakening  | Het betreft hier een samenvoeging van een subset van de bestaande populaties palen en borden zoals deze zijn opgenomen in de basisregistratie grootschalige topografie |
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van paal|Ja |
|Geometrie|Geometrische representatie van de paal|Ja (2,5D punt)|
|Status   | Fase van de levenscyclus waarin een paal zich bevindt|Ja   |

**Domeinwaarden**

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd



#### Straatmeubilair

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Constructie"

 

**Definitie**

| Naam  | Straatmeubilair  |
|---|---|
| Definitie | Constructie ter inrichting van de openbare ruimte niet verbonden met ondergrondse objecten|
|Herkomst definitie  |  Gebaseerd op IMGeo 2.2  |
|Verplicht  | Nee  |
|Gevolgen afbakening  | Het betreft hier een subset van de bestaande populaties *bak* en *straatmeubilair* zoals deze zijn opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van straatmeubilair|Ja |
|Geometrie|Geometrische representatie van het straatmeubilair|Ja (2,5D punt)|
|Status   | Fase van de levenscyclus waarin straatmeubilair zich bevindt|Ja   |

**Domeinwaarden**

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd



#### Bunker

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Constructie"

 

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
|Identificatie   |Unieke aanduiding van een bunker|Ja |
|Geometrie|Geometrische representatie van een bunker|Ja (2,5D vlak)|
|Status   | Fase van de levenscyclus waarin een bunker zich bevindt|Ja   |

**Domeinwaarden**

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd





### Onbepaald terrein


 

**Definitie**

| Naam  | Onbepaald terrein  |
|---|---|
| Definitie | Fysiek begrensd en zichtbaar terrein dat bij een gebouw hoort, dat niet nader wordt ingewonnen en dat bestaat uit een mengvorm van bodem, begroeiing, verharding en/of water|
|Herkomst definitie  | Gebaseerd op definitie van erf in BGT    |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *Erf* zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting| In plaats van onbepaald terreindeel kan ter plaatse ook de Reële topografie worden ingewonnen (vrijwillig)|

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van een onbepaald terrein|Ja |
|Geometrie|Geometrische representatie van een onbepaald terrein|Ja (2,5D vlak)|
|Status   |Fase van de levenscyclus waarin een onbepaald terrein zich bevindt|Ja   |



**Domeinwaarden**

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd

