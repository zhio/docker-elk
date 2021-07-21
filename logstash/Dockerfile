ARG ELK_VERSION

# https://www.docker.elastic.co/
FROM docker.elastic.co/logstash/logstash:${ELK_VERSION}

COPY ./mysql-connector-java-8.0.11.jar /usr/share/logstash/logstash-core/lib/jars/
COPY ./temp /usr/share/logstash/temp
# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json

# RUN echo y | logstash-plugin install logstash-input-jdbc