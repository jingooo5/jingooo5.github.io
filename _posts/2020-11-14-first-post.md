---
layout: post
title:  "프로젝트 진행 상황 1"
date:   2020-11-22
excerpt: "Just about everything you'll need to style in the theme: headings, paragraphs, blockquotes, tables, code blocks, and more."
tag:
- 프로젝트 선정 과정
- pytorch-tutorial
- 2020 OSS
- test
comments: true
---

## 프로젝트 선정 과정

 개인별로 8주차 수업과 9주차 과제를 진행하며 주제로 선정하고 싶은 오픈소스 프로젝트를 정하여 소개한 후, 투표를 통해 팀 주제를 선정하였습니다. 저희 10조는 이태기 팀장님의 의견인 [pytorch-tutorial](https://github.com/yunjey/pytorch-tutorial)을 주제로 선정하게 되었습니다. 해당 주제는 파이썬 딥러닝 모듈인 pytorch를 사용하기 위한 다양한 튜토리얼 예제를 제공해주는 프로젝트로 커뮤니티에 참여하며 머신러닝과 pytorch에 대해 공부할 수 있고, 새로운 pytorch 예제를 추가함으로써 프로젝트 기여도 확실히 할 수 있을 것이라 판단하여 팀 주제로 선정하였습니다.

## 프로젝트 진행상황

 프로젝트를 선정하고, 개인별 기여 방식 및 개선 계획을 정리하여 OSS실습 10주차 과제로 제출하였습니다. 팀 github repository를 만들었으며, 팀원 모두 협업하여 정적 페이지[(https://20-2-skku-oss.github.io/2020-2-OSS-10/)](https://20-2-skku-oss.github.io/2020-2-OSS-10/)를 구성하였습니다.
 이후 커뮤니티 활동 계획을 정하고 우선 개인별로 pytorch tutorial 주제를 정하여 학습하고, 팀원과 피드백을 하기로 정하였습니다.
 

 #### 커뮤니티 활동 계획 정리
 * 11 주차 : basic 각 네트워크 모델 학습 및 피드백
 * 12 주차 : Intermediate 각 네트워크 모델 학습 및 피드백
 * 13 주차 : basic part 예시 추가를 통해 코드 기여 및 테스트 진행
 * 14 주차 : Intermediate 예시 추가를 통해 코드 기여 및 테스트 진행 // 정적 페이지 제작(1)
 * 15 주차 : Intermediate 예시 추가를 통해 코드 기여 및 테스트 진행 // 정적 페이지 제작(2)
 
## 프로젝트 분석 및 개선 방향
 
 `pytorch-tutorial`은 pytorch을 사용하는데 있어 알아야할 기본 지식과 다양한 기능을 정리한 코드를 포함하는 프로젝트입니다. 깃허브 기준 18.8k개의 `star`와 6k번의 `fork`가 진행되었습니다. 
 pytorch 예제 난이도에 따라 basic, intermediate, advanced로 나누어 각 난이도마다 다양한 주제에 대한 pytorch 코드가 존재하며 필요한 경우 데이터파일과 프로젝트를 소개한 .md파일이 존재합니다. `pytorch-tutorial` 사용자는 tutorial 코드를 읽고 사용해보며 pytorch에 대해 학습할 수 있습니다.
  현재 프로젝트는 각 주제마다 하나의 예제 코드만 존재하고, 이용자는 코드의 주석에서만 추가 정보를 얻을 수 있다는 문제점이 있습니다. 저희 팀은 현재 각 주제마다 더 많은 예제 코드를 추가하고, 사용자가 예제를 보고 변형, 활용할 수 있도록 새로운 가이드라인과 문서를 추가하여 프로젝트를 개선할 예정입니다.
  basic난이도는 팀원 모두 함께 참여하여 개선하고, intermediate 난이도는 팀원별로 주제를 정하고 학습하여 해당 주제를 개선할 수 있도록 할 예정입니다.
  
  
## 개발 역량 분석

 pytorch와 딥러닝에 관한 지식은 거의 없지만, 이전에 프로젝트를 하며 간단하게 딥러닝에 대해 공부해 본 적이 있고, tensorflow를 다룬 책을 읽은 적이 있습니다. 해당 경험을 바탕으로 pytorch를 쉽게 공부할 수 있을 것이라 생각합니다. 프로젝트 기여의 주 목표는 새로운 예시 추가이므로 pytorch를 공부하고 직접 사용해보며 tutorial이 필요한 초보자 입장에서 어떤점이 추가되어야 할지 생각해보며 작업할 계획입니다.
 
## 개인 기여 방안
 
 우선 개인별로 inermediate 난이도의 주제를 하나씩 맡아 공부하고, 팀원들에게 피드백을 하고 해당 주제를 개선하기로 하였습니다. 저는 `Feedforward Neural Network`을 공부하기로 했습니다.
 `pytorch-tutorial`을 읽으며 개인적으로 불편했던 점은 예제 코드만 존재하고, 해당 코드에 대한 문서는 따로 존재하지 않는다는 점이었습니다. 초보자들이 `pytorch-tutorial`을 사용하여 pytorch를 쉽게 공부할 수 있도록 코드에 대한 개요와 문법적, 수학적 지식을 문서로 정리하는것이 중요하다고 생각해 해당 부분을 검토해보기로 했습니다.
 또 직접 pytorch와 `pytorch-tutorial`을 사용하여 더 다양한 예시 코드를 작성하여 추가할 예정입니다.
 팀 깃허브와 정적페이지는 팀원이 각각 맡은 부분을 정리하여 보완할 예정입니다.
