# how_use_git

# git 사용법

## 프로젝트를 remote repository와 연동하기
    * remote repository를 만든다
    * local repository를 만든다.
    * local repository에 remote repository 주소를 등록한다.
    * 파일을 만든다.
    * git commit을 한다.
    * git push를 한다.

## remote repository 만들기
  * git에 가입하고
  * e-mail인증을 하고
  * 로그인을 한 후
  * 프로젝트를 만든다.
  

## local repository(로컬 리포지토리)만들기
  * mkdir <프로젝트명>
  ex) mkdir how_use_git

  * git init
  * git add README.md
  * git commit -m "first commit"
  * git remote add origin https://github.com/Kyeongrok/how_use_git.git
  * git push -u origin master

## local repository란?
    * git init을 한 상태가 local repository이다.
    * project root에 git init을 한다.

## remote repository란?
    * github, bitbucket, aws codecommit 등 온라인 저장소
    * remote라고 한다.

## clone하는 법
    * remote git repository 주소를 복사 한다.
    * git clone <복사한주소>
    * 위 명령어를 쓴다.
  
## ws와 git을 연동 시키려면?
    * remote repository를 만든다
    * local repository를 만든다.
    * local repository를 remote repository에 올린다.
    
## commit이란?
    * 업데이트 - 프로젝트에 수정한게 있으면 commit한다