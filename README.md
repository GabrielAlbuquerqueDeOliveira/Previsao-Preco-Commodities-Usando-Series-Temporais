# 📊 Previsão de Preços do Café no Brasil

Este projeto realiza a previsão dos preços do café no Brasil utilizando o modelo de séries temporais **ARIMA**. O objetivo é analisar a eficácia do modelo e gerar previsões confiáveis para auxiliar produtores, investidores e formuladores de políticas públicas no contexto do mercado de commodities.

---

## 📁 Estrutura do Projeto

| Caminho | Descrição |
|---------|-----------|
| [`Previsao_cafe.ipynb` ](https://github.com/GabrielAlbuquerqueDeOliveira/Time-Series-Analysis/blob/main/S%C3%A9ries_Temporais_preco_cafe.ipynb) | Notebook principal com a análise e previsão dos preços do café |
| [`data` ](https://github.com/GabrielAlbuquerqueDeOliveira/Time-Series-Analysis/blob/main/cepea-consulta-modificadaxls.xlsx) | Pasta contendo dados do CEPEA/ESALQ preço do café 2023 |
| [`data` ](https://github.com/GabrielAlbuquerqueDeOliveira/Time-Series-Analysis/blob/main/Preco_cafe_2024_observado.xlsx) | Pasta contendo os dados do CEPEA/ESALQ preço do café 2024 |

---

## 🚀 Funcionalidades

- Coleta e tratamento de dados de preços diários do café
- Testes de estacionaridade (ADF e KPSS)
- Determinação de parâmetros ideais do modelo ARIMA (p, d, q)
- Ajuste do modelo ARIMA e diagnóstico dos resíduos
- Previsão de preços para os primeiros 60 dias de 2024
- Avaliação do modelo utilizando RMSE, MAE e MAPE
- Proposta de análises futuras para 2026

---

## 📦 Dataset

Os dados foram coletados a partir das seguintes fontes:

- 🔗 [CEPEA/ESALQ - Indicador do Café](https://www.cepea.esalq.usp.br/br/indicador/cafe.aspx)  
- 🔗 [Comex Stat - Exportações Brasileiras](https://comexstat.mdic.gov.br/pt/home)  

O dataset inclui preços diários do café em 2023 e dados de exportação para contextualizar a importância econômica da commodity.

---

## ▶️ Como Executar

Clone este repositório:

``bash
git clone https://github.com/seu_usuario/seu_repositorio.git
cd seu_repositorio
Instale as dependências (recomenda-se usar um ambiente virtual):

bash
Copiar
Editar
pip install -r requirements.txt
Execute o notebook: Você pode abrir o notebook diretamente no Jupyter ou no Google Colab:

Abrir no Colab

## 📊 Exemplos de Visualizações
Alguns gráficos presentes na análise:

Série temporal dos preços históricos do café

Preço real vs preço previsto para os primeiros 60 dias de 2024

Histogramas e análise dos resíduos do modelo ARIMA

Funções de autocorrelação (ACF) e autocorrelação parcial (PACF)

Comparação entre previsões e valores reais

(Confira todos os gráficos no notebook.)

## 🛠️ Tecnologias Utilizadas
Python 3.10+

Pandas

NumPy

Matplotlib

Statsmodels

Scikit-Learn

OpenPyXL

Jupyter Notebook / Google Colab

## 👤 Autoria

Desenvolvido por **Gabriel Albuquerque de Oliveira**  
🔗 [GitHub](https://github.com/GabrielAlbuquerqueDeOliveira)  
📧 gabriel.ooo@hotmail.com
💼 [LinkedIn](www.linkedin.com/in/gabriel-albuquerque-oliveira98)

## 📄 Licença
Este projeto está licenciado sob os termos da Licença MIT.

MIT License

```
Copyright (c) 2025 Gabriel Albuquerque

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

[...licença completa no arquivo LICENSE...]
```
## 🤝 Contribuições
Contribuições são bem-vindas!

Sinta-se à vontade para abrir issues ou pull requests com sugestões e melhorias.
