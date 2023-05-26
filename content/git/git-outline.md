+++
title = "Git Outline"
date = "2023-05-23T21:29:20+02:00"
tags = ["git", "github", "programming", "oss"]
categories = ["programming"]
banner = "img/banners/git.png"
authors = ["JeongJongMun"]
+++

# 1. Git이란 무엇인가?
***
깃(Git)은 2005년에 개발된 '분산 버전관리 시스템(DVCS)'이다.  
컴퓨터 파일의 변경사항을 추적하고 여러명의 사용자들 간에 파일에 대한 작업을 조율하는데 사용된다.  
(참고: <https://git-scm.com/book/ko/v2> Git 공식 사이트 한글 메뉴얼)  
즉, 주로 여러명의 개발자가 하나의 소프트웨어 개발 프로젝트에 참여할 때, 소스 코드를 관리하는데 주로 사용된다.

# 2. Git의 장점
***
1. 소스코드를 주고 받을 필요 없이, 같은 파일을 여러 명이 동시에 작업하는 병렬 개발이 가능하다.
2. 즉 브랜치를 통해 개발한 뒤, 본 프로그램에 합치는 방식(Merge)으로 개발을 진행할 수 있다.
3. 분산 버전관리이기 때문에 인터넷이 연결되지 않은 곳에서도 개발을 진행할 수 있으며, 중앙 저장소가 날라가버려도 다시 원상복구할 수 있습니다.
4. 팀 프로젝트가 아닌, 개인 프로젝트일지라도 GIT을 통해 버전 관리를 하면 체계적인 개발이 가능해지고, 프로그램이나 패치를 배포하는 과정도 간단해집니다. (pull을 통한 업데이트, patch 파일 배포) 

# 3. Git의 특징
***
1. Distributed development
- 전체 개발 이력을 각 개발자의 로컬로 복사본을 제공하고 변경된 이력을 다시 하나의 저장소로 복사한다.
- 이러한 변경은 추가개발지점을 가져와, 로컬개발 지점과 동일하게 병합(merge)할 수 있다.저장소는 Git protocol 및 HTTP로 쉽고 효율적(특별한 웹서버 구성없이)으로 접근할 수 있다.

2. Strong support for non-linear development
- 신속하고 편리항 branch 및 merge 지원, 비선형(여러갈래) 개발 이력을 시각화하고 탐색 할 수 있는 강력한 도구를 제공한다.

3. Efficient handling of large projects
- Git은 매우 빠르고, 대형프로젝트나 이력이 많은 작업에 매우 합리적이다. Git은 대부분의 다른 버전관리시스템보다 빠르게 요청한다. 그리고 일부 작업에서는 더 빠르게 진행한다.
- 또한, 최근의 정상급 오픈소스 버전관리 시스템보다 장기간의 수정내역을 매우 효율적인 압축방법을 사용한다.

4. Cryptographic authentication of history
- GIt의 이력은  성공한 개발이력의 commit에 의해 개정명으로 저장된다. 일단 그것이 배포되면, 그것을 모르고 예전버전으로 변경하는것은 불가능하다. 또한, 그것들을 암호화 할수 있다.

5 Toolkit design
- UNIX의 전통에 따라, GIT은 C로 작성된 많은 소규모 도구모음이다, 그리고 많은 스크립트들이 기능 보강을 제공한다. Git은 새로운 기발한 작업을 위한 손쉬운 사용과 쉬운 스크립팅을 위한 도구를 제공한다.

# 4. Git과 Github의 차이점
***
- Git : 형상 관리 도구(버전 관리 시스템)
- Github : 형상 관리 도구(버전 관리) 웹호스팅 서비스

## 4-1. Git (형상 관리 도구)
- 프로젝트를 진행하면서 소스 코드를 USB나 메일로 주고받는 건 엄청난 낭비 임과 동시에 보안성 위험이 있다.
- 그렇기 때문에 프로젝트를 진행 함에 있어 형상 관리 도구를 사용 한다. 
- 형상 관리 도구를 사용하면 변경을 쉽게 되돌릴 수 있다. 소스코드를 과거의 특정 시점으로 되돌리거나, 특정 시점의 변경 사항을 취소하거나, 두 버전의 소스 코드를 비교하는 등의 일이 가능하다.

## 4-2. Git 웹 호스팅 시스템
- 협업하고 있는 코드를 저장할 서버가 필요하다.
- 버전 관리 시스템을 지원하는 웹호스팅 서비스의 기능을 통해, push, pull request같은 이벤트에 반응하여 자동으로 작업(배포 등)을 실행하게 할 수 있다.
ex) GitHub, GitLab, BitBucket