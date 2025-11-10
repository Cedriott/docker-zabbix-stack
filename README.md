# Stack Zabbix + Grafana com Docker

Este repositório sobe um ambiente completo do Zabbix e Grafana.

## Pré-requisitos
- Docker
- Docker Compose

## Como usar

1. Clone o repositório:
   `git clone https://github.com/Cedriott/docker-zabbix-stack.git`

2. Crie um arquivo `.env` com as senhas conforme variaveis abaixo:
ZABBIX_DB_USER=SEU_USUARIO_DB
ZABBIX_DB_PASSWORD=SENHA_FORTE
ZABBIX_DB_ROOT_PASSWORD=SENHA_FORTE_ROOT

3. Inicie os serviços:
   `docker-compose up -d`

## Acesso
- **Zabbix:** `http://<ip-do-servidor>:8080`
- **Grafana:** `http://<ip-do-servidor>:3000`
