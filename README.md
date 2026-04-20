# 📊 Distorção Idade-Série no Maranhão – Análise com Python e Machine Learning
> **Projeto de Iniciação Científica** | Centro Universitário Santa Terezinha (CEST)  
> **Orientação:** Prof. Esp. Dadilton Bastos Melo

---

## 👨‍💻 Sobre o Projeto

Este estudo analisou **1.562 escolas estaduais** e **mais de 500 mil alunos** do Maranhão usando microdados do **Censo Escolar (INEP)**. O objetivo foi identificar os fatores associados à **distorção idade-série** no Ensino Médio usando **estatística descritiva** e **Árvore de Decisão**.

**🔍 O que eu fiz na prática:**
- Limpeza e integração de bases com +400 colunas e +200k registros
- Criação de indicadores (infraestrutura, recursos pedagógicos, taxa de transporte)
- Modelagem preditiva com scikit-learn (DecisionTreeClassifier)
- Visualização de dados com matplotlib
- Geração automatizada de relatórios e gráficos para artigo científico

---

## 🛠️ Stack Técnica

| Tecnologia | Aplicação no projeto |
|:-----------|:---------------------|
| **Python** | Linguagem principal |
| **Pandas / NumPy** | Manipulação e limpeza de dados |
| **Matplotlib** | Visualizações (boxplots, árvore, importância) |
| **Scikit-learn** | Árvore de Decisão, train_test_split, métricas |
| **Google Colab** | Ambiente de desenvolvimento |

---

## 📈 Resultados (em números)

| Métrica | Resultado |
|:--------|----------:|
| Escolas analisadas | 1.562 |
| Alunos no período | 509.474 |
| Redução da distorção (2023→2024) | **35,2% → 31,8%** (–3,4 p.p.) |
| Diferença Rural vs Urbana (2024) | **+19,8 p.p.** |
| Acurácia do modelo | **62,9%** |
| Variável mais importante | **Recursos pedagógicos (48%)** |

**💡 Principais aprendizados técnicos:**
- Recurso pedagógico é mais relevante que infraestrutura para explicar a distorção
- Localização rural é o segundo fator mais importante (25% de importância)
- Modelo com profundidade 3 já identifica padrões mesmo em dados reais e ruidosos

---

## 📁 O que tem neste repositório
📦 analise-distorcao-idade-serie/
┣ 📜 analise.ipynb # Notebook completo (Colab)
┣ 📜 analise.py # Script Python
┣ 📜 dados_maranhao_2023_2024.csv
┣ 📜 resumo_artigo.txt # Resultados formatados
┣ 📊 comparativo_distorcao.png
┣ 📊 arvore_decisao.png
┣ 📊 importancia_variaveis.png
┗ 📖 README.md

---

## 🚀 Como executar (se quiser testar)

```bash
pip install pandas numpy matplotlib scikit-learn
python analise.py

💼 Buscando oportunidade como Desenvolvedor Júnior ou Analista de Dados Júnior
