# Automação Infosiga — Diadema

Automação desenvolvida em Python para coleta, processamento e organização de dados do Infosiga SP, com foco no município de Diadema.

## Sobre o projeto

O projeto tem como objetivo automatizar o tratamento dos dados do Infosiga, facilitando a extração e a organização de informações relacionadas à segurança viária.

A automação busca reduzir tarefas manuais e preparar os dados para análises e utilização em ferramentas de visualização de dados.

## Funcionalidades

- Processamento de dados do Infosiga SP.
- Organização de dados por períodos.
- Tratamento de informações relacionadas a pessoas, sinistros e veículos.
- Filtragem de dados referentes ao município de Diadema.
- Geração de arquivos para análise.
- Execução automatizada por script.

## Tecnologias utilizadas

- Python
- Pandas
- CSV
- Google Sheets API
- Git e GitHub

## Estrutura do projeto

```text
AutomacaoInfoSiga/
├── main.py
├── executar_infosiga.bat
├── requirements.txt
├── .gitignore
└── README.md
```

## Como executar

### 1. Instale as dependências

```bash
pip install -r requirements.txt
```

### 2. Execute a automação

No Windows, execute:

```bash
executar_infosiga.bat
```

Ou diretamente pelo Python:

```bash
python main.py
```

## Fonte dos dados

Os dados utilizados são provenientes do Infosiga SP, sistema de informações sobre acidentes de trânsito do Estado de São Paulo.

## Objetivo final

Contribuir para a análise de indicadores de segurança viária de Diadema, apoiando a organização e a utilização de dados públicos.

## Autor

Desenvolvido por Paulo Otávio.

Projeto voltado à automação de dados e análise de indicadores públicos.
