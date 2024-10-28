# web-project-management Tool: ScienceHUB
### Developed a tool for managing scientific projects, including resource and collaboration management. The tool featured a local web interface created using HTML and CSS and a SQL-based database was implemented to store both user registrations and project data. We applied Scrum and Kanban methodologies for project management, and utilized Docker for containerization and SonarQube for code quality analysis.

## Anforderungen
---
* Python 3.x
* Flask 
* SQLite


## Docker Installation
---
### Image erstellen
* docker build -t website  . 

### Docker-Container starten
* docker run -d -p 8000:8000 --name container-fuer-website website

### Extra Docker Befehle
* Alle laufende Container anzeigen: docker ps
* Container stoppen: docker stop sciencehub-container
* Container löschen: docker rm sciencehub-container



## Verwendung
---
### Über Docker
* Nachdem der Container gestartet wurde läuft die Anwendung unter http://localhost:8000

### Über Python
* Führe den folgenden Befehl aus: python scienhub.py
Die Anwendung läuft dann auch unter http://localhost:8000



## Autoren
---
- **Imad Azizi**
- **Torge Rau**
- **Rafik Farhane**
- **Lukas Baumeister**

## Mentoren
---
- **Prof Stephan Jonas**
- **Marko Jovanović**
- **Leon Nissen**
- **Lara Marie Reimer**
