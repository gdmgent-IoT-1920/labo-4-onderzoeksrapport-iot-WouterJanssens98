# IOT: onderzoeksrapport RFID & RFID Tags

![RFID](https://www.reisartikelen.nl/media//blog/262645ec692a980080f911d8a6cc6aac.png "RFID picture")

RFID staat voor ‘radio-frequency identification’. Het is een techniek waarmee data opgeslagen wordt op een sticker (een RFID-tag of -label), of beter gezegd een minuscule chip. Via radiogolven leest een elektromagnetische lezer de gegevens op de chip af. Zo’n RFID-tag is minuscuul; hij kan zonder problemen verwerkt worden in allerlei objecten (van bankkaarten tot voedingsmiddelen), maar dient bijvoorbeeld ook om huisdieren en zelfs personen te ‘taggen’.


## Ontstaan van de RFID-technologie

Hoewel RFID de laatste jaren sterk gegroeid is, begint het verhaal in de helft van de 20ste
eeuw. Het principe van identificatie door middel van radiosignalen gaat terug tot de Tweede Wereldoorlog. Toen werden vliegtuigen voor het eerst voorzien van radiobakens, zodat vliegtuigen als vriend of vijand konden worden geïdentificeerd. De uitvinding van deze technologie wordt in het algemeen geassocieerd met het ontwerp van het IFF-systeem3 van de Royal Air Force waarmee de vliegtuigen van de
geallieerden tijdens de Tweede Wereldoorlog geïdentificeerd konden worden. Het is onmogelijk om de creatie van RFID toe te schrijven aan een enkele persoon, maar het is wel duidelijk dat Charles A. Walton een grote bijdrage leverde met de publicatie van verschillende octrooien, in het bijzonder het octrooi dat geregistreerd werd in 1973 voor een passieve transponder.


RFID, zoals het in zijn huidige vorm wordt toegepast, stamt uit de jaren zestig. Twee medewerkers van Philips ontdekten toen hoe chips op afstand konden worden uitgelezen. Het bedrijf ID Engineering ontwikkelde daaruit toepassingen op het gebied van diefstalpreventie. C&A was het eerste bedrijf in Europa dat detectiepoortjes inzette en aan de winkelwaren een RF-etiket bevestigde. De toevoeging van een unieke Electronic Product Code (EPC) en een beheerssysteem leidde tot de structuur die nu RFID heet. Hierna volgden legio toepassingen zoals diefstalpreventie, voorraadbeheer en toegangsdetectie.

De prijs, die de voorbije jaren gedaald is, bevorderde de interesse. Ook de toegenomen mogelijkheden en dalende energiebehoeften van de chips lag mee aan de oorsprong van het recente succes. Een andere stimulans is het verplichte gebruik: verschillende internationale bedrijven en organisaties, zoals Wal-Mart en het Amerikaanse ministerie van defensie, legden hun leveranciers deadlines op voor het gebruik van RFID. Hierdoor kwam de verspreiding in een stroomversnelling terecht. Tenslotte werd er ook werk gemaakt van de standaarden. Tot voor kort waren de RFID systemen merkafhankelijk, wat voor de nodige problemen zorgde. De voorbije jaren werden een aantal standaarden voorgesteld, die langzaamaan door de verschillende producenten aanvaard en gebruikt worden.

## Werking van de RFID-technologie

Bij RFID vindt de communicatie plaatst tussen de RFID Tag en de transceiver (lezer / ondervrager). De transceiver leest de chip uit welke verbonden is met een antenne. Zo’n chip noemen we ook wel een transponder ofwel “het integrated circuit”. Deze chip bevat de unieke (beveiligings)code ofwel de Electronic Product Code (EPC).

![RFID](https://jarnobaselier.nl/wp-content/uploads/2018/01/rfid2.jpg "RFID picture")

Voor een goede werking is het zaak dat zowel de transceiver als de RFID tag op dezelfde frequentie opereren.
De tranceiver zend een radiosignaal via een bepaalde frequentie uit welke door de antenne in de RFID tag ontvangen wordt. Het elektromagnetische veld zorgt ervoor dat de chip geactiveerd wordt en via zijn kleine antenne data retour stuurt naar de tranceiver. De chip in de RFID tag wordt voorzien van stroom via de antenne. De antenne verzameld energie en stuurt deze door naar de chip. Hoe groter de antenne des te verder het leesbereik is. Dit komt omdat een grotere antenne gebruik kan maken van een lagere frequentie. En over het algemeen geldt de regel “hoe lager de frequentie des te verder het leesbereik”. Daarnaast hebben RFID tags met hogere frequenties meer last van vocht en blokkerende metalen.


### Werking van de EPC (Electronic Product Code)

De Electronic Product Code in de chip is meestal een 96-bits datastring. De eerste 8 bits van deze string vormen de header. In de header staat omschreven welk protocol er gebruikt wordt. De volgende 28-bits identificeren de organisatie welke de data op de tag beheerd. De organisatie is gekoppeld aan een ID nummer uitgegeven door de GS1. Dit nummer staat in deze 28-bits. De volgende 24-bits vormen de “object-class”. De “object-class” identificeert het type product. De laatste 38-bits vormen dan het unieke nummer voor tag. In grafische weergave ziet er dit als volgt uit:

![EPC](https://jarnobaselier.nl/wp-content/uploads/2018/01/rfid1.jpg "EPC picture")


## Soorten RFID Tags

#### Hoe werkt een RFID Tag?

Elke RFID-tag bevat een unieke code waarmee het object of de persoon die de tag meevoert gevolgd kan worden. Die mogelijkheid kan echter ook negatief worden aangewend door misbruik of fraude door kwaadwillenden. Het vervalsen van de code is echter nagenoeg onmogelijk in tegenstelling tot bijvoorbeeld een streepjescode. Ook spelen weersinvloeden, vuil of beschadigingen geen of een veel mindere rol dan bij streepjescodes.

####  Actieve tags 

Het RFID-systeem gaat uit van een chip die in een tag is verwerkt. Tags zijn er in allerlei vormen en afmetingen en kunnen alleen lezen of zowel lezen als schrijven. Er bestaan tags die actief zijn maar ook modellen die passief zijn. Een actieve tag heeft een batterij voor de noodzakelijke stroomvoorziening voor het zenden en ontvangen van radiogolven. De tag zendt voortdurend signalen uit met een bepaald interval van een aantal seconden. Die signalen kunnen afstanden van honderd meter tot soms wel enkele kilometers overbruggen.

####  Semi-actieve en passieve tags

Semi-actieve tags zenden alleen als antwoord op een ontvangen signaal. Passieve tags hebben geen batterij en werken via het elektromagnetische veld van de lezer. Op die manier kunnen geen grote afstanden worden overbrugd maar slechts enkele centimeters tot maximaal vijf meter. Het bereik hangt mede af van de gebruikte frequentie waarbij hoge frequenties een groter bereik hebben. Veel gebruikte frequenties zijn:
- Low Frequency 125 kHz
- High Frequency 13,56 MHz
- Ultra High Frequency 860 tot 950 MHz
- Microwave 2,45 GHz

####  Chiploze tags

Naast actieve en passieve tags bestaan er ook chiploze RFID-tags. Deze worden vooral toegepast voor diefstalpreventie. Eigenlijk zijn dit geen RFID-tags omdat ze geen ID (uniek identificatienummer) bevatten. Als de zogenaamde LC-kring bij de kassa niet is doorgebrand tijdens het afrekenen gaat een alarm af zodra de chiploze tag door een elektromagnetische puls van een detectiepoortje wordt herkend.


## Prijsontwikkeling

De implementatie van de technologie is alleen duur wanneer RFID weinig toegevoegde waarde biedt. Daarnaast vergt het uiteraard gewoon een investering die te verantwoorden moet zijn. Bij een actief systeem zijn de RF-readers vaak goedkoper en de tags duurder. Bij een passief systeem is dit precies andersom. Een reader voor passieve tags kost tweehonderd euro, voor een actieve tag begint de prijs ongeveer bij tien euro.

De hoeveelheid data die een tag kan bevatten kan heel verschillend zijn en is ook mede prijsbepalend. Daardoor kan de prijs van een tag variëren van enkele tientallen eurocenten tot wel honderd euro. Er kan echter verwacht worden dat de prijzen de komende tijd dalen door steeds veelvuldiger toepassing. Een nieuwe mogelijkheid om tags te produceren is door middel van printen waarbij een metaalzoutoplossing van koper of zilver wordt geprint. Die wijze van produceren kan de prijs ook gunstig beïnvloeden.Een passieve tag kost (per duizenden) dertig eurocent en in het geval er miljoenen worden besteld is de prijs inmiddels gedaald tot ongeveer tien tot vijftien cent. De prijs van een actieve tag kan oplopen tot honderd euro per stuk.

RFID vergt een investering, maar het levert door middel van een betere traceability ook kostenbesparingen op. Een beter overzicht op de voorraad door RFID leidt tot een vermindering van de veiligheidsvoorraad en daardoor ook van het werkkapitaal dat nodig is om deze voorraad te handhaven. Daarnaast is met behulp van RF-tags op RTI’s als rolcontainers en pallets mogelijk om het beheer en het volgen ervan te verbeteren. Verlies en diefstal zijn te beperken en de inzetbaarheid van RTI’s vergroot. Daarnaast biedt de verhoogde efficiëntie de kans op een kleinere pool aan bijvoorbeeld rolcontainers.

## Toepassingen

RFID-tags hebben reeds zeer veel toepassingen maar verwacht kan worden dat dit aantal de komende jaren nog sterk zal toenemen. Mogelijke toepassingen zijn:
- **Autosleutels**    

- **Autotechnieken**

- **Bankpas**

- **Bescherming van personen**

- **Betalingen verrichten**

- **Bibliotheekboeken**

- **Identificatie van producten**

 En nog veel meer...

## Sterktes van de technologie

- Een RFID-tag kan veel meer informatie bevatten dan een streepjescode.
 
- Een RFID-tag hoeft niet zichtbaar te zijn; als het magnetisch veld van het leesapparaat het label maar weet te bereiken.

- Het uitlezen van een RFID-tag is ongevoelig voor stof en vuil.

- Een RFID-tag kan zodanig worden aangebracht dat deze niet snel beschadigd raakt, bijvoorbeeld door deze in de wand van een plastic krat te plaatsen. Een RFID-chip kan herprogrammeerbaar zijn, waardoor de informatie tijdens het uitlezen kan worden gewijzigd of aangevuld.

- Een RFID-tag kan van extra functies worden voorzien: bijvoorbeeld encryptie (alleen uit te lezen met bepaalde sleutel), sensoren (bijvoorbeeld voor temperatuur). Dit kan overigens alleen vooraf, tijdens de productie van de tag.

## Zwaktes van de technologie

- Met passieve tags is de uitleesafstand maximaal circa één meter; hoe kleiner de tag, hoe kleiner de uitleesafstand. Bij (duurdere) actieve tags kan die afstand oplopen tot ± acht meter.

- Een ‘metalen’ omgeving leent zich minder voor toepassing van RFID-tags, omdat metaal het magnetisch veld afschermt. Speciale tags zijn nog wel op of in de wand van een metalen voorwerp aan te brengen, maar nooit achter een metalen wand.

- De techniek is fraudegevoelig. Detectie van labels kan betrekkelijk eenvoudig worden verhinderd. Een tag is zonder veel moeite magnetisch af te schermen of zodanig te beschadigen (voor wie weet waar die zit) dat deze niet meer functioneert.

- Soms wordt het voorgesteld alsof in een supermarkt een kar met boodschappen in één keer kan worden gescand door deze door een poortje te rijden. Maar een (duur) voorwerp verborgen tussen blikken soep is niet gemakkelijk te detecteren.

- Gebrek aan goede standaardisatie. De toegelaten frequentiebanden en bijbehorende zendvermogens vertonen wereldwijd belangrijke verschillen. Bovendien heeft iedere RFID-fabrikant veel geïnvesteerd in de ontwikkeling van zijn eigen manier van informatie-overdracht tussen label en leesapparaat. Beide werken belemmerend op een goede en snelle standaardisatie en daarmee op een snelle en brede toepassing van RFID.

## Gevaren voor de RFID-technologie

Naast RFID bestaan er ook andere technieken: automatische identificatietechnieken, zoals streepjescode, dotcode en cameratechnieken (in sommige toepassingen).

De kost:  een RFID-tag is tien à twintig keer duurder dan een streepjescode. Zo’n tag kost een paar (euro)kwartjes. Een kale leesmodule (voor inbouw in een ander apparaat) kost ±100 euro, een compleet uitleesapparaat komt op 500 – 1000 euro. De prijs van een compleet RFID-systeem, bestaande uit tags en leesapparaten, hangt sterk af van de toepassing. Hoeveel tags zijn nodig, hoeveel lezers?

Op gebied van privacy: doordat er steeds meer gegevens over producten worden vastgelegd, en door koppeling met het betaalen koopgedrag van consumenten, wordt er steeds meer over individuele consumenten bekend. Hoewel de gevaren hiervan door wetgeving en technologie in belangrijke mate kunnen worden weggenomen, bestaat er een minstens zo groot gevaar dat er – deels door onbegrip – een negatieve sfeer onder het publiek ontstaat rond het toepassen van RFID.


## Toekomst van RFID in de Industrie 4.0

In het verleden beperkte de functionaliteit van RFID-systemen zich tot datadragers. Wat een grote doorbraak van de technologie in de weg stond, was de hoge kostprijs voor deze relatief eenvoudige taak. Toepassingen concentreerden zich veelal rond producten met een hoge toegevoegde waarde die de kostprijs konden rechtvaardigen. Er was zekerheid dat de fabrikant zijn waardevolle producten bij de klant kreeg, met desgewenst een perfecte traceerbaarheid. Met de intrede van Industrie 4.0 kunnen ze er echter een nieuw, uitgebreider takenpakket opnemen binnen de fabrieksmuren zelf. Data moet nu in elke fase van het productieproces ontgonnen worden en drijft de volledige productie aan om tot een fabriek van de toekomst te komen. RFID-technologie maakt in deze context het volgende niveau in automatisering mogelijk. Op de tags kan immers een schat aan informatie bewaard worden die de machines nodig hebben om te weten welke bewerkingsstap er nodig is voor het werkstuk in kwestie. Dat de technologie bovendien een stukje krachtiger (meer geheugen voor meer dataopslag) en goedkoper (grotere productieaantallen) geworden, doet zijn intrede in de fabriek van de toekomst nog versnellen.

In de toekomst zullen RFID-tags flinterdun moeten zijn en nog een stuk compacter dan vandaag al het geval is.


![RFID](https://www.ia-online.be/wp-content/uploads/2019/02/1434996103975.jpg "RFID picture")

Wel zijn er nog twee belangrijke uitdagingen vooraleer dit werkelijkheid wordt. Allereerst is er nood aan een uniforme radiostandaard doorheen de industrie en doorheen de wereld. Dit zal een verdere doorbraak van RFID alleen maar in de hand werken. Daarnaast wordt er nog gewerkt aan nieuwe manieren om de tags van energie te voorzien. In de toekomst zullen ze immers flinterdun moeten zijn en nog een stuk compacter dan vandaag al het geval is. Dan zal de huidige voedingstechnologie tekort schieten. Momenteel wordt er gekeken of er energie via radiofrequentievelden kan opgewekt worden voor de tags door middel van elektromagnetische veldsynthese. Zo kan de tag eigenlijk gevoed worden terwijl hij door de fabriek beweegt.  




## Bronnen

[Wikipedia - Radio Frequency Identification](https://nl.wikipedia.org/wiki/Radio-frequency_identification)

[Neopost - Wat is RFID](https://www.neopost.be/nl/blog/wat-is-rfid)

[Smalsresearch - RFID](https://www.smalsresearch.be/)

[Wetenschap Info Nu - RFID Chip & de vele toepassingen](https://wetenschap.infonu.nl/techniek/150384-rfid-chip-en-de-vele-toepassingen.html)

[Technisch Weekblad - Sterkte en Zwakte van RFID](https://www.technischweekblad.nl/nieuws/sterkte-en-zwakte-van-rfid)

[Jarno Baselier - RFID](https://jarnobaselier.nl/radio-frequency-identification-rfid/)

[IA Online - RFID als de ogen en oren industrie 4.0 systemen](https://www.ia-online.be/artikel/rfid-als-de-ogen-en-oren-van-industrie-4-0-systemen/)

[Scriptiebank - Studie over RFID](https://www.scriptiebank.be/scriptie/2005/rfid-studie-van-de-technologie-mogelijkheden-en-problemen-gericht-op-eventuele)

[Logistiek - Is het gebruik van RFID duur?](https://www.logistiek.nl/warehousing/artikel/2005/12/is-gebruik-van-rfid-duur-10123899?_ga=2.254236616.1934953932.1585409839-1323663922.1585409839)
