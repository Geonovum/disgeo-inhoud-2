## Fysieke objecttypen

In dit hoofdstuk is een eerste aanzet opgenomen tot nadere Typering van de verschillende fysieke objecttypen in de samenhangende objectenregistratie. Deze aanzet is primair gebaseerd op de ook nu reeds in de bestaande basisregistraties gehanteerde Typeringen. Vanwege een strikte scheiding tussen fysieke objecttypen en functionele objecttypen zijn op deze Typeringen soms beperkte aanpassingen doorgevoerd. Ook zijn enkele eerste wijzigingen voorgesteld die het gevolg zijn van het in hoofdstuk 2 genoemde uitgangspunt over heldere definiëring. Tenslotte is daar waar mogelijk reeds bekeken in hoeverre aanpalende sectorale Typeringen aanleiding kunnen geven tot een aangescherpte Typering. 

Deze Typering is in deze fase van het traject vooral bedoeld om een eerste indruk te geven van de richting waarin de inhoud van de samenhangende objectenregistratie zich beweegt. Samen met experts vanuit de verschillende domeinen en gebruikers zal in het vervolg nog nader onderzoek noodzakelijk zijn om tot definitieve Typeringen met bijbehorende definities te komen. Ook zal daarbij nog moeten worden bepaald in hoeverre het nu opgenomen onderscheid tussen de verplichte classificatie en de vrijwillige classificatie aanpassing behoeft. Hierbij is het uiteindelijk de bedoeling om te komen tot een “uitklapmodel” van Typeringen, waarbij gedetailleerde Typeringen (in de samenhangende objectenregistratie, maar bij voorkeur ook in sectorale registraties) altijd een nadere uitwerking vormen van één bepaalde hoofdTypering (in de samenhangende objectenregistratie).

### Bodem

#### Bodem

| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Bodem |
| Onderdeel van NEN3610-objecttype |  Bodem  |

ontwerpprincipe: 

<div class='note'>
    begrip Bodem nog bediscussieren in de werkgroep Inhoud
</div>


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
|---|---|
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
|Geometrie |De geometrische representatie van de randen van een gebouw   |Ja (3D)|
|Typering |Het doel waarvoor een gebouw gebruikt wordt  |Ja|
|Aard|De fysieke verschijningsvorm van een gebouw  |Ja|
|Oorspronkelijk bouwjaar | De aanduiding van het jaar waarin een gebouw oorspronkelijk als bouwkundig gereed is of zal worden opgeleverd|Ja|
|Naam| Een breed geaccepteerde benaming van een gebouw zoals deze door de eigenaar is toegekend of zoals deze in de volksmond bekend staat| Nee|
|Status   |De fase van de levenscyclus waarin het gebouw zich bevindt    |Ja   |
| Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
||||

**Domeinwaarden**

<div class='note'>
    De definitieve lijst met TYPE en AARD zal op een later moment worden opgeleverd. Het is daarbij de bedoeling dat deze lijst aansluit op de bij de WOZ in ontwikkeling zijnde lijst met domeinwaarden voor WOZ-deelobjecten. Ook moet nog een nadere uitlijning op typeringen vanuit de BRT plaatsvinden. Onderstaande domeinwaarden zijn uitsluitend voorbeelden van enkele waarschijnlijke typeringen om een indruk te geven van het soort waarden dat hier zal worden opgenomen.
</div>


| Waarde Typering| Beschrijving   |
|---|---|
| Woning| |
| Bedrijf ||

.

|Waarde Aard|	Beschrijving|
|---|---|
|Vrijstaand gebouw||	
|Aangrenzende gelijksoortige gebouwen||	
|Onderdeel heterogeen gebouwblok||

.

|Waarde status	|Beschrijving|
|---|---|
|Gepland|	Een gebouw dat zich in de ontwerpfase bevindt en waarvoor nog geen vergunning tot bouw is verleend|
|Bouwvergunning verleend|	Een gebouw dat nog niet is gebouwd maar waarvoor wel een vergunning tot bouw is verleend|
|Sloopvergunning verleend|	Een gebouw waarvoor een vergunning tot sloop is verleend|
|In aanbouw|	Een gebouw waarvan de feitelijke bouw is aangevangen door minimaal de aanleg van de fundering (waartoe niet het bouwrijp maken van een terrein wordt gerekend).|
|Bestaand|	Een gebouw dat is gebruik is genomen of als gebruiksgereed kan worden beschouwd|
|In verbouw|	Een gebouw waarvoor een vergunning tot verbouw is verleend en waarbij de verbouwing nog niet is voltooid|
|Gesloopt|	Een gebouw waarvan de feitelijke sloop is afgerond|
|Niet gerealiseerd|	Een gebouw waarvoor een bouwvergunning was verleend, maar waarvan is vastgesteld dat wordt afgezien van de bouw of waarvan de bouwvergunning is ingetrokken|
|Ten onrechte|	Gebouw is ten onrechte opgevoerd in de registratie|



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
|Geometrie |De geometrische representatie van de randen van een Bouwlaag  |Ja (2,5D)|
|Bouwlaagnummer |Het niveau waarop de bouwlaag zich bevindt|Ja|
|Status   |De fase van de levenscyclus waarin een Bouwlaag zich bevindt   |Ja   |
| Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|Ligt in|Gebouw| Ja|

**Domeinwaarden**

<div class='note'>
    In het kader van de review wordt u gevraagd om aan te geven of onderstaande statussen naar uw mening allemaal noodzakelijk zijn of dat volstaan kan worden met een beperkter aantal statussen (bijvoorbeeld gepland, bestaand, gesloopt en ten onrechte)
</div>


|Waarde status	|Beschrijving|
|---|---|
|Gepland|	Een bouwlaag dat zich in de ontwerpfase bevindt en waarvoor nog geen vergunning tot bouw is verleend|
|Bouwvergunning verleend|	Een bouwlaag die nog niet is gebouwd maar waarvoor wel een vergunning tot bouw is verleend|
|Sloopvergunning verleend|	Een bouwlaag waarvoor een vergunning tot sloop is verleend|
|In aanbouw|	Een bouwlaag waarvan de feitelijke bouw is aangevangen| 
|Bestaand|	Een bouwlaag die is gebruik is genomen of als gebruiksgereed kan worden beschouwd|
|In verbouw|	Een bouwlaag waarvoor een vergunning tot verbouw is verleend en waarbij de verbouwing nog niet is voltooid|
|Gesloopt|	Een bouwlaag waarvan de feitelijke sloop is afgerond|
|Niet gerealiseerd|	Een bouwlaag waarvoor een bouwvergunning was verleend, maar waarvan is vastgesteld dat wordt afgezien van de bouw of waarvan de bouwvergunning is ingetrokken|
|Ten onrechte|	Bouwlaag is ten onrechte opgevoerd in de registratie|



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
|Geometrie |De geometrische representatie van de randen van een Ruimte   |Ja (2,5D)|
|Typering|Het doel waarvoor een ruimte gebruikt wordt|Ja|
|Bouwlaagnummer |De bouwlaag waarop de ruimte zich bevindt|Ja|
|Oppervlakte| De gebruiksoppervlakte van de ruimte| Nee |
|Status   |De fase van de levenscyclus waarin een Ruimte zich bevindt   |Ja   |
| Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|Ligt op|Bouwlaag| Ja|

**Domeinwaarden**

<div class='note'>
    De definitieve lijst met TYPE zal op een later moment worden opgeleverd. Het is daarbij de bedoeling dat deze lijst aansluit op de begrippen zoals deze in BIM modellen voor de bouw worden gehanteerd. Onderstaande domeinwaarden zijn uitsluitend voorbeelden van enkele waarschijnlijke typeringen om een indruk te geven van het soort waarden dat hier zal worden opgenomen.
</div>



| Waarde Typering| Beschrijving   |
|---|---|
|Woonkamer| |
|Keuken ||

<div class='note'>
    In het kader van de review wordt u gevraagd om aan te geven of onderstaande statussen naar uw mening allemaal noodzakelijk zijn of dat volstaan kan worden met een beperkter aantal statussen (bijvoorbeeld gepland, bestaand, gesloopt en ten onrechte)
</div>


|Waarde status	|Beschrijving|
|---|---|
|Gepland|	Een ruimte dat zich in de ontwerpfase bevindt en waarvoor nog geen vergunning tot bouw is verleend|
|Bouwvergunning verleend|	Een ruimte die nog niet is gebouwd maar waarvoor wel een vergunning tot bouw is verleend|
|Sloopvergunning verleend|	Een ruimte waarvoor een vergunning tot sloop is verleend|
|In aanbouw|	Een ruimte waarvan de feitelijke bouw is aangevangen| 
|Bestaand|	Een ruimte die is gebruik is genomen of als gebruiksgereed kan worden beschouwd|
|In verbouw|	Een ruimte waarvoor een vergunning tot verbouw is verleend en waarbij de verbouwing nog niet is voltooid|
|Gesloopt|	Een ruimte waarvan de feitelijke sloop is afgerond|
|Niet gerealiseerd|	Een ruimte waarvoor een bouwvergunning was verleend, maar waarvan is vastgesteld dat wordt afgezien van de bouw of waarvan de bouwvergunning is ingetrokken|
|Ten onrechte|	Ruimte is ten onrechte opgevoerd in de registratie|


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
|Verplicht  | Deels (nog nader te bepalen welke onderdelen) |
|Gevolgen afbakening  | Het betreft hier ten opzichte van de bestaande basisregistraties grotendeels een nieuw objecttype. *Nog nader bepaald zal worden hoe we een en ander afstemmen op het BGT objecttype gebouwdeel en op het feit dat installaties ook bij andere objecten dan gebouwen kunnen behoren*|
|Toelichting| *volgt later* |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een Installatie  |Ja |
|Geometrie |De geometrische representatie van de randen van een Installatie   |Ja (1,5D of 2,5D)|
|Aard|Het soort installatie|Ja |
|Bijbehorend object |Het object waarbij de betreffende installatie behoort|Ja|
|Status   |De fase van de levenscyclus waarin de betreffende installatie zich bevindt   |Ja   |
| Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|Hoort bij|Verblijfsobject|Ja|
|Hoort bij|Gebouw|Ja|

**Domeinwaarden**

<div class='note'>
    De definitieve lijst met AARD zal op een later moment worden opgeleverd. Het is daarbij de bedoeling dat deze lijst aansluit op de begrippen zoals deze elders worden gehanteerd. Onderstaande domeinwaarden zijn uitsluitend voorbeelden van enkele waarschijnlijke typeringen om een indruk te geven van het soort waarden dat hier zal worden opgenomen.

    In het kader van de review wordt u gevraagd om aan te geven welke “installaties” naar uw mening van belang zijn om in een basisregistratie op te nemen
</div>


| Waarde Aard| Beschrijving   |
|---|---|
|zonnepanelen < 5 kWp| |
|zonnepanelen > 5 kWp| |
|dakkapel ||
|lift||
|luifel|Afdak aangebracht aan de gevel van een pand, eventueel rustend op kolommen.|
|bordes|Een verhard oppervlak, eventueel verhoogd en/of uitgevoerd met treden, grenzen aan een pand en primair bedoeld voor gebruik door voetgangers.|
|toegangstrap|Niet afsluitbare trap (of trappenhuis) die toegang biedt aan een gebouw.|


<div class='note'>
    In het kader van de review wordt u gevraagd om aan te geven of onderstaande statussen naar uw mening allemaal noodzakelijk zijn of dat volstaan kan worden met een beperkter aantal statussen (bijvoorbeeld gepland, bestaand, gesloopt en ten onrechte)
</div>


|Waarde status	|Beschrijving|
|---|---|
|Gepland|	Een installatie dat zich in de ontwerpfase bevindt en waarvoor nog geen vergunning tot bouw is verleend|
|Bouwvergunning verleend|	Een installatie die nog niet is gebouwd maar waarvoor wel een vergunning tot bouw is verleend|
|Sloopvergunning verleend|	Een installatie waarvoor een vergunning tot sloop is verleend|
|In aanbouw|	Een installatie waarvan de feitelijke bouw is aangevangen| 
|Bestaand|	Een installatie die is gebruik is genomen of als gebruiksgereed kan worden beschouwd|
|In verbouw|	Een installatie waarvoor een vergunning tot verbouw is verleend en waarbij de verbouwing nog niet is voltooid|
|Gesloopt|	Een installatie waarvan de feitelijke sloop is afgerond|
|Niet gerealiseerd|	Een installatie waarvoor een bouwvergunning was verleend, maar waarvan is vastgesteld dat wordt afgezien van de bouw of waarvan de bouwvergunning is ingetrokken|
|Ten onrechte|	Installatie is ten onrechte opgevoerd in de registratie|


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
|Verplicht  | Deels (nog nader te bepalen welke onderdelen) |
|Gevolgen afbakening  | Het betreft hier ten opzichte van de bestaande basisregistraties grotendeels een nieuw objecttype.  *Bekeken zal nog moeten worden in hoeverre we dit objecttype ook willen relateren aan objecten als kunstwerken en andere constructies.*|
|Toelichting| *volgt later* |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een Toegangsdeur  |Ja |
|Geometrie |De geometrische representatie van een Toegangsdeur   |Ja (1,5D)|
|Toegangssoort|De plaats waarvan de toegangsdeur toegang geeft|Ja|
|Gebruiksaard|De aard van gebruik van de  toegangsdeur|Ja|
|Bijbehorend object |Het object waarin de betreffende toegangsdeur zich bevindt|Ja|
|Status   |De fase van de levenscyclus waarin de betreffende Toegangsdeur zich bevindt   |Ja   |
| Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|Hoort bij|Verblijfsobject| Ja|
|Hoort bij|Gebouw| Ja|

**Domeinwaarden**

| Waarde Toegangssoort| Beschrijving   |
|---|---|
|directe toegang vanaf eigen terrein|de toegangsdeur bevindt zich op een erf, in een tuin of een andere specifiek terrein dat behoort bij het gebouw |
|directe toegang vanaf openbare weg|de toegangsdeur bevindt zich direct aan een voor iedereen toegankelijke weg |
|toegang vanaf gemeenschappelijke verkeersruimte |de toegangsdeur bevindt zich aan een inpandige ruimte die bedoeld is voor verplaatsingen door een gebouw door de verschillende gebruikers van dit gebouw  |

.

| Waarde Gebruiksaard| Beschrijving   |
|---|---|
|Personen|de toegangsdeur is primair bedoeld voor toegang tot een object door personen |
|Auto|de toegangsdeur is primair bedoeld voor toegang tot een object door voertuigen |
|Vracht|de toegangsdeur is primair bedoeld voor toegang tot een object door vracht zonder gebruik van een voertuig|

.

|Waarde status	|Beschrijving|
|---|---|
|Gepland|	Een toegangsdeur die zich in de ontwerpfase bevindt|
|Bestaand|	Een installatie die is gebruik is genomen of als gebruiksgereed kan worden beschouwd|
|Verwijderd|	Een toegangsdeur die feitelijk is verwijderd|
|Niet gerealiseerd|	Een geplande toegangsdeur die niet als zodanig is gerealiseerd|
|Ten onrechte|	Toegangsdeur is ten onrechte opgevoerd in de registratie|



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
|---|---|
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



#### Bak
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Bak  |
| Onderdeel van NEN3610-objecttype |Constructie  |

ontwerpprincipe: 

**Definitie**

| Naam  | Bak  |
|---|---|
| Definitie | Object met een permanent karakter dat dient om iets in te bergen of te verzamelen. |
|Herkomst definitie  | definities.geostandaarden.nl   |
|Verplicht  | Nee  |
|Gevolgen afbakening  | Het betreft hier een subset van de bestaande populatie *bak* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip bak |Ja |
|Geometrie|De geometrische representatie van de locatie van bak. *nader te preciseren op basis van generieke uitspraken over de vastlegging van geometrie* |Ja (punt)|
|Status   |   |Ja   |
|Type bak|Aanduiding soort bak|Nee|
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

|Waarde Type Bak| Beschrijving   |
|---|---|
|bassin|Bekken met een ondoorlaatbare bodem waarin water opgelagen kan worden. |
|afval apart plaats|Boven- of ondergrondse opslagplaats voor het gescheiden inzamelen van afval, met stortkoker(s) op het straatniveau.|
|container|Nagelvast met de grond verbonden inzamelmiddel voor afvalstoffen, doorgaans van metaal of kunststof waarin afvalstoffen worden verzameld, bewaard en waaruit deze afvalstoffen vervolgens worden overgeladen in een inzamelvoertuig.|





#### Deksel
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Deksel  |
| Onderdeel van NEN3610-objecttype |Constructie  |

ontwerpprincipe: 

**Definitie**

| Naam  | Deksel  |
|---|---|
| Definitie | Het afsluitende deel van een gegraven, koker of lijnvormige constructie waarin zich (vloei)stoffen kunnen bevinden. |
|Herkomst definitie  |     |
|Verplicht  | Nee  |
|Gevolgen afbakening  | Het betreft hier een samenvoeging van de bestaande populatie *put* en van een subset van de bestaande populatie *weginrichtingselementen* zoals deze zijn opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip deksel |Ja |
|Geometrie|De geometrische representatie van de ligging van het deksel. *nader te preciseren op basis van generieke uitspraken over de vastlegging van geometrie* |Ja (punt, lijn, vlak)|
|Status   |   |Ja   |
|Type deksel|aanduiding soort deksel |Ja|
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

|Waarde Type deksel| Beschrijving   |
|---|---|
|benzine-/olieput|Putdeksel die toegang geeft tot een benzine- of olietank ten behoeve van vullen, onderhoud of inspectie. |
|brandkraan/-put|Op de drinkwaterleiding aangesloten kraan, of put voor het plaatsen van een brandkraan.|
|drainageput|Put welke toegang geeft naar een poreuze of geperforeerde buisleiding, aangebracht onder de grond om de afwatering van de grond te verbeteren.|
|gasput|Put met afsluitkraan ten behoeve van het ondergrondse leidingenstelsel voor gastransport.|
|inspectie-/rioolput|Put die toegang geeft tot een (riool)leiding. |
|kolk|Op het riool aangesloten voorziening voor de opvang van hemel- en afvalwater afkomstig van erop aangesloten oppervlakken.|
|waterleidingput|Put met afsluitkraan ten behoeve van het ondergrondse leidingenstelsel voor watertransport.|
|lijnafwatering|Voorziening voor het afvoeren van overtollig hemel- en afvalwater afkomstig van erop aangesloten oppervlakken.|
|rooster|Evenwijdig of kruiselings lopende staafconstructie voor het tegenhouden van vuil uit hemel- en afvalwater.|



#### Depot
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Depot  |
| Onderdeel van NEN3610-objecttype |Constructie  |

ontwerpprincipe: 

**Definitie**

| Naam  | Depot  |
|---|---|
| Definitie | Object met een permanent karakter dat dient om gassen, energie, vaste- en vloeistoffen in te bergen of te verzamelen. |
|Herkomst definitie  |   |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier een subset van de bestaande populatie *overig bouwwerk* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip depot |Ja |
|Geometrie|De geometrische representatie van de locatie van depot. *nader te preciseren op basis van generieke uitspraken over de vastlegging van geometrie* |Ja (punt)|
|Status   |   |Ja   |
|Type bak|Aanduiding soort depot|Nee|
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

|Waarde Type Depot| Beschrijving   |
|---|---|
|opslagtank|Bovengrondse opslagfaciliteit voor gassen, energie en vloeistoffen. |
|voedersilo|Opslagfaciliteit voor vaste stoffen (bijvoorbeeld veevoer), bestaande uit een verticale container met een opening aan de onderkant.|


#### Geleider
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Geleider  |
| Onderdeel van NEN3610-objecttype |Constructie  |

ontwerpprincipe: 

**Definitie**

| Naam  | Geleider  |
|---|---|
| Definitie | Een constructie bedoeld voor de fysieke (be)geleiding van voer-, vaartuigen. |
|Herkomst definitie  |     |
|Verplicht  | Nee  |
|Gevolgen afbakening  | Het betreft hier een samenvoeging van een subset van de bestaande populaties *waterinrichtingselementen* en *weginrichtingselementen* zoals deze zijn opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip geleider |Ja |
|Geometrie|De geometrische representatie van de ligging van de geleider. *nader te preciseren op basis van generieke uitspraken over de vastlegging van geometrie* |Ja (lijn, vlak)|
|Status   |   |Ja   |
|Type geleider|aanduiding soort geleider|Nee|
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

|Waarde Type geleider| Beschrijving   |
|---|---|
|remmingswerk|Constructie langs de opstelruimte en wachtruimte bedoeld voor het afmeren van schepen. |
|geleidewerk|Fuikvormige constructie aansluitend aan het hoofd van een kunstwerk voor het geven van mechanische en visuele geleiding tijdens het invaren van dat kunstwerk.|
|geleideconstructie|Bermbeveiligingsconstructie bedoeld voor fysieke geleiding van voertuigen die uit de koers zijn geraakt.|
|verblindingswering|Constructie bedoeld om verblinding van weggebruikers door tegenlicht te voorkomen.|


#### Installatie
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Installatie  |
| Onderdeel van NEN3610-objecttype |Constructie  |

ontwerpprincipe: 

**Definitie**

| Naam  | Installatie  |
|---|---|
| Definitie | Een technisch, samenhangend systeem, al dan niet binnen een bestaande inrichting, dat een bepaald doel dient. |
|Herkomst definitie  |     |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier een samenvoeging van een subset van de bestaande populaties *kunstwerkdelen* en *installatie* zoals deze zijn opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip installatie |Ja |
|Geometrie|De geometrische representatie van de ligging van de installatie of van de randen van de installatie. *nader te preciseren op basis van generieke uitspraken over de vastlegging van geometrie* |Ja (punt, lijn, vlak)|
|Status   |   |Ja   |
|Type installatie|aanduiding soort installatie |Ja|
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

|Waarde Type installatie| Beschrijving   |
|---|---|
|pomp|Technische inrichting om vloeistoffen en/of gassen te verplaatsen.|


#### Mast
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Mast  |
| Onderdeel van NEN3610-objecttype |Constructie  |

ontwerpprincipe: 

**Definitie**

| Naam  | Mast  |
|---|---|
| Definitie | Een hoge draagconstructie voor de opwekking en transport van energie en elektromagnetische straling. |
|Herkomst definitie  |     |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier een samenvoeging van een subset van de bestaande populaties *gebouwen*, *kunstwerkdelen* en *mast* zoals deze zijn opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip mast |Ja |
|Geometrie|De geometrische representatie van de ligging van de mast of van de randen van de mast. *nader te preciseren op basis van generieke uitspraken over de vastlegging van geometrie* |Ja (punt, lijn, vlak)|
|Status   |   |Ja   |
|Type installatie|aanduiding soort mast |Ja|
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

|Waarde Type installatie| Beschrijving   |
|---|---|
|windturbine|Moderne hoge windmolen waarin winddruk wordt omgezet in mechanische energie. |
|hoogspanningsmast|Metalen mast of stellage ter ondersteuning van geleidedraden voor het transport van elektriciteit met een hoog voltage.|
|laagspanningsmast|Houten of metalen mast waaraan kabels voor het transport van elektrische energie met een spannning lager dan 500 V zijn bevestigd.|
|bovenleidingmast|Mast die een onderdeel vormt van de bovenleidingdraagconstructie voor het openbaar vervoer (trein, tram, bus).|
|straalzender|Een hoge constructie die wordt gebruikt voor het uitzenden van radio, televisie en telecommunicatie signalen. |
|zendmast|Een hoge constructie die wordt gebruikt voor het bevestigen van antennes voor telecommunicatie.|
|radarmast| Een hoge constructie die wordt gebruikt voor het bevestigen van radarantennes.|
|sirene| Een hoge constructie die wordt gebruikt voor het bevestigen van sirenes.|


#### Straatmeubilair
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Straatmeubilair  |
| Onderdeel van NEN3610-objecttype |Constructie  |

ontwerpprincipe: 

**Definitie**

| Naam  | Straatmeubilair  |
|---|---|
| Definitie | Een ruimtelijk object ter inrichting van de openbare ruimte. |
|Herkomst definitie  |  imgeo.geostandaarden.nl   |
|Verplicht  | Nee  |
|Gevolgen afbakening  | Het betreft hier een subset van de bestaande populaties *bak*, *paal* en *straatmeubilair* zoals deze zijn opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip straatmeubilair |Ja |
|Geometrie|De geometrische representatie van de locatie van het straatmeubilair. *nader te preciseren op basis van generieke uitspraken over de vastlegging van geometrie* |Ja (punt)|
|Status   |   |Ja   |
|Type installatie|aanduiding soort straatmeubilair |Nee|
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

|Waarde Type installatie| Beschrijving   |
|---|---|
|afvalbak|Bak of korf in de openbare ruimte met een permanent karakter; bedoeld voor het verzamelen van (meestal los) afval. |
|bloembak|Bak in de openbare ruimte met een permanent karakter, waarin planten of struiken zijn geplant.|
|zand-/zoutbak|Een bak met strooisel ten behoeve van gladheidsbestrijding.|
|poller|Een inzinkbare paal die door een elektrische of hydraulische aandrijving uit een wegdek omhoog wordt gestuurd en die dient om het autoverkeer te reguleren.|
|abri|Overdekte wachtplaats voor passagiers van het openbaar vervoer. |
|brievenbus|Uitpandige kast waar post in kan worden gedeponeerd ter bezorging.|
|fietsenrek|Een duurzaam verankerd rek in de openbare ruimte voor het stallen van (brom)fietsen.|
|kunstobject|Een object dat als kunst gezien wordt en een bepaalde schoonheid heeft, niet door de natuur gemaakt.|
|openbaar toilet|Voor mensen bedoeld toilet niet zijnde een pand, langs de openbare weg.|
|slagboom|Boom of balk om de weg of een gedeelte hiervan af te sluiten. |
|speelvoorziening|Aard en nagelvast met de grond verbonden constructie in de openbare ruimte, bedoeld als speelmateriaal voor kinderen.|
|telefooncel|Niet-inpandige ruimte in openbaar gebied louter bestemd voor telefoneren.|
|bank|Aaneengesloten zitplaats voor verscheidene personen, bedoeld voor openbaar gebruik en geplaatst in de openbare ruimte (vnl. in parken, plantsoenen, bossen en langs wegen).|
|picknicktafel|Een tafel met vaak daaraan gemonteerde zitbanken of stoelen die kan gebruikt worden om te picknicken. |
|fontein|Een fontein is een natuurlijke of kunstmatige installatie die water spuit.|
|lichtpunt|Een lichtpunt is een voorziening die licht uitzendt niet verbonden met een mast die het maaiveld raakt.|
|parkeerbeugel|Een omklapbare beugel voor het afschermen van een parkeerplaats.|
|betaalautomaat|Een apparaat dat betaalkaarten en/of contant geld accepteert om betalingen uit te voeren.|
|fietsenkluis|Een kluis om een fiets in te bewaren, meestal ter voorkoming van diefstal of beschadiging.|
|herdenkingsmonument|In het terrein aangelegd object ter herdenking van personen of evenementen.|


#### Sensor
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Sensor  |
| Onderdeel van NEN3610-objecttype |Constructie  |

ontwerpprincipe: 

**Definitie**

| Naam  | Sensor  |
|---|---|
| Definitie | Apparaat voor de meting van een fysieke grootheid (bijv. temperatuur, licht, druk, elektriciteit. |
|Herkomst definitie  | IMGeo 2.1.1    |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *sensor* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip sensor |Ja |
|Geometrie|De geometrische representatie van de sensor. *nader te preciseren op basis van generieke uitspraken over de vastlegging van geometrie* |Ja (punt)|
|Status   |   |Ja   |
|Type sensor|aanduiding soort sensor|Nee|
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

|Waarde Type sensor| Beschrijving   |
|---|---|
|hoogtedetectieapparaat|*Een mechanisch of elektronisch waarschuwingssysteem, dat in werking treedt bij overschrijding van de aangegeven maximale doorrijhoogte*|
|GMS sensor|*Gladheidsmeldsysteem (GMS) waarmee de kans op gladheid wordt voorspeld aan de hand van meting en interpretatie van de parameters die een rol spelen bij het ontstaan van gladheid.*|


#### Paal
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Paal  |
| Onderdeel van NEN3610-objecttype |Constructie  |

ontwerpprincipe: 

**Definitie**

| Naam  | Paal  |
|---|---|
| Definitie | Langwerpig stuk hout, ijzer, steen enz., dat in de grond staat. |
|Herkomst definitie  | IMGeo 2.1.1    |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *Paal* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip paal |Ja |
|Geometrie|De geometrische representatie van een paal. *nader te preciseren op basis van generieke uitspraken over de vastlegging van geometrie* |Ja (punt)|
|Status   |   |Ja   |
|Type paal|aanduiding soort paal|Nee|
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

|Waarde Type paal| Beschrijving   |
|---|---|
|informatiebord|*Een bord met daarop specifieke actuele informatie, zoals plattegronden of vertrektijden.*|
|plaatsnaambord|*Een bord waarop een naam van een (woon)plaats of locatie is vermeld*|
|straatnaambord|*Bord waarop de door de gemeente vastgestelde naam van de straat is vermeld. Bord kan zich op een paal of aan de gevel bevinden*|
|verkeersbord|*Bord waarop een verkeersteken is aangebracht en waarvan de uitvoering wettelijk is voorgeschreven volgens het ‘Reglement verkeersregels en verkeerstekens 1990 (RVV 1990)’.*|
|scheepvaartbord|*Bord waarop een scheepvaartteken is aangebracht en waarvan de uitvoering als richtlijn is voorgeschreven volgens ‘Richtlijnen Scheepvaarttekens (RST 2008)’.*|
|verklikker transportleiding|*Bovengrondse voorziening om een ondergrondse transportleiding te markeren.*|
|reclamebord|*Vrijstaand bord/zuil waarop rondom of aan één of meer zijden affiches kun worden (of zijn) geplakt.*|
|wegwijzer|*Constructie voorzien van een meer panelen met informatie ten behoeve van de bewegwijzering.*|
|dynamische snelheidsindicator|*Een snelheidsinformatiebord dat in “real time” de snelheid van de weggebruikers aanduidt.*|
|zonnepaneel|*Een zonnepaneel is een paneel dat zonne-energie omzet in elektriciteit.*|
|lichtmast|*Mast bestemd voor het dragen van een of meer verlichtingsarmaturen.*|
|telpaal|*Paal waaraan de verkeerstelle is bevestigd.*|
|portaal|*Geheel van twee of meer ondersteuningsconstructies die door een ligger zijn verbonden, bedoelt voor het aanbrengen van verkeersaanduidingen.*|
|verkeersregelinstallatiepaal|*Paal met daaraan bevestigd de verkeersregelinstallatie.*|
|verkeersbordpaal|*Paal waaraan een of meerdere verkeersborden zijn bevestigd.*|
|haltepaal|*Paal met daarop de dienstregeling ten behoeve van het openbaar vervoer.*|
|vlaggenmast|*Paal bedoeld om vlaggen aan te hangen.*|
|afsluitpaal|*Al dan niet verwijderbare paal in de grond om de weg of een gedeelte hiervan af te sluiten.*|
|praatpaal|*Stalen of kunststof paal langs verkeerswegen welke bedoeld is telefonisch contact te leggen met een centrale meldkamer (ANWB).*|
|hectometerpaal|*Paaltje of bordje geplaatst langs de weg, waarop een hectometerwaarde (weg) of kilometrering (vaarweg) is vermeld eventueel gevolgd door een letter.*|
|dijkpaal|*Een markant punt op de waterkering of op het strand dat dient als referentiepunt voor afstandsaanduidingen.*|
|drukknoppaal|*Paal met een lengte van ongeveer 1 m, met een drukknop waarmee de verkeersdeelnemer zich meldt bij een verkeersregelinstallatie.*|
|grensmarkering|*Paal ter afbakening van een grens.*|
|camera|*Installatie voor de registratie van beelden van situaties, waarvan directe observatie moeilijk of niet permanent mogelijk is.*|
|debietmeter|*Een instrument dat de (afvoer)capaciteit van de volumestroom meet.*|
|weerstation|*Een weerstation is een verzameling instrumenten die het weer kunnen meten.*|
|flitser|*Een flitser bevat een mechanisme om een snelheidsmeting uit te voeren om snelheidsovertredingen in het verkeer te kunnen vaststellen.*|
|waterstandmeter|*Een meter die de waterstand, over het algemeen ten opzichte van NAP, meet.*|
|windmeter|*Apparatuur waarmee de snelheid en de richting van de wind kan worden gemeten.*|
|lichtcel|*Lichtcel waarmee het verlichtingsniveau naar een lager verlichtingsniveau omgeschakeld wordt (dimmen) wanneer de situatie dit toelaat.*|
|radar detector|*Met een radardetector wordt het verkeer gedetecteerd, bijvoorbeeld voor het beïnvloeden van verkeerslichten.*|
|bolder|*Een inrichting aan de wal, waar een schip, door middel van een tros of landvast, aan vastgelegd kan worden.*|
|reclamezuil|*Vrijstaand bord/zuil waarop rondom of aan één of meer zijden affiches kunnen worden (of zijn) geplakt.*|
|betonning|*Een systeem van boeien en bakens, waarmee in open zee of in een vaarwater ondiepten of de aanwezigheid van gevaarlijke objecten worden aangegeven.*|
|meerpaal|*Paal voor een kade of in een haven waaraan een schip kan worden afgemeerd.*|


#### Kast
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Kast  |
| Onderdeel van NEN3610-objecttype |Constructie  |

ontwerpprincipe: 

**Definitie**

| Naam  | Kast  |
|---|---|
| Definitie | Object met een permanent karakter dat dient om iets in te bergen en te beschermen. |
|Herkomst definitie  | IMGeo 2.1.1    |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *Kast* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip kast |Ja |
|Geometrie|De geometrische representatie van een kast. *nader te preciseren op basis van generieke uitspraken over de vastlegging van geometrie* |Ja (punt)|
|Status   |   |Ja   |
|Type kast|aanduiding soort kast|Nee|
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

|Waarde Type hek| Beschrijving   |
|---|---|
|lage trafo|*Bouwwerk waarin transformator(en) zijn geplaatst voor elektriciteitsvoorziening.*|
|CAI-kast|*Kast ten behoeve van de regeling van radio- en televisiesignalen*|
|elektrakast|*Kast ten behoeve van het transport van elektriciteit.*|
|gaskast|*Kast ten behoeve van het transport van gas.*|
|telecom kast|*Kast ten behoeve van de regeling van telecommunicatie.*|
|rioolkast|*Kast ten behoeve van de regeling van het transport van rioolwater.*|
|openbare verlichtingkast|*Kast ten behoeve van de regeling van de openbare verlichting.*|
|verkeersregelinstallatiekast|*Kast ten behoeve van de regeling van het verkeer.*|
|telkast|*Kast ten behoeve van het meten van permanente verkeertellingen.*|
|GMS kast|*Kast ten behoeve van het meten van weers- en wegdekomstandigheden.*|
