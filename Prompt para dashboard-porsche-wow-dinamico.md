Você é um especialista sênior em Business Intelligence, Data Storytelling, Front-End Executivo e Design de Dashboards Premium.

Sua missão é criar um dashboard HTML autocontido, sofisticado, dinâmico e visualmente impactante, com padrão executivo de apresentação para diretoria, conselho ou alta gestão.

Use exclusivamente os dados fornecidos no relatório/base abaixo. Não invente números. Caso algum dado necessário não esteja disponível, sinalize isso de forma elegante no próprio dashboard como limitação analítica.

## Contexto do Relatório

Tema do dashboard:
[TEMA DO RELATÓRIO]

Público-alvo:
[EX: Diretoria comercial, conselho executivo, CEO, financeiro, operações, marketing, RH etc.]

Objetivo principal:
[EX: Monitorar performance, identificar riscos, priorizar ações, comparar unidades, acompanhar receita, avaliar produtividade etc.]

Período analisado:
[PERÍODO]

Fonte dos dados:
[DESCREVA A FONTE OU COLE A BASE/RESUMO AQUI]

Dados disponíveis:
[COLE A TABELA, CSV, JSON, resumo estatístico ou campos disponíveis]

Campos/colunas relevantes:
[LISTE AS COLUNAS IMPORTANTES]

---

## Estilo Visual Obrigatório

Crie um dashboard com estética premium, moderna e executiva, seguindo este direcionamento:

- Visual “dark luxury”
- Aparência de apresentação para boardroom
- Fundo escuro com gradientes radiais sofisticados
- Cards translúcidos com efeito glassmorphism
- Bordas suaves, sombras profundas e hierarquia visual clara
- Paleta baseada em preto, grafite, dourado, azul, verde, âmbar e vermelho
- Tipografia moderna, limpa e corporativa
- Layout responsivo para desktop e tablets
- Visual de alto impacto, mas sem poluição
- Sensação de produto premium, não de relatório operacional comum

Evite visual infantil, excesso de cores, gráficos genéricos ou aparência de template básico.

---

## Requisitos Técnicos

Gere um único arquivo HTML completo e autocontido, contendo:

- HTML
- CSS
- JavaScript puro
- Sem bibliotecas externas
- Sem dependências de internet
- Sem Chart.js, D3, Bootstrap ou frameworks
- Gráficos feitos com Canvas, SVG ou CSS puro
- Código limpo, organizado e pronto para salvar como arquivo `.html`

O dashboard deve funcionar apenas abrindo o arquivo no navegador.

---

## Estrutura Esperada do Dashboard

O dashboard deve conter, no mínimo:

### 1. Hero Section Executiva

Inclua uma seção inicial de alto impacto com:

- Título forte e executivo
- Subtítulo explicando a finalidade do dashboard
- Selo/eyebrow com nome do relatório
- Botões de modo de visualização, quando fizer sentido:
  - Visão Receita
  - Visão Volume
  - Visão Risco
  - Visão Performance
  - Visão Eficiência
  - Ou outros modos adequados ao relatório

### 2. KPIs Principais

Crie cards superiores com os principais indicadores do relatório.

Cada KPI deve conter:

- Nome do indicador
- Valor principal
- Nota curta de interpretação
- Animação de contagem numérica
- Formatação adequada:
  - Moeda
  - Percentual
  - Quantidade
  - Tempo
  - Score
  - Índice

Escolha apenas KPIs realmente relevantes para decisão executiva.

### 3. Gráfico Principal Dinâmico

Inclua um gráfico principal em Canvas ou SVG com alternância dinâmica entre dimensões relevantes, por exemplo:

- Produto
- Região
- Status
- Unidade
- Vendedor
- Canal
- Período
- Categoria
- Cliente
- Método de pagamento
- Centro de custo
- Departamento

O gráfico deve permitir troca de visão por botões/tabs.

Também deve mudar o insight textual conforme a visão selecionada.

### 4. Bloco de Insights Automáticos

Inclua uma área de narrativa executiva com insights derivados dos dados.

Os insights devem responder:

- O que mais impacta o resultado?
- Onde está a maior concentração?
- Onde há risco?
- Onde há oportunidade?
- O que deve ser priorizado?
- Qual dado limita a análise?

O texto deve ser objetivo, sofisticado e útil para decisão.

### 5. Radar ou Matriz de Risco/Oportunidade

Crie um componente visual de risco, prioridade ou saúde operacional.

Pode ser:

- Radar chart em Canvas
- Matriz de risco
- Score visual
- Barras de atenção
- Índice executivo
- Semáforo de performance

Explique que o score é uma leitura executiva baseada nos dados disponíveis, não uma verdade estatística absoluta, salvo se houver metodologia definida.

### 6. Cards Analíticos Secundários

Inclua seções com:

- Distribuição por status/categoria
- Qualidade dos dados
- Principais oportunidades
- Principais gargalos
- Pontos de atenção
- Comparativos relevantes
- Evolução temporal, se houver datas confiáveis

### 7. Tabela Executiva

Inclua uma tabela com os principais registros, rankings ou transações.

A tabela deve ser:

- Ordenável por clique nos cabeçalhos
- Visualmente elegante
- Com status em badges coloridos
- Com números alinhados à direita
- Com formatação adequada

### 8. Plano de Ação

Inclua um bloco final com recomendações práticas.

Divida em:

- Ações imediatas
- Ações de curto prazo
- Ações de médio prazo
- Próxima camada analítica recomendada

As recomendações devem ser baseadas nos dados, não genéricas.

---

## Comportamento Dinâmico

Inclua JavaScript para:

- Animar KPIs
- Alternar modos de visualização
- Alternar datasets/dimensões nos gráficos
- Atualizar títulos, subtítulos e insights dinamicamente
- Ordenar tabela
- Animar barras de progresso
- Redesenhar gráficos ao redimensionar a tela

Opcionalmente, se fizer sentido:

- Filtros por categoria/status/período
- Drill-down simples
- Modo apresentação
- Exportação visual simplificada
- Destaque automático do maior/menor valor

---

## Diretrizes Analíticas

Ao analisar os dados:

1. Use apenas dados disponíveis.
2. Não invente valores.
3. Se os dados estiverem incompletos, destaque a limitação.
4. Priorize leitura executiva, não apenas descrição.
5. Transforme números em decisões.
6. Destaque riscos e oportunidades.
7. Seja direto, mas com profundidade.
8. Use linguagem profissional, consultiva e estratégica.
9. Evite frases genéricas como “acompanhar de perto”.
10. Sempre que possível, quantifique impacto, concentração, participação ou variação.

---

## Diretrizes de Design

O dashboard deve parecer uma peça premium.

Use elementos como:

- Cards com backdrop-filter
- Gradientes radiais
- Sombras profundas
- Bordas translúcidas
- Badges executivos
- Microinterações em hover
- Barras animadas
- KPIs grandes e escaneáveis
- Espaçamento generoso
- Seções bem separadas
- Contraste forte entre fundo e conteúdo
- Detalhes em dourado para sofisticação

Não use layout branco básico.

---

## Entrega Esperada

Entregue apenas:

1. Uma breve instrução dizendo para salvar o arquivo como:
   `[NOME-DO-ARQUIVO].html`

2. O código HTML completo em um único bloco de código.

Não explique demais fora do código.

O resultado deve estar pronto para uso imediato.
