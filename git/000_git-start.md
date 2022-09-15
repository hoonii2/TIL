## GIT

VCS ( Version Control System ) 로 버전 관리 및 협업을 위해 사용됩니다.

---

### 1. 기초

1. Git 구성 요소
	- Blob : 파일 하나의 내용에 대한 정보
	- Tree : Blob 이나 Subtree 의 메타데이터 (디렉토리 위치, 속성, 이름 등)
	- Commit : 커밋 순간의 스냅샷

2. Git **Process Flow** , **Command**
```mermaid
graph LR
A(Working Directory) -- Add --> B(Staging Area)
B -- Commit --> C(Local .git)
C -- Checkout --> A
C -- Push --> D(Remote Github)
D -- Fetch --> C
D -- Pull --> A

- Local 영역 : Working Directory, Staging Area, Local .git
- Remote 영역 : Remote Github
```

---

### 2. 설치

> 1. Git 설치<br>
> [윈도우 Git 설치 링크](https://gitforwindows.org/)

> 2. Git 설치 확인 및 환경설정
> ```shell
> $ git -v
> $ git config --global user.name "유저네임"
> $ git config --global user.email "메일주소"
> $ git config --global core.editor "vim"
> $ git config --global core.pager "cat"
> ```

> 3. Github 가입 <br/>
> [Github 홈페이지](https://github.com/)

---

### 3. Github Repo 구성 및 Clone 저장

> 1. Github Repo 생성
> ![1번 이미지](https://github.com/lkh55913/TIL/blob/main/git/000%20%EC%9D%B4%EB%AF%B8%EC%A7%80/1.png)
> ![2번 이미지](https://github.com/lkh55913/TIL/blob/main/git/000%20%EC%9D%B4%EB%AF%B8%EC%A7%80/2.png)
> ![3번 이미지](https://github.com/lkh55913/TIL/blob/main/git/000%20%EC%9D%B4%EB%AF%B8%EC%A7%80/3.png)

> 2. 


마크다운으로 쓰기 어렵다..
