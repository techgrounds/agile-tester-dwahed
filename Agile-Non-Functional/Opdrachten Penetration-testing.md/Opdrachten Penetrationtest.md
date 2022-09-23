## Scenario waarbij een pentest kan worden uitgevoerd.

Bij het lanceren of updaten van een nieuw webappelicatie bij een overheidsinstantie of een bank.

Bijna iedere organisatie werkt met gevoelige (persoons-)gegevens en IT-systemen, maar de schade bij een een overheidsinstantie en de banksystemen zal de effect erger zijn. Een pentest op een bedrijfsnetwerk is in dit geval belangrijk, omdat hiermee inzicht kan verkrijgen in het niveau van de beveiliging en daarmee kan er gecontroleerd worden of de gegevens en systemen wel veilig zijn.

Voor sommige organisaties is er bovendien extra belang bij informatieveiligheid. Voor de meeste overheidsopdrachten is een ISO27001 certificering voor informatiebeveiliging vereist, waarvoor de audits op hun beurt een bedrijfsnetwerk pentest verplicht stellen.

Verder is het voor iedere grotere MKB’er, gemeente, ministerie, softwarebedrijf en financiële instelling cruciaal om de veiligheid en beveiliging van hun bedrijfsnetwerk te waarborgen. Een bedrijfsnetwerk pentest helpt dan om die veiligheid te controleren en bij te houden, zodat de bedrijfsvoering geen onnodige risico’s loopt.


# Wat is pentest?

Pentest (ethische hacken) is waarbij een systeem onderzocht wordt op kwetsbaarheden. Ethische hackers proberen
op verschillende manieren zwakke plekken in het systeem te ontdekken en aan het licht brengen. Penetratietest kan je indelen
in 3 delen, namelijk:

- Black box pentratietest
- White box penetratietest
- Gray box penetratietest

Bij uitvoeren van black box pentratietest heeft ethische hacker alleen informatie wat voor iedereen toegangelijk is
zoals de url adres, naam van organisatie etc.

Bij het uitvoeren van white box penetratietest heeft de ethische hacker all info, zoals de Systemen, netwerk, OS,
IP-adres, broncode en schema.

Bij het uitvoeren van gray box penetratietest heeft de ethische hacker gedeeltelijke kennis van de interne structuur
van de applicatie. Het doel van grey box-testen is het zoeken en identificeren van defecten als gevolg van een onjuiste
codestructuur of onjuist gebruik van applicaties.

Pentest heeft 2 methodes, nameijk:

- Manual pentest
- Automated pentest

Manual pentest vereist deskundigheid (expert), verschillende hulpmiddelen en test tot test verschilt.
Automated pentest is sneller, vereist minder hulpmiddelen en kan worden uitgevoerd door minder ervaren tester (ethische hackers).

Het uitvoeren van zo’n de test kan namelijk een waardevolle aanvulling zijn om de mate van de beveiliging te beoordelen en zo
risico’s en kwetsbaarheden te bestrijden. Pentesten resulteren in verbeteringen waarmee een organisatie preventief veiliger
wordt en risico’s worden verkleind. 


# Stappen Pentest:

Penetratietesten is het proces waarbij het netwerk van een organisatie wordt getest om erachter
te komen hoe het beter kan worden verdedigd. Penetratietesten, ook wel pentesten genoemd,  
is een manier waarop ethische hackers werken. Ze denken als echte hackers en vallen IT systemen aan.
Dit helpt bedrijven hun sterke en zwakke punten te begrijpen en hun organisatorische middelen te verbeteren.
Een pentest bestaat uit meerdere fasen. Je kunt niet zomaar in een systeem komen door een tool te gebruiken,
tenzij het doelwit hopeloos kwetsbaar is. In de meeste gevallen worden systemen beveiligd via firewalls,
antivirussoftware, standaardconfiguraties van besturingssystemen, enzovoort. Het vereist de juiste tools,
een sterke set vaardigheden en vooral geduld om een netwerk succesvol te exploiteren. Laten we eens kijken naar de
vijf hoofdfasen die een penetratietester zal doorlopen, samen met de tools die ze gebruiken om in te breken in een netwerk.

1 – Verkenning
Geef me zes uur om een boom om te hakken, de eerste vier zal ik besteden aan het slijpen van de bijl — Abraham Lincoln.
Verkenning is het belangrijkste onderdeel van een penetratietest. Het is waar de informatie over het doelwit wordt verzameld.
Verkenning is belangrijk omdat hoe meer informatie  over het doelwit bekend is, hoe gemakkelijker het wordt om te proberen toegang te krijgen.
Als eenmaal een heel netwerk in kaart is gebracht, wordt er begonnen met de  zwakste plekken te  identificeren en van daaruit beginnen.
Veelgebruikte hulpmiddelen zijn onder meer Google (ja!) En sociale-mediasites waar informatie over het doel kan worden verzameld.
Ook zijn linkedin en vacatures van het bedrijf interessant om te zien welk type technologieën gebruikt worden.


2 – Scannen
Dit is het deel waar contact wordt gelegd met het doelwit. Scannen omvat het verzenden van netwerkpakketten naar het doel en het interpreteren van hun reactie.
Scannen geeft nuttige informatie over het doel, zoals open poorten, IP-adressen, informatie over het besturingssysteem, geïnstalleerde services, enzovoort.
Nmap is de beste scanner om een netwerk te scannen. Het helpt bij het in kaart brengen van het netwerk en biedt gedetailleerde informatie over de doelsystemen.
shellback-nmap
Nmap biedt ook een aantal CLI-opties, waaronder scan-exporten die vervolgens geimporteerd kunnen worden in exploitatietools.
Nessus is een ander scantool, maar het is een commercieel product. Terwijl Nmap informatie geeft over het doelwit,
zal Nessus aangeven hoe het doelwit kan worden exploited door de kwetsbaarheden uit de Common Vulnerabilities and Exposures-database te matchen.


3 – Exploitatie
Dit is het gedeelte waar toegang wordt verschaft tot het systeem. Een succesvolle exploit geeft controle over het systeem op ten minste
een gebruikersniveau. Vervolgens is meestal privilege-escalatie nodig om root-toegang tot het doel te krijgen.
Als het op exploitatie aankomt, is Metasploit zonder twijfel de beste tool op de markt. Het is open-source (met ook een commerciële versie)
en is gemakkelijk om mee te werken. Metasploit wordt regelmatig bijgewerkt met nieuwe exploits die zijn gepubliceerd in de database Common Vulnerabilities and Exposures (CVE).
De scanresultaten kunnen worden gematched met de beschikbare exploits en vervolgens kan een exploit van Metasploit gebruikt worden om het doelwit aan te vallen.
Metasploit heeft een geavanceerde payload genaamd Meterpreter. Zodra toegang is verkregen tot het doelsysteem, geeft Meterpreter opties zoals het openen van webcams,
het dumpen van wachtwoord-hashes, enzovoort. Meterpreter leeft ook in het geheugen van het doel, dus het is erg moeilijk te detecteren.


4 – Toegang behouden
Toegang krijgen tot systemen is niet eenvoudig, vooral niet op bedrijfsnetwerken. Na al het harde werk dat is  verzet om een systeem te exploiteren,
heeft het geen zin om hetzelfde proces te doorlopen om het doel opnieuw te exploiteren.
Dit is waar het behouden van toegang om de hoek komt kijken. Achterdeurtjes, keyloggers en andere stukjes code installeren die toegang geven tot het systeem wanneer je maar wilt.
Metasploit heeft tools zoals keyloggers en Meterpreter-achterdeurtjes om toegang te behouden tot een uitgebuit systeem.
Ook kunnen aangepaste rootkits of trojans geinstalleerd worden nadat er toegang is verkregen.
Een rootkit is een stukje code waarmee de aanvaller beheerderstoegang heeft tot het systeem waarop het is aangesloten.
Rootkits kunnen ook worden geïnstalleerd wanneer bestanden worden gedownload van kwaadwillende websites.
Trojaanse paarden zijn software die eruitziet als nuttige software (bijvoorbeeld Adobe Photoshop), maar die een verborgen stukje schadelijke software kan bevatten.
Dit komt vaak voor bij illegale software waarbij aanvallers trojans insluiten in populaire software zoals MS Office.


5 – Rapporteren
Rapportage is het laatste deel van een penetratietest. Het is wat het onderscheid maakt tussen een aanvaller en een ethische hacker.
Zodra de penetratietest is voltooid, worden alle stappen samengevat die zijn ondernomen, van verkenning tot het verkrijgen van toegang.
Dit zal de organisatie helpen haar beveiligingsarchitectuur te begrijpen en zichzelf beter te verdedigen.
Een rapport geeft management en directie inzicht in cyberrisico’s en op welke onderdelen gestuurd moet worden.
Voor uitvoerend personeel is het een handreiking om gericht aanpassingen in IT door te voeren die het hackers lastiger maakt om binnen te komen of op het netwerk te verspreiden.





### Penetratietest kent 7 fases:

- Fase 1, Informatie verzamelen: het verzamelen van informatie wat beschikbaar is via openbare bronnen en klant.
- Fase 2, Dreigingsmodellering: Gedurende deze fase wordt de informatie georganiseerd en vastgesteld welke informatie relevant is voor de penetratietest.
- Fase 3, Kwetsbaarheidsanalyse:Nadat alle informatie is verzameld wordt in deze fase gezocht naar kwetsbaarheden in systemen en applicaties.
- Fase 4, Uitvoeren: Tijdens de exploitation fase is het doel toegang verkrijgen tot het systeem. De reeds verzamelde informatie wordt gebruikt om op een zorgvuldige wijze aanvallen uit te voeren.
- Fase 5, Na Exploitatie: In deze fase wordt er vastgesteld wat de waarde is van het gecompromitteerde (verdachte) systeem.
- Fase 6, Raporteren: Alle bevindingen zullen worden samengebracht in een compleet en helder uitgewerkt rapport.
- Fase 7, Opnieuw controleren: Op basis van de aanbevelingen kunnen de gevonden kwetsbaarheden door uw eigen organisatie (of externe partij) worden opgelost.
Zodra de kwetsbaarheden zouden moeten zijn opgelost, kan via een re-audit worden onderzocht en gerapporteerd of de kwetsbaarheden daadwerkelijk zijn opgelost.


