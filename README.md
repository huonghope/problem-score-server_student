# 문제은행 채점 서버

해당 프로젝트 프로그래밍 문제은행이라며 동국대학교 PLASS 연구실 연구원들이 개발하는 프로젝트입니다.

## 개발 화경
> Node.js

## 설치
```bash

# 프로젝트 github에서 받음
git clone `` 
cd problem-score-server/server

# 필요하는 packge 설치
npm start

# 컴파일 할때 소스코드 저장할 Folder를 만들 
mkdir DEBUG_TEMP_PATH

# .env 파일을 만들어서 환경변수를 추가함
vim .env
======= 
# .env 파일 내용을 다음과 같음.
# DB연결하기 위한 정보
MYSQL_HOST=
MYSQL_PORT=
MYSQL_ID=
MYSQL_PASS=
MYSQL_DB=problems_test


BOILERPLATE_PATH=boilerplates
DEBUG_TEMP_PATH=DEBUG_TEMP_PATH
DEBUG_TEMP_PATH_TEST=DEBUG_TEMP_PATH_TEST


DEBUG_TEMP_PATH_BANK_PROBLEMS=DEBUG_TEMP_PATH_BANK_PROBLEMS

# 서버 PORT
PORT=5111

# 원하는 signture 입력
TOKEN= 
======


```
## License
[MIT](https://choosealicense.com/licenses/mit/)