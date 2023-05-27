+++
title = "컨테이너 개념"
date = "2015-06-24T13:50:46+02:00"
tags = ["theme"]
categories = ["starting"]
description = "This tutorial will show you how to create a simple theme in Hugo. I assume that you are familiar with HTML, the bash command line, and that you are comfortable using Markdown to format content."
banner = "img/banners/banner-1.jpg"
authors = ["Jane Doe"]
+++

## 컨테이너 
• OS 커널을 여러 개의 격리된 공간으로 격리(Isolation)하여 독립적인 여러 개의 시스템처럼 사용하는 가상화   
• 호스트 OS의 커널을 공유하며 OS를 새로 설치하지 않음   
• 커널을 공유하는 방식이기 때문에 실행 속도가 빠르고, 성능 상의 손실이 거의 없음   
• 사용자에게는 가상 머신처럼 보임   
• 다른 OS를 사용할 수 없음   

## 컨테이너 이미지란  
• 컨테이너 실행을 위한 일종의 템플릿 파일, 그림 파일 아님   
• 소스 코드, 라이브러리, 종속성, 도구 및 응용 프로그램을 실행하는데 필요한 기타 파일을 포함하는 불변(변경 불가) 파일   
• 읽기 전용 파일이며 스냅샷이라고도 함   
• 특정 시점의 애플리케이션과 가상환경을 포함   
• 하나의 이미지 파일을 가지고 여러 개의 컨테이너를 실행할 수 있음   


