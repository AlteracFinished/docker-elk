# https://github.com/elastic/logstash-docker
FROM docker.elastic.co/logstash/logstash:5.6.8

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json
RUN bin/logstash-plugin install logstash-codec-json_lines

EXPOSE 10000