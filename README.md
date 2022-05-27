# Remember_Python_Basics
잊어버린 Python 생기초에 대해서 다시 한번 리마인드 하기 위한 정리 되지 않는 끄적이는 파일
### print함수<br>
 * sep : 구분자, 각 출력할 변수와 변수 사이에서 구별하는 역할을 함. <br>
 * end : 마지막에 출력할 문자열 <br>

### variable naming (변수 이름 규칙)
 * 숫자로 시작하는 이름을 제외하고 영문 대소문자, _, 숫자로 구성가능
 * 일반적으로 해당 변수를 표현하고자 하는 정확하고 간결한 이름을 사용하는 것이 원칙
 * e.g)  a = 1000보다 student_num = 1000으로 명시하는 것이 변수에 대한 이해가 더 빠름.<br>

### reserver keyword(예약어)
* python에서 미리 선점하여 사용 중인 키워드
* 변수, 함수, 클래스 등등의 사용자 정의 이름으로 사용 할 수 없음.
* e.g) class = 100.  .. for, while, class, try, excapt 

### type 함수
* 해당 변수, 값의 타입을 알고자 할 때 사용<br>
e.g) type(n)


### None
* 아무런 값을 갖지 않을 때 사용
* 일반적으로 변수가 초기값을 갖지 않게 하여 해당 변수 생성 시 하용
* 타 언어에서는 null, nil ..

### escape string
* 문자열 내의 일부 문자의 의미를 다리하여 특정한 효과 
* \n : new line 
* \t : tab

### indexing & slicing string ( 문자열 인덱스 및 추출)
* 인덱스가 하나의 문자만을 추출한다면, slicing은 부분 문자열을 추출 할 수 있음.
* [시작:끝] 와 같이 명시하여 [시작:끝]에 해당하는 부분 문자열 추출
* 시작, 끝 인덱스가 생략이 되어 있다면 0 부터 끝까지로 간주함.
*e.g)
* a = 'Hello world'  
* a[0:4] ==   'Hell' 출력

### replace
* 문자열 내의 특정 문자 치환
* e.g)
* a = 'hello world'
*     a.replace('h', 'j')
*     print) jello world


### format
* 문자열 내의 특정한 값을 변수로부터 초기화하여 동적으로 문자열 생성
* e.g)
* temp = 22.5
* prob = 80.0
* a = '오늘 기온{}도 이고, 비올 확률은 {}%입니다.'.format(temp, prob)
* print) 오늘 기온22.5도 이고, 비올 확률은 80.0%입니다.

###split
* 문자열을 특정한 문자 구분하여 문자열의 리스트로 치환
*e.g)
* a = 'hello world what'
* a.split()
* print) ['hello', 'world', 'what']

* a.split(w)
* print) ['hello', 'orld', 'hat']
* 값을 넣어줄 경우 값에 대한 부분 제외 split
