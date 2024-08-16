FROM jupyter/base-notebook
COPY requirements.txt /home/jovyan/work
WORKDIR /home/jovyan/work
RUN python -m pip install --no-cache -r requirements.txt
