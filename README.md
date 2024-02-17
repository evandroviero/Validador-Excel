# Validar Excel

1. Clone o repositório:
   ```bash
   git clone https://github.com/evandroviero/Validador-Excel.git
   cd Validador-Excel
   ```
2. Configure a versão correta do Python com `pyenv`:
   ```bash
   pyenv install 3.11.5
   pyenv local 3.11.5
   ```
3. Instale as dependências do projeto:
    ```bash
    python -m venv .venv
    source .venv/bin/activate # usuários de Linux e Mac
    .venv\Scripts\Activate # usuário de Windows
    pip install -r requirements.txt
    ```