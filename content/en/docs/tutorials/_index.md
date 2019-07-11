---
title: Tutorials
main_menu: true
weight: 60
content_template: templates/concept
---

{{% capture overview %}}

쿠버네티스 문서 중에 이 부분은 자습서를 포함하고 있다.
튜토리얼은 하나의 [학습](/docs/tasks/)을 공부하는 것 보다 더 큰 목표를 성취하는 하는 방법에 대해 보여준다.
일반적으로 하나의 문서는 각각의 절차의 순서대로 여러 개의 부분들로 구성되어 있다.  
각 자습서들을 형식적으로 다루기 전에, 여러분은 나중에 나오는 참고서 부분의 [표준 용어집](/docs/reference/glossary/) 페이지를 북마크하여 등록할 수도 있다.  

{{% /capture %}}

{{% capture body %}}

## 기본사항

* [쿠버네티스 기본사항](/docs/tutorials/kubernetes-basics/)은 쿠버네티스 시스템을 이해하고, 어떤 기본적인 쿠버네티스 특징들을 한번 살펴 볼 수 있도록 여러분을 도와주는 깊이있는 대화형 자습서이다. 
* [쿠버네티스와 함께 확장성있는 마이크로서비스 (Udacity)](https://www.udacity.com/course/scalable-microservices-with-kubernetes--ud615)

* [쿠버네티스 소개하기 (edX)](https://www.edx.org/course/introduction-kubernetes-linuxfoundationx-lfs158x#)

* [안녕하세요? Minikube 입니다.](/docs/tutorials/hello-minikube/)

## 환경설정

* [ConfigMap을 이용한 Redis 설정하기](/docs/tutorials/configuration/configure-redis-using-configmap/)

## 상태가 없는 응용프로그램(Stateless)

* [외부 IP 주소를 하나의 클러스터에서 응용프로그램을 접근하기](/docs/tutorials/stateless-application/expose-external-ip-address/)

* [예제: Redis 와 함께 PHP 방명록 응용프로그램 배포하기](/docs/tutorials/stateless-application/guestbook/)

## 상태가 있는 응용프로그램(Stateful)

* [StatefulSet 기본사항](/docs/tutorials/stateful-application/basic-stateful-set/)

* [예제: 지속적인 볼륨크기로 WordPress 와 MySQL 사용하기](/docs/tutorials/stateful-application/mysql-wordpress-persistent-volume/)

* [예제: 상태가 있는 집합(Stateful Set)들로 Cassandra 배포하기](/docs/tutorials/stateful-application/cassandra/)

* [CP 배포 시스템인 ZooKeeper 실행하기](/docs/tutorials/stateful-application/zookeeper/)

## CI/CD 파이프라인

* [쿠버네티스와 함께 CI/CD 파이프라인 설치하기 제1부: 개요](https://www.linux.com/blog/learn/chapter/Intro-to-Kubernetes/2017/5/set-cicd-pipeline-kubernetes-part-1-overview)

* [쿠버네티스에서 젠킨스 Pod 와 함께 CI/CD 파이프라인을 설치하기 (제2부)](https://www.linux.com/blog/learn/chapter/Intro-to-Kubernetes/2017/6/set-cicd-pipeline-jenkins-pod-kubernetes-part-2)

* [쿠버네티스 상에서 CI/CD 와 함께 분산 크로스워드 퍼즐 앱을 실행하고 확장하기 (제3부)](https://www.linux.com/blog/learn/chapter/intro-to-kubernetes/2017/6/run-and-scale-distributed-crossword-puzzle-app-cicd-kubernetes-part-3)

* [쿠버네티스 상에서 분산 크로스워드 퍼즐 앱을 위한 CI/CD 설치하기 (제4부)](https://www.linux.com/blog/learn/chapter/intro-to-kubernetes/2017/6/set-cicd-distributed-crossword-puzzle-app-kubernetes-part-4)

## 클러스터

* [AppArmor](/docs/tutorials/clusters/apparmor/)

## 서비스

* [소스 IP 이용하기](/docs/tutorials/services/source-ip/)

{{% /capture %}}

{{% capture whatsnext %}}

만일 여러분이 이 자습서를 작성하기 원한다면, 자습서 페이지 형태 및 자습서 템플릿 관련된 정보가 들어 있는 [페이지 템플릿 이용하기](/docs/home/contribute/page-templates/)를 보기 바란다.

{{% /capture %}}
