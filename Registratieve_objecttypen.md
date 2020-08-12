## Registratieve objecttypen


### Bestuurlijke objecttypen

#### Provincie

| klasse  | naam  |
|---|---|
|SOR-begrip   | provincie  |
| onderdeel van NEN3610-objecttype |registratief object  |

**Definitie**

**Eigenschappen**

**Relaties met andere objecttypen** 

**Domeinwaarden**



#### Waterschap

| klasse  | naam  |
|---|---|
|SOR-begrip   | waterschap |
| onderdeel van NEN3610-objecttype |registratief object  |

**Definitie**

**Eigenschappen**

**Relaties met andere objecttypen** 

**Domeinwaarden**

#### Burgerlijke gemeente

| klasse  | naam  |
|---|---|
|SOR-begrip   | burgerlijke gemeente  |
| onderdeel van NEN3610-objecttype |registratief object  |

**Definitie**

**Eigenschappen**

**Relaties met andere objecttypen** 

**Domeinwaarden**


### Woonplaats
| klasse  | naam  |
|---|---|
|SOR-begrip   | woonplaats  |
| onderdeel van NEN3610-objecttype |registratief object  |


ontwerpprincipe: *een woonplaats valt volledig binnen een burgerlijke gemeente*

ontwerpprincipe: *Geometrie van alle woonplaatsen in NL moet vlakdekkend zijn (op land) en mag niet overlappen*

**Definitie**

| Naam  | Woonplaats  |
|---|---|
| Definitie | Een woonplaats is een door het bevoegde gemeentelijke orgaan als zodanig aangewezen en van een naam voorzien gedeelte van het grondgebied van de gemeente  |
|Herkomst definitie  | Artikel 1 wet Basisregistratie adressen en gebouwen    |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie zoals opgenomen in de basisregistratie adressen en gebouwen   |
|Toelichting| *volgt later*  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een woonplaats, zoals opgenomen in de landelijke woonplaatsentabel  |Ja |
|Formele naam  |De benaming van een door het gemeentebestuur aangewezen woonplaats   |Ja   |
|Alternatieve naam | Een alternatieve benaming van een woonplaats zoals deze bekend staat in het Fries (bij een formele benaming in het Nederlands) of in het Nederlands (bij een formele benaming in het Fries)| Nee |
|Geometrie   |De geometrische representatie van de randen van het gebied dat als Woonplaats is benoemd   |Ja   |
|Status   |De fase van de levenscyclus waarin de betreffende Woonplaats zich bevindt    |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |


**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|ligt in   |Gerelateerde gemeente | Ja |


**Domeinwaarden**


|Waarde Status| Beschrijving   |
|---|---|
|Aangewezen|Woonplaats is formeel aangewezen door het bevoegd gezag |
| Ingetrokken | Woonplaats is formeel ingetrokken door het bevoegd gezag  |

### Wijk

| klasse  | naam  |
|---|---|
|SOR-begrip   | wijk  |
| onderdeel van NEN3610-objecttype |registratief object  |

**Definitie**

| Naam  | Wijk  |
|---|---|
| Definitie | Een aaneengesloten gedeelte van het grondgebied van een gemeente, waarvan de grenzen zo veel mogelijk zijn gebaseerd op sociaal-geografische kenmerken |
|Herkomst definitie  | GFO Basisgegevens   |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Wijken zijn op dit moment nog geen onderdeel van een basisregistratie. Wel hebben alle gemeenten (in overleg met het CBS) wijken vastgesteld. Deze zijn landelijk opgenomen in de WBI (wijk- en buurtindeling) die momenteel wordt beheerd door het CBS. Door de opname van wijken in de objectenregistratie ontstaat een formele vastlegging van wijken.  |
|Toelichting| Het betreft hier de in overleg met het CBS bepaalde indeling van de gemeente in wijken  |


**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een wijk  |Ja |
|Wijkcode   |De codering van een wijk zoals deze door het CBS wordt gebruikt   |Ja   |
|Wijknaam   |De naam die aan een wijk is toegekend in een daartoe strekkend formeel gemeentelijk besluit   |Ja   |
|Geometrie   |De geometrische representatie van de randen van het gebied dat als wijk is benoemd   |Ja   |
|Status   |De fase van de levenscyclus waarin de betreffende wijk zich bevindt    |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   |*ja*   |


**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|ligt in   |Gerelateerde woonplaats | Ja |

ontwerpprincipe: *een wijk valt volledig binnen een  woonplaats*

ontwerpprincipe: *Geometrie van alle wijken in NL moet vlakdekkend zijn (op land) en mag niet overlappen*


**Domeinwaarden**


| Waarde Status | Beschrijving   |
|---|---|
|Aangewezen|Wijk is benoemd door het bevoegd gezag |
| Ingetrokken | Wijk is ingetrokken door het bevoegd gezag  |



### Buurt

| klasse  | naam  |
|---|---|
|SOR-begrip   | buurt  |
| onderdeel van NEN3610-objecttype |registratief object  |

**Definitie**

| Naam  | Buurt  |
|---|---|
| Definitie | Een aaneengesloten gedeelte van een wijk, waarvan de grenzen zo veel mogelijk gebaseerd zijn op topografische elementen   |
|Herkomst definitie  | GFO Basisgegevens   |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Buurten zijn op dit moment nog geen onderdeel van een basisregistratie. Wel hebben alle gemeenten (in overleg met het CBS) buurten vastgesteld. Deze zijn landelijk opgenomen in de WBI (wijk- en buurtindeling) die momenteel wordt beheerd door het CBS. Door de opname van buurten in de objectenregistratie ontstaat een formele vastlegging van buurten.   |
|Toelichting| Het betreft hier de in overleg met het CBS bepaalde indeling van de gemeente in buurten   |


**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een buurt   |Ja |
|Buurtcode   |De codering van een buurt zoals deze door het CBS wordt gebruikt    |Ja   |
|Buurtnaam   |De naam die aan een buurt is toegekend in een daartoe strekkend formeel gemeentelijk besluit    |Ja   |
|Geometrie   |De geometrische representatie van de randen van het gebied dat als buurt is benoemd    |Ja   |
|Status   |De fase van de levenscyclus waarin de betreffende buurt zich bevindt   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|ligt in   |Gerelateerde wijk | Ja |


ontwerpprincipe: *buurten vallen binnen wijken*

ontwerpprincipe: *Geometrie van alle buurten in NL moet vlakdekkend zijn (op land) en mag niet overlappen*

**Domeinwaarden**


| Waarde Status| Beschrijving   |
|---|---|
|Aangewezen|Buurt is benoemd door het bevoegd gezag |
| Ingetrokken | Buurt is ingetrokken door het bevoegd gezag  |



### Openbare ruimte

| klasse  | naam  |
|---|---|
|SOR-begrip   | Openbare ruimte  |
| onderdeel van NEN3610-objecttype |registratief object  |

**Definitie**


| Naam  | Openbare ruimte  |
|---|---|
| Definitie | Een openbare ruimte is een door het bevoegde gemeentelijke orgaan als zodanig aangewezen en van een naam voorziene buitenruimte die binnen één woonplaats is gelegen  |
|Herkomst definitie  | Artikel 1 wet Basisregistratie adressen en gebouwen   |
|Verplicht  | Ja  |
|Gevolgen afbakening  | De populatie van openbare ruimten wijzigt als gevolg van de inperking van het aantal typen objecten waaraan een formele benaming van een openbare ruimte kan worden gekoppeld tot wegen en waterelementen |
|Toelichting| *volgt later*  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een Openbare ruimte  |Ja |
|Type   |De aard van de als zodanig benoemde openbare ruimte   |Ja   |
|Formele naam | De naam die aan een openbare ruimte is toegekend in een daartoe strekkend formeel gemeentelijk besluit | Ja|
|alternatieve naam|Een alternatieve benaming van een openbare ruimte zoals deze breed is geaccepteerd in de volksmond of zoals deze bekend staat in het Fries (bij een formele benaming in het Nederlands) of iNee|
|Geometrie   |De geometrische representatie van de randen van het gebied dat als openbare ruimte is benoemd  |Ja   |
|Status   |De fase van de levenscyclus waarin de betreffende openbare ruimte zich bevindt    |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|ligt in   |Gerelateerde woonplaats | Ja |

**Domeinwaarden**


| Waarde Status | Beschrijving   |
|---|---|
|Aangewezen|openbare ruimte  is formeel uitgegeven door het bevoegd gezag |
| Ingetrokken | openbare ruimte  is formeel ingetrokken door het bevoegd gezag  |


| Waarde Type | Beschrijving   |
|---|---|
|Weg|Transportvoorzienning voor wegverkeer |
| Waterlement |Transportvoorzienning voor water|

ontwerpprincipe: *Bij het objecttype spoorweg wordt een (vrijwillige) eigenschap “Naam spoorweg” opgenomen*

ontwerpprincipe: *Bij het objecttype kunstwerk (of eventuele verfijningen daarvan) wordt een (vrijwillige) eigenschap “Naam kunstwerk” opgenomen*

ontwerpprincipe: *Bij het objecttype weg wordt een verwijzing opgenomen naar de identificatiecode van de openbare ruimte waarbinnen de weg is gelegen (als deze formeel is benoemd)*

ontwerpprincipe: *Bij het objecttype waterelement wordt een verwijzing opgenomen naar de identificatiecode van de openbare ruimte waarbinnen het waterelement is gelegen (als deze formeel is benoemd)*

ontwerpprincipe: *Bij het objecttype geografisch gebied wordt een (vrijwillige) eigenschap “Naam geografisch gebied” opgenomen*

ontwerpprincipe: *Bij het objecttype functioneel object (of eventuele verfijningen daarvan) wordt een (vrijwillige) eigenschap “Naam functioneel object” opgenomen*


### Nummeraanduiding

| klasse  | naam  |
|---|---|
|SOR-begrip   | Nummeraanduiding  |
| onderdeel van NEN3610-objecttype |registratief object  |

**Definitie**

| Naam  | Nummeraanduiding  |
|---|---|
| Definitie | Een nummeraanduiding is een door het bevoegde gemeentelijke orgaan als zodanig toegekende aanduiding van een verblijfsobject, een standplaats of een ligplaats  |
|Herkomst definitie  | Artikel 1 wet Basisregistratie adressen en gebouwen |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie zoals opgenomen in de basisregistratie adressen en gebouwen  |
|Toelichting| *volgt later* |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een Nummeraanduiding  |Ja |
|Huisnummer |Een door of namens het gemeentebestuur ten aanzien van een adresseerbaar object toegekende ummering   |Ja|
|Huisletter |Een door of namens het gemeentebestuur ten aanzien van een adresseerbaar object toegekende toevoeging aan een huisnummer in de vorm van een alfanumeriek teken   |Ja|
|Huisnummer  toevoeging|Een door of namens het gemeentebestuur ten aanzien van *een adresseerbaar object* toegekende nadere toevoeging aan een huisnummer of een combinatie van huisnummer en huisletter   |Ja|
|Postcode | De door PostNL vastgestelde code behorende bij een bepaalde combinatie van een straatnaam en een huisnummer|Ja|
|Type object | De aard van het object waaraan een nummeraanduiding is toegekend| Ja|
|Status   |De fase van de levenscyclus waarin de betreffende Nummeraanduiding zich bevindt    |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|ligt aan| gerelateerde openbare ruimte |Ja|
|ligt in   |Gerelateerde gemeente | Ja |

**Domeinwaarden**


| Waarde Status | Beschrijving   |
|---|---|
|Aangewezen|Nummeraanduiding is formeel uitgegeven door het bevoegd gezag |
| Ingetrokken | Nummeraanduiding is formeel ingetrokken door het bevoegd gezag  |


| Waarde Type | Beschrijving   |
|---|---|
|Verblijfsobject|Nummeraanduiding is bedoeld voor een verblijfsobject |
| Standplaats |Nummeraanduiding is bedoeld voor een standplaats |
| Ligplaats |Nummeraanduiding is bedoeld voor een ligplaats |


### Stand- en Ligplaats
| klasse  | naam  |
|---|---|
|SOR-begrip   | ligplaats  |
| onderdeel van NEN3610-objecttype |functioneel object  |

Definitie ligplaats (Herkomst  : Catalogus BAG 2018): 
Door het bevoegde gemeentelijke orgaan als zodanig aangewezen plaats in het water al dan niet aangevuld met een op de oever aanwezig terrein of een gedeelte daarvan, die bestemd is voor het permanent afmeren van een voor woon-, bedrijfsmatige of recreatieve doeleinden geschikt drijvend object 
https://imbag.github.io/praktijkhandleiding/objecttypen/ligplaats

| klasse  | naam  |
|---|---|
|SOR-begrip   | standplaats  |
| onderdeel van NEN3610-objecttype |functioneel object  |

Definitie standplaats (Herkomst : Catalogus BAG 2018):
Door het bevoegde gemeentelijke orgaan als zodanig aangewezen terrein of gedeelte daarvan dat bestemd is voor het permanent plaatsen van een niet direct en niet duurzaam met de aarde verbonden en voor woon-, bedrijfsmatige, of recreatieve doeleinden geschikte ruimte
https://imbag.github.io/praktijkhandleiding/objecttypen/standplaats 

Er is vrijwel geen verschil tussen een ligplaats en een standplaats; beiden beogen hetzelfde te bereiken, nl. een locatie met adres. Het enige verschil is dat er bij een ligplaats sprake is van een drijvend object en bij een standplaats sprake is van een verplaatsbaar object.

Het is van belang is om het begrip ligplaats te onderscheiden van de in de praktijk veelvuldig voorkomende aanmeerplaatsen of afmeerplaatsen. Dergelijke plaatsen zijn bedoeld voor het tijdelijk aan- en afmeren van onder meer pleziervaartuigen en beroepsvaartuigen langs kades en in havens.



ontwerpprincipe: *Gebruik van stand- en ligplaatsen vooral in het overheidsdomein (gemeenten, inschrijving, nutsvoorzieningen, vindbaarheid)*

ontwerpprincipe: *Standplaatsen en ligplaatsen vormen een geometrische weergave van een gemeentelijk besluit*
