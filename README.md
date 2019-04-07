# git 사용법

1. $ git init
2. $ git add .
3. $ git commit -m "작성"
4. $ git remote add origin '깃 주소'
5. $ git config --list
  - 이곳에서 이메일과 이름이 입력되어 있는지 확인한다.
    - user.email=깃 이메일주소
    - user.name=깃 아이디
  - 나가고 싶을 때는 shift + ':' 와 'q'를 입력하면 나가진다.
6. $ git config user.email 깃 이메일주소
  - 위에서 확인시 이메일이 입력되어 있지 않으면, 깃 이메일주소 입력한다.
7. $ git config user.name 깃 아이디
  - 위에서 확인시 이름이 입력되어 있지 않으면, 깃 아이디를 입력한다.
8. git push -u origin master
  - 깃에 올린다.
  - 만약, Repository not found. 문구가 뜨면
    - $ git remote set-url origin "https://깃아이디@github.com/깃아이디/레포지토리.git"
