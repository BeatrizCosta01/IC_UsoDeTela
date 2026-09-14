# ARTIGO_22 Técnicas Psicométricas nas Pesquisas de Opinião: Mensuração de Ideologia com TRI por Institutos de Pesquisa

#### Topo da Pirâmide: Artigo Essencial e Decisivo

---

## Identificação do Estudo

* **Título Original:** Técnicas Psicométricas nas Pesquisas de Opinião: Mensuração de Ideologia com TRI por Institutos de Pesquisa


* **Autores:** João Cardoso Lara Camargos, João Paulo Dellasta do Nascimento e Magno Peluso Torquette


* **Periódico:** *Conexão Política*, Vol. 12, Nº 2, pp. 98–127


* **Ano / Ref:** 2023


* **Tipo de Estudo:** Estudo Metodológico / Aplicação Psicométrica Empírica (TRI Multidimensional)



---

## Referência Bibliográfica

* **Formato ABNT:**

> CAMARGOS, João Cardoso Lara; NASCIMENTO, João Paulo Dellasta do; TORQUETTE, Magno Peluso. Técnicas psicométricas nas pesquisas de opinião: mensuração de ideologia com TRI por institutos de pesquisa. **Conexão Política**, Teresina, v. 12, n. 2, p. 98-127, jul./dez. 2023.
> 
> 

* **Formato APA (7ª ed.):**

> Camargos, J. C. L., Nascimento, J. P. D., & Torquette, M. P. (2023). Técnicas psicométricas nas pesquisas de opinião: mensuração de ideologia com TRI por institutos de pesquisa. *Conexão Política*, 12(2), 98–127.
> 
> 

---

## Por que o Artigo foi Escolhido / Contribuição para o Projeto

* **Justificativa da Escolha:** Selecionado por prover a fundamentação metodológica para o tratamento psicométrico rigoroso de variáveis latentes subjetivas e não observáveis diretamente (como percepções, sentimentos e autoavaliações de saúde mental) por meio da Teoria de Resposta ao Item (TRI).


* **Contribuição Teórica:** Demonstra formalmente como modelos probabilísticos de TRI superam as limitações estruturais de *proxies* únicas e de índices aditivos simples (que assumem erroneamente pesos idênticos para todos os itens), capturando a variação contínua do traço latente sem exigir normalidade estrita em dados ordinais.


* **Aplicação Prática no Projeto:** Ampara metodologicamente a estratégia de análise de instrumentos de autorrelato (como IDHC e escalas de ansiedade), justificando por que a mensuração de percepções subjetivas deve ser modelada via traço latente indutivo para calibrar adequadamente a contribuição e a capacidade de discriminação de cada item.



---

## Síntese e Metodologia

* **Objetivo:** Demonstrar a viabilidade e a superioridade da aplicação de modelos psicométricos multidimensionais de Teoria de Resposta ao Item (TRI) na mensuração operacional de construtos latentes abstratos e ordinais.


* **Amostra:** Amostra total de $N = 2.989$ respondentes brasileiros, dividida em três coletas conduzidas pelo Instituto Ver: Belo Horizonte em novembro de 2019 ($N = 1.000$), Belo Horizonte em março de 2020 ($N = 1.189$) e Contagem em setembro de 2019 ($N = 800$).


* **Delineamento e Procedimentos:**
* **Instrumento:** Bloco de 23 questões ordinais estruturadas em escala Likert graduada de 4 pontos ("Concordo totalmente" a "Discordo totalmente").


* **Modelagem Psicométrica:** Emprego do Modelo de Resposta Graduada de Samejima (1969), específico para dados ordinais, com estimação exploratória de máxima verossimilhança via pacote `mirt` no software R.


* **Comparação Metodológica:** Teste comparativo via ANOVA para avaliar o ajuste estatístico entre modelos unidimensionais e bidimensionais utilizando o Critério de Informação de Akaike ($AIC$) e o Critério Bayesiano de Informação ($BIC$).


* **Validação Preditiva:** Aplicação dos escores latentes gerados pela TRI como variáveis dependentes em modelos de Regressão por Mínimos Quadrados Ordinários (MQO) contra preditores demográficos e atitudinais.



---

## Resultados Psicológicos e Psicométricos

* **Ajuste e Multidimensionalidade do Traço Latente:** O modelo bidimensional apresentou desempenho explicativo estatisticamente superior ao modelo unidimensional em todas as coletas (menores valores de $AIC$ e $BIC$; ex.: BH 2020 com $AIC = 40.990,39$ no modelo bidimensional vs $41.666,69$ no unidimensional), comprovando a natureza multidimensional de construtos latentes complexos.


* **Estimativa dos Parâmetros dos Itens:** A TRI permitiu extrair o parâmetro de discriminação ($a$) e de intercepto/dificuldade ($D$), demonstrando que itens em formato ordinal idêntico possuem pesos e capacidades nitidamente desiguais para distinguir os níveis da variável latente.


* **Padronização do Traço Latente (Escore $\theta$):** O modelo de Samejima padronizou a variável latente contínua com média e mediana centradas em zero, resultando em uma distribuição com tendência à normalidade que facilita a aplicação direta em modelos econométricos e estatísticos inferenciais sem violação de pressupostos.


* **Superação dos Erros do Índice Aditivo:** Demonstrou-se que somar itens em escalas aditivas simples atribui pesos arbitrários e gera diagnósticos imprecisos, ao passo que o ajuste indutivo via TRI minimiza o erro de mensuração e capta flutuações graduais com maior assertividade.



---

## Citações Chave (*Key Quotes*)

> "Operacionalizar conceitos para serem medidos em larga escala envolvem uma série de nuances, pois as respostas em pesquisas de survey estão sujeitas a uma série de vieses [...] transformar abstrações em indicadores empíricos que possibilitem a análise."
> 
> 

> "Índices aditivos apresentam um problema central, pois assumem que as variáveis contribuem com o mesmo peso, além de serem, em essência, dedutivos [...]. A TRI fornece pesos precisos para cada item, permitindo ajustar o modelo de acordo com múltiplas características."
> 
> 

> "A TRI provê estimativas específicas para avaliarmos a performance das perguntas em mensurar as dimensões criadas, sendo que a maioria dos modelos trabalha com dois parâmetros: o parâmetro de discriminação ou curva do item ($a$) [...] e o parâmetro de dificuldade ou intercepto do item ($D$)."
> 
>