# Processamento Digital de Imagens — UFPel

**Professor:** Guilherme Ribeiro Corrêa  
**Instituição:** Universidade Federal de Pelotas — CDTec / Computação  

Repositório oficial da disciplina *Processamento Digital de Imagens (PDI)*.  
Este repositório contém os notebooks de laboratório (LABs), o diretório de imagens de teste (`/data`) e materiais de apoio utilizados ao longo do semestre.

---

## Estrutura dos LABs

### LAB00 — Introdução ao Ambiente Python/Colab  
**Arquivo:** `LAB00_Intro_PDI_Python.ipynb`  
Conteúdos:
- Introdução ao Google Colab e Jupyter Notebook  
- Bibliotecas essenciais (`numpy`, `matplotlib`, `scikit-image`, `opencv`, `imageio`)  
- Matrizes e operações com `numpy`  
- Leitura e exibição de imagens  
- Canais RGB  

---

### LAB01 — Amostragem, Quantização e Interpolação  
**Arquivo:** `LAB01_Amostragem_Quantização_Interpolação.ipynb`  
Conteúdos:
- Resolução espacial e tonal  
- Subamostragem e quantização  
- Interpolação: vizinho mais próximo, bilinear, bicúbica  

---

### LAB02 — Alargamento de Contraste  
**Arquivo:** `LAB02_Alargamento_Contraste.ipynb`  
Conteúdos:
- Transformações de intensidade  
- Alargamento linear  
- Equalização de histogramas (global e CLAHE)  

---

### LAB03 — Filtragem Espacial (Parte I)  
**Arquivo:** `LAB03_Filtragem_Espacial.ipynb`  
Conteúdos:
- Suavização: média, mediana e gaussiana  
- Realce: laplaciano e alta frequência  

---

### LAB04 — Filtragem Espacial (Parte II – Continuação)  
**Arquivo:** `LAB04_Filtragem_Espacial_cont.ipynb`  
Conteúdos:
- Realce de bordas  
- Combinação de filtros  
- Aplicações em imagens naturais  

---

### LAB05 — Filtragem no Domínio da Frequência  
**Arquivo:** `LAB05_Filtragem_Frequencias.ipynb`  
Conteúdos:
- Transformada de Fourier 2D  
- Visualização de espectros  
- Filtros passa-baixa, passa-alta e passa-faixa no domínio da frequência  

---

### LAB06 — Remoção de Ruído e Melhoria de Qualidade  
**Arquivo:** `LAB06_Remocao_Ruido_Melhoria_Qualidade.ipynb`  
Conteúdos:
- Modelos de ruído (gaussiano, sal-e-pimenta, speckle)  
- Filtros adaptativos e não-lineares  
- Técnicas de restauração  

---

### LAB07 — Imagens Coloridas  
**Arquivo:** `LAB07_Imagens_Coloridas.ipynb`  
Conteúdos:
- Modelos de cor: RGB, HSV, YCbCr, Lab  
- Conversões entre espaços de cor  
- Manipulação de canais  

---

### LAB08 — Compressão JPEG  
**Arquivo:** `LAB08_Compressao_JPEG.ipynb`  
Conteúdos:
- Conceitos de compressão  
- DCT e quantização  
- Análise do fator de qualidade e artefatos  

---

### LAB09 — Processamento Morfológico  
**Arquivo:** `LAB09_Processamento_Morfologico.ipynb`  
Conteúdos:
- Erosão, dilatação, abertura e fechamento  
- Extração de fronteiras  
- Preenchimento de buracos  
- Elementos estruturantes  

---

### LAB10 — Segmentação de Imagens  
**Arquivo:** `LAB10_Segmentacao.ipynb`  
Conteúdos:
- Limiarização global e local  
- Método de Otsu  
- Region growing  
- Rotulagem de componentes conectados  

---

## Estrutura do Repositório

/ <br>
├── data/ → Imagens de teste <br>
├── Notebooks de cada laboratório (LAB00 a LAB10) <br>
└── README.md → Documento principal da disciplina



---

## Como usar no Google Colab

1. Acesse o notebook na pasta `labs/`.  
2. Clique em **Open in Colab**.  
3. No Colab, selecione *File → Save a copy in Drive*.  
4. Execute todas as células e responda às atividades propostas.  

---

## Entregas

As atividades devem ser apresentadas em aula ao professor.
