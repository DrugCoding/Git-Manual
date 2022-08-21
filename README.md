# Git 설정

  ## Git 최초 설정

  - git config --global user.name ""
  - git config --global user.email ""

## Git 시작

- git 으로 관리하고자 하는 폴더에서 터미널을 열고 ``git init`` 입력 후 엔터
- 해당 폴더에서 숨김파일 모두보기를 누르고 봤을 때 ``.git`` 폴더가 생성됐다면 성공

  ## 원격저장소 지정하기
  - git remote(원격저장소) add origin(origin으로 추가) https://github.com/(username)/(저장소이름).git
  ## 원격저장소로 커밋 올리기/받기
  - git push origin master (올리기)
  - git pull origin master (받기)
  ## 원격저장소 통으로 가져오기
  - git clone (원격저장소주소 https:// ~ .git)

  ## Git 저장소 주소 변경하기
  - git remote set-url origin (https://github.com/깃허브아이디/저장소이름.git)
