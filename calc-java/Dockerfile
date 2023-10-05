FROM openjdk:11

RUN mkdir /my_app

COPY calc.java /my_app/

WORKDIR /my_app

RUN javac calc.java

CMD ["java", "calc"]
