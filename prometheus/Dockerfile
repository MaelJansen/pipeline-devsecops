FROM prom/prometheus:v2.55.0

COPY prometheus.yml /etc/prometheus/prometheus.yml

CMD ["--config.file=/etc/prometheus/prometheus.yml", \
     "--storage.tsdb.path=/prometheus", \
     "--storage.tsdb.retention.time=15d", \
     "--web.enable-lifecycle"]