**Resumo do Caderno: Análise de Ações da B3**

O caderno em questão realiza uma análise de ações da B3 (Bolsa de Valores brasileira) com o objetivo de agrupá-las em clusters, utilizando técnicas como Clusterização Hierárquica e DBSCAN. Abaixo segue um resumo dos principais passos e resultados obtidos:

1. **Escolha dos Dados:**
   - Utilização de dados históricos de fechamento das ações mais comentadas da B3.
   - Símbolos obtidos através de uma consulta com uma API no site Infomoney.

2. **Justificativa e Objetivos:**
   - Motivação: Volatilidade econômica pós-COVID-19 dificulta identificação de ações sólidas.
   - Objetivos: Identificar padrões de semelhança, avaliar resiliência empresarial e revelar tendências e oportunidades.

3. **Coleta de Dados:**
   - Scraping dos códigos das ações mais ativas na B3 usando BeautifulSoup.

4. **Pré-Processamento:**
   - Normalização dos dados utilizando Standard Scaler.
   - Substituição de valores "nan" por "0".

5. **Clusterização Hierárquica:**
   - Análise de correlação entre séries temporais.
   - Utilização de dendrograma para visualização de clusters.
   - Identificação de grupos de ações com comportamentos semelhantes.

6. **DBSCAN (Density-Based Spatial Clustering of Applications with Noise):**
   - Aplicação do DBSCAN para identificar clusters baseados na densidade de pontos.
   - Destaque de outliers.

7. **Silhueta e Validação:**
   - Uso de índice de silhueta para avaliação dos clusters.
   - Escolha do número ideal de clusters utilizando método Elbow.

8. **Análise PCA com K-Means:**
   - Redução de dimensionalidade com PCA.
   - Utilização do K-Means para clustering.
   - Comparação de resultados com técnica de silhueta e método Elbow.

9. **Considerações Finais:**
   - Avaliação dos resultados obtidos com cada técnica.
   - Destaque para clusters que refletem características específicas das ações.

10. **Link para o Notebook:** [Análise de Ações da B3](https://colab.research.google.com/drive/14Pkyu52GDLNJx30bQ6LGkcdaiGTBnuow?usp=sharing)

O caderno proporciona uma abordagem abrangente na análise de séries temporais de ações, utilizando diversas técnicas de clusterização e validação.
