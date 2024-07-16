#  ETL_Apache_Beam

## Descrição

Este projeto realiza um processo ETL (Extract, Transform, Load) em dois datasets: um contendo dados de chuvas e outro contendo casos de dengue. O dataset de chuvas possui mais de 23 milhões de linhas com informações de data, quantidade de chuva em milímetros e o estado onde a medição foi realizada. O dataset de casos de dengue contém informações de data, quantidade de casos, código do IBGE, cidade, estado, CEP, latitude e longitude.

## Objetivo

O objetivo deste projeto é integrar, processar e analisar grandes volumes de dados de duas fontes distintas - chuvas e casos de dengue - utilizando Apache Beam. Através de uma série de transformações e tratamentos de dados, buscamos identificar correlações e padrões entre a quantidade de chuvas e a incidência de casos de dengue nos estados brasileiros. Isso inclui:

1. **Tratamento de dados de chuvas**: Correção de valores anômalos, como quantidades negativas de chuvas, e padronização das informações.
2. **Tratamento de dados de dengue**: Manipulação dos dados epidemiológicos para alinhar com o formato do dataset de chuvas, utilizando informações como estado e data de início da semana epidemiológica.
3. **Integração dos datasets**: Combinação dos datasets com base em informações comuns, como estado e data (ajustada para mês e ano), para permitir análises comparativas.
4. **Análise dos resultados**: Utilização de Pandas para análises exploratórias e geração de insights a partir dos dados processados.
   
   ![image](https://github.com/PATRICIAJUNQUEIRA/ETL_Apache_Beam/assets/96187596/218283f1-e48f-4730-bc50-195b97e2c866)



## Tecnologias e Ferramentas

- Apache Beam
- Python
- Google Cloud Dataflow 
- Pandas (para manipulação de dados e análise)
- Apache Beam I/O (para leitura e escrita de dados)

## Configuração do Ambiente

1. Clone o repositório:

   ```bash
   git clone https://github.com/seu_usuario/ETL_Apache_Beam.git
   cd ETL_Apache_Beam2. Crie e ative um ambiente virtual:

2. Crie e ative um ambiente virtual:python -m venv venv
   
   ```bash
    source venv/bin/activate  # Linux/Mac
    venv\Scripts\activate  # Windows
   
3. Instale as dependências:

   ```bash
   pip install -r requirements.txt

## Contato
Patrícia Miranda e Silva - patricia.junqueira11@gmail.com
LinkedIn - www.linkedin.com/in/patrícia-miranda-silva




