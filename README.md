# GenAI-Streaming
Projeto Streaming GenAI


# document-streaming
Repository for the Document streaming capstone projects

Outlook:

- Deploy the streamlit app as docker (build and add in dockerfile)
- Deploy the whole platform with all containers on a cloud platform of your choice
- Add an API between Streamlit and MongoDB so that Streamlit doesnt have to be directly connected with MongoDB (User& Password)

#  Links to deploy the streamlit app as docker container
#https://maelfabien.github.io/project/Streamlit/#the-application
#https://towardsdatascience.com/how-to-deploy-a-semantic-search-engine-with-streamlit-and-docker-on-aws-elastic-beanstalk-42ddce0422f3

# Docker needed

# Docker Compose up commands and Kafka Comands:

docker-compose -f .\docker-compose-elastic.yml up -d

Apos ativar o docker;
./kafka-console-consumer.sh --topic ingestion-topic --bootstrap-server localhost:9092
./kafka-console-consumer.sh --topic spark-output --bootstrap-server localhost:9092

