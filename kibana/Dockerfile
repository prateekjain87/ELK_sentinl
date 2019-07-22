ARG ELK_VERSION

# https://github.com/elastic/kibana-docker
FROM docker.elastic.co/kibana/kibana:6.5.4
# Add your kibana plugins setup here
RUN kibana-plugin install https://github.com/sirensolutions/sentinl/releases/download/tag-6.5.0-0/sentinl-v6.5.4.zip