## Git 버전관리

> Git은 폴더 단위로 코드를 관리하는 분산형 버전관리 시스템으로 원격저장소와 로컬 저장소를 제공
>
> - Repository : git에서 버전이 저장되는 곳
> - Working tree : 아직 버전으로 만들어지기 전 단계
> - Staging area : 버전을 만들려고 하는 파일들이 들어가는 곳



#### `git init`

> 특정폴더를 git으로 관리 시작

#### `git status`

> git에게 상태 확인

#### `git add [파일명]`

> Staging area에 파일 추가

#### `git commit -m "커밋 메세지"`

> 버전을 생성

#### `git log`

> 버전들의 히스토리 확인

#### `git config`

> 설정

#### `git remote`

> 원격저장소를 등록
>
> - `git remote add [저장소이름] [저장소주소]` :새로운 원격저장소 등록
> - `git remote rm [저장소이름]` : 등록된 원격저장소 삭제
> - `git remote show [저장소이름] ` : 저장한 원격저장소의 정보 출력
> - `git remote -v` :저장소 확인

#### `git push / pull`

> - `git push [저장소이름] [브랜치이름]` : 원격저장소에 업로드
> - `git pull [저장소이름] [브랜치이름] : 원격저장소에서 로컬저장소로 가져옴

#### `git clone`

> github주소를 git bash로 가져올때 사용
>
> - git clone [가져올 github 주소]
>   - 가져온 뒤 git bash에서 작업을 더 해서 더 추가할 수 있다.











