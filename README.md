# Repositorio da Sprint  8

## Resumo  do projeto

o propósito desse projeto é  ultilizar o arduino uno com um Sensor magnético para   monitorar se a porta do rack
de Rede está ABERTO ou FECHADO; enviar essa informação via Internet utilizando o protocolo MQTT (Message
Queuing Telemetry Transport) para um servidor MQTT hospedado na Amazon Web Service (AWS) e exibir a informação 
em um cliente MQTT[(Mqtt Dash)](https://play.google.com/store/apps/details?id=net.routix.mqttdash&hl=en&gl=US)
intalado em um celular,conforme na imagem abaixo.


![foto]( https://camo.githubusercontent.com/7beef2d4780d87a603d7de49b2da0467c8537dff96575b628a04bd4010ebb1cc/68747470733a2f2f692e696d6775722e636f6d2f4d576870586b562e706e67)
 
Foram utilizadas as seguintes bibliotecas

* [UIPEthernet](https://github.com/UIPEthernet/UIPEthernet)(conexao
