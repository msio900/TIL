# 원격저장소(remote repository) 기초

## 기본 설정

* 로컬 git 저장소
* GitHUB remote repository를 생성

## 명령어

### 원격 저장소 설정

```bash
$ git remote add origin 저장소URL
```

* 깃, 원격저장소(remote) 추가해줘(add) origin이라는 이름으로 저장소 URL을
  * origin은 원격저장소 이름!
  * 비조뒤일앞(빈도부사 위치)

### 원격 저장소 목록 보기

```bash
$ git remote -v

origin  https://github.com/msio900/practice1.git (fetch)
origin  https://github.com/msio900/practice1.git (push)
```

### 원격 저장소 설정 삭제하기

```bash
$ git remote rm origin
```

* 깃아, 원격저장소 삭제해줘(rm - remove) origin..을 

### push

```bash
$ git push origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 205 bytes | 102.00 Ki
Total 3 (delta 0), reused 0 (delta 0), pack-reused
To https://github.com/msio900/practice1.git
 * [new branch]      master -> master
```

* 깃아, 푸쉬해줘 origin 원격저장소에 master 브랜치!