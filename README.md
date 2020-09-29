# How_to_use_Git

- staging area에서 파일을 제거할 때

    `git reset 파일명`

- 이때 까지 commit한 내용들을 볼 때

    `git log --pretty=oneline`
    
- git에서 최신 commit을 수정하고 싶을 때

    `git commit --amend`
    
- git에서 alias를 통해서 변수 만들기

    `git config alias.history 'log --pretty=oneline'`
    
- commit들 사이에 변화를 보고 싶을 때

    `git diff 앞에 있는 commit 뒤에 있는 commit `
    
- commit의 HEAD를 바꾸고 싶을 때

    `HEAD가 가리키는 commit에 따라 working directory도 달라진다`
    
    `git reset --hard commitID`
    
- branch 생성
    
    `master 브랜치에서 작업했던 코드들이 그대로 옮겨져 간다`
    `git branch 브랜치명`
    
- branch 이동

    `git status로 현재 브랜치 확인 가능`
    `git checkout 이동할 브랜치명`
