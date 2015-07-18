# js_core_curri 

intro
http://jsfiddle.net/pouy_jsstudy/n6tnv4ef/


0 자바스크립트 데이터타입과 연산자

1 기본타입 --------------------------------------------------   http://jsfiddle.net/pouy_jsstudy/am287h9k/
2 참조타입 ----------------------------------------------------   http://jsfiddle.net/pouy_jsstudy/bntj91w9/
3 함수호출call by value vs call by reference----------  http://jsfiddle.net/pouy_jsstudy/z6j87c7e/
4 기본타입과 표준메서드  --------------------------------  http://jsfiddle.net/pouy_jsstudy/564cv53u/
5 연산자 ------------------------------------------------------  http://jsfiddle.net/pouy_jsstudy/1jo2skuc/



1 자바스크립트 객체

1 객체만들기 --------- ---------------------------------------http://jsfiddle.net/pouy_jsstudy/ktqs5vtz/
2.1 객체의 속성property 사용하기 ----------------------- http://jsfiddle.net/pouy_jsstudy/Lrvgtx13/
2.2 for in문과 delete로 프로퍼티보기/삭제 ------------http://jsfiddle.net/pouy_jsstudy/bdL3g66f/
3 객체가 일하게 하자 function ---------------------------http://jsfiddle.net/pouy_jsstudy/djogo2u9/
4 생성자함수를 직접 정의해보자 + var선언 ---------- http://jsfiddle.net/pouy_jsstudy/kg3r13nu/
5 JS 객체의 종류: native, host, custom ---------------- http://jsfiddle.net/pouy_jsstudy/Ltgb2j21/
 
#심화: 
http://www.slideshare.net/heejaekim85/javascript-33832492 자바스크립트 객체생성 패턴
http://www.bsidesoft.com/318 자바스크립트에서 new는 어떤일을 하는가?
http://www.bsidesoft.com/319#%ea%b7%b8-%ec%99%b8%ec%9d%98-%ed%99%9c%ec%9a%a9 특히 포스팅에서 <2.함수가 생성될 때 일어나는 일>을 보면, 객체생성과정을 디테일하게 설명함.



2. Function함수객체 prototype, __proto__, constructor 프로토타입 체이닝

1 함수를 만드는 법 - http://jsfiddle.net/pouy_jsstudy/uufyxdrr/
2 semicolon ; 문제 - http://jsfiddle.net/pouy_jsstudy/4z8dqs18/
3 함수재귀호출 - http://jsfiddle.net/pouy_jsstudy/53zffw8b/
4 함수호이스팅 - http://jsfiddle.net/pouy_jsstudy/5p6pcmuk/
5 함수도 객체다!! - http://jsfiddle.net/pouy_jsstudy/bnwzuuLu/
6.1 함수객체의 기본프로퍼티 - http://jsfiddle.net/pouy_jsstudy/hp9rst46/
6.2 length프로퍼티 - http://jsfiddle.net/pouy_jsstudy/Lvk7coc3/
7.1 프로토타입체이닝1, 객체생성 뜯어보기 - http://jsfiddle.net/pouy_jsstudy/zpsbu78L/
7.2 프로토타입체이닝2,  hasOwnProperty()메서드로 프로토타입체이닝을 확인 - http://jsfiddle.net/pouy_jsstudy/5umg6hu8/
7.3 내장native built-in객체들의 표준메서드와 그 확장 - http://jsfiddle.net/pouy_jsstudy/8td00rej/
7.4.1 함수객체의 디폴트 프로토타입 변경1 - http://jsfiddle.net/pouy_jsstudy/y8vceput/
7.4.2 함수객체의 디폴트 프로토타입 변경2 - http://jsfiddle.net/pouy_jsstudy/mrbpyt3h/
7.4.3 함수객체의 디폴트 프로토타입 변경3 - http://jsfiddle.net/pouy_jsstudy/r2drhgyj/
7.5 prototype프로퍼티로 JS객체지향 맛보기 - http://jsfiddle.net/pouy_jsstudy/vr4o7yah/

  #서브예제:
http://jsfiddle.net/pouy_jsstudy/ung8hrx6/
#참고: http://www.ecma-international.org/ecma-262/5.1/ 표준 ECMA-262 v5.1 
##추가참고: ‘깨우치다’ 129p 참고.



3. 함수와 this, Array배열 

1 콜백함수 - http://jsfiddle.net/pouy_jsstudy/c5r4c35z/
2 즉시실행함수 - http://jsfiddle.net/pouy_jsstudy/4aotvcnL/
3 내부함수 -  http://jsfiddle.net/pouy_jsstudy/nnof3cj4/
4 함수를 리턴하는 함수 - http://jsfiddle.net/pouy_jsstudy/ujexf9ao/
5 함수의 arguments 객체 - http://jsfiddle.net/pouy_jsstudy/cg8ocp5e/

6.1 함수호출과 this, 특정 객체의 ‘메서드’ 호출 - http://jsfiddle.net/pouy_jsstudy/rzf9x1h0/
6.2 함수호출과 this,객체가 특정되지 않은 함수호출* - http://jsfiddle.net/pouy_jsstudy/a0upcaxr/
6.3 함수호출과 this, 간단예제 - http://jsfiddle.net/pouy_jsstudy/8kc0q6kz/
6.4 함수호출과 this, 내부함수 전역this참조 - http://jsfiddle.net/pouy_jsstudy/vcqvpLat/
6.5 that변수로 6.4코드를 의도대로 출력하기 - http://jsfiddle.net/pouy_jsstudy/6bLsrp7o/
6.6 생성자함수에서의 this - http://jsfiddle.net/pouy_jsstudy/5mf8tjp9/
6.7 new를 사용하지 않을 때의 문제와 패턴해결책 - http://jsfiddle.net/pouy_jsstudy/23paxu0h/
6.8 call()과 apply(), 함수의 this를 특정객체에 바인딩 -  http://jsfiddle.net/pouy_jsstudy/b4171hdt/
6.9 call()과 apply() 활용 - http://jsfiddle.net/pouy_jsstudy/fxx0zh2v/
7 함수의 리턴값(6.6생성자this이해)- http://jsfiddle.net/pouy_jsstudy/x8shgeuL/

8.1 배열의 생성과 사용 --------------------------------------- http://jsfiddle.net/pouy_jsstudy/d6y3est6/
8.2 배열의 표준메서드와 length프로퍼티 ---------------- http://jsfiddle.net/pouy_jsstudy/kkchyxet/
8.3 배열과 객체 --- http://jsfiddle.net/pouy_jsstudy/1ft2wq44/
8.4 배열의 프로퍼티 - http://jsfiddle.net/pouy_jsstudy/fsbmrbxk/
8.5 생성자함수, 유사배열객체 - http://jsfiddle.net/pouy_jsstudy/c2j928fy/




4. 실행컨텍스트, 스코프체인과 클로저

4.1 실행컨텍스트execution context --- http://jsfiddle.net/pouy_jsstudy/dapek2st/
4.2 실행컨텍스트 생성과정 -- http://jsfiddle.net/pouy_jsstudy/atnc822r/
4.3.1 스코프체인1 -- http://jsfiddle.net/pouy_jsstudy/0e0v0rmx/
4.3.2 스코프체인2--  http://jsfiddle.net/pouy_jsstudy/f0xw127d/
4.3.3 실행컨텍스트와 함수호이스팅 - http://jsfiddle.net/pouy_jsstudy/nzgpqj49/
4.3.4 pure javascript evil, with - http://jsfiddle.net/pouy_jsstudy/z54ugtLx/

4.4.1 클로저 개념 - http://jsfiddle.net/pouy_jsstudy/tgpdz7dg/
4.4.2 클로저 활용1, 특정함수에 커스텀메서드연결 - http://jsfiddle.net/pouy_jsstudy/a476dw3v/
4.4.3 클로저 활용2, 함수의 캡슐화 - http://jsfiddle.net/pouy_jsstudy/jmw0v91q/
4.4.4 클로저 활용3, 이벤트처리(html소스와함께) -  http://jsfiddle.net/pouy_jsstudy/d66p14ht/
4.4.5 클로저 활용4, setTimeout() -  http://jsfiddle.net/pouy_jsstudy/j09stbwg/
4.4.6 클로저 주의1 - http://jsfiddle.net/pouy_jsstudy/6uL902g5/
4.4.7 클로저 주의2 - http://jsfiddle.net/pouy_jsstudy/z85ygk0d/
4.4.8 클로저 주의3(4.4소스와함께) - http://jsfiddle.net/pouy_jsstudy/zqqeLh5y/


#참고: 
http://www.nextree.co.kr/p7363/


5. 객체지향 프로그래밍

5.1   자바스크립트 클래스 기반 객체지향 - http://jsfiddle.net/pouy_jsstudy/wotfekwo/
5.2.1 자바스크립트 프로토타입 기반 객체지향 - http://jsfiddle.net/pouy_jsstudy/4wtj6p83/
5.2.2 크록포드의 메서드 정의 방법 -  http://jsfiddle.net/pouy_jsstudy/5cch7y2t/
5.3.1 프로토타입 기반 상속 - http://jsfiddle.net/pouy_jsstudy/35qqmxwx/
5.3.2 상속을 위한 extend()함수 구현 -  http://jsfiddle.net/pouy_jsstudy/59nhnxqf/
5.4.1 클래스 기반 상속 - http://jsfiddle.net/pouy_jsstudy/o58t89q3/
5.5.1 자바스크립트 상속 심화1 - http://jsfiddle.net/pouy_jsstudy/zjgxe0o4/
5.5.2 자바스크립트 상속 심화2 - http://jsfiddle.net/pouy_jsstudy/njqdhb9b/
5.6.1 캡슐화 - http://jsfiddle.net/pouy_jsstudy/shom0678/
5.7.1 JS객체지향 응용 - http://jsfiddle.net/pouy_jsstudy/ka56y65s/


6. 함수형 프로그래밍

6.1.1 함수형 패러다임 적용 이전 - http://jsfiddle.net/pouy_jsstudy/7hrm34cy/
6.1.2 함수형 패러다임 적용 이후 - http://jsfiddle.net/pouy_jsstudy/cL3htz59/
6.2 함수형패러다임 중 '순수함수'의 의미 - http://jsfiddle.net/pouy_jsstudy/8hx741py/
6.3 함수형으로 구현한 factorial과 캐싱 - http://jsfiddle.net/pouy_jsstudy/pg6cv0m8/
6.4.1 함수형 패러다임이 적용된 JS함수1 curry -  http://jsfiddle.net/pouy_jsstudy/xzayh60u/
6.4.2 함수형 패러다임이 적용된 JS함수2 bind - http://jsfiddle.net/pouy_jsstudy/yoeerf64/
6.4.3 함수형 패러다임이 적용된 JS함수3 wrap - http://jsfiddle.net/pouy_jsstudy/rgh2wcLk/
6.4.4 함수형 패러다임이 적용된 JS함수4 each - http://jsfiddle.net/pouy_jsstudy/xo3tozxv/
6.4.5 함수형 패러다임이 적용된 JS함수5 map - http://jsfiddle.net/pouy_jsstudy/b2gxbjn2/

참고:
https://namu.wiki/w/%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D%20%EC%96%B8%EC%96%B4 4.5.1 함수형언어 항목. 
http://www.mimul.com/pebble/default/2014/10/04/1412396596338.html


7. jquery소스 분석

1. 	L2 version 2.1.3
2.	L5 셀렉터 엔진 sizzle.js: 2000여line에 이르는 셀렉터엔진 	
cdn: https://cdnjs.cloudflare.com/ajax/libs/sizzle/2.2.0/sizzle.js
	예제: http://jsfiddle.net/pouy_jsstudy/Lp8xsL0b/
3. 	L15~L9283 즉시실행함수 
L38 window객체를 global인자로, 익명함수(L38~L9283)를 factory인자로 넣어 실행한다.	
4.	L73 jQuery변수 최초 선언, 할당. new키워드와 init()함수로 객체생성/반환
5.	L92~L175 jQuery.fn에 함수정의, jQuery.prototype에 할당하여 new jQuery로 생성되는 모든 제이쿼리객체의 기본함수가 됨. toArray,get,pushStack,each,map,slice,first,last,eq,end
6.	L177~L240 jQuery객체의 기능을 확장하기 위한 jQuery.extend() 함수 정의, extend()함수에 대해서 5.3.2예제소스 참고. jQuery.extend=jQuery.fn.extend=함수로 같은 함수를 참조함. 
7. 	L242~L525  jQuery.extend()함수에 여러 개의 함수를 정의하여 묶는 모듈패턴으로 인자를 집어넣어 jQuery를 확장한다.
8.	L532~L546 객체가 배열 혹은 유사배열객체인지 검사하는 isArraylike()함수 정의. 7번의 함수확장에서 많이 사용된다.
9.	L547~ L2627 Sizzle객체를 리턴하는 즉시실행함수 sizzle.js코드.
예제: http://jsfiddle.net/pouy_jsstudy/rLL0vrxt/
10.	L2631 jQuery.find에 Sizzle할당.  jQuery.fn.extend()로 jQuery.prototype의 확장.

73라인에서 생성되는jQuery함수객체를 extend로 확장
92라인에서 jQuery.fn으로 참조되는 jQuery.prototype객체를 extend로 확장

11.	L9275에서 window.$, 즉 전역변수$는 jQuery함수객체를 참조하게 된다. 이에 따라 $(“#id”)와 jQuery(“#id”)가 같은 동작을 하게 된다. 
12. 	L2751에서 init함수가 $혹은 jQuery함수객체의 인자로 들어온 selector를 이용해 string인지 검사하고 <>태그를 제거하고, jQuery객체를 만들어낸다. 
13	L4101부터 이벤트 처리를 위한 함수코드
14.	L5288 jQuery.fn.extend함수로 text,append 등 익숙한 jquery함수들이 많이 구현되어 있다.
15.	L4834 src폴더의 7.html소스를 가지고 on(이벤트, 콜백함수)함수의 이벤트 처리과정을 쫓아가본다. 
16 .	L7695~L8962 1300여 라인에 걸쳐 ajax 기능 구현
	L8361 $.post, $.get 구현
	L8585 new키워드로 XMLHttpRequest객체 생성
17.	L9287 다양한 프로퍼티들로 확장된 jQuery객체를 최종 리턴함으로써 1만여줄에 가까운 즉시실행함수를 드디어;;; 마무리한다.



javascript garvage collection
http://www.html5rocks.com/ko/tutorials/speed/static-mem-pools/
https://developer.mozilla.org/ko/docs/Web/JavaScript/Memory_Management



