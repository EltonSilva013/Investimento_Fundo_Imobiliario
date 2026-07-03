# 🏢 Estudo e Análise de Fundos Imobiliários (FIIs) com Inteligência Artificial

## 📝 1. Contexto e Objetivos
Este repositório foi criado como um **Caderno Temático Automatizado** voltado ao mercado de **Fundos Imobiliários (FIIs)**, servindo como documentação para o Desafio de Projeto da DIO. 

O principal objetivo deste material é aplicar técnicas de aprendizagem ativa com Inteligência Artificial para compreender as dinâmicas dos FIIs, analisar seus principais indicadores econômicos (como dividendos e valuation) e estruturar estratégias de estudo voltadas para a geração de renda passiva e diversificação patrimonial.

---

## 📚 2. Curadoria de Fontes (Knowledge Base)
As fontes abaixo foram selecionadas estrategicamente para alimentar a base de conhecimento do agente no **NotebookLM**, cobrindo dados institucionais, relatórios analíticos de mercado e estatísticas de crescimento:

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
Para demonstrar o raciocínio por trás dos resultados obtidos no NotebookLM, abaixo está mapeada a evolução da engenharia de prompts utilizada.

### 🧠 Variações de Prompts e Respostas Obtidas

*   **Tentativa 1 (Prompt Genérico):**
    *   *Prompt:* `"Me explique o que é um FII baseado nos links."`
    *   *Resposta obtidas:* Resposta muito conceitual e simples, ignorando a segmentação do mercado.
    *   *Crítica:* Não trouxe a profundidade necessária para um caderno técnico de estudos.

*   **Tentativa 2 (Prompt Direcionado - Roleplay + Contexto):**
    *   *Prompt:* `"Atue como um analista CNPI qualificado. Com base nos documentos fornecidos do Banco Safra, Santander e B3, elabore uma análise de risco comparativa detalhando a diferença de comportamento entre FIIs de Tijolo e FIIs de Papel em cenários de queda de juros."`
    *   *Resposta obtida:* O modelo segmentou com precisão os riscos. Explicou que os FIIs de Tijolo tendem a se valorizar com a queda de juros devido ao menor custo de financiamento imobiliário e valorização patrimonial, enquanto FIIs de Papel indexados ao CDI podem ver seus rendimentos nominais diminuírem.
    *   *Referências citadas pela IA:* Guia do Banco Safra (Fundamentos), Blog Santander (Tipos de Fundos) e Regulamentos da B3.

### 🩹 Dificuldades Encontradas (Cicatrizes e Soluções)
*   **Alucinação de Cotações em Tempo Real:** Sendo uma base estática do NotebookLM, a IA tentou inferir valores atuais do mercado. **Solução:** Adicionado comando restritivo ao prompt: *"Ignore oscilações diárias de mercado e foque estritamente no comportamento histórico e metodologias documentadas nas fontes"*.
*   **Extração de Conteúdo de Vídeo:** Ao analisar as playlists da XP Investimentos, o modelo se perdeu no volume de dados. **Solução (Troubleshooting):** Delimitei o escopo solicitando que o modelo buscasse apenas as ideias centrais presentes nos títulos de vídeos específicos de *Research*.

---

## 🏁 4. Miniguia de Estudo (Entrega Final)

### 📊 Resumos Estruturados
*   **Mecanismo dos FIIs:** Os Fundos Imobiliários funcionam como condomínios de investidores que juntam capital para investir em grandes empreendimentos (shoppings, galpões logísticos, lajes corporativas ou títulos de crédito como CRI e LCI). 
*   **Distribuição de Dividendos:** Por lei brasileira, os FIIs são obrigados a distribuir pelo menos 95% do lucro líquido apurado em regime de caixa a cada semestre, sendo comumente pago de forma mensal, o que atrai investidores focados em renda passiva recorrente.

### 📖 Glossário de Conceitos-Chave
*   **IFIX:** Índice de Fundos de Investimentos Imobiliários. É o indicador do desempenho médio das cotações dos FIIs negociados nos mercados de bolsa da B3.
*   **Dividend Yield (DY):** Relação entre os dividendos pagos por uma cota e o preço atual dessa cota (geralmente expresso em formato anual ou mensal).
*   **P/VP (Preço sobre Valor Patrimonial):** Indicador de avaliação de preço. Indica quantas vezes o valor de mercado representa o valor real dos imóveis e caixa do fundo.
*   **Vacância Física:** Percentual da área total dos imóveis do fundo que está atualmente desocupada.

### 🔄 Prompts Reutilizáveis para Revisão
Utilize os modelos abaixo para realizar revisões futuras no NotebookLM:

```text
"Com base no guia do Banco Safra e Santander, crie um questionário de 5 perguntas com respostas explicativas sobre como a taxa Selic afeta o rendimento dos FIIs de tijolo e de papel."
