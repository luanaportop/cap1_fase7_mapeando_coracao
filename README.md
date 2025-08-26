# FIAP - Faculdade de Informática e Administração Paulista

<p align="center">
<a href="https://www.fiap.com.br/"><img src="assets/logo-fiap.png" alt="FIAP - Faculdade de Informática e Administração Paulista" border="0" width=40% height=40%></a>
</p>

<br>

# Cap 1 - Batimentos de Dados – Mapeando o Coração Moderno

## Beginner Coders

## 👨‍🎓 Integrantes:
- <a href="https://www.linkedin.com/in/luana-porto-pereira-gomes/">Luana Porto Pereira Gomes</a>
- <a href="https://www.linkedin.com/in/luma-x">Luma Oliveira</a>
- <a href="https://www.linkedin.com/in/priscilla-oliveira-023007333/">Priscilla Oliveira </a>
- <a href="https://www.linkedin.com/in/paulobernardesqs?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app">Paulo Bernardes</a>

## 👩‍🏫 Professores:
### Tutor(a)
- <a href="https://www.linkedin.com/in/leonardoorabona/">Leonardo Ruiz</a>
### Coordenador(a)
- <a href="https://www.linkedin.com/in/profandregodoi/">André Godoi</a>

## 📜 Descrição

Este projeto tem como objetivo o desenvolvimento de uma solução digital para **previsão do risco de queimadas**, aplicando conceitos de Inteligência Artificial e Machine Learning em dados reais.  
O foco está em ajudar comunidades e autoridades a tomarem decisões preventivas, reduzindo os impactos ambientais e sociais das queimadas.

## 📝 Sobre o Projeto

Foram utilizados dados reais de queimadas e condições climáticas, incluindo:

- **Temperatura máxima e mínima**.
- **Umidade mínima e média**.
- **Velocidade máxima do vento**.
- **Precipitação**.
- **Risco de fogo** (variável alvo).

O trabalho foi desenvolvido como parte da Sprint 3 do Global Solution da FIAP, no 2º semestre do curso de Inteligência Artificial.

## Vídeo do projeto: https://youtu.be/1eod4Nov5Qw?si=kaPm7qhIe6l7av9Q

## 📁 Estrutura de pastas

Dentre os arquivos e pastas presentes na raiz do projeto, definem-se:

- <b>assets</b>: arquivos relacionados a elementos visuais do repositório, como imagens e ícones.

- <b>notebook</b>: versão final do notebook (.ipynb) com a análise exploratória e modelagem de Machine Learning.

- <b>README.md</b>: guia completo e explicativo sobre o projeto (este arquivo).


## 🔧 Como executar o código
### 🐍 Código Python:
   - Executar por meio do link do notebook: https://colab.research.google.com/drive/14JELSbnw3pgI9nuGfmAQC3WwrsS6O9gp#scrollTo=yWdZ5EXGGmH-
   - Faça upload do arquivo de dados por meio do drive: https://drive.google.com/drive/folders/1U3UMJlKK2v1G1XDlU4ig976l7u57G6hZ?usp=drive_link
   - Execute as células do notebook em sequência.

## ⚙️ Etapas Realizadas

**1. Coleta e Limpeza dos Dados:**
- Dados reais de queimadas e clima coletados de bases públicas.
- Tratamento de dados inconsistentes (como valores -999).
- Conversão de datas e remoção de duplicatas.

**2. Análise Exploratória de Dados (EDA):**
- Estatísticas descritivas das variáveis.
- Visualização gráfica (histogramas, gráficos de contagem e boxplots).
- Análise de correlação para identificar variáveis relevantes.

**3. Análise Temporal e Eventos Críticos:**
- Estudo da evolução mensal de variáveis como temperatura e umidade.
- Identificação de registros com risco crítico de queimadas.

**4. Modelagem de Machine Learning:**
- Divisão dos dados em treino e teste.
- Padronização dos dados com `StandardScaler` e imputação de valores faltantes.
- Teste de três modelos principais:
  - Random Forest Regressor
  - Gradient Boosting Regressor
  - MLPRegressor (Rede Neural)
- Avaliação de desempenho com **MAE** e **R²**.

**5. Visualização e Conclusões:**
- Comparação gráfica entre previsões e valores reais.
- Discussão sobre qual modelo teve melhor desempenho.

## 📊 Principais Resultados

| Modelo                  | MAE     | R²     |
|--------------------------|---------|--------|
| Random Forest            | 0.0198  | 0.816  |
| Gradient Boosting        | 0.0284  | 0.7297 |
| MLPRegressor (RN)        | 0.0320  | 0.6847 |

✅ O **Random Forest Regressor** foi o modelo com melhor desempenho, sendo escolhido como base final para a aplicação.

## 🧠 Conclusão

A solução desenvolvida integra dados reais, algoritmos de Machine Learning e simulações de sensores (via dados sintéticos).  
O modelo final pode ser integrado com dados coletados em tempo real de sensores ESP32, gerando alertas automáticos e auxiliando no combate a queimadas.

## 🛠️ Tecnologias Utilizadas
- Python 3.11
- Google Colab
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## 🗃 Histórico de lançamentos

* 0.5.0 - XX/XX/2025
    * Entrega final da Global Solution.
* 0.4.0 - XX/XX/2025
    * Inclusão de Redes Neurais e análise comparativa.
* 0.3.0 - XX/XX/2025
    * Modelagem com Random Forest e Gradient Boosting.
* 0.2.0 - XX/XX/2025
    * Análise de dados e EDA completos.
* 0.1.0 - XX/XX/2025
    * Estrutura inicial do projeto.
