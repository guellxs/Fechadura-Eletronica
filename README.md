#Fechadura Eletrônica com ESP32

Descrição: Este projeto implementa um sistema de controle de acesso baseado em uma fechadura eletrônica utilizando o microcontrolador ESP32.

Funcionalidades:

Entrada de senha via teclado matricial

Mascaramento da senha com '*'

Verificação de senha e acionamento da fechadura

Bloqueio após três tentativas erradas

Sensor anti-arrombamento (fim de curso)

Acionamento de alarme em caso de tentativa de violação

Display LCD para feedback ao usuário

Tecnologias Utilizadas:

Microcontrolador: ESP32

Linguagem: C

Framework: ESP-IDF

IDE: Visual Studio Code

Periféricos:

Teclado matricial

Display LCD

Sensor de fim de curso

Relé para controle da fechadura

Buzzer para alarme

Estrutura do Código:

Camada de hardware: Contém bibliotecas para controle de teclado, LCD e sensores.

Camada de serviços: Implementa o sistema de autenticação e controle da fechadura.

Camada de aplicação: Gerencia o fluxo do sistema através de uma máquina de estados.
