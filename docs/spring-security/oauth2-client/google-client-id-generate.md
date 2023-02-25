---
layout: default
title: Google 클라이언트 ID, 시크릿 발급
parent: OAuth2 Client
grand_parent: Spring Security
nav_order: 1
---

# Google Client ID, Secret 발급
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---



### Google 클라우드 플랫폼에서 프로젝트 생성

[https://console.cloud.google.com/](https://console.cloud.google.com/) 에 접속한다.

<br>



상단 새프로젝트 버튼 클릭

![1](./img/GOOGLE-PLATFORM-REGISTRATION/1.png)



<br>

프로젝트 명을 입력해서 만들기 버튼 클릭해서 프로젝트를 생성한다. 프로젝트가 모두 생성될 때 까지 몇 분 정도 걸린다.

![1](./img/GOOGLE-PLATFORM-REGISTRATION/2.png)



<br>



### OAuth 동의 화면 구성

- OAuth 클라이언트 ID 를 만들기를 하는 도중에 oAuth 동의 화면이 구성되어 있지 않은 경우 OAuth 동의 화면 구성 작업을 먼저 시작한다.
- 주로 OAuth 를 처음 연동해보는 경우에 적용된다.



![1](./img/GOOGLE-PLATFORM-REGISTRATION/3.png)



<br>

![1](./img/GOOGLE-PLATFORM-REGISTRATION/4.png)



<br>



![1](./img/GOOGLE-PLATFORM-REGISTRATION/5.png)

<br>

![1](./img/GOOGLE-PLATFORM-REGISTRATION/6.png)

<br>



![1](./img/GOOGLE-PLATFORM-REGISTRATION/7.png)

<br>



![1](./img/GOOGLE-PLATFORM-REGISTRATION/8.png)

<br>



![1](./img/GOOGLE-PLATFORM-REGISTRATION/9.png)

<br>



![1](./img/GOOGLE-PLATFORM-REGISTRATION/10.png)

<br>

테스트 사용자 생성

![1](./img/GOOGLE-PLATFORM-REGISTRATION/11.png)

<br>



![1](./img/GOOGLE-PLATFORM-REGISTRATION/12.png)

<br>



![1](./img/GOOGLE-PLATFORM-REGISTRATION/13.png)

<br>



### OAuth 사용자 인증정보 생성 (Client Id, 시크릿 생성)

![1](./img/GOOGLE-PLATFORM-REGISTRATION/14.png)

<br>



여기서 입력한 리다이렉션 URI는 애플리케이션 서버 소스코드 내의 Controller 에서 redirection url 로 mapping 을 꼭 해줘야 한다.

![1](./img/GOOGLE-PLATFORM-REGISTRATION/15.png)

<br>



OAuth 클라이언트 생성완료 된 화면.

![1](./img/GOOGLE-PLATFORM-REGISTRATION/16.png)





