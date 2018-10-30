http://localhost:8080/db/default   -->    url/property file name / profile 

need to keep the config server address at the bootstrap.properties as the clint by default loads the 8888 port

In clint the application.name should be the property file name in the git if the file is not application .properties.

if application.properties its been picked up by default with out name

for 2.0 actuator end points are with context path   actuator/refresh
refresh is a post end point

for incliuding end poitns of actuator management.endpoints.web.exposure.include=*
