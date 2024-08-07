#Install docker on machine -> 

1. Test running as executable. 
2. Schedule as jobs -> Argo workflow 
3. Test running against AI accelerated compute -> AKA jetson, RPI 5 ai kit. etc. 


#Run against  Base image 
docker run --rm -p 8889:8888 -v "$(pwd)/notebooks:/home/jovyan/work" quay.io/jupyter/base-notebook start-notebook.py --NotebookApp.token='my-token' #further improvements

#Run against new Image
Mapping to new image
docker run --rm -p 8889:8888 -v "$(pwd)/notebooks:/home/jovyan/work" nal-xgboost-v0.1 start-notebook.py --NotebookApp.token='my-token' #come back to this for further thinking

#Build image
docker build -t nal-xgboost-v0.1 .
