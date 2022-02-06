FROM jupyter/scipy-notebook

USER root

RUN conda install --yes --name root psycopg2

RUN pip install collection \
                statistics \
                spellchecker \
                python-string-utils \
                pyspellchecker \
                xgboost

USER jovyan