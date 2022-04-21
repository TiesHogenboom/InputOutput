
## Ties Hogenboom SD2A Mediacollege


# Intro
Mijn naam is Ties Hogenboom, Ik zit op het Mediacollege in Amsterdam en studeer Software Development. Ik zit in mijn 2e jaar. <br />

Op deze github pagina staan de bestanden van mijn project en in dit readme.md bestand staat de documentatie en werk process.


## Project & Wat ik maak

Voor de 3e periode in mijn 2e leerjaar maak ik een project voor de Input / Output module. De bedoeling voor dit project is om research te doen naar een unieke Input, en dat te combineren met een Output.<br />

Er zijn veel verschillende inputs waarmee je kan werken, en je mag alles gebruiken.<br /> Voorbeelden van een unieke input zijn:
Tracking technologie, Licht sensoren, Geluid sensoren, Chips etc.
De output kan ook van alles zijn: Game, Website, Licht, VR etc. <br />

Een voorbeeld voor dit project is een game te maken die werkt met geluid sensoren.
Dit project gaat minder over het maken van een volledig product en meer over het onderzoeken van een unieke input.<br />

Ik ga een mobiele betaling webpage maken en met nfc werken om een klant makkelijk op de pagina te krijgen. Hiervoor werk ik samen met Moodus, en mijn idee in hun product werken omdat Moodus op dit moment alleen maar gebruik maakt van contactloos betalen met een pinpas. <br /> <br />

Ik heb voor dit project gekozen om met NFC te werken omdat ik al een tijd iets met NFC wou maken. NFC werkt doormiddel van radiogolven, en is vergelijkbaar met bluetooth. NFC heeft veel verschillende toepassingen en je komt ze bijvoorbeeld tegen in pinpassen maar het wordt ook als losse chip gebruikt om het delen van informatie. Ik gebruik niet bluetooth omdat dat een powersource nodig heeft om te werken en ik wil mijn project zo simpel mogelijk houden. RFID was ook een optie omdat het bijna hetzelfde werkt als NFC, maar RFID wordt nauwelijks gebruikt voor wat ik wil doen, en er is minder informatie en projecten erover te vinden op het internet.<br />

Voor het afhandelen van de betalingen ga ik stripe gebruiken. Ik wou eerst zelf de betaling systeem maken maar dat kost heel veel geld en maanden werk dus dat is niet een optie. <br />

Er zijn naast stripe veel andere 'payment handeling' services, maar veel ervan zijn plugin's of een aparte webpagina. Een plugin wordt gebruikt als je een site maakt op bijvoorbeeld wordpress. Ik maak mijn site zelf met html en css dus een plugin kan ik niet gebruiken. Ook zijn er services die doormiddel van een link doorsturen naar hun eigen pagina voor de betalingen, maar dat maakt mijn project te simpel dus ik kies ik daar niet voor. Paypal is ook een optie maar als ik door de site van paypal gaat ziet het er best verwarrend uit dus heb ik er niet voor gekozen.

| Payment H | Customizable | Very easy to use |
| --------- |:-------------:|:-------------:|
| Stripe    | x             | x
| Rapyd     | -             | x
| Paypal    | x             | -
| Due       | x             | -



## Wat gebruik ik voor mijn project
Ik gebruik NFC tags, en een NFC reader om informatie van de tags af te lezen. Ik heb vele opties voor nfc tags en readers bekeken en heb uiteindelijk gekozen voor de tags (NTAG216) en reader (ACR122U) van nfcw.nl

![alt text](https://i.imgur.com/5UMLIbq.png)

![alt text](https://i.imgur.com/ksU2xKL.png)

De redenen dat ik op nfcw.nl heb besteld was omdat:
1. Beide producten hadden en goede prijs vergeleken met andere webwinkels.
2. De site is betrouwbaar omdat ik al eerder wat gekocht had van dezelfde site.
3. Veel andere sites zagen er niet betrouwbaar eruit
4. Wordt vanuit nederland bezorgd.
5. Site heeft beide producten die ik nodig heb.
---
(Website uit buitenland met hogere prijs)
![alt text](https://i.imgur.com/rnjEm7y.png)
---

De NFC reader die ik besteld heb is de enigste reader die ik online heb kunnen vinden, die werkt met mijn nfc tags.

De NFC tags werken met de reader die ik besteld heb en hebben veel opslag vergeleken met andere tags. Op de nfcw website staan ook NTAG215 coins, maar die hebben minder opslag.


![alt text](https://i.imgur.com/DhoER1f.png)


Voor het maken van de webpage gebruik ik HTML, CSS en Javascript omdat ik daarmee het liefsts werk. Ik kan ook als aternatief op wordpress de website maken maar ik heb niet genoeg ervaring ermee. Voor de betalingen gebruik ik Stripe, een service die ik makkelijk in mijn website kan zetten voor het handelen van de betalingen. Stripe maakt gebruik van node.js.

Het lasigste onderdeel van dit project is dat ik niet goed kan inschatten hoeveel tijd het mij gaat kosten omdat ik nog geen ervaring heb met het programeren van nfc tags.

De kennis die ik nodig heb voor dit project is coderen met HTML en CSS, hoe ik een payment handeling service toe voeg aan een website en hoe ik een nfc tag programeer.

Ik heb voor dit project ~ 6- 7 weken nodig. In die tijd wil ik veel research doen en uitproberen.

# Inhoud (Log boek)
## Periode 1
---
( How the nfc tag wil work )
![alt text](https://i.imgur.com/mLyhltC.png)
---

( How the nfc tag wil be programmed) </br>
![alt text](https://i.imgur.com/PGypiay.png)
---

## Periode 2
## Periode 3
## Periode 4

# Links
https://moodus.com/ <br />
https://stripe.com/ <br />
https://nfcw.nl/ <br />
### Research
uh vind iets over RFID vs NFC research
https://www.paypal.com/us/digital-wallet/manage-money
https://due.com/payments/
https://www.rapyd.net/


