# Git 명령어 정리
### 전역 설정 정보 조회
* git config --global --list
### 전역 설정 정보 삭제
* git config --global --unset-all user.email
* git config --global --usnet-all user.name
### 현재 git 버전 확인
* git --version
### 새로운 저장소 생성
* git init
### 저장소 복제
* git clone <저장소 url>
### 새로운 원격 저장소 추가
* git remote add <원격 저장소> <저장소 url>
### 새로운 파일 git에 등록 (staging)
* git add <파일>
### 현재까지 작업한 내용 저장
* git commit -m "<메시지>"
### 저장되지 않은 변경사항 조회
* git status
### 기존 파일 새 파일로 이동 (변경이력 유지)
* git mv 파일명 새파일명
### 현재 존재하는 브랜치 조회
* git branch
### 새로운 이름의 브랜치 생성
* git branch <이름>
### 브랜치 A 에서 새로운 브랜치 B 생성
* git branch <B> <A>
### 새로운 원격 저장소 추가
* git remote add <이름> <저장소 주소>
### 추가한 원격 저장소 목록 확인
* git remote
### 원격 저장소 제거
* git remote rm <이름>
### 원격 저장소에서 합치지 않고 지역 브랜치로 변경 사항 가져오기
* git fetch <원격 저장소>
### 원격 저장소에서 변경 사항을 가져와 현재 브랜치에 합치기
* git pull <원격 저장소>
### 새로운 로컬 브랜치를 원격 저장소에 푸싱
* git push <원격 저장소> <지역 브랜치>
