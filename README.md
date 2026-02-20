# Projeto MQTT - Publisher & Subscriber

Projeto simples utilizando **MQTT** em Python para envio e recebimento de mensagens usando um broker público.

## Sobre o projeto
Este projeto simula a comunicação entre dispositivos IoT:

- **publisher.py** → envia mensagens para um tópico
- **subscriber.py** → recebe mensagens do mesmo tópico

O broker utilizado é público: `broker.hivemq.com`

---

## Pré-requisitos

Antes de começar, você precisa ter instalado:

- Python 3.x
- pip (gerenciador de pacotes do Python)

---

## Instalação da biblioteca

Instale a biblioteca necessária com o comando:

```bash
pip install paho-mqtt
```

---

## Como executar o projeto

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
```

2. Execute o Subscriber:

```bash
python subscriber.py
```

3. Execute o Publisher (em outro terminal)

```bash
python publisher.py
```

4. Veja a comunicação acontecer
-> As mensagens digitadas no publisher aparecerão no subscriber.

---

## Como funciona
- O Publisher envia mensagens para o tópico senai/dev
- O Subscriber fica escutando esse tópico
- Quando uma mensagem é publicada, ela é recebida em tempo real

---

## Informações do Broker
- **Broker:** broker.hivemq.com
- **Porta:** 1883
- **Tópico:** senai/dev

---

## Créditos
Projeto baseado na aula de Redes IoT - Prof. Luis Felipe Cardoso (SENAI)
