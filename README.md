# Git 명령어 정리

## 시작하기
### 1. 설치
	https://git-scm.com/

### 2. 버전확인
	git -v

### 3. 사용자 정보
	git config --global user.name "JinwooKing"
	git config --global user.email "wlsdn9489@naver.com"
	
### 4. 설정 확인
	git config --list

### 5. 도움말 보기
	git help config
	git help <verb>

## 저장소 만들기
### 1. 로컬 리포지토리 생성
	git init

### 2. 파일 추적 시작
	git add .

### 3. 파일 커밋
	git commit -m "first commit"

### 4. 브랜치 메인 변경
	git branch -m main

### 5. 원격 리포지토리 등록
	git remote add origin "HTTPS URL"

### 6. 푸시
	git push origin main
	git push <remote> <branch>

### 7. 풀
	git pull origin main
	git pull <remote> <branch>

## ETC

### 1. README.md 파일 생성
	$ echo sampleText > README.md

### 2. gitignore 파일 생성
	$copy con.gitignore
	 sampleText
	 ^z or ^c

### 3. 이미 추적중인 파일 무시하기
	git rm -r --cached .
	git add .
	git commit -m "clear git cache"
	git push -u origin main

### 4. 주의사항
	.gitignore파일에 확장자 붙지 않도록 조심
	ex).gitignore.txt 


