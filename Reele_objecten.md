## Reële objecten 

### Oppervlaktewater

#### Watervlakte

Dit SOR-begrip is een nader type van de NEN 3610- hoofdklasse Oppervlaktewater.

**Definitie**

| Naam    | Watervlakte    |
|---|---|
| Definitie | Een niet langgerekte verlaging in het aardoppervlak van natuurlijke of kunstmatige oorsprong, die permanent of periodiek water bevat|
|Herkomst definitie    | gebaseerd op Aquo-standaard    |
|Verplicht    | Ja    |
|Gevolgen afbakening    | Het betreft hier grotendeels de bestaande populatie *watervlakte* en *zee* zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting| Het betreft hier enkel het aanwezige water bij het voorgeschreven waterpeil. Het bij dit waterpeil droog liggende gedeelte van de oever valt niet binnen de afbakening van dit object.    |

**Eigenschappen**

|Eigenschap     |Beschrijving     |Verplicht     |
|---|---|---|
|Identificatie     |Unieke aanduiding van een watervlakte|Ja |
|Geometrie|Geometrische representatie van een watervlakte|Ja (2,5D vlak)|
|Type |Typering van een watervlakte|Nee|
|Indicatie Primair | Deze watervlakte is al dan niet een hoofdverbinding in het watersysteem|Ja|
|Status     | Fase van de levenscyclus waarin een watervlakte zich bevindt|Ja     |


**Domeinwaarden**



*Type*

|Waarde Type | Beschrijving Type |
|---|---|
|Meer|Watervlakte (meestal zoet) die op natuurlijke wijze dan wel door menselijk ingrijpen (ingraving of afsluiting) is ontstaan|
|Plas|Waterpartij, ontstaan door de winning van delfstoffen in dagbouw, die in contact staat met de vrije grondwaterspiegel|
|Ven|Natuurlijk ontstaan meer op zandgrond|
|Vijver|Gegraven waterpartij, aangelegd in stedelijke omgeving of in een parklandschap|
|Zee|Uitgestrekt oppervlak zout water|


*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd



#### Watergang

Dit SOR-begrip is een nader type van de NEN 3610- hoofdklasse Oppervlaktewater.
 
**Definitie**

| Naam    | Watergang    |
|---|---|
| Definitie | Langgerekte verlaging in het aardoppervlak van natuurlijke of kunstmatige oorsprong die permanent of periodiek water bevat|
|Herkomst definitie    | AQUO lex |
|Verplicht    | Ja    |
|Gevolgen afbakening    | Het betreft hier grotendeels de bestaande populatie *waterloop* en *greppel/droge sloot* zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting| Het betreft hier enkel het aanwezige water bij het voorgeschreven waterpeil. Het bij dit waterpeil droog liggende gedeelte van de oever valt niet binnen de afbakening van dit object.   |

**Eigenschappen**

|Eigenschap     |Beschrijving     |Verplicht     |
|---|---|---|
|Identificatie     |Unieke aanduiding van een watergang|Ja |
|Geometrie|Geometrische representatie van een watergang|Ja (2,5D vlak)|
|Type |Aanduiding van het soort watergang|Nee|
|Watervoerend | Aanduiding of de watergang wel of geen water bevat| Ja|
|Indicatie Primair | Deze watergang is al dan niet een hoofdverbinding in het watersysteem|Ja|
|Status     |    Fase van de levenscyclus waarin een watergang zich bevindt|Ja     |


**Domeinwaarden**


*Type*

|Waarde Type | Beschrijving Type     |
|---|---|
|Beek|Natuurlijke smalle watergang zonder getij, die veelal doorwaadbaar is en afwatert op een rivier|
|Gracht|Gegraven watergang die hoofdzakelijk voorkomt in oude steden|
|Kanaal|Gegraven grote watergang die dient voor scheepvaart en/of watertransport|
|Rivier|Water dat door atmosferische neerslag op hellende terreinen valt, vloeit, voor zover het niet verdampt of door planten wordt opgenomen, tezamen tot een watergang en stroomt naar laaggelegen streken|
|Sloot|Watergang van beperkte breedte die stilstaand of langzaam stromend water bevat, en die is aangelegd met als doel het beheersen van het waterpeil|



*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd



#### Bron

Dit SOR-begrip is een nader type van de NEN 3610- hoofdklasse Oppervlaktewater.
 

**Definitie**

| Naam    | Bron    |
|---|---|
| Definitie | Grondwater dat op natuurlijke wijze uit het aardoppervlak tevoorschijn komt|
|Herkomst definitie    | IMGeo 2.2     |
|Verplicht    | Nee    |
|Gevolgen afbakening    | Het betreft hier de bestaande populatie *waterloop; Type bron*    zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|    |

**Eigenschappen**

|Eigenschap     |Beschrijving     |Verplicht     |
|---|---|---|
|Identificatie     |Unieke aanduiding van een bron|Ja |
|Geometrie|Geometrische representatie van een bron|Ja (2,5D vlak)|
|Status     | Fase van de levenscyclus waarin een bron zich bevindt|Ja     |

**Relaties met andere objecttypen** 

|Relatiesoort     |Relatierol |Verplicht|
|---|---|---|
|is onderdeel van|watervlakte|ja|
|is onderdeel van|watergang|ja|

**Domeinwaarden**

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd


#### Getijdengebied

Dit SOR-begrip is een nader type van de NEN 3610- hoofdklasse Oppervlaktewater.
 

**Definitie**

| Naam    | Getijdengebied    |
|---|---|
| Definitie | Geheel of gedeeltelijk droogvallende gronden die buitendijks gelegen zijn|
|Herkomst definitie    | Basisregistratie Topografie: Catalogus en Productspecificaties (versie 1.2.0.1)     |
|Verplicht    | Ja    |
|Gevolgen afbakening    | Het betreft hier de bestaande populatie *ondersteunend waterdeel; Type slik* en *begroeide terreindelen; Type kwelder* zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|    |

**Eigenschappen**

|Eigenschap     |Beschrijving     |Verplicht     |
|---|---|---|
|Identificatie     |Unieke aanduiding van een getijdengebied|Ja |
|Geometrie|Geometrische representatie van een getijdengebied|Ja (2,5D vlak)|
|Type |Aanduiding van het soort getijdengebied|Nee|
|Status     | Fase van de levenscyclus waarin een getijdengebied zich bevindt|Ja     |

**Domeinwaarden**



*Type*

|Waarde Type | Beschrijving Type |
|---|---|
|Schor|Buitendijks aangeslibd land, dat bij gewone vloed niet meer onderloopt en doorgaans begroeid is|
|Slik|Buitendijks aangeslibde, onbegroeide grond die bij vrijwel elk hoogwater onderloopt|


*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd



### Begroeiing


#### Bos

Dit SOR-begrip is een nader type van de NEN 3610- hoofdklasse Begroeiing 


**Definitie**

| Naam    | Bos |
|---|---|
| Definitie |Begroeiing die een dusdanige aantal bomen betreft dat deze een min of meer gesloten geheel vormen of, na volgroeiing van de bomen, zullen vormen|
| Herkomst definitie    | Gebaseerd op de definities van bos in de BGT 1.2 en van Griend en Hakhout uit IMGeo 2.2 |
| Verplicht    | Ja (grotendeels)|
|Gevolgen afbakening    | Het betreft hier grotendeels de bestaande populatie fysiek voorkomen *loofbos, naaldbos en gemengd bos en groenvoorziening van type bosplantsoen* van *begroeid terreindeel* zoals deze is opgenomen in de basisregistratie grootschalige topografie.|
| Toelichting| De definitie van Bos laat voldoende ruimte voor plaatselijke aanwezigheid van struiken. |

**Eigenschappen**

|Eigenschap     |Beschrijving     |Verplicht     |
|---|---|---|
|Identificatie     | Unieke aanduiding van een bos|Ja |
|Geometrie| Geometrische representatie van een bos|Ja (2,5D vlak)|
|Type | Aanduiding van het soort bos|Ja|
|Status     | Fase van de levenscyclus waarin een bos zich bevindt|Ja     |

**Domeinwaarden**

*Type*

|Waarde Type | Beschrijving Type    |Verplicht |
|---|---|---|
| Gemengd bos | Terrein begroeid met een dusdanig aantal naald- en loofbomen dat deze een min of meer gesloten geheel vormen of, na volgroeiing van de bomen, zullen vormen|    Ja|
| Griend en hakhout	|Terrein begroeid met loofbomen, in een dicht groeiverband die periodiek wordt ingekort| Nee|
| Loofbos |Terrein begroeid met een dusdanige aantal loofbomen dat deze een min of meer gesloten geheel vormen of, na volgroeiing van de bomen, zullen vormen| Ja|
| Naaldbos | Terrein begroeid met een dusdanige aantal naaldbomen dat deze een min of meer gesloten geheel vormen of, na volgroeiing van de bomen, zullen vormen| Ja|

Toelichting: Nog bekeken wordt hoe griend en hakhout als een subtype van loofbos gepositioneerd wordt.


*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd


#### Bomenrij

Dit SOR-begrip is een nader type van de NEN 3610- hoofdklasse begroeiing

**Definitie**

| Naam  | Bomenrij |
|---|---|
| Definitie | Opgaande rijvormige begroeiing van bomen zonder ondergroei van struiken |
|Herkomst definitie  |nieuw|
|Verplicht  | Ja |
|Gevolgen afbakening|Het betreft een nieuw op te nemen objecttype|
|Toelichting| Bomenrij wordt opgenomen vanwege het landschappelijke belang van dit object. In een later stadium zullen registratieregels worden opgesteld waarin nader wordt uitgewerkt wat de exacte relatie is tussen boom, houtsingel, bomenrij en bos, hoe deze begrippen zich verhouden tot andere aan het landschap gerelateerde begrippen en op welke wijze de geometrie van deze begrippen wordt vormgegeven.  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van een bomenrij|Ja |
|Geometrie|Geometrische representatie van een bomenrij|Ja (2,5D lijn of vlak)|
|Status   | De fase van de levenscyclus waarin een bomenrij zich bevindt|Ja   |

**Domeinwaarden**

*Status*

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd


#### Houtsingel

Dit SOR-begrip is een nader type van de NEN 3610- hoofdklasse begroeiing

**Definitie**

| Naam  | Houtsingel |
|---|---|
| Definitie |  Opgaande rijvormige begroeiing van bomen (enkelvoudige/meervoudige stammen) mét ondergroei van struiken|
|Herkomst definitie  |nieuw|
|Verplicht  | Ja |
|Gevolgen afbakening| Het betreft hier de bestaande populatie *houtwal* zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting| Houtsingel wordt opgenomen vanwege het landschappelijke belang van dit object. In een later stadium zullen registratieregels worden opgesteld waarin nader wordt uitgewerkt wat de exacte relatie is tussen boom, houtsingel, bomenrij en bos, hoe deze begrippen zich verhouden tot andere aan het landschap gerelateerde begrippen en op welke wijze de geometrie van deze begrippen wordt vormgegeven.  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van een houtsingel|Ja |
|Geometrie|Geometrische representatie van een Houtsingel|Ja (2,5D lijn of vlak)|
|Status   | De fase van de levenscyclus waarin een Houtsingel zich bevindt|Ja   |

**Domeinwaarden**

*Status*

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd


#### Boom

Dit SOR-begrip is een nader type van de NEN 3610- hoofdklasse Begroeiing 


**Definitie**

| Naam    | Boom |
|---|---|
| Definitie | Een overblijvende plant met verhoute stam en kroon|
|Herkomst definitie    | Wikipedia    |
|Verplicht    | Ja    |
|Gevolgen afbakening    | Het betreft hier de bestaande populatie boom zoals deze is opgenomen in de basisregistratie grootschalige topografie    |
|Toelichting| In een later stadium zullen registratieregels worden opgesteld waarin een nadere invulling wordt gegeven welke bomen verplicht in de registratie worden opgenomen. Ook zal dan nader worden uitgewerkt wat de exacte relatie is tussen boom, houtsingel, bomenrij en bos, hoe deze begrippen zich verhouden tot andere aan het landschap gerelateerde begrippen en op welke wijze de geometrie van deze begrippen wordt vormgegeven. |


**Eigenschappen**

|Eigenschap     |Beschrijving     |Verplicht     |
|---|---|---|
|Identificatie     |Unieke aanduiding van een boom|Ja |
|Geometrie| Geometrische representatie van een boom|Ja (2,5D punt)|
|Status     | Fase van de levenscyclus waarin een boom zich bevindt|Ja     |



**Domeinwaarden**


*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd


#### Fruit- of kweekbomen

Dit SOR-begrip is een nader type van de NEN 3610- hoofdklasse Begroeiing 


**Definitie**

| Naam    | Fruit- of kweekbomen |
|---|---|
| Definitie |Begroeiing die het kweken van meerjarige siergewassen en bomen betreft ten behoeve van een later gebruik elders of voor het kweken van fruit|
|Herkomst definitie    | nieuw |
|Verplicht    | ja    |
|Gevolgen afbakening    | Het betreft hier de bestaande populatie fysiek voorkomen *fruitteelt* en *boomteelt* zoals deze is opgenomen in de basisregistratie grootschalige topografie. En de *Boomkwekerij*, *Fruitkwekerij* en *Boomgaard* zoals deze is opgenomen in de basisregistratie topografie. |
|Toelichting| De hier bedoelde kwekerijen onderscheiden zich van kwekerijen van potplanten door de langdurige stand/teelt van gewassen |

**Eigenschappen**

|Eigenschap     |Beschrijving     |Verplicht     |
|---|---|---|
|Identificatie     | Unieke aanduiding van fruit- of kweekbomen |Ja |
|Geometrie| Geometrische representatie van fruit- of kweekbomen|Ja (2,5D vlak)|
|Type | Typering van fruit- of kweekbomen|Ja|
|Status     | Fase van de levenscyclus waarin fruit- of kweekbomen zich bevinden|Ja     |



**Domeinwaarden**

*Type* 

|Waarde Type | Beschrijving Type |
|---|---|
| Boomkwekerij |Terrein, overwegend in gebruik t.b.v. het opkweken van bomen (inclusief coniferen en sparren) en struiken, waarbij de hoogte van de aanplant niet van belang is|
| Fruitkwekerij met lage opstand|Terrein begroeid met laagstamfruitbomen, druivenstokken of begroeid met heesters voor zachtfruit zoals bessen of frambozen|
| Hoogstam boomgaarden |Terrein begroeid met hoogstamfruitbomen|


*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd


#### Tuunwal

Dit SOR-begrip is een nader type van de NEN 3610- hoofdklasse begroeiing

**Definitie**

| Naam  | Tuunwal |
|---|---|
| Definitie | Gestapelde grasplaggen op de scheiding tussen twee percelen |
|Herkomst definitie  |nieuw|
|Verplicht  | Ja |
|Gevolgen afbakening|Het betreft een nieuw op te nemen objecttype|
|Toelichting|  Tuunwal wordt opgenomen vanwege het landschappelijke belang van dit object. Tuunwallen wijken duidelijk af van vegetatieve perceelsscheiding (haag, bomenrij en houtsingel) en ook van de verschillende afscheidingen |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van een tuunwal|Ja |
|Geometrie|Geometrische representatie van een tuunwal|Ja (2,5D lijn of vlak)|
|Status   | De fase van de levenscyclus waarin een tuunwal zich bevindt|Ja   |

**Domeinwaarden**


*Status*

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd


####    Struiken

Dit SOR-begrip is een nader type van de NEN 3610- hoofdklasse Begroeiing 


**Definitie**

| Naam    | Struiken |
|---|---|
| Definitie |Begroeiing van bodembedekkers en/of houtachtige en/of meerstammige overblijvende planten|     
|Herkomst definitie    |    BGT 1.2 |
|Verplicht    | Ja    |
|Gevolgen afbakening    | Het betreft hier de bestaande populatie fysiek voorkomen *struiken, groenvoorziening* en *haag* zoals deze is opgenomen in de basisregistratie grootschalige topografie. En de *heg, haag* zoals deze is opgenomen in de basisregistratie topografie |
|Toelichting| Dit omvat alle begroeiing die niet valt onder de overige reële objecten onder Begroeiing| 

**Eigenschappen**

|Eigenschap     |Beschrijving     |Verplicht     |
|---|---|---|
|Identificatie     | Unieke aanduiding van struiken|Ja |
|Geometrie| Geometrische representatie van struiken|Ja (2,5D vlak)|
|Indicatie haag | Geeft aan of struiken als een haag onderhouden worden|Ja|
|Status     | Fase van de levenscyclus waarin struiken zich bevinden|Ja     |


**Domeinwaarden**

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd







#### Gras- en kruidachtigen

Dit SOR-begrip is een nader type van de NEN 3610- hoofdklasse Begroeiing 


**Definitie**

| Naam    | Gras- en kruidachtigen |
|---|---|
| Definitie |Begroeiing die een laagblijvende, aaneengesloten gras- en/of kruidachtige vegetatie betreft| 
|Herkomst definitie    | IMBOR 2020 |
|Verplicht    | ja    |
|Gevolgen afbakening    | Het betreft hier grotendeels de bestaande populatie fysiek voorkomen *gras- en kruidachtigen*,*grasland agrarisch* en *grasland overig* zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting| Onderscheid in gras voor agrarisch gebruik, dan wel voor natuurlijk gebruik of 'overig' gebruik is op basis van het nieuwe reëel object Gras- en kruidachtigen niet meer te zien. In sectormodel kan onderscheid gemaakt worden op basis van sector specifieke kenmerken. De combinatie van reëel object Gras- en kruidachtigen en functioneel object Park of Sportterrein en/of sectorregistraties (bv IMNA, gewaspercelen, IMBOR) kan voorzien in informatiebehoefte aan specifieke grastypen zoals 'gazon', agrarisch/natuurlijk gras' of 'sportveld'.| 

**Eigenschappen**

|Eigenschap     |Beschrijving     |Verplicht     |
|---|---|---|
|Identificatie     | Unieke aanduiding van gras- en kruidachtigen|Ja |
|Geometrie| Geometrische representatie van veld met gras- en kruidachtigen|Ja (2,5D vlak)|
|Status     | Fase van de levenscyclus waarin een veld met gras- en kruidachtigen zich bevindt|Ja     |


**Domeinwaarden**

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd





#### Akkerland


Dit SOR-begrip is een nader type van de NEN 3610- hoofdklasse Begroeiing 


**Definitie**

| Naam    | Akkerland    |
|---|---|
| Akkerland | Terrein in gebruik als akker, met gewassen die in een teelt-roulatieschema zijn opgenomen|
|Herkomst definitie    | Definitie gebaseerd op bouwland in de BGT 1.2 |
|Verplicht    | ja    |
|Gevolgen afbakening    | Het betreft hier de bestaande populatie fysiek voorkomen bouwland zoals deze is opgenomen in de basisregistratie grootschalige topografie. BRT-object    Braakliggend    wordt voor zover het landbouwgrond betreft ook in dit objecttype akkerland opgenomen|
|Toelichting| Kan tijdelijk zonder gewas zijn of braak liggen|

**Eigenschappen**

|Eigenschap     |Beschrijving     |Verplicht     |
|---|---|---|
|Identificatie     | Unieke aanduiding van een terrein akkerland|Ja |
|Geometrie| Geometrische representatie van een terrein akkerland|Ja (2,5D vlak)|
|Status     | Fase van de levenscyclus waarin een terrein akkerland zich bevindt|Ja     |

**Domeinwaarden**

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd




#### Moeras

Dit SOR-begrip is een nader type van de NEN 3610- hoofdklasse Begroeiing 

**Definitie**

| Naam    | Moeras |
|---|---|
| Definitie | Terrein met moerasvegetatie in stilstaand water van geringe diepte zonder merkbare toe- of afvloeiing. |
|Herkomst definitie    | BGT 1.2 |
|Verplicht    | Ja    |
|Gevolgen afbakening    | Het betreft hier de bestaande populatie *moeras*    zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|Het reëel object Moeras is opgenomen om de specifieke combinatie van water en kenmerkende moerasbegroeiing weer te geven ten behoeve van navigatie en toegankelijkheid. Deze gebieden kenmerken zich door een heel eigen verschijningsvorm, waarbinnen de begroeiing plaatselijk en tijdelijk kan veranderen, maar waar onderhoud gericht is op behoud van de typische verschijningsvorm van moerasland.    |

**Eigenschappen**

|Eigenschap     |Beschrijving     |Verplicht     |
|---|---|---|
|Identificatie     |Unieke aanduiding van een Moeras|Ja |
|Geometrie|Geometrische representatie van een moeras|Ja (2,5D vlak)|
|Status     |    Fase van de levenscyclus waarin een moeras zich bevindt|Ja     |


**Domeinwaarden**

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd



#### Rietland

Dit SOR-begrip is een nader type van de NEN 3610- hoofdklasse Begroeiing 

**Definitie**

| Naam    | Rietland |
|---|---|
| Definitie |Terrein overwegend begroeid met rietvegetatie|
|Herkomst definitie    | BGT 1.2 |
|Verplicht    | Ja    |
|Gevolgen afbakening    | Het betreft hier de bestaande populatie *rietland*    zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting| Het reëel object Rietland is opgenomen om de specifieke combinatie van water en kenmerkende begroeiing weer te geven ten behoeve van navigatie en toegankelijkheid. Deze gebieden kenmerken zich door een heel eigen verschijningsvorm, waarbinnen de begroeiing plaatselijk en tijdelijk kan veranderen, maar waar onderhoud gericht is op behoud van de typische verschijningsvorm van rietland. |

**Eigenschappen**

|Eigenschap     |Beschrijving     |Verplicht     |
|---|---|---|
|Identificatie     |Unieke aanduiding van een Rietland|Ja |
|Geometrie|Geometrische representatie van een rietland|Ja (2,5D vlak)|
|Status     |    Fase van de levenscyclus waarin een rietland zich bevindt|Ja     |


**Domeinwaarden**

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd


#### Heide

Dit SOR-begrip is een nader type van de NEN 3610- hoofdklasse Begroeiing 

**Definitie**

| Naam    | Heide |
|---|---|
| Definitie | Terrein begroeid met heide en heideachtige vegetaties|
|Herkomst definitie    | BGT 1.2 |
|Verplicht    | Ja    |
|Gevolgen afbakening    | Het betreft hier de bestaande populatie *heide* zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|Het reëel object Heide is opgenomen om de kenmerkende begroeiing weer te geven ten behoeve van navigatie en toegankelijkheid. Deze gebieden kenmerken zich door een heel eigen verschijningsvorm, waarbinnen de begroeiing plaatselijk en tijdelijk kan veranderen, maar waar onderhoud gericht is op behoud van de typische verschijningsvorm van heide    |

**Eigenschappen**

|Eigenschap     |Beschrijving     |Verplicht     |
|---|---|---|
|Identificatie     |Unieke aanduiding van een heide|Ja |
|Geometrie|Geometrische representatie van een heide|Ja (2,5D vlak)|
|Status     |    Fase van de levenscyclus waarin een heide zich bevindt|Ja     |


**Domeinwaarden**

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd



#### Onbegroeide grond

Dit SOR-begrip is een nader type van de NEN 3610- hoofdklasse Begroeiing 


**Definitie**

| Naam    | Onbegroeide grond |
|---|---|
| Definitie |Oppervlakte die niet bedekt is met enige vorm van begroeiing, water, verharding, gebouwen of andere constructies|
| Herkomst definitie    | Nieuw |
| Verplicht    | Ja    |
| Gevolgen afbakening    | Het betreft hier ten opzichte van de bestaande basisregistraties een nieuw objecttype, grotendeels het bestaande fysieke voorkomen type onverhard van terreinen in de basisregistratie grootschalige topografie|
| Toelichting| Onbegroeide grond is bewust niet bedekt|

**Eigenschappen**

|Eigenschap     |Beschrijving     |Verplicht     |
|---|---|---|
|Identificatie     |Unieke aanduiding van onbegroeide grond|Ja |
|Geometrie| Geometrische representatie van onbegroeide grond|Ja (2,5D vlak)|
|Status     | Fase van de levenscyclus waarin een stuk onbegroeide grond zich bevindt|Ja     |


**Domeinwaarden**

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd



### Gebouw



#### Gebouw

Dit SOR-begrip is een nader type van de NEN 3610- hoofdklasse Gebouw 

**Definitie**

| Naam    | Gebouw    |
|---|---|
| Definitie | Overdekte en geheel of grotendeels met wanden omsloten constructief zelfstandige eenheid bedoeld voor het in een afgeschermde omgeving onderbrengen van mensen, dieren of voorwerpen of voor de productie van goederen|
|Herkomst definitie    |Gebaseerd op definitie “pand” in artikel 1 Wet basisregistratie adressen en gebouwen en de INSPIRE richtlijn |
|Verplicht    | Ja    |
|Gevolgen afbakening    | Het betreft hier grotendeels de bestaande populatie panden zoals deze is opgenomen in de basisregistratie adressen en gebouwen en de basisregistratie grootschalige topografie. De bestaande definitie van het begrip pand is uitgebreid met een aantal elementen die zijn opgenomen in de INSPIRE richtlijn. |
|Toelichting| In een later stadium zullen registratieregels worden opgesteld waarin een nadere invulling wordt gegeven aan de interpretatie die aan gebouw moet worden gegeven |



**Eigenschappen**

|Eigenschap     |Beschrijving     |Verplicht     |
|---|---|---|
|Identificatie     |Unieke aanduiding van een gebouw|Ja |
|Geometrie |Geometrische representatie van een gebouw     |Ja (3D)|
|Type|Categorisering van een gebouw op basis van het constructief beoogde gebruik|Ja|
|Aard|Fysieke verschijningsvorm van een gebouw    |Ja|
|Oorspronkelijk bouwjaar | Aanduiding van het jaar waarin een gebouw oorspronkelijk als bouwkundig gereed is of zal worden opgeleverd|Ja|
|Naam| Breed geaccepteerde benaming van een gebouw zoals deze door de eigenaar is toegekend of zoals deze in de volksmond bekend staat| Nee|
|Status     |Fase van de levenscyclus waarin een gebouw zich bevindt |Ja     |


**Domeinwaarden**


*Type* 

|Waarde Type|	Beschrijving Type|
|---|---|
|Bedrijfsgebouw	|Gebouw waarvan de constructie zodanig is vormgegeven dat het geschikt is voor het daarbinnen uitoefenen van specifieke bedrijfsmatige activiteiten|
|Bijgebouw	|Gebouw dat constructief is opgezet om aan een woongebouw ondersteunende opslagfaciliteiten te bieden
|Doelgroepengebouw	|Gebouw met een constructieve opzet gericht op het tijdelijk of permanent onderbrengen van grotere groepen personen voor zorg, onderwijs, detentie of militaire doeleinden|
|Gebedsgebouw	|Gebouw dat zodanig is ontworpen dat het primair geschikt is voor het houden van religieuze bijeenkomsten|
|Installatiegebouw	|Gebouw met een constructieve opbouw gericht op het binnen het gebouw onderbrengen van specifieke technische installaties of voorzieningen|
|Kantoorgebouw	|Gebouw met een constructieve opzet gericht op het daarbinnen kunnen uitoefenen van administratieve werkzaamheden|
|Multigebouw	|Gebouw met een constructie gericht op het daarbinnen kunnen vormen van meerdere op wonen en/of bedrijfsmatige activiteiten gerichte gebruikseenheden|
|Recreatiegebouw	|Gebouw met een constructie die het mogelijk maakt dat daarbinnen activiteiten kunnen plaatsvinden gericht op of ondersteunend aan sport, cultuur of ontspanning|
|Toren	|Gebouw met een constructie waarbij de verhouding van de hoogte ten opzichte van lengte en breedte karakteristiek is voor de verschijningsvorm|
|Vestingsgebouw	|Gebouw met een constructie die het mogelijk maakt om aanvallen van buiten het gebouw te kunnen weerstaan|
|Woongebouw	|Gebouw met een constructie die primair geschikt voor bewoning|


Met de bovenstaande typering worden alle gebouwen van een typering voorzien. Als nadere invulling van “het uitklapmodel” (zie paragraaf [Aansluiting sectormodellen](#aansluiting-sectormodellen)) moeten gebouwen met de typering bijgebouw, gebedsgebouw en vestingsgebouw daarnaast altijd worden voorzien van een nadere typering:

|Waarde Subtype|Beschrijving Subtype|
|---|---|
|**Bijgebouw**||
|Garage	|Bijgebouw met een constructie gericht op het kunnen stallen van    motorvoertuigen op meer dan twee wielen ter ondersteuning van een woonfunctie |
|Schuur	|Bijgebouw met een constructie gericht op het kunnen opslaan van goederen ter ondersteuning van een woonfunctie|
|**Gebedsgebouw**||
|Kapel	|Klein gebedsgebouw dat is vormgegeven om te kunnen fungeren voor individuele bezinning|
|Kerkgebouw	|Gebedsgebouw met een constructie gericht op het houden van christelijke erediensten|
|Klooster	|Gebedsgebouw bedoeld voor huisvesting en eventueel het voorzien in levensonderhoud van een geloofsgemeenschap|
|Moskee	|Gebedsgebouw met een constructie gericht op islamitische geloofsuitoefening|
|Synagoge	|Gebedsgebouw met een constructie gericht op joodse geloofsuitoefening|
|Tempel| Gebedsgebouw met een constructie gericht op niet-abrahamitische geloofsuitoefening|
|**Vestingsgebouw**	 ||
|Bunker	|Van oorsprong versterkt militair gebouw gericht op het schuilen tegen beschietingen en bombardementen|
|Fort	|Naar alle zijden tegen vijandelijke aanvallen verdedigbaar militair gebouw dat van oorsprong is ingericht om een eenheid militairen te herbergen|
|Kasteel	|Versterkt en te verdedigen gebouw dat van oorsprong is bedoeld voor bewoning


Bij alle andere gebouwen wordt uitsluitend een nadere typering aangebracht als het gebouw voldoet aan de definitie van één van de hieronder genoemde subtyperingen:

|    Waarde Subtype |    Beschrijving Subtype |
|---|---|
|    **Bedrijfsgebouw** |        |
|    Boerderij |     Gebouw dat zodanig constructief is vormgegeven dat daarbinnen een combinatie van agrarische bedrijfsvoering en bewoning door de bedrijfsvoerder kan     plaatsvinden |
|    Fabriek |    Bedrijfsgebouw     dat constructief is vormgegeven zodat daarbinnen op grote schaal stoffen of goederen     geproduceerd kunnen worden |
|    Hangar |    Bedrijfsgebouw     met een omvang en constructie gericht op het produceren, onderhouden of     stallen van vliegtuigen en/of helikopters |
|    Kas |    Gebouw     bestaande uit een structuur van meestal glas en metaal die gebruikt wordt     voor het commercieel kweken van planten in een beschermde omgeving op een     natuurlijke of kunstmatige ondergrond |
|    Loods |    Groot en hoog     gebouw met veelal grote inrijdeuren bedoeld voor het opslaan van handels- of     industriële goederen |
|    Molen |    Bedrijfsgebouw     dat gekenmerkt wordt door het in een aan het gebouw aanwezig zijn    van een draaiend mechaniek waarbij wind     wordt omgezet in rotatie-energie van de op het gebouw aanwezige wieken |
|    Stal |    Bedrijfsgebouw     met een constructie gericht op het daarbinnen onderbrengen van vee |
|    Voertuigenstalling |    Gebouw met een constructie gericht op het bedrijfsmatig kunnen stallen van voertuigen |
|    **Doelgroepengebouw**     |        |
|    Gevangenis |    Gebouw dat     zodanig constructief is vormgegeven dat daarbinnen personen in verzekerde     bewaring kunnen worden gesteld om een gevangenisstraf uit te zitten |
|    Kazerne |    Gebouw met     een constructie gericht op het kunnen huisvesten van militairen |
|    **Installatiegebouw** |        |
|    Energiecentrale |    Gebouw met     een constructie die het mogelijk maakt om daarbinnen centraal energie op te     wekken |
|    Gemaalgebouw |    Gebouw dat is     ingericht om de installaties te herbergen die nodig zijn voor het van een     lager naar een hoger niveau brengen van water |
|    **Recreatiegebouw**     |        |
|    Sportgebouw |    Gebouw met     een specifieke constructie die is bedoeld om het mogelijk te maken om     binnensporten te kunnen beoefenen |
|    **Toren** |        |
|    Fabrieksschoorsteen |    Losstaand     hoog stenen kanaal bedoeld voor het afvoeren van verbrandingsgassen |
|    Klokkentoren |    Toren bedoeld     voor de ophanging van een uurwerk en/of klokkenspel |
|    Vuurtoren |    Toren bedoeld     als drager van een ter oriëntatie van schepen dienend licht |
|    Watertoren |    Toren die     oorspronkelijk is bedoeld voor de opslag van drinkwater in een bovenin het     gebouw gelegen waterreservoir |


Op een later moment zal nog worden bepaald in hoeverre het wenselijk en mogelijk is alle gebouwen van een eenduidige subtypering te voorzien. De opgenomen definities konden slechts gedeeltelijk op bestaande definities worden gebaseerd. De verschillende definities zullen op een later moment daarom mogelijk nog verder worden aangescherpt.


*Aard*

|Waarde Aard|Beschrijving Aard|
|---|---|
|Heterogeen	|Gebouw dat onderdeel uitmaakt van een reeks aan elkaar verbonden gebouwen die onafhankelijk van elkaar zijn gerealiseerd|
|Repeterend	|Gebouw dat onderdeel uitmaakt van een reeks aan elkaar verbonden gebouwen die als zodanig in één project zijn gerealiseerd|
|Vrijstaand	|Gebouw dat niet is verbonden met een ander gebouw|


*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd. De mate waarin alle genoemde statussen ook daadwerkelijk verplicht zullen worden en de regels omtrent interpretatie en overgang van statussen zullen in een later stadium nog gedetailleerder worden uitgewerkt in registratieregels.    Daarbij zal ook de aansluiting op de Omgevingswet verder worden aangescherpt. De status “in gebruik (niet ingemeten)” keert in de SOR niet als een afzonderlijke status terug. De mate waarin sprake is van definitieve geometrie zal door middel van meta-informatie bij de eigenschap geometrie worden vastgelegd.



#### Bouwlaag

Dit SOR-begrip is een nader type van de NEN 3610- hoofdklasse Gebouw 

**Definitie**

| Naam    | Bouwlaag    |
|---|---|
| Definitie | Verzameling van ruimten die zijn gelegen op hetzelfde niveau binnen een gebouw |
|Herkomst definitie    |Gebaseerd op de definitie van het begrip Bouwlaag (IfcBuildingStorey) uit de concepten rondom Bouwwerkinformatiemodellen (BIM)|
|Verplicht    | Ja    |
|Gevolgen afbakening    | Het betreft hier ten opzichte van de bestaande basisregistraties een nieuw objecttype |
|Toelichting| In een later stadium zullen registratieregels worden opgesteld waarin een nadere invulling wordt gegeven aan de interpretatie die aan bouwlaag moet worden gegeven|

**Eigenschappen**

|Eigenschap     |Beschrijving     |Verplicht     |
|---|---|---|
|Identificatie     |Unieke aanduiding van een bouwlaag|Ja |
|Geometrie |Geometrische representatie van een bouwlaag    |Ja (2,5D)|
|Bouwlaagnummer |Niveau waarop een bouwlaag zich bevindt|Ja|
|Status     |Fase vruimtean de levenscyclus waarin een bouwlaag zich bevindt     |Ja     |


**Relaties met andere objecttypen** 

|Relatiesoort     |Relatierol |Verplicht|
|---|---|---|
|Ligt in|Gebouw| Ja|

**Domeinwaarden**

*Bouwlaagnummer*

Voor de nummering van de bouwlaag geldt:
-   Tweede kelder laag = bouwlaagnummer -2
-	Kelder = bouwlaagnummer -1
-	Begane grond = bouwlaagnummer 0
-	Eerste verdieping = bouwlaagnummer 1
-	Tweede verdieping = bouwlaagnummer 2 

Toelichting: Op een later moment zal nog worden uitgewerkt op welke wijze de nummering van halve verdiepingen zal worden vastgelegd. In de registratievoorschriften zullen daarnaast afspraken worden opgenomen over het niveau dat als begane grond wordt gehanteerd als een gebouw meerdere toegangen op verschillende bouwlagen kent.

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd. De mate waarin alle genoemde statussen ook daadwerkelijk verplicht zullen worden en de regels omtrent interpretatie en overgang van statussen zullen in een later stadium nog gedetailleerder worden uitgewerkt in registratieregels.    
	


#### Ruimte

Dit SOR-begrip is een nader type van de NEN 3610- hoofdklasse Gebouw 

**Definitie**

| Naam    | Ruimte    |
|---|---|
| Definitie | Voor mensen toegankelijk deel van een gebouw, dat ten minste aan de onderzijde en/of de bovenzijde wordt begrensd door een scheidingsconstructie en dat een netto-hoogte heeft van tenminste 1,5 m|
|Herkomst definitie    |Ontleend aan NEN 2580 en aansluitend op het begrip Ruimte (IfcSpace) uit de concepten rondom Bouwwerkinformatiemodellen (BIM)|
|Verplicht    | Nee    |
|Gevolgen afbakening    | Het betreft hier ten opzichte van de bestaande basisregistraties een nieuw objecttype |
|Toelichting| In een later stadium zullen registratieregels worden opgesteld waarin een nadere invulling wordt gegeven aan de interpretatie die aan ruimte moet worden gegeven. Ook zal dan gedetailleerder worden vastgelegd welke ruimten in de registratie zouden kunnen worden opgenomen. Hierbij gaat de gedachte primair uit naar ruimten in multifunctionele complexe gebouwen met meerdere ruimten met verschillende functies. Het is niet de bedoeling om landelijk alle ruimten in woningen in de registratie op te gaan nemen.|

**Eigenschappen**

|Eigenschap     |Beschrijving     |Verplicht     |
|---|---|---|
|Identificatie     |Unieke aanduiding van een ruimte|Ja |
|Geometrie |Geometrische representatie van een ruimte     |Ja (2,5D)|
|Bouwlaagnummer |Bouwlaag waarop een ruimte zich bevindt|Ja|
|Oppervlakte| Gebruiksoppervlakte van een ruimte| Nee |
|Type|Categorisering van een ruimte op basis van het constructief beoogde gebruik| Ja|
|Status     |Fase van de levenscyclus waarin een ruimte zich bevindt     |Ja     |


**Relaties met andere objecttypen** 

|Relatiesoort     |Relatierol |Verplicht|
|---|---|---|
|Ligt op|Bouwlaag| Ja|

**Domeinwaarden**

*Bouwlaagnummer*

Voor de nummering van de bouwlaag geldt:
-   Tweede kelder laag = bouwlaagnummer -2
-	Kelder = bouwlaagnummer -1
-	Begane grond = bouwlaagnummer 0
-	Eerste verdieping = bouwlaagnummer 1
-	Tweede verdieping = bouwlaagnummer 2

Toelichting: Op een later moment zal nog worden uitgewerkt op welke wijze de nummering van halve verdiepingen zal worden vastgelegd. In de registratievoorschriften zullen daarnaast afspraken worden opgenomen over het niveau dat als begane grond wordt gehanteerd als een gebouw meerdere toegangen op verschillende bouwlagen kent.


*Type* 

|    Waarde Type |    Beschrijving     Type |
|-|-|
|    Commerciële     ruimte |    Ruimte die ruimtelijk zodanig is vormgegeven dat deze geschikt is voor het daarin     uitvoeren van op verkoop gerichte activiteiten |
|    Gebedsruimte |    Ruimte die ruimtelijk zodanig is vormgegeven dat deze geschikt is voor gebed en     individuele bezinning |
|    Horecaruimte |    Ruimte met een zodanige inrichting dat deze geschikt is voor het verstrekken van bereide maaltijden, snacks en dranken aan gasten voor onmiddellijke consumptie |
|    Installatieruimte |    Ruimte die speciaal is ingericht voor het daarin kunnen plaatsen van specifieke     technische installaties |
|    Kantoorruimte |    Ruimte die geschikt is gemaakt voor de uitoefening van een bedrijf, beroep of dienst waarin geen product wordt vervaardigd maar uitsluitend dienstverlening wordt bedreven |
|    Keukenruimte |    Ruimte die voorzieningen bevat voor het bereiden van voedsel en/of het reinigen van bij de bereiding en nuttiging van het voedsel benodigde hulpmiddelen |
|    Kleedruimte |    Ruimte die is ingericht voor het kunnen wisselen van kleding ten behoeve van een specifieke activiteit |
|    Leslokaal |    Ruimte die is ingericht voor het daarin kunnen verzorgen van instructies gericht op het bijbrengen van kennis en/of vaardigheden |
|    Ontvangstruimte |    Ruimte die is ingericht voor het kunnen opvangen en verwelkomen van bezoekers |
|    Opslagruimte |    Ruimte die geschikt is voor het voor kortere of langere tijd opslaan van goederen |
|    Recreatieruimte |    Ruimte die geschikt is gemaakt voor het daarbinnen kunnen uitoefenen van vormen van vrijetijdsbesteding die in     hoofdzaak geen lichamelijke beweging omvatten |
|    Sanitaire     ruimte |    Ruimte waarin zich voornamelijk op waterleiding en riolering aangesloten voorzieningen bevinden     die zijn gericht op persoonlijke verzorging en hygiëne |
|    Sportruimte |    Ruimte die geschikt is voor activiteiten gericht op lichamelijke oefeningen en     ontspanning waarbij vaardigheid, kracht en inzicht vereist worden |
|    Vergaderruimte        |    Ruimte die is ingericht om daarbinnen bijeenkomsten te houden waarin meerder personen met     elkaar overleg voeren |
|    Werkruimte |    Ruimte die primair geschikt is gemaakt voor de uitoefening van een bedrijf, beroep of dienst waarin een product wordt vervaardigd |
|    Woonruimte |    Ruimte die is ingericht voor het daarin permanent kunnen verblijven van personen voor niet bedrijfsmatige activiteiten |
|    Zaal |    Grote ruimte     die als locatie wordt gebruikt voor bijeenkomsten, evenementen of andere doeleinden waar meerdere mensen bij betrokken zijn |
|    Zorgruimte |    Ruimte die is ingericht voor het daarin kunnen bieden van lichamelijke of geestelijke hulp of aandacht |

Op een later moment zal nog worden bepaald in hoeverre de hier opgenomen typering afdoende is voor het kunnen duiden van ruimten binnen een gebouw. De opgenomen definities konden slechts beperkt op bestaande definities worden gebaseerd. De verschillende definities zullen op een later moment daarom mogelijk nog verder worden aangescherpt.

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd. De mate waarin alle genoemde statussen ook daadwerkelijk verplicht zullen worden en de regels omtrent interpretatie en overgang van statussen zullen in een later stadium nog gedetailleerder worden uitgewerkt in registratieregels.    



#### Gebouwcomponent

Dit SOR-begrip is een nader type van de NEN 3610- hoofdklasse Gebouw 

**Definitie**

| Naam    | Gebouwcomponent    |
|---|---|
| Definitie | Component aan de buitenzijde van een gebouw, die het aanzicht van het gebouw mede bepaalt |
|Herkomst definitie    |IMGeo 2.2|
|Verplicht    | Deels (nog nader te bepalen welke onderdelen) |
|Gevolgen afbakening    |Het betreft hier grotendeels de bestaande populatie van *gebouwinstallatie* zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting| In een later stadium zullen inwinregels worden opgesteld die de minimale omvang van de vast te leggen objecten aangeeft. Ook zullen registratieregels worden opgesteld waarin een nadere invulling wordt gegeven aan de interpretatie die aan gebouwcomponenten moet worden gegeven |

**Eigenschappen**

|Eigenschap     |Beschrijving     |Verplicht     |
|---|---|---|
|Identificatie     |Unieke aanduiding van een gebouwcomponent|Ja |
|Geometrie |Geometrische representatie van een gebouwcomponent     |Ja (1D, 1,5D of 2,5D)|
|Aard|Soort gebouwcomponent|Ja |
|Bijbehorend object |Object waarbij een gebouwcomponent behoort|Ja|
|Status     |Fase van de levenscyclus waarin een gebouwcomponent zich bevindt     |Ja     |


**Relaties met andere objecttypen** 

|Relatiesoort     |Relatierol |Verplicht|
|---|---|---|
|Hoort bij|Verblijfsobject|Ja|
|Hoort bij|Gebouw|Ja|
|Hoort bij 2 (loopbrug) | Gebouw|Ja|

**Domeinwaarden**


*Aard*

| Waarde Aard| Beschrijving     |
|---|---|
|Afdak|Constructie aangebracht en vast verbonden aan de gevel van een pand, gericht op beschutting tegen weersinvloeden |
|Balkon|Open uitbouw die niet gelijkvloers aan de gevel is aangebracht en waarvan het bovenvlak vanuit het gebouw toegankelijk is|
|Bordes|Verhard oppervlak, eventueel verhoogd en/of uitgevoerd met treden, grenzen aan een pand en primair bedoeld voor gebruik door voetgangers|
|Dakkapel |Uitbouw van het schuine dakvlak|
|Laadperron	|Tegen het gebouw aangebrachte constructie die is bedoeld voor het kunnen laden en lossen van voertuigen|
|Loopbrug	|Constructie bedoeld voor het op hoogte verbinden van twee bij elkaar liggende gebouwen zodat een oversteek van het ene naar het andere gebouw kan plaatsvinden|
|Toegangstrap|Buiten de gevel geplaatste trapconstructie die toegang biedt tot een gebouw en vast verbonden is met dat gebouw|


Voorbeelden van een afdak zijn: luifels en carports (die vast verbonden zijn met de gevel van een pand). Een afdak kan gedeeltelijk rusten op kolommen. Deze kolommen zijn dan echter uitsluitend ondersteunend aan de hangende hoofdconstructie.

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd. De mate waarin alle genoemde statussen ook daadwerkelijk verplicht zullen worden en de regels omtrent interpretatie en overgang van statussen zullen in een later stadium nog gedetailleerder worden uitgewerkt in registratieregels.    

#### Toegangsdeur

Dit SOR-begrip is een nader type van de NEN 3610- hoofdklasse Gebouw 

**Definitie**

| Naam    | Toegangsdeur |
|---|---|
| Definitie | Deur of andere voorziening die vanaf de openbare weg, een erf of een gedeelde verkeersruimte toegang geeft tot een object|
|Herkomst definitie    |Begrip sluit aan bij het begrip Deur (IfcDoor) uit de concepten rondom Bouwwerkinformatiemodellen (BIM)|
|Verplicht    | Deels (nog nader te bepalen welke onderdelen) |
|Gevolgen afbakening    | Het betreft hier ten opzichte van de bestaande basisregistraties grotendeels een nieuw objecttype|
|Toelichting| In een later stadium zullen registratieregels worden opgesteld waarin een nadere invulling wordt gegeven aan de interpretatie die aan toegangsdeur moet worden gegeven |

**Eigenschappen**

|Eigenschap     |Beschrijving     |Verplicht     |
|---|---|---|
|Identificatie     |Unieke aanduiding van een toegangsdeur|Ja |
|Geometrie |Geometrische representatie van een toegangsdeur     |Ja (1,5D)|
|Toegangssoort|Plaats waarvan een toegangsdeur toegang geeft|Ja|
|Gebruiksaard|Aard van gebruik van een toegangsdeur|Ja|
|Bijbehorend object |Object waarin een toegangsdeur zich bevindt|Ja|
|Status     |Fase van de levenscyclus waarin een toegangsdeur zich bevindt     |Ja     |


**Relaties met andere objecttypen** 

|Relatiesoort     |Relatierol |Verplicht|
|---|---|---|
|Hoort bij|Verblijfsobject| Ja|
|Hoort bij|Gebouw| Ja|

**Domeinwaarden**

*Toegangssoort*

| Waarde Toegangssoort| Beschrijving     |
|---|---|
|Directe toegang vanaf eigen terrein|Toegangsdeur bevindt zich op een erf, in een tuin of een andere specifiek terrein dat behoort bij het gebouw |
|Directe toegang vanaf openbare weg|Toegangsdeur bevindt zich direct aan een voor iedereen toegankelijke weg |
|Toegang vanaf gemeenschappelijke verkeersruimte |Toegangsdeur bevindt zich aan een inpandige ruimte die bedoeld is voor verplaatsingen door een gebouw door de verschillende gebruikers van dit gebouw    |

*Gebruiksaard*

| Waarde Gebruiksaard| Beschrijving     |
|---|---|
|Auto|Toegangsdeur is primair bedoeld voor toegang tot een object door voertuigen |
|Personen|Toegangsdeur is primair bedoeld voor toegang tot een object door personen |
|Vracht|Toegangsdeur is primair bedoeld voor toegang tot een object door vracht zonder gebruik van een voertuig|

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd. De mate waarin alle genoemde statussen ook daadwerkelijk verplicht zullen worden en de regels omtrent interpretatie en overgang van statussen zullen in een later stadium nog gedetailleerder worden uitgewerkt in registratieregels.    


#### Open bouwwerk


Dit SOR-begrip is een nader type van de NEN 3610- hoofdklasse Constructie 

**Definitie**

| Naam    | Open bouwwerk |
|---|---|
| Definitie | Afzonderlijk staande overdekking rustend op een constructie met kolommen met één of meerdere open gevels bedoeld voor het beschutten of stallen van mensen, dieren, objecten en/of voer- en vaartuigen |
|Herkomst definitie    |Gebaseerd op definities “open loods” en “overkapping” uit de gegevenscatalogus BGT|
|Verplicht    | Ja |
|Gevolgen afbakening    |Het betreft hier grotendeels de bestaande populatie open loodsen en overkappingen zoals deze is opgenomen in de basisregistratie grootschalige topografie |
|Toelichting| In een later stadium zullen de inwinregels worden opgesteld die de minimale omvang van de vast te leggen objecten en de eventuele kolommen aangeeft. Ook zullen registratieregels worden opgesteld waarin een nadere invulling wordt gegeven aan de interpretatie die aan open bouwwerken moet worden gegeven |

**Eigenschappen**

|Eigenschap     |Beschrijving     |Verplicht     |
|---|---|---|
|Identificatie     |Unieke aanduiding van een open bouwwerk|Ja |
|Geometrie |Geometrische representatie van een open bouwwerk     |Ja (3D)|
|Type| Soort open bouwwerk|Ja|
|Naam| Breed geaccepteerde benaming van een open bouwwerk zoals deze door de eigenaar is toegekend of zoals deze in de volksmond bekend staat| Nee|
|Status     |Fase van de levenscyclus waarin een    open bouwwerk zich bevindt     |Ja     |




**Domeinwaarden**

*Type*

|Waarde Type| Beschrijving Type|
|---|---|
|Open loods|Niet verplaatsbaar licht gebouw met een open gevel, bestemd als berg- of werkplaats of als tijdelijk onderdak voor andere doeleinden|
|Overkapping|Afzonderlijk staande overdekking rustend op kolommen|
|Parkeergarage|Open constructie die geheel of gedeeltelijk in gebruik is als voorziening voor het parkeren van voertuigen|
|Uitkijktoren	|Hoge open constructie die ontworpen is om vanuit een hoog punt de wijde omgeving te kunnen bekijken en/of bewaken|

Voorbeelden van open bouwwerken met typering overkapping zijn: losstaande carports, buitenkeukens, open tuinhuizen en tribunes. Bij open loodsen gaat het onder meer om open frontstallen, dierenverblijven, hobbykassen en boothuizen. Parkeergarages die zich in een gebouw bevinden maken onderdeel uit van het gebouw. Parkeergarages die bestaan uit een open (staal) constructie behoren tot de open bouwwerken. Het kan daarbij zowel gaan om parkeergarages voor motorvoertuigen als grotere parkeervoorzieningen voor fietsers. 

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd. De mate waarin alle genoemde statussen ook daadwerkelijk verplicht zullen worden en de regels omtrent interpretatie en overgang van statussen zullen in een later stadium nog gedetailleerder worden uitgewerkt in registratieregels.    




### Verharding


Dit SOR-begrip is een nader type van de NEN 3610- hoofdklasse Verharding 

 

**Definitie**

| Naam    | Verharding |
|---|---|
| Definitie |Oppervlak, dat door egaliseren, verstevigen en/of verruwen voor het beoogde gebruik geschikt gemaakt is, bestaande uit in één of meer lagen over een ondergrond of onderliggende constructie aangelegd materiaal|
|Herkomst definitie    |  NEN3610   |
|Verplicht    | Ja    |
|Gevolgen afbakening    | Het betreft hier een selectie van de bestaande populatie fysieke voorkomen van *wegdelen*, *ondersteunende wegdelen* en *onbegroeide terreindelen* zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting| Een verhardingsvlak bestaat uit één Type verharding. Het gaat hierbij over het Type verharding waarmee het vlak overwegend is bedekt|

**Eigenschappen**

|Eigenschap     |Beschrijving     |Verplicht     |
|---|---|---|
|Identificatie     |Unieke aanduiding van een verharding|Ja |
|Geometrie|Geometrische representatie van een verhardingsvlak|Ja (vlak, 2.5D)|
|Type |Aanduiding van het soort verharding|Ja|
|Status     | Fase van de levenscyclus waarin een verhardingsvlak zich bevindt|Ja     |


**Domeinwaarden**


*Type*

|Waarde Type | Beschrijving Type     |
|---|---|
| Asfaltverharding|Gesloten verharding bestaande uit asfaltbeton of andere met bitumen gebonden materialen|
| Betonverharding |Gesloten verharding bestaande uit gewapend of ongewapend beton|
| Elementenverharding|Open verharding opgebouwd uit losse elementen die in meer of mindere mate met elkaar verbonden zijn|
| Halfverharding|Open verharding bestaande uit onsamenhangend materiaal dat meer draagkracht levert dan de originele grond|
| Kunststofverharding|Verharding bestaande uit een synthetisch vervaardigd materiaal|
| Onverhard| Verharding bestaande uit natuurlijke materialen met een onverhard karakter|

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd

 

### Kunstwerk
#### Overbrugging

Dit SOR-begrip is een nader type van de NEN 3610- hoofdklasse Kunstwerk 

**Definitie**

| Naam    | Overbrugging    |
|---|---|
| Definitie | Kunstwerk dat een beweegbare of vaste verbinding tussen twee punten betreft, die door water, een weg of anderszins    gescheiden zijn,    bestaande uit een brugdek/-bak met landhoofden en veelal gesteund door pijlers|
|Herkomst definitie    | nieuw    |
|Verplicht    | Ja    |
|Gevolgen afbakening    | Het betreft hier grotendeels de bestaande populatie    *overbruggingsdelen; hoort bij Type overbrugging* zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|    |

**Eigenschappen**

|Eigenschap     |Beschrijving     |Verplicht     |
|---|---|---|
|Identificatie     |Unieke aanduiding van overbrugging|Ja |
|Geometrie|Geometrische representatie van een overbrugging|Ja (vlak, 2.5D)|
|Type |Aanduiding van het soort overbrugging|Ja|
|Naam| Breed geaccepteerde benaming van een overbrugging zoals deze door de eigenaar is toegekend of zoals deze in de volksmond bekend staat| Nee|
| Indicatie beweegbaar    |Deze overbrugging is al dan niet beweegbaar is (kan open en dicht) |Ja|
|Status     | Fase van de levenscyclus waarin een overbrugging zich bevindt|Ja     |



**Domeinwaarden**


*Type* 

|Waarde Type | Beschrijving Type    |
|---|---|
| Aquaduct |Overbruggingsconstructie waarmee een watergang door een bakvormige constructie over een weg, een spoorweg, een andere watergang, een leiding of een terrein wordt geleid|
| Brug |Overbruggingsconstructie over een watervlakte of watergang, bedoeld voor verkeer|
| Ecoduct |Overbruggingsconstructie over een weg of spoorweg,    bedoeld voor het passeren van dieren|
| Flyover|Kunstwerk in de vorm van een viaduct dat deel uitmaakt van een verkeersbaan en waarmee een verkeersstroom over twee of meer ongelijkvloerse verkeersstromen wordt geleid |
| Overkluizing |Civieltechnisch kunstwerk waarmee een weg, een plein of een watergang (kruiselings) wordt overwelfd, waarbij het dek meestal niet uitsluitend uit een pad of weg bestaat|
| Viaduct |Overbruggingsconstructie over een weg, spoorweg of terreinverdieping, bedoeld voor verkeer|


*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd



#### Ondertunneling


Dit SOR-begrip is een nader type van de NEN 3610- hoofdklasse Kunstwerk 

 

**Definitie**

| Naam    | Ondertunneling    |
|---|---|
| Definitie | Ondergrondse of onder water gelegen verbinding tussen twee punten, aan beide einden voorzien van een open bakconstructie.|
|Herkomst definitie    | nieuw |
|Verplicht    | Ja    |
|Gevolgen afbakening    | Het betreft hier grotendeels de bestaande populatie    *tunneldelen* zoals deze is opgenomen in de basisregistratie grootschalige topografie. En van *kunstwerkdelen van Type duiker* indien opgenomen in het IMGeo deel van de basisregistratie grootschalige topografie|
|Toelichting|  In een later stadium zullen registratieregels worden opgesteld waarin een nadere invulling wordt gegeven welke typeringen verplicht in de registratie worden opgenomen  |

**Eigenschappen**

|Eigenschap     |Beschrijving     |Verplicht     |
|---|---|---|
|Identificatie     |Unieke aanduiding van een ondertunneling|Ja |
|Geometrie|Geometrische representatie van een ondertunneling|Ja (vlak, 2.5D)|
|Type | Aanduiding van het soort ondertunneling|Ja|
|Naam| Breed geaccepteerde benaming van een ondertunneling zoals deze door de eigenaar is toegekend of zoals deze in de volksmond bekend staat| Nee|
|Status     | Fase van de levenscyclus waarin een ondertunneling zich bevindt|Ja     |


**Domeinwaarden**


*Type*

|Waarde Type | Beschrijving Type |
|---|---|
| Duiker |Kunstwerk voor de waterhuishouding, bestaande uit een gesloten kokervormige constructie met een in- en uitstroomopening, die niet de gehele waterbreedte beslaat, aangebracht onder een weg of spoorweg of in een dam of ander terrein en de bodem van de watergang onderbreekt|
| Hevel | Kokervormige constructie met een verhoogd middengedeelte dat twee wederzijds gelegen wateren met elkaar verbindt.|
| Sifon | Kokervormige constructie met een verlaagd middengedeelte dat geheel met water is gevuld en die twee watergangen met elkaar verbindt.|
| Tunnel |Kokervormig kunstwerk onder een of meer wegen, spoorwegen, waterwegen en/of andere hindernissen, als ondergrondse doorgang voor verkeer, leidingen of dieren|


*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd




#### Waterstaatkundig kunstwerk


Dit SOR-begrip is een nader type van de NEN 3610- hoofdklasse Kunstwerk 

**Definitie**

| Naam    | Waterstaatkundig kunstwerk |
|---|---|
| Definitie | Kunstwerk voor de beheersing van het oppervlaktewater en alles wat daarin voorkomt|
|Herkomst definitie    | nieuw    |
|Verplicht    | Ja    |
|Gevolgen afbakening    | Het betreft hier grotendeels de bestaande populatie kunstwerkdeel zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting| De kerende functie kan worden vastgelegd middels de functionele ruimte    kering    van het type    water    |

**Eigenschappen**

|Eigenschap     |Beschrijving     |Verplicht     |
|---|---|---|
|Identificatie     |Unieke aanduiding van een waterstaatkundig kunstwerk|Ja |
|Geometrie|Geometrische representatie van een waterstaatkundig kunstwerk|Ja (2.5D vlak)|
|Type | Aanduiding van het soort waterstaatkundig kunstwerk|Ja|
|Status     | Fase van de levenscyclus waarin een waterstaatkundig kunstwerk zich bevindt|Ja     |

**Relaties met andere objecttypen** 

|Relatiesoort     |Relatierol |Verplicht|
|---|---|---|
| heeft mogelijk een functie| kering| Ja|


**Domeinwaarden**



*Type*

|Waarde Type| Beschrijving Type    | Verplicht|
|---|---|---|
| Bodemval |Sprong in de bodem van een watergang| Nee|
| Coupure |Onderbreking in een waterkering voor de doorvoer van een weg of spoorweg, die bij extreme waterstanden afsluitbaar is|Nee|
| Damwand |Grondkerende of waterkerende constructie bestaande uit (nagenoeg) verticaal in de grond aangebrachte elementen die door middel van een langsprofiel in elkaar grijpen|Ja|
| Dijklichaam|Aangelegde waterkering van grond, die het achterliggende land beschermt tegen overstromingen|Ja|
| Gemaal | Kunstwerk in principe bedoeld om water van een laag peil naar een hoog peil te brengen|Ja|
| Kademuur | Verticale wand ter scheiding van land en water, opgebouwd uit een muur van gemetselde stenen of gestort beton|Ja|
| Keermuur | Muur die door vorm, gewicht en fundering zonder verankering de grond keert | Ja|
| Krib | Kunstmatig lichaam van aarde, steen, turf of rijshout (en tegenwoordig beton of staal), om water te keren of te leiden|Ja|
| Ponton |Vastliggend drijflichaam, dat dienst doet als aanlegplaats van vaartuigen of daartoe toegang geeft|Nee|
| Schot|Permanente afscheiding, verticaal in het water geplaatst, bedoeld om het waterpeil van het aan beide zijden aanwezige water te regelen|Nee|
| Sluis |Kunstmatige, afsluitbare waterkering die een scheepvaartverbinding tussen twee wateren met verschillende waterpeilen mogelijk maakt|Ja|
| Steiger |Vaste (niet drijvende) waterbouwkundige constructie, verbonden met de wal, voor het aanleggen van schepen en bedoeld om deze schepen vanaf de wal te laden en te lossen|Ja|
| Stormvloedkering|Waterkerende constructie die gesloten wordt bij zeer hoge buitenwaterstanden|Ja|
| Strekdam | Dam in de richting van de loop van de rivier of kanaal, ter beveiliging van de oevers of brugpijlers of ter beheersing van de rivier| Ja|
| Stuw |Vaste of beweegbare constructie in het water die dient om de waterstand bovenstrooms en/of benedenstrooms van de constructie te regelen    |Ja|
| Vaste dam | Dwars door een water gelegen afsluiting, bedoeld om water te keren of te beheersen.| Ja|
| Vispassage |Waterbouwkundig constructie dat tot doel heeft vissen toegang te bieden tot een door een kunstwerk onbereikbaar geworden achterland|Nee|
| Voorde |Doorwaadbare, doorgaans verharde, plaats in de watergang, die dient voor de oversteek van die watergang|Nee|
| Vuilvang | Voorziening om de watergang dan wel één of meerdere objecten benedenstrooms te vrijwaren van drijvend vuil en dergelijke|Ja|
| Walbescherming |Nagenoeg verticale wand tot kering van grond om afkalving van water te voorkomen, niet zijnde een kademuur| Ja|

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd



#### Kunstwerkdeel

Dit SOR-begrip is een nader type van de NEN 3610- hoofdklasse Kunstwerk 

 

**Definitie**

| Naam    |Kunstwerkdeel    |
|---|---|
| Definitie |    Onderdeel van een civieltechnisch werk voor de infrastructuur van wegen, water, spoorbanen, waterkeringen en/of leidingen |
|Herkomst definitie    | BGT 1.2    |
|Verplicht    | ja    |
|Gevolgen afbakening    | Het betreft hier grotendeels de bestaande populatie    *overbruggingsdelen, Type overbruggingsdeel* zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|    |

**Eigenschappen**

|Eigenschap     |Beschrijving     |Verplicht     |
|---|---|---|
|Identificatie     |Unieke aanduiding van een kunstwerkdeel|Ja |
|Geometrie|Geometrische representatie van een kunstwerkdeel|Ja (vlak, 2.5D)|
|Type | Aanduiding van het soort kunstwerkdeel|ja|
|Status     |    Fase van de levenscyclus waarin een kunstwerkdeel zich bevindt|Ja     |

**Relaties met andere objecttypen** 

|Relatiesoort     |Relatierol |Verplicht|
|---|---|---|
| is onderdeel van| kunstwerk, type overbrugging | ja|
| is onderdeel van | kunstwerk, type sluis | ja|

**Domeinwaarden**


*Type*

|Waarde Type | Beschrijving Type    | is onderdeel van|
|---|---|---|
| Dek |Direct door het verkeer belaste deel van de bovenbouw van de brug| overbrugging|
| Landhoofd |Ondersteuningsconstructie ter plaatse van een overgang van de aardebaan naar een kunstwerk|overbrugging|
| Pijler |Ondersteuningsconstructie van bruggen en soortgelijke kunstwerken|overbrugging|
| Pyloon |Boven de bovenbouw uitstekende draagconstructie voor tuien (kabels)|overbrugging|
| Schutkolk |Deel van de sluis waarin de te schutten schepen afmeren en op een hoger of lager niveau worden gebracht|sluis|
| Sloof |Deel van de pijler voor de overdracht van krachten naar de ondergrond of de fundering|overbrugging|
| Sluisdeur |Beweegbare deur die wordt toegepast bij (hoog)waterkeringen en sluizen om het niveauverschil aan beide zijden in stand te houden| sluis|



*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd






### Overige constructies


#### Afvalcontainer

Dit SOR-begrip is een nader type van de NEN 3610- hoofdklasse Constructie 

 

**Definitie**

| Naam    | Afvalcontainer    |
|---|---|
| Definitie | Constructie met een permanent karakter voor het inzamelen van afval|
|Herkomst definitie    | Gebaseerd op IMGeo 2.2    |
|Verplicht    | Nee    |
|Gevolgen afbakening    | Het betreft hier een subset van de bestaande populatie *bak* zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|    |

**Eigenschappen**

|Eigenschap     |Beschrijving     |Verplicht     |
|---|---|---|
|Identificatie     |Unieke aanduiding van een afvalcontainer|Ja |
|Geometrie|Geometrische representatie van een afvalcontainer|Ja (2,5D punt) Nee (2,5D vlak)|
|Status     | Fase van de levenscyclus waarin een afvalcontainer zich bevindt|Ja     |

**Domeinwaarden**

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd


#### Dok
    

Dit SOR-begrip is een nader type van de NEN 3610- hoofdklasse Constructie 

 
**Definitie**


| Naam    | Dok  |
|---|---|
| Definitie | Constructie bedoeld om schepen uit het water te halen en vervolgens weer in het water te laten| 
| Herkomst definitie| |Wikipedia|
|Verplicht    | Ja  |
|Gevolgen afbakening    | Het betreft hier deels de bestaande populatie overig bouwwerk type bassin zoals deze is opgenomen in de basisregistratie grootschalige topografie |
|Toelichting|     |

**Eigenschappen**

|Eigenschap     |Beschrijving     |Verplicht     |
|---|---|---|
| Identificatie     |Unieke aanduiding van een dok|Ja |
| Geometrie|Geometrische representatie van een dok| Ja (2,5D vlak)|
| Status     | Fase van de levenscyclus waarin een dok zich bevindt|Ja     |

**Domeinwaarden**

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd.



#### Geleideconstructie

Dit SOR-begrip is een nader type van de NEN 3610- hoofdklasse Constructie 
 

**Definitie**

| Naam    | Geleideconstructie    |
|---|---|
| Definitie | Constructie bedoeld voor de fysieke (be-)geleiding van voer- of vaartuigen|
|Herkomst definitie    | nieuw |
|Verplicht    | Nee    |
|Gevolgen afbakening    | |
|Toelichting|Het SOR-begrip geleideconstructie omvat meer dan het gelijknamige BGT/IMGeo objecttype weginrichtingselement; geleideconstructie. |

**Eigenschappen**

|Eigenschap     |Beschrijving     |Verplicht     |
|---|---|---|
|Identificatie     |Unieke aanduiding van een geleideconstructie|Ja |
|Geometrie|Geometrische representatie van de ligging van de geleideconstructie|Ja (2,5D punt, lijn, vlak)|
|Status     | Fase van de levenscyclus waarin een geleideconstructie zich bevindt|Ja     |

**Domeinwaarden**

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd



#### Installatie

Dit SOR-begrip is een nader type van de NEN 3610- hoofdklasse Constructie 

 

**Definitie**

| Naam    | Installatie    |
|---|---|
| Definitie | Constructie die een technisch samenhangend systeem betreft dat een bepaald doel dient|
|Herkomst definitie    | Gebaseerd op installatie in IMGeo 2.2    |
|Verplicht    | Ja|
|Gevolgen afbakening    | Het betreft hier de bestaande populatie    *installatie* en onderdelen van de bestaande populaties *paal, kast en overig bouwwerk*    zoals deze zijn opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|    |



**Eigenschappen**

|Eigenschap     |Beschrijving     |Verplicht     |
|---|---|---|
|Identificatie     |Unieke aanduiding van een installatie|Ja |
|Geometrie|Geometrische representatie van de installatie|Ja (2,5D punt, lijn, vlak)|
|Type | Aanduiding van het soort installatie|Ja|
|Status     | Fase van de levenscyclus waarin een installatie zich bevindt|Ja     |


**Relaties met andere objecttypen** 

|Relatiesoort     |Relatierol |Verplicht|
|---|---|---|
|hoort bij|gebouw|ja|



**Domeinwaarden**

*Type* 

|Waarde Type | Beschrijving Type    |
|---|---|
|**verplicht**||
|Kast|Constructie met een permanent karakter dat dient om iets in te bergen en te beschermen|
|Sirene|Installatie welke geluiden van variabele toonhoogte kan voortbrengen om de bevolking te waarschuwen voor gevaarlijke situaties|
|Verlichtingsarmatuur|Installatie bedoeld voor verlichten van de openbare ruimte|
|Windturbine|Turbine waarin winddruk omgezet wordt in mechanische energie|
|**vrijwillig**||
|Lift| Installatie gericht op het verticaal vervoeren van personen en goederen|
|Oplaadpunt| Systeem voor opladen van elektrische auto's |
|Pomp|Technische inrichting om vloeistoffen en/of gassen te verplaatsen|
|Zonnepanelen| Installatie om zonne-energie om te zetten in energie |


*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd




#### Mast

Dit SOR-begrip is een nader type van de NEN 3610- hoofdklasse Constructie 

 

**Definitie**

| Naam    | Mast    |
|---|---|
| Definitie | Hoge draagconstructie voor een installatie of het transport van energie en elektromagnetische straling |
|Herkomst definitie    |    nieuw     |
|Verplicht    | Ja    |
|Gevolgen afbakening    | Het betreft hier een samenvoeging van een subset van de bestaande populaties *overig bouwwerk, kunstwerkdeel en mast* zoals deze zijn opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|    |

**Eigenschappen**

|Eigenschap     |Beschrijving     |Verplicht     |
|---|---|---|
|Identificatie     |Unieke aanduiding van een mast|Ja |
|Geometrie|Geometrische representatie van de mast|Ja (2,5D punt, multipunt , lijn, vlak of multivlak )|
|Indicatie Open    	|Geeft aan of een mast al dan niet open is|	Ja|
|Status     | Fase van de levenscyclus waarin een mast zich bevindt|Ja     |

**Domeinwaarden**


*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd



#### Muur
    

Dit SOR-begrip is een nader type van de NEN 3610- hoofdklasse Constructie 

 
**Definitie**

| Naam    | Muur |
|---|---|
| Definitie |Constructie die een relatief smal, rechtopstaand bouwwerk betreft|
|Herkomst definitie    |Gebaseerd op Basisregistratie Topografie: Catalogus en Productspecificaties (versie 1.2.0.1)|
|Verplicht    | Ja    |
|Gevolgen afbakening    | Het betreft hier grotendeels de bestaande populatie *scheidingen, type muur en type kademuur, en kunstwerkdeel, type keermuur* zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|     |

**Eigenschappen**

|Eigenschap     |Beschrijving     |Verplicht     |
|---|---|---|
| Identificatie     |Unieke aanduiding van een muur|Ja |
| Geometrie|Geometrische representatie van een muur|Ja (2,5D lijn) Nee (2,5D vlak)|
| Indicatie Valbescherming| Muur die al dan niet bedoeld is om vallen te voorkomen |	Ja|
| Status     | Fase van de levenscyclus waarin een muur zich bevindt|Ja     |

**Relaties met andere objecttypen** 

|Relatiesoort     |Relatierol |Verplicht|
|---|---|---|
| heeft mogelijk een functie| kering| Ja|
| heeft mogelijk een functie| afscheiding|Ja|


**Domeinwaarden**

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd





 

#### Omheining


Dit SOR-begrip is een nader type van de NEN 3610- hoofdklasse Constructie 

 

**Definitie**

| Naam    | Omheining |
|---|---|
| Definitie | Kunstmatige verticale constructie die bedoeld is om de toegang tot een gebied te weren|
|Herkomst definitie    |nieuw|
|Verplicht    | Nee |
|Gevolgen afbakening    | Het betreft hier grotendeels de bestaande populatie    *scheidingen, Type hek en Type draadraster, faunaraster* zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|    |

**Eigenschappen**

|Eigenschap     |Beschrijving     |Verplicht     |
|---|---|---|
|Identificatie     |Unieke aanduiding van een omheining|Ja |
|Geometrie|Geometrische representatie van een omheining|Ja (2,5D lijn)|
| Indicatie Valbescherming| Omheining die al dan niet bedoeld is om vallen te voorkomen |	Ja|
|Status     | Fase van de levenscyclus waarin een omheining zich bevindt|Ja     |


**Relaties met andere objecttypen** 

|Relatiesoort     |Relatierol |Verplicht|
|---|---|---|
| heeft mogelijk een functie| afscheiding  | Ja|


**Domeinwaarden**

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd



#### Opslagtank

Dit SOR-begrip is een nader type van de NEN 3610- hoofdklasse Constructie 

 

**Definitie**

| Naam    | Opslagtank    |
|---|---|
| Definitie | Constructie in de vorm van een bovengronds, afgesloten reservoir bestemd voor gassen, energie of vloeistoffen|
|Herkomst definitie    | IMGeo 2.2    |
|Verplicht    | Ja    |
|Gevolgen afbakening    | Het betreft hier de bestaande populatie overig bouwwerk, type opslagtank zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|    |

**Eigenschappen**

|Eigenschap     |Beschrijving     |Verplicht     |
|---|---|---|
|Identificatie     |Unieke aanduiding van een opslagtank|Ja |
|Geometrie|Geometrische representatie van een opslagtank|Ja (2,5D vlak)|
|Status     | Fase van de levenscyclus waarin een opslagtank zich bevindt|Ja     |

**Domeinwaarden**

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd



#### Paal

Dit SOR-begrip is een nader type van de NEN 3610- hoofdklasse Constructie 

 

**Definitie**

| Naam    | Paal    |
|---|---|
| Definitie | Lage draagconstructie voor onder meer installaties of borden |
|Herkomst definitie    |    nieuw |
|Verplicht    | Nee    |
|Gevolgen afbakening    | Het betreft hier een samenvoeging van een subset van de bestaande populaties palen en borden zoals deze zijn opgenomen in de basisregistratie grootschalige topografie |
|Toelichting|    |

**Eigenschappen**

|Eigenschap     |Beschrijving     |Verplicht     |
|---|---|---|
|Identificatie     |Unieke aanduiding van paal|Ja |
|Geometrie|Geometrische representatie van de paal|Ja (2,5D punt)|
|Status     | Fase van de levenscyclus waarin een paal zich bevindt|Ja     |

**Domeinwaarden**

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd




#### Putdeksel

Dit SOR-begrip is een nader type van de NEN 3610- hoofdklasse Constructie 

 

**Definitie**

| Naam    | Putdeksel    |
|---|---|
| Definitie | Afsluitende deel van een toegang tot een ingegraven constructie    of netwerk|
|Herkomst definitie    |     Afgeleid van de definitie van een put in IMGeo 2.2 |
|Verplicht    | Ja     |
|Gevolgen afbakening    | Het betreft hier een samenvoeging van de bestaande populatie *put* en van een subset van de bestaande populatie *weginrichtingselementen* zoals deze zijn opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|    |

**Eigenschappen**

|Eigenschap     |Beschrijving     |Verplicht     |
|---|---|---|
|Identificatie     |Unieke aanduiding van een putdeksel|Ja |
|Geometrie|Geometrische representatie van een putdeksel|Ja (2,5D punt)|
|Status     | Fase van de levenscyclus waarin een putdeksel zich bevindt|Ja     |

**Domeinwaarden**

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd






#### Reservoir

Dit SOR-begrip is een nader type van de NEN 3610- hoofdklasse Constructie 

 **Definitie**

| Naam    | Reservoir    |
|---|---|
| Definitie | Constructie voor het (tijdelijk) bergen van water|
|Herkomst definitie    |gebaseerd op IMBOR 2020 |
|Verplicht    | Nee    |
|Gevolgen afbakening    | Het betreft hier de bestaande populatie *overig bouwwerk, type bezinkbak en type bassin* zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|    |

**Eigenschappen**

|Eigenschap     |Beschrijving     |Verplicht     |
|---|---|---|
|Identificatie     |Unieke aanduiding van een reservoir|Ja |
|Geometrie|Geometrische representatie van een reservoir|Ja (2,5D vlak)|
|Status     | Fase van de levenscyclus waarin een reservoir zich bevindt|Ja     |

**Domeinwaarden**

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd



#### Scherm
    

Dit SOR-begrip is een nader type van de NEN 3610- hoofdklasse Constructie 

 

**Definitie**

| Naam    | Scherm |
|---|---|
| Definitie |Lineaire constructie specifiek bedoeld om te reduceren|
|Herkomst definitie    |nieuw|
|Verplicht    | Ja    |
|Gevolgen afbakening    | Het betreft hier grotendeels de bestaande populatie    *scheidingen, Type geluidscherm* zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|    |

**Eigenschappen**

|Eigenschap     |Beschrijving     |Verplicht     |
|---|---|---|
|Identificatie     |Unieke aanduiding van een scherm|Ja |
|Geometrie|Geometrische representatie van een scherm|Ja (2,5D lijn)|
|Status     | Fase van de levenscyclus waarin een scherm zich bevindt|Ja     |

**Relaties met andere objecttypen** 

|Relatiesoort     |Relatierol |Verplicht|
|---|---|---|
| heeft mogelijk een functie| reducering |Ja|

**Domeinwaarden**



*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd



#### Straatmeubilair

Dit SOR-begrip is een nader type van de NEN 3610- hoofdklasse Constructie 

 

**Definitie**

| Naam    | Straatmeubilair    |
|---|---|
| Definitie | Constructie ter inrichting van de openbare ruimte niet verbonden met ondergrondse objecten|
|Herkomst definitie    |    Gebaseerd op IMGeo 2.2    |
|Verplicht    | Nee    |
|Gevolgen afbakening    | Het betreft hier een subset van de bestaande populaties *bak* en *straatmeubilair* zoals deze zijn opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|    |

**Eigenschappen**

|Eigenschap     |Beschrijving     |Verplicht     |
|---|---|---|
|Identificatie     |Unieke aanduiding van straatmeubilair|Ja |
|Geometrie|Geometrische representatie van het straatmeubilair|Ja (2,5D punt)|
|Type    	|Typering van straatmeubilair	|Nee|
|Status     | Fase van de levenscyclus waarin straatmeubilair zich bevindt|Ja     |

**Domeinwaarden**

*Type*

| Waarde Type    | Beschrijving Type    |
|---|---|
|Abri	|Overdekte wachtplaats voor passagiers van het openbaar vervoer|
|Afvalbak| Bak of korf in de openbare ruimte met een permanent karakter; bedoeld voor het verzamelen van (meestal los) afval|
|Bank 	|Aaneengesloten zitplaats voor verscheidene personen, bedoeld voor openbaar gebruik en geplaatst in de openbare ruimte (vnl. in parken, plantsoenen, bossen en langs wegen)|
|Fietsen parkeerplaats|	Voorziening in de openbare ruimte voor het stallen van fietsen|
|Fontein	|Natuurlijke of kunstmatige installatie die water spuit|
|Herdenkingsmonument	|Langs de weg of elders in het terrein aangelegd object ter herdenking van personen of gebeurtenissen|
|Kunstobject	|Object dat als kunst gezien wordt en een bepaalde schoonheid heeft, niet door de natuur gemaakt|
|Openbaar toilet	|Voor mensen bedoeld toilet niet zijnde een gebouw, langs de openbare weg|
|Picknicktafel	|Tafel met vaak daaraan gemonteerde zitbanken of stoelen die kan gebruikt worden om te picknicken, bedoeld voor openbaar gebruik en geplaatst in de openbare ruimte (vnl. in parken, plantsoenen, bossen en langs wegen)|
|Speelvoorziening	|Aard en nagelvast met de grond verbonden constructie in de openbare ruimte, bedoeld als speelmateriaal voor kinderen|



*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd





#### Zwembad
    

Dit SOR-begrip is een nader type van de NEN 3610- hoofdklasse Constructie 

 
**Definitie**


| Naam    | Zwembad  |
|---|---|
| Definitie | Constructie in de vorm van een bassin bedoeld om in te zwemmen | 
| Herkomst definitie| |nieuw|
| Verplicht    | Ja  |
| Gevolgen afbakening    | Het betreft hier deels de bestaande populatie overig bouwwerk type bassin zoals deze is opgenomen in de basisregistratie grootschalige topografie |
| Toelichting| In een later stadium zullen registratieregels worden opgesteld waarin een nadere invulling wordt gegeven aan de interpretatie die aan zwembad moet worden gegeven. Daarbij zal ook nader worden bepaald in welke gevallen overdekte zwembaden in de registratie worden opgenomen. |

**Eigenschappen**

|Eigenschap     |Beschrijving     |Verplicht     |
|---|---|---|
| Identificatie     |Unieke aanduiding van een zwembad|Ja |
| Geometrie|Geometrische representatie van een zwembad| Ja (2,5D vlak)|
| Status     | Fase van de levenscyclus waarin een zwembad zich bevindt|Ja     |


*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd.




### Onbepaald terrein


 

**Definitie**

| Naam    | Onbepaald terrein    |
|---|---|
| Definitie | Fysiek begrensd en zichtbaar terrein dat bij een gebouw hoort, dat niet verder wordt gedetailleerd in andere reële objecten en dat bestaat uit een mengvorm van verharding, water, begroeiing en/of constructies|
|Herkomst definitie    | Gebaseerd op definitie van erf in BGT |
|Verplicht    | Ja    |
|Gevolgen afbakening    | Het betreft hier de bestaande populatie *Erf* zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting| In plaats van onbepaald terrein kan ter plaatse ook de reële topografie worden ingewonnen (vrijwillig).|

**Eigenschappen**
 
|Eigenschap     |Beschrijving     |Verplicht     |
|---|---|---|
|Identificatie     |Unieke aanduiding van een onbepaald terrein|Ja |
|Geometrie|Geometrische representatie van een onbepaald terrein|Ja (2,5D vlak)|
|Status     |Fase van de levenscyclus waarin een onbepaald terrein zich bevindt|Ja     |



**Domeinwaarden**

*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van reële objecten zijn benoemd

