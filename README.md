# Dashboard de RH — Power BI

## 📌 Sobre o Projeto

Este projeto foi desenvolvido com foco em análise de indicadores de Recursos Humanos utilizando o Power BI. O objetivo é transformar dados brutos em informações visuais e estratégicas que auxiliem na tomada de decisão dentro do setor de RH.

O dashboard apresenta métricas importantes relacionadas aos colaboradores, permitindo uma visão mais clara sobre o quadro de funcionários da empresa.

---

# 🎯 Objetivos do Projeto

* Desenvolver um dashboard profissional no Power BI
* Aplicar conceitos de análise de dados e visualização
* Praticar modelagem e tratamento de dados
* Criar indicadores úteis para RH
* Construir um projeto para portfólio profissional

---

# 🛠️ Ferramentas Utilizadas

* Power BI
* Power Query
* Excel
* DAX
* Figma (planejamento visual)

---

# 📊 Indicadores Desenvolvidos

O dashboard contém os seguintes indicadores:

### ✔️ Total de Funcionários

Quantidade total de colaboradores registrados na base.

### ✔️ Funcionários por Departamento

Distribuição de colaboradores por área da empresa.

### ✔️ Funcionários por Cidade

Visualização geográfica da concentração de funcionários.

### ✔️ Tempo Médio de Empresa

Média de permanência dos colaboradores na empresa.

### ✔️ Contratações por Período

Análise de admissões ao longo do tempo.

### ✔️ Distribuição por Gênero

Indicador de diversidade do quadro de funcionários.

### ✔️ Faixa Salarial

Análise da distribuição salarial dos colaboradores.

### ✔️ Média Salarial

Média geral de salários da empresa.

---

# 📁 Estrutura do Projeto

```bash
📦 dashboard-rh-powerbi
 ┣ 📂 dados
 ┃ ┗ 📄 base_funcionarios.xlsx
 ┣ 📂 imagens
 ┃ ┗ 📄 dashboard.png
 ┣ 📄 Dashboard_RH.pbix
 ┗ 📄 README.md
```

---

# 🧹 Tratamento de Dados

Durante o desenvolvimento do projeto, foram realizadas as seguintes etapas de tratamento:

* Remoção de valores nulos
* Padronização de colunas
* Ajuste de tipos de dados
* Criação de colunas calculadas
* Criação de medidas em DAX
* Organização da modelagem

---

# 📈 Medidas DAX Utilizadas

## Total de Funcionários

```DAX
Total Funcionarios = COUNT(Funcionarios[ID])
```

## Média Salarial

```DAX
Media Salarial = AVERAGE(Funcionarios[Salario])
```

## Tempo Médio de Empresa

```DAX
Tempo Medio Empresa = AVERAGE(Funcionarios[TempoEmpresa])
```

---

# 🎨 Design do Dashboard

O projeto foi desenvolvido utilizando um padrão visual moderno, com foco em:

* Organização visual
* Hierarquia das informações
* Boa experiência do usuário
* Paleta de cores profissional
* Cards padronizados
* Gráficos limpos e objetivos

---

# 📌 Principais Aprendizados

Durante o desenvolvimento deste projeto, foram praticadas habilidades como:

* Construção de dashboards
* Storytelling com dados
* Modelagem de dados
* Criação de KPIs
* Utilização de DAX
* Design de dashboards
* Tratamento de dados no Power Query

---

# 🚀 Possíveis Melhorias Futuras

* Integração com banco de dados
* Dashboard responsivo para mobile
* Inclusão de análise preditiva
* Atualização automática de dados
* Novos indicadores de RH
* Comparativos entre períodos

---

# 📷 Preview do Projeto

## Dashboard Principal

<img width="1228" height="686" alt="ProjetoRH" src="https://github.com/user-attachments/assets/0c85495d-3acf-4e93-9fb3-872b4c034be2" />

--- 

<img width="1148" height="646" alt="projetoRH2" src="https://github.com/user-attachments/assets/f719f847-7c41-4be3-bcca-d98a984a1a39" />


---

# 💼 Sobre o Projeto

Este projeto foi criado com fins de estudo, prática e construção de portfólio na área de Dados/Business Intelligence.

---

# 👨‍💻 Autor

Samuel Elias de Lima

* Excel Intermediário
* Power BI
* Análise de Dados
* Dashboards

LinkedIn:

> www.linkedin.com/in/samuellimausa

GitHub:

> https://github.com/SamuelAnalytics

---

# ⭐ Considerações Finais

Este projeto representa minha evolução prática em análise de dados e visualização de informações utilizando Power BI. O desenvolvimento do dashboard permitiu aplicar conceitos importantes de BI, além de reforçar habilidades analíticas e de apresentação de dados.
