## Este script implementa de forma automatica os containers abaixo:

1. Zabbix Frontend
2. Zabbix Backend
3. MysqlServer
4. Grafana

## 🚀 Como Usar

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/Cedriott/docker-zabbix-stack.git
    ```

2.  **Crie o arquivo de ambiente:**
    Crie um arquivo chamado `.env` na raiz do projeto com o seguinte conteúdo:

    ```env
    ZABBIX_DB_USER=SEU_USUARIO_DB
    ZABBIX_DB_PASSWORD=SENHA_FORTE
    ZABBIX_DB_ROOT_PASSWORD=SENHA_FORTE_ROOT
    ```

3.  **Inicie os serviços:**
    ```bash
    docker-compose up -d
    ```

## Acesso

* **Zabbix:** `http://<ip-do-servidor>:8080`
* **Grafana:** `http://<ip-do-servidor>:3000`
