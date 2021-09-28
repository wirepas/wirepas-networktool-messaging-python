FROM alpine:3.14

ARG base_folder=wnt_examples
ARG packet_name=wirepas-networktool-messaging
ARG project_name=wirepas-networktool-messaging-python
ARG settings_file=settings.yml

RUN apk add --no-cache bash python3 py3-pip git

RUN mkdir ${base_folder}
WORKDIR /${base_folder}

RUN pip3 install ${packet_name}

RUN git clone https://github.com/wirepas/${project_name}.git
WORKDIR /${base_folder}/${project_name}/examples

RUN pip3 install -r requirements.txt

ENTRYPOINT bash
