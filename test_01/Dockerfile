FROM java:8
# kopiuje z maszyny fizycznej do obrazu
COPY src/main/java /src

WORKDIR src
# uruchamiam kompilacje
RUN javac Hello.java

CMD ["java", "Hello"]
