# Utiliser JDK 11 officiel
FROM eclipse-temurin:11

# Créer un volume temporaire (utile pour Spring Boot)
VOLUME /tmp

# Exposer le port de l'application
EXPOSE 8081

# Chemin relatif vers le JAR généré
ARG JAR_FILE=target/demo-0.0.1.jar

# Copier le JAR dans l'image
COPY ${JAR_FILE} app.jar

# Commande pour lancer l'application
ENTRYPOINT ["java","-jar","/app.jar"]
