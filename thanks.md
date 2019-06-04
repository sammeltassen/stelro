---
title: Huwelijk Stella de Man en Rob Schoonman
layout: page
indexing: false
feature_image: "/assets/img/StellaRob_01-1000px.jpg"
feature_image_bottom: "/assets/img/StellaRob_02-1000px.jpg"
permalink: thanks.html
feature_text: |
---

# Stella de Man <br>Rob Schoonman

_Bedankt voor het invullen van het formulier!_

## Huwelijkssluiting
Zowel de burgerlijke huwelijksbekrachtiging als de kerkelijke/spirituele huwelijksviering vinden plaats in de Waalse Kerk. Het eerste vangt aan om 11.00 u ’s morgens en het tweede om 14.00 uur ’s middags. Tussen 12.00 uur en 13.45 uur worden jullie uitgenodigd om gezamenlijk de lunch te gebruiken in het Valkenbergpark op 7 minuten lopen vanaf de Waalse Kerk.

Indien je/jullie van plan bent/zijn om alleen de ochtend aanwezig te zijn, dan wel alleen bij de middagviering aanwezig te zijn, geef dat dan aan door gebruik te maken van de optie ‘bericht’ bij je aanmelding. Vermeld dan tevens in je bericht of je wel of niet gebruik wilt maken van de lunch.

## Ceremoniemeesters
<ul>
{% for ceremoniemeester in site.data.ceremoniemeesters %}
  <li>
    <b>{{ ceremoniemeester.naam }}</b><br>
	Telefoonnummer: {{ ceremoniemeester.mobiel }}<br>
	<a href="mailto:{{ ceremoniemeester.email | encode_email }}" title="Email">Email</a>
  </li>
{% endfor %}
</ul>

## Kledingadvies
Feestelijk

## Geschenken
Wij hebben bewust gekozen voor ons bruiloftfeest op Landgoed Nuwenhuys omdat de stichters hiervan beogen om in de werkzaamheden en festiviteiten op Nuwenhuys mensen met en zonder handicap met elkaar samen te brengen en samen dingen te doen en te vieren. 

De stichting Landgoed Nuwenhuys is op 21 juni 2018 van start gegaan en heeft nog de nodige investeringen voor de boeg alvorens de organisatie van de beoogde sociale activiteiten zoals het project ‘Zinvol werk voor mensen met een beperking’, van start kan gaan (zie [www.nuwenhuys.nl](http://www.nuwenhuys.nl/)).

Jullie giften zijn derhalve zeer welkom!

Voor het realiseren van jullie donaties aan de Stichting Steunfonds Landgoed Nuwenhuys zie [deze pagina](http://www.nuwenhuys.nl/donaties-welkom/).

## Adressen
<ul>
{% for locatie in site.data.locaties %}
  <li>
    <b>{{ locatie.naam }}</b><br>
	{{ locatie.adres }}<br>
	<a href="http://{{ locatie.url }}">Website</a> | 
	<a href="https://www.google.com/maps/search/?api=1&query={{ locatie.adres | uri_escape}}">Google Maps</a>
  </li>
{% endfor %}
</ul>

## Parkeren

### Bij de Waalse Kerk

<ul>
{% for parkeerplaats in site.data.parkeren %}
  <li>
    <b>{{ parkeerplaats.naam }}</b><br>
    {% if parkeerplaats.comment %}<i>{{ parkeerplaats.comment }}</i><br>{% endif %}
	{{ parkeerplaats.adres }}<br>
	<a href="https://www.google.com/maps/search/?api=1&query={{ hotel.adres | uri_escape}}">Google Maps</a>
  </li>
{% endfor %}
</ul>

### Bij Landgoed Nuwenhuys
Het parkeerterrein van Hockeyclub Zwart-Wit. De Club weet en is ermee akkoord dat onze gasten hun P-plaats gebruiken op 27 juni a.s. (het seizoen is dan al afgesloten). De ingang van de P-plaats vind je tussen [Reeptiend 19 en Reeptiend 25 te Breda](https://goo.gl/maps/tYPvPXBgda7azA3D8). Let op de drie richting aangevende houten bordjes met aanduiding stelro2019!
Rijdend vanaf de bebouwde kom van Breda zuidwaarts op de Galderseweg passeer je allereerst aan de linker kant het Kasteel Bouvinge, de kantoren van het Waterschap, het complex van Justitiële Jeugdinrichting en de hockeyvelden. Direct na de hockeyvelden wordt de afslag Reeptiend links (doodlopende weg) gemarkeerd door een horecabedrijf en het aan de lantaarnpaal bevestigde richtingbordje ‘stelro2019’.

## Tip
De afstand tussen de Waalse Kerk in Breda en Landgoed Nuwenhuys aan de Zuidkant van Breda is nog geen 6 km. Het is een aantrekkelijke fietsroute via Ginnekenweg, Ginnekenpleintje en het fietspad langs de Mark naar het landgoed. 
Parkeren bij het landgoed is mogelijk op het parkeerterrein van de hockeyclub aan het Reeptiend (het is buiten het hockeyseizoen). Kom je met de auto, neem je fietsen mee en parkeer 
de auto ‘s morgens aan het Reeptiend (gratis) en fiets dan naar de Waalse Kerk!

## Routebeschrijving
Sla vanaf het parkeerterrein linksaf, rechts voor je ligt dan het landgoed. Laat het Landgoed rechts liggen en neem het eerstkomende fietspad dat je ziet in het voor je liggende Markdal naar links. Fiets dat helemaal uit tot het einde van dat vrijliggende fietspad. Sla rechtsaf zodra je op de weg komt. Dan kom je op het Ginnekenplein en sla dan linksaf en vervolg daarna de Ginnekenweg (let op bij de kruising met de verdiepte ligging van de Zuidelijke Rondweg want daar moet je even rechts en dan meteen linksaf over de rondweg heen je weg vervolgen in de Ginnekenweg), Wilhelminastraat en daarna over de singels Ginnekenstraat totdat je in het centrum van de stad op ‘een soort van rotonde’ met een IJssalon rechts op de hoek arriveert. Sla daar rechtsaf (pas op dat stukje moet je delen met voetgangers) en sla zodra je weer de fiets/voetgangerszone verlaat linksaf met de bocht mee langs popcentrum Mezzo. Fiets die weg helemaal uit en fiets aan het einde met de bocht mee naar rechts. Daarna het eerste steegje linksaf het centrum in. Kijk uit, dit is een gevaarlijk en onoverzichtelijk punt om linksaf te slaan. Zodra je het steegje met kinderkopjes hebt bereikt met links de bibliotheek, fiets je rechtdoor, je kruist loodrecht de voetgangerszone, tot aan een T-kruising in het historische hart van Breda. Sla rechtsaf en dan zie je de Waalse Kerk links voor je!

## Overnachting
De nog beperkte B&B faciliteit van Nuwenhuys is reeds gereserveerd voor familie. Overige overnachtingsmogelijkheden zijn:

### Hotels
<ul>
{% for hotel in site.data.hotels %}
  <li>
    <b>{{ hotel.naam }}</b><br>
    {% if hotel.comment %}<i>{{ hotel.comment }}</i><br>{% endif %}
	{{ hotel.adres }}<br>
	<a href="http://{{ hotel.url }}">Website</a> | 
	<a href="https://www.google.com/maps/search/?api=1&query={{ hotel.adres | uri_escape}}">Google Maps</a>
  </li>
{% endfor %}
</ul>

### Kamperen
<ul>
{% for camping in site.data.campings %}
  <li>
    <b>{{ camping.naam }}</b><br>
	{{ camping.adres }}<br>
	<a href="http://{{ camping.url }}">Website</a> | 
	<a href="https://www.google.com/maps/search/?api=1&query={{ camping.adres | uri_escape}}">Google Maps</a>
  </li>
{% endfor %}
</ul>

_Beeld: [studio ilse van klei](http://ilsevanklei.nl)_

[Terug naar boven](#top)