FROM tensorflow/tensorflow

RUN apt update \
    && apt upgrade -y \
    && apt install -y curl build-essential git vim

RUN apt install graphviz graphviz-dev

COPY requirements.txt /tmp/requirements.txt
WORKDIR /tmp
RUN pip install -v -r requirements.txt