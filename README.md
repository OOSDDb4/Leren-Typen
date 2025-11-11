# Typefout
TypeFout is een leerapplicatie die gebruikers helpt om sneller en nauwkeuriger te leren typen.  
De app meet je typesnelheid, geeft persoonlijke feedback en slaat je resultaten op, zodat je je voortgang kunt volgen.  
Daarnaast bevat de app speciale oefeningen die gericht zijn op het verbeteren van specifieke typevaardigheden.

---
## Functionaliteiten
- **Typesnelheid meten**: De app meet hoe snel je typt en geeft je een score op basis van je prestaties.
- **Persoonlijke feedback**: Na elke oefening ontvang je feedback over je typevaardigheden en tips om te verbeteren.\
- **Resultaten opslaan**: Je voortgang wordt opgeslagen, zodat je kunt zien hoe je verbetert over tijd.

## Tehcnische stack
- **Frontend**: .NET MAUI (C#)  
- **Backend**: ASP.NET Core Web API (C#) 
- **Database**: SQLite
- **Versiebeheer**: Git en GitHub

## Team
**Project**: TypeFout
**Teamlieder**: Onne Krol
**Teamleden**: - Alina Koroleva
               - Jeroen Maassen Van Den Brink
               - Fedde Talma
               - Elan Zandt
               - Ius de Visser
**Opdrachtgever**: HBO-ICT docenten (Windesheim University of Applied Sciences)


---
## Branching strategie
We gebruiken de Gitflow branching strategie voor dit project.
- **Main branch**: Bevat de stabiele versie van de code die klaar is voor productie.
- **Develop branch**: Bevat de nieuwste ontwikkelingsversies van de code. Nieuwe features en bugfixes worden hier eerst geïntegreerd.
- **Staging branches**: Wordt gebruikt als testomgeving tussen de ontwikkel- en productiebranch, waar nieuwe functies eerst worden gecontroleerd voordat ze live gaan.
- **Hotfix branches**: Voor kritieke bugfixes die direct in productie moeten worden opgelost, wordt een hotfix branch gemaakt vanaf de main branch. Na voltooiing wordt deze gemerged terug naar zowel main als develop.

---
## Code conventies
We hanteren de volgende code conventies om de leesbaarheid en onderhoudbaarheid van onze code te waarborgen:
- **C# Coding Standards**: We volgen de officiële C# coding standards zoals beschreven door Microsoft.
- **Naming Conventions**: We gebruiken duidelijke en beschrijvende namen voor variabelen, methoden en klassen.
- **Commentaar**: We schrijven duidelijke commentaren bij complexe codeblokken om de functionaliteit uit te leggen.
- **Code Reviews**: Alle code wordt gereviewd door ten minste één teamlid voordat deze wordt gemerged naar de develop branch.