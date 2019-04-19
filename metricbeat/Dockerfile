FROM docker.elastic.co/beats/metricbeat:7.0.0
COPY metricbeat.yml /usr/share/metricbeat/metricbeat.yml
USER root
RUN chown root:metricbeat /usr/share/metricbeat/metricbeat.yml
RUN chown -R root /usr/share/metricbeat/
RUN chmod -R go-w /usr/share/metricbeat/
USER metricbeat
