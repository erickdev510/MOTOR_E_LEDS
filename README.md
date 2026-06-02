# Projeto IoT - 3 MOTORES ⚙️




O projeto simula um sistema eletrônico de controle de acesso inteligente. Ele integra componentes eletrônicos para criar uma interface simples e funcional, permitindo visualizar informações no display, controlar estados com botões e representar mecanicamente a abertura e fechamento das portas através do servo motor.




## Sobre o Projeto 📚
A atividade propõe o desenvolvimento de um protótipo de controle de acesso para três portas utilizando um ESP32, display OLED, botões, LEDs e servo motor. O objetivo é sim ular o funcionamento de um sistema de segurança que controla o acesso a diferentes ambientes de uma instituição. Cada porta representa um ambiente específico:

Porta 1 → Laboratório de Informática Porta 2 → Sala dos Professores Porta 3 → Almoxarifado de Equipamentos

O sistema deve permitir que o usuário selecione uma das portas por meio dos botões. Após a seleção, o display OLED mostra qual porta foi escolhida e informa se ela está bloqueada ou liberada. Os LEDs funcionam como indicadores visuais do estado do acesso, enquanto o servo motor representa a trava da porta.

Quando a porta estiver:

Bloqueada → servo em 0° Liberada → servo em 90°



## Componentes 📚
ESP32
Display OLED I2C
3 micro servos
Protoboard
5 botões (PUSHBUTTON)
LEDs coloridos
Resistores


![imagem](https://github.com/erickdev510/MOTOR_E_LEDS/blob/main/MOTOR_e_LEDS.png)
