# https://github.com/elastic/elasticsearch-docker
FROM docker.elastic.co/elasticsearch/elasticsearch-oss:6.3.0

# Add your elasticsearch plugins setup here
# Example: RUN elasticsearch-plugin install analysis-icu
RUN elasticsearch-plugin install https://github.com/NLPchina/elasticsearch-sql/releases/download/6.3.0.0/elasticsearch-sql-6.3.0.0.zip
