# UFRN_BIB
Projeto do 7DayOfCode para análise de empréstimos de livros da biblioteca da UFRN
Pronto, fiz a primeira etapa de juntar os dados em um único DataFrame importando primeiro os emprestimos tipo csv com read_csv()
e depois o dados_exemplares tipo Apache Parquet com read_parquet(). Depois limpei com o drop_duplicates() em um novo DataFrame df_concact_cleaned.
Notei muitos registro NaN na culuna data_renovacao, ainda analisando se essa coluna será necessária ou não e decidir o melhor tratamento se será exclui-la com o dropna() ou completar com datas padronizadas de prazo máximo de devolução. Ainda analisando...
