# Gtec

Nosso objetivo é tornar o mundo um lugar mais sustentável por meio da nossa paixão, que é a tecnologia. A seguir segue o passo a passo para a implementação de nosso protótipo de sensor de monitoramento botânico batizado de Gtec.

## Hardware
1. Arduino UNO
2. ProtoBoard
3. Sensor DHT11 na porta digital 10
4. Sensor LDR na porta digital A2

## Arduino IDE
1. No canto superior direito, clique em Ferramentas > Gerenciar Bibliotecas...
2. Instale as seguintes Bibliotecas:
   - ArduinoJson
   - DHT sensor library
3. Copie e cole o código presente no arquivo Código-arduinoIDE.txt, presente na pasta códigos.


## Node-red
1. Faça a instalação do Node.js - www.nodejs.org
2. Abra  o CMD e digite o seguinte comando :
   - npm install -g --unsafe-perm node-red
3. Após a instalação, para acessar o recurso digite:
   - node-red
4. Acesse com seu browser a URL:
   - http://localhost:1880
5. Já dentro da plataforma, acesse o menu no canto superior direito e clique em "Manege palette" depois em "Install" e instale o seguinte pallete:
   - node-red-node-serialport


## Configulando nós
Dentro do node-red configure os nós da seguinte forma:


