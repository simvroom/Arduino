# Arduino
졸음 및 부주의를 경고하는 소리와 진동을 출력한다. 피에조 부저를 통해 특정 멜로디의 소리를 출력하고, 
동시에 진동 모터가 포함된 진동 모듈을 이용하여 강한 세기의 진동을 출력한다. 안전벨트에 디바이스를 부착하여
운전중 졸음과 부주의에 대해 운전자에게 즉각적이고 직접적으로 신호를 전달하여 운전에 집중할 수 있도록 도와준다.

블루투스 모듈 HC-06을 통해 라즈베리파이와 블루투스 시리얼 통신을 설정한다. 라즈베리파로부터 신호(문자열)를 
전달받으면 진동 모듈과 소리 센서가 동시에 10초 동안 작동한다. 소리 센서에서는 0.5초 간격으로 '삐-' 소리를 출력한다.
10초 이후에 디바이스는 작동하지 않으며, 신호가 다시 전달되면 앞선 동작을 반복한다.

![image](https://github.com/simvroom/Arduino/assets/129640503/e61caeb3-50e0-49e1-beea-e14ef84ff101)
![image](https://github.com/simvroom/Arduino/assets/129640503/e3ce9794-45cd-40b7-b023-edd5b2e858c5)

오류로 인한 신호전달로 디바이스가 작동했을 경우 운전에 오히려 방해가 될 수 있다. 
이를 예방하기 위하여, 신호를 수동으로 제어(OFF)할 수 있는 버튼을 추가할 예정이다.

Fusion360을 통해 완전한 디바이스를 제작 및 설계할 것이며, 이때 3D 프린터를 이용할 예정이다.
