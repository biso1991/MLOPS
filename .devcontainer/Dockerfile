FROM mcr.microsoft.com/devcontainers/universal:2-linux


COPY requirements.txt  /tmp/requirements.txt

RUN pip install -r /tmp/requirements.txt \
&& rm -rf /tmp/requirements.txt

