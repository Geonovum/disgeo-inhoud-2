## Transponering

In dit hoofdstuk wordt aangegeven hoe elementen uit de huidige basisregistraties als begrip terugkomen in de samenhangende objectenregistratie. 
Ook wordt aangegeven als er voor is gekozen om bepaalde elementen NIET terug te laten keren in de SOR. 
Daarnaast zijn er nog andere bronnen waarvandaan elementen in de SOR worden overgenomen. 

### BGT en IMGeo

|Object|BGT classificatie (verplicht)|Plus classificatie (optioneel)|SOR-begrip in dit document|
|-----------------|----------------------|-----------------|---------------|
| **Wegdeel**               | Functie:               |                        |                                                                                         |
|                           | OV-baan                |                        | verkeerskundig functionele zone: type OV-baan                                           |
|                           | overweg                |                        | spoorzone: type overweg                                                                 |
|                           | spoorbaan              |                        | spoorzone: type spoorbaan                                                               |
|                           | baan voor vliegverkeer |                        | luchtvaartzone: type baan voor vliegverkeer                                             |
|                           | rijbaan autosnelweg    |                        | wegverbinding: type autosnelweg                                                         |
|                           | rijbaan autosnelweg    | verbindingsweg         | wegverbinding: type verbindingsbaan                                                     |
|                           | rijbaan autosnelweg    | calamiteitendoorsteek  | *nog onbekend*                                                                          |
|                           | rijbaan autoweg        |                        | wegverbinding: type autoweg                                                             |
|                           | rijbaan autoweg        | verbindingsweg         | wegverbinding: type verbindingsbaan                                                     |
|                           | rijbaan autoweg        | calamiteitendoorsteek  | *nog onbekend*                                                                          |
|                           | rijbaan regionale weg  |                        | wegverbinding: type gebiedsontsluitingsweg                                              |
|                           | rijbaan regionale weg  | verbindingsweg         | wegverbinding: type verbindingsbaan                                                     |
|                           | rijbaan regionale weg  | verkeersdrempel        | wegzone: type verkeersdrempel                                                           |
|                           | rijbaan lokale weg     |                        | wegverbinding: type erftoegangsweg                                                      |
|                           | rijbaan lokale weg     | verkeersdrempel        | wegzone: type verkeersdrempel                                                           |
|                           | fietspad               |                        | wegverbinding: type fietspad                                                            |
|                           | voetpad                |                        | wegverbinding: type voetpad                                                             |
|                           | voetpad op trap        |                        | wegverbinding: type voetpad                                                             |
|                           | ruiterpad              |                        | wegverbinding: type ruiterpad                                                           |
|                           | parkeervlak            |                        | verkeerskundig functionele zone: type parkeervlak                                       |
|                           | voetgangersgebied      |                        | *vervalt waarschijnlijk, wordt vervangen door netwerk en eigenschappen van het netwerk* |
|                           | inrit                  |                        | verkeerskundig functionele zone: type inrit                                             |
|                           | woonerf                |                        | *vervalt waarschijnlijk, wordt vervangen door netwerk en eigenschappen van het netwerk* |
|                           |                        |                        |                                                                                         |
| **Wegdeel**               | Fysiek voorkomen:      |                        |                                                                                         |
|                           | gesloten verharding    | asfalt                 | verharding: asfaltverharding                                                            |
|                           |                        | cementbeton            | verharding: betonverharding                                                             |
|                           | open verharding        | betonstraatstenen      | verharding: elementenverharding                                                         |
|                           |                        | gebakken klinkers      | verharding: elementenverharding                                                         |
|                           |                        | tegels                 | verharding: elementenverharding                                                         |
|                           |                        | sierbestrating         | verharding: elementenverharding                                                         |
|                           |                        | beton element          | verharding: elementenverharding                                                         |
|                           | half verhard           | grasklinkers           | verharding: halfverharding                                                              |
|                           |                        | schelpen               | verharding: halfverharding                                                              |
|                           |                        | puin                   | verharding: halfverharding                                                              |
|                           |                        | grind                  | verharding: halfverharding                                                              |
|                           |                        | gravel                 | verharding: halfverharding                                                              |
|                           | onverhard              | boomschors             | verharding: halfverharding                                                              |
|                           |                        | zand                   | verharding: onverhard of onbegroeide grond                                              |
|                           |                        |                        |                                                                                         |

|Object|BGT classificatie (verplicht)|Plus classificatie (optioneel)|SOR-begrip in dit document|
|-----------------|----------------------|-----------------|---------------|
| **Ondersteunend wegdeel** | Functie:               |                        |                                                                                         |
|                           | verkeerseiland         |                        | wegzone: type verkeerseiland                                                            |
|                           | berm                   |                        | wegzone: type berm                                                                      |
|                           |                        |                        |                                                                                         |
| **Ondersteunend wegdeel** | Fysiek voorkomen:      |                        |                                                                                         |
|                           | gesloten verharding    | asfalt                 | verharding: asfaltverharding                                                            |
|                           |                        | cementbeton            | verharding: betonverharding                                                             |
|                           | open verharding        | betonstraatstenen      | verharding: elementenverharding                                                         |
|                           |                        | gebakken klinkers      | verharding: elementenverharding                                                         |
|                           |                        | tegels                 | verharding: elementenverharding                                                         |
|                           |                        | sierbestrating         | verharding: elementenverharding                                                         |
|                           |                        | beton element          | verharding: elementenverharding                                                         |
|                           | half verhard           | grasklinkers           | verharding: halfverharding                                                              |
|                           |                        | schelpen               | verharding: halfverharding                                                              |
|                           |                        | puin                   | verharding: halfverharding                                                              |
|                           |                        | grind                  | verharding: halfverharding                                                              |
|                           |                        | gravel                 | verharding: halfverharding                                                              |
|                           | onverhard              | boomschors             | verharding: halfverharding                                                              |
|                           |                        | zand                   | verharding: onverhard of onbegroeide grond                                              |
|                           | groenvoorziening       | bosplantsoen           | struiken                                                                                |
|                           |                        | gras- en kruidachtigen | gras- en kruidachtigen                                                                  |
|                           |                        | planten                | struiken                                                                                |
|                           |                        | struikrozen            | struiken                                                                                |
|                           |                        | heesters               | struiken                                                                                |
|                           |                        | bodembedekkers         | struiken                                                                                |
|                           |                        |                        |                                                                                         |

|Object|BGT classificatie (verplicht)|Plus classificatie (optioneel)|SOR-begrip in dit document|
|-----------------|----------------------|-----------------|---------------|
| **Spoor**                 | Functie:               |                        |                                                                                         |
|                           | trein                  |                        | spoorweg: type spoorverbinding                                                          |
|                           | sneltram               |                        | spoorweg: type spoorverbinding                                                          |
|                           | tram                   |                        | spoorweg: type spoorverbinding                                                          |
|                           | Niet BGT               | (haven)kraan           | *nog onbekend*                                                                          |

.

|Object|BGT classificatie (verplicht)|Plus classificatie (optioneel)|SOR-begrip in dit document|
|-----------------|----------------------|-----------------|---------------|
| **Onbegroeid terreindeel** | Fysiek voorkomen:   |                        |                                            |
|                            | erf                 |                        | onbepaald terreindeel                      |
|                            | gesloten verharding | asfalt                 | verharding: asfaltverharding               |
|                            |                     | cementbeton            | verharding: betonverharding                |
|                            |                     | kunststof              | verharding: kunststofverharding            |
|                            | open verharding     | betonstraatstenen      | verharding: elementenverharding            |
|                            |                     | gebakken klinkers      | verharding: elementenverharding            |
|                            |                     | tegels                 | verharding: elementenverharding            |
|                            |                     | sierbestrating         | verharding: elementenverharding            |
|                            |                     | beton element          | verharding: elementenverharding            |
|                            | half verhard        | grasklinkers           | verharding: halfverharding                 |
|                            |                     | schelpen               | verharding: halfverharding                 |
|                            |                     | puin                   | verharding: halfverharding                 |
|                            |                     | grind                  | verharding: halfverharding                 |
|                            |                     | gravel                 | verharding: halfverharding                 |
|                            | onverhard           | boomschors             | verharding: halfverharding                 |
|                            |                     | zand                   | verharding: onverhard of onbegroeide grond |
|                            | zand                | strand en strandwal    | geografisch object: type strand            |
|                            |                     | zandverstuiving        | geografisch object: type zandverstuiving   |
|                            |                     |                        |                                            |
|                            |                     |                        |                                            |

|Object|BGT classificatie (verplicht)|Plus classificatie (optioneel)|SOR-begrip in dit document|
|-----------------|----------------------|-----------------|---------------|
| **Begroeid terreindeel**   | Fysiek voorkomen:   |                        |                                            |
|                            | loofbos             | griend en hakhout      | bos: type loofbos                          |
|                            | gemengd bos         |                        | bos: type gemengd bos                      |
|                            | naaldbos            |                        | bos: type naaldbos                         |
|                            | heide               |                        | heide                                      |
|                            | struiken            |                        | struiken                                   |
|                            | houtwal             |                        | houtsingel                                 |
|                            | duin                | open duinvegetatie     | duin                                       |
|                            |                     | gesloten duinvegetatie | duin                                       |
|                            | grasland overig     |                        | gras- en kruidachtigen                     |
|                            | moeras              |                        | moeras                                     |
|                            | rietland            |                        | rietland                                   |
|                            | kwelder             |                        | getijdengebied: type schor                 |
|                            | fruitteelt          | laagstam boomgaarden   | fruit- en kweekboom                        |
|                            |                     | hoogstam boomgaarden   | fruit- en kweekboom                        |
|                            |                     | wijngaarden            | fruit- en kweekboom                        |
|                            |                     | klein fruit            | fruit- en kweekboom                        |
|                            | boomteelt           |                        | fruit- en kweekboom                        |
|                            | bouwland            | akkerbouw              | gewas                                      |
|                            |                     | braakliggend           | gewas                                      |
|                            |                     | vollegrondsteelt       | gewas                                      |
|                            |                     | bollenteelt            | gewas                                      |
|                            | grasland agrarisch  |                        | gras- en kruidachtigen                     |
|                            | groenvoorziening    | bosplantsoen           | struiken                                   |
|                            |                     | gras- en kruidachtigen | gras- en kruidachtigen                     |
|                            |                     | planten                | struiken                                   |
|                            |                     | struikrozen            | struiken                                   |
|                            |                     | heesters               | struiken                                   |
|                            |                     | bodembedekkers         | struiken                                   |

.

|Object|BGT classificatie (verplicht)|Plus classificatie (optioneel)|SOR-begrip in dit document|
|-----------------|----------------------|-----------------|---------------|
| **Waterdeel**               | Type:               |                         |                                                          |
|                             | zee                 |                         | watervlakte: type zee                                    |
|                             | waterloop           | rivier                  | waterloop: type rivier                                   |
|                             |                     | sloot                   | waterloop: type sloot                                    |
|                             |                     | kanaal                  | waterloop: type kanaal                                   |
|                             |                     | beek                    | waterloop: type beek                                     |
|                             |                     | gracht                  | waterloop: type gracht                                   |
|                             |                     | bron                    | bron                                                     |
|                             | watervlakte         | haven                   | functionele zone: havencomplex : aanleg en overslag      |
|                             |                     | meer, plas, ven, vijver | watervlakte: type meer, type plas, type ven, type vijver |
|                             | greppel/droge sloot |                         | *vervalt waarschijnlijk, wordt eigenschap bij waterloop* |
|                             |                     |                         |                                                          |


|Object|BGT classificatie (verplicht)|Plus classificatie (optioneel)|SOR-begrip in dit document|
|-----------------|----------------------|-----------------|---------------|
| **Ondersteunend waterdeel** | oever/slootkant     |                         | oever                                                    |
|                             | slik                |                         | getijdengebied: type slik                                |

.

|Object|BGT classificatie (verplicht)|Plus classificatie (optioneel)|SOR-begrip in dit document|
|-----------------|----------------------|-----------------|---------------|
| **Pand**            | Grondvlaksituatie van BAG-pand  |            | Gebouw                                                      |
|                     |                                 |            |                                                             |

|Object|BGT classificatie (verplicht)|Plus classificatie (optioneel)|SOR-begrip in dit document|
|-----------------|----------------------|-----------------|---------------|
| **Overig bouwwerk** | Type:                           |            |                                                             |
|                     | overkapping (maaiveldgeometrie) |            | open bouwwerk: type overkapping                             |
|                     | open loods                      |            | open bouwwerk: type open loods                              |
|                     | opslagtank                      |            | Depot: type opslagtank                                      |
|                     | bezinkbak                       |            | overig kunstwerk: type bezinkbak                            |
|                     | windturbine                     |            | mast: type windturbinemast en installatie: type windturbine |
|                     | lage trafo                      |            | Kast: type electra                                          |
|                     | bassin                          |            | bak: type bassin                                            |
|                     | Niet BGT                        | bunker     | bunker                                                      |
|                     | Niet BGT                        | voedersilo | Depot: type voedersilo                                      |
|                     | Niet BGT                        | schuur     | gebouw, met typering                                        |
|                     |                                 |            |                                                             |


|Object|BGT classificatie (verplicht)|Plus classificatie (optioneel)|SOR-begrip in dit document|
|-----------------|----------------------|-----------------|---------------|
| **Scheiding** | Type:          |             | Ondergebracht bij functie: afscheiding, kering, reducering |
|               | muur           |             | muur                                                       |
|               | Kademuur       |             | kerend kunstwerk: type kademuur                            |
|               | damwand        |             | kerend kunstwerk: type damwand                             |
|               | geluidsscherm  |             | scherm                                                     |
|               | walbescherming |             | kerend kunstwerk: type walbescherming                      |
|               | hek            |             | hek                                                        |
|               | Niet BGT       | draadraster | raster                                                     |
|               | Niet BGT       | faunaraster | raster                                                     |


.

|Object|BGT classificatie (verplicht)|Plus classificatie (optioneel)|SOR-begrip in dit document|
|-----------------|----------------------|-----------------|---------------|
| **Overbruggingsdeel** | overbruggingsdeel | Hoort bij type overbrugging: | overbrugging                      |
|                       |                   | brug                         | overbrugging: type brug           |
|                       |                   | aquaduct                     | overbrugging: type aquaduct       |
|                       |                   | viaduct                      | overbrugging: type viaduct        |
|                       |                   | ecoduct                      | overbrugging: type ecoduct        |
|                       |                   | fly-over                     | overbrugging: type fly-over       |
|                       |                   |                              |                                   |
|                       |                   | Type Overbruggingsdeel:      | kunstwerkdeel                     |
|                       |                   | dek                          | kunstwerkdeel: type dek           |
|                       |                   | landhoofd                    | kunstwerkdeel: type landhoofd     |
|                       |                   | pijler                       | kunstwerkdeel: type pijler        |
|                       |                   | sloof                        | kunstwerkdeel: type sloof         |
|                       |                   | pyloon                       | kunstwerkdeel: type pyloon        |
|                       |                   |                              |                                   |

|Object|BGT classificatie (verplicht)|Plus classificatie (optioneel)|SOR-begrip in dit document|
|-----------------|----------------------|-----------------|---------------|
| **Tunneldeel**        | Tunneldeel        |                              | ondertunneling: type tunnel       |
|                       |                   |                              |                                   |

|Object|BGT classificatie (verplicht)|Plus classificatie (optioneel)|SOR-begrip in dit document|
|-----------------|----------------------|-----------------|---------------|
| **Kunstwerkdeel**     | Type:             |                              |                                   |
|                       | hoogspanningsmast |                              | mast: type hoogspanningsmast      |
|                       | gemaal            |                              | overig kunstwerk: type gemaal     |
|                       | perron            |                              | spoorzone: type perron            |
|                       | sluis             |                              | kerend kunstwerk: type sluis      |
|                       | strekdam          |                              | overig kunstwerk: type strekdam   |
|                       | steiger           |                              | overig kunstwerk: type steiger    |
|                       | stuw              |                              | kerend kunstwerk: type stuw       |
|                       | Niet BGT          | keermuur                     | kerend kunstwerk: type keermuur   |
|                       | Niet BGT          | overkluizing                 | overbrugging: type overkluizing   |
|                       | Niet BGT          | duiker                       | ondertunneling: type duiker       |
|                       | Niet BGT          | faunavoorziening             | *vervalt waarschijnlijk*          |
|                       | Niet BGT          | vispassage                   | overig kunstwerk: type vispassage |
|                       | Niet BGT          | bodemval                     | overig kunstwerk: type bodemval   |
|                       | Niet BGT          | coupure                      | overig kunstwerk: type coupure    |
|                       | Niet BGT          | ponton                       | overig kunstwerk: type ponton     |
|                       | Niet BGT          | voorde                       | overig kunstwerk: type voorde     |


.

|Object|BGT classificatie (verplicht)|Plus classificatie (optioneel)|SOR-begrip in dit document|
|-----------------|----------------------|-----------------|---------------|
| **Functioneel Gebied** | Type:    |                                            |                                                         |
|                        | kering   |                                            | kering                                                  |
|                        | Niet BGT | bedrijvigheid                              | *vervalt waarschijnlijk*                                |
|                        | Niet BGT | natuur en landschap                        | *vervalt waarschijnlijk*                                |
|                        | Niet BGT | landbouw                                   | *vervalt waarschijnlijk*                                |
|                        | Niet BGT | bewoning                                   | *vervalt waarschijnlijk*                                |
|                        | Niet BGT | infrastructuur verkeer en vervoer          | *vervalt waarschijnlijk*                                |
|                        | Niet BGT | infrastructuur waterstaatswerken           | *vervalt waarschijnlijk*                                |
|                        | Niet BGT | waterbergingsgebied                        | *vervalt waarschijnlijk*                                |
|                        | Niet BGT | maatschappelijke en/of publieksvoorziening | *vervalt waarschijnlijk*                                |
|                        | Niet BGT | recreatie                                  | recreatie                                               |
|                        | Niet BGT | begraafplaats                              | begraafplaats                                           |
|                        | Niet BGT | functioneel beheer                         | *vervalt waarschijnlijk*                                |
|                        | Niet BGT | functioneel beheer: hondenuitlaatplaats    | *vervalt waarschijnlijk*                                |
|                        | Niet BGT | recreatie: speeltuin                       | recreatie: speeltuin                                    |
|                        | Niet BGT | recreatie: park                            | recreatie: park                                         |
|                        | Niet BGT | recreatie: sportterrein                    | recreatie: sportterrein                                 |
|                        | Niet BGT | recreatie: camping                         | recreatie: camping                                      |
|                        | Niet BGT | recreatie: bungalowpark                    | recreatie: bungalowpark                                 |
|                        | Niet BGT | recreatie: volkstuin                       | recreatie: volkstuin                                    |
|                        | Niet BGT | bushalte                                   | wegzone: type halteplaats                               |
|                        | Niet BGT | carpoolplaats                              | verkeerskundig functionele zone: type carpoolplaats     |
|                        | Niet BGT | benzinestation                             | verkeerskundig functionele zone: type benzinestation    |
|                        | Niet BGT | verzorgingsplaats                          | verkeerskundig functionele zone: type verzorgingsplaats |


.

|Object|BGT classificatie (verplicht)|Plus classificatie (optioneel)|SOR-begrip in dit document|
|-----------------|----------------------|-----------------|---------------|
| **Bak**                        |          | Type:                         | andere definitie                          |
|                                | Niet BGT | afval apart plaats            | bak: afval apart plaats                   |
|                                | Niet BGT | afvalbak                      | straatmeubilair                           |
|                                | Niet BGT | drinkbak                      | *vervalt waarschijnlijk*                  |
|                                | Niet BGT | bloembak                      | straatmeubilair                           |
|                                | Niet BGT | zand- / zoutbak               | straatmeubilair                           |
|                                | Niet BGT | container                     | bak: container                            |
|                                |          |                               |                                           |

|Object|BGT classificatie (verplicht)|Plus classificatie (optioneel)|SOR-begrip in dit document|
|-----------------|----------------------|-----------------|---------------|
| **Bord**                       |          | Type:                         |                                           |
|                                | Niet BGT | informatiebord                | paal                                      |
|                                | Niet BGT | plaatsnaambord                | paal                                      |
|                                | Niet BGT | straatnaambord                | paal                                      |
|                                | Niet BGT | verkeersbord                  | paal                                      |
|                                | Niet BGT | scheepvaartbord               | paal                                      |
|                                | Niet BGT | verklikker transportleiding   | paal                                      |
|                                | Niet BGT | reclamebord                   | paal                                      |
|                                | Niet BGT | wegwijzer                     | paal                                      |
|                                | Niet BGT | waarschuwingshek              | hek                                       |
|                                | Niet BGT | dynamische snelheidsindicator | paal                                      |
|                                |          |                               |                                           |

|Object|BGT classificatie (verplicht)|Plus classificatie (optioneel)|SOR-begrip in dit document|
|-----------------|----------------------|-----------------|---------------|
| **Gebouwinstallatie**          |          | Type:                         |                                           |
|                                | Niet BGT | bordes                        | gebouwcomponent: aard bordes              |
|                                | Niet BGT | luifel                        | gebouwcomponent: aard luifel              |
|                                | Niet BGT | toegangstrap                  | gebouwcomponent: aard toegangstrap        |
|                                |          |                               |                                           |

|Object|BGT classificatie (verplicht)|Plus classificatie (optioneel)|SOR-begrip in dit document|
|-----------------|----------------------|-----------------|---------------|
| **Installatie**                |          | Type:                         |                                           |
|                                | Niet BGT | pomp                          | Installatie: type pomp                    |
|                                | Niet BGT | zonnepaneel                   | Installatie: type zonnepanelen            |
|                                |          |                               |                                           |

|Object|BGT classificatie (verplicht)|Plus classificatie (optioneel)|SOR-begrip in dit document|
|-----------------|----------------------|-----------------|---------------|
| **Kast**                       |          | Type:                         |                                           |
|                                | Niet BGT | CAI-kast                      | kast: type telecom                        |
|                                | Niet BGT | elektrakast                   | kast: type elektra (inclusief lage trafo) |
|                                | Niet BGT | gaskast                       | kast: type gas                            |
|                                | Niet BGT | telecom kast                  | kast: type telecom                        |
|                                | Niet BGT | rioolkast                     | kast: type riool                          |
|                                | Niet BGT | openbare verlichtingkast      | kast: type openbare verlichting           |
|                                | Niet BGT | verkeersregelinstallatiekast  | kast: type verkeer                        |
|                                | Niet BGT | telkast                       | kast: type verkeer                        |
|                                | Niet BGT | GMS kast                      | kast: type verkeer                        |
|                                |          |                               |                                           |

|Object|BGT classificatie (verplicht)|Plus classificatie (optioneel)|SOR-begrip in dit document|
|-----------------|----------------------|-----------------|---------------|
| **Mast**                       |          | Type:                         |                                           |
|                                | Niet BGT | bovenleidingmast              | mast: type bovenleidingmast               |
|                                | Niet BGT | laagspanningsmast             | mast: type laagspanningsmast              |
|                                | Niet BGT | straalzender                  | mast: type straalzender                   |
|                                | Niet BGT | zendmast                      | mast: type zendmast                       |
|                                | Niet BGT | radarmast                     | mast: type radarmast                      |
|                                |          |                               |                                           |

|Object|BGT classificatie (verplicht)|Plus classificatie (optioneel)|SOR-begrip in dit document|
|-----------------|----------------------|-----------------|---------------|
| **Paal**                       |          | Type:                         |                                           |
|                                | Niet BGT | lichtmast                     | paal                                      |
|                                | Niet BGT | telpaal                       | paal                                      |
|                                | Niet BGT | portaal                       | paal                                      |
|                                | Niet BGT | verkeersregelinstallatiepaal  | paal                                      |
|                                | Niet BGT | verkeersbordpaal              | paal                                      |
|                                | Niet BGT | poller                        | straatmeubiliar                           |
|                                | Niet BGT | haltepaal                     | paal                                      |
|                                | Niet BGT | vlaggenmast                   | paal                                      |
|                                | Niet BGT | afsluitpaal                   | paal                                      |
|                                | Niet BGT | praatpaal                     | paal                                      |
|                                | Niet BGT | hectometerpaal                | paal                                      |
|                                | Niet BGT | dijkpaal                      | paal                                      |
|                                | Niet BGT | drukknoppaal                  | paal                                      |
|                                | Niet BGT | grensmarkering                | paal                                      |
|                                | Niet BGT | sirene                        | mast: type sirene                         |
|                                |          |                               |                                           |

|Object|BGT classificatie (verplicht)|Plus classificatie (optioneel)|SOR-begrip in dit document|
|-----------------|----------------------|-----------------|---------------|
| **Put**                        |          | Type:                         |                                           |
|                                | Niet BGT | benzine- / olieput            | putdeksel: benzine- / olie                |
|                                | Niet BGT | brandkraan / -put             | putdeksel: brandkraan                     |
|                                | Niet BGT | drainageput                   | putdeksel: riolering                      |
|                                | Niet BGT | gasput                        | putdeksel: gas                            |
|                                | Niet BGT | inspectie- / rioolput         | putdeksel: riolering                      |
|                                | Niet BGT | kolk                          | putdeksel: riolering                      |
|                                | Niet BGT | waterleidingput               | putdeksel: waterleiding                   |
|                                |          |                               |                                           |

|Object|BGT classificatie (verplicht)|Plus classificatie (optioneel)|SOR-begrip in dit document|
|-----------------|----------------------|-----------------|---------------|
| **Sensor**                     |          | Type:                         |                                           |
|                                | Niet BGT | camera                        | paal                                      |
|                                | Niet BGT | debietmeter                   | paal                                      |
|                                | Niet BGT | hoogtedetectieapparaat        | sensor: hoogtedetectieapparaat            |
|                                | Niet BGT | detectielus                   | *vervalt waarschijnlijk*                  |
|                                | Niet BGT | weerstation                   | paal                                      |
|                                | Niet BGT | flitser                       | paal                                      |
|                                | Niet BGT | waterstandmeter               | paal                                      |
|                                | Niet BGT | windmeter                     | paal                                      |
|                                | Niet BGT | lichtcel                      | paal                                      |
|                                | Niet BGT | GMS sensor                    | sensor: GMS sensor                        |
|                                | Niet BGT | radar detector                | paal                                      |
|                                |          |                               |                                           |

|Object|BGT classificatie (verplicht)|Plus classificatie (optioneel)|SOR-begrip in dit document|
|-----------------|----------------------|-----------------|---------------|
| **Straatmeubilair**            |          | Type:                         |                                           |
|                                | Niet BGT | abri                          | straatmeubilair                           |
|                                | Niet BGT | bolder                        | paal                                      |
|                                | Niet BGT | brievenbus                    | straatmeubilair                           |
|                                | Niet BGT | fietsenrek                    | straatmeubilair                           |
|                                | Niet BGT | kunstobject                   | straatmeubilair                           |
|                                | Niet BGT | openbaar toilet               | straatmeubilair                           |
|                                | Niet BGT | slagboom                      | straatmeubilair                           |
|                                | Niet BGT | speelvoorziening              | straatmeubilair                           |
|                                | Niet BGT | telefooncel                   | straatmeubilair                           |
|                                | Niet BGT | bank                          | straatmeubilair                           |
|                                | Niet BGT | picknicktafel                 | straatmeubilair                           |
|                                | Niet BGT | fontein                       | straatmeubilair                           |
|                                | Niet BGT | lichtpunt                     | straatmeubilair                           |
|                                | Niet BGT | parkeerbeugel                 | straatmeubilair                           |
|                                | Niet BGT | betaalautomaat                | straatmeubilair                           |
|                                | Niet BGT | reclamezuil                   | paal                                      |
|                                | Niet BGT | fietsenkluis                  | straatmeubilair                           |
|                                | Niet BGT | herdenkingsmonument           | straatmeubilair                           |
|                                |          |                               |                                           |

|Object|BGT classificatie (verplicht)|Plus classificatie (optioneel)|SOR-begrip in dit document|
|-----------------|----------------------|-----------------|---------------|
| **Waterinrichtings-element**   |          | Type:                         |                                           |
|                                | Niet BGT | remmingswerk                  | geleider: remmingswerk                    |
|                                | Niet BGT | betonning                     | paal                                      |
|                                | Niet BGT | geleidewerk                   | geleider: geleidewerk                     |
|                                | Niet BGT | vuilvang                      | kunstwerkdeel: type vuilvang              |
|                                | Niet BGT | meerpaal                      | paal                                      |
|                                | Niet BGT | hoogtemerk                    | *vervalt waarschijnlijk*                  |
|                                |          |                               |                                           |

|Object|BGT classificatie (verplicht)|Plus classificatie (optioneel)|SOR-begrip in dit document|
|-----------------|----------------------|-----------------|---------------|
| **Weginrichtings-element**     |          | Type:                         |                                           |
|                                | Niet BGT | molgoot                       | *vervalt waarschijnlijk*                  |
|                                | Niet BGT | lijnafwatering                | putdeksel: riolering                      |
|                                | Niet BGT | wegmarkering                  | *vervalt waarschijnlijk*                  |
|                                | Niet BGT | wildrooster                   | functionele wegzone:  type wildrooster    |
|                                | Niet BGT | rooster                       | *vervalt waarschijnlijk*                  |
|                                | Niet BGulT | geleideconstructie            | geleider: geleideconstructie              |
|                                | Niet BGT | balustrade                    | gesplitst: hek en functie: valbescherming |
|                                | Niet BGT | boomspiegel                   | *vervalt waarschijnlijk*                  |
|                                | Niet BGT | verblindingswering            | geleider: verblindingswering              |
|                                |          |                               |                                           |

|Object|BGT classificatie (verplicht)|Plus classificatie (optioneel)|SOR-begrip in dit document|
|-----------------|----------------------|-----------------|---------------|
| **Vegetatieobject**            |          | Type:                         |                                           |
|                                | Niet BGT | boom                          | boom                                      |
|                                | Niet BGT | haag                          | haag                                      |
|                                |          |                               |                                           |
|Object|BGT classificatie (verplicht)|Plus classificatie (optioneel)|SOR-begrip in dit document|
|-----------------|----------------------|-----------------|---------------|
| **Buurt**                      | Niet BGT |                               | registratief objecttype: buurt            |
| **Openbare Ruimte**            | Niet BGT |                               | registratief objecttype: openbare ruimte  |
| **Stadsdeel**                  | Niet BGT |                               | *vervalt waarschijnlijk*                  |
| **Waterschap**                 | Niet BGT |                               | registratief objecttype: waterschap       |
| **Wijk**                       | Niet BGT |                               | registratief objecttype: wijk             |
|                                |          |                               |                                           |

|Object|BGT classificatie (verplicht)|Plus classificatie (optioneel)|SOR-begrip in dit document|
|-----------------|----------------------|-----------------|---------------|
| kruinlijn: lijn                |          |                               | *vervalt waarschijnlijk als eigenschap*   |
| op talud: ja/nee               |          |                               | *vervalt waarschijnlijk als eigenschap*   |
| Overbrugging is beweegbaar J/N |          |                               | eigenschap bij overbrugging               |



### BAG

|BAG object | SOR-begrip in dit document|
|---|---|
|woonplaats	|registratief object; woonplaats|
|openbare ruimte|	registratief object; openbare ruimte|
|nummeraanduiding|	registratief object; nummeraanduiding|
|pand	|fysiek object; gebouw|
|ligplaats|	registratief object; benoemde plaats|
|standplaats|	registratief object; benoemde plaats|
|verblijfsobject|	functioneel object; verblijfsobject|


### BRT

De transponering vanuit de BRT zal op een later moment worden toegevoegd op basis van de resultaten van het traject BRT.Next.


### Nieuw in de SOR

Hier worden de begrippen aangeduid die nieuw zijn ten opzichte van de begrippen uit de basisregistraties waauit de SOR is doorontwikkeld. Het gaat daarbij om dingen in de werkelijkheid die voorheen in de basisregistraties nog niet waren opgenomen. Het gaat NIET om dingen in de werkelijkheid die al waren opgenomne maar die nu van een andere begripsnaam zijn voorzien. Deze worden in de voorgaande paragrafen van dit hoofdstuk al geduid.

Deze opsomming verwijst naar begrippen uit de index van het document. Indien een begrip een verbijzondering is van een begrip uit de index, wordt dit aangegeven door de naam uit de index gevolgd door een dubbelep punt en de naam van het begrip.

#### Reële objecten

- Onbegroeide grond
- Bouwland
- Landschapselement : Bomenrij
- Landschapselement : Tuunwal
- Gebouw *(voorheen pand)*
- Bouwlaag
- Ruimte
- Gebouwcomponent: dakkapel
- Gebouwcomponent: laadperron
- Gebouwcomponent: loopbrug
- Toegangsdeur
- Open bouwwerk: parkeergarage
- Kunstwerkdeel: sluisdeur
- Kunstwerkdeel: schutkolk
- Kunstwerrkdeel: vuilvang
- Waterstaatkundig kunstwerk
- Waterstaatkundig kunstwerk: schot
- Waterstaatkundig kunstwerk: dijk
- Waterstaatkundig kunstwerk: stormvloedkering
- Omheining
- Scherm
- Overige constructies: afvalcontainer
- Installatie: sirene
- Installatie: verkeerslicht
- Installatie: openbare verlichting
- Installatie: lift
- Installatie: oplaadpunt
- Mast: open
- Mast: gesloten
- Onbepaald terrein

#### Functionele ruimten

- Transportruimten: weg
- Transportruimten: spoorweg
- Gebouwzone
- Verkeerskundig functionele zone: halteplaats
- Verkeerskundig functionele zone: overstapplaats
- Verkeerskundig functionele zone: snellaadstation
- Verkeerskundig functionele zone: tolplaats
- Verkeerskundig functionele zone: tankstation
- Spoorzone: emplacement
- Luchtvaartzone: luchthaven
- Complex
- Reducering
- Valbescherming
- Afscheiding

#### Registratieve ruimten

- Rijk
- Provincie
- Waterschap
- Gemeente
- Nederlandse territoriale zee
- Nederlandse aansluitende zone
- Nederlandse exclusieve economische zone
- Wijk
- Buurt

#### Geografische ruimten

- Bebouwdingskern
- Streek
- Bosgebied
- Duingebied
- Heidegebied
- Watergebied
- Eiland
- Polder
- Relief



### Niet opnemen in SOR

Voorstel om de volgende, in BGT|IMGeo 2.2 opgenomen typeringen, niet meer op te nemen in de SOR:
-	wegdeel, functie calamiteitendoorsteek
-	overig bouwwerk, type voedersilo
-	kunstwerkdeel, type fauna voorziening
-	functioneel gebied, type bedrijvigheid
-	functioneel gebied, type natuur en landschap
-	functioneel gebied, type landbouw
-	functioneel gebied, type bewoning
-	functioneel gebied, type infrastructuur verkeer en vervoer
-	functioneel gebied, type waterbergingsgebied
-	functioneel gebied, type infrastructuur waterstaatswerken
-	functioneel gebied, type maatschappelijke en/of publieksvoorziening
-	functioneel gebied, type functioneel beheer
-	functioneel gebied, type functioneel beheer: hondenuitlaatplaats
-	bak, type drinkbak
-	bord, alle typen
-	mast, alle typen *)
-	paal, alle typen **)
-	sensor, alle typen
-	straatmeubilair, alle typen ***)
-	waterinrichtings-element, type betonning
-	waterinrichtings-element, type meerpaal
-	waterinrichtings-element, type hoogtemerk
-	weginrichtings-element, type molgoot
-	weginrichtings-element, type wegmarkering
-	weginrichtings-element, type rooster
-	weginrichtings-element, type boomspiegel
-	weginrichtings-element, type verblindingswering
-	kruinlijn
-	op talud


*) mast typen vervallen, mast blijft in SOR
**) paal typen vervallen, paal blijft in SOR
***) straatmeubilair merendeel van typen vervallen, straatmeubilair blijft in SOR

      

