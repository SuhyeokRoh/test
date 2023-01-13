
# About Git

![image](https://miro.medium.com/max/640/1*zpvd5fjZAFGsVAEsvMGKxA.webp)

- Local 파일에서 저장한 내용을 온라인 저장소에 업로드하기 위해서는 다음과 같은 과정이 필요하다.

### 1. touch filename.md(파일 확장자 명)

`local file 내에 'filename'을 이름으로 갖는 파일이 생성`

### 2. git add filename.md

`Staging area에 내가 만든 파일을 업로드`

- git status: 현재 git의 상태로 file이 어디에 위치해 있는지 알 수 있다.

### 3. git commit -m "input something"

`file에 수정된 부분에 대한 comment를 남기기`
- git log: 지금까지 남긴 commit을 확인할 수 있다.
(종료할 때에는 q 입력)

- git commit --amend: 입력한 commit을 수정할 수 있다.(i 입력 후 수정, esc 클릭 후 명령어 입력)

### 4. git push

`Local git에 저장된 file을 온라인 저장소에 업로드`

이런 과정을 통해 Local에서 수정한 파일/ 생성된 파일을 온라인 저장소에 업로드 할 수 있다.