# Python

Python은 1991년에 발표된 Interpreter 방식의 프로그래밍 언어로 C, C++, Java 등과 더불어 많은 사람들이 아는 프로그래밍 언어 중에 하나입니다. Python은 현재 2019년 2월 기준, 프로그래밍 언어 전체 인기도 3위를 차지하고 있으며, 사람들이 이해하기 쉬운 문법의 고급 프로그래밍 언어입니다. 파이썬은 또한 다양한 모듈과 프레임 워크가 지원 되어서 Flask, Django 등을 활용한 Web 개발도 할 수 있으며 Pandas, Scikit-learn, Matplotlib 등을 활용하여 데이터 분석도 할 수 있을 뿐만 아니라 Numpy, Tensorflow, Keras 등도 지원되기 때문에 머신 러닝, 딥 러닝을 하는 많은 사람들이 파이썬을 사용합니다.
<br/>

## 변수(variable)
  데이터를 저장하는 공간입니다. <br/>
  메모리에 값을 생성하고 이름을 지정해줍니다. <br/>

### 변수 선언하는 방법
  C나 JAVA와 달리, Python은 변수에 저장된 값을 스스로 판단하여 자료형을 지정합니다. <br/>
<code>변수명 = 변수에 저장할 값(데이터)</code> <sub>여기서 '='는 대입 연산자 라고 합니다. </sub> <br/>
  
## 출력(print)
<code>print('Hello World!')</code> <sub>결과 : Hello World! </sub> <br/><br/>
<code>a = 20</code> <br/>
<code>print(a)</code> <sub>결과 : 20 </sub> <br/>

값을 출력하는데 사용합니다. <br/><br/>

## 입력(input)
<code>a = input()</code> <sub>입력 예시 : Hello! </sub> <br/><br/>
<code>print(a)</code> <sub>결과: Hello! </sub> <br/>

값을 입력하는데 사용합니다. <br/><br/>

<code>a = input().split()</code> <sub>입력 예시 : 10 20 30 </sub> <br/><br/>
<code>print(a)</code> <sub>결과: ['10', '20', '30'] </sub> <br/>

.split() 을 이용하면 띄어쓰기를 기준으로 각각을 원소로 하는 리스트가 만들어집니다. <br/>
리스트에 대한 내용은 아래에서 다루겠습니다. <br/><br/>

<code>a, b = input().split()</code> <sub>입력 예시 : 10 20 </sub> <br/><br/>
<code>print(a)</code> <sub>결과: 10  </sub> <br/>
<code>print(b)</code> <sub>결과: 20  </sub> <br/>
<code>print(a + b)</code> <sub>결과: 1020  </sub> <br/>

여기서 주의해야하는게 우리가 숫자를 정수로 생각하고 입력하더라도 우리가 입력한 값은 문자열입니다. <br/>
따라서 이와 같은 결과가 나오는 것입니다. 착각하여 고생하지 맙시다 :) <br/><br/>

만약 정수로 입력을 받고 싶다면, map을 사용할 수 있습니다.
<code>a, b = map(int, input().split())</code> <sub>입력 예시 : 10 20 </sub> <br/><br/>
<code>print(a)</code> <sub>결과: 10  </sub> <br/>
<code>print(b)</code> <sub>결과: 20  </sub> <br/>
<code>print(a + b)</code> <sub>결과: 30  </sub> <br/>

map에 대한 내용 역시 리스트를 다룰 때에 다시 다루겠습니다.

## 반복

### for
<code>for i in range(0, 10):  print(i)</code>

range 

enumerate
