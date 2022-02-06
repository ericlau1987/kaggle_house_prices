FROM jupyter/scipy-notebook

USER root

RUN conda install --yes --name root psycopg2 \
    sqlalchemy \
    scikit-learn \
    statistics \
    seaborn \
    matplotlib \
    collections \
    string \
    spellchecker

USER jovyan