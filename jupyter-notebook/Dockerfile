FROM quay.io/jupyter/scipy-notebook:2024-04-29
RUN conda install -c conda-forge poppler
COPY requirements.txt .
RUN pip install -r requirements.txt
RUN rm requirements.txt
