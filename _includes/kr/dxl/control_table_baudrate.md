제어기와 통신하기 위한 통신 속도 입니다. 0 ~ 254 (0xFE) 까지 사용 가능하며 산출 공식은 다음과 같습니다.  
Baudrate(BPS) = 2,000,000 / (Value + 1)

| 값     | 통신속도(bps)     | 오차율     |
| :------------: | :------------: | :------------: |
|1|1M|0.000 [%]|
|3|500,000| 0.000 [%]|
|4|400,000| 0.000 [%]|
|7|250,000| 0.000 [%]|
|9|200,000| 0.000 [%]|
|16|115200| -2.124 [%]|
|34(초기값)|57600| 0.794 [%]|
|103|19200| -0.160 [%]|
|207|9600| -0.160 [%]|

`참고` UART는 Baudrate 오차가 3 [%] 이내이면 통신에 지장이 없습니다.
{: .notice}
