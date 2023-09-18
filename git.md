# Git

## 최초설정
```dash
git config --global user.name 'name'

git config --global user.email 'email'
```

## 명령어
- `git init`
    -`.git` : repository를 생성하는 명령어(현재폴더에 비어있는 폴더 만들어줌)

- `git add <file name>` : 무대 위에 올리기
    - `working directory`에서 `stageing area`로 추가
    - 일반저긍로 모든 파일, 폴더를 한번에 추가하기 위해 아래의 명령어로 작성
    - `git add .`
- `git commit"` :하나의 사진찍기?
    -`staging area`에 올라간 파일들의 스냅샷을 찍어 `git direectory`에 저장
    - 일반적으로 -m 옵션을 넣어서 커밋메세지를 추가 
    -`git commit -m "message"`



