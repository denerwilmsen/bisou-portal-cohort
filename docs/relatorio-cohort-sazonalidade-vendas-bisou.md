# Bisou Jalecos - Relatório de recompra e ritmo de vendas

Atualizado em 2026-06-08.

Versão em portal: http://127.0.0.1:8765/relatorio-cohort-sazonalidade-vendas-bisou.html

## 1. Resumo para apresentação

A Bisou tem volume de vendas e a promoção atual ajuda a gerar receita no curto prazo. O ponto de atenção é que poucas clientes voltam para comprar de novo. Isso muda a forma de avaliar campanhas: não basta olhar faturamento e ROAS; é necessário olhar margem, ticket médio, recompra e valor do cliente ao longo do tempo.

Em termos simples:

> A promoção compra a primeira venda. A pergunta agora é se ela está criando uma segunda venda com margem saudável.

## 2. O que foi analisado

Foram usadas duas bases da Nuvemshop:

1. **Análise de cohort e recompra**
   - Fonte: API da Nuvemshop.
   - Período: 2024-11-07 a 2026-06-05.
   - Pedidos brutos coletados: 7.299.
   - Pedidos considerados após filtros: 6.475.
   - Clientes analisadas: 6.086.
   - Receita analisada: R$ 3.811.182,46.

2. **Análise de ritmo de vendas por dia e horário**
   - Fonte: relatório consolidado da Nuvemshop.
   - Período: 2025-01-01 a 2026-06-03.
   - Pedidos pagos considerados: 6.127.
   - Receita analisada: R$ 3.637.897,76.
   - Ticket médio: R$ 593,75.

Os pedidos cancelados, reembolsados ou inválidos foram removidos da leitura principal para evitar que a análise superestime venda real.

## 3. O que é cohort, sem complicar

Cohort é uma forma de agrupar clientes pelo mês da primeira compra e observar se elas voltam a comprar depois.

Exemplo:

- clientes que compraram pela primeira vez em janeiro formam a cohort de janeiro;
- depois, analisamos quantas dessas clientes compraram novamente em fevereiro, março, abril e assim por diante;
- isso mostra se a marca está apenas adquirindo novas clientes ou se está construindo recorrência.

Essa leitura é importante porque um e-commerce pode parecer saudável quando vende muito na primeira compra, mas ainda assim ter dificuldade de lucro se precisar pagar por uma nova cliente o tempo todo.

## 4. Resultado principal da cohort

| Indicador | Resultado |
|---|---:|
| Pedidos analisados | 6.475 |
| Clientes analisadas | 6.086 |
| Clientes que recompraram | 329 |
| Taxa de recompra por cliente | 5,41% |
| Pedidos de recompra | 389 |
| Participação da recompra nos pedidos | 6,01% |
| Receita de recompra | R$ 230.971,85 |
| Participação da recompra na receita | 6,06% |

## 5. Leitura de negócio

A recompra de 5,41% mostra que a Bisou ainda depende muito da primeira venda. Isso não significa que a marca vende mal. Pelo contrário: ela vende. O problema é outro.

O risco é usar uma promoção agressiva como principal motor de crescimento sem confirmar se essa promoção:

- preserva margem suficiente;
- atrai clientes que compram novamente;
- aumenta ticket médio de forma sustentável;
- fortalece a percepção premium da marca;
- cria uma base própria de relacionamento, e não apenas novas compras dependentes de mídia.

Com margem de contribuição base de 35%, a leitura operacional é que o **Compre 2 Pague 1** pode derrubar a margem para perto de 17,5%. Se a cliente não recompra depois, a primeira venda fica mais pesada para o caixa.

Por isso, o problema não é "a promoção funciona ou não funciona". Ela funciona para gerar venda imediata. A pergunta correta é:

> Essa promoção está gerando clientes lucrativas ou apenas aumentando faturamento bruto com margem menor?

## 6. O que os meses mostram

As cohorts antigas tiveram mais tempo para recomprar e, por isso, tendem a apresentar percentuais maiores. Mesmo assim, as cohorts de maior volume mostram que a escala não veio acompanhada de recompra proporcional.

| Cohort | Clientes | Taxa de recompra | Leitura |
|---|---:|---:|---|
| 2025-11 | 686 | 3,50% | Muito volume, baixa recompra proporcional |
| 2025-12 | 663 | 4,98% | Muito volume, recompra ainda baixa |
| 2026-01 | 509 | 2,36% | Volume alto, pouca segunda compra até agora |
| 2026-02 | 504 | 1,98% | Mesmo padrão: aquisição maior que retenção |

Isso sugere que a máquina de aquisição está funcionando melhor do que a máquina de relacionamento.

## 7. Dias da semana com mais vendas

Na leitura por dia da semana, quarta-feira aparece como o melhor dia em volume e receita média diária. Terça e sexta também são fortes. Domingo é o dia mais fraco, mas ainda representa volume relevante.

| Dia da semana | Pedidos | Receita | Receita média por dia | Ticket médio | Share da receita |
|---|---:|---:|---:|---:|---:|
| Quarta-feira | 974 | R$ 570.176,29 | R$ 7.919,12 | R$ 585,40 | 15,67% |
| Sexta-feira | 934 | R$ 544.512,61 | R$ 7.669,19 | R$ 582,99 | 14,97% |
| Terça-feira | 934 | R$ 552.786,55 | R$ 7.572,42 | R$ 591,85 | 15,20% |
| Quinta-feira | 863 | R$ 516.127,62 | R$ 7.168,44 | R$ 598,06 | 14,19% |
| Segunda-feira | 828 | R$ 501.929,07 | R$ 6.971,24 | R$ 606,19 | 13,80% |
| Sábado | 826 | R$ 491.656,56 | R$ 6.924,74 | R$ 595,23 | 13,51% |
| Domingo | 768 | R$ 460.709,06 | R$ 6.488,86 | R$ 599,88 | 12,66% |

### Leitura

O melhor uso dessa informação não é simplesmente "ligar campanha na quarta". A decisão mais inteligente é usar a sazonalidade para organizar intensidade de mídia, remarketing, disparos de CRM e comunicação de oferta.

Recomendação prática:

- concentrar lançamentos, reforço de oferta e criativos de conversão entre terça e sexta;
- usar segunda para aquecimento e recuperação de carrinho;
- usar domingo com estratégia mais leve, voltada a remarketing, conteúdo e preparação para a semana.

## 8. Horários de pico de vendas

Os horários com maior volume aparecem em dois blocos principais:

- manhã comercial, especialmente 09h a 11h;
- noite, especialmente 20h a 22h.

| Horário | Pedidos | Receita | Ticket médio | Share da receita |
|---|---:|---:|---:|---:|
| 10h | 420 | R$ 248.561,49 | R$ 591,81 | 6,83% |
| 21h | 396 | R$ 237.314,99 | R$ 599,28 | 6,52% |
| 22h | 392 | R$ 235.748,66 | R$ 601,40 | 6,48% |
| 09h | 384 | R$ 224.480,88 | R$ 584,59 | 6,17% |
| 11h | 368 | R$ 221.113,69 | R$ 600,85 | 6,08% |
| 20h | 351 | R$ 208.782,28 | R$ 594,82 | 5,74% |
| 08h | 350 | R$ 205.288,12 | R$ 586,54 | 5,64% |
| 12h | 348 | R$ 203.263,47 | R$ 584,09 | 5,59% |
| 17h | 347 | R$ 204.519,75 | R$ 589,39 | 5,62% |
| 14h | 341 | R$ 200.935,83 | R$ 589,25 | 5,52% |

## 9. Períodos do dia

| Período | Pedidos | Receita | Ticket médio | Share da receita |
|---|---:|---:|---:|---:|
| Manhã | 1.840 | R$ 1.089.163,12 | R$ 591,94 | 29,94% |
| Tarde | 2.026 | R$ 1.204.460,51 | R$ 594,50 | 33,11% |
| Noite | 2.035 | R$ 1.208.792,02 | R$ 594,00 | 33,23% |
| Madrugada | 226 | R$ 135.482,11 | R$ 599,48 | 3,72% |

### Leitura

Tarde e noite concentram mais receita, mas a manhã também é forte. O ticket médio varia pouco entre os períodos. Isso indica que a principal diferença não está no valor do pedido, e sim no volume de decisões de compra.

Em outras palavras:

> O horário muda mais a quantidade de compras do que o valor médio de cada compra.

## 10. Implicações para mídia e CRM

### Mídia paga

As campanhas não devem ser avaliadas apenas por ROAS. O ideal é cruzar:

- receita imediata;
- margem da oferta;
- ticket médio;
- taxa de recompra;
- recompra em 30, 60 e 90 dias;
- CAC payback por oferta.

Para distribuição de verba, usar os horários fortes como janelas de maior pressão comercial:

- 09h a 11h;
- 14h a 17h;
- 20h a 22h.

Horários mais fracos podem receber campanhas de remarketing, visualização, prova de produto e aquecimento, sem necessariamente carregar a maior parte do investimento de conversão.

### CRM

Como a recompra é baixa, o CRM precisa deixar de ser apenas comunicação e virar uma máquina de segunda compra.

Fluxo mínimo recomendado:

| Janela | Objetivo | Exemplo de abordagem |
|---|---|---|
| Pós-entrega D+3 | Confirmar experiência | Verificar se a peça chegou bem e reforçar caimento/acabamento |
| D+12 | Coletar review | Pedir avaliação e foto real |
| D+30 | Segunda peça complementar | Indicar modelo que combina com a primeira compra |
| D+45 | Kit de rotina | Sugerir combinações para semana profissional |
| D+90 | Reativação | Apresentar nova cor, modelo ou coleção |

## 11. Recomendação de próximo teste

A recomendação não é remover toda promoção de uma vez. O caminho mais seguro é testar uma mecânica que preserve melhor margem e aumente ticket:

> Monte seu kit profissional Bisou: escolha 3 peças e pague 2 em modelos selecionados.

Esse teste deve comparar contra o Compre 2 Pague 1 olhando:

- conversão;
- ticket médio;
- margem por pedido;
- receita por cliente;
- recompra em 30/60/90 dias;
- troca/devolução;
- impacto na percepção premium.

## 12. Decisão executiva

A Bisou não tem apenas um problema de campanha. Ela tem uma oportunidade de transformar venda promocional em relacionamento recorrente.

O plano recomendado e:

1. Manter a promoção atual como controle de comparação, não como única identidade comercial.
2. Testar oferta de kit com menor destruição de margem.
3. Reforçar criativos e loja com prova de produto antes do desconto.
4. Ativar CRM de segunda compra por janela.
5. Programar mídia e CRM nos dias e horários de maior intenção de compra.
6. Medir campanhas por margem e recompra, não apenas por receita imediata.

## 13. Arquivos de origem

- `relatorios/nuvemshop-cohort-retention.json`
- `relatorios/nuvemshop-cohort-retention.csv`
- `relatorios/dados-relatorio-2025-2026.json`
- `docs/cohort-retention-nuvemshop.md`
