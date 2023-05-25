+++
title = "Git Command"
date = "2023-05-23T13:50:46+02:00"
tags = ["git", "github", "programming", "oss"]
categories = ["programming"]
banner = "img/banners/command.jpg"
authors = ["JeongJongMun"]
+++

# Command
Git에서 주로 사용하는 명령어들을 정리해보았습니다.  

## Git 기본 명령어

**현재 상태 확인**
```
git status
```

**원격 저장소와 연결 확인**
```
git remote
```

**git 저장소 생성하기**
```
git init
```

**git 저장소 Clone**
```
git clone [URL]
```

**git저장소에 코드 추가**
```
git add
```

**커밋 생성**
```
git commit -m "message"
```

**변경 사항 저장소에 푸시**
```
git push
```

**원격 저장소의 변경 사항 확인**
```
git fetch
```

**원격 저장소의 변경 사항 가져오기**
```
git pull
```


## Git Branch 관련

**브랜치 생성**
```
git branch [name]
```

**브랜치 이동**
```
git checkout [name]
```

**브랜치 확인**
```
git branch
```

**브랜치 삭제**
```
git branch -d [name]
```