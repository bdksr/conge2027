# Luiaard conge 2027

Statische pagina (één bestand: `index.html`) voor GitHub Pages.

## Online zetten
1. Maak op github.com een nieuwe repository (bijvoorbeeld `conge-2027`).
2. Upload `index.html` (en deze README) naar de hoofdmap van de repository.
3. Ga naar Settings > Pages. Kies bij "Build and deployment": "Deploy from a branch", branch `main`, map `/ (root)`, en bewaar.
4. Na ongeveer een minuut staat de pagina op `https://<gebruikersnaam>.github.io/<repository>/`.

## Hoe het werkt
- Iemand kiest zijn naam, kiest de dagen (max. 42: eerste 30 hoge prioriteit, volgende 12 lage prioriteit, max. 8 dagen in juli + augustus) en bevestigt.
- De pagina maakt dan een Excel-bestand met alle dagen van 2027 (beschikbaar / gekozen / prioriteit) en opent een e-mail naar ben.dekeyser@zone1.be met onderwerp "conge 2027". De bijlage voegt de persoon zelf toe.
- Er is geen server en geen login: er wordt niets op GitHub opgeslagen. De keuze van iemand wordt alleen op zijn eigen toestel onthouden.

## Aanpassen
Alles staat in `index.html`: namen en groepen (`GROUPS`), het e-mailadres (`MAIL_TO`), het onderwerp (`MAIL_SUBJECT`) en de limieten (`LIMIT`, `HIGH_LIMIT`, `LOW_LIMIT`, `SUMMER_LIMIT`).
