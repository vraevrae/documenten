# Projectvoorstel

## Samenvatting
Het doel van onze webapplicatie is dat gebruikers live een triviaspel tegen elkaar kunnen spelen.
Het doel van de website is de triviale kennis van de gebruikers vergroten door je kennis te testen tegen vrienden.
Wanneer de site wordt geopend moet de gebruiker een naam opgeven en kiezen tussen het joinen van een al bestaande quiz (door een code in te vullen) of een nieuwe quiz aanmaken.
Vervolgens beland iedereen in een lobby waarin alle namen van de deelnemers verschijnen en de code van de quiz. De gebruiker die de quiz heeft aangemaakt ziet ook een start knop.
Wanneer er op de start knop is gedrukt begint het spel en start een timer. Na een nog te bepalen tijd krijgen alle spelers de volgende vraag te zien, ongeacht of ze wel of niet iets hebben ingevuld. Aan het einde verschijnt een scherm waarop te zien is wie er gewonnen heeft.


## Schetsen

### TODO, *Robert-Jan*

## Features
 * De website moet stabiel zijn (MVP)
 * Er moeten vragen kunnen worden beantwoord (MVP)
 * Er moet minimaal ondersteuning zijn voor de implementatie van jservice.io (MVP)
 * Het design moet duidelijk en dus overzichtelijk zijn (MVP)
 * De gebruikers moeten live met elkaar kunnen spelen (MVP)
 * Omgaan met error's (MVP)
 * Je moet niet twee keer dezelfde vraag krijgen binnen één quiz
 * Er moet een scorebord zijn
 * Scores moeten worden bijgehouden per competitie, eventueel ook globaal
 * Er kan gekozen worden om een random quiz te joinen
 * Gebruikers kunnen inloggen en registreren
 * Gebruikers de mogelijkheid geven om aan te geven als vragen niet goed of leuk zijn en ze te verwijderen uit de database
 * Meerdere moeilijkheidsgraden mogelijk bij quizvragen
 * Wanneer blijkt dat iedereen de vragen goed/fout heeft, de volgende vragen moeilijker/makkelijker maken
 * Gebruikers kunnen level up gaan door middel van xp die verdiend kan worden bij 
 * Feed van quizes met publieke quizzes waaraan iedereen kan meedoen
 * *Eventueel:* een chat na een quiz om vragen te bespreken of gebruikers te feliciteren
 * *Eventueel:* vriendensysteem waarin gebruikers met vrienden kunnen meespelen

## Afhankelijkheden
### Databronnen
 * jservice.io

### Externe componenten
 * Bootstrap
 * SQLite
 * Github

### Concurrenten
 * Kahoot!, live spelen tegen elkaar.
 * Trivia Crack, tegen elkaar spelen met quizvragen en het bijhouden door middel van ene scorebord.

### Moeilijke delen
 * Het live spelen en eerlijk houden van spelers (latency)
 * Meerdere API's ondersteunen


## Sanity check
Komt nog!
