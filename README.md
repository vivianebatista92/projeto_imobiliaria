# <div align="center"> Projeto Imobiliário - Pandas
</div>

<div align="center"><a target="_blank" href="https://colab.research.google.com/github/vivianebatista92/projeto_imobiliaria/blob/main/projeto_imobiliaria.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a></div>  

> ℹ️ **NOTE:** Análise desenvolvida para a formação de Data Science do programa [ONE - Oracle Next Educacion](https://www.oracle.com/br/education/oracle-next-education/) realizada na plataforma [Alura](https://www.alura.com.br/).


Este projeto simula um cenário real em que fomos contratados como **Cientistas de Dados** por uma empresa do setor imobiliário. Nossa principal função é **dar suporte ao time de Machine Learning e ao time de Desenvolvimento**, realizando a análise, limpeza, tratamento e enriquecimento de uma base de dados de imóveis, utilizando a biblioteca **Pandas**.

---

## 📂 **Base de Dados**

A base de dados utilizada contém informações sobre diversos tipos de imóveis no Rio de Janeiro, incluindo:

- Tipo do imóvel (apartamento, casa, comércio, etc)
- Valor de aluguel
- Valor de condomínio
- IPTU
- Número de quartos, entre outras características

📌 **Arquivo:** [aluguel.csv](https://raw.githubusercontent.com/alura-cursos/pandas-conhecendo-a-biblioteca/main/base-de-dados/aluguel.csv)

---

## 🔧 Ferramenta e Linguagem

![Google Colab](https://img.shields.io/badge/Google%20Colab-%23F9A825.svg?style=for-the-badge&logo=googlecolab&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)


## 📚 Bibliotecas utilizadas

![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)

---

## 🚀 **Etapas e Atividades do Projeto**

### 1️⃣ Importar e Conhecer a Base de Dados
- Importação do arquivo `aluguel.csv`.
- Verificação da estrutura dos dados: quantidade de linhas e colunas, nomes e tipos das colunas.
- Exploração inicial das características gerais do dataset.

---

### 2️⃣ Análise Exploratória dos Dados (Demanda do Time de ML)
- Cálculo dos **valores médios de aluguel por tipo de imóvel**.
- Análise do **percentual de cada tipo de imóvel** presente na base de dados.

---

### 3️⃣ Tratamento de Valores Nulos (Demanda do Time de ML)
- Identificação de colunas com valores ausentes.
- Aplicação das estratégias adequadas para o tratamento dos dados nulos.

---

### 4️⃣ Remoção de Registros Inconsistentes (Demanda do Time de ML)
- Exclusão de imóveis com **valor de aluguel igual a 0**.
- Exclusão de imóveis com **valor de condomínio igual a 0**.

---

### 5️⃣ Aplicação de Filtros (Demanda do Time de ML)
- Seleção de apartamentos com **1 quarto e aluguel menor que R$ 1200**.
- Seleção de apartamentos com **pelo menos 2 quartos, aluguel menor que R$ 3000 e área maior que 70 m²**.

---

### 6️⃣ Salvamento dos Dados (Demanda do Time de ML)
- Exportação do dataframe final tratado em formato **CSV** para uso futuro.

---

### 7️⃣ Criação de Colunas Numéricas (Demanda do Time de Desenvolvimento)
- `valor_por_mes`: gastos mensais com aluguel + condomínio.
- `valor_por_ano`: gastos anuais, considerando IPTU + 12 meses de aluguel e condomínio.

---

### 8️⃣ Criação de Colunas Categóricas (Demanda do Time de Desenvolvimento)
- `descricao`: resumo contendo tipo do imóvel, bairro, número de quartos e vagas de garagem.
- `possui_suite`: coluna indicando se o imóvel possui pelo menos uma suíte (sim/não).


--
#

<p align="center">
<img 
    src="src/projetos_banner.gif"
    >
