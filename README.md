## 자바스크립트 변수

#### 1. Variable (변할 수 있는 값) --> Mutable

_자바스크립트 변수는 let 을 사용_

_var 사용은 권장하지 않음 (너무 자유로음) block scope 도 없고 선언하기 전에 사용하여도 문제없음_

_var hoisting : var 를 맨위로 끌어올려 사용_

#### 2. Constant (한번 할당되면 변하지 않는 값) --> Immutable

_Constant 타입시 수를 가르키는 포인터가 잠겨있어 값을 변경 불가능_

#### 3. Primitive Type

_더 이상 작아질 수 없음(boolean, string, number, null, undefined, symbol)_

#### 4. Objective Type

_싱글타입들을 묶어놓은 것_

#### 5. Function, First class Function

_자바스크립트는 Function 도 데이터 타입중에 하나임 다른 데이터 타입처럼 변수설정 및 인자로 넘기는 것도 가능 리턴도 가능_

#### 6. 기타

_null 과 undefined 는 다른것임 null 은 let a = null; 선언하고 아무것도 아니라는걸 지정 let b; undefined는 아직 아무것도 하지않는 것_

_자바스크립트는 Dynamic typically language 임 선언시에 데이터 타입을 결정하는 것이 아니라 런타임 시에 타입을결정 (에러가 많이 발생 주의)_

## 연산자

_Procedure Language 는 function 이 굉장히 중요함_

_자바스크립트에서 function은 object 임_

_하나의 함수는 한가지 일 만 하도록 만들어야 함_

_함수에 return 문이 없는 것은 return undefined 임 return 자바스크립트는 return 생략 가능_

_local scope 밖에서는 안이 보이지 않고 안에서만 밖이 보인다_

_First-class Function : function은 다른 변수와 마찬가지로 할당도 가능 리턴도 가능_

_Callback Function --> 함수를 전달하여 상황에 적합할 시 이 함수를 호출_

_anonymous function 과 named function이 있음 (named function 이 디버깅시에 나음)_

_Arrow Function --> 함수를 간결하게 만들어 줌 anonoymous function 임 parameter 전달도 가능_

## Class 와 Object

_Class --> 조금 연관되어있는것들을 묶어 놓은 것들을 말 함_

_수강신청, 쇼핑몰, class 로 분류 묶는 연습 도움이 많이 됨_

_클래스는 template, declare once, date in --> Object를 만들기 위함_

_캡슐화는 함부로 변수설정을 외부에서 하지 않게 하기 위함 (setter/ getter)_

_static은 공통적으로 사용하는 것 항상 똑같은 것은 static을 붙여 메모리 낭비 줄이기_

_다형성 덕분에 획기적인 일들이 가능 !_

###### Heading 6

**bolic** (\*\_ 2개 감싸기 \* 1개로 감싸면 italic)
~~ 모양 두개로 감싸주면 strikethrough

~~strike~~

_italic_

앞에 \* 모양 하나로 감싸줄시 목록 list 로 만들어짐 - 작성도 가능 숫자도 가능

- 1
- 2
- 3

  1 1
  2 2
  3 3

| Header | (   | 로 감싸줄기 Table 형태로 가능 | --  | -- 로 하면됨) |
| ------ | --- | ----------------------------- | --- | ------------- |

테이블 정렬법도 있음

백티그로 감싸주면 컬러로 감싸짐
백티그로 감쌀 시 코드 블럭이 만들어져 코드작성이 용이

Github 는 Github 전용 Markdown 들이 있음 github markdown 숙지하기 !
