FROM jupyter/datascience-notebook

RUN pip install pandas

COPY assignment(1).ipynb /home/jovyan/work/

WORKDIR /home/jovyan/work

CMD ["jupyter", "notebook", "--ip='0.0.0.0'", "--port=8888", "--no-browser", "--allow-root", "--NotebookApp.default_url=/notebooks/assignment(1).ipynb"]