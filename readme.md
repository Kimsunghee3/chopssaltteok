### git 사용법
- github에서 repository 생성 후
```sh
# .git폴더 생성(git을 사용할 수 있는 환경을 만들어줌)
$ git init
# github저장소와 나의 local에 있는 .git폴더가 연결됨
$ git remote add origin https://github.com/Kimsunghee3/chopssaltteok.git
* origin: github 저장소 
# push해서 github저장소로 넘겨줌
$ git push origin main
```

### uncommitted Changes
- 커밋되지 않은 변경 사항들

### git status
- 현재 git 상태
- 추적하지 않는 파일: 새로 생성된 파일들..추가 되지 않은 상태
- 수정함: 기존에 있던 파일들이 수정된 상태

### git remote -v
- 현재 remote되어있는 것들..

### git reset
<!-- 작업 내용 다 날림 -->
- git reset --hard 
ex) git reset --hard 32a8ecefe2481e12df2f4a65775e80c120aba44a

<!-- 작업 내용 working directory로 보냄 -->
- git reset --mixed // default
ex) git reset --mixed 32a8ecefe2481e12df2f4a65775e80c120aba44a
<!-- 작업 내용 staging area로 보냄 -->
- git reset --soft
ex) git reset --soft 32a8ecefe2481e12df2f4a65775e80c120aba44a




