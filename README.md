**Resumo do Caderno para GitHub: Análise de Ações da B3**

O caderno realiza uma análise de ações da B3 (Bolsa de Valores brasileira), agrupando-as em clusters através de técnicas como Clusterização Hierárquica e DBSCAN. Seguem os principais passos e resultados:

1. **Escolha dos Dados:**
   - Dados históricos de fechamento das ações mais comentadas da B3.
   - Símbolos obtidos via API no site Infomoney.

2. **Justificativa e Objetivos:**
   - Motivação: Volatilidade pós-COVID-19 dificulta identificação de ações sólidas.
   - Objetivos: Identificar padrões, avaliar resiliência e revelar tendências.

3. **Coleta de Dados:**
   - Scraping dos códigos das ações mais ativas na B3 via BeautifulSoup.

4. **Pré-Processamento:**
   - Normalização dos dados com Standard Scaler.
   - Substituição de valores "nan" por "0".

5. **Clusterização Hierárquica:**
   - Análise de correlação entre séries temporais.
   - Dendrograma para visualização de clusters.
   - Identificação de grupos de ações com comportamentos semelhantes.

6. **DBSCAN:**
   - Aplicação para identificar clusters baseados na densidade de pontos.
   - Destaque de outliers.

7. **Silhueta e Validação:**
   - Índice de silhueta para avaliação dos clusters.
   - Escolha do número ideal de clusters com método Elbow.

8. **Análise PCA com K-Means:**
   - Redução de dimensionalidade com PCA.
   - Uso do K-Means para clustering.
   - Comparação de resultados com técnica de silhueta e método Elbow.

9. **Considerações Finais:**
   - Avaliação dos resultados obtidos com cada técnica.
   - Destaque para clusters refletindo características específicas das ações.

10. **Link para o Notebook:** [Análise de Ações da B3](https://colab.research.google.com/drive/14Pkyu52GDLNJx30bQ6LGkcdaiGTBnuow?usp=sharing)

O caderno proporciona uma abordagem abrangente na análise de séries temporais de ações, utilizando diversas técnicas de clusterização e validação.
