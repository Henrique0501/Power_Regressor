# Power Regressor

> Plataforma web interativa para criação, treinamento e análise de modelos de regressão sem necessidade de programação.

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/Flask-3.0+-green.svg)](https://flask.palletsprojects.com/)
[![License: CC BY-NC-ND 4.0](https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-nd/4.0/)
[![Status](https://img.shields.io/badge/Status-Beta-orange.svg)]()

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
