# Análise de Sucesso do Cliente
* <a href="https://app.powerbi.com/view?r=eyJrIjoiMzEzZmI1MzYtY2Q4NC00ODA5LWI2MjEtYWU5ZjdlMWI0ZjE4IiwidCI6IjZlNTRiMDEwLWRhOGItNDQzYi04OTQ4LTc1NDA3MGNhYTg3MSJ9">Acesse o dashboard interativo aqui</a>

## Visão geral

Este projeto foi desenvolvido como parte de um desafio técnico para uma vaga de <strong>Estágio em Sucesso do Cliente</strong>. 
<br/>
O objetivo principal foi analisar os dados operacionais da área, gerar insights estratégicos e propor melhorias por meio da visualização de informações e automação de processos.
<br/>

### Metodologias utilizadas:
* <strong>Power BI</strong>: Construção de um dashboard interativo e dinâmico, com foco em clareza visual e análise de desempenho.
* <strong>DAX</strong>: Criação de medidas e KPIs, incluindo tempo médio de atendimento, taxa de resolução, volume por responsável, sazonalidade, entre outros.
* <strong>Power Query</strong>: Realização do processo de ETL (extração, transformação e carregamento de dados), incluindo limpeza, junção e padronização de tabelas.
* <strong>Análise exploratória</strong>: Identificação de padrões, outliers e oportunidades de melhoria nos dados operacionais.

<br/>

## Análise de Performance do Time
<br/>
<img src='https://github.com/thiago-albuquerque/analiseSucessoDoCliente/blob/main/Power%20BI/images/performance_time_img.JPG'/>
<br/>

### Insights:
* O dashboard mostra um desempenho desigual entre responsáveis: Há um desequilíbrio significativo na performance dos responsáveis. Enquanto Ana concluiu 92% das suas tarefas, outros membros como Pedro (55%) e Rafael (57%) apresentam índices muito abaixo da média. Isso pode indicar necessidade de redistribuição de carga ou acompanhamento mais próximo desses profissionais.

* Ana é a mais produtiva, mas sofre com atrasos: Com 323 tarefas, 66% delas foram entregues após o prazo. Isso mostra que apesar de eficaz, há dificuldade de priorização ou carga excessiva.

* Alta Taxa de Conclusão em Atividades Prioritárias: Apesar dos desafios, a equipe mostra um bom desempenho em relação às tarefas de maior prioridade: 85% das atividades de prioridade Alta foram concluídas — um número superior ao das de prioridade Média e Baixa. Isso demonstra uma boa capacidade de foco nas demandas críticas, o que pode ser reforçado como prática positiva.

<br/>

## Análise de Relacionamento com o Cliente
<br/>
<img src='https://github.com/thiago-albuquerque/analiseSucessoDoCliente/blob/main/Power%20BI/images/relacionamento_cliente_img.JPG'/>
<br/>

### Insights:
* Nesse trecho do dashboard, é mostrado que a Adoção e Onboarding estão com pouca atenção: Somente 8% das interações estão no Onboarding e 32% na fase de adoção, enquanto 60% já estão em acompanhamento. Isso pode indicar que muitos clientes estão sendo acompanhados sem passar adequadamente pelas etapas anteriores, o que prejudica a maturidade no uso da solução.

* Contatos ativos trazem melhores resultados: Reuniões com clientes (93%) e internas (89%) têm as maiores taxas de conclusão, mostrando que interações diretas e planejadas trazem melhores entregas.

* Atendimento equilibrado entre faixas de receita: A empresa está distribuindo bem o esforço entre clientes de diferentes faixas de receita, com pequeno destaque para os clientes entre R$ 5.000 e R$ 10.000. Isso mostra que a equipe está mantendo um bom senso de equidade.

<br/>

## Conclusão
<br/>
<img src='https://github.com/thiago-albuquerque/analiseSucessoDoCliente/blob/main/Power%20BI/images/dash_overview_img.JPG'/>
<br/>

A análise mostrou que o time tem bons resultados em tarefas prioritárias e mantém um atendimento equilibrado entre clientes de diferentes faixas de receita. No entanto, também foram identificados pontos de atenção: diferenças de desempenho entre os responsáveis, alto índice de atrasos e baixa atenção às fases iniciais da jornada do cliente, como o Onboarding.
<br/><br/>
Para ajudar a melhorar esse cenário, foi proposto um fluxo de automação simples e direto. Ele alerta o responsável quando a atividade estiver perto do vencimento e ainda não tiver sido finalizada, além de criar uma tarefa de follow-up automática.
<br/>
Essa iniciativa busca evitar atrasos, garantir um acompanhamento mais próximo dos clientes e tornar a rotina da equipe mais organizada e eficiente.
