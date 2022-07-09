# Git 설정
  ## Git 최초 설정
  - git config --global user.name ""
  - git config --global user.email ""
  ## 로컬저장소의 버전을 원격저장소로 보내기전에 할 일
  - git remote(원격저장소) add origin(origin으로 추가) https://github.com/(username)/(저장소이름).git
  ## 원격저장소로 커밋 올리기/받기
  - git push origin master (올리기)
  - git pull origin master (받기)
  ## 로컬저장소 통으로 가져오기
  - git clone (원격저장소주소 https:// ~ .git)

# Git 오류
  ## Git 저장소 주소 변경하기
  - git remote
    -git remote set-url origin (https://github.com/깃허브아이디/저장소이름.git)
