# rdsgn

<h3>Inleiding, wat wil je weten?</h3>
De No2ocd app is momenteel niks anders dan een digitale registratie tool, waar alleen tekst na een exposure opdracht kan worden ingevoerd. Uit de interviews kwam naar voren dat een trigger om een opdracht uit te voren erg gewenst is. Vervolgens zijn we na gaan denken wat voor triggers van toepassing kunnen zijn, hieruit kwamen de volgende triggers:
- een trigger gebaseerd op de tijd.
- een trigger gebaseerd op afstand/snelheid
- een trigger gebaseerd op locatie
- een trigger gebaseerd op andere mensen
- een trigger gebaseerd op het weer
- een trigger die vanuit de persoonlijke agenda komt.

Ik wil deze uitdaging in Framer.js uitwerken. Omdat Framer.js webbased is zou het mogelijk zijn om een Geolocation API toe te voegen binnen Framer.js.

<h3>Hoe heb ik onderzoek aangepakt?</h3> 
Ik heb deskresearch gedaan naar de mogelijkheden binnen de techniek van de verschillende triggers en wat de voor- en nadelen kunnen zijn.
<h5>Wat zijn de resultaten</h5>
GPS is de meest relevante optie om een push notificatie te triggeren als een er een exposure opdracht uitgevoerd moet worden. Volgens GPS.gov de officiële overheids website over GPS van de Verenigde Staten is de nauwkeurigheid van GPS 2.169 meter met een uitschieting van 7.8 meter (gps.gov). Een juiste push notificatie moet leuk en relevant zijn die de gebruiker direct naar de juiste pagina binnen de applicatie brengt, zegt  Mark Tack, vice president marketing bij Vibes (mobilemarketeer.com). In het zelfde artikel verteld Kevin Jennings, vice president strategy bij Fuzz Productions dat een push notificatie alleen werkt als er rekening gehouden wordt met frequentie, timing, relevantie, and waarde. Verder verteld Jennings dat consumenten direct het verschil zien tussen een push notificatie die alleen waarde aan de app hecht en niet aan de gebruiker zelf, en ze je niet zullen vergeven. GPS meet ook snelheid en kunnen deze techniek ook gebruiken voor een trigger gebaseerd op afstand/snelheid.

Push notificaties binnen apps zien we vaak terug bij apps met een hoge frequentie van gebruikers. Deze apps maken gebruik van het persuasive principe ‘nudging’ en zijn onderdeel geworden uit het dagelijkse leven van de gebruiker. Utility-apps, financiële services en auto-deel apps leiden in hoeverre het normaal is dat deze apps deel uit maken uit ons leven. Push notificaties en incentives zijn ontzettend effectief binnen deze applicaties. Wij zien dan ook graag terug dat No2ocd deel uit gaat maken uit het dagelijks leven van de patiënt. (andrewchen.co) 

Een trigger vanuit de persoonlijke agenda van de gebruiker is ideaal als de app weet welke exposure opdracht er bij de activiteit hoort. Een voorbeeld kan zijn dat de gebruiker boodschappen moet halen en een notificatie krijgt over de exposure opdracht die op dat moment uitgevoerd moet/kan worden. Vervolgens kunnen we GPS techniek toepassen, wanneer de gebruiker weer thuis is om weer een push notificatie te sturen waarin de gebruiker direct de exposure opdracht kan invullen. Google’s Calendar API stelt ons in staat om activiteiten uit de gebruikers agenda uit te lezen.

<h3>Conclusie: antwoord op wat je wilde weten</h3>
Triggers in de vorm van push notificaties kunnen erg effectief zijn als ze juist worden ontworpen, daarmee doel ik op wanneer de gebruiker verwacht een trigger te ontvangen. Een trigger op basis van GPS is accuraat en helpt de gebruiker als de trigger de juiste, leuke informatie laat zien. Het is belangrijk om de No2ocd-app écht een deel uit het dagelijks leven van de patiënt te maken, omdat notificaties uit apps met een hoge engagement ontzettend effectief blijken te zijn. 

<h3>Technische uitdaging</h3>
Er zijn niet veel recourses te vinden over hoe geolocatie toe te voegen is binnen Framer.js, vandaar dat het denk ik verstandig is om eerst de core werkend te krijgen (JavaScript + HTML), om hem daarna (als de tijd het toelaat) in Framer.js te implenteren.

<h3>Hoofdvraag:</h3>
Hoe kunnen we OCD-patiënten hun proces laten monitoren en ervoor zorgen dat OCD patiënten op de juiste momenten getriggerd worden om hun exposure opdrachten uit te voeren.





