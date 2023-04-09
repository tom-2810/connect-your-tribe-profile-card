> _Fork_ deze leertaak en ga aan de slag. Onderstaande outline ga je gedurende deze taak in jouw eigen GitHub omgeving uitwerken. De instructie vind je in: [docs/INSTRUCTIONS.md](docs/INSTRUCTIONS.md)

# Profile Card Tom Poortman
Eenvoudig visitekaartje met link naar GitHub profiel, mail en beknopte biografie.

## Inhoudsopgave

  * [Beschrijving](#beschrijving)
  * [Kenmerken](#kenmerken)
  * [Installatie](#installatie)
  * [Gebruik](#gebruik)
  * [Bronnen](#bronnen)
  * [Licentie](#licentie)

## Beschrijving

<img src="https://user-images.githubusercontent.com/112861614/230780878-673193db-d6e3-4440-b406-7c8f4a4a63c4.png" height="700">
<!-- In de Beschrijving staat hoe je project er uit ziet, hoe het werkt en wat je er mee kan. -->
Door middel van [dit visitekaartje](https://panicky-lime-zebra.cyclic.app/) stel ik mezelf kort voor. Mijn naam, nickname, avatar, biografie, GitHub profiel link en mailaddress zijn verwerkt tot een mobiel vriendelijke ontwerp.
<!-- Voeg een mooie poster visual toe 📸 -->
<!-- Voeg een link toe naar Github Pages 🌐-->

## Kenmerken

Dit visitekaartje is tot stand gekomen met Node JS, Express en als met het template framework EJS.
De getoonde data is dynamisch en word gehaald uit de [WHOIS API](https://whois.fdnd.nl/api/v1/member/tom-poortman) die alleen mijn gegevens ophaald.
Deze gegevens worden met Express meegeven aan het index.ejs bestand, waardoor ik deze gegevens kan tonen.

```ejs
<section class="name">
   <h1>
      <%= member.name %>
      <%= member.surname %>
   </h1>
   <h2>@<%= member.nickname %>
   </h2>
</section>
```
<!-- Bij Kenmerken staat welke technieken zijn gebruikt en hoe. Wat is de HTML structuur? Wat zijn de belangrijkste dingen in CSS? Wat is er met Javascript gedaan en hoe? Misschien heb je een framwork of library gebruikt? -->

## Installatie
Fork het project en voer eerst `npm install` uit in de terminal om alle nodige packages en dependencies binnen te halen. Vervolgens maakt `npm start` een port vrij om de website te bekijken in de browser.

## Gebruik

Open het visitekaartje met de volgende link: https://panicky-lime-zebra.cyclic.app/ .

Bezoek mijn GitHub profiel door op de groene knop te drukken "Visit".

![image](https://user-images.githubusercontent.com/112861614/230781484-2cc3c892-e940-46e1-a6b2-6131847b7e72.png)

Of leg direct contact met mij door op het mail icoontje rechtsbeneden te klikken. Deze opent je mailprogramma met mijn mailaddress vooraf ingevuld.

![image](https://user-images.githubusercontent.com/112861614/230781560-1063ffd0-d59d-41db-a1ee-27184feb78f5.png)


## Bronnen

## Licentie

![GNU GPL V3](https://www.gnu.org/graphics/gplv3-127x51.png)

This work is licensed under [GNU GPLv3](./LICENSE).
