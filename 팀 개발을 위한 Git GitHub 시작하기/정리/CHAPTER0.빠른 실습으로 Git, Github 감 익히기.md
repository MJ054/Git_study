# 목차
- Git, 그리고 GitHub
- Git을 설치하고 로컬저장소에서 커밋 관리하기
- GitHub 원격저장소에 커밋 올리기
- GitHub 원격저장소의 커밋을 로컬 저장소에 내려받기

# 1. Git,그리고 GitHub
- 버전관리: 내가 원하는 시점(버전)으로 이동할 수 있게 해 주는 것.
- Git: 소스코드 버전 관리 시스템
- GitHub: Git으로 관리하는 프로젝트를 올려둘 수 있는 Git 호스팅 사이트. 깃허브 외에도 있다.

# 2. Git을 설치하고 로컬저장소에서 커밋 관리하기(add,commit)
- 나 혼자 버전 관리.
- 로컬저장소 만들기: git init
- 커밋 만들기: git add README.txt
              git commit -m "[상세 설명]"
- 커밋 확인: git log
- 커밋 되돌리기: git checkout [커밋 아이디]

# 3. GitHub 원격저장소에 커밋 올리기(push)
- 인터넷에 올려서 함께 버전관리.
- 로컬 저장소에 원격저장소 주소 알려줌: git remote add origin [git주소]
- 원격저장소에 올리기: git push origin master

# 4. GitHub 원격저장소의 커밋을 로컬 저장소에 내려받기
## 4.1. 원격저장소의 커밋을 로컬 저장소에 내려받기(clone)
- git clone [저장소] .
- 저장소 뒤 .을 넣어야 현재폴더 안에 파일이 내려받아진다.
## 4.2. 원격저장소의 커밋을 로컬 저장소에 갱신하기(pull)
- git pull origin master
