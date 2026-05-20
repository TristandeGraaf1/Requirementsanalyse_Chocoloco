# Chocoloco Requirements Analyse 
![Login](Afbeelding092.png)


#### Groepsnaam
Chocoloco

#### Teamleden
- Tristan de Graaf  
- Brian den Ouden  
- Thijs Wulffraat  
- Lukas van Bekkum  
- Mohamed-Amine Charifi  

#### MMMLabel
Geassisteerd door AI

## Inhoud
1.	[Organisatorische context](https://github.com/TristandeGraaf1/Requirementsanalyse_Chocoloco#1-organisatorische-context)
2.	[Actoren](https://github.com/TristandeGraaf1/Requirementsanalyse_Chocoloco#2-actoren)
3.	[Bedrijfsprocesanalyse](https://github.com/TristandeGraaf1/Requirementsanalyse_Chocoloco#3bedrijfsprocesanalyse)	
4.	[productvisie](https://github.com/TristandeGraaf1/Requirementsanalyse_Chocoloco#4productvisie-met-de-product-vision-board-template)	
5.	[User stories inclusief acceptatiecriteria en inschatting](https://github.com/TristandeGraaf1/Requirementsanalyse_Chocoloco#5-user-stories-inclusief-acceptatiecriteria-en-inschatting)	
6.	[DoR en DoD](https://github.com/TristandeGraaf1/Requirementsanalyse_Chocoloco#6-dor-en-dod)		
7.	[Sitemap](https://github.com/TristandeGraaf1/Requirementsanalyse_Chocoloco#7-sitemap)	
8.	[Wireframes](https://github.com/TristandeGraaf1/Requirementsanalyse_Chocoloco#8-wireframes)	



## 1. Organisatorische context

### Missie  
Chocoloco wil klanten een transparante, persoonlijke, inspirerende en unieke chocoladebeleving bieden.  Waarbij duurzaamheid, kwaliteit en gemak een belangrijke rol spelen. Met smart technologie versterken we de band met onze klanten en creëren we blijvende waarde. 

### Visie
Chocoloco streeft ernaar marktleider te worden met het een robuust digitale platform voor unieke chocoladebeleving, waarin innovatie, duurzaamheid en persoonlijke klantinteractie centraal staan. 

### Strategie
Chocoloco richt zich op Customer Intimacy door het opbouwen van langdurige, persoonlijke klantrelaties via een centrale mobiele app. In deze app wordt klantdata zoals voorkeuren, aankoopgeschiedenis en interacties gebruikt om een volledig gepersonaliseerde dashboard te bieden voor een unieke chocoladebeleving. Daarbij komt dat klanten in de app met de Design service hun eigen producten kunnen samenstellen en eigen verpakkingen kunnen ontwerpen wat het een unieke ervaring maakt. Klanten worden door een medewerker persoonlijk gebeld wanneer hun product bestelde product verzonden wordt of opgehaald kan worden in de  winkel.
Bij Chocoloco staat persoonlijke en exclusieve service centraal. Klanten kunnen eenvoudig ondersteuning krijgen via een live-chat met een medewerker of in een van onze winkels. Met onze exclusieve Chocolate service kunnen klanten een afspraak maken voor een persoonlijk productadvies aan huis of in een van de winkels. Met het loyaliteitsprogramma kunnen klanten sparen voor een gratis product of toegang tot een event. Met het loyaliteitsprogramma bouwen we aan een langdurige klantrelatie. Tevens kan een klant via een meldsysteem klachten en kwaliteitsproblemen melden, waarbij oplossingen meteen en op maat worden aangeboden.
Chocoloco zal de komende jaren blijven innoveren in de persoonlijk en exclusieve services om een sterke klantloyaliteit en langdurige klantrelatie op te behouden. 


### Doelstellingen 
 
1.	Verhogen klanttevredenheid

    Binnen 2 jaar moeten de klanttevredenheidcijfers in NPS (Net promotor Score) met 25 punten zijn toegenomen ten opzichte van het jaar 2024.

  	 KPI: klanttevredenheid meten in NPS

3.	Verhogen van de marge op producten

    Binnen 2 jaar moet de productmarge met 5% verhoogd zijn door de inkoop kosten te optimaliseren en verkoopprijzen te verhogen.

  	 KPI: Product marge per product in procenten

4.	Verhogen van community deelname

    De Chocolate Firm wil binnen 12 maanden 20% meer actieve leden in de community ten opzichte van de lancering.

  	 KPI: Aantal actieve gebruikers in de community


### Organogram
![Organogram van de organisatie](Afbeelding1.png)

Afbeelding 1: Organogram van de organisatie
### Stakeholder analyse 

#### Identificatie 
-	Consumenten (B2C-klanten): Eindgebruikers van de app.

-	B2B-klanten: Zakelijke afnemers die via de app aanvullende informatie ontvangen.

-	Klantenservicemedewerkers: Medewerkers die de livechat afhandelen en klachten verwerken.

-	Marketing- en salesafdeling: Stelt gepersonaliseerde aanbiedingen op.

-	Ontwikkelteam: Verantwoordelijk voor de bouw en onderhoud van de applicatie.

-	Raad van Commissarissen: Opdrachtgever.

-	Leveranciers / cacaoboeren: Data van hun goederen wordt gebruikt in de app. 
-	AVG-autoriteiten: Stellen wettelijke eisen aan privacybescherming en databeheer.

-	Cybercriminelen: Uit op persoonsgegevens, betaaldata en/ of bedrijfsinformatie.

#### Prioritering 

| Direct                         | Kwaadwillend     | Indirect                    |
|--------------------------------|------------------|-----------------------------|
| Consumenten (B2C)              | Cybercriminelen  | Leveranciers / cacaoboeren  |
| B2B-klanten                    |                  | AVG-autoriteiten            |
| Klantenservicemedewerkers      |                  |                             |
| Marketing- en salesafdeling    |                  |                             |
| Ontwikkelteam                  |                  |                             |
| Raad van Commissarissen        |                  |                             |



#### Belangen

| Stakeholder                    | Impact | Voordelen                                                                 | Nadelen                                                                                                   |
|--------------------------------|--------|---------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|
| Consumenten (B2C)              | Hoog   | Snelle toegang tot de shop, informatie en gepersonaliseerde aanbiedingen. | Risico op datalek.                                                                                         |
| B2B-klanten                    | Hoog   | Inzichten in leveringen en extra informatie.                              | Verandering, training in gerbruik van app.                                                                 |
| Klantenservicemedewerkers      | Midden | Minder personeel nodig door ai bot, klanten beter kunnen helpen door crm systeem. | Training crm. Werkdruk kan erg verhogen als de bot niet voldoet aan iedereen zijn vragen.                |
| Marketing- en salesafdeling    | Midden | Data van aankoopgedrag.                                                   | AVG naleving komt in het nauw.                                                                             |
| Ontwikkelteam                  | Midden | Nieuw mooi systeem, mogelijk ook voor andere bedrijven interessant.       | Veel onderhoud eerste jaar.                                                                                |
| Raad van Commissarissen        | Hoog   | Meer omzet door klantloyaliteit.                                          | Grote investering, risicovol.                                                                              |
| Leveranciers/ cacaoboeren      | Laag   | Zichtbaarheid herkomst producten, spoort aan om "groen” te farmen.        | Naamsbekendheid als een product mislukt aankomt bij een klant.                                             |
| AVG-autoriteiten               | Hoog   | Stimuleerd het goed omgaan van data.                                      | Kans op boetes of app opschorsing bij niet naleven AVG.                                                    |
| Cybercriminelen                | Hoog   | Veilige app door veel pentesten en goed beveiligde data.                  | Proberen persoonsgevens en bedrijfsgegevens te verkrijgen via de app.                                      |


## 2. Actoren
Binnen de mobiele applicatie van de Chocoloco zijn er verschillende actoren die elk een eigen rol hebben:

•	**Functie:** Klant (B2C)  
**Rol:** gebruiker  
**Omschrijving:** Gebruikt de app om producten te registreren, informatie te bekijken, bestellingen te plaatsen, klachten in te dienen en deel te nemen aan de community.  

•	**Functie:** B2B-klant  
**Rol:** gebruiker  
**Omschrijving:** Zakelijke klant die naast de standaard functionaliteiten ook gebruikmaakt van extra opties zoals inzicht in voorraad, levertijden en grotere bestellingen.  

•	**Functie:** Klantenservicemedewerker  
**Rol:** gebruiker  
**Omschrijving:** Behandelt vragen en klachten van klanten, beheert meldingen en communiceert met klanten via de app.  

•	**Functie:** Marketingmedewerker  
**Rol:** gebruiker  
Beheert promoties, aanbiedingen en content zoals nieuwe producten, recepten en campagnes binnen de app.  

•	**Functie:** Admin  
**Rol:** beheerder  
**Omschrijving:** Verantwoordelijk voor het technisch beheer van de applicatie, gebruikersbeheer en het monitoren van prestaties en beveiliging.  

•	**Functie:** Systeemactor  
**Rol:** AI-chatbot  
**Omschrijving:** Ondersteunt klanten 24/7 door automatisch vragen te beantwoorden en eenvoudige problemen op te lossen.

## 3.	Bedrijfsprocesanalyse 

### **IST-situatie** (huidige situatie)
Momenteel verloopt het contact met klanten via verschillende losse kanalen zoals de website, e-mail en telefoon. Productinformatie staat verspreid en klanten moeten zelf zoeken naar antwoorden. Klachten en vragen worden handmatig verwerkt, wat tijd kost en foutgevoelig is. Er is weinig tot geen personalisatie en klantdata wordt beperkt gebruikt.

### **Knelpunten**
- Geen centraal platform voor klanten 
- Trage en inefficiënte klantenservice 
- Gebrek aan inzicht in klantvoorkeuren 
- Weinig klantbetrokkenheid 
- Veel handmatige handelingen

### **SOLL-situatie (gewenste situatie)**
In de gewenste situatie gebruiken klanten één centrale app voor alle interacties. Producten kunnen eenvoudig worden geregistreerd en klanten krijgen direct toegang tot informatie, ondersteuning en persoonlijke aanbevelingen. Klantenservice verloopt grotendeels automatisch via self-service en een chatbot. Data wordt actief gebruikt voor personalisatie en verbetering van processen.

### **GAP-analyse**
Er is een duidelijk verschil tussen de huidige en gewenste situatie. Op dit moment ontbreekt een geïntegreerd systeem, terwijl dit juist nodig is om efficiënter te werken en de klanttevredenheid te verhogen.

### **Belangrijkste verschillen:** 

- Geen centrale app → wel gewenst 

- Handmatige processen → geautomatiseerde processen

- Geen personalisatie → wel personalisatie 

- Beperkt datagebruik → datagedreven werken

## 4.	Productvisie (Met de product vision board template)

**Vision**

Chocoloco wil een innovatieve mobiele applicatie ontwikkelen die klanten een gepersonaliseerde en duurzame chocoladebeleving biedt. Door middel van deze applicatie word de relatie met de klant versterkt, dit komt door de slimme technologie hierdoor word klantloyaliteit vergroot.

**Target Group**

Consumenten (B2C) die chocolade kopen en van wie hun interesse ligt bij kwaliteit en duurzame chocolade
Zakelijke klanten (B2B) zoals supermarkten en speciaalzaken

**Needs**

-	Inzicht in producten ( bijvoorbeeld herkomst)
-	Gepersonaliseerde aanbiedingen.
-	Snelle en makkelijke klantenservice
-	Makkelijk bestellen en productregistratie
-	Betrokkenheid via community
-	Vragen stellen via chatbot/live chat
-	Suggesties en feedback geven
-	Offertes vragen
-	
**Product**
 	
Een mobiele applicatie die kan worden gebruikt via zowel IOS als Android met als kernfunconaliteiten:
-	Product registratie via QR-CODE en Dashboard
-	AI-Chatbot en klantenservice
-	Persoonlijke aanbevelingen op basis van klantdata
-	Bestelfunctie gekoppeld aan ons ERP-systeem
-	Community ( denk aan reviews) 
-	Winkelzoeker via geolocatie


**Business goals ( Voor het bedrijf zelf )**

•	Verhogen van klanttevredenheid en klantloyaliteit door een persoonlijke gebruikerservaring 
•	Versterken van customer intimacy door langdurige klantrelaties op te bouwen via gepersonaliseerde interacties, aanbevelingen en ondersteuning 
•	Omzet verhogen door gepersonaliseerde aanbiedingen en productaanbevelingen 
•	Verlagen van servicekosten door self-service via de AI-chatbot 
•	Verkrijgen van betere inzichten in klantgedrag via BI-data 
•	Ondersteunen en versterken van duurzaamheidsdoelen

**Competitors**

-	Chocolademerken zonder een app zoals die van ons
-	Webshops zonder klantdata-integratie 
-	Apps met beperkte functionaliteit

**Revenue Streams**

-	Verkoop via de app uit de casus “producten direct via de app bestellen”
-	Premium producten en seizoens pakketten 
-	Cross-selling
-	Loyaliteitsprogramma’s
-	Exclusieve limited editions


**Cost Factors**

-	Ontwikkeling van de app. Om deze app te ontwikkelen zullen er kosten gemaakt moeten worden
-	Koppeling met systemen (ERP, CRM, BI)
-	Onderhoud en updates
-	Marketing speelt ook een rol
-	En als laatste de klantenservice
  
**Channels**

-	Mobiele App
-	Pushnotificaties kunnen ook krachtig zijn
-	Bestellen via de app
-	CRM ( Klantdata)
-	E-Mail marketing kan bijvoorbeeld helpen.

**Vision board**

![Login](Visionboard.png)


## 5. User stories (inclusief acceptatiecriteria en inschatting)

**1. Product registreren**

Als klant wil ik een chocoladeproduct kunnen scannen met een QR-code, zodat ik productinformatie kan bekijken.  

Acceptatiecriteria:
- QR-code kan gescand worden via camera  
- Product word dan toegevoegd in het dashboard  
- Product info word gegeven.  

Inschatting: M  


**2. Dashboard bekijken**

Als klant wil ik een overzicht zien van mijn geregistreerde producten zodat ik inzicht heb in mijn aankopen.  

Acceptatiecriteria:
- Producten worden weergegeven  
- Product details aanklikbaar  

Inschatting: M  


**3. AI-Chatbot**

Als klant wil ik de AI chatbot gebruiken om vragen te stellen, zodat mijn vragen snel beantwoord kunnen worden.  

Acceptatiecriteria:
- Doorverwijzing naar medewerker mogelijk  
- Snelle reactie vereist  
- Geen nutteloze antwoorden  

Inschatting: L  


**4. Klachten**

Als klant wil een klacht kunnen indienen, zodat mijn probleem wordt opgelost.  

Acceptatiecriteria:
- Klantformulier beschikbaar  
- Foto upload mogelijk  
- Status van de klacht is zichtbaar  


**5. Product bestellen**

Als klant wil ik chocoladeproducten kunnen bestellen via de app, zodat ik eenvoudig nieuwe producten kan kopen.  

Acceptatiecriteria:
- Producten zijn zichtbaar  
- Bestelknop werkt  
- Koppeling met ERP werkt correct  

Inschatting: L  


**6. Aanbevelingen**

Als klant wil ik gepersonaliseerde aanbevelingen ontvangen zodat ik producten ontdek die bij mij passen.  

Acceptatiecriteria:
- Aanbevelingen gebaseerd op eerdere aankopen  
- Relevante producten worden getoond  
- Updates bij nieuwe producten  

Inschatting: L  


**7. Product notificaties**

Als klant wil ik notificaties ontvangen wanneer een product bijna over datum is, zodat ik producten op tijd kan gebruiken.  

Acceptatiecriteria:
- De app stuurt automatisch een melding  
- De melding toont productnaam en datum  
- Gebruiker kan meldingen aan/uit zetten  

Inschatting: M  


**8. Favoriete smaken**

Als klant wil ik favoriete smaken kunnen opslaan, zodat ik sneller producten terug kan vinden.  

Acceptatiecriteria:
- Gebruiker kan producten als favoriet markeren  
- Favorieten zijn zichtbaar in profiel  
- Favorieten blijven opgeslagen na uitloggen  

Inschatting: S  


**9. Herinneringen**
    
Als gebruiker wil ik herinneringen ontvangen voor workshops en events, zodat ik deze niet vergeet.  

Acceptatiecriteria:
- Gebruiker ontvangt een pushnotificatie  
- Tijd en locatie worden weergegeven  
- Herinneringen kunnen uitgezet worden  

Inschatting: M  


**10. Volgen van klachten**

Als klant wil ik de status van mijn klacht kunnen volgen, zodat ik weet wanneer deze wordt opgelost.  

Acceptatiecriteria:
- Gebruiker ziet huidige status  
- Updates worden automatisch weergegeven  
- Gebruiker ontvangt notificaties bij wijzigingen  

Inschatting: L  


**11. Donker en lichte modus**

Als gebruiker wil ik kunnen kiezen tussen lichte en donkere modus, zodat de app prettig te gebruiken is.  

Acceptatiecriteria:
- Gebruiker kan thema aanpassen  
- Instelling wordt opgeslagen  
- Interface verandert direct  

Inschatting: S  


12. Recepten zoeken
    
**Als gebruiker wil ik recepten kunnen zoeken op smaak of ingrediënt, zodat ik sneller passende recepten kan vinden.** 

Acceptatiecriteria:
- Zoekfunctie werkt op naam en ingrediënt  
- Resultaten worden direct weergegeven  
- Gebruiker kan recepten openen  

**Inschatting:** M













































## 6. DoR en DoD 

### Definition of Ready (DoR)
Binnen ChocoLoco wordt de Definition of Ready gebruikt om te bepalen wanneer een user story klaar is om ontwikkeld te worden. Dit voorkomt onduidelijkheid en zorgt ervoor dat het ontwikkelteam efficiënt kan werken.

Een user story is “ready” wanneer aan de volgende voorwaarden is voldaan:

- De user story is duidelijk geformuleerd volgens het format: Als [gebruiker] wil ik [functionaliteit] zodat [doel]  
- De acceptatiecriteria zijn concreet en testbaar beschreven  
- De scope van de user story is duidelijk en niet te groot (bijv. één functionaliteit zoals QR-scannen of dashboardweergave)  
- De benodigde systemen en koppelingen zijn bekend (zoals ERP, CRM of BI) 
- Eventuele afhankelijkheden (bijv. productdata of klantgegevens) zijn inzichtelijk 
- De prioriteit van de user story is vastgesteld  
- Het ontwikkelteam begrijpt de user story volledig
- De user story is inschatbaar (bijv. S, M of L) 

Door deze criteria toe te passen, wordt voorkomen dat er gestart wordt met onduidelijke of incomplete user stories.


### Definition of Done (DoD)
De Definition of Done beschrijft wanneer een user story volledig is afgerond en opgeleverd kan worden. Binnen ChocoLoco wordt hiermee de kwaliteit van het systeem gewaarborgd.

Een user story is “done” wanneer aan de volgende voorwaarden is voldaan:

- Alle acceptatiecriteria zijn behaald 
- De functionaliteit werkt correct binnen de mobiele applicatie (bijv. QR-scan, dashboard, chatbot, bestelproces) 
- De functionaliteit is getest en bevat geen kritieke fouten of bugs 
- Koppelingen met andere systemen (ERP, CRM, BI) functioneren correct 
- De gebruiker kan de functionaliteit succesvol gebruiken (gebruiksvriendelijkheid is gecontroleerd) 
- Eventuele data wordt correct weergegeven (bijv. productinformatie, klantgegevens, aanbevelingen) 
- De code en documentatie zijn bijgewerkt 
- De user story is gevalideerd en goedgekeurd door de product owner of opdrachtgever
  
Door het hanteren van de Definition of Done wordt gegarandeerd dat elke opgeleverde functionaliteit voldoet aan de gestelde eisen en direct waarde levert voor de gebruiker.





## 7. Sitemap
![Sitemap](sitemap1.svg)

Afbeelding 3: Sitemap van de app


## 8. Wireframes
Login pagina:


![Login](Login.png)

2FA: 


![Login](2FA.png)


Account registeren:


![Login](accountmaken.png)


Eerste product registeren:


![Login](Registeer1product.png)


Dashboard:


![Login](Dashboard.png)


Klantenservice pagina:


![Login](Klantenservice.png)


Terugbel functie: 


![Login](Terugbellen.png)


Klacht indienen:



![Login](Klachtindienen.png)


AI-chatbot:


![Login](AI_bot.png)


Status van de klacht:


![Login](status.png)


FAQ:


![Login](FAQ.png)


Live-chat:


![Login](Livechat.png)


Loyaliteitsprogramma: Choco rewards

Om op deze pagina te komen moet de gebruiker via het dashboard op de knop "Chocorewards" drukken. Dit is de extra functionaliteit van Chocoloco.

![Login](Chocorewards.png)


Producten: 

Om op deze pagina te komen moet de gebruiker via het dashboard op de knop "Producten" drukken.

![Login](Producten.png)


Mijn producten: 

Om op deze pagina te komen moet de gebruiker via de productpagina op de knop "Mijn producten drukken" drukken.

![Login](Mijnproducten.png)


Product registreren: 

Om op deze pagina te komen moet de gebruiker via de productpagina op de knop "Product registeren" drukken.

![Login](Productregisteren02.png)


Product Details: 

Om op deze pagina te komen moet de gebruiker via de "Mijnproduct" pagina op een bepaald geregistreed product drukken.

![Login](Productdetails.png)


Ontdekken: 

Om op deze pagina te komen moet de gebruiker via het dashboard op de knop "Ontdekken" drukken.

![Login](Ontdekken.png)


Zoeken: 

Om op deze pagina te komen moet de gebruiker via de pagina ontdekken op de knop "Zoekfunctie" drukken.

![Login](Zoeken.png)


Recepten: 

Om op deze pagina te komen moet de gebruiker via de pagina ontdekken op de knop "Recepten" drukken.

![Login](Recepten.png)


Community: 

Om op deze pagina te komen moet de gebruiker via het dashboard  op de knop "Community" drukken.

![Login](Community.png)


Community forum: 

Om op deze pagina te komen moet de gebruiker via de community  op de knop "Forum" drukken.

![Login](Forumpost.png)


Community forum post: 

Om op deze pagina te komen moet de gebruiker via de community forum  op de knop "Nieuwe post maken" drukken.

![Login](Berichtplaatsen.png)


Shop 

Om op deze pagina te komen moet de gebruiker via het dashboard op de knop "Shop" drukken.

![Login](shop.png)


Productcatalogus 

Om op deze pagina te komen moet de gebruiker via de shop op de knop "productcatalogus" drukken.

![Login](productcatalogus.png)


Bestellen 

Om op deze pagina te komen moet de gebruiker via de shop op de knop "bestellen" drukken.

![Login](bestellen.png)


































