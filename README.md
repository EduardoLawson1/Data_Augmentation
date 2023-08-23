# Aumento de Dados com CLAHE, Recorte Central, Espelhamento Horizontal e Rotação Aleatória 90 Graus

Aprimorar a diversidade e qualidade dos seus dados de treinamento é essencial para criar modelos de aprendizado de máquina robustos. Em tarefas de visão computacional, técnicas de aumento de dados desempenham um papel crucial na melhoria da generalização do modelo. Este repositório fornece um trecho de código em Python para realizar o aumento de dados usando as técnicas de CLAHE (Equalização Adaptativa de Histograma Limitado por Contraste), Recorte Central, Espelhamento Horizontal e Rotação Aleatória 90 Graus.

## Sobre o Código

Aumento de dados é uma técnica que envolve a aplicação de várias transformações nas suas imagens de treinamento, criando novas variações ao mesmo tempo em que mantém a integridade do conteúdo original. Este código demonstra como realizar as seguintes técnicas de aumento:

1. **CLAHE (Equalização Adaptativa de Histograma Limitado por Contraste):** Aprimora o contraste local, tornando os detalhes mais visíveis em regiões claras e escuras.
2. **Recorte Central:** Extrai a região central da imagem, focando no conteúdo mais importante.
3. **Espelhamento Horizontal:** Espelha a imagem horizontalmente, proporcionando uma perspectiva diferente.
4. **Rotação Aleatória 90 Graus:** Gira a imagem aleatoriamente em 90 graus, diversificando a orientação.

Essas técnicas juntas criam um conjunto de dados de treinamento mais diversificado, ajudando o seu modelo a generalizar melhor para várias situações do mundo real.

## Como Usar

1. Clone este repositório para a sua máquina local.
2. Modifique o trecho de código fornecido em `Data_Augmentation.ipynb` para se adequar ao seu conjunto de dados e caminhos de arquivo.
3. Execute o script `Data_Augmentation.ipynb` para aplicar as técnicas de aumento nas suas imagens.

## Dependências

O código fornecido aqui utiliza as seguintes bibliotecas Python:

- OpenCV
- Albumentations
- OS

