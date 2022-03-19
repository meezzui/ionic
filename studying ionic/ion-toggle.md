### ion-toggle 기능 사용하기
<img width="350" height="350" src="https://user-images.githubusercontent.com/86812098/159123201-cc4d0efb-40a8-48cc-b9d7-252d73a60212.png">

+ 토글은 단일 옵션의 상태를 변경한다.
+ 누르거나 스와이프하여 켜거나 끌 수 있다.
+ `ion-toggle` 기능 사용법
  + `ionicToggle`을 `import`하고 `default`안의 `name`에 `ionToggle`을 추가해주어야 한다.
  + 그리고 태그이름은 `ion-toggle`이라고 적으면 된다. 
  + 이 기능은 `css`를 적용할 때 따로 `class`나 `id`값을 주지 않고 그냥 이름 그대로 지정해서 써주면 된다.
  + `css`를 적용할 때는 속성 앞에 `--`를 붙여 주어야 기능이 적용된다.
 
  ```node
  ion-toggle {
  --background: #000; //toggle 배경 색
  --background-checked: #7a49a5; // 체크 되었을 때 배경색

  --handle-background: #7a49a5;
  --handle-background-checked: #000;
  }
  ```
