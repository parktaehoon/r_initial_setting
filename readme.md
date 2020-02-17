# 초기 Setting

## github
- 회원 가입

## Web Browser

### Google Chrome 설치
- headings map
- OpenWAX
- Tota11y Plugin, from Khan Academy
- Web Developer

## VS Code + Git 설치

### EXTENTIONS 설치
- Auto Close Tag
- Auto Rename Tag
- Debugger for Firefox
- Korean Language Pack for Visual Studio Code
- Live Server
- Markdown All in One
- Monokai-Contrast Theme
- vscode-icon

### 기본 설정 (Code > 기본설정)
#### 설정
- font : 18
- tabsize : 2칸
- minimap : 해제
#### 바로가기키
- emmit : 수식평가 => shift+command+y
- emmit : 약어로 개별줄 래핑 => shift+command+a
- shift+option+방향키 아래 : 복사
- shift+option+f : 구조 맞춤법 (들여쓰기 등)
- shift+command+k : 해당 줄 삭제
#### 터미널
- 드롭다운 => 기본셀 선택 => bash
- .bash_profile 설정 (교수님께 문의 ㅜㅜ)

## Mac 단축키
- shift+command+. : 숨김파일 보기
- command+space : Sportlight 

## CLI(Command Line interface) 명령어
- cd : 디렉토리 이동
- mkdir : 디렉토리 만들기
- rmdir : 비어있는 디렉토리 삭제
* mv : 이동 및 이름 변경
* cp : 복사
* rm : 파일 및 디렉토리 삭제
* touch : 빈문서 생성
* echo : 내용이 있는 문서 생성
+ clear : 화면 지우기
+ pwd : 현재 디렉토리 위치 조회
+ history : 명령어 히스토리 조회
- command+w : 파일(창) 닫기
- command+q : 파일(창) 종료

## Git 명령어

### 최초 등록
- git config --global user.name "사용자 이름"
- git config --global user.email "사용자 이메일주소"
- git config --list : 설정내용 확인

### git에 저장된 기존 자료 바로 가져오기
- git clone 원격저장소주소 (github에서 주소 복사)

### 신규 폴더 생성
- git init
- git remote add origin "리모트 저장소 URL" (웹사이트에서는 commit 후 입력)
- 파일 생성 (.html .css .md)
- git add . (생성된 모든 파일) or git add 파일명.확장자
- git status (add 된 상태 확인)
- git commit -m "내용" (입력하면 초록색으로 master 보임)
- git log --oneline (commit 된 상태 확인)
- git push origin master -u (github 업로드)