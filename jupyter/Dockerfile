#FROM langchain/langchain:0.1.0
FROM jupyter/minimal-notebook:x86_64-python-3.11.6

RUN mkdir /var/app/
COPY langchain-tutorial.py /var/app/
# Install python requirement packages
COPY requirements.txt /tmp/requirements.txt
RUN pip install -r /tmp/requirements.txt
