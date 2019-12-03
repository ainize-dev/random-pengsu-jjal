# random-image-api

> A simple random-pengsu-jjal written in PHP.

**Live Version:** https://endpoint.ainize.ai/laeyoung/pengsu-jjal/

[![Run on Ainize](https://ainize.ai/static/images/run_on_ainize_button.png)](https://ainize-cloud-run.web.app/redirect?git_repo=github.com/Laeyoung/random-pengsu-jjal)

## Getting started

#### 1. Clone git repo

`git clone https://github.com/Laeyoung/random-pengsu-jjal.git`

#### 2. Update pengsu-jjal images.

> Img Path: **./assets/images/**

#### 3. Build new docker image

`docker build -t pengsu-jjal .`

#### 4. Run new pengsu-jjal

`docker run -p 8080:80 -d pengsu-jjal`

#### 5. Open [localhost:8080](http://localhost:8080)

## Deploy on Ainize

#### 1. Build docker image for dockerhub

`docker build -t ${YOUR_DOCKER_HUB_ID}/${DOCKER_HUB_REPO_NAME} .`

#### 2. Push docker image to dockerhub

`docker push ${YOUR_DOCKER_HUB_ID}/${DOCKER_HUB_REPO_NAME}`



### Original Repo Author
- **OblivionSan** - [@OblivionSan](https://twitter.com/OblivionSan) | [Discord Server](https://discord.gg/kxNeGRC) | [Website](https://oblivionsan.tk)
