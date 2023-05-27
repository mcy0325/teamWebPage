+++
title = "컨테이너 명령어 정리"
date = "2021-08-01T21:29:20+02:00"
tags = ["golang", "programming", "theme", "hugo"]
categories = ["programming","lorem","pseudo"]
banner = "img/banners/banner-4.jpg"
authors = ["John Doe"]
+++

### 도커 컨테이너 시작   
컨테이너 생성 - docker create   
컨테이너 시작 - docker start   
컨테이너 생성 후 시작 - docker run   

### 도커 컨테이너 종료   
컨테이너 종료 - docker stop   
컨테이너 강제 종료 - docker kill   

### 도커 컨테이너 목록 확인하기   
실행중인 컨테이너 상태 확인 - docker ps      
전체 컨테이너 상태 확인 - docker ps -a      
컨테이너 상세 정보 확인 - docker inspect    

### 도커 컨테이너 삭제   
컨테이너 삭제 - docker rm       
컨테이너 강제 종료 후 삭제 - docker rm -f       
컨테이너 실행 종료 후 자동 삭제 - docker run --rm       


