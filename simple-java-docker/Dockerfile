#os for enviorment
FROM openjdk:17-jdk-alpine

#work directory
WORKDIR /app

#copy the  src to the work directory
COPY . /app

#install the requirements
RUN javac /app/src/Main.java

#run the app
CMD ["java", "Main"]