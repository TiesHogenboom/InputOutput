
## Ties Hogenboom SD2A Mediacollege


# Intro
Mijn naam is Ties Hogenboom, Ik zit op het Mediacollege in Amsterdam en studeer Software Development. Ik zit in mijn 2e jaar. <br />

Op deze github pagina staan de bestanden van mijn project en in dit readme.md bestand staat de documentatie en werk process.

<br>
<br>
<br>
<br>

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


<br>
<br>
<br>
<br>

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

Voor het programeren van de nfc tags gebruik ik nfctools.  De andere writer die ik heb gevonden deed het niet met opstarten.

| NFC write program| Works with reader| starts up |
| --------- |:-------------:|:-------------:|
| nfctools (WakeDev)    | x             | x
| nfctools (FLOSS)     | -             | x




Het lasigste onderdeel van dit project is dat ik niet goed kan inschatten hoeveel tijd het mij gaat kosten omdat ik nog geen ervaring heb met het programeren van nfc tags.

De kennis die ik nodig heb voor dit project is coderen met HTML en CSS, hoe ik een payment handeling service toe voeg aan een website en hoe ik een nfc tag programeer.

Ik heb voor dit project ~ 6- 7 weken nodig. In die tijd wil ik veel research doen en uitproberen.

<br>
<br>
<br>
<br>

# Inhoud (Log boek)
## Periode 1
---
( Hoe de nfc tag werkt)
![alt text](https://i.imgur.com/mLyhltC.png)
---

( Hoe ik de nfc tag programmeer) </br>
![alt text](https://i.imgur.com/UtSsEoe.png)
---
De eerste 2 weken heb ik research gedaan naar wat nfc tags zijn, waar ze gebruikt voor worden en hoe ik zelf een nfc tag in mijn project ga gebruiken. Ik heb ook op school geregeld dat ik dit periode samen met Moodus samenwerk.

Ik heb als eerst gewerkt aan planning en github, zoals ik elk ander project begin. Mijn planning is op trello, want ik heb al vaker met trello gewerkt. Door het project heen hou ik mijn github en trello bij. De github bijhouden is handig zo dat te zien is hoeveel ik aan mijn project heb gewerkt en op welke dagen, ook om terug te gaan naar een vorige versie. De trello is om mijn project hellemaal uit te kunnen plannen tot in de kleinste details.

Aan het einde van de periode had ik een gesprek over mijn idee, en een 'go' gekregen om door te gaan met mijn project

## Periode 2

Ik begon periode 2 met het kopen van de spullen die ik nodig heb voor mijn project. Hieronder vallen de nfc chips en de nfc reader. Ik wou aan het einde van de periode al iets kunnen laten zien maar eerst research over wat er mogelijk is.

Ik heb ook tijdens de 2e periode met docenten gesproken over mijn project. Het probleem waar ik mee zat was dat mijn project niet heel uitgebreid of moeilijk is. Na wat advies heb ik een paar idëen opgeschreven, maar omdat ik eerst op mijn eerste project moest focussen heb ik dat ook gedaan.

Een probleem waar ik het 2e periode mee zat is dat ik toch iets meer research wou doen dan wat ik eerst dacht, dus heb ik aan het einde van de periode niet iets kunnen laten zien.
## Periode 3
In periode 3 heb ik veel van mijn opdracht uitgewerkt. Het begon met de betaalpagina, die ik met behulp van een youtube video heb gemaakt. Nadat de betaalpagina werkte moest ik de pagina ervoor maken, waarin je een bedrag kon kiezen. 

Mijn plan was om aan het einde van de periode de opdracht af te hebben zodat ik in periode 4 nog een opdracht erbij kon maken. Omdat mijn project niet zo moeilijk was heb ik periode 3 alles af kunnen maken en in de 2e week van de periode ben ik begonnen met het denken aan mijn 2e project.

Na een paar dagen na te denken had ik een leuk en handig idee. Een nfc chip in mijn kamer die ik kon scannen om mijn workout te starten in de ochtend. In periode 4 heb ik dit idee verder uitgewerkt.
## Periode 4
Op het begin van de periode heb ik mijn idee afgemaakt en begon ik met bouwen. Ik wou dat er een lamp aan ging met een nfc chip die aan mijn muur vastgeplakt was en dat mijn telefoon op stil stand ging en dat spotify opende. Na mijn workout kon ik doormiddel van een andere nfc chip de workout eindigen en dan mijn uren opschrijven in een bestand. Ook zou de workout zelf eindigen na 1 uur, en de lamp zelf weer aan gaan.

Ik had net voor de deadline mijn opdracht af, en had op het einde van de periode mijn eind presentatie. Daarvoor moest ik een presentatie gemaakt en de betaalautomaat meegenomen naar school om te laten zien tijdens mijn presentatie

## Herkansing

Er miste een paar dingen in mijn project waaronder mijn logboek, en usertest. Dus moest ik opnieuw presenteren op een latere datum. Ik begon met het maken van mijn logboek en kreeg die snel af. Ook heb ik usertest gedaan op het bedrijf. 

Een paar dagen later heb ik iets aan mijn project veranderd, nadat ik heb gesproken met de baas van het bedrijf waar ik het project voor maakte. De nfc chip zat eerst op de betaalautomaat zelf, maar dat vonden wij beiden niet de beste plek ervoor. Dus hebben we de nfc chip verplaatst naar de het bord wat om de betaal automaat zit.

Op de dag voor de presentatie heb ik mijn powerpoint nagekeken en afgemaakt.

# Links
https://moodus.com/ <br />
https://stripe.com/ <br />
https://nfcw.nl/ <br />
https://www.wakdev.com/en/apps/nfc-tools.html (WakeDev)<br />
https://nfc-tools.github.io/ (FLOSS) <br />
### Research
uh vind iets over RFID vs NFC research
https://www.paypal.com/us/digital-wallet/manage-money
https://due.com/payments/
https://www.rapyd.net/
