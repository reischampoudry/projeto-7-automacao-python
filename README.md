
# Projeto 7 — Automação de Testes com Python

## Status

Este repositório contém a estrutura preparatória do Projeto 7. Os testes em `main.py` ainda não executam automações; a implementação funcional está no [Projeto 8 — Automação com Selenium](https://github.com/reischampoudry/projeto-8-automacao-selenium).

## Sobre o projeto

Este projeto faz parte da formação em QA (Quality Assurance) e prepara a estrutura inicial para a automação de testes do aplicativo Urban Routes.

O objetivo desta etapa é organizar os arquivos, armazenar os dados de teste, preparar os casos de teste e verificar a disponibilidade do servidor.

## Tecnologias utilizadas

- Python
- Pytest
- Selenium
- Git e GitHub
- PyCharm

## Estrutura do projeto

- `data.py`: armazena as constantes utilizadas nos testes.
- `helpers.py`: contém as funções auxiliares fornecidas originalmente pela TripleTen.
- `main.py`: contém a classe de testes e a estrutura inicial dos casos de teste.
- `requirements.txt`: lista as dependências do projeto.
- `.gitignore`: define os arquivos que não devem ser enviados ao GitHub.

## Casos de teste preparados

1. Definir a rota.
2. Selecionar o plano.
3. Preencher o telefone.
4. Adicionar o cartão.
5. Adicionar comentário para o motorista.
6. Solicitar cobertor e lenços.
7. Solicitar dois sorvetes.
8. Verificar a exibição da busca por táxi.

Os testes estão preparados para receber a implementação de automação na etapa seguinte do projeto.

## Configuração

Clone o repositório e acesse a pasta do projeto.

Crie e ative um ambiente virtual Python.

Instale as dependências com:

```bash
python -m pip install -r requirements.txt
```

## Execução dos testes

Execute no terminal:

```bash
python -m pytest main.py -v
```

## Observação

A URL do servidor Urban Routes deve ser configurada em `data.py` antes da verificação de disponibilidade do servidor.

Nesta etapa, os casos de teste ainda não executam as funcionalidades da aplicação. A implementação com Selenium será realizada posteriormente.
