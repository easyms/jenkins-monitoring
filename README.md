# jenkins monitoring
A poc validating jenkins monitoring based on statistics-gatherer plugin (https://plugins.jenkins.io/statistics-gatherer/) and ELK stack.


# Summary of set up
+ Install Docker
+ Activate Jenkins
+ Install statistics-gatherer plugin
+ Congigure logstash http endpoints in statistics-gatherer plugin
+ Launch jenkins sample jobs
+ Get jenkins build, queues and projects data in elastcsearch
