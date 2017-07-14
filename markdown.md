# markdown

## 1. 개인메모
```
1. 가장 큰 제목 # 제목
   두번쨰 큰 글씨 ## 제목2
   세번째 글씨 ### 내용1-1
   네번째 글씨 #### 내용1-1-1
   ...

2. 글씨 앞뒤로 __ 붙이면 볼드 스타일  ex) __볼드스타일문자__

3. 글씨 앞뒤로 _ 붙이면 이태릭 스타일  ex) _이태릭스타일_

4. 글씨 앞뒤로 ___ 붙이면 볼드+이태릭  ex)___볼드+이태릭___

5. 글씨 앞뒤로 '' 붙이면 하이라이트 ex) 이 문자는 '하이라이트' 입니다.

6. 줄 내림(Enter)은 스페이스(띄어쓰기) 두칸하고 엔터 
   -> 개요나 그런건 자동 줄내림이 되고, 그냥 일반 텍스트 같은거에 적용

7. 인용구문은 앞에 > 붙이기  ex) > 하늘이 블로그 - http://haneul.blog.com

8. 하이퍼링크 [클릭](이동하고자하는 링크)

9. 이미지 삽입 ![이미지가 깨질때 나오는 text](이미지 주소)

10. 테이블
	|컬럼1|컬럼2|컬럼3|
	|:-:|:-:|:-:|  -> :- 왼쪽정렬 :-: 가운데정렬 -: 오른쪽정렬
	|내용|내용|내용|

	(인터넷에 markdown table 치면 예제 나오는거 복붙해서 사용해도 됨)

11. 텍스트 박스
	``` 
	이 안에는 엔터쳐도 자동 줄내림되고 마크다운 형식이 아니라 쭉쭉 써짐!
	```
	```javascript  -> 이렇게 언어를 붙이면 그 형식대로 나옴
	import { Component } from '@angular/core';
	import { Nav, NavController, LoadingController } from 'ionic-angular';
	import { Member } from '../../app/member';
	import { Global } from '../../app/global';
	import { AdminHomeService } from './admin-home-service';
	```
```