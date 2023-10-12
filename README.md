# Crossmarx Handprint & Footprint Calculator

Een webapplicatie waarbij kleine ondernemers door middel van een vragenlijst inzicht krijgen over hun ecologische footprint en handprint.

## Inhoudsopgave

* [Beschrijving](https://github.com/Robin1224/nextjs-crossmarx#beschrijving)
* [Kenmerken](https://github.com/Robin1224/nextjs-crossmarx#kenmerken)

## Beschrijving

**User story:**

> Ontwerp een webapplicatie waarmee een relatief klein bedrijf (tot ongeveer 100 man personeel) op een makkelijke, leuke manier geholpen wordt om zijn eigen handprint en footprint inzichtelijk te maken

Deze website is een webapplicatie, waarbij kleine ondernemers een vragenlijst afnemen, en op basis van hun antwoorden een inzicht krijgen over hun ecologische footprint en handprint. De website is gemaakt om er strak en modern uit te zien, en om zo gebruikersvriendelijk mogelijk te zijn. De vragen zijn opgedeeld in 5 categorieën: medewerkers, klanten, leveranciers, omgeving en aandeelhouders.

![image](https://github.com/Robin1224/nextjs-crossmarx/assets/81151231/07758e95-beca-4bc0-b9cc-866e528c3a63)

## Kenmerken

De website is gebouwd in **React**.
Ook is er gebruik gemaakt van de volgende libraries, frameworks en services:
* NextJS
  * Fonts 
  * Vercel
* TailwindCSS
* Typescript
* Firebase
  * _Firestore Realtime Database_
  * _Firebase Authentication_
* RadixUI React
  * _Tabs_
  * _Dialog_
  * _Progress_
* React Icons

<img src="https://github.com/Robin1224/nextjs-crossmarx/assets/81151231/5a51a730-bda8-435e-8041-f0c5f05c7e28" align="right" width="250">

### NextJS

De website is geschreven in React, wat vervolgens NextJS gebruikt als framework voor bijvoorbeeld optimalisatie en routing.  
De website gebruikt de volgende functies van NextJS:
* **Font optimalisatie**  
  _Next Fonts is gebruikt om Google Fonts gemakkelijk lokaal te kunnen hosten. De fonts worden tijdens het build proces gedownload, geoptimaliseerd, en vervolgens lokaal gehost om API calls te verminderen._
* **Routing**  
  _De website gebruikt verwisselende componenten om de verschillende pagina's van iedere tab te tonen, in de toekomst wordt dit vervangen door de Next router._
* **Clientside rendering**  
  _De website gebruikt veel state. Daarom wordt er veel gebruik gemaakt van clienside components in plaats van serverside components. Dit betekent dat de pagina clientside gerenderd wordt._
* **Vercel integratie**  
  _De Vercel integratie van Next is gebruikt om de website gemakkelijk te hosten._

<br clear="right"/>

### TailwindCSS

<img src="https://github.com/Robin1224/nextjs-crossmarx/assets/81151231/c6123634-7c07-4d6a-9fb5-88a28f82b015" align="left" height="100">

Tailwind is gebruikt om de website van styling te voorzien. Dit is gekozen vanwege de sterke integrering met NextJS, en de snelheid waarmee er een design gemaakt kan worden in Tailwind, en de fijne developer experience bij het testen van verschillende styling.

<br clear="left"/>

<img src="https://github.com/Robin1224/nextjs-crossmarx/assets/81151231/460fd343-27e0-4d21-b060-df3c9e7d2ded" align="right" width="500">

### Typescript

Het gehele project is geschreven in Typescript. Er is op gelet dat alle componenten typesafe zijn, en er is ook gelet op type safety bij het gebruiken van third party libraries. Dit maakt het makkelijker om code te debuggen, en zorgt er daarnaast voor dat code editors duidelijkere informatie kunnen geven over functies en variabelen in de code.

<br clear="right"/>
