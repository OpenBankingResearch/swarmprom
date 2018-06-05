FROM prom/alertmanager:latest

COPY conf /etc/alertmanager/

ENTRYPOINT  [ "/bin/alertmanager" ]
CMD        [ "--config.file=/etc/alertmanager/alertmanager.yml", \
             "--storage.path=/alertmanager" ]
