# 리눅스 기초 실습

#### 2026.01.17 작성
---
## example 1


1. `ls -al`로 example1에 있는 디렉토리 및 파일을 체킹한다.<br>


![example1디렉토리](../image/2026/2026-1/3주차/example1/example1_directory.png) <br>


2. 먼저 dir1부터 살펴볼 것이다. `cd dir1`을 이용해 dir1로 이동한다.
3. `ls -al`로 dir1에 있는 디렉토리 및 파일을 체킹한다. <br>

![dir1디렉토리](../image/2026/2026-1/3주차/example1/dir1_directory.png) <br>


4. `cd dir11`을 이용해 dir11로 이동한다.
5. `ls -al`을 이용해 dir11에 있는 디렉토리 및 파일을 체킹한다. <br>

![dir11디렉토리](../image/2026/2026-1/3주차/example1/dir11_directory.png) <br>

6. file.txt를 찾았으니 `cat file.txt`를 이용하여 파일을 읽어준다. <br>

![file읽기](../image/2026/2026-1/3주차/example1/cat_file.png) <br>


7. hello!%가 나왔으니 이는 답이 아니다. `cd ../`으로 다시 example1으로 돌아가자.

8. 다음으로 dir2를 살펴볼 것이다. `cd dir2`를 이용해 dir2로 이동한다.
9. `ls -al`을 이용해 dir2에 있는 디렉토리 및 파일을 체킹한다. <br>

![dir2디렉토리](../image/2026/2026-1/3주차/example1/dir2_directory.png) <br>

10. `cd dir22를` 이용해 dir22로 이동한다.
11. `ls -al`을 이용해 dir22에 있는 디렉토리 및 파일을 체킹한다. <br>

![dir22디렉토리](../image/2026/2026-1/3주차/example1/dir22_directory.png) <br>

12. flag.txt를 찾았으니 `cat flag.txt`를 이용해 flag.txt를 읽어준다. <br>

![flag읽기](../image/2026/2026-1/3주차/example1/cat_flag.png) <br>

<u>***flag{welcome_you_got_first_flag}%***</u> 를 찾았다!!<br><br>


## example 2


1. `ls -al`로 example2에 있는 디렉토리 및 파일을 체킹한다.<br>


![example2디렉토리](../image/2026/2026-1/3주차/example2/example2_directory.png) <br>


2. `cat hello`를 이용해 hello를 읽는다. <br>

![hello읽기](../image/2026/2026-1/3주차/example2/cat_hello.png) <br>


3. cat hello로는 hello 파일을 해석할 수 없으니 `./hello`를 이용해 hello를 실행시킨다. <br>

![hello실행시키기](../image/2026/2026-1/3주차/example2/work_hello.png) <br>


4. <u>***flag{file_read_flag}***</u>  를 찾았다!!<br><br>