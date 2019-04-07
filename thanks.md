---
title: Huwelijk Stella de Man en Rob Schoonman
layout: page
feature_image: "/assets/img/StellaRob_01-1000px.jpg"
permalink: thanks.html
feature_text: |
---

Bedankt voor het invullen van het formulier!

## Kledingadvies
Feestelijk

## Geschenken
Indien jullie de behoefte hebben om ons als bruidspaar iets te willen geven, lever dan een bijdrage aan de verdere ontwikkeling van Landgoed Nuwenhuys.

Wij hebben bewust gekozen voor ons bruiloftfeest op Landgoed Nuwenhuys omdat de stichters hiervan beogen om in de werkzaamheden en festiviteiten op Nuwenhuys mensen met en zonder (meervoudige) handicap met elkaar samen te brengen en samen dingen te doen en te vieren. 

De stichting Landgoed Nuwenhuys is op 21 juni 2018 van start gegaan en heeft nog de nodige investeringen voor de boeg alvorens de organisatie van de beoogde sociale activiteiten zoals het project ‘Zinvol werk voor mensen met een beperking’, van start kan gaan (zie [www.nuwenhuys.nl](http://www.nuwenhuys.nl/)).

Jullie giften zijn derhalve zeer welkom! Nuwenhuys betaalt geen erf- en schenkbelasting dus jullie donatie komt dus voor 100% goed terecht.

Voor het realiseren van jullie donaties aan de Stichting Steunfonds Landgoed Nuwenhuys zie [deze pagina](http://www.nuwenhuys.nl/donaties-welkom/).

## Adressen van de bruiloft
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

### Kamperen in de omgeving

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