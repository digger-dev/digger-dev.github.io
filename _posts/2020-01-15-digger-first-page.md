---
layout: post
title: "React + Webpack + Electron <br/> 프로젝트 생성하기"
featured-img: test
categories: [React, Webpack, JavaScript, Electron]
---


# React + Webpack + Electron 프로젝트 생성하기

---
```
Q : 왜 React + Webpack + Electrone 프로젝트가 필요했을까?
A : 개발 효율은 높이고 성능은 강력한 소프트웨어를 제작하기 위해 다음과 같은 구조의 프로젝트를 기획했습니다!
```
---

Digo 서비스를 기획하면서 서버에서도 개인 PC에서도 설치하여 자동화 시킬 수 있는 인공지능 툴을 개발하고자 했습니다.
그래서 Web, JavaScript기반으로 가벼운 GUI서비스를 제작하려고 결정했습니다. 
<br/>

### 1. Electron이란?
---
Electron은 웹기반의 소프트웨어를 단독 프로그램으로 사용할 수 있도록 만드는 플러그인입니다. Chrome기반으로 만들어져 있으면서
개발자가 설정한 페이지만을 View에 그려줍니다. 서버에서 받아올수도 있지만 로컬에 있는 웹 프로젝트를 단독으로 실행 시킬 수 있는
고마운 플러그인입니다.

<div style="width:150px; height:150px; margin-left:auto; margin-right:auto;">
    <img src="../assets/img/posts/electron_logo.png"/>
</div>
