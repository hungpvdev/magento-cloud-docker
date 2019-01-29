FROM docker.elastic.co/elasticsearch/elasticsearch:5.2.2

RUN echo "xpack.security.enabled: false" >> /usr/share/elasticsearch/config/elasticsearch.yml

RUN bin/elasticsearch-plugin install analysis-phonetic

RUN bin/elasticsearch-plugin install analysis-icu

RUN bin/elasticsearch-plugin install analysis-smartcn

RUN bin/elasticsearch-plugin install analysis-stempel

EXPOSE 9200 9300
