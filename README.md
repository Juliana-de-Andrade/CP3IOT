#Projeto IoT com ESP32 e MQTT

Descrição
Este projeto tem como objetivo implementar um sistema de comunicação IoT utilizando o protocolo MQTT com o microcontrolador ESP32. A comunicação é feita entre o ESP32 e uma máquina virtual Linux hospedada na Microsoft Azure, onde estão instalados o Node-RED e o Mosquitto Broker.

Etapas do Projeto
✅ Etapa 1 – Configuração do Servidor na Azure
Criação de uma máquina virtual Linux (Ubuntu) na plataforma Azure.

Instalação e configuração do Mosquitto MQTT Broker.

Instalação do Node-RED para visualização dos dados em tempo real.

✅ Etapa 2 – Comunicação com o ESP32
Desenvolvimento de um código no ESP32 para simular o envio de dados ambientais:

Temperatura

Umidade

Pressão atmosférica

Altitude

Publicação dos dados simulados via protocolo MQTT para o broker Mosquitto na VM.

Visualização e tratamento dos dados recebidos via Node-RED.
