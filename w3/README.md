# 2023_OSS
## 2023_OSS 수업
---

### 3주차 git

### 이미지

![항공대 로고](https://github.com/You-jisang/2023_OSS/blob/main/img/kau/kau%20(1).png)

### 링크

[LMS](https://lms.kau.ac.kr/)

#### ProGit 링크

[ProGit](https://git-scm.com/book/ko/v2)


##### 주요 git 명령어

* add:

* commit

* branch

* merge

* status

* log 
* 예)

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

*single asterisks*
_single underscores_ 
**double asterisks** 
__double underscores__ 
~~cancelline~~



