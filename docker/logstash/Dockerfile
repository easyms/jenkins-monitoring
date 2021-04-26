ARG ELK_VERSION

# https://www.docker.elastic.co/
FROM docker.elastic.co/logstash/logstash:${ELK_VERSION}

# Add your logstash plugins setup here
RUN logstash-plugin install logstash-integration-jdbc

COPY ./driver/mysql-connector-java-8.0.23.jar /usr/share/logstash/logstash-core/lib/jars/mysql-connector-java-8.0.23.jar


