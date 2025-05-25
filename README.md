🌱 Projeto IoT – Irrigação Automática com ESP8266
📘 Projeto desenvolvido para a disciplina de Objetos Inteligentes Conectados
Este projeto tem como objetivo automatizar a irrigação de um jardim utilizando Internet das Coisas (IoT). Para isso, é utilizado um sensor de umidade do solo (higrômetro), que detecta as condições do solo e, por meio do módulo Wi-Fi NodeMCU ESP8266, envia comandos para acionar a irrigação automaticamente.

⚙️ Funcionamento
Quando o solo está seco, o sistema:

Acende o LED vermelho

Aciona a bomba de água via módulo relé

Quando o solo está úmido, o sistema:

Acende o LED verde

Mantém a bomba desligada

As informações do sensor também são enviadas via MQTT e podem ser monitoradas remotamente através do aplicativo MQTT Dash.

🧾 Conteúdo deste repositório
Neste repositório, você encontrará:

Código-fonte Arduino (.ino) com comentários explicativos

Documentação do projeto com descrições técnicas

Artigo explicativo sobre os objetivos e funcionamento do sistema

Vídeo de demonstração da solução implementada

📹 Assista ao vídeo do projeto no YouTube: https://www.youtube.com/watch?v=M2FlXNyD050

🧩 Componentes utilizados
NodeMCU ESP8266 (Wi-Fi)

Sensor de umidade do solo (higrômetro)

LEDs (vermelho e verde)

Módulo relé

Mini bomba de água

Protoboard e jumpers

Node-RED (Broker MQTT)

Aplicativo MQTT Dash
