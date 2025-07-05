# Climaclassification

Projeto desenvolvido por **Júlia Marques Boaventura** e **Vinícius Meireles Pereira Santos** para a disciplina **SIN 393 - Introdução à Visão Computacional**, sob orientação do **Prof. Dr. João Fernando Mari** na **Universidade Federal de Viçosa**.

O objetivo do trabalho é **classificar condições climáticas em imagens** utilizando **redes neurais convolucionais (CNNs)** e técnicas de **visão computacional**. O projeto inclui experimentos com diferentes configurações e épocas de treinamento.

---

## 🔍 Visão Geral

- 🔗 **Artigo com detalhes do projeto**:  
  [Classificação de Condições Climáticas Usando Redes Neurais Convolucionais (PDF)](https://github.com/vinimeirelres/climaclassification/blob/d2769ad2194bffcb27ff3676a02ef6bf02f79821/Artigo/Classifica%C3%A7%C3%A3o_de_Condi%C3%A7%C3%B5es_Clim%C3%A1ticas_Usando_Redes_Neurais_Convolucionais.pdf)

- 🎞️ **Vídeo de Apresentação**:  
  [https://youtu.be/5lR9iDkAUJw](https://youtu.be/5lR9iDkAUJw)

---

## 🧪 Como Executar

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/vinimeirelres/climaclassification.git
   cd climaclassification
   ```

2. **Crie e ative o ambiente virtual:**
   ```bash
   python -m venv venv
   source venv/bin/activate        # ou venv\Scripts\activate no Windows
   ```

3. **Instale as dependências:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Execute os notebooks:**
   - Um dos notebooks realiza o treinamento do modelo.
   - Outro notebook executa a avaliação com métricas.
   - Outro notebook exibe visualizações dos resultados.

---

## 📦 Dataset

As imagens utilizadas já estão incluídas no repositório local, portanto **não é necessário baixá-las novamente do Kaggle**.  
Caso deseje utilizar a fonte original por conta própria:  
🔗 [Weather Dataset – Kaggle](https://www.kaggle.com/datasets/jehanbhathena/weather-dataset)

---

## 🧰 Tecnologias Utilizadas

- Python  
- PyTorch  
- OpenCV  
- Matplotlib  
- Seaborn  
- scikit-learn  
- Jupyter Notebooks

---

## 📄 Licença

Este projeto é de uso **educacional/acadêmico** e não possui fins comerciais.  
Sinta-se livre para estudar e modificar, mas credite os autores.

---

## 🌐 English Version (Short Summary)

**Climaclassification** is an academic project developed during the course *Introduction to Computer Vision* at UFV (Brazil). It classifies weather conditions in images using convolutional neural networks (CNNs). The dataset is included, and the project contains training, evaluation and visualization notebooks.  
See also: [📽️ video](https://youtu.be/5lR9iDkAUJw) | [📄 article (PDF)](https://github.com/vinimeirelres/climaclassification/blob/main/Artigo/Classifica%C3%A7%C3%A3o_de_Condi%C3%A7%C3%B5es_Clim%C3%A1ticas_Usando_Redes_Neurais_Convolucionais.pdf)
