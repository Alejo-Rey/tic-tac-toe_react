## The game Tic Tac Toe

You can play with anothe player, the X player always begin. one feature is you can back in the history of the game.


### Requirements
* Git
* Docker
* Docker-compose


### Run it 
firts download the repo. 
RUN `git clone https://github.com/Alejo-Rey/tic-tac-toe_react.git && cd tic-tac-toe_react`

Then you need to up the service
RUN `docker-compose up -d --build`

### Edit
You can edit the code directly in the path of the game or you can manage the container.
RUN `docker-compose exec node bash`
once inside the conatiner you can exit of this with the command `exit`

### down or stop the service
You can down the service with:
`docker-compose down`
or stop it with:
`docker-compose stop`