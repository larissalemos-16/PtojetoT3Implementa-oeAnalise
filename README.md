# Implementação e Análise de Classificação com Redes Convolucionais e o dataset CUFS
Grupo 12: 
Larissa Fernanda

## Objetivo do Projeto  
Este projeto tem como objetivo implementar um modelo de rede neural convolucional (CNN) para classificar imagens do dataset CUFS, composto por imagens faciais reais e estilizadas.  
A proposta inclui:  
- Preparação dos dados com técnicas de augmentação.  
- Construção de um modelo CNN eficiente.  
- Análise crítica dos resultados obtidos, incluindo métricas como precisão, recall e F1-score.  
Os resultados esperados são um modelo capaz de generalizar bem para os dados de validação, com insights sobre possíveis melhorias e limitações.  

---

## Instruções para Execução do Código  

### 1. Requisitos de Software  
Antes de começar, certifique-se de ter as seguintes ferramentas instaladas:  
- **Python 3.8 ou superior**  
- **Bibliotecas Python:**  
  - TensorFlow  
  - NumPy  
  - Matplotlib  
  - Scikit-learn  

Recomenda-se o uso de um ambiente virtual (como `venv` ou `conda`) para isolar as dependências.  

### 2. Instalação de Dependências  
Clone o repositório e instale as dependências:  
```bash
git clone https://https://github.com/larissalemos-16/PtojetoT3Implementa-oeAnalise/edit/main/README.md
cd seu-repositorio
pip install -r requirements.txt

### 3. Principais considerações

Resultados Obtidos
O modelo atingiu uma acurácia média de X% e um F1-score médio de Y%, com desempenho superior em classes bem representadas.
A matriz de confusão revelou que imagens estilizadas são mais desafiadoras para o modelo.
Limitações Identificadas
Desbalanceamento de classes: Algumas classes apresentaram menor representação no dataset, o que impactou a performance do modelo.
Qualidade das imagens: A presença de ruído e variações de iluminação dificultaram a classificação.


