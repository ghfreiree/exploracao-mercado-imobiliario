# Análise de Dados do Mercado Imobiliário

## Sobre o Projeto
Este projeto tem como objetivo realizar uma Análise Exploratória de Dados (EDA) em uma base de dados de imóveis para aluguel. Através da manipulação e tratamento dos dados, o notebook explora características dos imóveis, como localização, quantidade de quartos, vagas de garagem e se possuem suíte, além de analisar os valores de aluguel.

Este repositório demonstra habilidades práticas em limpeza de dados, filtragem, agrupamento e extração de insights utilizando a linguagem Python.

## Tecnologias e Ferramentas Utilizadas
* **Python 3**
* **Pandas:** Manipulação e análise de dados tabulares.
* **Jupyter Notebook:** Ambiente interativo de desenvolvimento.

## Estrutura dos Dados
A base de dados utilizada (`aluguel.csv`) contém diversas informações sobre as propriedades imobiliárias. Algumas das principais variáveis analisadas incluem:
* `Tipo`: Categoria do imóvel (Apartamento, Casa de Vila, etc.)
* `Bairro`: Localização do imóvel.
* `Quartos`, `Vagas`, `Suites`: Características estruturais.
* `Area`: Metragem do imóvel.
* `Valor`: Valor do aluguel.
* `Condominio` e `IPTU`: Taxas adicionais.
* `Possui_suite` / `Descricao`: Variáveis categóricas e descritivas sobre a propriedade.

## Como Executar o Projeto

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git](https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git)
   ```

2. **Navegue até o diretório:**
   ```bash
   cd NOME_DO_REPOSITORIO
   ```

3. **Instale as dependências:**
   Certifique-se de ter o Python instalado. Recomenda-se o uso de um ambiente virtual. Instale o Pandas e o Jupyter com o comando:
   ```bash
   pip install pandas jupyter
   ```

4. **Abra o Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

5. Abra o arquivo `dados_imobiliaria.ipynb` e execute as células sequencialmente.

## Principais Aprendizados e Próximos Passos
* **Manipulação com Pandas:** Importação de bases via URL, tratamento de valores nulos e exploração de variáveis categóricas e numéricas.
* **Próximos passos (Sugestões):** Criar visualizações gráficas utilizando `Matplotlib` ou `Seaborn` para identificar tendências de preço por bairro, ou até mesmo aplicar modelos de regressão para prever o valor do aluguel com base nas características do imóvel.

---
*Desenvolvido com dedicação para aprofundamento em Data Science e análise de dados.*
