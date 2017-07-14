ROS Serial을 사용하는데 디버깅을 위한 STM32F407Discovery용 인터페이스 펌웨어입니다.
==========

Pin Descrip
------------
PA2 UART_TX
PA3 UART_RX

Firmware Descrip
----------------
###order character
'!' read mode
'$' clear
'%' show status
<hr/>
길이 100의 ring 버퍼를 이용하여 입력을 받을 수 있고, 오버플로우를 알려준다. 