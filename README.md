# Projeto-Vazamento-Agua
Sistema de monitoramento de umidade para detecção de possíveis vazamentos utilizando Arduino Uno, sensor DHT22, LEDs e buzzer.

Descrição do Projeto

Este projeto foi desenvolvido utilizando um Arduino Uno e um sensor DHT22 para monitorar a umidade do ambiente em tempo real. A proposta é identificar situações que possam indicar vazamentos de água ou níveis elevados de umidade, emitindo alertas visuais e sonoros para facilitar a percepção do problema. A solução foi simulada no Wokwi e utiliza LEDs e um buzzer para informar o estado do ambiente de forma simples e intuitiva.

Objetivo da Solução

O objetivo deste projeto é criar um sistema acessível e de baixo custo capaz de auxiliar na detecção precoce de possíveis vazamentos. Ao monitorar continuamente a umidade do ambiente, o sistema pode alertar o usuário antes que o problema cause desperdício de água, aumento de custos ou danos estruturais ao local.

Componentes Utilizados

Para o desenvolvimento da solução foram utilizados um Arduino Uno, um sensor DHT22, três LEDs nas cores verde, amarela e vermelha, um buzzer, três resistores de 220Ω, uma protoboard e fios jumper para realizar as conexões do circuito.

Funcionamento do Sistema

O sensor DHT22 realiza leituras constantes da umidade do ambiente e envia essas informações para o Arduino. Com base nos valores recebidos, o sistema classifica a situação em três níveis. Quando a umidade está em até 50%, o LED verde é acionado, indicando que o ambiente está em condições normais. Quando a umidade fica entre 51% e 70%, o LED amarelo acende, sinalizando um estado de atenção. Caso a umidade ultrapasse 70%, o LED vermelho e o buzzer são ativados, indicando uma possível anomalia hídrica ou vazamento. Além disso, todas as leituras e mensagens de status são exibidas no Monitor Serial da IDE Arduino.

Estrutura do Circuito e Execução

O sensor DHT22 foi conectado ao pino digital 2 do Arduino. Os LEDs foram ligados aos pinos 8, 9 e 10, representando os níveis normal, atenção e alerta, respectivamente. O buzzer foi conectado ao pino 11 para emitir alertas sonoros quando necessário. Todos os componentes foram montados em uma protoboard com resistores para proteção dos LEDs.

Para executar o projeto, basta montar o circuito conforme o esquema desenvolvido, abrir o código na IDE Arduino ou no simulador Wokwi, instalar a biblioteca DHT Sensor Library, compilar o programa e iniciar a execução. O funcionamento pode ser acompanhado pelos LEDs, pelo buzzer e pelas mensagens exibidas no Monitor Serial.

Integrantes do Grupo

Mariana de Souza Bruzadim (RM568864)

Donizetti Batista (RM569576)

Davi Gualberto (RM569825)

Arthur Nery (RM569088)

Rhuan Camargo (RM568967)

Link da Simulação

https://wokwi.com/projects/465379070421234689
