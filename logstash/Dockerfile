# https://github.com/elastic/logstash-docker
FROM docker.elastic.co/logstash/logstash-oss:5.6.4

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json
RUN bin/logstash-plugin install logstash-codec-json_lines
ADD ./logstash-springboot.conf /etc/logstash/conf.d/

EXPOSE 10000