# Micro-Services  Basé Sur La JVM avec trois languages de programmation : JAVA Kotlin et Groovy #

Guide: Comment Construire Des Micro-Services Avec le Framework Micronaut  Basé Sur La JVM
avec trois langages de programmation : JAVA Kotlin et Groovy


## To run the service discovery

Télécharger kinematic pour windows, Pour toolbox c'est inclus.

sinon pour les desktop :

https://github.com/docker/kitematic/releases/download/v0.17.11/Kitematic-0.17.11-Windows.zip

Dezipper et lancer l'application Kinematic.

Puis se loguer avec le compte Docker.

Paramétrer les ports comme dans le tutoriel.

Ouvrez http://localhost:8500/ui dans votre navigateur.

Vous allez voir les services qui sont lancé.

## To run the microservices

./gradlew run -parallel 

# Tests 

## To run tests:

./gradlew test

## To run acceptance test

Ouvrez un nouveau terminal dans le dossier complet:

./gradlew acceptancetest:test

curl http://localhost:8080/books





