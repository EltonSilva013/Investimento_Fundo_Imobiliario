# 🏢 Estudo e Análise de Fundos Imobiliários (FIIs) com Inteligência Artificial

## 📝 1. Contexto e Objetivos
Este repositório foi criado como um **Caderno Temático Automatizado** focado no mercado de **Fundos Imobiliários (FIIs)**. O principal objetivo de estudo deste material é compreender as dinâmicas de funcionamento dos FIIs, analisar seus principais indicadores econômicos e estruturar estratégias voltadas para a geração de renda passiva e diversificação patrimonial.

Para enriquecer e fundamentar as análises, as informações foram consolidadas através de um agente de inteligência artificial criado no **NotebookLM**, utilizando uma curadoria rigorosa de fontes oficiais do setor financeiro.

---

## 📚 2. Curadoria de Fontes (Knowledge Base)
As fontes de dados abaixo foram selecionadas estrategicamente para alimentar a base de conhecimento do agente, cobrindo dados institucionais, relatórios de mercado, estatísticas de crescimento e conteúdos educacionais:

### 🌐 Fontes Oficiais e Artigos Técnicos
*   **B3 (Bolsa de Valores):** [Regulamentação e Produtos de FIIs](https://www.b3.com.br/pt_br/produtos-e-servicos/negociacao/renda-variavel/fundos-de-investimento-imobiliario-fii.htm) — Visão oficial do mercado regulado.
*   **Caixa Econômica Federal:** [FII Caixa Carteira Imobiliária](https://www.caixa.gov.br/fundos-investimento/imobiliarios/fii-caixa-carteira-imobiliaria/Paginas/default.aspx) — Análise de portfólio institucional.
*   **XP Investimentos:** [Relatórios e Análises de FIIs](https://conteudos.xpi.com.br/aprenda-a-investir/relatorios/fundos-imobiliarios/) — Estudos de mercado e análises macroeconômicas.
*   **Banco Safra:** [O Especialista: Guia de FIIs](https://oespecialista.safra.com.br/o-que-sao-fundos-imobiliarios/) — Conceituação e fundamentos de investimento.
*   **Mais Retorno:** [Índice IFIX](https://maisretorno.com/indice/ifix) — Acompanhamento do principal índice do mercado de FIIs.
*   **Investidor10:** [Rankings de FIIs](https://investidor10.com.br/fiis/rankings/) — Indicadores comparativos de performance.
*   **Blog Nubank:** [Entendendo os Fundos Imobiliários](https://blog.nubank.com.br/o-que-sao-fundos-imobiliarios/) & **Blog Santander:** [Tipos de FIIs do Mercado](https://www.santander.com.br/blog/tipos-de-fundos-imobiliarios-fiis) — Guias práticos de classificação e funcionamento.
*   **Fiis.com.br:** [Análise de Crescimento Histórico](https://fiis.com.br/noticias/fundos-imobiliarios-cresceram-mais-de-50-2025/) e [Carteiras Recomendadas](https://fiis.com.br/noticias/carteiras-fiis-veja-7-fundos-imobiliarios-mais-recomendados-para-junho-2026-jj/) — Dados estatísticos e recomendações periódicas.

### 🎥 Conteúdos em Vídeo e Multimídia
*   **Análises de Mercado:** [Research XP - Fundos Imobiliários](https://www.youtube.com/watch?v=MGLCcvKNUSI)
*   **Estratégias Práticas:** [Nubank - Como Viver de Renda com FIIs](https://www.youtube.com/watch?v=Vn2_rZ6OE4Q)
*   **Canais de Referência:** [Canal da Caixa](http://www.youtube.com/canalcaixa) | [XP Oficial](https://www.youtube.com/@XP_Oficial) | [Arena Trader](https://www.youtube.com/@ArenaTrader)
*   **Playlists Temáticas (XP Investimentos):**
    *   [Morning Call](https://www.youtube.com/playlist?list=PLMl5SicO7iPAblUrGoWYKJ1Gw7QDFkEZ8) | [Aprenda a Investir](https://www.youtube.com/playlist?list=PLMl5SicO7iPBJCO6neYAMHzD6A4N2obd8) | [Expert Drops](https://www.youtube.com/playlist?list=PLMl5SicO7iPBhT6GEhjbKzRjthuRJNooJ)
    *   [XP da Questão](https://www.youtube.com/playlist?list=PLMl5SicO7iPD7al7AA9avt38GakAzywlR) | [Expert Talks CEOs](https://www.youtube.com/playlist?list=PLMl5SicO7iPDNakKDzADxTzxIE6-neGz2) | [Expert Talks](https://www.youtube.com/playlist?list=PLMl5SicO7iPBskZKNtXB6H1Q6HNwmFSbP)
    *   [Carteira XP](https://www.youtube.com/playlist?list=PLMl5SicO7iPANIBcR15gMLZrldezx4ng8) | [Outliers](https://www.youtube.com/playlist?list=PLMl5SicO7iPAD17AwEQ3uJ00zUMBTsUAf)

---

## 🛠️ 3. Engenharia de Prompts e "Cicatrizes" (Troubleshooting)
Para extrair o melhor rendimento do modelo de IA a partir das fontes fornecidas, foi aplicado um processo iterativo de desenvolvimento de prompts.

### 🧠 Evolução dos Prompts
1.  **Prompt Inicial (Genérico):** *"Me explique o que é um FII baseado nos links."*
    *   *Resultado:* Resposta superficial que ignorava nuances importantes como a diferença entre fundos de tijolo e papel.
2.  **Prompt Refinado (Roleplay + Contexto):** *"Atue como um analista CNPI certificado. Com base nos relatórios de Research da XP e dados da B3 fornecidos, estruture uma análise comparativa de risco entre FIIs de Tijolo e FIIs de Papel."*
    *   *Resultado:* Resposta altamente técnica, referenciando diretamente os critérios das fontes.

### 🩹 Dificuldades Encontradas (Cicatrizes do Projeto)
*   **Alucinação de Indicadores:** O modelo inicialmente tentou inferir cotações em tempo real. **Solução:** O prompt foi ajustado para restringir as respostas estritamente aos dados históricos e conceitos presentes nos links informados.
*   **Processamento de Vídeos:** Transcrever e extrair pontos exatos de playlists longas do YouTube exigiu prompts focados em cronogramas (ex: *"Extraia as 3 principais teses de investimento citadas no vídeo da XP"*).

---

## 🏁 4. Miniguia de Estudo (Entrega Final)

### 📊 Resumos Estruturados
*   **O que são FIIs:** Reunião de investidores com o objetivo de aplicar recursos em empreendimentos imobiliários (sejam imóveis físicos ou títulos de crédito do setor).
*   **Geração de Valor:** O investidor recebe uma parcela dos aluguéis ou dos juros dos títulos proporcional à quantidade de cotas que possui, configurando uma excelente alternativa para construção de renda passiva mensal isenta de Imposto de Renda para pessoa física (sob as regras atuais).

### 📖 Glossário de Conceitos-Chave
*   **IFIX:** Índice que mede o desempenho médio dos fundos imobiliários negociados na B3.
*   **Dividend Yield (DY):** Indicador que mede o rendimento dos dividendos distribuídos por um fundo em relação ao preço atual de sua cota.
*   **P/VP (Preço sobre Valor Patrimonial):** Métrica utilizada para avaliar se um fundo está caro ou barato. Um P/VP abaixo de 1 pode indicar que o fundo está sendo negociado abaixo do valor real de seus ativos.
*   **Vacância:** Percentual do espaço físico dos imóveis do fundo que se encontra desocupado.

### 🔄 Prompts Reutilizáveis para Revisão
Sinta-se à vontade para utilizar os prompts abaixo no seu modelo de IA para revisar o conteúdo:
```text
"Com base no guia do Banco Safra e Santander, crie um questionário de 5 perguntas com respostas explicativas sobre como a taxa Selic afeta o rendimento dos FIIs de tijolo e de papel."
