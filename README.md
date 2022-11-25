# Task_Scheduler
 Task Scheduler for Cortex Mx processors

* The project is developed in STM32Cube IDE.
* The code is written specifically for STM32F407G-DISC1 board.
* The task scheduler main code is in the file 'main.c' 
<br>`Task_Scheduler > Src > main.c` </br>
* The Scheduler is PendSV, and the sysTick handler is used to pend the PendSV exception.