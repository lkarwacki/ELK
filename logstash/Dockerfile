FROM docker.elastic.co/logstash/logstash:5.5.0

RUN logstash-plugin install logstash-filter-grok
RUN logstash-plugin install logstash-filter-translate
#RUN logstash-plugin uninstall x-pack

#RUN logstash-plugin install  com.floragunn:search-guard-5:5.5.0-14
