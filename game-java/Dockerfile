FROM openjdk:alpine

LABEL version="1.0.1"

WORKDIR /prt1/game-java

COPY . .

RUN javac game.java

CMD [ "java" , "game" ]
