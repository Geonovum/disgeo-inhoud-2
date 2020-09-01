## Functionele objecttypen

In dit hoofdstuk is een eerste aanzet opgenomen tot nadere typering van de verschillende functionele objecttypen in de samenhangende objectenregistratie. Deze aanzet is primair gebaseerd op de ook nu reeds in de bestaande basisregistraties opgenomen functionele objecttypen en uitgebreid met netwerken voor wegen, water en spoorwegen. 

Vanwege een strikte scheiding tussen fysieke objecttypen en functionele objecttypen in de nu bestaande basisregistraties zijn op deze typeringen soms beperkte aanpassingen doorgevoerd. Ook zijn enkele eerste wijzigingen voorgesteld die het gevolg zijn van het in hoofdstuk 2 genoemde uitgangspunt over heldere definiëring. Tenslotte is daar waar mogelijk reeds bekeken in hoeverre aanpalende sectorale typeringen aanleiding kunnen geven tot een aangescherpte typering.

Deze typering is in deze fase van het traject vooral bedoeld om een eerste indruk te geven van de richting waarin de inhoud van de samenhangende objectenregistratie zich beweegt. Samen met experts vanuit de verschillende domeinen en gebruikers zal in het vervolg nog nader onderzoek noodzakelijk zijn om tot definitieve typeringen met bijbehorende definities te komen. Ook zal daarbij nog moeten worden bepaald in hoeverre het nu opgenomen onderscheid tussen de verplichte classificatie en de vrijwillige classificatie aanpassing behoeft. Hierbij is het uiteindelijk de bedoeling om te komen tot een “uitklapmodel” van typeringen, waarbij gedetailleerde typeringen (in de samenhangende objectenregistratie, maar bij voorkeur ook in sectorale registraties) altijd een nadere uitwerking vormen van één bepaalde hoofdtypering (in de samenhangende objectenregistratie).

De uitbreiding met objecttypen voor netwerkinformatie is gebaseerd op het Conceptueel model netwerken, juli 2020. 



### Transportvoorziening

<div class='note'>
    Transportvoorziening in de SOR moet nog verder uitgewerkt worden o.b.v. het conceptuele model netwerken.
</div>

#### Weg

| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Weg|
| Onderdeel van NEN3610-objecttype | Functioneel object |

ontwerpprincipe: 

**Definitie**

| Naam  | Weg |
|---|---|
| Definitie | Transport voorziening voor wegverkeer. |
|Herkomst definitie  | concept NEN3610 2020|
|Verplicht  | ja  |
|Gevolgen afbakening||
|Toelichting| *volgt later*  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|||
|Identificatie   |De unieke aanduiding van een weg  |Ja |
|Geometrie |De geometrische representatie van een weg  |Ja (2,5D)|
|Type weg| ||
|Naam|||
|Status   |De fase van de levenscyclus waarin het betreffende verblijfsobject zich bevindt   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |


**Domeinwaarden**

| Waarde Type weg| Beschrijving   |
|---|---|
|rijbaan autosnelweg||
|rijbaan autoweg||
|rijbaan regionale weg||
|rijbaan lokale weg||
|verbindingsweg||
|calamiteitendoorsteek||
|fietspad||
|voetpad||
|voetpad op trap||
|ruiterpad||


##### Verbinding
| Klasse  | Naam  |
|---|---|
|SOR-begrip   | Verbinding|
| Onderdeel van NEN3610-objecttype |Functioneel object  |

ontwerpprincipe: 

**Definitie**

| Naam  | Verbinding  |
|---|---|
| Definitie | De verbinding beschrijft een relatie tussen knopen, een weg van kruispunt tot kruispunt. |
|Herkomst definitie  | conceptueel model netwerken     |
|Verplicht  | Ja  |
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|||

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
| verbinding | hoort bij 2 | knopen |

**Domeinwaarden**

|Waarde Status| Beschrijving   |
|---|---|
|||


##### Knoop
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Knoop|
| Onderdeel van NEN3610-objecttype |Functioneel object  |

ontwerpprincipe: 

**Definitie**

| Naam  | Knoop  |
|---|---|
| Definitie | Een knoop is een beslispunt waarop de weggebruiker een keuze moet maken. |
| Herkomst definitie  | conceptueel model netwerken     |
| Verplicht  | Ja  |
| Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|||

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
| knoop | hoort bij 1 of meer | verbindingen |

**Domeinwaarden**

|Waarde Status| Beschrijving   |
|---|---|
|||


##### Hyperkant
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Hyperkant |
| Onderdeel van NEN3610-objecttype |Functioneel object  |

ontwerpprincipe: 

**Definitie**

| Naam  | Hyperkant  |
|---|---|
| Definitie | Een hyperkant is een relatie tussen twee objecten die een functionele samenhang hebben. |
| Herkomst definitie  | conceptueel model netwerken     |
| Verplicht  | Ja  |
| Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|||

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
| hyperkant| verbindt 2 of meer | *objecten* |

**Domeinwaarden**

|Waarde Status| Beschrijving   |
|---|---|
|||



#### Spoorweg

#### Vaarweg

<div class='note'>
    Is vaarweg wel een apart netwerk? moet varen niet idem als bij wegen als een soort modaliteit aan het waterelementen netwerk worden gekoppeld?
</div>


#### Waterelement

#### Inrit





### Functionele zonering
| Klasse  | Naam  |
|---|---|
|SOR-begrip   | Functionele zonering |
| Onderdeel van NEN3610-objecttype |Functioneel object  |


<div class='note'>
    De functionele zoneringen zijn voor het overzicht opgedeeld in rode, grijze, groene, blauwe en overige gebieden met een objecttypering. Deze indeling is functioneel ingestoken en heeft geen relatie met het fysieke voorkomen in het terrein.
</div>

 

### Functionele zonering ROOD

#### Verblijfsobject


| Klasse  | Naam  |
|---|---|
|SOR-begrip   | Verblijfsobject  |
| Onderdeel van NEN3610-objecttype |Functioneel object  |

**Definitie**

| Naam  | Verblijfsobject |
|---|---|
| Definitie | De kleinste binnen één of meer gebouwen gelegen eenheid van gebruik die ontsloten wordt via een eigen afsluitbare toegang vanaf de openbare weg, een erf of een gedeelde verkeersruimte, onderwerp kan zijn van goederenrechtelijke rechtshandelingen en in functioneel opzicht zelfstandig is|
|Herkomst definitie|Gebaseerd op definitie “verblijfsobject” in artikel 1 Wet basisregistratie adressen en gebouwen |
|Verplicht  | Ja |
|Gevolgen afbakening  | Het betreft hier in principe de bestaande populatie verblijfsobjecten zoals deze is opgenomen in de basisregistratie adressen en gebouwen |
|Toelichting| *volgt later* |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een Verblijfsobject  |Ja |
|Geometrie |De geometrische representatie van een Verblijfsobject  |Ja (2,5D)|
|Gebruiksdoel|Een categorisering van de gebruiksdoelen van het betreffende verblijfsobject zoals in de vergunning is opgenomen of bij constatering is vastgesteld|Ja|
|Feitelijk gebruik|Een categorisering van het feitelijke gebruik dat van het betreffende verblijfsobject wordt gemaakt|Ja|
|Gebruiksoppervlakte|De gebruiksoppervlakte van een verblijfsobject |
|Status   |De fase van de levenscyclus waarin het betreffende verblijfsobject zich bevindt   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|verblijfsobject|Hoort bij 1 of meer|Gebouw|
|verblijfsobject|Heeft een |Nummeraanduiding|

**Domeinwaarden**

|Waarde gebruiksdoel|	Beschrijving|
|---|---|
|woonfunctie|	Gebruiksfunctie voor het wonen|
|Bijeenkomstfunctie|	Gebruiksfunctie voor het samenkomen van personen voor kunst, cultuur, godsdienst, communicatie, kinderopvang, het verstrekken van consumpties voor het gebruik ter plaatse of het aanschouwen van sport|
|Celfunctie|	Gebruiksfunctie voor dwangverblijf van personen|
|Gezondheidszorgfunctie|	Gebruiksfunctie voor medisch onderzoek, verpleging, verzorging of behandeling|
|Industriefunctie|	Gebruiksfunctie voor het bedrijfsmatig bewerken of opslaan van materialen en goederen, of voor agrarische doeleinden|
|Kantoorfunctie|	Gebruiksfunctie voor administratie|
|Logiesfunctie|	Gebruiksfunctie voor het bieden van recreatief verblijf of tijdelijk onderdak aan personen|
|Onderwijsfunctie|	Gebruiksfunctie voor het geven van onderwijs|
|Sportfunctie|	Gebruiksfunctie voor het beoefenen van sport|
|Winkelfunctie|	Gebruiksfunctie voor het verhandelen van materialen, goederen of diensten|
|Overige gebruiksfunctie|	Andere gebruiksfunctie voor activiteiten waarbij het verblijven van personen een ondergeschikte rol speelt|

<div class='note'>
    De definitieve lijst met gebruiksfuncties zal op een later moment nog worden afgestemd op de begrippen in bijlage I van het besluit bouwwerken leefomgeving (Omgevingswet)
</div>

<div class='note'>
    De definitieve lijst voor FEITELIJK GEBRUIK zal op een later moment worden opgeleverd. Het is daarbij de bedoeling dat deze lijst aansluit op de begrippen zoals deze in het kader van de WOZ zullen worden gehanteerd. Onderstaande domeinwaarden zijn voorbeelden van typeringen zoals deze momenteel bekend zijn en uitsluitend bedoeld om een indruk te geven van het soort waarden dat hier zal worden opgenomen. Ook wordt deze lijst nog afgestemd met begrippen in de BRT.
</div>

| Waarde Feitelijk Gebruik| Beschrijving   |
|---|---|
| vrijstaande woning ||
| 2-onder-1-kapwoning ||
| geschakelde 2-onder-1-kapwoning ||
| geschakelde woning ||
| halfvrijstaande woning ||
| tussenwoning ||
| hoekwoning ||
| eindwoning ||
| galerijflat ||
| portiekflat ||
| corridorflat ||
| maisonnette ||
| benedenwoning ||
| bovenwoning ||
| portiekwoning ||
| (woonwagen/stacaravan) ||
| (woonwagenstandplaats/ stacaravanstandplaats) ||
| (woonboot) ||
| (ligplaats) ||
| waterwoning ||
| tijdelijke woning ||
| woon-/winkelpand ||
| (bouwkavel) ||
| garage ||
| (parkeerplaats) ||
| berging ||
| bijzonder woongebouw ||
| detailhandel ||
| horeca ||
| kantoor ||
| bedrijfsruimte ||
| industrie ||
| agrarisch ||
| laboratorium ||
| onderwijs ||
| cultuur ||
| medisch ||
| overheidsfunctie ||
| nutsvoorzieningen (energie/water) ||
| transport  ||
| sport en recreatie ||
| eredienst ||

.

|Waarde status	|Beschrijving|
|---|---|
|Gepland|	Een verblijfsobject dat zich in de ontwerpfase bevindt en waarvoor nog geen vergunning tot bouw is verleend|
|Gevormd|	Een verblijfsobject dat deel gaat uitmaken van een nog niet gerealiseerd gebouw waarvoor een vergunning tot bouw is verleend of dat wordt gerealiseerd in een reeds bestaand gebouw|
|In gebruik|	Een verblijfsobject dat in gebruik is genomen of als gebruiksgereed kan worden beschouwd |
|Buiten gebruik	|Een verblijfsobject dat onderdeel uitmaakt van een gebouw dat in dusdanige bouwkundige staat is dat niet te verwachten is dat het gebouw zal worden hersteld en weer in gebruik zal worden genomen|
|Beëindigd|	Een verblijfsobject dat als zodanig opgehouden heeft te bestaan|
|Niet gerealiseerd|	Een gepland verblijfsobject dat niet als zodanig is gerealiseerd|
|Ten onrechte|	Verblijfsobject is ten onrechte opgevoerd in de registratie|



#### Gebouwzone

| Klasse  | Naam  |
|---|---|
|SOR-begrip   | Gebouwzone  |
| Onderdeel van NEN3610-objecttype |Functioneel object  |

**Definitie**

| Naam  | Gebouwzone |
|---|---|
| Definitie | Het grootst mogelijke gedeelte van een gebouw dat in zijn geheel is gelegen op een bouwlaag en binnen de afbakening van een gebouw en een verblijfsobject, waaraan eenduidig een bouwjaar kan worden toegekend, en dat qua constructie en gebruiksmogelijkheden voldoende uniform is|
|Herkomst definitie|Begrip gebaseerd op de functionele deelobjecten uit de WOZ en aansluitend bij het begrip Zonering (IfcZone) uit de concepten rondom Bouwwerkinformatiemodellen (BIM), waarbij Ruimten worden gezoneerd tot bijvoorbeeld verblijfsobject of gebouwzone |
|Verplicht  | Ja |
|Gevolgen afbakening  | Het betreft hier ten opzichte van de bestaande basisregistraties grotendeels een nieuw objecttype |
|Toelichting| *volgt later* |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een Gebouwzone  |Ja |
|Geometrie |De geometrische representatie van een Gebouwzone   |Ja (2,5D)|
|Geometrie oppervlakte| De geometrische representatie van de oppervlakte van een gebouwzone die betrokken wordt in de berekening van de gebruiksoppervlakte|Nee (2D)|
|Bouwlaag|De bouwlaag waarop de gebouwzone is gelegen|Ja|
|Bouwjaar|Het bouwjaar waarin een gebouwzone is ontstaan|Ja|
|Type|Een categorisering van het feitelijke gebruik dat van de betreffende gebouwzone wordt gemaakt|Ja|
|Aard|Een aanduiding van de fysieke constructie waarin de gebouwzone zich bevindt|Ja|
|Gebruiksopppervlakte|De gebruiksoppervlakte van een gebouwzone|Ja|
|Kwaliteitsindicatie|Een aanduiding van de kwalitatieve staat waarin de gebouwzone zich bevindt|NTB|
|Status   |De fase van de levenscyclus waarin de betreffende Gebouwzone zich bevindt   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|gebouwzone|Hoort bij |Verblijfsobject|
|gebouwzone|Ligt op |Bouwlaag|

**Domeinwaarden**

<div class='note'>
    De definitieve lijst voor TYPE zal op een later moment worden opgeleverd. Het is daarbij de bedoeling dat deze lijst aansluit op de begrippen zoals deze in het kader van de WOZ zullen worden gehanteerd. Onderstaande domeinwaarden zijn voorbeelden van typeringen zoals deze momenteel bekend zijn en uitsluitend bedoeld om een indruk te geven van het soort waarden dat hier zal worden opgenomen.
</div>


| Waarde Type| Beschrijving   |
|---|---|
|woonruimte  | | 
|garage | | 
|bergruimte | | 
|kantoorruimte | | 
|winkelruimte | | 
|opslagruimte | | 
|praktijkruimte | | 
|ruimte medische zorg | | 
|productieruimte | | 
|bijeenkomstruimte | | 
|verkeersruimte | | 
|technische ruimte | | 

<div class='note'>
    In het kader van de review wordt u gevraagd om aan te geven of er naar uw mening meerdere type gebouwonderdelen relevant zijn om als AARD gebouwzone te onderscheiden
</div>

| Waarde Aard| Beschrijving   |
|---|---|
|basisconstructie |Een gebouwzone maakt onderdeel uit van de oorspronkelijke constructie van het gebouw waarin de gebouwzone is gelegen|
|aanbouw/opbouw |Een gebouwzone betreft een later aanbouw (niet zijnde een serre) of opbouw ten opzichte van de oorspronkelijke constructie van het gebouw waarin de gebouwzone is gelegen|
|serre |Een gebouwzone betreft een serre die al dan geen onderdeel uitmaakt van de oorspronkelijke constructie van het gebouw waarin de gebouwzone is gelegen|

<div class='note'>
    De definitieve lijst voor KWALITEITSINDICATIE zal op een later moment worden opgeleverd. Het is daarbij de bedoeling dat deze lijst aansluit op de begrippen zoals deze in het kader van de WOZ zullen worden gehanteerd. Onderstaande domeinwaarden zijn voorbeelden van typeringen zoals deze momenteel bekend zijn en uitsluitend bedoeld om een indruk te geven van het soort waarden dat hier zal worden opgenomen.
</div>

| Waarde Kwaliteitsindicatie| Beschrijving   |
|---|---|
|  | |

.

|Waarde status	|Beschrijving|
|---|---|
|Gepland|	Een gebouwzone dat zich in de ontwerpfase bevindt en waarvoor nog geen vergunning tot bouw is verleend|
|Gevormd|	Een gebouwzone dat deel gaat uitmaken van een nog niet gerealiseerd gebouw waarvoor een vergunning tot bouw is verleend of dat wordt gerealiseerd in een reeds bestaand gebouw|
|In gebruik|	Een gebouwzone die in gebruik is genomen of als gebruiksgereed kan worden beschouwd |
|Buiten gebruik|	Een gebouwzone dat onderdeel uitmaakt van een gebouw dat in dusdanige bouwkundige staat is dat niet te verwachten is dat het gebouw zal worden hersteld en weer in gebruik zal worden genomen|
|Beëindigd|	Een gebouwzone dat als zodanig opgehouden heeft te bestaan|
|Niet gerealiseerd|	Een geplande gebouwzone dat niet als zodanig is gerealiseerd|
|Ten onrechte|	Gebouwzone is ten onrechte opgevoerd in de registratie|



### Functionele zonering GRIJS

#### Verkeerseiland
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Verkeerseiland |
| Onderdeel van NEN3610-objecttype |Functioneel object  |

**Definitie**

| Naam  | Verkeerseiland  |
|---|---|
| Definitie | Weggedeelte van beperkte omvang, uitgevoerd als een verhoging of wegmarkering, dat wordt omsloten door rijbanen of rijstroken en als doel heeft verkeersstromen te scheiden.  |
|Herkomst definitie  | IMBOR2020-1 |
|Verplicht  | Ja  |
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een verkeerseiland  |Ja |
|Geometrie |De geometrische representatie van een verkeerseiland  |Ja |
|Status   |De fase van de levenscyclus waarin het betreffende verkeerseiland zich bevindt   |Ja   |
|Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|

**Domeinwaarden**

|Waarde status	|Beschrijving|
|---|---|
|Gepland|	Een verkeerseiland dat zich in de ontwerpfase bevindt |
|Gevormd|	Een verkeerseiland dat is gerealiseerd|
|Beëindigd|	Een verkeerseiland dat als zodanig opgehouden heeft te bestaan|
|Niet gerealiseerd|	Een gepland verkeerseiland dat niet als zodanig is gerealiseerd|
|Ten onrechte|	Verkeerseiland is ten onrechte opgevoerd in de registratie|


#### Berm
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Berm |
| Onderdeel van NEN3610-objecttype | Functioneel object  |

<div class='note'>
    definitie afstemmen tussen werkgroep GRIJS en GROEN
</div>


**Definitie**

| Naam  | Berm |
|---|---|
| Definitie | Een strook grond langs een weg of spoorweg. |
|Herkomst definitie  | BGT 1.1.1. |
|Verplicht  | Ja  |
|Toelichting|  |


**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een berm  |Ja |
|Geometrie |De geometrische representatie van een berm  |Ja |
|Status   |De fase van de levenscyclus waarin het betreffende berm zich bevindt   |Ja   |
|Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|

**Domeinwaarden**

|Waarde status	|Beschrijving|
|---|---|
|Gepland|	Een berm dat zich in de ontwerpfase bevindt |
|Gevormd|	Een berm dat is gerealiseerd|
|Beëindigd|	Een berm dat als zodanig opgehouden heeft te bestaan|
|Niet gerealiseerd|	Een gepland berm dat niet als zodanig is gerealiseerd|
|Ten onrechte|	Berm is ten onrechte opgevoerd in de registratie|



#### Voetgangersgebied
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Voetgangersgebied |
| Onderdeel van NEN3610-objecttype | Functioneel object  |

**Definitie**

| Naam  | Voetgangersgebied |
|---|---|
| Definitie | Wegdeel alleen voor het gebruik door voetgangers, waarbij het door voetgangers te gebruiken gebied de volle breedte van de weg beslaat en het gebied een nadrukkelijk openbaar karakter heeft. |
|Herkomst definitie  | BGT 1.1.1. |
|Verplicht  | Ja  |
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een voetgangersgebied  |Ja |
|Geometrie |De geometrische representatie van een voetgangersgebied  |Ja |
|Status   |De fase van de levenscyclus waarin het betreffende voetgangersgebied zich bevindt   |Ja   |
|Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|

**Domeinwaarden**

|Waarde status	|Beschrijving|
|---|---|
|Gepland|	Een voetgangersgebied dat zich in de ontwerpfase bevindt |
|Gevormd|	Een voetgangersgebied dat is gerealiseerd|
|Beëindigd|	Een voetgangersgebied dat als zodanig opgehouden heeft te bestaan|
|Niet gerealiseerd|	Een gepland voetgangersgebied dat niet als zodanig is gerealiseerd|
|Ten onrechte|	Voetgangersgebied is ten onrechte opgevoerd in de registratie|


#### Woonerf
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Woonerf |
| Onderdeel van NEN3610-objecttype | Functioneel object  |


**Definitie**

| Naam  | Woonerf |
|---|---|
| Definitie | Wegdeel waar de verblijfsfunctie (lopen, spelen, ontmoeten enzovoorts) prioriteit heeft boven de verkeersfunctie. |
|Herkomst definitie  | BGT 1.1.1. |
|Verplicht  | Ja  |
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een woonerf  |Ja |
|Geometrie |De geometrische representatie van een woonerf  |Ja |
|Status   |De fase van de levenscyclus waarin het betreffende woonerf zich bevindt   |Ja   |
|Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|

**Domeinwaarden**

|Waarde status	|Beschrijving|
|---|---|
|Gepland|	Een woonerf dat zich in de ontwerpfase bevindt |
|Gevormd|	Een woonerf dat is gerealiseerd|
|Beëindigd|	Een woonerf dat als zodanig opgehouden heeft te bestaan|
|Niet gerealiseerd|	Een gepland woonerf dat niet als zodanig is gerealiseerd|
|Ten onrechte|	Woonerf is ten onrechte opgevoerd in de registratie|



#### Parkeervlak
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Parkeervlak |
| Onderdeel van NEN3610-objecttype | Functioneel object  |


**Definitie**

| Naam  | Parkeervlak |
|---|---|
| Definitie | Wegdeel bestemd voor het parkeren van motorvoertuigen |
|Herkomst definitie  |  |
|Verplicht  | Ja  |
|Toelichting|  |


**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een parkeervlak  |Ja |
|Geometrie |De geometrische representatie van een parkeervlak  |Ja |
|Status   |De fase van de levenscyclus waarin het betreffende parkeervlak zich bevindt   |Ja   |
|Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|

**Domeinwaarden**

|Waarde status	|Beschrijving|
|---|---|
|Gepland|	Een parkeervlak dat zich in de ontwerpfase bevindt |
|Gevormd|	Een parkeervlak dat is gerealiseerd|
|Beëindigd|	Een parkeervlak dat als zodanig opgehouden heeft te bestaan|
|Niet gerealiseerd|	Een gepland parkeervlak dat niet als zodanig is gerealiseerd|
|Ten onrechte|	Parkeervlak is ten onrechte opgevoerd in de registratie|


#### Carpoolplaats
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Carpoolplaats |
| Onderdeel van NEN3610-objecttype | Functioneel object  |

<div class='note'>
    alleen opnemen als dit door BRT.next wordt aangegeven
</div>

**Definitie**

| Naam  | Carpoolplaats |
|---|---|
| Definitie | Parkeerplaats die qua ligging en ontsluiting geschikt is voor carpooling. |
|Herkomst definitie  | |
|Verplicht  | Ja  |
|Toelichting|  |


**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een carpoolplaats  |Ja |
|Geometrie |De geometrische representatie van een carpoolplaats  |Ja |
|Status   |De fase van de levenscyclus waarin het betreffende carpoolplaats zich bevindt   |Ja   |
|Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|

**Domeinwaarden**

|Waarde status	|Beschrijving|
|---|---|
|Gepland|	Een carpoolplaats dat zich in de ontwerpfase bevindt |
|Gevormd|	Een carpoolplaats dat is gerealiseerd|
|Beëindigd|	Een carpoolplaats dat als zodanig opgehouden heeft te bestaan|
|Niet gerealiseerd|	Een gepland carpoolplaats dat niet als zodanig is gerealiseerd|
|Ten onrechte|	Carpoolplaats is ten onrechte opgevoerd in de registratie|


#### laadplein
| Laadplein | Een laadplein bestaat uit meer dan twee laadpunten voor elektrische voertuigen die niet afzonderlijk op het net zijn aangesloten en samen één aansluiting hebben.|

#### Transferium
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Transferium |
| Onderdeel van NEN3610-objecttype | Functioneel object  |

<div class='note'>
    alleen opnemen als dit door BRT.next wordt aangegeven
</div>

**Definitie**

| Naam  | Transferium |
|---|---|
| Definitie | Voorziening voor het overstappen tussen vervoersmodaliteiten, die zodanig is gesitueerd en ingericht dat een verplaatsing met meerdere vervoersmodaliteiten aantrekkelijker is dan dezelfde verplaatsing met de auto. |
|Herkomst definitie  | |
|Verplicht  | Ja  |
|Toelichting|  |


**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een transferium  |Ja |
|Geometrie |De geometrische representatie van een transferium  |Ja |
|Status   |De fase van de levenscyclus waarin het betreffende transferium zich bevindt   |Ja   |
|Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|

**Domeinwaarden**

|Waarde status	|Beschrijving|
|---|---|
|Gepland|	Een transferium dat zich in de ontwerpfase bevindt |
|Gevormd|	Een transferium dat is gerealiseerd|
|Beëindigd|	Een transferium dat als zodanig opgehouden heeft te bestaan|
|Niet gerealiseerd|	Een gepland transferium dat niet als zodanig is gerealiseerd|
|Ten onrechte|	Transferium is ten onrechte opgevoerd in de registratie|



#### Verzorgingsplaats
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Verzorgingsplaats |
| Onderdeel van NEN3610-objecttype | Functioneel object  |

<div class='note'>
    alleen opnemen als dit door BRT.next wordt aangegeven
</div>

**Definitie**

| Naam  | Verzorgingsplaats |
|---|---|
| Definitie |  Langs de weg gelegen parkeergelegenheid, met inbegrip van de daarbij behorende verharde en onverharde banen en een of meer voorzieningen ten behoeve van reizigers en/of voertuigen. |
|Herkomst definitie  | |
|Verplicht  | Ja  |
|Toelichting|  |


**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een verzorgingsplaats  |Ja |
|Geometrie |De geometrische representatie van een verzorgingsplaats  |Ja |
|Status   |De fase van de levenscyclus waarin het betreffende verzorgingsplaats zich bevindt   |Ja   |
|Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|

**Domeinwaarden**

|Waarde status	|Beschrijving|
|---|---|
|Gepland|	Een verzorgingsplaats dat zich in de ontwerpfase bevindt |
|Gevormd|	Een verzorgingsplaats dat is gerealiseerd|
|Beëindigd|	Een verzorgingsplaats dat als zodanig opgehouden heeft te bestaan|
|Niet gerealiseerd|	Een gepland verzorgingsplaats dat niet als zodanig is gerealiseerd|
|Ten onrechte|	Verzorgingsplaats is ten onrechte opgevoerd in de registratie|


#### Perron
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Perron |
| Onderdeel van NEN3610-objecttype | Functioneel object  |

**Definitie**

| Naam  | Perron |
|---|---|
| Definitie |  Verhoogde constructie langs een spoorrail of tramrail voor het in- en uitstappen van passagiers of voor het laden en lossen van goederen. |
|Herkomst definitie  | |
|Verplicht  | Ja  |
|Toelichting|  |


**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een perron  |Ja |
|Geometrie |De geometrische representatie van een perron  |Ja |
|Status   |De fase van de levenscyclus waarin het betreffende perron zich bevindt   |Ja   |
|Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|

**Domeinwaarden**

|Waarde status	|Beschrijving|
|---|---|
|Gepland|	Een perron dat zich in de ontwerpfase bevindt |
|Gevormd|	Een perron dat is gerealiseerd|
|Beëindigd|	Een perron dat als zodanig opgehouden heeft te bestaan|
|Niet gerealiseerd|	Een gepland perron dat niet als zodanig is gerealiseerd|
|Ten onrechte|	Perron is ten onrechte opgevoerd in de registratie|


#### Baan voor vliegverkeer
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Baan voor vliegverkeer |
| Onderdeel van NEN3610-objecttype | Functioneel object  |

**Definitie**

| Naam  | Baan voor vliegverkeer |
|---|---|
| Definitie | Wegdeel uitsluitend bedoeld voor vliegverkeer.  |
|Herkomst definitie  | |
|Verplicht  | Ja  |
|Toelichting|  |


**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een baan voor vliegverkeer  |Ja |
|Geometrie |De geometrische representatie van een baan voor vliegverkeer  |Ja |
|Status   |De fase van de levenscyclus waarin het betreffende baan voor vliegverkeer zich bevindt   |Ja   |
|Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|

**Domeinwaarden**

|Waarde status	|Beschrijving|
|---|---|
|Gepland|	Een baan voor vliegverkeer dat zich in de ontwerpfase bevindt |
|Gevormd|	Een baan voor vliegverkeer dat is gerealiseerd|
|Beëindigd|	Een baan voor vliegverkeer dat als zodanig opgehouden heeft te bestaan|
|Niet gerealiseerd|	Een gepland baan voor vliegverkeer dat niet als zodanig is gerealiseerd|
|Ten onrechte|	Baan voor vliegverkeer is ten onrechte opgevoerd in de registratie|


#### Luchthaven
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Luchthaven |
| Onderdeel van NEN3610-objecttype | Functioneel object  |

<div class='note'>
    alleen opnemen als dit door BRT.next wordt aangegeven
</div>

**Definitie**

| Naam  | Luchthaven |
|---|---|
| Definitie | Vliegveld voor verkeersvliegtuigen met groot, effen terrein met al dan niet verharde banen, waar vliegtuigen kunnen opstijgen en landen, eventueel met accomodatie voor ontvangst en vertrek van passagiers en verzending van goederen.  |
|Herkomst definitie  | |
|Verplicht  | Ja  |
|Toelichting|  |


**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een luchthaven  |Ja |
|Geometrie |De geometrische representatie van een luchthaven  |Ja |
|Status   |De fase van de levenscyclus waarin het betreffende luchthaven zich bevindt   |Ja   |
|Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|

**Domeinwaarden**

|Waarde status	|Beschrijving|
|---|---|
|Gepland|	Een luchthaven dat zich in de ontwerpfase bevindt |
|Gevormd|	Een luchthaven dat is gerealiseerd|
|Beëindigd|	Een luchthaven dat als zodanig opgehouden heeft te bestaan|
|Niet gerealiseerd|	Een gepland luchthaven dat niet als zodanig is gerealiseerd|
|Ten onrechte|	Luchthaven is ten onrechte opgevoerd in de registratie|


#### overweg
| overweg | Een gelijkvloerse kruising van een wegdeel en een wegdeel type ov-baan met spoor type trein of sneltram. |verplicht|

#### spoorbaan
| spoorbaan | Gebaand gedeelte voor het verkeer over rails. |verplicht|

#### emplacement
| emplacement	 | Het totaal aan sporen op een terrein ten behoeve van het rangeren en stallen van treinen.|verplicht|
*alleen opnemen als dit door BRT.next wordt aangegeven*
#### OV-baan
| OV-baan | Wegdeel dat uitsluitend is bestemd en gemarkeerd voor openbaar vervoer en afgescheiden is van de andere wegdelen niet 
uitsluitend door markering.|verplicht|

#### parkeerplaats
| parkeerplaats |Parkeergelegenheid voor meerdere voertuigen in de openlucht.|verplicht|
*alleen opnemen als dit door BRT.next wordt aangegeven*
#### benzinestation
| benzinestation | Geheel van installaties, verharding en opstallen waar brandstoffen ten behoeve van verbrandingsmotoren worden verkocht.
|optioneel|
#### snellaadstation
| Snellaadstation | Infrastructuurelement, doorgaans langs autosnelwegen, dat in elektrische energie voorziet om elektrische plug-invoertuigen op te laden in een relatief korte tijd.|optioneel|

#### halteplaats
| Halteplaats | Het geheel van voorzieningen bedoeld als stopplaats voor voertuigen van het openbaar vervoer.| optioneel|

#### zone
| Zone | Verkeerskundige afbakening van een gebied.|optioneel|

#### verkeersdrempel
| Verkeersdrempel | Verhoging in een regionale rijbaan, bedoeld om het gemotoriseerde verkeer met een lage snelheid te laten rijden.| verplicht|

#### molgoot
| molgoot | Smalle goot (lijngeometrie) in de lengterichting van de verharding, met veelal een cirkelsegment als dwarsprofiel. |optioneel|

#### Wildrooster
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Wildrooster |
| Onderdeel van NEN3610-objecttype |Functioneel object  |

<div class='note'>
    Wildrooster of Rooster. Rooster is algemener. Rooster kan dan ook een fysiek verhardingstype zijn.
</div>



ontwerpprincipe: 

**Definitie**

| Naam  | Wildrooster  |
|---|---|
| Definitie |   |
|Herkomst definitie  |     |
|Verplicht  | Ja  |
|Gevolgen afbakening||
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip wildrooster|Ja |
|Geometrie||nee (vlak)|
|Status   |   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|||

**Domeinwaarden**

|Waarde Status| Beschrijving   |
|---|---|
|||



### Functionele zonering GROEN

<div class='note'>
    De nu in de basisregistratie opgenomen typeringen die nog geen plaats hebben gekregen in de SOR: 
</div>


|Objecttype |classificatie (verplicht)	| Plus classificatie (vrijwillig)|
|-----------|---------------------------|--------------------------------|
|Functioneel Gebied (groen)|	Functie:	 ||
||*Niet BGT*| 	 	Landbouw|
||*Niet BGT*| 	 	recreatie: speeltuin|
||*Niet BGT*| 	 	recreatie: park|
||*Niet BGT*| 	 	recreatie: sportterrein|
||*Niet BGT*| 	 	recreatie: camping|
||*Niet BGT*| 	 	recreatie: bungalowpark|
||*Niet BGT*| 	 	recreatie: volkstuin|  

#### Strand
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Strand |
| Onderdeel van NEN3610-objecttype | Functioneel object  |

ontwerpprincipe: 

**Definitie**

| Naam  | Strand |
|---|---|
| Definitie | Onbegroeide zandige kustvlakte op de overgang van zee met land. Staat onder invloed van het zeewater en de wind. |
|Herkomst definitie  | IMGeo 2.1.1 |
|Verplicht  | Ja  |
|Toelichting|  |

#### Duin
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Duin |
| Onderdeel van NEN3610-objecttype | Functioneel object  |

ontwerpprincipe: 

**Definitie**

| Naam  | Duin |
|---|---|
| Definitie | Verhoging of heuvel van zand of fijne losse aarde en verpulverd gesteente opgeworpen door wind of door stromend water. |
|Herkomst definitie  | BGT 1.1.1 |
|Verplicht  | Ja  |
|Toelichting|  |


### Functionele zonering BLAUW

<div class='note'>
    De nu in de basisregistratie opgenomen typeringen die nog geen plaats hebben gekregen in de SOR: 
</div>
 

|Objecttype |classificatie (verplicht)	| Plus classificatie (vrijwillig)|
|-----------|---------------------------|--------------------------------|
|Functioneel Gebied (blauw)|	Functie:	 ||
||*Niet BGT*| 	 	Opstelpunt open water|
||*Niet BGT*| 	 	Zuiveringscomplex|
||*Niet BGT*| 	 	Waterwingebied|
||*Niet BGT*|	 	Waterbergingsgebied|
||*Niet BGT*|	 	Infrastructuur waterstaatswerken|  


#### Kering
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Kering|
| Onderdeel van NEN3610-objecttype | Functioneel object |

ontwerpprincipe: 

**Definitie**

| Naam  | Kering |
|---|---|
| Definitie | Voorziening met kerende functie. |
|Herkomst definitie  |nieuw|
|Verplicht  | ja  |
|Gevolgen afbakening||
|Toelichting| *volgt later*  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip kering|Ja |
|Geometrie||nee (lijn)|
|type kering|||
|Status   |   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |

**Domeinwaarden**

|Waarde Status| Beschrijving   |
|---|---|
|||

.

|Waarde type kering| Beschrijving   |Herkomst|
|---|---|---|
|grond	|voorziening bedoeld om grond te keren|	nieuw|
|water	|voorziening bedoeld om water te keren|	nieuw|


#### Oever,slootkant
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Oever,slootkant |
| Onderdeel van NEN3610-objecttype |Functioneel object  |

ontwerpprincipe: 

**Definitie**

| Naam  | Oever,slootkant  |
|---|---|
| Definitie | *De strook land die in direct contact staat met water, inclusief het gebied tussen de hoogwaterlijn en laagwaterlijn. (bron: Inspire)*  |
|Herkomst definitie  | BGT 1.1.1.     |
|Verplicht  | Ja  |
|Gevolgen afbakening||
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip oever,slootkant|Ja |
|Geometrie||nee (lijn)|
|Status   |   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|||

**Domeinwaarden**

|Waarde Status| Beschrijving   |
|---|---|
|||

#### Complex
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Complex |
| Onderdeel van NEN3610-objecttype |Functioneel object  |

ontwerpprincipe: 

**Definitie**

| Naam  | Complex  |
|---|---|
| Definitie |   |
|Herkomst definitie  |     |
|Verplicht  | Ja  |
|Gevolgen afbakening||
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip complex|Ja |
|Geometrie||nee (vlak)|
|Type complex|||
|Status   |   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|||

**Domeinwaarden**

|Waarde Status| Beschrijving   |
|---|---|
|||

. 

|Waarde Type complex| Beschrijving   |
|---|---|
|||
|havencomplex||
|gemaalcomplex||
|sluiscomplex||
|stuwcomplex||
|coupurecomplex||


#### Vuilvang
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Vuilvang |
| Onderdeel van NEN3610-objecttype |Functioneel object  |

<div class='note'>
    Is vuilvang een functie of een kunstwerk? (IMBOR zegt kunstwerk)
</div>



ontwerpprincipe: 

**Definitie**

| Naam  | Vuilvang  |
|---|---|
| Definitie |   |
|Herkomst definitie  |     |
|Verplicht  | Ja  |
|Gevolgen afbakening||
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip vuilvang|Ja |
|Geometrie||nee (vlak)|
|Status   |   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|||

**Domeinwaarden**

|Waarde Status| Beschrijving   |
|---|---|
|||




### Functionele zonering OVERIG
#### Reducering

| Klasse  | Naam  |
|---|---|
| SOR-begrip   | reducering|
| Onderdeel van NEN3610-objecttype | Functioneel object |

ontwerpprincipe: 

**Definitie**

| Naam  | Reducering |
|---|---|
| Definitie |voorziening om bepaalde effecten van omgevingsfactoren te verminderen|
|Herkomst definitie  |nieuw|
|Verplicht  | ja  |
|Gevolgen afbakening||
|Toelichting| *volgt later*  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip reducering|Ja |
|Geometrie||nee (lijn)|
|type reducering|||
|Status   |   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |

**Domeinwaarden**
|Waarde Status| Beschrijving   |
|---|---|
|||

. 

|Waarde Type reducering| Beschrijving   |Herkomst|
|---|---|---|
|geluid|	voorziening bedoeld om geluidshinder in de buitenlucht te verminderen|	nieuw|
|fijnstof|	voorziening bedoeld om verspreiding van fijnstof te verminderen	|nieuw|


#### Valbescherming
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Valbescherming|
| Onderdeel van NEN3610-objecttype | Functioneel object |

ontwerpprincipe: 

**Definitie**

| Naam  | Valbescherming |
|---|---|
| Definitie |Voorziening om vallen te voorkomen|
|Herkomst definitie  |nieuw|
|Verplicht  | nee  |
|Gevolgen afbakening||
|Toelichting| *volgt later*  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip valbescherming|Ja |
|Geometrie||nee (lijn)|
|Status   |   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|||

**Domeinwaarden**

|Waarde Status| Beschrijving   |
|---|---|
|||


#### Afscheiding 
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Afscheiding |
| Onderdeel van NEN3610-objecttype | Functioneel object |

ontwerpprincipe: 


**Definitie**

| Naam  | Afscheiding |
|---|---|
| Definitie |Voorziening om terrein af te scheiden.|
|Herkomst definitie  |nieuw|
|Verplicht  | nee  |
|Gevolgen afbakening||
|Toelichting| *volgt later*  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip afscheiding|Ja |
|Geometrie||nee (lijn)|
|Status   |   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|||

**Domeinwaarden**

|Waarde Status| Beschrijving   |
|---|---|
|||





