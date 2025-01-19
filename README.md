# Climaclassification

Este repositório contém os arquivos relacionados à pesquisa realizada por **Júlia Marques Boaventura** (8105) e **Vinícius Meireles Pereira Santos** (8112) para a obtenção de créditos na disciplina **SIN 393 - Introdução à Visão Computacional**, sob orientação do **Prof. Dr. João Fernando Mari**.  

O objetivo do projeto foi **classificar imagens climáticas** utilizando técnicas de visão computacional e aprendizado profundo.  

## Conteúdo do Repositório
- **Dataset**: Utilizamos o dataset disponível no Kaggle, que pode ser acessado [aqui](https://www.kaggle.com/datasets/jehanbhathena/weather-dataset).
- **Códigos**: Incluem os testes realizados em diferentes épocas de treinamento.
- **Artigo**: Documento explicando o projeto e os resultados obtidos, que pode ser acessado [aqui](https://github.com/vinimeirelres/climaclassification/blob/d2769ad2194bffcb27ff3676a02ef6bf02f79821/Artigo/Classifica%C3%A7%C3%A3o_de_Condi%C3%A7%C3%B5es_Clim%C3%A1ticas_Usando_Redes_Neurais_Convolucionais.pdf)
- **Vídeo de Apresentação**: Uma breve explicação dos principais resultados, pode ser acessado [aqui]().

## Requisitos
Para executar os códigos, é necessário instalar as seguintes bibliotecas no ambiente de execução (ou carregá-las em caso de estar executando no Google Colab):

- `os`  
- `random`  
- `time`  
- `platform`  
- `numpy`  
- `matplotlib`  
- `scikit-learn`  
- `tqdm`  
- `torch` (PyTorch (com CUDA))  
- `seaborn`

## Instruções para Execução
1. **Baixar o Dataset**  
   Faça o download do dataset diretamente do [Kaggle](https://www.kaggle.com/datasets/jehanbhathena/weather-dataset) e salve-o em sua máquina.

2. **Configurar os Caminhos**  
   - Altere no código o caminho do dataset para corresponder à localização onde ele foi salvo em sua máquina.  
   - Configure também os caminhos para o **salvamento** (durante o treinamento) e **recuperação** (durante a avaliação) dos checkpoints.

3. **Executar o Código**  
   Com os pré-requisitos instalados e os caminhos configurados, você pode executar os scripts para treinar ou avaliar os modelos.

---

Sinta-se à vontade para sugerir melhorias ou reportar problemas no repositório.  
Agradecemos por conferir nosso projeto!


