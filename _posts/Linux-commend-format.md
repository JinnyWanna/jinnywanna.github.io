---
title: Linux commend format
date: 2024-01-18 17:57
categories: [Docker, 서브카테고리]
tags: [Docker]
pin: false
image: 
img_path:
---

## 리눅스 명령어 형식

```Linux
command <ARG1> <ARG2> ...
```
기본 형식은 명렁어를 선입력한 후 띄어쓰기로 인자(ARG)들을 입력합니다.

### 리눅스 기본 명령어

```
pwd // 현재 디렉토리 위치 출력

ls // 현재 디렉토리 파일 목록 출력

cd // 디렉토리 이동

cp <파일1> <파일2> ... <파일n-1> <복사할 디렉토리> // n-1개 파일을 <복사할 디렉토리>로 복사

mv <파일1> <파일2> ... <파일n-1> <이동할 디렉토리> // n-1개 파일 <이동할 디렉토리>로 복사
```

### 리눅스 명령어 옵션 형식

리눅스 명령어의 옵션은 -나 --로 시작하여 인자와 구분됩니다.
<br/>
보통 옵션은 command와 ARG 사이에 입력합니다. 다른 위치에서 사용할 시 에러가 발생할 수 있습니다.

```
ls -1 // 파일 목록을 한줄에 하나씩만 출력

```
이런식으로 옵션 지정이 가능합니다. - 로 시작하는 옵션의 경우 묶어서 여러 옵션을 실행할 수 있습니다

```
ls -a -G -1
ls -G1a
ls -1aG
```
모두 똑같은 옵션입니다.
<br/>
보통 리눅스에서 -옵션은 한 글자로 이루어진 옵션에서 사용합니다.
--는 여러 글자로 이루어진 옵션에서 사용합니다. (프로그램마다 예외가 있을 수 있습니다.)

아래에 인터넷에서 쉽게 구할 수 있는 명령어 reference pdf를 첨부합니다.
![image](https://github.com/JinnyWanna/jsFightingGame/assets/105906254/254f8c9f-9f37-4491-83e3-1c54e0c821c3)

![image](https://github.com/JinnyWanna/jsFightingGame/assets/105906254/7c4b3631-e484-448e-af13-47816881dec7)

![image](https://github.com/JinnyWanna/jsFightingGame/assets/105906254/67529684-e291-431e-aa62-eaf32a365324)


