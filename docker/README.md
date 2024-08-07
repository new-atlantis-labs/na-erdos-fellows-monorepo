#Install docker on machine -> 

1. Test running as executable. 
2. Schedule as jobs -> Argo workflow 
3. Test running against AI accelerated compute -> AKA jetson, RPI 5 ai kit. etc. 

docker run --rm -p 8889:8888 -v "$(pwd)/notebooks:/home/jovyan/work" quay.io/jupyter/base-notebook start-notebook.py --NotebookApp.token='my-token'
