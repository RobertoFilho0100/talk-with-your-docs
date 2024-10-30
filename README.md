
# Configuração do Ambiente Virtual para execução da automação de testes do PDV

Esse é um projeto base que será utilizado em aplicações de integração de CHAT + IA para análise de arquivos PDF, CSV, Videos e Sites.

## Pré-requisitos
---
- **Python** (recomendado download da última versão do Python) [Link para download](https://www.python.org/downloads/)
- **Pip** (gerenciador de pacotes do Python). Normalmente, já é instalado junto ao Python. Para confirmação, basta executar o comando:

  ```bash
  pip --version
  ```

---

## Passo a Passo

### 1. Instale o Virtualenv
---
Instale o `virtualenv`, que será usado para criar o ambiente virtual isolado:

  ```bash
  pip install virtualenv
  ```

### 2. Crie o Ambiente Virtual
---
Em seguida, crie o ambiente virtual na pasta do projeto. Vamos chamá-lo de `venv`:

  ```bash
  virtualenv venv
  ```

### 3. Ative o Ambiente Virtual
---
Estando na raiz do projeto, ative o ambiente virtual com o comando:

  ```bash
  venv\Scripts\activate
  ```

Após a ativação, o prefixo `(venv)` deve aparecer no início da linha de comando, indicando que o ambiente virtual está ativo.

### 4. Instale as Dependências do Projeto
---
Com o ambiente virtual ativo, instale as dependências listadas no arquivo `requirements.txt`. Para isso, ainda na raiz do projeto, execute:

  ```bash
  pip install -r requirements.txt
  ```

### 5. Como executar o projeto
---
Para executar o projeto, basta executar o comando:

  ```bash
  streamlit run main.py
  ```

---
### OBS: 
Qualquer dependência instalada deve ser instalada dentro do ambiente virtual. Além disso, o desenvolvedor deve validar se a dependência foi corretamente adicionada no arquivo `requirements.txt`, que deve estar presente no seu repositório.
