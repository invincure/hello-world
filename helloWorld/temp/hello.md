#Hellow

##git명령어
- clone : github원격 저장소를 로컬로 복사
- add : 스테이지 영역에 작업파일 추가
- commit : 스테이지 영역의 파일들을 로컬 레파지토리에 저장하고, 커밋을 만든다
- push : 커밋들을 원격 저장소에 업로드

##Comment Branch
- branch : 기능
- checkout : 저장소에서 특저 커밋이나 브랜치로 가고실을때 사용
- HEAD : 현재 작업중인 브랜치 = HEAD브렌치

##Issue 기능 추가
- 개발 SR이 요청될때마다 새로운 Issue를 발급한다.
- issue하나당 하나의 branch를 생성하여 개발한다.이때 master브랜치가 아닌, develop브랜치 하위에 새로운 브랜치를 생성하여 개발을 진행한다.
-개발이 완료되면, develop브랜치에 push하고, PR(Pull Request)을 통해 리뷰를 요청한다.
-reviewer 가 confirm 해주면, master 브랜치로 push하여 product 환경에 배포를 진행한다.
-master 브랜치로의 push는 github 또는 gitlab에서 일괄지원됨.   