# Build Status -> [![CircleCI](https://circleci.com/gh/sandeepvalapi/Docker/tree/master.svg?style=svg)](https://circleci.com/gh/sandeepvalapi/Docker/tree/master) [![Maintainability](https://api.codeclimate.com/v1/badges/9861a7505855f4cb0519/maintainability)](https://codeclimate.com/github/sandeepvalapi/Docker/maintainability) [![Test Coverage](https://api.codeclimate.com/v1/badges/9861a7505855f4cb0519/test_coverage)](https://codeclimate.com/github/sandeepvalapi/Docker/test_coverage) <a href="https://img.shields.io/badge/Developer-Sandeep-yellowgreen.svg"><img src="https://img.shields.io/badge/Developer-Sandeep-yellowgreen.svg" /></a>

1. This project uses Maven as build tool. Checkout the project and run below command
> mvn clean install

2. Verify, the build is successful and target folder has a Jar.

3. To build a docker image, run below command
> docker build -t <docker_image_name> .
```This step builds the docker image from dockerfile location```

4. To run created docker image using customized port(verify dockerfile) 
> docker run -p 8080:8080 <imagename>

5. We have integrated it with Circle CI, to build automatically.

