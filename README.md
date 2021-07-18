# graphdb-jena-connect

Set up instructions: 

Set up GraphDB
1) Download GraphDB free from https://graphdb.ontotext.com/
2) Launch GraphDB locally
3) Click "import" on the left navigation bar, and click RDF
4) Click upload RDF files and upload ngbo.owl file
5) Click "SPARQL" on the left navigation bar to open SPARQL query & update editor window
6) Click "run" in the bottom right corner to test a SPARQL query with the default code

Set up front-end web app
1) Download front-end web app code from https://github.com/Dalalghamdi/NGBOProject
2) Install Java JDK 11 from https://www.oracle.com/ca-en/java/technologies/javase-downloads.html
3) Install Apache Jena Fuseki from https://jena.apache.org/download/index.cgi
4)  Install pycharm community version from https://www.jetbrains.com/pycharm/download/#section=mac
5) Install python from https://www.python.org/downloads/
6) Open front end project file in pycharm using "open project"
7) Connect python as the intepreter in pycharm through the bottom right corner
8) Launch fuseki server through downloading the apache jena fuseki file and opening fuseki-server.bat or fuseki-server
9) Launch localhost:3030 and upload ngbo.owl file with /NGBO as the sparql end point
10) Install flask following instructions from https://flask.palletsprojects.com/en/2.0.x/installation/ (pip install flask, etc.) 
11) Right click on main.py in NGBOProject-main, and click "run" to run the web app locally
