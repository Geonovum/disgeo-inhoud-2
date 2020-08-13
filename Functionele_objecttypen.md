## Functionele objecttypen


### Netwerk
| klasse  | naam  |
|---|---|
|SOR-begrip   | netwerk  |
| onderdeel van NEN3610-objecttype | transportvoorziening  |

Voor de functionele typering van netwerken is aangesloten bij de beschikbare typeringen in de BGT|IMGeo voor wegen en spoor. Verdere afstemming is nodig met NWB, IMBOR/IMWV, Prorail en de watersector. Voor wegverbindingen zijn de voorstellen voor IMGeo 2.2 overgenomen. Voor spoorverbindingen is de typering vereenvoudigd. Het uitgangspunt dat objecttypen scherp zijn afgebakend, maakt dat de typering sneltram is vervallen en dat havenkraan vervangen is door (laad-/los)kraan.

#### Wegennetwerk


|Objecttype |classificatie (verplicht)	| Plus classificatie (vrijwillig)|
|-----------|---------------------------|--------------------------------|
|Wegverbindingen|	Functie:	 ||
|| 	OV-baan	 ||
|| 	overweg	 ||
|| 	spoorbaan	 ||
|| 	baan voor vliegverkeer	 ||
|| 	rijbaan autosnelweg	|Verbindingsweg|
||| 	 	calamiteitendoorsteek|
|||		Verkeersdrempel|
|| 	rijbaan autoweg	|Verbindingsweg|
||| 	 	calamiteitendoorsteek|
|||		Verkeersdrempel|
|| 	rijbaan regionale weg	|Verbindingsweg|
|||		Verkeersdrempel|
||	rijbaan lokale weg	|Verkeersdrempel|
||	fietspad	|Verkeersdrempel|
||	voetpad	||
||	voetpad op trap	||
||	ruiterpad	||
||	inrit	||
|||| 	 	 


#### Spoornetwerk

Objecttype |classificatie (verplicht)	| Plus classificatie (vrijwillig)|
|-----------|---------------------------|--------------------------------|
|
|Spoorverbindingen	|Functie:	 ||
|| 	trein	 ||
|| 	tram	 ||
||*Niet BGT*| 	 	(laad/los-)kraan|
|||| 	 	

#### Waternetwerk

Objecttype |classificatie (verplicht)	| Plus classificatie (vrijwillig)|
|-----------|---------------------------|--------------------------------|
	 
|Waterwegverbindingen	|Functie:	 ||
|| 	vaaweg	 ||
|| 	hydrologie???	 ||
|||| 	 	 
||Knooppunten	\Type:	 |
|| 	kruispunt fysieke wegen	 ||
|| 	overweg	 ||
|| 	wijziging attribuutwaarde	 ||
|| 	tussenpunt	 ||
||||


### Functionele zonering
| klasse  | naam  |
|---|---|
|SOR-begrip   | functionele zonering |
| onderdeel van NEN3610-objecttype |functioneel object  |



De functionele zoneringen zijn voor het overzicht opgedeeld in grijze, groene en blauwe gebieden met een objecttypering. Deze indeling is functioneel ingestoken en heeft geen relatie met het fysieke voorkomen in het terrein. Hierbij is aangesloten op de typering zoals voor BGT|IMGeo wordt gebruikt, inclusief de voorstellen voor IMGeo 2.2. Als gevolg van het uitgangspunt dat fysiek en functie worden gescheiden zijn een aantal functies verschoven van voorheen een typering bij een fysiek objecttype naar een eigenstandig functioneel objecttype.

#### GRIJS


|Objecttype |classificatie (verplicht)	| Plus classificatie (vrijwillig)|
|-----------|---------------------------|--------------------------------|
|Functioneel Gebied (grijs)|	Functie:	 ||
|| 	verkeerseiland	|Vluchtheuvel|
||| 	 	Verkeersdruppel|
|| 	berm	 ||
|| 	parkeervlak	|Carpoolplaats|
||*Niet BGT*| 	 	Halteplaats
||*Niet BGT*|	 	verkeersaansluiting
||*Niet BGT*| 	 	verkeersknooppunt|
||*Niet BGT*| 	 	Verkeerskruispunt|
||*Niet BGT*| 	 	Verkeerszone|
||*Niet BGT*| 	 	Voetgangersgebied|
||*Niet BGT*| 	 	Woonerf|
||*Niet BGT*| 	 	infrastructuur verkeer en vervoer|
||*Niet BGT*| 	 	Bushalte|
||*Niet BGT*| 	 	Benzinestation|
||*Niet BGT*| 	 	Verzorgingsplaats|  

#### GROEN

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
  
#### BLAUW 

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

|Waarde type reducering| Beschrijving   |Herkomst|
|---|---|---|
|geluid|	voorziening bedoeld om geluidshinder in de buitenlucht te verminderen|	nieuw|
|fijnstof|	voorziening bedoeld om verspreiding van fijnstof te verminderen	|nieuw|

#### kering

| klasse  | naam  |
|---|---|
|SOR-begrip   | kering|
| onderdeel van NEN3610-objecttype | **functioneel object** |

ontwerpprincipe: 


**Definitie**

| Naam  | kering |
|---|---|
| Definitie |voorziening met kerende functie|
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

|Waarde type kering| Beschrijving   |Herkomst|
|---|---|---|
|grond	|voorziening bedoeld om grond te keren|	nieuw|
|water	|voorziening bedoeld om water te keren|	nieuw|


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
##### perron
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


##### Oever/slootkant

| klasse  | naam  |
|---|---|
|SOR-begrip   | Oever/slootkant |
| onderdeel van NEN3610-objecttype |Functioneel object  |

ontwerpprincipe: 

**Definitie**

| Naam  | Oever/slootkant  |
|---|---|
| Definitie |   |
|Herkomst definitie  |    |
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
  
  
### Bebouwing

De typering behorende bij de aan gebouwen gerelateerde functionele objecttypen zal in het vervolgtraject nader worden onderzocht.

#### Gebouwzone


#### Verblijfsobject



### Functionele objecttypen uit BRT

De typering behorende bij de aan gebouwen gerelateerde functionele objecttypen zal in het vervolgtraject nader worden onderzocht.




