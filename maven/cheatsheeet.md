#MAVEN

## Creacion nuevo proyecto JAVA basado en plantilla (arquetipo)
mvn archetype:generate -DarchetypeArtifactId=maven-archetype-quickstart


## Identificacion proyecto en maven:
- groupID: 
    - Empresa/Organizacion a cargo del desarrollo (Dominio internet invertido): 
        Ejemplo: com.gfi
    - Que estoy desarrollando? a alto nivel:
        Ejemplo: web-app-nominas
    Todo el groupID seria: com.gfi.web-app-nominas

- artifactID: Ques es nuestro proyecto?
    Ejemplo: web-services

El identificador es la suma de los dos: groupID+artifactID

## GOLES
mvn GOLE_NAME
    - clean:        limpiacd 
    - compile:      compila el proyecto
    - test compile: compila los test unitarios
    - test:         ejecuta las pruebas unitarias, haria las 2 anteriores 
    - package:      empaqueta el proyecto, haria las 3 anteriores si no estan hechas (compile, test compila y test)
    - install:      incluir nuestro artefacto (proyecto) en el repositorio local de mavencat -gitignore