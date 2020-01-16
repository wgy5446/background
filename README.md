# background 

날짜:2020-01-16

---

-`background`는 요소의 배경을 설정한다.

-`background-color`는 요소의 배경 색상을 지정한다.

​-`background-image`는 요소의 배경에 하나 이상의 이미지를 삽입한다.다중으로 삽입할 경우 순서는 마지막이 밑으로 깔린다.

-`background-repeat`은 배경 이미지의 반복을 설정한다.

-`background-position`은 배경 이미지의 위치를 설정한다.사용법은 값이 방향일 경우 방향1과방향2는 방향2와방향1로 바뀌어도 상관없고, 값이 단위(%,   px 등)일 경우 x축과Y축은 바뀌면 값이 달라지게 되어서 바뀌면 안된다. 그리고 방향과 값을 동시에 같이 쓸수도 있는데 left,right는 x축에  
  top,bottom은 y축에 쓴다. 

-`background-attachment`는 요소가 스크롤될 때 배경 이미지의 스크롤 여부를 설정한다.

-`background- size`는 배경 이미지의 크기를 지정한다.

___
## 도식화​

| background type | 기본 값 |  
|---|---:|                     
| color | transparent |        
| image | none, URL("경로") | 
| repeat | repeat |
| position | 0 0 |
|attachment|scroll|
|size|auto| 
___
|repeat 속성 값| 의미 |
|---|---:|
|repeat|수직 or 수평 반복|
|repeat-X|수평 반복|
|repeat-Y|수직 반복|
|no-repeat|반복 없음|
___
|attachment 속성 값| 의미 |
|---|---:|
|scroll|요소를 따라 같이 스크롤 됨|
|fixed|뷰포트에 고정되어 요소와 같이 스크롤 안됨|
|local|요소내 스크롤 시 배경이미지가 같이 스클롤 됨|
___
|size 속성 값|의미|
|---|---:|
|auto|원래의크기로 표시|
|단위|px,em,%|
|cover|크기비율 유지, 요소의 더 넓은 너비에 맞춰 이미지가 잘림|
|contain|크기비율 유지, 요소의 더 짧은 너비에 맞춰 이미지가 안 잘림|
___



​
