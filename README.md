# 📊 Análise da População dos Municípios de Minas Gerais

## 📌 Sobre o projeto

Este projeto apresenta uma **Análise Exploratória de Dados (EDA)** sobre a população dos municípios de Minas Gerais.

Os dados foram obtidos através da **API do IBGE** e posteriormente tratados e analisados utilizando Python.

O projeto foi desenvolvido como parte dos meus estudos em **Análise de Dados e Ciência de Dados**, com o objetivo de praticar um fluxo completo de análise: desde a coleta dos dados até a geração de insights e visualizações.

---

## 🎯 Objetivos

* Consumir dados utilizando uma API;
* Transformar os dados em um DataFrame;
* Explorar e compreender a estrutura dos dados;
* Realizar limpeza e tratamento;
* Filtrar os municípios de Minas Gerais;
* Analisar a distribuição populacional;
* Identificar os municípios mais populosos;
* Calcular medidas estatísticas;
* Criar faixas populacionais;
* Desenvolver visualizações para facilitar a interpretação dos dados.

---

## 🛠️ Tecnologias utilizadas

* **Python**
* **Pandas**
* **Matplotlib**
* **Requests**
* **Google Colab**
* **API do IBGE**

---

## 🔄 Etapas do projeto

### 1. Coleta dos dados

Os dados foram obtidos através da API do IBGE utilizando uma requisição HTTP.

Após realizar a requisição, foi feita uma verificação do retorno para confirmar se os dados foram obtidos corretamente.

### 2. Transformação dos dados

Os dados retornados pela API estavam estruturados em **JSON**.

Utilizando o Pandas, os dados foram transformados em um **DataFrame**, facilitando sua manipulação e análise.

### 3. Análise exploratória

Inicialmente, foi realizada uma análise da estrutura do conjunto de dados, verificando:

* Quantidade de linhas e colunas;
* Nomes das colunas;
* Tipos de dados;
* Valores nulos;
* Registros duplicados;
* Estatísticas descritivas.

O conjunto inicial possui **5.571 registros e 11 colunas**.

### 4. Tratamento dos dados

Foram realizados procedimentos de preparação dos dados, incluindo:

* Renomeação das colunas;
* Remoção de registros inadequados;
* Verificação de valores ausentes;
* Verificação de duplicidades;
* Conversão dos tipos de dados;
* Seleção das informações necessárias para a análise.

### 5. Filtragem de Minas Gerais

Após o tratamento inicial, os dados foram filtrados para manter apenas os municípios pertencentes ao estado de **Minas Gerais**.

### 6. Análise

Foram realizadas análises relacionadas à população dos municípios, incluindo:

* População total;
* Média populacional;
* Mediana;
* Maior população;
* Menor população;
* Diferença entre o maior e o menor valor;
* Top 10 municípios mais populosos;
* Distribuição dos municípios por faixa populacional.

### 7. Visualização

Foram desenvolvidas visualizações para facilitar a interpretação dos resultados, incluindo gráficos relacionados aos municípios mais populosos e à distribuição dos municípios por faixa populacional.

---

## 📈 Principais aprendizados

Durante o desenvolvimento deste projeto, pude praticar diferentes etapas de um processo de análise de dados e compreender melhor a importância de cada uma delas.

Além das ferramentas utilizadas, o projeto me ajudou a desenvolver principalmente o **raciocínio analítico**, pensando em quais perguntas poderiam ser respondidas pelos dados e quais métodos seriam mais adequados para cada análise.

---

## 📂 Estrutura do projeto

```text
📁 analise-populacao-mg
│
├── 📓 analise_populacao_mg.ipynb
├── 📄 README.md
└── 📊 dados/
```

---

## 👩‍💻 Sobre mim

Meu nome é **Lana Bartl** e sou estudante de **Arquitetura de Dados e Desenvolvimento de Sistemas**, com foco no desenvolvimento de conhecimentos em **Análise de Dados e Ciência de Dados**.

Tenho estudado e desenvolvido projetos utilizando **Python, Pandas, SQL e Power BI**, buscando transformar meus conhecimentos em aplicações práticas.

Este projeto faz parte da construção do meu portfólio e representa mais uma etapa da minha evolução na área de dados.

---

## 🔗 Conecte-se comigo

💼 **LinkedIn:** https://www.linkedin.com/in/lanabartl/
