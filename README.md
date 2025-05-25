# Alura Store - Análise de Dados 📊✨

## Visão Geral do Projeto 📈

Este projeto tem como objetivo principal analisar o desempenho de quatro lojas distintas da AluraStoreBr, utilizando dados de faturamento, categorias de produtos, avaliações de clientes, produtos mais e menos vendidos e custos de frete. A análise foi realizada para fornecer ao Senhor João uma recomendação embasada sobre qual loja seria mais estratégica para ser vendida. 🎯

## Estrutura do Repositório 📂

O repositório está organizado da seguinte forma:

````
├── AluraStoreBr.ipynb
├── datasets/
│   ├── loja_1.csv
│   ├── loja_2.csv
│   ├── loja_3.csv
│   └── loja_4.csv
└── README.md
````

- `AluraStoreBr.ipynb`: Contém todo o código-fonte da análise de dados, incluindo a instalação de bibliotecas, importação de dados, cálculos e geração de visualizações. 💻
- `datasets/`: Pasta que armazena os arquivos CSV com os dados de vendas de cada loja. 📊
- `README.md`: Este arquivo, que fornece uma visão geral do projeto. 📖

## Instalação 🚀

Para configurar e executar este projeto em sua máquina local, siga os passos abaixo:

1.  **Clone o Repositório:**
    ```bash
    git clone https://github.com/rafaelflorentinobarbosa/Analise_Dados_Alura
    ```

2.  **Crie um Ambiente Virtual (Recomendado):**
    ```bash
    python -m venv venv
    ```

3.  **Ative o Ambiente Virtual:**
    * **No Windows:**
        ```bash
        .\venv\Scripts\activate
        ```
    * **No macOS/Linux:**
        ```bash
        source venv/bin/activate
        ```

## Dependências 🛠️

As principais bibliotecas Python necessárias para este projeto são:

* `pandas`: Para manipulação e análise de dados.
* `matplotlib`: Para criação de visualizações gráficas.

Você pode instalar estas dependências usando pip:

```bash
pip install pandas matplotlib
```

## Dados 📦

Os dados utilizados neste projeto são provenientes de quatro arquivos CSV, cada um representando os dados de vendas de uma loja específica:
- `loja_1.csv` 🛒
- `loja_2.csv` 🛍️
- `loja_3.csv` 🏪
- `loja_4.csv` 🏬

Cada arquivo CSV contém as seguintes colunas:
- `Produto`: Nome do produto vendido. 🏷️
- `Categoria do Produto`: Categoria à qual o produto pertence. 📚
- `Preço`: Preço do produto. 💲
- `Frete`: Custo do frete da compra. 🚚
- `Data da Compra`: Data em que a compra foi realizada. 📅
- `Vendedor`: Nome do vendedor responsável pela venda. 👨‍💼
- `Local da compra`: Localidade onde a compra foi feita (estado). 📍
- `Avaliação da compra`: Avaliação da compra feita pelo cliente (escala de 1 a 5). ⭐
- `Tipo de pagamento`: Método de pagamento utilizado. 💳
- `Quantidade de parcelas`: Número de parcelas do pagamento. 🔢
- `lat`: Latitude do local da compra. 🌍
- `lon`: Longitude do local da compra. 🗺️

## Análise e Resultados 📈📉

A análise exploratória dos dados abrangeu as seguintes áreas:

### 1. Análise do Faturamento 💰

Foi calculado o faturamento total de cada loja, tanto com quanto sem o frete. Além disso, foram gerados gráficos de faturamento médio mensal e anual para identificar tendências ao longo do tempo. 📊📆

- **Faturamento Total (com frete)**:
    - Loja 1: R$ 1.534.509,12 🥇
    - Loja 2: R$ 1.488.459,06 🥈
    - Loja 3: R$ 1.464.025,03 🥉
    - Loja 4: R$ 1.384.497,58 👎

A Loja 1 se destacou com o maior faturamento, enquanto a Loja 4 apresentou o menor.

### 2. Vendas por Categoria 🛍️📚

Identificamos as categorias de produtos mais populares em cada loja. A análise revelou que **móveis, eletrônicos e brinquedos** são os produtos mais vendidos em todas as lojas. Os produtos menos vendidos variam bastante de loja para loja. 🧸🛋️🔌

### 3. Média de Avaliação das Lojas ⭐👍

A satisfação do cliente foi avaliada através da média das avaliações de compra.

- Loja 1: Média de Avaliações: 3.98 😔
- Loja 2: Média de Avaliações: 4.04 😊
- Loja 3: Média de Avaliações: 4.05 😄
- Loja 4: Média de Avaliações: 4.00 😐

A Loja 3 obteve a melhor avaliação média, enquanto a Loja 1 teve a menor.

### 4. Produtos Mais e Menos Vendidos 🚀🐌

Além das categorias, foi feita uma análise detalhada dos produtos individualmente mais e menos vendidos em cada estabelecimento. Como dito anteriormente, **móveis, eletrônicos e brinquedos** são sempre os mais vendidos em todas as lojas. Já os menos vendidos variam bastante entre elas. 📈📉

### 5. Custo Médio de Frete por Loja 💸🚚

O custo médio de frete foi calculado para cada loja.

- Loja 1: Custo Médio de Frete: R$ 34,69
- Loja 2: Custo Médio de Frete: R$ 33,62
- Loja 3: Custo Médio de Frete: R$ 33,07
- Loja 4: Custo Médio de Frete: R$ 31,28

A Loja 4 apresentou o menor custo médio de frete.

## Conclusão e Recomendação 🤝💡

Com base na análise completa dos dados, a recomendação para o Senhor João é **vender a Loja 4**. 💰➡️🏡

**Justificativa:**

* **Faturamento:** A Loja 4 possui o menor faturamento entre todas as lojas, tanto com quanto sem frete. A venda desta loja permitiria ao Senhor João concentrar recursos nas lojas mais rentáveis. 📉💸
* **Categorias de Produtos:** A Loja 4 apresenta baixa diversidade e volume de vendas em várias categorias, com pouca saída de produtos, tornando-a menos atrativa para ser mantida. 📉📚
* **Avaliações de Clientes:** Embora o custo de frete seja o menor, ele não resultou em um aumento significativo nas vendas ou na melhoria do faturamento. 😔👎
* **Produtos Mais/Menos Vendidos:** A Loja 4 possui uma baixa quantidade de produtos com alto volume de vendas e muitos itens com poucas unidades vendidas. 📊🐌
* **Custo de Frete:** Apesar de possuir o menor custo médio de frete, esse diferencial não impacta positivamente o faturamento geral da loja. 🚚🤷‍♂️

Em suma, a **Loja 4 apresenta diversos pontos fracos que a tornam a candidata ideal para venda**. A venda desta loja permitiria ao Senhor João focar em outras lojas mais rentáveis, reduzir custos operacionais e potencializar a eficiência do seu negócio. ✅🚀