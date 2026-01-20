# 리눅스 기초 실습

#### 2026.01.19 작성

----

## bandit 0

1. 주어진 문제에 나와있는대로 `ssh bandit0@bandit.labs.overthewire.org -p 2220`을 이용해 bandit에 접속해준다.

2. password ***bandit0***를 입력한다.
3. `ls -al`로 bandit0에 있는 디렉토리 및 파일을 체킹한다. <br>

![bandit0디렉토리](../image/2026/2026-1/3주차/bandit0/bandtit0_directory.png) <br>


4. `cat readme`를 이용해 readme를 읽어준다. <br>

![readme읽기](../image/2026/2026-1/3주차/bandit0/cat_readme.png) <br>


비밀번호 <u>***ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If***</u> 를 찾았다!!<br><br>


## bandit 1


1. `ssh bandit1@bandit.labs.overthewire.org -p 2220`을 이용해 bandit에 접속해준다.

2. password ***ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If***를 입력한다. (이후 작성할 bandit2부터 이 과정은 생략하겠다.)
3. `ls -al`로 bandit1에 있는 디렉토리 및 파일을 체킹한다. <br>

![bandit0디렉토리](../image/2026/2026-1/3주차/bandit1/bandit1_directory.png) <br>


4. 파일명이 - 이므로 파일명이 아닌 상대경로와 절대경로를 이용하여 파일을 읽어보자.

    - 절대경로
    1. `pwd`를 이용하여 현재 위치를 파악한다.
    2. 현재 위치는 **/home/bandit1**이므로 `cat /home/bandit1/-`  을 이용하여 - 파일을 읽는다.

    - 상대경로 
    1. `cat ./-`을 이용하여 - 파일을 읽는다.

![bandit0디렉토리](../image/2026/2026-1/3주차/bandit1/cat_-.png) <br>

비밀번호 <u>***263JGJPfgU6LtdEvgfWU1XP5yac29mFx***</u> 를 찾았다!!<br><br>


## bandit 2


1. `ls -al`로 bandit2에 있는 디렉토리 및 파일을 체킹한다. <br>

![bandit2디렉토리](../image/2026/2026-1/3주차/bandit2_directory.png) <br>


2. 파일명이 --spaces in this filename-- 이므로 파일명이 아닌 상대경로와 절대경로를 이용하여 파일을 읽어보자.

    - 절대경로
    1. `pwd`를 이용하여 현재 위치를 파악한다.
    2. 현재 위치는 **/home/bandit2**이므로 `cat /home/bandit2/--spaces in this filename--`  을 이용하여 --spaces in this filename-- 파일을 읽는다.

    - 상대경로 
    1. `cat ./--spaces in this filename--`을 이용하여 --spaces in this filename-- 파일을 읽는다.

비밀번호 <u>***MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx***</u> 를 찾았다!!<br><br>


## bandit 2


1. `ls -al`로 bandit2에 있는 디렉토리 및 파일을 체킹한다. <br>

![bandit2디렉토리](../image/2026/2026-1/3주차/bandit2/bandit2_directory.png) <br>


2. 파일명이 --spaces in this filename-- 이므로 파일명이 아닌 상대경로와 절대경로를 이용하여 파일을 읽어보자.

    - 절대경로
    1. `pwd`를 이용하여 현재 위치를 파악한다.
    2. 현재 위치는 **/home/bandit2**이므로 `cat /home/bandit2/--spaces in this filename--`  을 이용하여 --spaces in this filename-- 파일을 읽는다.

    - 상대경로 
    1. `cat ./--spaces in this filename--`을 이용하여 --spaces in this filename-- 파일을 읽는다.

![bandit2디렉토리](../image/2026/2026-1/3주차/bandit2/cat_--spaces%20in%20this%20filename--.png) <br>


비밀번호 <u>***MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx***</u> 를 찾았다!!<br><br>


## bandit 3


1. `ls -al`로 bandit3에 있는 디렉토리 및 파일을 체킹한다. <br>

![bandit3 디렉토리](../image/2026/2026-1/3주차/bandit3/bandit3_directory.png) <br>


2. `cd inhere`을 이용해 inhere로 이동한다.

3. `ls -al`을 이용해 inhere에 있는 디렉토리 및 파일을 체킹한다. <br>

![inhere 디렉토리](../image/2026/2026-1/3주차/bandit3/inhere_directory.png) <br>

4. 파일명이 ...Hiding-From-You 이므로 파일명이 아닌 상대경로와 절대경로를 이용하여 파일을 읽어보자.

    - 절대경로
    1. `pwd`를 이용하여 현재 위치를 파악한다.
    2. 현재 위치는 **/home/bandit3/inhere**이므로 `cat /home/bandit3/inhere/...Hiding-From-You`  을 이용하여 ...Hiding-From-You 파일을 읽는다.

    - 상대경로 
    1. `cat ./...Hiding-From-You`을 이용하여 ...Hiding-From-You 파일을 읽는다.

![inhere 디렉토리](../image/2026/2026-1/3주차/bandit3/cat_...Hiding-From-You.png) <br>


비밀번호 <u>***2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ***</u> 를 찾았다!!<br><br>


## bandit 4


1. `ls -al`로 bandit4에 있는 디렉토리 및 파일을 체킹한다. <br>

![bandit4 디렉토리](../image/2026/2026-1/3주차/bandit4/bandit5_directory.png) <br>


2. `cd inhere`을 이용해 inhere로 이동한다.

3. `ls -al`을 이용해 inhere에 있는 디렉토리 및 파일을 체킹한다. <br>

![inhere 디렉토리](../image/2026/2026-1/3주차/bandit4/inhere_directory.png) <br>

4. 수많은 파일중 정답이 들어있는 파일을 찾기위해 `./file -file0*`을 사용하여 파일의 유형을 분류한다. <cd>

![파일 유형 분류하기](../image/2026/2026-1/3주차/bandit4/file_-file0X.png) <br>

5. -file07의 유형이 아스키코드이므로 `cat ./-file07`을 이용해 -file07을 읽어준다.

![파일 유형 분류하기](../image/2026/2026-1/3주차/bandit4/cat_-file07.png) <br>


비밀번호 <u>***4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw***</u> 를 찾았다!!<br><br>


## bandit 5

1. `ls -al`로 bandit5에 있는 디렉토리 및 파일을 체킹한다. <br>

![bandit5 디렉토리](../image/2026/2026-1/3주차/) <br>


2. `cd inhere`을 이용해 inhere로 이동한다.

3. `ls -al`을 이용해 inhere에 있는 디렉토리 및 파일을 체킹한다. <br>

![inhere 디렉토리](../image/2026/2026-1/3주차/) <br>

4. 
비밀번호 <u>******</u> 를 찾았다!!<br><br>


