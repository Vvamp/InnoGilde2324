

# Presentatie 1
## Cover slide
- Korte introductie over presentatie.
- 

## Agenda Slide
- Kort vertellen wat we gaan doen

## Project Informatie Slide 
- Korte uitleg context project. 
- - Opdrachtgever: Hugo / HU
- - Klant: Mensen met Fairphones


## Probleemstelling
- Diepgang over project. 
- - Doel: android apps zonder google services.
- - Prio: werkende mobiele data, zodat het een functionele telefoon is

## Mijn Taken
- Sprint 1: 
-   - uitleg over het opzetten van de buildserver. Voornamelijk installatie scripts. Uitleggen wat dit zijn. Uitleg over hoe te verbinden etc. Vertellen dat het de server is van daan en hij het opzetten vooral heeft gedaan.
- Sprint 2:
-   - Ook begin aan docker maken, door veel errors waarvan we verwachtte dat het kwam door cache. Uiteindelijk problemen met de package manager(zypper) in docker. Overgegeven aan Rinske.
-   - Doel om SailfishOS te kunnen bouwen. Lijst met errors en oplossingen gemaakt voor het team. Os werkte, maar de boot image niet. <uitleg boot image>. Boot image veroorzaakte boot loops
- Sprint 3:
-   - Bootloopende image oplossen. Uitleg wat er gebeurde. Wat de conclusie was(niet goed geflasht. boot image niet overschreven?). Image bekeken met programma, was de ram disk 0 bytes. <Uitleg initramfs>.
-   - Tijdens oplossen goed gekeken naar de stappen om uit te vogelen waar de ram disk gemaakt zou moeten worden. Uiteindelijk gestuit op wat errors van make.
-   - Ja ja, uiteindelijke probleem: 2 missende packages die niet in de lijst van requirements stond op de readme.
- Sprint 4:
-   - Build environment werkt. Wat nu? Mobiele data! Onze eerste echte contributie. 
-   - Taken waren opgesplitst. Mijn doel: uitzoeken wat connman doet, waar het ligt in het proces met 4G en of er errors zijn/configuraties verkeerd staan.
-   - Ik stuitte op errors dat Ofono de boosdoener was. Toen even ofono logs bekeken. Stuitte op error 4100. Gegoogled: kon niks vinden.
-   - Overlegd met remy. Hij had ook gegoogled: mogelijk package 'dummy\_netd installeren'
-   - Dummy\_netd geinstalleerd op telefoon. Werkte!
-   - Mijn taak: uitzoeken hoe het te packagen in de image. 
-   - <uitleg hoe installeren en packagen. Uitleg patterns>

## Mijn Taken (Sprint 5)
- Proberen waydroid te installeren via de build environment. 
- - Problemen met gbinder (pytthon library voor binder nodes)
- Gestuit op SailfishOS: Chum. Een repository voor zypper voor sailfishos 
- Besloten te installeren direct op de telefoon.
- - Geinstalleerd! Probleem: binder nodes 
- Onderzocht wat binder nodes zijn. Uitleg binder nodes.
-  Build releasen van 4g op verschillende forums

## Mijn taken (toekomst)
- Binder nodes mee te compileren in de kernel. 
- Testen of hiermee waydroid werkt.
- Als dat makkelijker is, gewoon een post-install script maken voor waydroid ipv op de build server (ivm missende packages op een niet-live environment)
## Vragen en feedback
- Vragen over de inhoud of het project?
- Feedback!
