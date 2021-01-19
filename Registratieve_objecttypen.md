## Registratieve objecttypen




### Bestuurlijke gebieden



#### Rijk

| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Rijk |
| Onderdeel van NEN3610-objecttype |Registratieve ruimte |

 

**Definitie**

| Naam  | Rijk |
|---|---|
| Definitie | Het grondgebied van het Koninkrijk der Nederlanden*|
|Herkomst definitie  | BRK  |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de rijksgrenzen zoals opgenomen in de basisregistratie kadaster.  |
|Toelichting| |

. 

*Dit betreft in eerste instantie het Europese deel. Over het niet-Europese deel zal nog nadere besluitvorming plaatsvinden.

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het Rijk |Ja |
|Geometrie| De geometrische representatie van de randen van het gebied dat als Rijk is benoemd. |Ja (vlak)|
|Status   | De fase van de levenscyclus waarin het Rijk zich bevindt.  |Ja   |
| Landcode |	De codering van het land zoals deze door de RVIG wordt gebruikt.|Ja|



**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Aangewezen	|Het Rijk is formeel aangewezen door het bevoegd gezag|
|Ingetrokken	|Het Rijk is formeel ingetrokken door het bevoegd gezag|
|Ten onrechte opgevoerd	|Het Rijk is ten onrechte opgevoerd in de registratie|





#### Provincie
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Provincie |
| Onderdeel van NEN3610-objecttype |Registratieve ruimte  |

 

**Definitie**

| Naam  | Provincie |
|---|---|
| Definitie | Een provincie is een afgebakend gedeelte van het grondgebied van Nederland, onder zeggenschap van een openbaar lichaam met diverse bestuurlijke taken, ingesteld op basis van artikel 123 van de Grondwet en de provinciewet.|
|Herkomst definitie  | Grondwet en Provinciewet  |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de provinciegrenzen zoals opgenomen in de basisregistratie kadaster.  |
|Toelichting| |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van de Provincie |Ja |
|Provinciecode|	De codering van een provincie zoals deze door het CBS wordt gebruikt.|Ja   |
|Provincienaam|	De naam van een provincie zoals formeel benoemd door het bevoegd gezag.|Ja   |
|Geometrie| De geometrische representatie van de randen van het gebied dat als Provincie is benoemd. |Ja (vlak)|
|Status   | De fase van de levenscyclus waarin de Provincie zich bevindt.  |Ja   |




**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Aangewezen	|De Provincie is formeel aangewezen door het bevoegd gezag|
|Ingetrokken	|De Provincie is formeel ingetrokken door het bevoegd gezag|
|Ten onrechte opgevoerd	|De Provincie is ten onrechte opgevoerd in de registratie|






#### Waterschap
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Waterschap |
| Onderdeel van NEN3610-objecttype |Registratieve ruimte |

 

**Definitie**

| Naam  | Waterschap |
|---|---|
| Definitie | Een waterschap is een afgebakend gedeelte van het grondgebied van Nederland, onder zeggenschap van een openbaar lichaam welke de waterstaatskundige verzorging van dat gebied ten doel heeft, ingesteld op basis van artikel 133 van de Grondwet en de Waterschapswet.|
|Herkomst definitie  | Grondwet en Waterschapswet.  |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Waterschappen waren tot nu toe nog geen verplicht onderdeel van een basisregistratie. Wel bood BGT IMGeo de mogelijkheid tot vrijwillige vastlegging. Door de opname van waterschappen in de objectenregistratie ontstaat een formele vastlegging van waterschappen.  |
|Toelichting|In een latere fase moet nog worden bepaald welke gebiedsbegrenzing wordt vastgelegd (de administratieve gebiedsbegrenzing of het reglementsgebied). |





**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het waterschap |Ja |
|Waterschapscode|	De codering van een waterschap zoals deze door het CBS wordt gebruikt.|Ja   |
|Waterschapsnaam|	De naam van een waterschap zoals formeel benoemd door het bevoegd gezag.|Ja   |
|Geometrie| De geometrische representatie van de randen van het gebied dat als waterschap is benoemd. |Ja (vlak)|
|Status   | De fase van de levenscyclus waarin het waterschap zich bevindt.  |Ja   |




**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Aangewezen	|Het waterschap is formeel aangewezen door het bevoegd gezag|
|Ingetrokken	|Het waterschap is formeel ingetrokken door het bevoegd gezag|
|Ten onrechte opgevoerd	|Het waterschap is ten onrechte opgevoerd in de registratie|



#### Gemeente
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Gemeente |
| Onderdeel van NEN3610-objecttype |Registratieve ruimte  |

 

**Definitie**

| Naam  | Gemeente |
|---|---|
| Definitie | Een gemeente is een afgebakend gedeelte van het grondgebied van Nederland, onder zeggenschap van een openbaar lichaam met diverse bestuurlijke taken, ingesteld op basis van artikel 123 van de Grondwet en de Gemeentewet.|
|Herkomst definitie  | Grondwet en Gemeentewet.  |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de gemeentegrenzen zoals opgenomen in de basisregistratie kadaster. |
|Toelichting| |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van de gemeente |Ja |
|Gemeentecode|	De codering van een gemeente zoals deze door het CBS wordt gebruikt.|Ja |
|Formele naam|	De naam van een gemeente zoals formeel benoemd door het bevoegd gezag.|Ja |
|Alternatieve naam|	Een alternatieve benaming van een gemeente zoals deze bekend staat in het Fries (bij een formele benaming in het Nederlands) of in het Nederlands (bij een formele benaming in het Fries)|Nee |
|Geometrie| De geometrische representatie van de randen van het gebied dat als gemeente is benoemd. |Ja (vlak)|
|Status   | De fase van de levenscyclus waarin de gemeente zich bevindt.  |Ja   |
| Landcode |	De codering van het land zoals deze door de RVIG wordt gebruikt.|Ja|


**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|ligt in |gerelateerde provincie |ja |

**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Aangewezen	|De Gemeente is formeel aangewezen door het bevoegd gezag|
|Ingetrokken	|De Gemeente is formeel ingetrokken door het bevoegd gezag|
|Ten onrechte opgevoerd	|De Gemeente is ten onrechte opgevoerd in de registratie|


#### Nederlandse territoriale zee

| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Nederlandse territoriale zee |
| Onderdeel van NEN3610-objecttype |Registratieve ruimte  |

 

**Definitie**

| Naam  | Nederlandse territoriale zee |
|---|---|
| Definitie | De Nederlandse territoriale zee is het gebied vanaf de laagwaterlijn tot 12 zeemijl uit de kust.|
|Herkomst definitie  | Wet grenzen Nederlandse territoriale zee.  |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de territoriale zee zoals nu reeds wordt vastgelegd door de Dienst der Hydrografie. Dit was tot nu toe nog geen onderdeel van een basisregistratie.  |
|Toelichting| |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van de Nederlandse territoriale zee |Ja |
|Geometrie| De geometrische representatie van de randen van het gebied dat als Nederlandse territoriale zee is benoemd. |Ja (vlak)|
|Status   | De fase van de levenscyclus waarin de Nederlandse territoriale zee zich bevindt.  |Ja   |
| Landcode |	De codering van het land zoals deze door de RVIG wordt gebruikt.|Ja|




**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Aangewezen	|De Nederlandse territoriale zee is formeel aangewezen door het bevoegd gezag|
|Ingetrokken	|De Nederlandse territoriale zee is formeel ingetrokken door het bevoegd gezag|
|Ten onrechte opgevoerd	|De Nederlandse territoriale zee is ten onrechte opgevoerd in de registratie|


#### Nederlandse aansluitende zone

| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Nederlandse aansluitende zone |
| Onderdeel van NEN3610-objecttype |Registratieve ruimte  |

 

**Definitie**

| Naam  | Nederlandse aansluitende zone |
|---|---|
| Definitie | De Nederlandse aansluitende zone is het gebied buiten en grenzend aan de territoriale zee dat zich niet verder uitstrekt dan 24 zeemijlen vanaf de laagwaterlijn.|
|Herkomst definitie  | Rijkswet instelling aansluitende zone.  |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de aansluitende zone zoals nu reeds wordt vastgelegd door de Dienst der Hydrografie. Dit was tot nu toe nog geen onderdeel van een basisregistratie.  |
|Toelichting| |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van de Nederlandse aansluitende zone |Ja |
|Geometrie| De geometrische representatie van de randen van het gebied dat als Nederlandse aansluitende zone is benoemd. |Ja (vlak)|
|Status   | De fase van de levenscyclus waarin de Nederlandse aansluitende zone zich bevindt.  |Ja   |
| Landcode |	De codering van het land zoals deze door de RVIG wordt gebruikt.|Ja|




**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Aangewezen	|De Nederlandse aansluitende zone is formeel aangewezen door het bevoegd gezag|
|Ingetrokken	|De Nederlandse aansluitende zone is formeel ingetrokken door het bevoegd gezag|
|Ten onrechte opgevoerd	|De Nederlandse aansluitende zone is ten onrechte opgevoerd in de registratie|








#### Nederlandse exclusieve economische zone
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Nederlandse exclusieve economische zone |
| Onderdeel van NEN3610-objecttype |Registratieve ruimte  |

 

**Definitie**

| Naam  | Nederlandse exclusieve economische zone |
|---|---|
| Definitie | De Nederlandse exclusieve economische zone is het gebied buiten en grenzend aan de territoriale zee dat zich niet verder uitstrekt dan tweehonderd zeemijlen vanaf de laagwaterlijn.|
|Herkomst definitie  | Rijkswet instelling exclusieve economische zone.  |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de Nederlandse exclusieve economische zone zoals nu reeds wordt vastgelegd door de Dienst der Hydrografie. Dit was tot nu toe nog geen onderdeel van een basisregistratie.  |
|Toelichting| |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van de Nederlandse exclusieve economische zone |Ja |
|Geometrie| De geometrische representatie van de randen van het gebied dat als Nederlandse exclusieve economische zone is benoemd. |Ja (vlak)|
|Status   | De fase van de levenscyclus waarin de Nederlandse exclusieve economische zone zich bevindt.  |Ja   |
| Landcode |	De codering van het land zoals deze door de RVIG wordt gebruikt.|Ja|




**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Aangewezen	|De Nederlandse exclusieve economische zone is formeel aangewezen door het bevoegd gezag|
|Ingetrokken	|De Nederlandse exclusieve economische zone is formeel ingetrokken door het bevoegd gezag|
|Ten onrechte opgevoerd	|De Nederlandse exclusieve economische zone is ten onrechte opgevoerd in de registratie|



### Woonplaats
| Klasse  | Naam  |
|---|---|
|SOR-begrip   | woonplaats  |
| Onderdeel van NEN3610-objecttype |Registratieve ruimte   |


ontwerpprincipe: *een woonplaats valt volledig binnen een gemeente*

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



**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|ligt in   |Gerelateerde gemeente | Ja |


**Domeinwaarden**


|Waarde Status| Beschrijving   |
|---|---|
| Aangewezen |Woonplaats is formeel aangewezen door het bevoegd gezag |
| Ingetrokken | Woonplaats is formeel ingetrokken door het bevoegd gezag  |
| Ten onrechte | Woonplaats is ten onrechte opgevoerd in de registratie |

### Wijk

| Klasse  | Naam  |
|---|---|
| SOR-begrip   | wijk  |
| Onderdeel van NEN3610-objecttype |Registratieve ruimte   |

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



**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|ligt in   |Gerelateerde gemeente | Ja |

ontwerpprincipe: *een wijk valt volledig binnen een gemeente*

ontwerpprincipe: *Geometrie van alle wijken in NL moet vlakdekkend zijn (op land) en mag niet overlappen*


**Domeinwaarden**


| Waarde Status | Beschrijving   |
|---|---|
| Aangewezen | Wijk is benoemd door het bevoegd gezag |
| Ingetrokken | Wijk is ingetrokken door het bevoegd gezag  |
| Ten onrechte | Wijk is ten onrechte opgevoerd in de registratie |


### Buurt

| Klasse  | Naam  |
|---|---|
| SOR-begrip   | buurt  |
| onderdeel van NEN3610-objecttype |Registratieve ruimte  |

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


**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|ligt in   |Gerelateerde wijk | Ja |


ontwerpprincipe: *buurten vallen binnen wijken*

ontwerpprincipe: *Geometrie van alle buurten in NL moet vlakdekkend zijn (op land) en mag niet overlappen*

**Domeinwaarden**


| Waarde Status| Beschrijving   |
|---|---|
| Aangewezen | Buurt is benoemd door het bevoegd gezag |
| Ingetrokken | Buurt is ingetrokken door het bevoegd gezag  |
| Ten onrechte | Buurt is ten onrechte opgevoerd in de registratie |


### Openbare ruimte

| Klasse  | Naam  |
|---|---|
|SOR-begrip   | Openbare ruimte  |
| Onderdeel van NEN3610-objecttype |Registratieve ruimte  |

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
|Alternatieve naam|Een alternatieve benaming van een openbare ruimte zoals deze breed is geaccepteerd in de volksmond of zoals deze bekend staat in het Fries (bij een formele benaming in het Nederlands) of in het Nederlands (bij een formele benaming in het Fries) | Nee|
|Geometrie   |De geometrische representatie van de randen van het gebied dat als openbare ruimte is benoemd  | Nee  |
|Status   |De fase van de levenscyclus waarin de betreffende openbare ruimte zich bevindt    |Ja   |


**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|ligt in   |Gerelateerde woonplaats | Ja |

**Domeinwaarden**


| Waarde Status | Beschrijving   |
|---|---|
| Aangewezen | Openbare ruimte is formeel uitgegeven door het bevoegd gezag |
| Ingetrokken | Openbare ruimte is formeel ingetrokken door het bevoegd gezag  |
| Ten onrechte | Openbare ruimte is ten onrechte opgevoerd in de registratie |

.

| Waarde Type | Beschrijving   |
|---|---|
| Weg|Transportvoorzienning voor wegverkeer |
| Waterlement |Transportvoorzienning voor water|

ontwerpprincipe: *Bij het objecttype spoorweg wordt een (vrijwillige) eigenschap “Naam spoorweg” opgenomen*

ontwerpprincipe: *Bij het objecttype kunstwerk (of eventuele verfijningen daarvan) wordt een (vrijwillige) eigenschap “Naam kunstwerk” opgenomen*

ontwerpprincipe: *Bij het objecttype weg wordt een verwijzing opgenomen naar de identificatiecode van de openbare ruimte waarbinnen de weg is gelegen (als deze formeel is benoemd)*

ontwerpprincipe: *Bij het objecttype waterelement wordt een verwijzing opgenomen naar de identificatiecode van de openbare ruimte waarbinnen het waterelement is gelegen (als deze formeel is benoemd)*

ontwerpprincipe: *Bij het objecttype geografisch gebied wordt een (vrijwillige) eigenschap “Naam geografisch gebied” opgenomen*

ontwerpprincipe: *Bij het objecttype functioneel object (of eventuele verfijningen daarvan) wordt een (vrijwillige) eigenschap “Naam functioneel object” opgenomen*


### Nummeraanduiding

| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Nummeraanduiding  |
| Onderdeel van NEN3610-objecttype |Registratieve ruimte  |

**Definitie**

| Naam  | Nummeraanduiding  |
|---|---|
| Definitie | Een nummeraanduiding is een door het bevoegde gemeentelijke orgaan als zodanig toegekende aanduiding van een verblijfsobject of een benoemde plaats.  |
|Herkomst definitie  | Gebaseerd op Artikel 1 wet Basisregistratie adressen en gebouwen |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie zoals opgenomen in de basisregistratie adressen en gebouwen  |
|Toelichting| *volgt later* |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een Nummeraanduiding  |Ja |
|Huisnummer |Een door of namens het gemeentebestuur aan een verblijfsobject of benoemde plaats toegekende nummering   |Ja|
|Huisletter | Een door of namens het gemeentebestuur aan een verblijfsobject of benoemde plaats toegekende toevoeging aan een huisnummer in de vorm van een alfanumeriek teken  |Ja|
|Huisnummer  toevoeging| Een door of namens het gemeentebestuur aan een verblijfsobject of benoemde plaats toegekende nadere toevoeging aan een huisnummer of een combinatie van huisnummer en huisletter |Ja|
|Postcode | De door PostNL vastgestelde code behorende bij een bepaalde combinatie van een straatnaam en een huisnummer|Ja|
|Type object | De aard van het object waaraan een nummeraanduiding is toegekend| Ja|
|Status   |De fase van de levenscyclus waarin de betreffende Nummeraanduiding zich bevindt    |Ja   |


**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|ligt aan| gerelateerde openbare ruimte |Ja|
|ligt in   |Gerelateerde woonplaats | Ja |

**Domeinwaarden**


| Waarde Status | Beschrijving   |
|---|---|
| Aangewezen | Nummeraanduiding is formeel uitgegeven door het bevoegd gezag |
| Ingetrokken | Nummeraanduiding is formeel ingetrokken door het bevoegd gezag  |
| Ten onrechte | Nummeraanduiding is ten onrechte opgevoerd in de registratie |

.

| Waarde Type | Beschrijving   |
|---|---|
| Verblijfsobject |Nummeraanduiding is bedoeld voor een verblijfsobject |
| Benoemde plaats |Nummeraanduiding is bedoeld voor een benoemde plaats |


### Benoemde plaats

| Klasse  | naam  |
|---|---|
| SOR-begrip   | Benoemde plaats  |
| Onderdeel van NEN3610-objecttype |Registratieve ruimte  |

**Definitie**

| Naam  | Benoemde plaats |
|---|---|
| Definitie | Door het bevoegde gemeentelijk orgaan als zodanig aangewezen delen van een terrein en/of water waarvan het belang is daaraan een adres toe te kennen en dat bedoeld is voor het permanent plaatsen van een niet direct en niet duurzaam met de aarde verbonden ruimte, het permanent afmeren van een drijvend object of het permanent aanwezig zijn van specifieke technische voorzieningen.  |
|Herkomst definitie  | Gebaseerd op artikel 1 wet Basisregistratie adressen en gebouwen |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Stand- en ligplaatsen worden momenteel door gemeenten afgebakend in het kader van de BAG. Dit meer generieke object biedt ook mogelijkheden voor andere objecten (zoals onbemande tankstations).  |
|Toelichting| *volgt later* |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een benoemde plaats  |Ja |
|Geometrie| De geometrische representatie van de randen van het gebied dat als benoemde ruimte is benoemd. |Ja|
|Status   |De fase van de levenscyclus waarin de betreffende Benoemde plaats zich bevindt    |Ja   |
|Type benoemde plaats| De aard van het object op de benoemde plaats|Ja|





**Domeinwaarden**


| Waarde Status | Beschrijving   |
|---|---|
|Aangewezen| Benoemde plaats is formeel uitgegeven door het bevoegd gezag |
| Ingetrokken | Benoemde plaats is formeel ingetrokken door het bevoegd gezag  |
| Ten onrechte | Benoemde plaats is ten onrechte opgevoerd in de registratie |

'

| Waarde Type benoemde plaats| Beschrijving   |
|---|---|
|Mobiele ruimte||
|Drijvend object||
|Tankstation||

