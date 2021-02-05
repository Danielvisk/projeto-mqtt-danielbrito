# Repositorio da Sprint  8

## Resumo  do projeto

o propósito desse projeto é  ultilizar o arduino uno com um Sensor magnético para   monitorar se a porta do rack
de Rede está ABERTO ou FECHADO; enviar essa informação via Internet utilizando o protocolo MQTT (Message
Queuing Telemetry Transport) para um servidor MQTT hospedado na Amazon Web Service (AWS) e exibir a informação 
em um cliente MQTT[(Mqtt Dash)](https://play.google.com/store/apps/details?id=net.routix.mqttdash&hl=en&gl=US)
intalado em um celular,conforme na imagem abaixo.


![foto]( https://camo.githubusercontent.com/7beef2d4780d87a603d7de49b2da0467c8537dff96575b628a04bd4010ebb1cc/68747470733a2f2f692e696d6775722e636f6d2f4d576870586b562e706e67)
 
Foram utilizadas as seguintes biblioteca:

* [UIPEthernet](https://github.com/UIPEthernet/UIPEthernet)(conexao  do ENC28J60 com o arduino)
* [PubSubClient](https://github.com/knolleary/pubsubclient)(cliente MQTT para o Arduino)

#  Materiais

* Arduino Uno
* Módulo Ethernet (ENC28J60)
* Sensor Magnético (MC-38)
* Jumpers

# Circuito do Projeto
![projeto](https://camo.githubusercontent.com/ad1da211b35b60b23fb095a64e76dc6504d0c3229e853bd82a69a4d5d27bbb88/68747470733a2f2f692e696d6775722e636f6d2f594947477453472e706e67)

Autor : Daniel Brito

[![gmail Badge](https://img.shields.io/badge/-gmail-blue?style=flat-square&logo=gmail&logoColor=white&link=https://)](https://mail.google.com/mail/mu/mp/985/#tl/priority/%5Esmartlabel_personal)

[![instagram Badge](https://img.shields.io/badge/-instagram-purple?style=flat-square&logo=Instagram&logoColor=white&link=https://)](https://www.instagram.com/danielbritoo01/)


[![facebook Badge](https://img.shields.io/badge/-facebook-darkblue?style=flat-square&logo=facebook&logoColor=white&link=https://)](https://m.facebook.com/daniel.brito.5494360)


[![linkedin Badge](https://img.shields.io/badge/-linkedin-black?style=flat-square&logo=linkedin&logoColor=white&link=https://)](https://www.linkedin.com/mwlite/me)
