# Build Status -> [![CircleCI](https://circleci.com/gh/sandeepvalapi/Docker/tree/master.svg?style=svg)](https://circleci.com/gh/sandeepvalapi/Docker/tree/master)

# Docker Build Status -> [![CircleCI](https://circleci.com/gh/sandeepvalapi/Docker/tree/master.svg?style=svg)](https://circleci.com/gh/sandeepvalapi/Docker/tree/master)

1. This project uses Maven as build tool. Checkout the project and run below command
> mvn clean install

2. Verify, the build is successful and target folder has a Jar.

3. To build a docker image, run below command
> docker build -t <docker_image_name> .
```This step builds the docker image from dockerfile location```

4. To run created docker image using customized port(verify dockerfile) 
> docker run -p 8080:8080 <imagename>

5. We have integrated it with Circle CI, to build automatically.

