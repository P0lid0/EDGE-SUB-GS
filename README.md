# EDGE-SUB-GS
O sistema deve registrar na memória EEPROM o valor da temperatura média em graus Celsius (ºC) e a luminosidade média (em uma escala de 0 a 100%) todas as vezes que a temperatura da água exceder 23ºC. Este parâmetro é essencial para observar a relação entre a incidência solar e o aumento da temperatura da água.

Os valores médios são calculados a partir de 30 leituras realizadas ao longo de 1 minuto, com uma leitura a cada 2 segundos. A média simples das leituras é utilizada para determinar tanto a temperatura quanto a luminosidade médias, que são então armazenadas na EEPROM.

Toda vez que a temperatura exceder o valor de 23° haverá um "bip" emitido, e também existe um gráfico de LEDs que demonstram em porcentagem a quantidade de luminosidade sendo recebida e tudo isso e mostrado no LCD.






