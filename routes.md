### Template pagina's
/

/lobby

/game

/scoreboard

### QUIZ
/api/quiz/new POST
- RETURN 200 quiz_id
  
/api/quiz/:quiz_id GET -> Lobby
- RETURN 200 quiz object + users
  
/api/quiz/:quiz_id/join POST -> Join quiz
- RETURN 200 None
  
/api/quiz/:quiz_id/score GET -> Scoreboard
- RETURN 200 list of users with scores

/api/quiz/:quiz_id/question/current GET -> Quiz
- RETURN 200 question + answers

### QUESTION
	/api/question/:question_id GET -> Krijgen van vraag en antwoorden
	- RETURN 200 question + possible answers

### USER
/api/user/new POST -> Nieuwe gebruiker aanmaken
- RETURN 200 None

/api/user/:user_id GET -> Returned eigen data van user (zonder relaties)
- RETURN 200 user data
  
/api/user/:user_id/answer/new POST -> voeg een antwoord toe
- RETURN 200 None
  
/api/user/:user_id/answers GET -> haalt alle antwoorden op
- RETURN 200 list of answer
  
/api/user/:user_id/answers/:quiz_id GET -> haalt alle antwoorden op voor quiz_id
- RETURN 200 list of answers per quiz

/api/user/:user_id/quiz/current -> haalt de huidige quiz op waarin de user deelneemt
- RETURN 200 current quiz_id

/api/user/:user_id/quizes GET -> haalt alle quizes op waarin de user heeft deelgenomen
- RETURN 200 all quizes user participated in
