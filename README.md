# Intelligent Interpreters

##### Disclaimer

The focus of this project is to create a fully functional web application where the audio clip is to first record and process an audio clip, make predictions using the model, transcribe the speech into text, and translate the audio into a different language. I personally was not involved in the development of the Neural Network model that is used for prediction in this project. It was originally developed by a group of my batchmates at George Brown College on a previous project. They gave us full permission to use the model for this project.

## Project Goal

The goal of the project is to create a web app to deploy a trained neural network model that can detect the gender and language of a speech from a 10 second audio clip, transcribe the audio into text, and then to translate the audio in a different language (English in this case). Throughout the development of the project, Agile Project Management (Scrum) methodologies were followed. This is an overview of the project, detailed project report of the different sprints and development can be found in the project report in the Project Documents directory in this repository.

## Approach

The project was developed following Scrum methodologies of Agile Project Management. The whole project was divided into 4 sprints, each sprint was completed in 2-3 days. The user stories for the 4 sprints are as follows:

1. User needs a Flask app which can capture audio from their microphone and save it into a file
2. User wants to read the audio into the app and return the prediction
3. User wants to transcribe audio from the app and return the translation
4. User wants to access the web application in a remote server so they can access it online

The entire application was deployed on a cloud GPU server on Linode, which is a cloud IaaS provider. The GPU server was used for faster inferencing. For the OS, Ubuntu 20.04 was used for stability, since Linux/Unix environments are known to be more stable. The Flask app was deployed through NGINX, using gunicorn for passing the port of the flask app to port 443.

## Conclusion

The project was a success, except for a few minor bugs, which was also mostly fixed later on. Scrum methodologies helped keep focus on the task in hand, divide the project into different modules, as well as meeting deadlines, and to keep all the project members updated with the progress on a daily basis. For the detailed project report, please look at hte project report in the Project Documents directory in this repository.
