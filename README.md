2 b) PA8 TIM1_CH1
  d) 16
  e) 10 kHz
  
3 b) sConfigOC.Pulse = 50;

4 c) sConfigOC.Pulse = 25;
  d) 1. htim1.Instance->CCR1 =dutyCycle   --->  Sprememba dutycycle-a preko registra.
     2. dutyCycle+=10;                    --->  Dodaja 10% širine impulza.
     3. if(dutyCycle>90) dutyCycle=10;    --->  Če je dutyCycle manj kot 90% naj se dutyCycle resetira na 10
