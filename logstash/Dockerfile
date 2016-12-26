FROM logstash:5

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json
RUN logstash-plugin install logstash-input-beats \
logstash-input-gelf \
logstash-input-syslog \
logstash-filter-json \
logstash-output-elasticsearch \
logstash-output-redis \
logstash-codec-multiline \
logstash-codec-rubydebug \
logstash-codec-line \
logstash-codec-plain \
logstash-codec-json \
logstash-filter-alter \
logstash-filter-aggregate \
logstash-filter-date \
logstash-filter-geoip \
logstash-filter-json \
logstash-filter-grok \
logstash-filter-mutate \
logstash-filter-syslog_pri \
logstash-filter-useragent