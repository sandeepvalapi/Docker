# Docker Build Status -> [![CircleCI](https://circleci.com/gh/sandeepvalapi/Docker/tree/master.svg?style=svg)](https://circleci.com/gh/sandeepvalapi/Docker/tree/master)

1. Do maven build using 
mvn clean install

2. Check target folder for jar

3. docker build -t <imagename> .

4. docker run -p 8080:8080 <imagename>
