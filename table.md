# - Table

기본적인 Table 작성법은 다음과 같다.

```
| 제목 | 저자 | 발행일 | {제목 부분} |
| --- | --- | --- | --- |
| Test | Ahri | 2023-09-04 | b |
| Hello | World | 2023-09-05 | c |
```

| 제목 | 저자 | 발행일 | {제목 부분} |
| --- | --- | --- | --- |
| Test | Ahri | 2023-09-04 | b |
| Hello | World | 2023-09-05 | c |

-  -  -

':'콜론을 사용하여 정렬 방식을 지정할 수 있다.    
   
:---   왼쪽 정렬   
---:   오른쪽 정렬   
:---:  중앙 정렬

```
| 제목 | 저자 | 발행일 | {제목 부분} |
| :--- | ---: | --- | :---: |
| Test | Ahri | 2023-09-04 | b |
| Hello | World | 2023-09-05 | c |
```

| 제목 | 저자 | 발행일 | {제목 부분} |
| :--- | ---: | --- | :---: |
| Test | Ahri | 2023-09-04 | b |
| Hello | World | 2023-09-05 | c |
