# JSONDesignRecovery

JSONConverter is a tool converting a JSON file to a UML class diagram at conceptual level.
The result is written on the console in PlantUML format.
The diagram can be visualized with the server available at: https://plantuml.com/

Folder tests contains examples of the tool usage: 
- *.json - files in JSON
- *.puml - generated files in PlantUML
- *.png - diagrams in graphical format

# Requirements
Java 1.8 JRE is required.

# How to run the tool
To run the tool:
1. Download the JSONConverter.jar
2. Optionally downolad the tests folder
2. Open a console window and change the folder to that one, the JSONConverter exists
3. Write:
  java -jar JSONConverter.jar path_to_json
for example:
  java -jar JSONConverter.jar tests/1.json
  
