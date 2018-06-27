# meetUsProject
This repository intends to guide the API Rest endpoint that will be used for the project.

## Functionalities
En las siguientes líneas se describirán las funcionalidades de la app.


### See common places
The main user could add other users he/she would like to meet and choose for a meeting purpose. Then, the app will show a list of 20 places where they can meet.

#### API
The endpoint that will cover this funcionality will be `POST /places`.

### Search participants
The main user could search for posibles participants by their full name and then add them to the solicitude for seeing places. The app will saved the user id in memory. The main user could look for many participants.

The endpoint that will cover this funcionality will be `GET /participants`