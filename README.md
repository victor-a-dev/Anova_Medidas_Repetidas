# 📊 Análise de Eficácia de Tratamento para Ansiedade

Este repositório contém um estudo estatístico e análise de dados focados em avaliar a eficácia de um tratamento terapêutico/médico para a ansiedade ao longo do tempo. O projeto utiliza **Análise de Variância (ANOVA) de Medidas Repetidas** para comparar os escores de ansiedade dos pacientes em três momentos distintos.

---

## 🎯 Objetivo da Análise

O objetivo principal é verificar se houve uma redução estatisticamente significativa nos níveis de ansiedade dos pacientes submetidos ao tratamento, acompanhados em três marcos temporais:
1. **Início do tratamento** ($baseline$)
2. **Após 3 meses**
3. **Após 6 meses**

---

## 📈 Etapas do Projeto

O notebook executado abrange as seguintes fases metodológicas:

1. **Preparação e Limpeza de Dados:** Instalação de dependências (`pingouin`), carregamento da base de dados e transformação do formato *wide* para o formato *long* (`pd.melt`), preparando a estrutura adequada para modelos de medidas repetidas.
2. **Análise Exploratória de Dados (EDA):** Cálculo de estatísticas descritivas (média, mediana, desvio padrão, mínimo e máximo) para cada período e geração de gráficos de tendência temporal utilizando a biblioteca Seaborn.
3. **Modelagem Estatística (ANOVA de Medidas Repetidas):** Execução da ANOVA para testar o efeito principal do tempo sobre o escoramento da ansiedade.
4. **Testes Post-Hoc:** Identificação de diferenças pontuais entre os pares de momentos avaliados.
5. **Conclusões:** Interpretação clínica e estatística dos resultados obtidos.

---

## 🛠️ Tecnologias e Bibliotecas Utilizadas

O projeto foi desenvolvido em **Python** dentro do ambiente Google Colab, utilizando as seguintes bibliotecas:

* **Manipulação e Análise de Dados:** `pandas`, `numpy`
* **Estatística e Inferência:** `statsmodels`, `pingouin`
* **Visualização de Dados:** `matplotlib`, `seaborn`

---

## 🚀 Como Executar o Projeto

Se você deseja executar o notebook no Google Colab, siga os passos abaixo:

1. Instale as dependências necessárias (incluindo o pacote `pingouin` para estatísticas avançadas):
   ```bash
   pip install pingouin statsmodels matplotlib seaborn pandas numpy
