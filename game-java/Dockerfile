FROM openjdk

RUN mkdir /my_app

COPY game.java /my_app/

WORKDIR /my_app

RUN javac game.java

CMD ["java", "game"]