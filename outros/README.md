# Resumos dos artigos

A pasta contém quatro trabalhos relacionados à previsão de nuvens e irradiância solar. Abaixo está um pequeno resumo de cada um deles.

## Determination of Cloud Motion Applying the Lucas-Kanade Method to Sky Cam Imagery
Modelo que usa imagens de uma câmera do céu e o método de fluxo óptico de Lucas-Kanade para prever o deslocamento das nuvens. O foco é a previsão de curto prazo para otimização de usinas solares, alcançando cerca de 92% de acerto em 10 minutos e 82% para 25–30 minutos à frente.

## Development of advanced cloud classification and segmentation models for solar energy applications using deep learning and synthetic data augmentation
Dissertação que amplia um conjunto de dados de nuvens usando segmentação semissupervisionada e testa várias arquiteturas de redes neurais. A inclusão de mapas de fluxo óptico como indício de movimento melhora a segmentação, elevando a precisão e o IoU em alguns pontos percentuais.

## Optimizing cloud motion estimation on the edge with phase correlation and optical flow
Estudo sobre a extração de vetores de movimento das nuvens por correlação de fase em blocos, analisando tamanho do bloco, intervalo entre quadros e canais de cor. A técnica é comparada ao fluxo óptico e aplicada em uma plataforma de computação de borda para prever nuvens em tempo real.

## Precise Forecasting of Sky Images Using Spatial Warping
Apresenta o SkyNet, método que utiliza redes neurais e uma etapa de "warping" espacial para diminuir a distorção perto do horizonte nas câmeras hemisféricas. A abordagem gera previsões de imagens do céu em maior resolução, o que ajuda em horizontes de tempo mais longos.
