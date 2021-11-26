---
layout: page
title: Résumé
subtitle: You can find out what I have done here :)
---

<span style="float: right; "><a href="{{ '/assets/resume.pdf' | prepend: site.baseurl }}"><strong>> Download as PDF</strong></a> </span>
<br>

## SUMMARY

`4+ years experience working closely with software engineering, especially Restful API design. `

- Experienced programming on different languages: Java, Python, Groovy, Golang, and Javascript.
- Strong knowledge of design patterns, concurrency, multithreading, lambda in Java
- Experienced on various frameworks: Spring Boot, Netty, Hibernate, React, and NodeJS.
- Experienced on distributed computing protocols like REST, WebSocket, Protobuff, and gRPC.
- Experienced working SQL and NoSQL(Redis & DynamodDb).
- Experienced on AWS cloud infrastructures like Lambda, ECS, EC2, dynamodb and Elasticache

## EDUCATION

**University of San Francisco (USFCA)** <span style="float: right; ">Aug. 2019 - May. 2021</span> <br/>
Master of Science in Computer Science <span style="float: right; ">GPA: 3.97/4</span>

- Concentration: Software Engineering
- Relevant Cources: Algorithms, Principles SW Development, Systems Foundations, Data Processing in Cloud, Machine Learning, Big Data, Programming Language Paradigms, Software Development Life Cycle.

**National Yunlin University of Science and Technology, Taiwan** <span style="float: right; "> Sep. 2013 - Jun 2017.</span> <br/>
Bachelor of Computer Science <span style="float: right; ">GPA: 3.1/4</span>

## EXPERIENCE

**Software Engineer** at Innova Solutions <span style="float: right; ">May. 2021 - present</span>

_Working with the Change Heathcare to build pratical heath insurance service._

- Developed a batch process handling a large amount of data using Spring Batch and Java Concurrency Strategy
- Developed serverless solutions majorly using AWS lambda, SNS, SQS

_Used Knowledge of Java & Python, Spring Boot, Spring Batch, AWS state machine, lambda, ECS, EC2, load balancer, Dynamodb, etc_

**Software Developer** at 玉山銀行(E.SUN Bank) <span style="float: right; ">Jan. 2019 - Jun. 2019</span>

_Worked alongside a big team(~50 people) to implement a huge, microservice-based backend system of banking applications._

- Involved system design on the E-Collection(online bill payment) application.
- Used Spring Boot to handle requests from differernt protocols, and implemtend buisness logics on the backing process included money transfer, innercoounting and E-Collection.
- Implemented stored procedures on Oracle PL/SQL to process data-side logics.

_Used Knowledge of Java, Spring Boot, Oracle Stored Procedure._

## PROJECTS

**Patient Roster**. <span style="float: right; ">2021, Innova Solutions</span>

- Receive a request data which has up to 1 million rows.
- Parse and validate every row.
- Request each row to FHIR api
- Retrieve patient document once FHIR published a pipeline end event.
  Spring Boot, Spring batch, ECS, Lambda, S3, SNS, SQS, DynamodDb

**Waterflow** - A easy to use microservices deploy web page. <span style="float: right; ">2021, USFCA</span>

Worked in a team of 9 to create an easy-to-use micro-services deployment system

- Architecture designers are able to design micro-services based on BPMN 2.0 model, and assign each tasks to developers.
- Developers make AWS ECR images and provide the sources to the Waterflow, the system will validate these images.
- When the all micro-services are ready, the designers can decide to enable the workflow, and the Waterflow will deploy all services on Zeebe.
  Bpmn.io, Micronaut, Groovy, React, Elasticsearch, AWS ECR & ECS

**Pocket Realtor** - Better Airbxb? <span style="float: right; ">2020, Master's project of USFCA</span>

- https://github.com/mchen81/pocket-realtor-backend
- Pocket Realtor provides a web service for homeowners, real estate agents, and people seeking to
  make the process of renting housing with friends more seamless.
- Homeowners will have a page to post the house(s) which they would like to sell or rent.
- Tenants will discover useful information about available properties to rent in their area, such as square footage, rent price, nearby amenities, and more
- Tenants are able to create a group with their friends so that they can share information about
  their rental choices with one another and find a place that is the best fit.

NodeJS, Express, Sequelize, JWT, PostgreSQL, AWS EC2 & RDS

**Distributed Storage System** - <span style="float: right; ">2020, BigData course from USFCA</span>

- https://github.com/mchen81/DFS-java-netty
- Like [Hadoop Distributed Storage System](https://hadoop.apache.org/), it provides a storage place to keep avalibility for data.
- Make every chunk of data has 3 replicas distributed around cluster
- Make a backup if detecting a chunk is broken

Java And Netty

**Buy-Tracker** - A web app tracking what you've payed. <span style="float: right; ">2019</span>  
When I was first in the US, I tried to write down my spending in some mobile app. It's painful bucause typing lots of items and prices from reciptes didn't make sense. I realized I could write an app to help me achieve that - ocr. Taking a phto then tracking is done - how beautiful it is. Therefore, I built this app and got famaliar with Spring Boot.

_But it didn't help a lot since I gotta take a really clear image. Even worse, it a web page but not a mobile app._

**Security system of open field with cloud computing, drone and robot** - Bachelor's Project <span style="float: right; ">2016, Bachelor's project of YUNTECH</span>

Worked in a team of three to create a security system for large open spaces, such as parks using
Raspberry Pi, drones and Hadoop.

_Since this is my first time to complete such big project, the code was really disgusting..._
