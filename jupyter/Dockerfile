FROM jupyter/scipy-notebook

COPY  notebooks/PythonDataScienceHandbook/requirements.txt /tmp/requirements.txt
RUN pip install --requirement /tmp/requirements.txt
RUN pip install fastai