Fazer a IDE do Arduino reconhecer os módulos ESP8266
====================================================

Estas instruções se referem ao vídeo mostrado [aqui](https://youtu.be/Xcg8fAQ49Uw).

### Instalando a biblioteca utilizando o gerenciamento de placas da IDE do Arduino ###

À partir da versão 1.6.4, a IDE do Arduino permite a instalação de pacotes de plataforma de terceiros usando o Gerenciador de Placas.
Existem pacotes disponíveis para Windows, Mac OS e Linux (32 e 64 bits).

Instale Arduino 1.6.9 à partir do site da Arduino.
Abra a IDE do Arduino e vá em Preferências.
Digite http://arduino.esp8266.com/stable/package_esp8266com_index.json no campo URLs adicionais de Gerenciadores de Placas.
Você pode adicionar várias URLs, separando com vírgulas.
Abra o Gerenciador de Placas a partir do menu Ferramentas > Placa e instale plataforma esp8266 (e não se esqueça de selecionar sua placa ESP8266 de menu Ferramentas > Placa após a instalação).

### Conteúdo das pastas ###

* A pasta "ESP8266_HelloWorld" contém o código que deve ser colocada na IDE do arduino.
* A pasta Esquematico contém os esquemáticos do circuito.

### Com quem falo para obter ajuda? ###

* Em caso de dúvidas, críticas ou sugestões, envie e-mail para marco.rabelo@gmail.com
* [Inscreva-se no meu canal](https://www.youtube.com/channel/UC05P95nXawYc15gIpN8GFPw?sub_confirmation=1) no youtube para receber as novidades.