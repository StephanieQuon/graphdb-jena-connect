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
2) Install a Java JDK 1.8.x from https://www.oracle.com/ca-en/java/technologies/javase-downloads.html
3) Download Apache Jena Fuseki from https://jena.apache.org/download/index.cgi
4) Get Apache Jena source code from https://jena.apache.org/getting_involved/index.html
5) Download Eclipse IDE from https://www.eclipse.org/ide
6) Download ARQ 2.9.3 from https://repository.apache.org/content/repositories/releases/org/apache/jena/jena-arq
7) Follow the steps to use Apache Jena in Eclipse from https://jena.apache.org/tutorials/using_jena_with_eclipse.html

For using pycharm
1) Download pycharm community version from https://www.jetbrains.com/pycharm/download/#section=mac
2) Install python from https://www.python.org/downloads/
3) Download front end from https://github.com/Dalalghamdi/NGBOProject
4) Open front end project file in pycharm using "open project"
5) Connect python as the intepreter in pycharm through the bottom right corner
6) Install flask following instructions from https://flask.palletsprojects.com/en/2.0.x/installation/
7) Right click on main.py in NGBOProject-main, and click "run" to run the web app locally

Regular use of web app
1) Open pycharm
2) Open NGBOProject and make sure pythin is connected as the interpreter 
3) Launch fuseki server through downloading the apache jena fuseki file and opening fuseki-server.bat or fuseki-server
4) Download Java JDK 11 
5) Launch localhost:3030 and upload ngbo.owl file with /NGBO as the sparql end point
6) Right click on main.py in NGBOProject-main, and click "run" to run the web app locally
