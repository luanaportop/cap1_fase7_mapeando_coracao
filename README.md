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

---

## 📜 Descrição

Este repositório faz parte do projeto acadêmico **CardioIA**, cujo objetivo é construir um ecossistema inteligente de cardiologia baseado em dados clínicos reais, textos médicos e imagens.

Na Fase 1 – Batimentos de Dados, levantamos, organizamos e entendemos dados cardiológicos que servirão como base para as fases seguintes.

---

### Parte 1 – Dados Numéricos (IoT)

**Origem dos Dados**

Utilizamos o dataset público do Kaggle – Heart Failure Prediction:
👉 [Link para o Dataset no Kaggle](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction?resource=download)  

- **Autor**: fedesoriano  
- **Formato**: CSV  
- **Total de registros**: 918  
- **Total de variáveis**: 12


**📊 Estrutura das Variáveis**


| Variável          | Descrição | Relevância Clínica |
|-------------------|-----------|--------------------|
| `Age`            | Idade do paciente | Idade é fator de risco essencial para DCV. |
| `Sex`            | Sexo (M/F) | Diferenças biológicas impactam risco cardiovascular. |
| `ChestPainType`  | Tipo de dor no peito | Sintoma clássico na triagem de doenças cardíacas. |
| `RestingBP`      | Pressão arterial em repouso | Hipertensão é um dos principais fatores de risco. |
| `Cholesterol`    | Colesterol sérico total | Relacionado à aterosclerose e risco de infarto. |
| `FastingBS`      | Glicemia de jejum | Diabetes aumenta risco cardiovascular. |
| `RestingECG`     | Resultado do ECG em repouso | Identificação de arritmias e anormalidades. |
| `MaxHR`          | Frequência cardíaca máxima | Avalia capacidade funcional do coração. |
| `ExerciseAngina` | Angina induzida por exercício | Demonstra resposta cardíaca ao esforço. |
| `Oldpeak`        | Depressão do segmento ST | Indicador de isquemia miocárdica. |
| `ST_Slope`       | Inclinação do segmento ST | Útil para análise de alterações isquêmicas. |
| `HeartDisease`   | Diagnóstico (0 = saudável, 1 = doença) | Variável alvo para predição por IA. |


**🩺 Justificativa Clínica**


O dataset selecionado é relevante porque reúne variáveis reconhecidas como fatores de risco e indicadores diagnósticos para doenças cardiovasculares, que são a principal causa de mortalidade no mundo segundo a OMS.

- *Idade e Sexo*: são determinantes importantes, pois o risco cardiovascular aumenta com o envelhecimento e difere entre homens e mulheres.

- *Pressão Arterial e Colesterol*: hipertensão arterial e dislipidemia estão diretamente ligadas ao desenvolvimento de aterosclerose e insuficiência cardíaca.

- *Glicemia de Jejum*: níveis elevados de glicose sinalizam diabetes, condição que multiplica o risco de infarto e outras complicações cardíacas.

- *ECG, Frequência Cardíaca Máxima, ST Segment*: fornecem informações funcionais e elétricas essenciais para detectar arritmias, isquemias e alterações cardíacas.

- *Dor no Peito e Angina*: sintomas clássicos na triagem de pacientes com suspeita de doença arterial coronariana.

Além da relevância clínica, este conjunto de dados é valioso para Inteligência Artificial porque permite treinar modelos preditivos para avaliar risco de insuficiência cardíaca e prever desfechos clínicos, possibilita a aplicação de técnicas de classificação e regressão em Machine Learning e pode ser integrado com dados textuais e visuais para construir uma visão multimodal da saúde cardiovascular.
Portanto, este dataset não apenas reflete variáveis utilizadas na prática médica real, como também oferece uma base sólida para o desenvolvimento de soluções inovadoras de IA aplicada à cardiologia.

---

### Parte 2 – Dados Textuais (NLP)

**Origem dos Dados**


---

### Parte 3 – Dados Visuais (VC)

**Origem dos Dados**

Utilizamos o dataset público do PhysioNet – Dataset for Segmentation and Classification of Cardiac Implantable Electronic Devices in Chest X-Rays:
👉 [Link para as imagens no PhysioNet](https://physionet.org/content/cardiac-implantable-device-cxr/1.0.0/originals/)  

- **Autores**: Keno Bressem,  Felix Busch,  Andrei Zhukov,  Lisa Adams  
- **Formato**: PNG  
- **Total de registros**: 2,321


 🌐 Link para Download

As imagens estão hospedadas em nosso repositório pessoal:
👉 [Google Drive](https://drive.google.com/drive/folders/16uYB4JKlMxnXxFq0bDDPcdMxGRKIpsOy?usp=sharing)


**🩺 Justificativa Clínica**

A escolha do banco de imagens radiográficas de pacientes com dispositivos cardiológicos implantáveis (CIEDs) justifica-se pela relevância clínica e pelo potencial de aplicação em projetos de Inteligência Artificial voltados à saúde. Os CIEDs, que incluem marcapassos, desfibriladores implantáveis, monitores e dispositivos de ressincronização cardíaca, desempenham papel essencial na prevenção de mortes súbitas, na regulação elétrica do coração e no acompanhamento contínuo de condições cardiovasculares. Considerando que as doenças do coração permanecem entre as principais causas de mortalidade global, a identificação precisa e rápida desses dispositivos é de grande impacto tanto em contextos de emergência quanto em acompanhamento clínico de longo prazo.

Do ponto de vista técnico, as imagens radiográficas oferecem condições ideais para análises com algoritmos de Visão Computacional, uma vez que permitem a detecção de padrões estruturais, a segmentação de áreas de interesse, o reconhecimento de anomalias e a classificação de diferentes modelos de dispositivos. Essa capacidade pode contribuir para a automatização de processos tradicionalmente dependentes da interpretação manual, aumentando a eficiência, reduzindo erros e oferecendo suporte em cenários críticos.

Além disso, o banco de dados utilizado possui robustez metodológica, abrangendo mais de uma década de registros coletados em ambiente hospitalar, com diversidade de fabricantes e modelos de CIEDs. As imagens foram devidamente anonimizadas, garantindo conformidade com princípios de Governança de Dados e mitigação de riscos relacionados a privacidade e vieses. Esse cuidado torna o conjunto de dados não apenas seguro para pesquisa, mas também adequado para o treinamento e validação de modelos de IA com potencial aplicação em sistemas clínicos reais.

Dessa forma, a seleção desse banco de imagens se mostra coerente com os objetivos do projeto, pois alia relevância médica, potencial analítico e conformidade ética, estabelecendo uma base sólida para o desenvolvimento de soluções inovadoras em saúde digital.

---

## 📁 Estrutura de pastas

Dentre os arquivos e pastas presentes na raiz do projeto, definem-se:

- <b>assets</b>: arquivos relacionados a elementos visuais do repositório, como imagens e ícones.

- 

- <b>README.md</b>: guia completo e explicativo sobre o projeto (este arquivo).

---

## 🗃 Histórico de lançamentos

* 0.5.0 - XX/XX/2025
* 0.4.0 - XX/XX/2025
* 0.3.0 - XX/XX/2025
* 0.2.0 - XX/XX/2025
* Estrutura inicial do projeto - 26/08/2025
