#GIT 명령어

##git init
    `Create an empty Git repository or reinitialize an existing one.`
    현재 위치한 폴더를 빈 깃 레포지토리로 초기화하기 위해 사용함.
    다음에 나올 명령어로 현재 소유하고 있는 깃 허브 `repository`로 연결할 수도 있음

##git remote add origin ${repo 주소}
    github 레포지토리와 연결하기 위해 사용하는 명령어

##git switch
    `git branch {생성할 브랜치 명}`을 한 이후, 생성된 브랜치로 이동할 때 사용하는 명령어

##git clone {repo 주소}
    *가장 헷갈렸던 명령어*
    clone을 받으면 해당 레포에 있는 폴더와 파일들을 말 그대로 `복제`한다.
    `git init`을 할 필요 없이, (권한이 있다면) github 레포와 연결되기 때문에 바로 `git push` 명령어를 사용할 수 있다. 