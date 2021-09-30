

    1. Install Flask Framework - (In CLI) pip3 install Flask
    2. Add new python file - (In CLI) touch run.py
    3. To run the app - (In CLI) python3 run.py
    4. To stop the app running - (In CLI) ctrl+c

NOTE: "debug=True" should not be used in deployed version of project! Change to debug=False before submission.

Importing template from STARTBOOTSTRAP:

    1. (In CLI) mkdir static
    2. (In CLI) cd static
    3. (In CLI) wget {download link from chosen template}
    4. (In CLI) ls [to check files now in directory]
    5. (In CLI) unzip gh-pages.zip [to unzip the file]
    6. (In CLI) cd - [to go back to main directory]

Working with Heroku in the CLI:

    1. (In CLI) npm install -g heroku
    2. (In CLI) heroku login -i
    3. (In CLI) heroku apps [to list all of the apps in Heroku account]
    4. (In CLI) heroku apps:rename {new-app-name} --app {old-app-name}
    
