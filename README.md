# LLama2 RAG

## Descrição
Para utilizar desse código, será necessário fazer a instalação do Ollama, instalar o modelo desejado e realizar as mudanças personalizáveis no código, como o modelo utilizado, template, documento pesquisado, etc. Todos esses pontos estarão destacados no código por comentários.

## Instalação
Para Linux, deve-se executar a seguinte linha de comando:
```bash
curl -fsSL https://ollama.com/install.sh | sh
```
Para instalação no Windows, baixe no site https://ollama.com/download/windows e execute o executável.

Após isso, o Ollama já é configurado para utilizar a GPU para rodar os modelos, baseado nessa lista de GPUs, que contém mais informações de compatibilidade:
https://github.com/ollama/ollama/blob/main/docs/gpu.md

## Setup
Para baixar um modelo do Ollama e executá-lo, segue-se o seguinte tutorial:
1. Baixe o modelo:
   ```bash
   ollama pull llama3
   ```
2. Execute o modelo para teste:
   ```bash
   ollama run llama3
   ```

### Para utilizá-lo no código do notebook, é necessário apenas instalá-lo, sendo a execução realizada através do código.
3. Criar ambiente para execução do código

```bash
$ python3 -m venv .venv
$ source .venv/bin/activate
$ pip install -r requirements.txt
```


