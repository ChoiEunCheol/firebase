### 0. 프로젝트 생성
- 로컬 디렉토리 생성 or github repository
### 1. app.js 
- 파일 생성
### 2. npm init
- 패키지 관리 초기화
### 3. 디버거 설치
- ctrl + shift + D
-------

#### 4. firebase 설치 준비
- 시스템 당 첫번째 작업은 글로벌(마치 시작프로그램 처럼)로 설치해야 한다.
- firebase는 구글에서 서비스 중이므로 구글 아이디가 필요하다.

### 5. firebase 설치
`npm install -g firebase-tools`
- 여기서 -g는 global 설치를 뜻한다.
- 글로벌 설치 이므로 프로젝트 패키지와는 아직 관련이 없다.
- 위의 명령을 통해 설치하면, `firebase` 라는 명령어를 사용할 수 있다.
`firebase --help`
`firebase --version`
위와 같은 간단한 조회 명령으로 정상적으로 명령이 되는지 확인한다.

### 6. firebase 로그인
- CLI 이긴하지만, 엄연히 계정권한이 필요하므로 로그인을 진행해야 한다.
`firebase login`
- 위의 로그인 명령어를 작성, 실행하면 아래 와 같은 승인 관련 요청이 발생한다.

### 7. firebase 구글 계정 승인 처리
? Allow Firebase to collect CLI and Emulator Suite usage and error reporting information? (Y/n) 
- firebase에 사용량과, 오류 보고와 같은 정보 수집을 허용 하시겠습니까?
- 정보 수집 동의이므로 Y로 응답한다. 
- 동의하는 순간 브라우저가 열리면서 로그인을 요구한다.
? 계정 엑세스 창이 활성화되며, 허용을 선택한다.
허용한다면
+  Success! Logged in as kongukjae@gmail.com <- 다음과 같은 로그가 CLI 화면에 응답된다.

### 8. 유지보수를 위해 프로젝트 디렉토리를 하위로 하나를 만든다.
- 예제의 경우 app이라는 디렉토리를 만들었고, 그 하위로 public 이라는(index.html을 담기위한) 디렉토리를 간단하게 구성했다.
- 최초 테스트이므로, index.html에 h1 태그 정도만 작성했다.


