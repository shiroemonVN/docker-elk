FROM logstash:latest

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json 
RUN logstash-plugin install logstash-input-beats
RUN logstash-plugin install logstash-input-gelf
RUN logstash-plugin install logstash-input-syslog
RUN logstash-plugin install logstash-filter-json
RUN logstash-plugin install logstash-output-elasticsearch
RUN logstash-plugin install logstash-output-redis
RUN logstash-plugin install logstash-codec-multiline
RUN logstash-plugin install logstash-codec-rubydebug
RUN logstash-plugin install logstash-codec-line
RUN logstash-plugin install logstash-codec-plain
RUN logstash-plugin install logstash-codec-json
RUN logstash-plugin install logstash-filter-alter
RUN logstash-plugin install logstash-filter-aggregate
RUN logstash-plugin install logstash-filter-date
RUN logstash-plugin install logstash-filter-geoip
RUN logstash-plugin install logstash-filter-json
RUN logstash-plugin install logstash-filter-grok
RUN logstash-plugin install logstash-filter-mutate
RUN logstash-plugin install logstash-filter-syslog_pri
RUN logstash-plugin install logstash-filter-useragent