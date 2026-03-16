Estratégia de Crescimento de Receita do Hotel: Análise Estratégica & Recomendações

📊 Visão Geral

Este repositório contém uma análise estratégica completa de um case de negócios real, focado em aumentar a receita anual de um hotel em 20%, saindo de R$ 11,6M para R$ 13,9M. A análise foi conduzida através de metodologia robusta de ciência de dados, combinando análise exploratória (EDA), modelagem de cenários e recomendações estratégicas baseadas em dados.

🎯 Objetivo Principal

Identificar alavancas de crescimento de receita através da análise de 119.390 reservas históricas, estruturando recomendações em torno de três pilares estratégicos:

•
Preço (ADR - Average Daily Rate)

•
Volume (Ocupação)

•
Mix de Clientes




📈 Resultados Principais

Métrica
Valor
Receita Atual
R$ 11,6M
Receita Alvo
R$ 13,9M
Meta de Crescimento
+20%
Rota Conservadora
+5,65% (~R$ 655 mil)
Rota Otimista
+13,14% (~R$ 1,52M)
Taxa de Cancelamento
27,8% (principal vazamento)
Clientes Recorrentes
4,4% (oportunidade de fidelização)







🔍 Insights Principais

1. Vazamento de Receita por Cancelamentos

•
Grupos (42,4%) e Agências de Turismo Online (35,2%) apresentam as maiores taxas de cancelamento

•
Representam ~R$ 4,5M em receita perdida anualmente

•
Impacto Potencial: Reduzir cancelamentos em 15% recuperaria ~R$ 700 mil

2. Risco de Sazonalidade

•
Julho e Agosto representam R$ 5,3M (45%) da receita anual

•
Dependência excessiva da alta temporada cria vulnerabilidade

•
Oportunidade: Estratégias de precificação dinâmica podem aumentar receita em 5% nos meses de baixa temporada

3. Dependência de Canais Online

•
Canais online (AT Online + AT Offline) dominam com R$ 8,05M (69%) da receita

•
Oferecem margens menores e risco operacional mais elevado

•
Estratégia: Aumentar reservas diretas em 10% adicionaria R$ 244 mil com margens 20% superiores

4. Lacuna de Fidelização

•
Apenas 4,4% dos clientes são recorrentes

•
Indica custos de aquisição ineficientes (CAC) e potencial não explorado de valor ao longo da vida (LTV)

•
Potencial: Aumentar recorrência para 8% geraria R$ 580 mil em receita adicional




📊 Metodologia de Análise

Estrutura Analítica

A análise foi estruturada em torno de uma árvore de hipóteses com três pilares estratégicos:

Crescimento de Receita (Meta: +20%)

1. Preço (ADR)

•
Revenue Management Dinâmico

•
Otimização de Precificação por Segmento

•
Estratégias de Sazonalidade

2. Volume (Ocupação)

•
Redução de Cancelamentos

•
Aumento de Lead Time

•
Expansão de Capacidade

3. Mix de Clientes

•
Fidelização de Clientes

•
Fortalecimento do Canal Direto

•
Segmentação de Mercado

Ferramentas e Tecnologias

•
Linguagem: Python 3.11

•
Bibliotecas Principais:

•
Pandas - Manipulação e análise de dados

•
NumPy - Computação numérica

•
Matplotlib & Seaborn - Visualização de dados

•
Scikit-learn - Modelagem estatística



•
Ambiente: Jupyter Notebook

Dados Utilizados

•
Base de Dados: 119.390 reservas históricas

•
Período Analisado: 12 meses (2024-2025)

•
Confiabilidade: 99%

•
Segmentação: Por canal, segmento de mercado, sazonalidade e lead time

Etapas da Análise

1.
Limpeza e Preparação de Dados

•
Remoção de outliers

•
Tratamento de valores ausentes

•
Normalização de variáveis



2.
Análise Exploratória de Dados (EDA)

•
Distribuição de receita por segmento

•
Análise de sazonalidade

•
Padrões de cancelamento

•
Comportamento de lead time



3.
Segmentação de Clientes

•
Análise por canal de reserva

•
Análise por segmento de mercado

•
Identificação de padrões de comportamento



4.
Modelagem de Cenários

•
Cenário Conservador: Premissas mais realistas e viáveis

•
Cenário Otimista: Premissas agressivas com potencial máximo



5.
Recomendações Estratégicas

•
Priorização por Impacto vs. Esforço

•
Plano de Implementação de 120 dias

•
Métricas de Sucesso e KPIs






🎯 Recomendações Estratégicas

Rota Recomendada: Otimista (+13,14%)

Embora não atinja os 20% sozinha, a Rota Otimista posiciona o hotel no caminho certo com um crescimento realista de +13,14% (R$ 1,52M).

Ações Prioritárias (120 Dias)

Fase 1: Quick Wins (Dias 1-30)

1.
Revisão de Políticas de Cancelamento

•
Impacto: ~R$ 700 mil

•
Esforço: Baixo

•
Ação: Implementar políticas mais rigorosas para Grupos e AT Online



2.
Otimização de Revenue Management

•
Impacto: ~R$ 580 mil

•
Esforço: Médio

•
Ação: Implementar precificação dinâmica por segmento



Fase 2: Estratégico (Dias 31-90)

1.
Fortalecimento do Canal Direto

•
Impacto: ~R$ 244 mil

•
Esforço: Médio

•
Ação: Investir em marketing direto e programa de fidelidade



2.
Programa de Fidelização

•
Impacto: ~R$ 580 mil

•
Esforço: Alto

•
Ação: Criar programa de pontos e benefícios para clientes recorrentes



Fase 3: Consolidação (Dias 91-120)

1.
Análise de Lead Time

•
Impacto: Variável

•
Esforço: Baixo

•
Ação: Ajustar políticas de antecedência de reserva


🚀 Como Usar Este Repositório

Pré-requisitos

•
Python 3.8+

•
Jupyter Notebook

•
Bibliotecas: pandas, numpy, matplotlib, seaborn, scikit-learn

Instalação

Bash


# Clone o repositório
git clone https://github.com/Sam-Batisti/-Hotel-case-analysis.git
cd -Hotel-case-analysis

# Instale as dependências
pip install -r requirements.txt

# Abra o Jupyter Notebook
jupyter notebook Case_hotel_Insider.ipynb



Executando a Análise

1.
Abra o arquivo Case_hotel_Insider.ipynb no Jupyter Notebook

2.
Execute as células sequencialmente para reproduzir a análise

3.
Visualize os gráficos e insights gerados

4.
Modifique os parâmetros conforme necessário para explorar cenários alternativos




📊 Visualizações Principais

O notebook inclui as seguintes visualizações:

•
Receita por Segmento: Distribuição de receita entre canais e segmentos

•
Sazonalidade: Padrão de receita ao longo dos meses

•
Taxa de Cancelamento: Análise por segmento e canal

•
Lead Time vs. Cancelamento: Correlação entre antecedência e cancelamento

•
Cenários de Impacto: Comparação visual dos cenários conservador e otimista




📈 Métricas de Sucesso

Para validar a implementação das recomendações, monitore:

KPI
Baseline
Alvo (Rota Otimista )
Frequência
Receita Total
R$ 11,6M
R$ 13,1M
Mensal
Taxa de Cancelamento
27,8%
23,6%
Semanal
ADR Médio
R$ 450
R$ 473
Mensal
Taxa de Ocupação
65%
68%
Diária
Clientes Recorrentes
4,4%
6,5%
Mensal
Receita do Canal Direto
R$ 3,55M
R$ 3,79M
Mensal







🔗 Recursos Adicionais

•
Site Interativo: Estratégia de Crescimento de Receita - Apresentação visual da análise

•
Dashboard Power BI: Receita - insider - Visualizações interativas em tempo real




👤 Autor

Samantha Batisti

•
GitHub: @Sam-Batisti

•
LinkedIn: Samantha Batisti




📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.




🤝 Contribuições

Sugestões e melhorias são bem-vindas! Sinta-se livre para:

•
Abrir issues com dúvidas ou sugestões

•
Fazer fork e enviar pull requests

•
Compartilhar insights adicionais




📧 Contato

Para dúvidas sobre a análise ou metodologia, entre em contato através de:

•
Email: samantha.pbatisti@gmail.com

•
GitHub Issues: Abrir uma issue




Última Atualização: Março de 2026




📚 Referências

•
Análise de Receita Hoteleira: Melhores Práticas em Revenue Management

•
Técnicas de Segmentação de Clientes em Hospitality

•
Modelos Preditivos para Cancelamento de Reservas

•
Estratégias de Precificação Dinâmica em Hotelaria




Nota: Este é um case de negócios real utilizado para fins de análise estratégica e demonstração de habilidades em ciência de dados, análise de negócios e tomada de decisão baseada em dados.


