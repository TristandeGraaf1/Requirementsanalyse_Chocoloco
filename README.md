# Chocoloco Requirements Analyse
# LET OP  h1 afbeelding organogram nog invoegen 
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
1.	Organisatorische context	
2.	Actoren	
3.	Bedrijfsprocesanalyse	
4.	productvisie	
5.	User stories inclusief acceptatiecriteria en inschatting
6.	DoR en DoD	
7.	Een sitemap voor het te ontwikkelen systeem	
8.	Wireframes	



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
![Beschrijving](Afbeelding1.png)
[Foto invoegen]

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
•	Geen centraal platform voor klanten 
•	Trage en inefficiënte klantenservice 
•	Gebrek aan inzicht in klantvoorkeuren 
•	Weinig klantbetrokkenheid 
•	Veel handmatige handelingen

### **SOLL-situatie (gewenste situatie)**
In de gewenste situatie gebruiken klanten één centrale app voor alle interacties. Producten kunnen eenvoudig worden geregistreerd en klanten krijgen direct toegang tot informatie, ondersteuning en persoonlijke aanbevelingen. Klantenservice verloopt grotendeels automatisch via self-service en een chatbot. Data wordt actief gebruikt voor personalisatie en verbetering van processen.

### **GAP-analyse**
Er is een duidelijk verschil tussen de huidige en gewenste situatie. Op dit moment ontbreekt een geïntegreerd systeem, terwijl dit juist nodig is om efficiënter te werken en de klanttevredenheid te verhogen.

### **Belangrijkste verschillen:** 

•	Geen centrale app → wel gewenst 

•	Handmatige processen → geautomatiseerde processen

•	Geen personalisatie → wel personalisatie 

•	Beperkt datagebruik → datagedreven werken

## 4.	Productvisie (Met de product vision board template)

## 5. User stories (inclusief acceptatiecriteria en inschatting)



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

## 8. Wireframes







