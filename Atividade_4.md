# Atividade 4 - 21/11 - Entrevistas com moradores e outros levantamento de campo

![](Imagens/DJI_20251121115918_0415_D.jpg)

## Equipamentos Utilizados

### Mavic Air 3
A aerofotogrametria é uma técnica de mapeamento que utiliza fotografias aéreas para obter medidas precisas de objetos e da superfície terrestre, permitindo a criação de mapas, plantas e modelos 3D (como ortofotos e Modelos Digitais de Elevação - MDE). O advento dos Drones (ou Veículos Aéreos Não Tripulados - VANTs) revolucionou essa técnica, tornando-a muito mais acessível, rápida e econômica em comparação com a aerofotogrametria tradicional realizada por aeronaves tripuladas.

No contexto do trabalho de campo, o drone atua como uma plataforma de sensoriamento remoto de baixa altitude. Ele é programado para seguir rotas de voo predefinidas, capturando uma grande quantidade de imagens sobrepostas do terreno. Essas imagens são posteriormente processadas por softwares específicos, que utilizam algoritmos de visão computacional e estrutura por movimento (SfM) para reconstruir a geometria da área. O resultado é um produto cartográfico de alta resolução espacial, ideal para estudos de detalhe em diversas aplicações geográficas, como monitoramento ambiental, análise urbana e gestão territorial.

O equipamento utilizado para a coleta de dados, o DJI Air 3, é um drone de médio porte que se destaca por sua portabilidade e, principalmente, por seu sistema de câmera dupla principal.

As principais características que o tornam adequado para trabalhos de campo em Geografia e Fotogrametria incluem:

Sistema de Câmera Dupla: O Air 3 possui duas câmeras CMOS de 1/1.3 polegada que podem capturar imagens de 48 megapixels (MP).

![](https://blog.proaventura.com.br/wp-content/uploads/2023/08/Lancamento_drone_DJI_Air_3_Saiba_tudo_sobre_ele-2-1024x576.png)

Câmera Grande-Angular: Equivalente a 24 mm, oferece um amplo campo de visão, ideal para o mapeamento geral de grandes áreas.

Câmera Telefoto Média (3x): Equivalente a 70 mm, permite capturar detalhes de objetos a uma distância segura, mantendo uma perspectiva mais próxima da realidade (menos distorção de grande-angular).

Tempo Máximo de Voo: Cerca de 46 minutos, o que aumenta significativamente a área que pode ser mapeada em um único voo, otimizando o tempo de campo.

Detecção de Obstáculos Omnidirecional: Este recurso garante a segurança do voo ao detectar obstáculos em todas as direções, fundamental para operações em terrenos irregulares ou com infraestrutura.

Transmissão de Vídeo O4: Oferece um link de transmissão de vídeo robusto e de longo alcance, garantindo o controle e o monitoramento em tempo real do voo, crucial para a precisão da coleta de dados.

O uso do Air 3, com sua capacidade de alta resolução e autonomia, assegura a obtenção de dados de qualidade métrica para o processamento fotogramétrico do projeto.

### Trimble DA2 Geo 

Para garantir a precisão geométrica do mapeamento fotogramétrico obtido com o drone, foi essencial o estabelecimento de Pontos de Controle em Solo (GCPs). Os GCPs são alvos visíveis na superfície do terreno, marcados antes do voo, que servem como referências para georreferenciar e ajustar o modelo tridimensional gerado a partir das imagens aéreas, corrigindo erros sistêmicos e garantindo que o produto final esteja rigorosamente posicionado no sistema de coordenadas adotado.

![](https://scparana.com.br/wp-content/uploads/2025/03/4-1024x576.jpg)

A coleta das coordenadas de alta precisão desses pontos foi realizada com o receptor GNSS Trimble DA2 Geo. Este equipamento de nível profissional, quando pareado com a tecnologia de correção Trimble RTX (Real-Time eXtended), possibilitou o posicionamento de precisão centimétrica sem a necessidade de uma estação base local (RTK), utilizando correções transmitidas via satélite. O fluxo de trabalho envolveu a ocupação dos alvos dos GCPs por um período determinado para convergência da solução RTX, registrando as coordenadas geodésicas (latitude, longitude e altitude). A utilização deste método de Posicionamento por Satélite de Precisão (PPP) assegura que os GCPs forneçam uma base de referência cartográfica de elevada confiança, sendo um passo crucial para a acurácia horizontal e vertical dos ortomosaicos e Modelos Digitais de Elevação (MDE) produzidos.

### Lidar FJD Trion P1 

Em complemento à nuvem de pontos gerada pela aerofotogrametria, que se destaca na modelagem da superfície e elementos superiores, utilizou-se a tecnologia LiDAR SLAM (Simultaneous Localization and Mapping) para a aquisição de dados em trechos específicos. O equipamento empregado foi o FJD Trion P1, um scanner a laser terrestre que coleta rapidamente milhões de pontos tridimensionais, resultando em nuvens de pontos coloridas de altíssima densidade e precisão.

![](https://www.fjdynamics.com/web/image/144894-c25e391e/P1.png)

O uso do LiDAR SLAM foi crucial em áreas onde a cobertura aérea, seja por densa vegetação ou por estruturas verticais (como fachadas de edifícios), limitava a visibilidade do solo ou a obtenção de detalhes precisos. A principal vantagem desta abordagem foi a possibilidade de combinar as nuvens de pontos aéreas e terrestres. Essa fusão de dados permite a criação de um Modelo 3D Integrado e completo, superando as limitações individuais de cada método: a componente aérea fornece o contexto geral e a geometria superior, enquanto a componente terrestre preenche os vazios de dados (ex: sob a copa das árvores ou em faces verticais) e detalha a geometria do solo e elementos urbanos. A integração desses conjuntos de dados garante um mapeamento final com acurácia superior e riqueza de detalhes para todas as feições da área de estudo.




## Mapa 1
[Áreas Mapeadas com RPA](https://alixandrini.github.io/Webmapa2/) 

[Ortomosaico Siribinha](https://oin-hotosm-temp.s3.us-east-1.amazonaws.com/69233a91e9b232b73ea3b87c/0/69233a91e9b232b73ea3b87d.tif)

[OpenAerialMap](https://map.openaerialmap.org/#/-37.52449035644531,-11.763165316465917,16/square/211021010321220031/69233cc6e9b232b73ea3bcea?_k=neg5l0)

[Relatório de Processamento Ortofoto Siribinha](Relatorios/Report.pdf) 
 