## Functionele objecttypen

### Transportvoorziening

#### Weg

| klasse  | naam  |
|---|---|
| SOR-begrip   | Weg|
| onderdeel van NEN3610-objecttype | Functioneel object |

ontwerpprincipe: 

**Definitie**

| Naam  | Weg |
|---|---|
| Definitie | Transport voorziening voor wegverkeer. |
|Herkomst definitie  | concept NEN3610 2020|
|Verplicht  | ja  |
|Toelichting| *volgt later*  |

##### Verbinding
| klasse  | naam  |
|---|---|
|SOR-begrip   | Verbinding|
| onderdeel van NEN3610-objecttype |Functioneel object  |

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
| klasse  | naam  |
|---|---|
| SOR-begrip   | Knoop|
| onderdeel van NEN3610-objecttype |Functioneel object  |

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
| klasse  | naam  |
|---|---|
| SOR-begrip   | Hyperkant |
| onderdeel van NEN3610-objecttype |Functioneel object  |

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


**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip weg|Ja |
|Geometrie-type|lijn|Ja|
|Afbakening   |  | |
|type weg|||
|Status   |   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |

|Waarde type weg| Beschrijving   |Herkomst|
|---|---|---|



#### Spoorweg

#### Vaarweg
*is vaarweg wel een apart netwerk? moet varen niet idem als bij wegen als een soort modaliteit aan het waterelementen netwerk worden gekoppeld?*

#### Waterelement




### Infrastructuur waterstaatswerken
#### Kering
| klasse  | naam  |
|---|---|
|SOR-begrip   | Kering|
| onderdeel van NEN3610-objecttype | Functioneel object |

ontwerpprincipe: 


**Definitie**

| Naam  | Kering |
|---|---|
| Definitie | Voorziening met kerende functie. |
|Herkomst definitie  |nieuw|
|Verplicht  | ja  |
|Toelichting| *volgt later*  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip kering|Ja |
|Geometrie-type|lijn|nee|
|Afbakening   |  | |
|type kering|||
|Status   |   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |

**Domeinwaarden**

|Waarde type kering| Beschrijving   |Herkomst|
|---|---|---|
|grond	|voorziening bedoeld om grond te keren|	nieuw|
|water	|voorziening bedoeld om water te keren|	nieuw|


#### Oever,slootkant
| klasse  | naam  |
|---|---|
|SOR-begrip   | Oever,slootkant |
| onderdeel van NEN3610-objecttype |Functioneel object  |

ontwerpprincipe: 

**Definitie**

| Naam  | Oever,slootkant  |
|---|---|
| Definitie | *De strook land die in direct contact staat met water, inclusief het gebied tussen
de hoogwaterlijn en laagwaterlijn. (bron: Inspire)*  |
|Herkomst definitie  | BGT 1.1.1.     |
|Verplicht  | Ja  |
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|||

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|||

**Domeinwaarden**

|Waarde Status| Beschrijving   |
|---|---|
|||

#### Complex

### Watergebruik
#### Havencomplex


### Functionele zonering
| klasse  | naam  |
|---|---|
|SOR-begrip   | Functionele zonering |
| onderdeel van NEN3610-objecttype |Functioneel object  |



De functionele zoneringen zijn voor het overzicht opgedeeld in grijze, groene en blauwe gebieden met een objecttypering. Deze indeling is functioneel ingestoken en heeft geen relatie met het fysieke voorkomen in het terrein. Hierbij is aangesloten op de typering zoals voor BGT|IMGeo wordt gebruikt, inclusief de voorstellen voor IMGeo 2.2. Als gevolg van het uitgangspunt dat fysiek en functie worden gescheiden zijn een aantal functies verschoven van voorheen een typering bij een fysiek objecttype naar een eigenstandig functioneel objecttype.

### Functionele zonering ROOD

#### Verblijfsobject


| klasse  | naam  |
|---|---|
|SOR-begrip   | Verblijfsobject  |
| onderdeel van NEN3610-objecttype |Functioneel object  |

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
|Geometrie |De geometrische representatie van een Verblijfsobject *nader te preciseren op basis van generieke uitspraken over de vastlegging van geometrie*  |Ja|
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

| Waarde Gebruiksdoel| Beschrijving   |
|---|---|
|bijeenkomstfunctie ||
|| |
|*nader te bepalen op grond wijzigingen Omgevingswet* ||
.
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
|||
||*lijst nog afstemmen op laatste versie van WOZ*|
.
| Waarde Status | Beschrijving   |
|---|---|
|Gepland||
|Gevormd||
|Buiten gebruik||
|Beëindigd||
|Niet gerealiseerd||
|Ten onrechte||


#### Gebouwzone

| klasse  | naam  |
|---|---|
|SOR-begrip   | Gebouwzone  |
| onderdeel van NEN3610-objecttype |Functioneel object  |

**Definitie**

| Naam  | Gebouwzone |
|---|---|
| Definitie | DHet grootst mogelijke gedeelte van een gebouw dat in zijn geheel is gelegen op een bouwlaag en binnen de afbakening van een gebouw en een verblijfsobject, waaraan eenduidig een bouwjaar kan worden toegekend, en dat qua constructie en gebruiksmogelijkheden voldoende uniform is|
|Herkomst definitie|Begrip gebaseerd op de functionele deelobjecten uit de WOZ en aansluitend bij het begrip Zonering (IfcZone) uit de concepten rondom Bouwwerkinformatiemodellen (BIM), waarbij Ruimten worden gezoneerd tot bijvoorbeeld verblijfsobject of gebouwzone |
|Verplicht  | Ja |
|Gevolgen afbakening  | Het betreft hier ten opzichte van de bestaande basisregistraties grotendeels een nieuw objecttype |
|Toelichting| *volgt later* |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een Gebouwzone  |Ja |
|Geometrie |De geometrische representatie van een Gebouwzone *nader te preciseren op basis van generieke uitspraken over de vastlegging van geometrie*  |Ja|
|Geometrie oppervlakte| NTB||
|Bouwlaag|De bouwlaag waarop de gebouwzone is gelegen|Ja|
|Bouwjaar|Het bouwjaar waarin een gebouwzone is ontstaan|Ja|
|Type|Een categorisering van het feitelijke gebruik dat van de betreffende gebouwzone wordt gemaakt|Ja|
|Aard|Een aanduiding van de fysieke constructie waarin de gebouwzone zich bevindt|Ja|
|Gebruiksopppervlakte|De gebruiksoppervlakte van een gebouwzone|Ja|
|Kwaliteitsindicatie||
|Status   |De fase van de levenscyclus waarin de betreffende Gebouwzone zich bevindt   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|gebouwzone|Hoort bij |Verblijfsobject|
|gebouwzone|Ligt op |Bouwlaag|

**Domeinwaarden**

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
|||
||*lijst nog afstemmen op laatste versie van WOZ*|
.
| Waarde Aard| Beschrijving   |
|---|---|
|basisconstructie ||
|aanbouw/opbouw ||
|serre ||
|||
|*meer*||
.
| Waarde Kwaliteit| Beschrijving   |
|---|---|
|*NTB*  | |
.
| Waarde Status | Beschrijving   |
|---|---|
|Gepland||
|Gevormd||
|Buiten gebruik||
|Beëindigd||
|Niet gerealiseerd||
|Ten onrechte||


### Functionele zonering GRIJS

#### Verkeerseiland
| klasse  | naam  |
|---|---|
| SOR-begrip   | Verkeerseiland |
| onderdeel van NEN3610-objecttype |Functioneel object  |

ontwerpprincipe: 

**Definitie**

| Naam  | Verkeerseiland  |
|---|---|
| Definitie | Weggedeelte van beperkte omvang, uitgevoerd als een verhoging of wegmarkering, dat wordt omsloten door rijbanen of rijstroken en als doel heeft verkeersstromen te scheiden.  |
|Herkomst definitie  | IMBOR2020-1 |
|Verplicht  | Ja  |
|Toelichting|  |

#### Berm
| klasse  | naam  |
|---|---|
| SOR-begrip   | Berm |
| onderdeel van NEN3610-objecttype | Functioneel object  |

ontwerpprincipe: 

**Definitie**

| Naam  | Berm |
|---|---|
| Definitie | Een strook grond langs een weg of spoorweg. |
|Herkomst definitie  | BGT 1.1.1. |
|Verplicht  | Ja  |
|Toelichting|  |
*definitie afstemmen tussen werkgroep GRIJS en GROEN*

#### Voetgangersgebied
| klasse  | naam  |
|---|---|
| SOR-begrip   | Voetgangersgebied |
| onderdeel van NEN3610-objecttype | Functioneel object  |

ontwerpprincipe: 

**Definitie**

| Naam  | Voetgangersgebied |
|---|---|
| Definitie | Wegdeel alleen voor het gebruik door voetgangers, waarbij het door voetgangers te gebruiken gebied de volle breedte van de weg beslaat en het gebied een nadrukkelijk openbaar karakter heeft. |
|Herkomst definitie  | BGT 1.1.1. |
|Verplicht  | Ja  |
|Toelichting|  |

#### Woonerf
| klasse  | naam  |
|---|---|
| SOR-begrip   | Woonerf |
| onderdeel van NEN3610-objecttype | Functioneel object  |

ontwerpprincipe: 

**Definitie**

| Naam  | Woonerf |
|---|---|
| Definitie | Wegdeel waar de verblijfsfunctie (lopen, spelen, ontmoeten enzovoorts) prioriteit heeft boven de verkeersfunctie. |
|Herkomst definitie  | BGT 1.1.1. |
|Verplicht  | Ja  |
|Toelichting|  |


#### parkeervlak
| parkeervlak |Wegdeel bestemd voor het parkeren van motorvoertuigen| verplicht|

#### carpoolplaats
| carpoolplaats | Parkeerplaats die qua ligging en ontsluiting geschikt is voor carpooling.|verplicht|
*alleen opnemen als dit door BRT.next wordt aangegeven*

#### laadplein
| Laadplein | Een laadplein bestaat uit meer dan twee laadpunten voor elektrische voertuigen die niet afzonderlijk op het net zijn aangesloten en samen één aansluiting hebben.|

#### transferium
| Transferium | Voorziening voor het overstappen tussen vervoersmodaliteiten, die zodanig is gesitueerd en ingericht dat een verplaatsing met meerdere vervoersmodaliteiten aantrekkelijker is dan dezelfde verplaatsing met de auto.|verplicht|
*alleen opnemen als dit door BRT.next wordt aangegeven*
#### verzorgingsplaats
| verzorgingsplaats | Langs de weg gelegen parkeergelegenheid, met inbegrip van de daarbij behorende verharde en onverharde banen en een of meer voorzieningen ten behoeve van reizigers en/of voertuigen. |verplicht|
*alleen opnemen als dit door BRT.next wordt aangegeven*
#### perron
| perron | Verhoogde constructie langs een spoorrail of tramrail voor het in- en uitstappen van passagiers of voor het laden en lossen van goederen.|verplicht|

#### baan voor vliegverkeer
| baan voor vliegverkeer | Wegdeel uitsluitend bedoeld voor vliegverkeer. |verplicht|

#### vliegveld, luchthaven
| vliegveld, luchthaven | Vliegveld voor verkeersvliegtuigen met groot, effen terrein met al dan niet verharde banen, waar vliegtuigen kunnen opstijgen en landen, eventueel met accomodatie voor ontvangst en vertrek van passagiers en verzending van goederen.|verplicht|
*alleen opnemen als dit door BRT.next wordt aangegeven*
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


### Functionele zonering GROEN

#### GROEN bestaand

|Objecttype |classificatie (verplicht)	| Plus classificatie (vrijwillig)|
|-----------|---------------------------|--------------------------------|
|Functioneel Gebied (groen)|	Functie:	 ||
||	oever/slootkant	 ||
||*Niet BGT*| 	 	Landbouw|
||*Niet BGT*| 	 	recreatie: speeltuin|
||*Niet BGT*| 	 	recreatie: park|
||*Niet BGT*| 	 	recreatie: sportterrein|
||*Niet BGT*| 	 	recreatie: camping|
||*Niet BGT*| 	 	recreatie: bungalowpark|
||*Niet BGT*| 	 	recreatie: volkstuin|  

#### Strand
| klasse  | naam  |
|---|---|
| SOR-begrip   | Strand |
| onderdeel van NEN3610-objecttype | Functioneel object  |

ontwerpprincipe: 

**Definitie**

| Naam  | Strand |
|---|---|
| Definitie | Onbegroeide zandige kustvlakte op de overgang van zee met land. Staat onder invloed van het zeewater en de wind. |
|Herkomst definitie  | IMGeo 2.1.1 |
|Verplicht  | Ja  |
|Toelichting|  |

#### Duin
| klasse  | naam  |
|---|---|
| SOR-begrip   | Duin |
| onderdeel van NEN3610-objecttype | Functioneel object  |

ontwerpprincipe: 

**Definitie**

| Naam  | Duin |
|---|---|
| Definitie | Verhoging of heuvel van zand of fijne losse aarde en verpulverd gesteente opgeworpen door wind of door stromend water. |
|Herkomst definitie  | BGT 1.1.1 |
|Verplicht  | Ja  |
|Toelichting|  |


### Functionele zonering BLAUW

#### BLAUW bestaand  

|Objecttype |classificatie (verplicht)	| Plus classificatie (vrijwillig)|
|-----------|---------------------------|--------------------------------|
|Functioneel Gebied (blauw)|	Functie:	 ||
||kering	 ||
|| 	haven	 ||
||*Niet BGT*| 	 	opstelpunt open water|
||*Niet BGT*| 	 	Sluiscomplex|
||*Niet BGT*| 	 	Zuiveringscomplex|
||*Niet BGT*| 	 	Waterwingebied|
||*Niet BGT*|	 	    waterbergingsgebied|
||*Niet BGT*|	 	    infrastructuur waterstaatswerken|  





### Functionele zonering OVERIG
#### reducering

| klasse  | naam  |
|---|---|
|SOR-begrip   | reducering|
| onderdeel van NEN3610-objecttype | **functioneel object** |

ontwerpprincipe: 


**Definitie**

| Naam  | reducering |
|---|---|
| Definitie |voorziening om bepaalde effecten van omgevingsfactoren te verminderen|
|Herkomst definitie  |nieuw|
|Verplicht  | ja  |
|Toelichting| *volgt later*  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip reducering|Ja |
|Geometrie-type|lijn|nee|
|Afbakening   |  | |
|type reducering|||
|Status   |   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |

**Domeinwaarden**

|Waarde type reducering| Beschrijving   |Herkomst|
|---|---|---|
|geluid|	voorziening bedoeld om geluidshinder in de buitenlucht te verminderen|	nieuw|
|fijnstof|	voorziening bedoeld om verspreiding van fijnstof te verminderen	|nieuw|


#### valbescherming
| klasse  | naam  |
|---|---|
|SOR-begrip   | valbescherming|
| onderdeel van NEN3610-objecttype | **functioneel object** |

ontwerpprincipe: 


**Definitie**

| Naam  | valbescherming |
|---|---|
| Definitie |voorziening om vallen te voorkomen|
|Herkomst definitie  |nieuw|
|Verplicht  | nee  |
|Toelichting| *volgt later*  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip valbescherming|Ja |
|Geometrie-type|lijn|nee|
|Afbakening   |  | |
|Status   |   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |


#### afscheiding 
| klasse  | naam  |
|---|---|
|SOR-begrip   | afscheiding |
| onderdeel van NEN3610-objecttype | **functioneel object** |

ontwerpprincipe: 


**Definitie**

| Naam  | afscheiding |
|---|---|
| Definitie |Voorziening om terrein af te scheiden.|
|Herkomst definitie  |nieuw|
|Verplicht  | nee  |
|Toelichting| *volgt later*  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip afscheiding|Ja |
|Geometrie-type|lijn|nee|
|Afbakening   |  | |
|Status   |   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |












### Functionele zonering *nog toedelen*

##### jachthaven
##### vaarweg beroeps
##### vaarweg recreatief
##### infiltratiegebied
##### waterwingebied
##### zuiveringsinstallatie
##### zuiveringscomplex
##### zwemwaterlokatie
##### recreatie: water, lucht, land
##### opstelpunt open water
##### waterbeheergebied kwantiteit
##### waterbeheergebied kwaliteit
##### waterbeheergebied beheer waterstaatwerken
##### waterbeschermingsgebied (geen wateronttrekking, geen gebouwen, niet spuiten etc)
##### visserijgebied beroeps en recreatief?
##### waterkering
##### waterbergingsgebied
##### havencomplex
##### gemaalcomplex
##### sluiscomplex
##### stuwcomplex
##### coupurecomplex
##### scheepvaartbord 
##### pomp 
##### dijkpaal 
##### debietmeter 
##### weerstation 
##### waterstandmeter 
##### bolder 
##### remmingswerk 
##### betonning 
##### geleidewerk 
##### vuilvang 
##### meerpaal 
##### hoogtemerk 




#### OVERIG

|Objecttype |classificatie (verplicht)	| Plus classificatie (vrijwillig)|
|-----------|---------------------------|--------------------------------|
|Functioneel Gebied |	Type:	 ||	 
|| 	*Niet BGT*	|Stiltegebied|
|| 	*Niet BGT*	|Zonnepanelenveld|
|| 	*Niet BGT*	|Bedrijvigheid|
||	*Niet BGT*	|natuur en landschap|
|| 	*Niet BGT*	|Bewoning|
|| 	*Niet BGT*	|maatschappelijke en/of publieksvoorziening|
|| 	*Niet BGT*	|Recreatie|
|| 	*Niet BGT*	|Begraafplaats|
|| 	*Niet BGT*	|functioneel beheer|
|| 	*Niet BGT*	|functioneel beheer: hondenuitlaatplaats|  
  
  


### Functionele objecttypen uit BRT

De typering behorende bij de aan gebouwen gerelateerde functionele objecttypen zal in het vervolgtraject nader worden onderzocht.




