SETUP
To setup and execute this codebase, you will need a way to host a local web server. Simply host a local webserver which serves the included index.html, access the page, and you should see the simulation running.
As I use python, these instructions will be for how to do so in python.
1. Ensure the directory is unzipped, and "Assets" and "index.html" are in the same directory together.
2. Open a terminal (command prompt in Windows) IN THE DIRECTORY and run "python -m http.server 8000". This should open a simple web server that serves the content of the directory.
3. Open any internet broweser and navigate to 127.0.0.1:8000. This should display the simulation, and it should automatically start running!
