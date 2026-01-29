<br><br>


# Command injection 실습
#### 2026.01.27 작성
<br>

## Command injection 1

1. `;sh`로 서브쉘을 열어준다. <br>
![서브 쉘 열기](../../../../image/2026/2026-1/4주차/command_injection1/서브쉘열기.png) <br>


2. `ls -al`로 디렉토리 및 파일을 체킹한다. <br>
![디렉토리 체킹](../../../../image/2026/2026-1/4주차/command_injection1/directory.png)

3. `cat flag`를 이용하여 flag 파일을 읽어준다. <br>
![flag 파일 읽기](../../../../image/2026/2026-1/4주차/command_injection1/cat_flag.png)


비밀번호 <u>***flag{cmd_1_15_3z}%***</u> 를 찾았다!!<br><br>

---------

<br>

## Command injection 2
### ban
-flag <br>
-sh <br>

1. sh, flag 사용 시 **Nah.. I don't like that!** 을 출력하므로 *를 이용해 우회하여 접근할 것이다. <br>
`;cat fla*`를 이용하여 바로 flag 파일을 읽어내자. <br>
![flag 읽기](../../../../image/2026/2026-1/4주차/command_injection2/cat_flag.png) <br>


비밀번호 <u>***flag{t00_m4ny_4rgu73n75}%***</u> 를 찾았다!!<br><br>

---------

<br>

## Command injection 3
### ban
-flag <br>
-sh <br>
-vi <br>
-cat <br>
-ls <br>
-pwd <br>

1. 이번에는 명령어 head와 tail, *를 이용해 우회하여 접근할 것이다. <br>
`;head fla*`를 이용하여 flag 파일의 앞부분을 읽어낸다. <br>
![flag 앞부분 읽기](../../../../image/2026/2026-1/4주차/command_injection3/head_flag.png) <br>

2. `;tail fla*`를 이용하여 flag 파일의 뒷부분을 읽어낸다. <br>
![flag 뒷부분 읽기](../../../../image/2026/2026-1/4주차/command_injection3/tail_flag.png) <br>

비밀번호 <u>***flag{head_and_tail}***</u> 를 찾았다!!<br><br>

---------

<br>

## Command injection 4
### ban
-flag <br>
-sh <br>
-vi <br>
-cat <br>
-ls <br>
-pwd <br>
-head <br>
-tail <br>
-* <br>
-; <br>
-/ <br>
-| <br>

1. 이번에는 명령어 head와 tail, *를 이용해 우회하여 접근할 것이다. <br>
`;head fla*`를 이용하여 flag 파일의 앞부분을 읽어낸다. <br>
![flag 앞부분 읽기](../../../../image/2026/2026-1/4주차/command_injection3/head_flag.png) <br>

2. `;tail fla*`를 이용하여 flag 파일의 뒷부분을 읽어낸다. <br>
![flag 뒷부분 읽기](../../../../image/2026/2026-1/4주차/command_injection3/tail_flag.png) <br>

비밀번호 <u>***flag{head_and_tail}***</u> 를 찾았다!!<br><br>

---------