# Ventilador IoT com Sensor de Movimento

Trabalho final da disciplina de IoT. O projeto detecta a presença de uma pessoa no ambiente com um sensor de movimento (PIR) e gira o ventilador na direção dela. Na simulação, o ventilador é representado por um servo motor.

## Simulação

O projeto está no Wokwi: https://wokwi.com/projects/481796301081077761

Para testar, abra o link, clique em ▶ para iniciar a simulação e clique no sensor PIR para simular um movimento.

## Como funciona

- O sensor PIR (pino 9) verifica se há movimento no ambiente.
- Com movimento detectado, o servo (pino 8) gira até 150°, na direção da pessoa.
- Sem movimento, o servo volta ao centro (90°).
- O servo se move 1° por segundo, e o estado atual aparece no Monitor Serial (9600 baud).

## Componentes

- Placa compatível com Arduino
- Sensor de movimento PIR
- Servo motor (representa o ventilador)

## Integrantes

- Henrique Laroque
- Lucas Fernandes
- Gustavo Kirst
- Rafael Medeiros
