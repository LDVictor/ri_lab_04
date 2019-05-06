# Recuperação da Informação e Busca na Web
## Laboratório 04: Indexação e Processamento de Consulta

### Descrição

Nessa atividade você vai exercitar os conceitos de indexação e processamento de consultas vistos em sala. Utilizando a base de notícias que você coletou.

1. Execute o algoritmo ilustrado na Fig. 5.8 do livro texto (pag. 157) para gerar um índice similar o mostrado na Fig. 5.4 (pag. 134). Guarde o índice em disco em formato csv. (1 pt)

2. Implemente as abordagens de processamento de consulta documento-por-vez e termo-por-vez (Fig. 5.16 e 5.18). (2 pts)
  1. Defina 5 consultas de um termo somente.
  2. Execute as 5 consultas em cada algoritmo retornando os top-10 documentos (parâmetro k do algoritmo).
  3. Dê evidências de que sua implementação está correta.
  4. Compare os tempos médios de execução e uso de memória de cada algoritmo.

3. Implemente uma das versões de consulta conjuntiva (AND) (Fig. 5.20 ou 5.21). (2 pts)
  1. Defina 5 consultas conjuntivas (AND).
  2. Execute as 5 consultas em cada algoritmo retornando os top-10 documentos (parâmetro k do algoritmo).
  3. Dê evidências de que sua implementação está correta.

### Como entregar

Link para o notebook jupyter no GitHub ou Colab (de preferência) com o código comentado e explicado. É importante que tudo esteja bem documentado e explicado, incluindo por exemplo, estratégia usada para tokenização, estruturas de dados utilizadas, etc.
