---
layout: post
title: "Docker를 처음 사용하는 방법"
featured-img: dockerused
categories: [Docker]
---


# Docker(도커)를 처음 사용하는 방법

---

### 1. Docker 이미지 검색
---
Docker 이미지는 Docker 허브(https://hub.docker.com/)에 저장되어 있는데 docker search [사용하고자 하는 라이브러리 이름] 형식으로 검색할 수 있습니다.  

```bash
$ docker search ubuntu
```
위 명령어를 실행하면 

![img](../assets/img/posts/docker-used0.png)

그림과 같이 ubuntu와 관련되는 이미지들의 리스트를 확인할 수 있습니다.
<br/><br/>

[사용하고자 하는 라이브러리 이름]는 라이브러리의 이름과 Tag로 구성되어 있습니다. Tag를 통해 자신이 사용하고자 하는 버전을 검색할 수 있습니다. 
```bash
docker search ubuntu:latest
```
위 명령어와 같이 ubuntu뒤에 있는:latest 가 태그 입니다. 태그를 사용하면 그 버전에 관해서만 검색할 수 있습니다. 

### 2. Docker 이미지 받기
---

Docker 이미지를  받기 위해서는 pull명령어를 사용하는데pull 명령어를 사용해 이미지를 받습니다. 
```bash
docker pull emcconkey/apache-php
```

