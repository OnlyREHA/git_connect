# git_connect

### git 설치  --> 기본 값으로 설치

시작버튼에서 Git Bash 열기(실행)

```
git config --global user.name "reha"
```

GitHub 이메일이랑 동일해야함.
```
git config --global user.email "reha01047@gmail.com"
```

정보 확인하기
```
git config --list
```

![image](https://github.com/OnlyREHA/git_connect/assets/145514740/97f1d994-4909-41ce-9ac6-aafca058a9e3)

내용은 컴퓨터에 한번만 설치하면 됨.

--------------------------------------------

### GitHub에 코드 업로드 하기

### vscode reha폴더 업로드 파일 올려서 뉴터미널

1.초기화

```
git init
```
-.git 이라는 폴더가 생성된다


2.파일 올리기

```
git add .
```


3.히스토리 만들기

```
git commit -m "내가 적고싶은 메세지"  
```
-메세지에는 한글이 가능하다.
- -m 메세지의 준말


4.GitHub repository랑 내 로컬 프로젝트랑 연결 

-프로젝트를 올릴 repository를 먼저 만들어야함

-아래주소는 내가 만든 repository에서 복사해서 가져와야한다 ( repository만들때 readme 선택하지말기)


5. 연결 확인


```
git remote -v
```


6.GitHub에 자료 올리기


```
git push origin master
```



//네트리파이 등록하고 주소복사해서

vscode ../ -> ..을 빼고 네트리주소 넣기,

깃허브 ../ -> ..을 빼고 네트리주소 넣기


--------------------------------------------------


### GitHub에 계속 업데이트 하는 방법

1. 추가할 파일 더하기

```
git add .
```


2. 히스토리 만들기

```
git commit -m ""
```

3. GitHub에 올리기

```
git push origin master
```

📌 다시 GitHub의 내용을 끌어와야함

```
git pull origin master
```

  내용을 끌어와서

2. 히스토리 만들기부터 재시작




























