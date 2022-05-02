# 깃 초기화(현재 프로젝트에서 변경사항 추적(버전 관리)를 시작)
```bash
$ git init
```
# 깃 글로벌 변수 등록(최초 1회)
```bash
$ git config --global core.autocrlf [window : true / Mac : input] //개행문자 처리(Newline) 설정
$ git config --global user.name 'user_name' //사용자정보 name
$ git config --global user.email 'user_email' //사용자정보 email
```

# 등록된 글로벌 변수 확인
```bash
$ git config --global --list
```

# 깃 상태확인
```bash
$ git status
```

# 깃 업로드 파일 추가
```bash
$ git add file_name ['.'은 현재경로의 모든파일 의미]
```

# 깃에 추가한 파일 커밋
```bash
$ git commit -m 'commit_message'
```

# 깃 커밋 로그 확인
```bash
$ git log
```

# 깃 원격(깃허브)저장소 주소 추가
```bash
$ git remote add origin repository_address
```

# 깃 원격 저장소에 파일 업로드
```bash
$ git push origin master
```

# 깃 브렌치 확인
```bash
$ git branch
```

# 깃 브렌치 및 원격서버 접속자 등 모든 정보 표시
```bash
git branch -a
```

# 깃 브렌치 생성
```bash
git branch branch_name
```

# v깃 브렌치 삭제
```bash
$ git branch -d branch_name
```

# 브렌치 사용자 변경
```bash
$ git checkout branch_name
```

# 깃 레포지터리 내용 clone
```bash
$ git clone repository_address
```

# 깃 커밋 버전 리셋
```bash
$ git reset --hard HEAD~1 [HEAD에 있는 부분에서 1만큼 이전 작업으로 상태가 되돌아감]
```

# 깃 커밋 버전 리셋 되돌리기
```bash
$ git reset --hard ORIG_HEAD
```
# 깃 원격 사용자 불러오기 (clone으로 파일을 복사 후 사용자 branch가 없을때)
```bash
$ git checkout -t origin/branch_name
```

# 깃 브렌치 생성 후 해당 브렌치로 바로 이동
```bash
$ git branch -b branch_name
```

# 깃 원격저장소에서 데이터 가져오기
```bash
$ git pull origin master
```

# vsCode 에서 현재 경로의 폴더 열기
```bash
$ code . -r ['.'은 현재 경로, r속성은 현재 열린 vscode편집기에서 열기]
```
