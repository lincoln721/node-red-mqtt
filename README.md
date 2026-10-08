# Aula RSFI - MQTT com Node-RED

Trabalho da aula **RSFI - Protocolo MQTT**.

## 📌 Descrição
Implementação prática do protocolo MQTT (Publish/Subscribe) utilizando o Node-RED e o broker público `broker.hivemq.com:1883`.

## 📂 Conteúdo da pasta `flows/`
- `01-exercicio-mqtt-pub-sub.json`: Fluxo com `inject` -> `mqtt out` e `mqtt in` -> `debug` no tópico `ifsp/turma-x/teste`.
- `02-recipes-mqtt-json-retained.json`: Exemplo de publicação JSON tratada e mensagem retida (*retained*).
- `03-desafio-http-endpoint.json`: Desafio de HTTP Endpoint (`GET /api/status`) e requisição HTTP externa com `http request`.

## 🚀 Como Executar
1. Inicie o Node-RED (`node-red` no terminal).
2. Acesse `http://127.0.0.1:1880`.
3. Vá no menu (☰) -> **Import** -> selecione os arquivos JSON da pasta `flows/`.
4. Clique em **Deploy**.
