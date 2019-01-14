Doen: maak een lijst van routes (met korte omschrijving) en bedenk alvast de naam van de functie. Geef aan of er een scherm bij hoort en of het een GET of POST request is.

Routes:
1.Index (Post/Get)
2.Lobby (Post/Get)
3.Quiz (Post/Get)
4.Scoreboard (Post/Get)

Bij elke route hoort er een scherm. 

models:
Class Quiz: 
* contructor, maakt nieuwe quiz aan
* add_player, voegt een speler aan de quiz toe
* next_question, ga naar de volgende vraag
* finished, sluit quiz af, redirect spelers naar scorebord

Class DataSources:
* contructor, maakt class aan
* geeft 10 dicts in een lijst terug met in elke dict een vraag met 3 foute antwoorden, 1 goede, een vraag

Class User: 
* contructor, maakt class aan
* update_score, geeft int met de nieuwe score

Class Question:
* contructor, maakt class aan

Javascript:
* Timer
* Redirect als de timer klaar is

Plugins/Frameworks:
* Flask
* Flask-Session
* passlib
* SQLAlchemy
