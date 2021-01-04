# nodeJs_tutorial : 기본 nodeJs
  1. 다운로드
  * https://nodejs.org/ko/download/
  2. 설치 확인
  * npm version(터미널)
  	* npm(node package manager) : 자바스크립트 패키지 매니저이다. Node.js에서 사용할 수 있는 모듈들을 패키지화하여 모아둔 저장소
	* Node.js에서 사용할 수 있는 모듈인 패키지를 설치할 때에는 npm install 명령어 뒤에 설치할 패키지 이름을 지정한다.
  3. nodeJs 예제
  * 터미널 프로젝트 생성을 원하는 경로 이동 npm init (nodeJs 기본 실행 패키지정보를 만들어줌) 또는 package.json 을 생성 프로젝트경로/package.json 에 넣어서 사용 npm init [react or react-create-app or ....] 여러 라이브러리 기본 프로젝트 기본 구성으로 만들어줌 인터넷 참고
  * 실행
  	npm start
	init 으로만 생성 시 package.json 에 스크립트를 실행할 수 있게 추가해야함
	"scripts": {
	"start": "node 실행을원하는.js"(nodeJs 라이브러리 를 사용하여 js 실행)
	}
	예제파일 생성 (프로젝트 경로)/App.js <-("start": "node App.js")
	App.js
	consoel.log("hellow~ nodeJs npm start");
