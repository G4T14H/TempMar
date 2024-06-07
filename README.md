Projeto de Monitoramento de pH com Arduino e LCD
Este projeto utiliza um Arduino para simular a leitura de um sensor de pH e exibir os valores de pH em um LCD. O código foi desenvolvido em C++ usando a IDE do Arduino.

Componentes Utilizados
Arduino Uno
LCD 16x2
Sensor de pH (simulado no código)
Potenciômetro (simulado para ajuste de valores de pH)
Resistores
Como Funciona
O Arduino lê um valor analógico simulado, que representa a leitura de um sensor de pH. Esse valor é então convertido em um valor de pH, que é exibido no LCD. O pH varia entre 4 e 8, simulando a faixa de pH da água.

Configuração do Hardware
Conecte os componentes conforme o esquema abaixo:

LCD:
Pino RS ao pino digital 12
Pino Enable ao pino digital 11
Pinos D4, D5, D6 e D7 aos pinos digitais 5, 4, 3 e 2, respectivamente
Sensor de pH (simulado):
Pino analógico ao pino A0 do Arduino
Potenciômetro (simulado):
Pino analógico ao pino A1 do Arduino
Instalação
Clone este repositório para o seu computador.
Abra o arquivo pH_monitoring.ino na IDE do Arduino.
Conecte o Arduino ao computador via USB.
Compile e faça o upload do código para o Arduino.
Execução
Após carregar o código no Arduino, o LCD começará a exibir os valores simulados de pH. Você pode observar como os valores variam entre 4 e 8 ao longo do tempo.

Licença
Este projeto está licenciado sob a Licença Temp Mar.
