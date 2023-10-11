# event calender

## add event pagina
- form met input velden om een event toe te voegen.
- een submit knop om het event aan de database toe te voegen.

## event pagina
- laad alle events in.
- optioneel een knop om het event te verwijderen.

## event class
- een event class met de volgende properties:
    - id?
    - title
    - description
    - date
    - startTime
    - endTime
    - location
  - methods:
    - event duration
    - hoeveel dagen tot event
    - toJson
    - add to html 
    - add to database
  
## utilities
- enum voor event types
  



## start the project 

1. clone this template

1. open the project folder in vscode
2. cd into event-exercise
3. run `npm install`
4. run `npm run dev`
5. run `npm run db` in a new terminal


execution error on npm run db?
run this command in a powershell as admininstrator
```sh
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope LocalMachine
```