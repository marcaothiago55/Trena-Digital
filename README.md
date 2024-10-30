Projeto da Trena Digital em Arduino
Objetivo do Projeto
Medir distâncias usando um sensor ultrassônico.

Componentes Utilizados

Arduino Uno
Display OLED (SSD1306)
Sensor Ultrassônico (HC-SR04)
LEDs (verde e vermelho)
Buzzer
Estrutura do Código

setup(): Inicializa display, LEDs e comunicação serial.
loop(): Executa leitura de distância e controla displays e LEDs.
Funções Principais

readUltrasonicDistance(): Lê a distância usando o sensor.
mostrarDistanciaOLED(): Exibe a distância no display.
controleLEDs(): Acende LEDs baseado na distância medida.
Leitura da Distância
O sensor emite um pulso e mede o tempo que leva para voltar.
Calcula a distância com a fórmula.

Apresentação dos Dados
Exibe distância em centímetros e polegadas no OLED.
Informações do autor e versão são mostradas abaixo.

Controle dos LEDs

LED verde acende se a distância for ≤ 50 cm.
LED vermelho acende se a distância for > 50 cm.
Alerta Sonoro
O buzzer emite som se a distância for ≤ 50 cm.

Extensões e Melhorias

Ajustar limites de distância.
Adicionar modos de medição.
Melhorar a interface do display.
Conclusão
Integra sensores, displays e controle de LEDs,
promovendo aprendizado em eletrônica e programação.
Se precisar de mais detalhes, é só perguntar!
