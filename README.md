# Human trafficking data analysis

Estes dados consistem em informações sobre vítimas identificadas e relatadas de tráfico humano. As variáveis captam informações do perfil sociodemográfico das vítimas, o processo de tráfico (como meios de controle utilizados nas vítimas) e tipo de exploração.

Este conjunto de dados pode ser baixado do site da [*Counter Trafficking Data Collaborative*](https://www.ctdatacollaborative.org/) por qualquer pessoa interessada em realizar suas próprias análises. O conjunto de dados globais combina dados de diversos parceiros e é submetido a duas fases de desidentificação de dados. Primeiramente todos os nomes e detalhes de identificação são removidos dos dados antes da combinação e, após a combinação os dados são k-anonimizados (k=11).

K-anonimização (*K-anonymization*) é uma técnica de anonimização de dados que redige casos caindo em conjuntos com menos de k-1 membros, onde cada conjunto é definido por uma combinação única de valores das diferentes variáveis em um conjunto de dados. Isso significa que não é possível consultar um conjunto de dados e ter retorno inferior a um número pré-determinado (k-1) de resultados, independentemente da consulta. Com base em pesquisa e testes, adotou-se k=11 para os dados CTDC, o que significa que os casos foram redigidos a partir do conjunto de dados global de tal forma que as consultas para o conjunto de dados global não podem retornar menos de 10 resultados.

Salienta-se que este conjunto de dados não pode ser considerado uma amostra aleatória ou necessariamente representativa de todas as vítimas do tráfico de seres humanos a nível mundial, devido à natureza deste crime oculto.  O conjunto de dados é composto por casos identificados ou auto notificados de vítimas de tráfico. Na medida em que certos tipos de tráfico humano podem ser mais propensos a serem identificados, reconhecidos ou relatados, esse conjunto de dados será tendencioso em relação a esses tipos de tráfico em comparação com a população de vítimas de tráfico no mundo (identificados e não identificado). Os dados também podem ter um viés geográfico à medida que são coletados em locais onde as operações de combate ao tráfico são conduzidas.

Este app encontra-se disponível online aqui [Heroku](https://huma-trafficking.herokuapp.com/).