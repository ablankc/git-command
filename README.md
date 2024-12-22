# git-command

![Me](./Images/LineStick.png)

~~주석~~
> 손도 익숙 하지 않고 기억도 못하는 나에게
>> 어디에 있는지도 모른다는......

<https://github.com/ablankc/git-command>

[이 페이지](https://github.com/ablankc/git-command, "마크다운 문법도")


` git clone git@github.com:ablankc/git-command.git `

```
cat ~/.ssh/config
Host github.com
	Hostname github.com
	user git
	IdentityFile ~/.ssh/nano_id_rsa
```

___git-command___

_1. 초기  설정_
- git init
  - 
- git clone
  - 
- git status
  -
- git add * -m "New repo file"
  -   
- git commit -am "Modify file"
  -   
- git push
  -
- git pull
  -  
- git log 
  -  
- git checkout -- README.md `이전 파일로 복원`
  -  
- git reset
  - 
  - git reset HEAD^ `아마 pull 한 버전으로 돌아가 겠지?`
  - git reset --soft HEAD^ `최근 커밋을 하기 전 상태로`
  - git reset mixed HEAD^ `최근 커밋과 스테이징을 하기 전 상태로, 옵션 없이 git reset 명령을 사용할 때 기본 `
  - git reset --hard HEAD^ `최근 커밋,스테이징 하기전, 복구 불가`
  - git reset --hard "commit hash" `해당 커밋으로 이동, 이후 커밋 삭제`
- git revert
  - 
  - git revert "commit hash" `해당 커밋을 취소 하는 기록을 남김, 복구 가능 `
- git remote
  - 
  - git remote -v
  - 
- git branch
  - 
- git checkout "branch name"
  - 

- git checkout main
  - edidt README.md file and commit & push
- run git merge 
- git merge "branch name"
  - 
- 
_2. merge
- git branch MG
- git checkout MG
- edit file README.md

- git stash
  - git stash list
  - git stash pop
  - git stash apply
  - git stash drop

_3. git remote
 - git remote add origin XXXX.git