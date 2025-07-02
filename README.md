
# Análise de Teste A/B com Cupons — Case Técnico iFood

Este projeto tem como objetivo analisar o impacto financeiro e comportamental de uma campanha promocional com cupons utilizando um teste A/B. 

## Abordagem

A campanha consistiu em oferecer cupons a um grupo de usuários (grupo **Target**), enquanto o grupo de controle (**Control**) não recebeu o benefício. Avaliamos o comportamento dos usuários, analisamos a significância estatística dos resultados e simulamos diferentes cenários de segmentação para encontrar a estratégia mais eficiente.

---

## Estrutura dos Notebooks

1. **Notebook 1 — 1_data_preparation**
   - Carregamento e tratamento das bases: `order`, `ab_test`, `consumer`, `restaurants`.
   - Agregação dos dados de pedidos por usuário.
   - Cálculo de métricas: número de pedidos, gasto total, ticket médio.
   - Junção das bases e construção da base final.

2. **Notebook 2 — 2_analysis**
   - Comparação entre grupos (target vs control).
   - Testes T para gasto total e número de pedidos.
   - Teste Z para proporção de conversão.
   - Cálculo de ROI e impacto financeiro da campanha.
  
3. **Notebook 3 — 3_financial_viability**
   - Cálculo de ROI e impacto financeiro da campanha.
  
4. **Notebook 4 — 4_user_segmentation**
   - Segmentação de usuários por:
     - Atividade (ativo/inativo)
     - Frequência (1 pedido/recorrente)
     - Gasto total (baixo, médio, alto — usando quantis)
   - Testes estatísticos por segmento.
   - Avaliação do ROI e lucro por cenário.
   - Simulação com diferentes valores de cupom (R$5, R$10, R$15).

---
