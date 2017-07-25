# json-to-db
Parse any JSON object and persist to any database with EclipseLink JPA

I'm starting from a fork of https://github.com/spring-projects/spring-boot/tree/master/spring-boot-samples/spring-boot-sample-actuator.  My goal for this project is to use Jackson to parse any incoming JSON object, then persist it to a database table with EclipseLink JPA.  Sometimes, you just need to read some random JSON from a REST API and save it in a database table for later!
