# 2023_OSS
## 2023_OSS 수업

---

### 3주차 git

### 이미지

![항공대 로고](https://github.com/You-jisang/2023_OSS/blob/main/img/kau/kau%20(1).png "한국항공대학교")

### 링크

[LMS](https://lms.kau.ac.kr/ "LMS")

#### ProGit 링크

[ProGit](https://git-scm.com/book/ko/v2 "ProGit")


##### 주요 git 명령어

* init : .git 초기화
* add: `untracked` 파일을 `tracked` 로 변경 -> 동시에 `stage`로 변경, 이미 
`tracked` 이고 `modified` 인 경우 `staged`로 변경
    * git add . : 모든 파일 변경
* commit : `staged` 된 파일만 커밋할 수 있음
    * 커밋 메시지 입력 : git commit -m "의미있는 메시지" or git commit 후 
편집기에서 입력
* branch : 브랜치 보기
* merge : 브랜치 합병
* diff : 수정했지만 아직 `stage` 하지 않은 파일 들을 비교   
* log : 커밋한 이력을 보여줌, 최근 커밋이 위에 표시
    * 예) git log --oneline --decorate --graph --all : 로그에 브랜치가 잘 
나타나게 표시
    * 예) git log --oneline -n -3
* push : `github` 에서 `clone` 한 소스를 커밋한 후 원격저장로 푸시
---
* 과제 하면서 찾은 명령어
* git push origin +main : `push` 할 때 `! [rejected] master -> master 
(fetch first)` 에러 해결
* git remote add origin 원격저장소URL : 레파지토리 연결
> 출처 : 
https://donggu1105.tistory.com/104<br/>https://curryyou.tistory.com/427
---

### 2주차 숙제

```bash

#!/bin/sh

name="유지상"
student_id=2020125044
FILE_PATH=$(find /home/kau2 -name "w2_homework.txt" 2>/dev/null)
LINE_NUM=$(wc -l $FILE_PATH | cut -c 1)
LAST_LINE=$(tail -n 1 $FILE_PATH)

echo "----------"
echo "name :"
echo $name
echo "\n----------"
echo "student id ":
echo $student_id
echo "----------\n"
echo "file path :"
echo $FILE_PATH
echo "\n----------"
echo "line number :"
echo $LINE_NUM
echo "\n----------"
echo "last line :"
echo $LAST_LINE
```

---

## 마크다운

### 목록

#### 번호 있는 목록 : 내림차순 정렬

1. 첫번째
3. 세번째
2. 두번째

#### 번호 없는 목록 : *, -, +

* 첫번째
- 세번째
+ 두번째

---
* 빨강
    - 녹색
        + 파랑	



### 강조

*single asterisks*<br/>
_single underscores_<br/> 
**double asterisks**<br/> 
__double underscores__<br/> 
~~cancelline~~



