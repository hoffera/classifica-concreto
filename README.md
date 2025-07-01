
# 🧱 Classificador de Fissuras em Concreto

Este é um aplicativo web construído com [Streamlit](https://streamlit.io/) que utiliza um modelo TensorFlow Lite para classificar **fissuras em concreto** como **positivas** (indicando presença de fissura relevante) ou **negativas** (sem fissura relevante), a partir de imagens fornecidas pelo usuário.

## 🔍 Funcionalidades

- Upload de imagens `.png`, `.jpg` ou `.jpeg`
- Redimensionamento automático da imagem para o formato exigido pelo modelo
- Normalização dos dados da imagem (valores entre 0 e 1)
- Classificação utilizando modelo `.tflite`
- Exibição interativa das probabilidades com gráfico de barras (Plotly)

## 🧠 Modelo

- Formato: `.tflite` (TensorFlow Lite)
- Tamanho da entrada: 64x64x3 (RGB)
- Classes previstas:
  - `positive` — Indica presença de fissura relevante
  - `negative` — Indica ausência de fissura relevante

O modelo é baixado automaticamente de um link do Google Drive:

