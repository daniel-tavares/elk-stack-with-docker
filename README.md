# elk-stack-with-docker
ELK Stack with docker


# CRIAÇÃO DOKER ELASTICSEARCH

- docker pull docker.elastic.co/elasticsearch/elasticsearch:6.0.1

- docker run -p 9200:9200 -p 9300:9300 -e "discovery.type=single-node" docker.elastic.co/elasticsearch/elasticsearch:6.0.1
