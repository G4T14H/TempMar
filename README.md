Projeto de Monitoramento Ambiental com Arduino

Este é um projeto de monitoramento ambiental utilizando um Arduino para capturar e exibir informações de pH, profundidade e fluxo em um display LCD e no monitor serial.

Componentes Utilizados:

Arduino Uno
Sensor de pH
Sensor ultrassônico (HC-SR04) para medição de profundidade
Sensor de fluxo
Potenciômetro
Display LCD 16x2
Jumpers e resistores
Configuração do Hardware:

Conecte o sensor de pH ao pino A0 do Arduino.
Conecte o sensor de fluxo ao pino A1 do Arduino.
Conecte o sensor ultrassônico ao pino trigPin (7) e echoPin (6) do Arduino.
Conecte o potenciômetro ao pino A1 do Arduino.
Conecte o display LCD aos pinos rs, en, d4, d5, d6 e d7 do Arduino.
Funcionamento:

O Arduino lê o valor do potenciômetro para ajustar o contraste do display LCD.
O sensor de pH fornece informações sobre o pH da solução.
O sensor ultrassônico mede a profundidade da água.
O sensor de fluxo mede o fluxo de água em litros por minuto.
As informações coletadas são exibidas no display LCD e no monitor serial.
Instalação:

Baixe e instale a IDE do Arduino em seu computador, se ainda não o fez.
Conecte o Arduino ao computador usando um cabo USB.
Abra o arquivo do código-fonte do Arduino.
Verifique se a placa e a porta estão selecionadas corretamente na IDE.
Faça o upload do código para o Arduino.
Observações:

Certifique-se de calibrar o sensor de pH adequadamente para obter leituras precisas.
As medições de profundidade e fluxo podem variar dependendo das condições do ambiente.
Este projeto pode ser expandido para incluir mais sensores ou funcionalidades, como armazenamento de dados ou controle remoto.

Licença:
Este projeto é licenciado sob a Temp Mar.
