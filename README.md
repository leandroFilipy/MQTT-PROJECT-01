🔗 Conexão MQTT – Projeto em Sala com o Professor
📌 Descrição
Este repositório contém um código desenvolvido em conjunto com o professor, cujo objetivo é realizar a conexão com um broker MQTT e testar a comunicação entre dispositivos ou aplicações.

O MQTT (Message Queuing Telemetry Transport) é um protocolo leve de mensagens, muito utilizado em projetos de IoT (Internet das Coisas) por sua eficiência em redes com baixa largura de banda e por consumir poucos recursos.

📡 O que o código faz?
🔐 Estabelece conexão com um broker MQTT (como Mosquitto, HiveMQ, etc.)

📥 Inscreve-se em um ou mais tópicos MQTT

📤 Publica mensagens em tópicos específicos

📄 Exibe mensagens recebidas no console

💡 Pode ser adaptado para comunicação entre sensores, atuadores, ou softwares de automação

🧪 Tecnologias utilizadas
🧠 Linguagem: (Ex: Python, JavaScript, C, etc.)

📦 Bibliotecas: (Ex: paho-mqtt, mqtt.js, etc.)

🌐 Broker MQTT: Mosquitto / HiveMQ / outro

💻 Ambiente: VSCode, Arduino IDE, Node-RED (dependendo do projeto)

📁 Estrutura do projeto
css
Copiar
Editar
mqtt-conexao/
├── main.py (ou main.js, main.ino, etc.)
├── README.md
▶️ Como executar
Pré-requisitos: Ter o broker MQTT instalado localmente ou usar um online (ex: broker.hivemq.com)

bash
Copiar
Editar
# Exemplo em Python
pip install paho-mqtt
python main.py
Ou siga os passos de acordo com a linguagem usada.

🧑‍🏫 Sobre o desenvolvimento
Este código foi feito colaborativamente em sala de aula, com acompanhamento do professor. O objetivo foi compreender na prática como funciona:

A assinatura e publicação de tópicos MQTT

A estrutura cliente-servidor do protocolo

Aplicações reais de comunicação assíncrona



👨‍🏫 Professor [Nome do professor, se quiser colocar]

🎯 Objetivos didáticos
Aprender a configurar e conectar a um broker MQTT

Compreender o ciclo publish-subscribe

Aplicar o protocolo em simulações de projetos de IoT

Praticar a integração entre hardware, software e redes

