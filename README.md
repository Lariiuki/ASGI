Este repositório contém um projeto Django configurado para demonstrar o uso de views assíncronas e síncronas. O projeto inclui exemplos de chamadas HTTP assíncronas utilizando `httpx` e `asyncio`, além de exemplos tradicionais síncronos. A estrutura segue o padrão de projetos Django, com arquivos de configuração, gerenciamento de dependências e exemplos de rotas para testar o comportamento assíncrono e síncrono das views.## Como rodar o projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/ASGI.git
   cd ASGI
2. Crie e ative um ambiente virtual:   
    ```
    python3 -m venv venv
    source venv/bin/activate
3. Instale as dependências:
    ```
    pip install -r requirements.txt
4. Aplique as migrações do Django:
    ```
    python manage.py migrate
5. Inicie o servidor de desenvolvimento
    ```
    python manage.py runserver
6. Acesse o projeto em http:localhost:8000
    ```
    Adapte o link do repositório se necessário.
