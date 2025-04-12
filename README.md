# Brasileirão

Este projeto realiza uma análise dos dados do Campeonato Brasileiro de Futebol, explorando aspectos como a qualidade dos dados, padrões de dados ausentes e imputação de dados onde necessário.

## Sumário

- [Sobre o Projeto](#sobre-o-projeto)
- [Configuração do Ambiente](#configuração-do-ambiente)
- [Como Usar](#como-usar)
- [Autor](#autor)

## Sobre o Projeto

O objetivo principal deste projeto é analisar dados do Campeonato Brasileiro de Futebol no período entre 2015 e 2024. A análise busca especificamente observar se há árbitros que beneficiam certos times ao longo do campeonato. Além disso, examinamos a qualidade dos dados, identificando padrões de valores ausentes e realizando imputação de dados quando útil e/ou necessário.

Os dados utilizados nesse projeto são disponibilizados pela [Transfermartk](https://www.transfermarkt.com.br/) e organizados pela [Base dos Dados](https://basedosdados.org/).

Esta é uma versão inicial do projeto e novas análises serão incorporadas em breve.

## Configuração do Ambiente

Para configurar seu ambiente para executar este projeto, siga as instruções abaixo:

1. **Pré-requisitos**: Certifique-se de ter Python 3.13 ou superior instalado.

2. **Poetry**: Este projeto utiliza o Poetry para gerenciar o ambiente virtual e as dependências. Certifique-se de que o Poetry está instalado.

```bash
# Criar e ativar o ambiente com Poetry
poetry install

# Para iniciar o ambiente virtual
poetry env activate
```

## Como Usar

### Execução do Notebook:

- Abra o Jupyter Notebook e execute o notebook `analise_brasileirao.ipynb` para realizar as análises e visualizações.

### Configuração do Google Cloud:

- Não é estritamente necessário configurar o Google Cloud Platform (GCP), pois o conjunto de dados já foi baixado e está disponível localmente como `../data/brasileirao_2015_2024.csv`.

## Autor

Desenvolvido por Vinicius Princiotti.
- Email: [vinicius.princiotti@gmail.com](mailto:vinicius.princiotti@gmail.com)