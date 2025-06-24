-----

# 📊 Análise Exploratória de Transporte Ferroviário de Cargas no Brasil

Este projeto contém um notebook Jupyter para análise exploratória de dados (EDA) de transporte ferroviário de cargas no Brasil. O objetivo é extrair *insights* sobre os volumes de carga, identificar tendências, padrões sazonais e a participação de diferentes grupos de mercadorias ao longo do tempo.

-----

## 🎯 Objetivos da Análise

  * Obter uma **visão geral** da estrutura e conteúdo dos dados.
  * Calcular os **totais de carga** transportada por ano e por grupo de mercadoria.
  * Analisar a **participação** de cada grupo de mercadoria no transporte ferroviário.
  * Identificar **tendências e padrões** ao longo do tempo, com foco especial na **sazonalidade** dos últimos 10 anos.
  * Gerar **estatísticas descritivas básicas** (média, mediana, desvio padrão, etc.).
  * Realizar uma **projeção simples** da carga total para o ano de 2025 com base nos dados disponíveis.

-----

## 🛠️ Bibliotecas Utilizadas

As seguintes bibliotecas Python são utilizadas neste projeto:

  * **`pandas`**: Para manipulação e agregação de dados.
  * **`numpy`**: Para operações numéricas e cálculos estatísticos.
  * **`matplotlib`**: Para a criação de visualizações gráficas.

-----

## 🗂️ Fonte dos Dados

Os dados utilizados nesta análise são **públicos** e contêm registros mensais de transporte ferroviário de carga no Brasil, classificados por ano, mês e grupo de mercadoria.

  * `transporte_ferroviario.csv`: Arquivo CSV contendo os dados de carga ferroviária.

-----

## 🚀 Como Executar a Análise

1.  **Clone este repositório**:
    ```bash
    git clone https://github.com/seu-usuario/nome-do-seu-repositorio.git
    cd nome-do-seu-repositorio
    ```
2.  **Crie um ambiente virtual (recomendado)**:
    ```bash
    python -m venv venv
    # No Windows
    .\venv\Scripts\activate
    # No macOS/Linux
    source venv/bin/activate
    ```
3.  **Instale as dependências**:
    ```bash
    pip install pandas numpy matplotlib
    ```
4.  **Execute o Notebook Jupyter**:
    ```bash
    jupyter notebook Analise_Transporte_Ferroviario.ipynb
    ```
    Isso abrirá o Jupyter Notebook em seu navegador, onde você poderá executar as células e explorar a análise.

-----

## 📈 Principais Análises Realizadas

  * **Inspeção e Limpeza de Dados**: Verificação de valores ausentes, duplicados e tipos de dados.
  * **Carga Total Anual e por Grupo de Mercadoria**: Soma da carga ao longo dos anos e para cada tipo de produto.
  * **Sazonalidade da Carga Ferroviária**: Análise dos padrões mensais nos últimos 10 anos, com visualização da série temporal e da média de carga por mês.
  * **Participação de Grupos de Mercadoria**: Identificação dos grupos que mais contribuíram para o volume de carga nos últimos 10 anos.
  * **Projeção de Carga para 2025**: Uma estimativa simples da carga total para o ano corrente com base nos meses já registrados.

-----

## 💡 Contribuições

Sinta-se à vontade para abrir *issues* ou enviar *pull requests* com melhorias, novas análises ou sugestões.

-----
