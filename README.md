#react native 프로젝트 시작
<node.js, jdk, 안드로이드 스튜디오, vscode 설치 필요>

#node.js 설치 확인
-lts 버전 다운
-cmd 창 입력하기
node --version

#파이썬 설치
-2버전 설치 -> 리액트 네이티브에서는 파이썬 2 사용

#jdk 설치
-설치 후 시스템>고급 시스템 설정> 환경변수> 시스템 변수> 새로만들기 통해서 
![image](https://user-images.githubusercontent.com/123061106/229601847-e1c0cafc-29da-45b4-bb2d-ca74a92c576e.png)
![image](https://user-images.githubusercontent.com/123061106/229602021-bd0d24c2-2856-4ea2-b97c-0877e648064d.png)
-cmd 창 입력하기
java -version
javac -version

#안드로이드 스튜디오 설치
-설치 후 시스템>고급 시스템 설정> 환경변수> 사용자 변수> 새로만들기 통해서
![image](https://user-images.githubusercontent.com/123061106/229602547-9f5d4d48-e82b-4084-b208-453f4bacebb9.png)
![image](https://user-images.githubusercontent.com/123061106/229602670-3a664fdb-99a0-4aee-b70a-4cfb4b0e82e3.png)
-cmd 창 입력하기
adb -version



#cmd 창 입력하기
- 프로그램이 잘 설치 된 것을 확인하기
node --version
java -version
javac -version

-expo 설치, 프로젝트 생성(nvm 설치 필요 해당 블로그 참고 : https://seunghyun90.tistory.com/52)
nvm install v12.10.0 (노드)
nvm use v12.10.0 (노드)
npm install -global expo-cli
npm install -g yarn

- expo 웹사이트에서 회원가입 하기 아래 부분은 이후 실행

expo login
expo init 앱이름
blank 선택

-expo 프로젝트 실행
cd 앱이름
npm start 
-> 오류발생 unhandled promise rejection waring error : cannot find modul 'fs/promises'
------------------------------------------------------------------------------------------------------------------
오류 해결 방법 : node.js 버전을 14이상으로 해주기 그런데 nvm 때문에 다운그레이드 한것인데 어떡하지?
cmd 창에 nvm list 검색시 v18.15.0 사용 가능한 것으로 보여 버전을 업그레이드 해보자
![image](https://user-images.githubusercontent.com/123061106/229605192-62d08a88-61eb-42e5-b7ef-fb3b2a726fd1.png)
cmd 창에서 node 다른 버전 다운 받기
nvm list
nvm list available
nvm install 사용할 버전
nvm use 사용할 버전
-> v18.15.0 변경
오류 해결
------------------------------------------------------------------------------------------------------------------
