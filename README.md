# F411_LAB
F411_LAB

<details>
<summary><b>초음파 거리 측정</b></summary>

HC-SR04로 거리를 측정한다.

![NUCLEO-F411RE 보드 연결](images/board.png)

### 하드웨어

| 항목 | 내용 |
|------|------|
| 보드 | NUCLEO-F411RE (STM32F411RE) |
| 센서 | HC-SR04 |
| TRIG | PA1 (출력) |
| ECHO | PA0 (EXTI 입력) |
| 타이머 | TIM1, 1 MHz (1 tick = 1 µs) |
| 시리얼 | USART2, 115200 8N1 (PuTTY로 확인) |

![PuTTY 시리얼 출력과 STM32CubeIDE 코드](images/putty_output.png)

![오실로스코프 측정 파형](images/oscilloscope.png)

### SWV

![SWV 데이터 트레이스 타임라인 그래프](images/swv.png)

</details>

<details>
<summary><b>초음파+온습도</b></summary>

![NUCLEO-F411RE 핀맵](images/pinout.png)

![핀 할당 표](images/pin_table.png)

![NUCLEO-F411RE 보드 연결 (초음파+온습도)](images/board_dht.png)

![STM32CubeIDE 코드와 PuTTY 출력](images/ide_putty_dht.png)

![SWV 데이터 트레이스 타임라인 그래프 (echo, dht, trig)](images/swv_dht.png)

</details>
