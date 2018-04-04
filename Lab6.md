Try Github 정리
===============
1. git init
> Git repository 생성

![text](./LAB6/1.PNG)
------------------------------
2. git status
> 현재 상태를 확인한다

![text](./LAB6/2.PNG)
-------------------------------
3. git add octocat.txt
> otcocat.txt 파일을 추적한다

![text](./LAB6/3_1.PNG)
![text](./LAB6/3_2.PNG)
----------------------------------
4. git status
> git status로 현재 상태를 확인하면 'changes to be commited' 되어있다
> 'changes to be commited'는 octocat.txt파일이 tracked 상태이면서 커밋에 추가될 staged 상태라는 뜻이다

![text](./LAB6/4.PNG)
--------------------------------------------------------------------------------------------------------
5. git commit -m "Add cute octocat story"
> 준비 영역에서 변경 내역을 저장소로 저장하기 위해서 남길 메세지와 함께 commit 명령어를 사용한다

![text](./LAB6/5.PNG)
-----------------------------------------------------------------------------------------------
6. git add '*.txt'
> 
