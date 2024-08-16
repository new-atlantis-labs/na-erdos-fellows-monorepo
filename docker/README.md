#Run against  Base image 
docker run --rm -p 8889:8888 -v "$(pwd)/notebooks:/home/jovyan/work" quay.io/jupyter/base-notebook start-notebook.py --NotebookApp.token='my-token' #further improvements

#Build image
docker build -t nal-xgboost-v0.1 .


#Run against new Image
Mapping to new image
docker run --rm -p 8889:8888 -v "$(pwd)/notebooks:/home/jovyan/work" nal-xgboost-v0.1 start-notebook.py --NotebookApp.token='my-token' #come back to this for further thinking

