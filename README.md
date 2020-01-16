# background 

날짜:2020-01-16

---

-`background`는 요소의 배경을 설정한다.
-`background-color`는 요소의 배경 색상을 지정한다.
​-`background-image`는 요소의 배경에 하나 이상의 이미지를 삽입한다.다중으로 삽입할 경우 순서는 마지막이 밑으로 깔린다.
-`background-repeat`은 배경 이미지의 반복을 설정한다.
-`background-position`은 배경 이미지의 위치를 설정한다.사용법은 값이 방향일 경우 방향1과방향2과 방향2와방향1로 바뀌어도 상관없고, 값이 단위(%,   px 등)일 경우 x축과Y축은 바뀌면 값이 달라지게 되어서 바뀌면 안된다. 그리고 방향과 값을 동시에 같이 쓸수도 있는데 left,right는 x축에  
 top,bottom은 y축에 쓴다. 
-`background-attachment`는 요소가 스크롤될 때 배경 이미지의 스크롤 여부를 설정한다.
-`background- size`는 배경 이미지의 크기를 지정한다.
---
​
## 도식화
​                  (값)          (속성 값)         (기본값)       ㅣ               (값)
               -->color      =                    transparent   ㅣ            -->repeat(수직,수평 반복, 기본값)
               -->image      =  none,URL("경로")  none          ㅣ            -->repeat-X(수평 반복)
`(background)` -->repeat     =                    repeat        ㅣ  `(repeat)`-->repeat-Y(수직 반복)
​               -->position   =                    0 0           ㅣ            -->no-repeat(반복 없음)
               -->attachment =                    scroll        ㅣ
               -->size       =                                  ㅣ
​                                                                ㅣ
 
              -->scroll(요소를 따라 같이 스크롤 됨, 기본값)                 ㅣ           -->auto(원래의 크기로 표시,기본값)
`(attachment)`-->fixed (뷰포트에 고정되어 요소와 같이 스크롤 안됨.)          ㅣ   `(size)`-->단위(px,em,%) 
              -->local (요소 내 스크롤 시 배경 이미지가 같이 스크롤 됨.)     ㅣ           -->cover(크기 비율 유지,요소의 더 넓은 너비에 맞춰지고                                                                           이미지가 잘릴 수 있음.)
                                                                                       -->contain(크기 비율 유지,요소 더 짧은 너비에                 맞춰지고 이미지가 안 잘림.)


## 모르는 내용
​
