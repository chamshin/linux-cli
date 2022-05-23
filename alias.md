# alias


#### alias 추가
```
$ alias [별칭]=[명령어]
$ alias k=kubectl
```

#### alias 조회
```
$ alias
```

#### alias 해제
```
$ unalias [별칭]
```

#### alias 영구 설정
alias 명령어는 현재 사용중인 쉘에서만 적용되고 쉘이 종료되면 alias 기능이 상실된다.
다음은 alias를 영구 설정하는 방법이다.

- **계정별로 다른 alias 설정**
  - 사용자의 home에서 현재 사용 중인 쉘의 profile에 alias 설정
```
$ vim ~/.bash_profile
$ source ~/.bash_profile
```

- **모든 사용자 계정에 설정**
  - etc/profile에 alias 설정
```
$ sudo vim /etc/profile
$ source /etc/profile
```
