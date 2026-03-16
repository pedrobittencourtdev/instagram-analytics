# 📊 Instagram Analytics — Análise de Desempenho para Agências de Marketing

![Python](https://img.shields.io/badge/Python-blue)
![Pandas](https://img.shields.io/badge/Pandas-green)
![Status](https://img.shields.io/badge/Status-Concluído-brightgreen)

## 📌 Sobre o Projeto

Análise exploratória de dados de **29.999 posts do Instagram**, com o objetivo de 
identificar os melhores nichos, formatos e horários para maximizar o engajamento 
de clientes de uma agência de marketing digital.

> Dados retirados da plataforma [Kaggle](https://www.kaggle.com).

---

## 🎯 Objetivos

- Identificar quais categorias de conteúdo geram mais engajamento
- Descobrir os melhores dias e horários para postar
- Avaliar o impacto do formato de mídia (Reel, Image, Carousel)

---

## 🔍 Principais Insights

| Análise | Resultado |
|--------|-----------|
| 🏆 Top categorias | Music, Fitness e Fashion |
| 📅 Melhor dia (Fashion) | Terça-feira |
| 📅 Melhor dia (Music) | Sábado |
| ⏰ Melhores horários | 02h, 03h e 08h |
| 🎬 Melhor formato | Equivalentes (diferença < 0.5%) |

---

## 📁 Estrutura do Projeto
```
instagram-analytics/
│
├── SocialMediaDataAnalysis.ipynb   # Notebook principal
├── Instagram_Analytics.csv         # Dataset
├── grafico_engajamento.png
├── grafico_saves.png
├── melhores_dias_postagem.png
├── heatmap_hora_dia.png
├── grafico_media_type.png
└── README.md
```

---

## 🛠️ Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## ▶️ Como Executar

1. Clone o repositório:
```bash
git clone https://github.com/pedrobittencourtdev/instagram-analytics.git
```

2. Instale as dependências:
```bash
pip install pandas numpy matplotlib seaborn
```

3. Abra o notebook:
```bash
jupyter notebook SocialMediaDataAnalysis.ipynb
```

> As dependências também são instaladas automaticamente ao executar 
> a primeira célula do notebook.

---

## ⚠️ Limitações

- Dataset sintético do Kaggle — pode não refletir dados reais do Instagram
- Diferenças de engajamento entre categorias são pequenas (< 1%)


---

## 👨‍💻 Autor

**Pedro Bittencourt**  
Estudante de Engenharia de Software

[![GitHub](https://img.shields.io/badge/GitHub-pedrobittencourtdev-black?logo=github)](https://github.com/pedrobittencourtdev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Pedro%20Bittencourt-blue?logo=linkedin)](https://www.linkedin.com/in/pedro-lucas-bittencourt/)