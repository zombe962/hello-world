# hello git

## git 명령어 요약0

- git init
- git reomte add origin <repository address>
- git pull origin master
- git status
- git add .
- git commit -m "message"
- git push origin (master)
- git pull origin master


## git 명령어 요약1

- clone : 원격 저장소 복사
- add: 스테이지 영역에 작업 파일 추가
- commit: 세이브, 스테이지 영역의 파일들을 가지고 커밋(=세이브)를 만들 수 있다.
- push: 원격 저장소에 커밋을 업로드한다. 
- checkout: 수정된 내용을 다시 되돌린다. (코드뭉치 버리기)

## git 명령어 요약2

- git init : git 생성하기
- git pull : git 서버에서 최신 코드 받아와 merge
- git add : 커밋에 파일의 변경 사항을 포함
- git commit -m "커밋 메시지" : 커밋 생성
- git status : 파일 상태 확인

https://velog.io/@delilah/GitHub-Git-%EB%AA%85%EB%A0%B9%EC%96%B4-%EB%AA%A8%EC%9D%8C


## 브랜치 변경하기
- 브랜치: 기존 내용을 유지한 체 새로운 내용을 추가하고 싶을 때 사용한다.
- 체크아웃: 특정 브랜치(혹은 커밋)으로 돌아가고 싶을 때 사용.
- 소스트리의 체크아웃: 브랜치 이름을 더블 클릭하는 것만으로 체크아웃 가능

## 병합하기 1

- 헤드 브랜치에 변경사항이 없고
- 병합 대상 브랜치가 헤드로부터 시작된 경우
- 아주 쉽게 병합 가능 = Fast-forward

## 병합하기 2
- 헤드 브랜치에 추가적인 커밋이 생기는 경우
- 진짜 병합이 필요해 진다.
- 충돌이 안 나면 좋은데, 충돌이 나도 겁내지 말자.