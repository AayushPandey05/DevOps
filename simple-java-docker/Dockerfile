#Pull a BASE IMAGE which gives all required tools and lib
FROM eclipse-temurin:17-jdk-alpine

#create a folder where the app code will be stored [Working Directory]
WORKDIR /app

#COPY source code from your HOST machine to your container
COPY src/Main.java .

# compile the application code [Install Dependencies]
RUN javac Main.java

#Run the application
CMD ["java", "Main"]
