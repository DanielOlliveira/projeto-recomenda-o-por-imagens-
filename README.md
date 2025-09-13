🔍 Sistema de Recomendação Visual com Imagens
Este projeto implementa um sistema de recomendação baseado em similaridade visual entre imagens de produtos. A partir de uma imagem de entrada, o sistema retorna os itens mais parecidos visualmente, utilizando redes neurais pré-treinadas para extração de características.

Estrutura do Projeto
sistema-recomendacao-imagens/
├── notebook.ipynb
├── README.md

Dataset Utilizado
O dataset está hospedado no repositório:

🔗 DanielOlliveira/recomendacao-dataset

Estrutura do dataset:
recomendacao-dataset/
├── relogios/
├── oculos/
├── fones/
├── mochilas/
├── consulta/
│   └── relogio_timewear.png

Cada pasta representa uma categoria de produto com imagens reais. A imagem de consulta está em consulta/.

Resultado Esperado
O sistema exibe:

A imagem de origem (consulta)

As 5 imagens mais similares visualmente, com pontuação de similaridade

Tecnologias Utilizadas
Python

TensorFlow / Keras

MobileNetV2

OpenCV

Scikit-learn

Google Colab
