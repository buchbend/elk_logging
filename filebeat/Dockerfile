FROM docker.elastic.co/beats/filebeat:7.5.1
COPY ./filebeat.yml /usr/share/filebeat/filebeat.yml
USER root
RUN chown root:root /usr/share/filebeat/filebeat.yml &&\
    chmod 600 /usr/share/filebeat/filebeat.yml
