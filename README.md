# Projeto MQTT - Teste de Publicação e Assinatura

## Autor
- **Rian** - SESI SENAI de CPV

## Descrição
Este projeto tem como objetivo testar a comunicação entre um cliente de publicação e um cliente de assinatura usando o protocolo MQTT. O projeto é dividido em duas partes:  
- **subscriber.py**: Responsável por se inscrever no tópico e receber mensagens.  
- **publisher.py**: Responsável por enviar mensagens ao tópico.

## Pré-requisitos
Antes de rodar o código, é necessário ter o Python 3.x instalado em sua máquina e a biblioteca `paho-mqtt`.

### Instalar a biblioteca necessária
Execute o seguinte comando para instalar a biblioteca `paho-mqtt`:

```sh
pip install paho-mqtt
