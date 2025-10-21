
<p align="center">
  <img src="https://raw.githubusercontent.com/Henrique0501/Meu_Portfolio/main/static/Logo_HM.png">
</p>

<h1 align="center">
Power Regressor
</h1>

> Plataforma web interativa para criação, treinamento e análise de modelos de regressão sem necessidade de programação.

<p align="center">
  <a href="[https://henriquemartins.herokuapp.com/](https://powerregressor.onrender.com/)" target="_blank">Link do projeto</a>
</p>

<p align="center">
  <img src="http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg" href="https://creativecommons.org/licenses/by-nc-nd/4.0/">
</p>
[![Flask](https://img.shields.io/badge/Flask-3.0+-green.svg)](https://flask.palletsprojects.com/)
[![License: CC BY-NC-ND 4.0](https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-nd/4.0/)



---

## 📋 Índice

- [Sobre](#sobre)
- [Funcionalidades](#funcionalidades)
- [Tecnologias](#tecnologias)
- [Permissões Especiais](#permissões-especiais)

---

## Sobre

**Power Regressor** é uma plataforma web que democratiza o acesso a modelos de Machine Learning, permitindo que usuários sem conhecimento de programação possam:

- 📊 Fazer upload de datasets (CSV, Excel, JSON)
- 🤖 Treinar múltiplos modelos de regressão simultaneamente
- 📈 Visualizar resultados com gráficos interativos
- 💾 Exportar modelos treinados e predições
- 🎨 Comparar performance de diferentes algoritmos

**Ideal para:** Analistas de dados, estudantes, pesquisadores e profissionais que precisam criar modelos preditivos rapidamente.

---

## Funcionalidades

### 🔹 Gestão de Dados
- ✅ Upload de múltiplos formatos (CSV, XLSX, JSON)
- ✅ Visualização prévia dos dados
- ✅ Seleção interativa de features e target
- ✅ Tratamento automático de valores ausentes

### 🔹 Treinamento de Modelos
- ✅ **8 algoritmos disponíveis:**
  - Linear Regression
  - Ridge Regression
  - Lasso Regression
  - Random Forest
  - XGBoost
  - LightGBM
  - Prophet (séries temporais)
  - LSTM (redes neurais)
- ✅ Configuração de hiperparâmetros via interface
- ✅ Cross-validation automático
- ✅ Suporte a Forecaster Recursive (previsões recursivas)
- ✅ Controle de train/test split e shuffle

### 🔹 Análise e Visualização
- ✅ Métricas de performance (R², RMSE, MAE)
- ✅ Feature importance
- ✅ Gráficos interativos (Plotly)
- ✅ Comparação lado a lado de modelos
- ✅ Análise de treino vs teste
- ✅ Detecção de overfitting

### 🔹 Export e Persistência
- ✅ Download de modelos (Joblib, Pickle, JSON)
- ✅ Export de predições (CSV)
- ✅ Sessões isoladas por usuário
- ✅ Limpeza automática de dados antigos

### 🔹 Interface
- ✅ Design moderno e responsivo
- ✅ Tema claro/escuro
- ✅ Drag & drop para organização de cards
- ✅ Gráficos em tela cheia
- ✅ Presets para análise rápida

---

## Tecnologias

### Backend
- **Flask 3.0+** - Framework web
- **Flask-Session** - Gerenciamento de sessões
- **Flask-CORS** - Suporte a requisições cross-origin
- **Pandas** - Manipulação de dados
- **NumPy** - Computação numérica
- **Scikit-learn** - Modelos de ML clássicos
- **XGBoost** - Gradient boosting
- **LightGBM** - Gradient boosting otimizado
- **Skforecast** - Forecasting recursivo
- **Prophet** - Previsão de séries temporais
- **Plotly** - Visualizações interativas

### Frontend
- **HTML5 / CSS3** - Estrutura e estilo
- **JavaScript (Vanilla)** - Lógica do cliente
- **Plotly.js** - Gráficos interativos
- **Font Awesome** - Ícones

### Infraestrutura
- **Gunicorn** - Servidor WSGI (produção)
- **Python-dotenv** - Gerenciamento de variáveis de ambiente

---

### Permissões Especiais

Para uso comercial ou modificações, entre em contato:
- Email: [mf.henrique05@gmail.com](mailto:mf.henrique05@gmail.com)

Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
