# e-Portfolio JHipster

## Requirements
1. Java 8
2. Maven (In IntelliJ und eclipse integriert) / Gradle

## Installation von JHipster
1. [NodeJS](https://nodejs.org/en/) (LTS version)
2. Yeoman: ```npm install -g yo```
2. Bower: ```npm install -g bower```
3. Gulp: ```npm install -g gulp-cli```
4. JHipster: ```npm install -g generator-jhipster```


## Demonstration
1. Erstelle einen Ordner (z.B. "cars" und führe in diesem Verzeichnis den folgenden Befehl  aus: ```yo jhipster```
	* 1/13 "Monolithic application"
	* 2/13 ENTER
	* 3/13 "de.dhbw.cars"
	* 4/13 ENTER
	* 5/13 ENTER
	* 6/13 ENTER
	* 7/13 H2 with in-memory persistence
	* 8/13 ENTER
	* 9/13 Maven / Gradle
	* 10/13 Enter
	* 11/13 Enter
	* 12/13 no
	* 13/13 Cucumber
2. Erstelle die Entities ```Owner``` und ```Car``` mit dem [JDL Studio](http://jhipster.github.io/jdl-studio/). Wie die einzelen Datentypen spezifiert werden können, kann aus [hier](http://jhipster.github.io/jdl/) nachgelassen werden.
3. Der ```Owner``` verfügt über folgende Attribute:
	* Firstname
	* Lastname
	* Birthday
3. Das ```Car``` verfügt über folgende Attribute:
	* Model
	* Company
	* DateOfProduction
4. Ein ```Car``` verfügt genau über einen ```Owner```. Ein ```Owner``` kann über mehrere ```Cars``` verfügen.
5. Importiere die erstellen Entitäten in JHipster mit dem folgendem Befehl ```yo jhipster:import-jdl filename.jh```
7. Starte die Anwendung und lege einen ```Owner``` mit einem zugehörigen ```Car``` an.
8. Importiere die Anwendung in deine IDE.
