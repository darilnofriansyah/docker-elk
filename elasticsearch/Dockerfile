ARG ELK_VERSION

FROM docker.elastic.co/elasticsearch/elasticsearch:${ELK_VERSION}
RUN sudo chown 1000:1000 /usr/share/elasticsearch/data

# Add your elasticsearch plugins setup here
# Example: RUN elasticsearch-plugin install analysis-icu
