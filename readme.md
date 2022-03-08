# Observability

This repository goal is to document the study of observability in microservices. This documentation is divided into three topics:
concepts, objectives and practical projects.

## Concepts

### What is Observability

´A simple way of describing observability is how well you can understand the system from the work it does. In control theory, observability is defined as <b>how engineers can infer the internal states of a system from knowledge of that system's external outputs</b>. Expanded to IT, software, and cloud computing, observability is how engineers can understand the current state of a system from the data it generates. To fully understand, you’ve got to proactively collect the right data, and then visualize it and apply intelligence.´ - https://newrelic.com/topics/what-is-observability

### Monitoring

Monitoring is part of a observability strategy

* Monitoring shows there is something wrong
* Monitoring is about knowing the key metrics of your business
* Monitoring allow us to understand why something is wrong

### Pilars

#### Metrics

Metric is a precise data that represents a info of your system.

##### Technical Metrics

Import data about your application health. Examples:

* Number of available pods
* Cpu usage
* Memory usage
* Error rate

##### Business Metrics

Import data for your business. Examples:

* Trials created
* Transactions performed
* Money amount transactioned
* Amount of active users

#### Logs

Log shows result of an event. You must have a good log solution, otherwise you will lost valuable data.

#### Tracing

Allows engineers to trace an event, and to see the all processes executed and the processes order, inputs and outputs 

## Objectives

### Avaiability

Today is common to have contracts or goals of avaiability. The percentage of avaiability can be different from software to software. But, in order to accomplish these avaiability goal, you must be able to evaluate your system avaiability through time, and also recover fast from problems. This is one objective of implementing observability. To increase the avaiability of your system.

### Compliance

Regulation about user data is increasing in the last few years. And every company has to attend to one or another regulation such as LGPD. A good log solution can help the company to provide proof of compliance. But always have in mind that the sensible data must be anonymized.

### Data Oriented Decision

Observability delivers information about the application. Business and technical information. It helps Product teams to make better decisions about product development.

## Pratical Projects