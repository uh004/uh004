# add,commit,log,show

## add 명령어
```
깃의 add 명령어는 워킹 디렉터리의 파일을 스테이지 영역으로 등록한다.
$ git add '내가만든 파일'
```

## commit 명령어
```
깃의 commit 명령어는 git add를 통해 스테이지 영역에서 지역 저장소로 등록 후 커밋메세지 를 저장한다.
$ git commit -m '커밋메세지'
```

![128hsgntnsu9bww0y8sz](https://user-images.githubusercontent.com/105197524/196039835-5fbce362-a775-4ebb-b315-01a3c7d5cf6e.jpg)

## log 명령어
```
마지막 커밋인 head부터 이전 모든 이력 로그 표시한다.
git config 명령을 통해 세팅했던 user.name/user.email 값이 표기
$ git log
```
![제목 없음](https://user-images.githubusercontent.com/105197524/196040065-4f32120d-5261-4910-a44b-a7e3ea8a7d74.png)

## show 명령어
```
commit의 자세한 정보 확인가능
1. 지정한 커밋인 head의 정보 확인
2. Author 영역의 이름과 이메일 주소
3. git config 명령을 통해 세팅했던 user.name / user.email 값이 표기
4. 파일의 변화(patch)도 표시
$ git show
```
![제목 없음](https://user-images.githubusercontent.com/105197524/196040317-8bb56aee-7116-4bc0-b7d1-28402fbde653.png)
