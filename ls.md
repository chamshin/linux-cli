# ls

#### 현재 있는 디렉토리의 모든 파일을 보여준다 -> 숨김파일(.file) 까지 보여줌.
```
$ ls -a

.         .git      alias.md  cdmod.md  curl.md   grep.md   ls.md     pwd.md
..        README.md cd.md     cp.md     find.md   kill.md   man.md    touch.md
```
#### 상세 정보를 보여준다
```
$ ls -l

total 104
-rw-r--r--  1 shinbaak  staff  116  5 19 23:11 README.md
-rw-r--r--  1 shinbaak  staff    5  5 19 23:12 alias.md
-rw-r--r--  1 shinbaak  staff    5  5 19 23:11 cd.md
-rw-r--r--  1 shinbaak  staff    5  5 19 23:11 cdmod.md
-rw-r--r--  1 shinbaak  staff    5  5 19 23:11 cp.md
-rw-r--r--  1 shinbaak  staff    5  5 19 23:12 curl.md
-rw-r--r--  1 shinbaak  staff    5  5 19 23:12 find.md
-rw-r--r--  1 shinbaak  staff    5  5 19 23:12 grep.md
-rw-r--r--  1 shinbaak  staff    5  5 19 23:12 kill.md
-rw-r--r--  1 shinbaak  staff    5  5 19 23:11 ls.md
-rw-r--r--  1 shinbaak  staff    5  5 19 23:12 man.md
-rw-r--r--  1 shinbaak  staff    5  5 19 23:12 pwd.md
-rw-r--r--  1 shinbaak  staff    5  5 19 23:12 touch.md
```
#### -l 옵션을 사용하면 추가로 파일 모드, 하드링크 수, 소유자, 그룹, 파일의 크기, 마지막 수정일, 파일명 순으로 표시된다.
```
$ ls -al

total 104
drwxr-xr-x  16 shinbaak  staff  512  5 19 23:12 .
drwx------@ 21 shinbaak  staff  672  5 19 01:50 ..
drwxr-xr-x  14 shinbaak  staff  448  5 19 23:13 .git
-rw-r--r--   1 shinbaak  staff  116  5 19 23:11 README.md
-rw-r--r--   1 shinbaak  staff    5  5 19 23:12 alias.md
-rw-r--r--   1 shinbaak  staff    5  5 19 23:11 cd.md
-rw-r--r--   1 shinbaak  staff    5  5 19 23:11 cdmod.md
-rw-r--r--   1 shinbaak  staff    5  5 19 23:11 cp.md
-rw-r--r--   1 shinbaak  staff    5  5 19 23:12 curl.md
-rw-r--r--   1 shinbaak  staff    5  5 19 23:12 find.md
-rw-r--r--   1 shinbaak  staff    5  5 19 23:12 grep.md
-rw-r--r--   1 shinbaak  staff    5  5 19 23:12 kill.md
-rw-r--r--   1 shinbaak  staff    5  5 19 23:11 ls.md
-rw-r--r--   1 shinbaak  staff    5  5 19 23:12 man.md
-rw-r--r--   1 shinbaak  staff    5  5 19 23:12 pwd.md
-rw-r--r--   1 shinbaak  staff    5  5 19 23:12 touch.md
```
