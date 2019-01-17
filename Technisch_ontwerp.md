Routes:

1. Index (Post/Get)

2. Quiz (Post/Get)


Bij elke route hoort er een scherm. 

## models:
answer, app, datasource, opentdb, quiz, store, user, view

Class Answer:
 * conctructor: slaat variable op in instance
 * check_answer: controleert het antwoord van de vraag

Class App:
 * contructor: opent nieuwe class store
 * new_quiz: maakt een nieuwe quiz aan
 * join_quiz: laat een gebruiker een quiz joinen
 * get_view: returned de huidige view
 * start_quiz: quizstarter kan de quiz starten.
 * answer_question: controleert of het antwoord op de vraag correct is door middel van de class Answer

Class Datasource:
 * constructor: controleert of de gevraagde datasource beschikbaar is en initialiseert deze.
 * get_datasources: returned alle beschikbare datasources
 * update_cache_data: ontvangt nieuwe quizvragen van de class OpenTDB
 * get_all_questions: returned het gevraagde aantal vragen (MAX = 50) van OpenTDB
 * get_question: returned 1 vraag uit cache_data

Class OpenTDB:
 * contructor: initialiseert class
 * \_download_data: interne functie die data opvraagt aan de Open Trivia DB API
 * \_format_opentdb_data: interne functie die de Open Trivia DB herformateerd
 * get_formatted_data: returned een lijst van alle opgevraagde vragen

Class Question:
 * constructor: initialiseert class
 * add_answer_by_id: voegt een antwoord toe aan de quiz
 
Class Quiz:
 * conctructor: initialiseert class en slaat variabelen op in de instance
 * add_question_by_id: voegt een vraag toe aan de quiz
 * add_user_by_id: voegt een speler toe aan de quiz
 * start: start de quiz
 * get_current_question_id: returned het id van de huidige vraag
 * finish: stopt de quiz
 * next_question: zorgt ervoor dat de quiz naar de volgende vraag gaat

Class Store:
 * constructor: initialiseert class en slaat variabelen op in de instance
 * create_quiz: maakt een nieuwe quiz aan en voegt het toe aan de instance 
 * create_answer: maakt een nieuw answer aan en voegt het toe aan de instance en de quiz
 * create_user: maakt een nieuwe gebruiker aan en voegt de gebruiker toe aan de App()
 * create_question: maakt een nieuwe vraag aan en voegt deze toe aan de instance en de quiz
 * create_question_from_source: vraagt een nieuwe vraag op aan de Datasource class
 * get_quiz_by_id: returned data van een quiz met een bepaalde id
 * get_quiz_by_code: returned data van een quiz met een bepaalde quiz code
 * get_question_by_id: returned data van een vraag met een bepaalde id
 * get_answer_by_id: returned data van een antwoord van een bepaalde questionid
 * get_answers_by_id: returned data van antwoorden van een bepaalde questionid
 * get_user_by_id: returned data van een bepaalde gebruiker met gebruikers id
 * get_users_by_id: returned data van een bepaalde gebruikers met gebruikers id
 * get_user_by_session_id: returned data van een bepaalde gebruikers met sessie id

Class User:
 * contructor: initialiseert class en slaat variabelen op in de instance
 * add_score: voeg een score toe aan de gebruiker
 * get_screen: ??????

Class View:
 * constructor: initialiseert class en slaat variabelen op in de instance

## Javascript:
* Timer
* Redirect als de timer klaar is

## Plugins/Frameworks:
* Flask
* Flask-Session
* passlib
* SQLAlchemy
