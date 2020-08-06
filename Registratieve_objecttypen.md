## Registratieve objecttypen





### Woonplaats
| klasse  | naam  |
|---|---|
|SOR-objecttype   | woonplaats  |
| onderdeel van NEN3610-objecttype |registratief object  |

Van het objecttype woonplaats worden de volgende eigenschappen geregistreerd:
- Identificatiecode 
- verwijzing naar bijbehorende burgerlijke gemeente
- Metagegevens zoals geldigheid en status (mogelijke waarden: aangewezen en ingetrokken)
- Formele naam van de woonplaats
- Woonplaatscode
- Geometrie van de woonplaats zoals opgenomen in het besluit

ontwerpprincipe: *een woonplaats valt volledig binnen een burgerlijke gemeente*
ontwerpprincipe: *Geometrie van alle woonplaatsen in NL moet vlakdekkend zijn (op land) en mag niet overlappen*



| Naam  | Woonplaats  |
|---|---|
| Definitie | Een woonplaats is een door het bevoegde gemeentelijke orgaan als zodanig aangewezen en van een naam voorzien gedeelte van het grondgebied van de gemeente  |
|Herkomst definitie  | Artikel 1 wet Basisregistratie adressen en gebouwen    |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie zoals opgenomen in de basisregistratie adressen en gebouwen   |
|Toelichting| *volgt later*  |



|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een woonplaats, zoals opgenomen in de landelijke woonplaatsentabel  |Ja |
|Formele naam  |De benaming van een door het gemeentebestuur aangewezen woonplaats   |Ja   |
|Alternatieve naam | Een alternatieve benaming van een woonplaats zoals deze bekend staat in het Fries (bij een formele benaming in het Nederlands) of in het Nederlands (bij een formele benaming in het Fries)|
|Geometrie   |De geometrische representatie van de randen van het gebied dat als Woonplaats is benoemd   |Ja   |
|Status   |De fase van de levenscyclus waarin de betreffende Woonplaats zich bevindt    |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|ligt in   |Gerelateerde gemeente | Ja |


| Waarde  | Beschrijving Status  |
|---|---|
|Aangewezen|Woonplaats is formeel aangewezen door het bevoegd gezag |
| Ingetrokken | Woonplaats is formeel ingetrokken door het bevoegd gezag  |

### Wijk
| klasse  | naam  |
|---|---|
|SOR-objecttype   | wijk  |
| onderdeel van NEN3610-objecttype |registratief object  |

.


| Naam  | Wijk  |
|---|---|
| Definitie | Een aaneengesloten gedeelte van het grondgebied van een gemeente, waarvan de grenzen zo veel mogelijk zijn gebaseerd op sociaal-geografische kenmerken |
|Herkomst definitie  | GFO Basisgegevens   |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Wijken zijn op dit moment nog geen onderdeel van een basisregistratie. Wel hebben alle gemeenten (in overleg met het CBS) wijken vastgesteld. Deze zijn landelijk opgenomen in de WBI (wijk- en buurtindeling) die momenteel wordt beheerd door het CBS. Door de opname van wijken in de objectenregistratie ontstaat een formele vastlegging van wijken.  |
|Toelichting| Het betreft hier de in overleg met het CBS bepaalde indeling van de gemeente in wijken  |


Van het objecttype wijk worden de volgende eigenschappen geregistreerd:
- Identificatiecode 
- verwijzing naar bijbehorende woonplaats
- Metagegevens zoals geldigheid en status (mogelijke waarden: aangewezen en ingetrokken)
- Formele naam van de wijk
- Wijkcode zoals gebruikt door het CBS
- Geometrie van de wijk zoals opgenomen in het besluit

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een wijk  |Ja |
|Wijkcode   |De codering van een wijk zoals deze door het CBS wordt gebruikt   |Ja   |
|Wijknaam   |De naam die aan een wijk is toegekend in een daartoe strekkend formeel gemeentelijk besluit   |Ja   |
|Geometrie   |De geometrische representatie van de randen van het gebied dat als wijk is benoemd   |Ja   |
|Status   |De fase van de levenscyclus waarin de betreffende wijk zich bevindt    |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   |*ja*   |

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|ligt in   |Gerelateerde woonplaats | Ja |







ontwerpprincipe: *een wijk valt volledig binnen een  woonplaats*
ontwerpprincipe: *Geometrie van alle wijken in NL moet vlakdekkend zijn (op land) en mag niet overlappen*

| Waarde  | Beschrijving Status  |
|---|---|
|Aangewezen|Wijk is benoemd door het bevoegd gezag |
| Ingetrokken | Wijk is ingetrokken door het bevoegd gezag  |



### Buurt
| klasse  | naam  |
|---|---|
|SOR-objecttype   | buurt  |
| onderdeel van NEN3610-objecttype |registratief object  |

.

| Naam  | Buurt  |
|---|---|
| Definitie | Een aaneengesloten gedeelte van een wijk, waarvan de grenzen zo veel mogelijk gebaseerd zijn op topografische elementen   |
|Herkomst definitie  | GFO Basisgegevens   |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Buurten zijn op dit moment nog geen onderdeel van een basisregistratie. Wel hebben alle gemeenten (in overleg met het CBS) buurten vastgesteld. Deze zijn landelijk opgenomen in de WBI (wijk- en buurtindeling) die momenteel wordt beheerd door het CBS. Door de opname van buurten in de objectenregistratie ontstaat een formele vastlegging van buurten.   |
|Toelichting| Het betreft hier de in overleg met het CBS bepaalde indeling van de gemeente in buurten   |



Van het objecttype buurt worden de volgende eigenschappen geregistreerd:
- Identificatiecode 
- verwijzing naar bijbehorende wijk
- Metagegevens zoals geldigheid en status (mogelijke waarden: aangewezen en ingetrokken)
- Formele naam van de buurt
- Buurtcode zoals gebruikt door het CBS
- Geometrie van de buurt zoals opgenomen in het besluit


|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een buurt   |Ja |
|Buurtcode   |De codering van een buurt zoals deze door het CBS wordt gebruikt    |Ja   |
|Buurtnaam   |De naam die aan een buurt is toegekend in een daartoe strekkend formeel gemeentelijk besluit    |Ja   |
|Geometrie   |De geometrische representatie van de randen van het gebied dat als buurt is benoemd    |Ja   |
|Status   |De fase van de levenscyclus waarin de betreffende buurt zich bevindt   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   |*ja*   |

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|ligt in   |Gerelateerde wijk | Ja |


ontwerpprincipe: *buurten vallen binnen wijken*
ontwerpprincipe: *Geometrie van alle buurten in NL moet vlakdekkend zijn (op land) en mag niet overlappen*

| Waarde  | Beschrijving Status  |
|---|---|
|Aangewezen|Buurt is benoemd door het bevoegd gezag |
| Ingetrokken | Buurt is ingetrokken door het bevoegd gezag  |



### Openbare ruimte
| klasse  | naam  |
|---|---|
|SOR-objecttype   | Openbare ruimte  |
| onderdeel van NEN3610-objecttype |registratief object  |

.


| Naam  | Openbare ruimte  |
|---|---|
| Definitie | Een openbare ruimte is een door het bevoegde gemeentelijke orgaan als zodanig aangewezen en van een naam voorziene buitenruimte die binnen één woonplaats is gelegen  |
|Herkomst definitie  | Artikel 1 wet Basisregistratie adressen en gebouwen   |
|Verplicht  | Ja  |
|Gevolgen afbakening  | De populatie van openbare ruimten wijzigt als gevolg van de inperking van het aantal typen objecten waaraan een formele benaming van een openbare ruimte kan worden gekoppeld tot wegen en waterelementen |
|Toelichting| *volgt later*  |

.

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een Openbare ruimte  |Ja |
|Type   |De aard van de als zodanig benoemde openbare ruimte   |Ja   |
|Formele naam | De naam die aan een openbare ruimte is toegekend in een daartoe strekkend formeel gemeentelijk besluit | Ja|
|alternatieve naam|Een alternatieve benaming van een openbare ruimte zoals deze breed is geaccepteerd in de volksmond of zoals deze bekend staat in het Fries (bij een formele benaming in het Nederlands) of in het Nederlands (bij een formele benaming in het Fries) |Ja|
|Geometrie   |De geometrische representatie van de randen van het gebied waarin de betreffende openbare ruimte zich bevindt  |Ja   |
|Status   |De fase van de levenscyclus waarin de betreffende openbare ruimte zich bevindt    |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   |*ja*   |

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|ligt in   |Gerelateerde woonplaats | Ja |


| Waarde  | Beschrijving Status  |
|---|---|
|Aangewezen|openbare ruimte  is formeel uitgegeven door het bevoegd gezag |
| Ingetrokken | openbare ruimte  is formeel ingetrokken door het bevoegd gezag  |

| Waarde  | Beschrijving Type  |
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
|SOR-objecttype   | Nummeraanduiding  |
| onderdeel van NEN3610-objecttype |registratief object  |

.


| Naam  | Nummeraanduiding  |
|---|---|
| Definitie | Een nummeraanduiding is een door het bevoegde gemeentelijke orgaan als zodanig toegekende aanduiding van een verblijfsobject, een standplaats of een ligplaats  |
|Herkomst definitie  | Artikel 1 wet Basisregistratie adressen en gebouwen |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie zoals opgenomen in de basisregistratie adressen en gebouwen  |
|Toelichting| *volgt later* |


|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een Nummeraanduiding  |Ja |
|Huisnummer |Een door of namens het gemeentebestuur ten aanzien van een adresseerbaar object toegekende ummering
   |Ja|
|Huisletter |Een door of namens het gemeentebestuur ten aanzien van een adresseerbaar object toegekende toevoeging aan een huisnummer in de vorm van een alfanumeriek teken   |Ja|
|Huisnummer  toevoeging|Een door of namens het gemeentebestuur ten aanzien van *een adresseerbaar object* toegekende nadere toevoeging aan een huisnummer of een combinatie van huisnummer en huisletter   |Ja|
|Postcode | De door PostNL vastgestelde code behorende bij een bepaalde combinatie van een straatnaam en een huisnummer|Ja|
|Type object | De aard van het object waaraan een nummeraanduiding is toegekend| Ja|
|Status   |De fase van de levenscyclus waarin de betreffende Nummeraanduiding zich bevindt    |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   |*ja*   |

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|ligt aan| gerelateerde openbare ruimte |Ja|
|ligt in   |Gerelateerde gemeente | Ja |

.

| Waarde  | Beschrijving Status  |
|---|---|
|Aangewezen|Nummeraanduiding is formeel uitgegeven door het bevoegd gezag |
| Ingetrokken | Nummeraanduiding is formeel ingetrokken door het bevoegd gezag  |

| Waarde  | Beschrijving Type  |
|---|---|
|Verblijfsobject|Nummeraanduiding is bedoeld voor een verblijfsobject |
| Standplaats |Nummeraanduiding is bedoeld voor een standplaats |
| Ligplaats |Nummeraanduiding is bedoeld voor een ligplaats |