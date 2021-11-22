# cds-303-project

## Setup
Download docker (Availible at [docker.io](https://www.docker.com/))


## Running container without model 
The cds303-docker folder contains a dash app without the actual model. To build and run the app use the following commands: 
  docker build -t cds303 . 
  docker run -p 8050:8050 cds303
  
## Running container with model
The docker-model folder contains our model inside of a streamlit app. To build and run the app with the model use the following commands:
  docker build -t 303model .
  docker run -p 8501:8501 303model
  
