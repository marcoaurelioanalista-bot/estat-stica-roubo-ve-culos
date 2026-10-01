# 🚗 Análise Estatística de Roubo e Furto de Veículos

<div align="center">

[![Status do Projeto](https://img.shields.io/badge/Status-Concluído-success.svg)]()
[![Tecnologias](https://img.shields.io/badge/Stack-SQL_%7C_Power_BI_%7C_Python-blue.svg)]()
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Conectar-blue?logo=linkedin)](https://www.linkedin.com/in/marco-aurélio-moreira)

</div>

---

## 📌 Contexto do Projeto
Este projeto desenvolve uma solução analítica completa para o estudo de estatísticas de **roubo e furto de veículos**, unindo técnicas de engenharia de dados, modelagem analítica e Business Intelligence. 

Dada a minha experiência prévia no setor de seguros e análise de riscos (mapeamento de sinistros, precificação e subscrição), o objetivo principal deste estudo é traduzir dados brutos de segurança pública em **insights acionáveis**, auxiliando na avaliação de exposição ao risco, identificação de padrões geográficos e temporais, e suporte à tomada de decisão estratégica.

---

## 🛠️ Tecnologias e Ferramentas Utilizadas

* **SQL:** Extração, limpeza de dados, criação de *views* e consultas avançadas (*joins*) para consolidação da base histórica e estruturação do banco relacional.
* **Power BI:** Modelagem de dados (Star Schema), criação de métricas avançadas em **DAX** e desenvolvimento de painéis interativos focados em *storytelling* de negócios e KPIs de sinistralidade.
* **Python (Pandas):** Análise exploratória inicial (EDA), tratamento de valores ausentes e validação de consistência estatística das bases de dados.

---

## 📊 Arquitetura e Etapas do Projeto

1. **Ingestão e Limpeza (SQL & Python):** Consolidação dos registros brutos, padronização de campos de data/localização e remoção de inconsistências estruturais.
2. **Modelagem de Dados (Power BI / DAX):** Construção de modelo relacional otimizado para performance, garantindo medidas precisas de frequência e severidade.
3. **Data Storytelling & Dashboards:** Criação de visualizações dinâmicas permitindo filtrar por período, região, marca/modelo do veículo e *modus operandi* das ocorrências.

---

## 📈 Principais Insights de Negócio
* **Concentração de Ocorrências:** Mapeamento dos horários e dias da semana com maior incidência de sinistros, evidenciando janelas críticas de exposição ao risco.
* **Perfil dos Alvos:** Identificação das categorias e modelos de veículos mais visados, métrica essencial para modelos de precificação de apólices e aceitação de risco.
* **Sazonalidade:** Análise de comportamento temporal dos índices de criminalidade ao longo dos períodos.

---

## 📂 Estrutura do Repositório

```text
📁 estat-stica-roubo-ve-culos
├── 📁 data/              # Amostras de dados ou instruções de acesso
├── 📁 notebooks/         # Scripts em Python para EDA e tratamento prévio
├── 📁 sql/               # Scripts SQL de criação de tabelas, views e consultas
├── 📁 dashboard/         # Arquivo do Power BI (.pbix) ou capturas de tela
└── 📄 README.md          # Documentação oficial do projeto
