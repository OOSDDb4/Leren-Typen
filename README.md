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
**Teamleider**: Onne Krol
**Teamleden**: - Alina Koroleva
               - Jeroen Maassen Van Den Brink
               - Fedde Talma
               - Elan Zandt
               - Ius de Visser
**Opdrachtgever**: HBO-ICT docenten (Windesheim University of Applied Sciences)


---
## Branching strategie
### **Main (P)**
De code die op de `main` branch staat is stabiele, geaccepteerde en geteste code die door de Product Owner is goedgekeurd.

#### Merge voorwaarden
- De code moet getest zijn op de `staging` branch.  
- De code moet geaccepteerd zijn door de Product Owner (John Brouwers).  
- De code mag alleen door de Team Lead () gemerged worden.  


### **Staging (A)**
De code die op de `staging` branch staat is code die klaar is om getest te worden.  
Er is gekozen om met een losse `staging` branch te werken, zodat er ondertussen op `develop` verder gewerkt kan worden zonder de acceptatietesten te beïnvloeden.

#### Merge voorwaarden
- De code moet getest zijn op de `develop` branch.  
- De code moet geaccepteerd zijn door de Team Lead ().  
- De code mag alleen door de Team Lead () gemerged worden.  


### **Develop (T)**
De code die op de `develop` branch staat is code die klaar is om getest te worden.  
Op de `develop` branch wordt gewerkt aan nieuwe features en bugfixes (in de vorm van feature branches).  
Er wordt gewerkt met een `develop` branch om te zorgen dat alle losse feature branches goed gemerged kunnen worden.

#### Merge voorwaarden
- De code moet lokaal getest zijn.  
- De code moet minstens door een ander teamlid gereviewed en goedgekeurd zijn.  
- De code moet voldoen aan de code conventies.  


### **Feature/naam_van_feature (O)**
Een `feature/` branch wordt gebruikt wanneer er aan een nieuwe feature wordt gewerkt.  
`Feature/` branches worden altijd aangemaakt vanuit de `develop` branch.  
De naam van de feature branch moet omschrijvend zijn.  
Werk volgens de afgesproken code conventies.  


### **Hotfix/naam_van_bugfix (O)**
Een `hotfix/` branch wordt gebruikt wanneer een bug wordt opgelost.  
De naam van de hotfix branch moet omschrijvend zijn.  

---
## Code conventies

- Naamgeving van variabele, functies/methods en klasses moeten beschrijvend zijn. Zo moet er geen x of y staan maar addProduct of removeProduct.  
- Geef alles een type en gebruik niet var.  
- Namen van Classes, Methodes, Enumerations, Public fields, Public Properties en Namespaces gebruiken PascalCase.  
- Namen van locale variables gebruiken camelCase.  
- Namen van private, protected, internal en protected Internal fields en properties gebruiken _camelCase.  
- Namen van een interface beginnen met een I bijvoorbeeld: IInterface.  
- Alle classes en interfaces hebben hun eigen bestand.  
- De bestandsnaam moet exact overeenkomen met de class of interface binnen dat bestand.  
- Houd een vaste volgorde aan in klassen:  
  1. Fields  
  2. Properties  
  3. Constructors  
  4. Public Methods  
  5. Private Methods  
  6. Events  
- Sorteer en groepeer using statements: Eerst system namespaces, daarna project namespaces.
