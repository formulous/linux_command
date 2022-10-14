# linux_command

`useradd [id]` : 유저 추가

`passwd [id]` : 유저 id에 password 추가

`scp -P [port] [file] [user]@[ip]:[path]`: ip주소의 user계정에 path경로로 파일 전송 

`rm [OPTION] [file]` : file 삭제

`mv [file1] [file1edit]` : file1 이름을 file1edit 으로 수정

`chown [OPTION] [id]` : file에 대한 권한 변경
- `OPTION -R` : 하위 디렉토리의 권한까지 전체 

`vi [file]` : 문서 편집모드

`:wq` : 편집모드 저장 후 종료

`:q!` : 편집모드 저장하지 않고 종료


## 압축 관련

* .gz로 압축하기
`tar -zcvf [파일명.tar.gz] [압축 할 폴더명]`

* gz 압출 풀기
`tar -zxvf [파일명.tar.gz]`
