# Learn Git

## What is Git?

### VCS(Version Control System) / SCM(Source Code Manager)

git 은 버전관리를 한다. github 이랑은 다르다!

| Command                                | Description                                                  | Example                                          |
| -------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------ |
| `$ git init`                           | `.git` 디렉토리 생성 및 초기화                               | `$ git init`                                     |
| `$ git add <FILE>`                     | `<FILE>` 을 트랙/스테이징 한다.                              | `$ git add index.html`                           |
| `$ git add <PATH>`                     | `<PATH>` 안의 전체 파일을 트랙/스테이징 한다.                | `$ git add .`                                    |
| `$ git commit -m 'MSG'`                | 마지막 `add` 를 통해 스테이징 된 상태를 커밋(버젼만들기)한다. | `$ git commit -m "First commit"`                 |
| `$ git remote add origin <REMOTE-URL>` | 리모트 리포를 가리킨다.                                      | `$ git remote add origin https://remoterepo.git` |
| `$ git push -u origin master`          | 리모트 리포로 푸—쉬(처음에만!)                               | `$ git push -u origin master`                    |



