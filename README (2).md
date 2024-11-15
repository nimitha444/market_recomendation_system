# market_recommendation_system
Description

A Regression type prediction model using Random Forest Regressor algorithm. It uses R², MSE (Mean Squared Error) as the metric for prediction. It is used for the improvement of the recommendation algorithm for marketing.
Github commands used:

    mkdir <file_name> to create the folder
    cd <file name> to go inside the folder
    git init, initializing folder as git repository
    git add . to add all the files into git track
    git commit -m "<message>", it commits whatever is there in the track
    git remote add origin <GitHub repository link>, builds connection between git and github
    git push --set-upstream origin master, sends all the files from git to github.

Docker:

    docker build -t <file_name> .
    docker run <file_name

Steps:

    Building the required files: app.py: flask code, requirements.txt: contains required libraries, marketing_recommendations.csv: The required dataset for this model, train_model.py: code to test the file, Dockerfile: contains commands to be run in docker
    Create a new item under Freestyle Project type in Jenkins.
    Select Git in Source Code Management and paste your repository url in the given space
    Add Execute windows batch command in Build Steps
    Build now and visualize console output
    Open command prompt with the directory of the folder with the required file
    Run the docker commands mentioned above
    Visualize the output in both command prompt and Docker desktop app

Output:![my3 docker proof recommendation_model](https://github.com/user-attachments/assets/5eb89014-7d9a-4e5f-9b4a-a570d7490d3d)
