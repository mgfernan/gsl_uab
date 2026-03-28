FROM debian:12.13-slim

WORKDIR /workspace

RUN apt update \
 && apt install -y wget python3 python3-pip git

COPY requirements.txt /workspace/requirements.txt

RUN python3 -m pip config set global.break-system-packages true \
 && python3 -m pip install -r ./requirements.txt

 RUN wget -O /tmp/quarto.deb https://github.com/quarto-dev/quarto-cli/releases/download/v1.9.36/quarto-1.9.36-linux-amd64.deb \
 && dpkg -i /tmp/quarto.deb \
 && rm /tmp/quarto.deb
