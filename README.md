# ELK Stack Dockercompose 🦌

> This project is to create a simple Dockercompose file that will spin up and connect
> all the core pieces of an [ELK](https://www.elastic.co/what-is/elk-stack) stack for testing and learning on.


# Core Pieces 🧩

## [Elasticsearch](https://www.elastic.co/elasticsearch/) 🧠

> Sitting at the center of the core ELK stack is [Elasticsearch](https://www.elastic.co/elasticsearch/), this is your ctl+f, calculator, and Excel all in one.
> It gives you the tools to search through your stored data, preform analytical calculations, and way more!

## [Logstash](https://www.elastic.co/logstash) 🚐

> This is what delivers your many streams of data to Elasticsearch, [Logstash](https://www.elastic.co/logstash) not only delivers your precious data but it also
> refines and processes the data in it's input streams to make your life easier before it even touches Elasticsearch!

## [Kibana](https://www.elastic.co/kibana) 🎀

> Trying to visualize things while only looking at the raw data is not the easiest, I think we can all agree on that, and lucky for you 
> that is where [Kibana](https://www.elastic.co/kibana) comes in! Kibana allows for beautification and easy visualization of your data for every occasion,
> but that's not all it can do. You can also create dashboards for easy to read storyboards and trend driven analysis!

## [Beats](https://www.elastic.co/beats/) 🐝

> Now while currently not in this project it would be wrong to not mention [Beats](https://www.elastic.co/beats/) while talking about the core ELK stack.
> This is not a singlular unit but rather a family of data shippers that can work on nearly any server or machine that you throw them at. 
> These are the worker bees for the ELK stack, they are what collects and sends out the data for you to work with!
