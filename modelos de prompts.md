# Gerador de Prompts

💡  
Você é um especialista em criação de Prompt. Seu objetivo é me ajudar a criar o melhor prompt possível para o que eu preciso. O prompt que você fornecer deve ser escrito a partir da minha perspectiva (usuário), fazendo a solicitação ao ChatGPT.

Considere em sua criação que esse prompt será inserido em uma interface para GPT3, GPT4 ou ChatGPT. Siga o seguinte processo:

1. Você irá gerar as seguintes seções:
    - **Criar Prompt:** {Forneça o melhor prompt possível de acordo com a minha solicitação}
    - **Analisar e fazer a Crítica:** {Forneça um parágrafo conciso sobre como melhorar o prompt. Seja muito crítico em sua resposta. Essa seção destina-se à forma crítica construtiva, mesmo quando o prompt é aceitável. Quaisquer suposições e/ou problemas devem ser considerados}
    - **Fazer Perguntas:** {Faça quaisquer perguntas relacionadas a quais informações básicas e adicionais são necessárias de mim para melhorar o prompt (máximo de 5). Se o prompt precisar de mais esclarecimentos ou detalhes, faça perguntas para obter mais informações para incluir no prompt}

2. Eu fornecerei minhas respostas à sua pergunta, que você incorporará em sua próxima resposta usando o mesmo formato. Continuaremos esse processo iterativo comigo te fornecendo informações adicionais, e você atualizará o prompt até que ele seja aperfeiçoado.

Lembre-se, o prompt que estamos criando deve ser escrito a partir da minha perspectiva como solicitante, fazendo o pedido a você (GPT3, GPT4, agentes de IA ou ferramentas similares).

Pense cuidadosamente e use seu conhecimento de especialista para criar um prompt impecável.

Sua primeira resposta agora deve ser apenas uma saudação e perguntar sobre o que o prompt que preciso.

---

## Modelo Genérico

---

## 🧩 Modelo de Prompt para Descrição de Telas (UI/UX) com IA

Este modelo é destinado à documentação ou geração de telas via IA. Estruture a descrição com base nas seções abaixo para obter maior clareza visual, coerência de estilo e controle criativo.

### 1. Visão Geral da Tela

Descreva brevemente:

- Tipo de produto e setor (ex: app bancário, plataforma educacional)
- Dispositivo e plataforma (mobile, tablet, desktop – Android, iOS, Web)
- Estilo visual (ex: minimalista, técnico, emocional, institucional)
- Objetivo funcional da tela (ex: login, agenda, cadastro, dashboard)
- Tom ou sensação da interface (ex: confiança, pertencimento, diversão)

**Exemplo:**
Aplicativo mobile iOS para torcedores de futebol acompanharem jogos ao vivo.
Estilo escuro, com foco em emoção, pertencimento e ação rápida.
Tela de login que convida o usuário a criar conta, fazer login ou acessar sem cadastro.

### 2. Estrutura e Componentes da Tela

Liste as seções da interface e detalhe cada uma conforme abaixo.

#### Nome da Seção

- **Função:** [Descreva o papel dessa seção no fluxo da tela]
- **Elementos internos:** [Liste botões, campos, textos, ícones com exemplos reais]
- **Estilo visual local:** [Informe cor, tipografia, borda, alinhamento, etc.]
- **Comportamento esperado:** [Descreva estados ativos, hover, interações esperadas]

Repita este bloco para quantas seções forem necessárias:

- Header
- Menu lateral
- Conteúdo central
- Painel de status ou cards
- Formulário ou lista
- Barra de ações / botões
- Rodapé ou navegação inferior

### 3. Estilo Global e Heurísticas

Informe as diretrizes visuais e heurísticas aplicadas a toda a tela.

- **Paleta de cores:** [ex: fundo branco, texto cinza escuro, botões roxos]
- **Tipografia:** [ex: Sans-serif, títulos 24px bold, texto 16px regular]
- **Espaçamento e hierarquia:** [ex: margens amplas, alinhamento à esquerda]
- **Princípios de Gestalt aplicados:** [proximidade, contraste, repetição]
- **Foco visual intencional:** [ex: botão primário destacado]
- **Acessibilidade:** [ex: contraste mínimo 4.5:1, toque mínimo de 48px]
- **Tom de voz (UX Writing):** [ex: caloroso, direto, técnico, amigável]

### 4. Instrução Final para a IA

Use esta seção para definir o que deseja como saída ao aplicar este prompt.

**Exemplos:**

- Gere um mockup visual estático da tela descrita acima.
- Analise os elementos da interface e sua hierarquia visual.
- Crie três variações visuais com ajustes na disposição e estilo.

### 💡 Opcional: Conexão com outras telas (Fluxo)

Se fizer parte de uma jornada maior, conecte com telas anteriores e seguintes.

- **Nome da Etapa:** [ex: Tela 1 – Login]
- **Anterior:** [ex: Tela de Splash]
- **Próxima:** [ex: Tela de Cadastro]
- **Mudanças visuais esperadas:** [ex: transição do fundo emocional para interface limpa com formulário]

---

## Modelos Geradores de Prompts por Indústria

---

### #01 - Aeroespacial e Defesa

#### Blocos Típicos – Indústria: Aeroespacial e Defesa

##### [M01] Navegação Hierárquica Lateral

- Ícones funcionais e rotulados por tooltip
- Divisão clara por módulos como: dashboard, agenda, fases do projeto, documentos técnicos

##### [M02] Área Central de Visualização Técnica

- Espaço destinado à visualização de entidade central (ex: aeronave, esquema técnico, blueprint)
- Possível uso de representação 3D, visualizações por seção ou corte

##### [M03] Painel Temporal ou de Fases

- Linha do tempo horizontal ou matriz por status de produção
- Indicação clara da fase atual com elementos visuais em destaque

##### [M04] Painel de Status Operacional

- Listagem de tarefas, execuções, inspeções ou eventos críticos
- Ícones ou cores de apoio para indicar andamento ou atenção

##### [M05] Módulo de Agenda ou Planejamento

- Exibição de datas, blocos de tempo, previsões de execução ou marcos
- Ação complementar como botão de detalhes ou checklist

#### Estilo Visual e Heurísticas Recomendadas

- Paleta clara ou neutra com acento técnico (azul, roxo, cinza técnico)
- Tipografia sans-serif de leitura objetiva (sem floreios visuais)
- Layout modular com espaçamento generoso e foco na leitura rápida
- Uso de metáforas físicas (ex: modelos ou peças) para apoio cognitivo
- Contraste adequado e responsividade para análise em múltiplas telas
- Consistência visual e sem ruído estético — foco é clareza e controle

#### Instrução Final para Geração – Aeroespacial e Defesa

> Use este modelo como base para gerar prompts detalhados de interfaces da indústria aeroespacial.  
> A estrutura deve refletir modularidade, sofisticação técnica e suporte a decisões baseadas em dados.  
> Evite conteúdos fictícios específicos. Priorize composição, estilo e estrutura visual típicas da indústria.

---

### #02 - Automotiva

#### Blocos Típicos – Indústria: Automotiva

##### [M01] Navegação Modular por Função

- Menus laterais ou inferiores com acesso a: veículo, desempenho, serviços, manutenção, concessionárias
- Ícones com visual técnico (veículo, rodas, painel, engrenagens)

##### [M02] Visualização do Veículo ou Componente

- Imagem ou render do carro em destaque (2D ou 3D)
- Possível corte de seção (motor, pneus, bateria, conectividade)
- Marcadores para alertas, status ou personalizações

##### [M03] Painel de Desempenho ou Diagnóstico

- Indicadores visuais (medidores, velocímetro, temperatura, consumo, etc.)
- Layout em painéis ou cards com microdados operacionais

##### [M04] Fluxos de Serviço ou Manutenção

- Agendamento de revisão, histórico de serviços, status de ordens
- Cards de status com CTA como “Reagendar”, “Ver mais”, “Acompanhar solicitação”

##### [M05] Interação com Marca ou Experiência

- Mensagens de boas-vindas personalizadas
- Integrações com marca (design system, cores, tipografia própria)
- Sugestões de rotas, recursos premium, notificações dinâmicas

#### 🧠 Estilo Visual e Heurísticas Recomendadas

- **Estilo híbrido:** técnico + emocional (precisão com experiência de marca)
- **Paleta típica:** preto, grafite, prata, vermelho ou azul elétrico como cor de ação
- **Tipografia:** robusta, levemente condensada, com clareza e sofisticação
- **Composição:** cards ou blocos com espaçamento calculado, comportamento responsivo
- **Feedback visual:** ícones de status, animações sutis para transições de fases
- **Foco em mobilidade:** design que respeita leitura em movimento, com foco visual em CTAs e status

#### 🧩 Instrução Final para Geração – Automotiva

> Use este modelo como base para gerar prompts descritivos ou mockups de interfaces para produtos digitais no setor automotivo.  
> Mantenha estrutura modular, misturando visual técnico com branding forte.  
> Priorize legibilidade, navegação intuitiva e dados operacionais com apresentação de alto impacto visual.  
> Evite nomes de veículos ou dados fictícios — descreva composição, estilo e comportamento esperados.

---

### #03 - Bancos

#### Blocos Típicos – Indústria: Bancos

##### [M01] Header com Identificação e Navegação – Bancos

- Área superior com saudação ao usuário, ícone de perfil e notificações
- Identificadores visuais de segurança (ex: ícone de cadeado ou certificado)
- Menu de acesso rápido a configurações, chat ou ajuda

##### [M02] Resumo Financeiro ou Conta Corrente

- Exibição do saldo principal com opção de ocultar/mostrar
- Carrossel com cartões, contas vinculadas ou contas em outras instituições
- Indicadores visuais simples de saldo positivo, negativo, bloqueado

##### [M03] Grade de Ações Principais

- Ícones circulares ou em botões com texto curto:
  - Transferir
  - Pagar
  - Pix
  - Depositar
  - Agendar
- Hierarquia visual entre ações mais usadas e secundárias

##### [M04] Histórico de Transações ou Atividades

- Lista cronológica de movimentações: ícone, nome da operação, valor, data
- Pode incluir filtros por período, tipo de transação ou tags
- Estilo de apresentação: cards, linhas ou blocos

##### [M05] Sessão Promocional ou Educativa

- Cards com sugestões de serviços como crédito pessoal, investimentos, seguros
- Estilo alinhado à identidade visual do banco
- Pode incluir CTAs ou botões para contratação, simulação ou aprendizado

## 📊 Estilo Visual e Heurísticas Recomendadas

- **Paleta:** Azul, verde escuro, cinza, branco ou dourado – cores que comunicam solidez e tranquilidade
- **Tipografia:** Institucional, sem serifas, altamente legível mesmo em tamanhos reduzidos
- **Layout:** Modular, com espaços bem definidos para leitura rápida e toque seguro
- **Gestalt aplicada:** Proximidade e repetição entre elementos do mesmo grupo
- **Acessibilidade:** Contraste forte, suporte a leitores de tela, foco por teclado/tab, toque mínimo 48px
- **Microinterações:** Discretas, voltadas à confirmação de ações ou alertas (ex: Pix enviado, boleto agendado)

---

## 📎 Instrução Final para Geração – Bancos

> Use este modelo como estrutura base para descrever ou gerar prompts de interfaces bancárias.  
> O design deve refletir clareza, formalidade, confiança e usabilidade universal.  
> Evite simular valores ou dados reais; concentre-se na organização da tela, seu comportamento esperado e estilo visual coerente com o setor bancário.

---

### #04 - Bens e Serviços

#### Blocos Típicos – Indústria: Bens de Consumo e Serviços

##### [M01] Área de Apresentação do Produto

- Destaque visual com imagem do produto (TV, geladeira, smartphone, etc.)
- Carrossel de ângulos, zoom, variações de cor e recursos principais
- Pode incluir selo da marca, reviews ou indicação de destaque (“mais vendido”)

##### [M02] Grade de Funcionalidades ou Especificações

- Ícones com texto breve ou bullet points de diferenciais
- Separação por categorias: desempenho, design, conectividade, sustentabilidade
- Pode ser exibido em blocos com ícones ilustrativos ou abas

##### [M03] Ações Relacionadas ao Produto

- Botões ou cards para:
  - Comparar
  - Agendar instalação
  - Baixar manual
  - Solicitar suporte técnico
- Formatos variados: botão destacado, callout, ou blocos horizontais

##### [M04] Relacionamento com o Cliente

- Formulário de registro de produto ou garantia
- Canal de suporte com chat, FAQ, telefone, WhatsApp
- Cards com histórico de atendimento ou status de solicitação

##### [M05] Personalização e Recomendação

- Produtos similares ou complementares
- Sugestões baseadas em uso ou perfil do consumidor
- Seções visuais com sugestões do tipo “Você também pode gostar”

## 🖼️ Estilo Visual e Heurísticas Recomendadas

- **Paleta flexível, adaptada à marca:** Pode variar entre minimalismo clean (branco/cinza) ou cores vibrantes (vermelho, azul, laranja)
- **Tipografia:** Comercial, legível, com variações de peso para destacar funcionalidades e títulos de produto
- **Layout modular:** Dividido em sessões claras, com imagens amplas e textos curtos
- **Foco visual:** Imagem do produto e benefícios percebidos
- **Microinterações:** Em carrosséis, expansão de especificações, confirmação de ações de suporte
- **Acessibilidade:** Textos alternativos para imagens, botões com toque mínimo, foco no contraste de CTAs

---

## 🔧 Instrução Final para Geração – Bens de Consumo e Serviços

> Use este modelo como base para gerar prompts de interfaces no setor de bens de consumo e serviços.  
> O design deve refletir a identidade da marca, destacar produtos de forma atrativa e funcional, e oferecer acesso intuitivo a suporte, informações e comparações.  
> Evite usar nomes ou dados reais de produtos; descreva os blocos visuais, estrutura e interações esperadas com clareza.

---

### #05 - Comunicações e Mídia

#### Blocos Típicos – Indústria: Comunicações e Mídia

##### [M01] Header ou Barra Editorial

- Logotipo da marca, menu de seções (Notícias, Esportes, Cultura, Ao Vivo)
- Ícones de busca, login/perfil e alerta (breaking news ou notificações personalizadas)
- Possibilidade de barra de destaque rotativa com chamada principal

##### [M02] Destaques do Dia ou Matérias em Evidência

- Cards grandes com imagem, título, subtítulo, categoria e data
- Grid ou carrossel horizontal
- Selo de “ao vivo”, “urgente” ou “novo” com destaque visual

##### [M03] Feed de Conteúdo Personalizado

- Lista cronológica ou por tema com artigos, vídeos, podcasts, etc.
- Filtro por tipo de mídia ou preferência do usuário
- Pode incluir tags como “Opinião”, “Investigativo”, “Esporte”

##### [M04] Player de Mídia Integrado

- Controles de reprodução, timeline, legendas e ajuste de qualidade
- Pode ser flutuante, fixo no topo ou integrado ao conteúdo
- Opções de salvar, compartilhar ou reagir

##### [M05] Área de Engajamento ou Comunidade

- Comentários, curtidas, enquetes, ou respostas a jornalistas e colunistas
- Cards com artigos recomendados ou relacionados
- Botão para seguir temas, autores ou editorias

## 🖋️ Estilo Visual e Heurísticas Recomendadas

- **Paleta editorial:** branco, preto, vermelho ou azul institucional (ou variações mais leves conforme o veículo)
- **Tipografia:** inspirada em publicações – serifadas para títulos, sans-serif para corpo de texto
- **Layout modular:** foco em cards de conteúdo, colunas e quebras de leitura para escaneabilidade
- **Hierarquia de informação:** destaque para manchete > subtítulo > categoria > data
- **Acessibilidade:** texto ajustável, contraste forte, suporte a transcrição e legendas
- **Interatividade suave:** animações leves para carrosséis e ações de engajamento (curtir, comentar)

---

## 🧩 Instrução Final para Geração – Comunicações e Mídia

> Use este modelo como base para descrever ou gerar prompts de interfaces no setor de comunicações e mídia.  
> O foco deve ser o consumo fluido e personalizado de conteúdo multimídia, com atenção à hierarquia editorial, estética clara e engajamento do usuário.  
> Evite inserir nomes de matérias ou veículos reais. Foque na estrutura, ritmo visual e estilo da informação.

---

### #06 - Educação

#### Blocos Típicos – Indústria: Educação

##### [M01] Área de Boas-Vindas ou Dashboard Pessoal

- Saudação ao aluno ou professor com destaque de progresso e notificações
- Cards com próximas atividades, mensagens importantes ou agenda
- Personalização leve (nome, foto, cor associada ao curso)

##### [M02] Trilha de Aprendizado ou Grade de Aulas

- Listagem linear ou em grid de módulos, lições, unidades ou etapas
- Cada item pode conter: nome, status (pendente/concluído), nota, botão “continuar”
- Uso de ícones ou miniaturas para diferenciar conteúdos (vídeo, quiz, leitura, fórum)

##### [M03] Visualização de Conteúdo Didático

- Player integrado (vídeo ou áudio), visualizador de PDF, texto corrido ou slides
- Controles de velocidade, legenda, anotações
- Botões para marcar como concluído ou fazer download

##### [M04] Avaliações e Atividades

- Blocos com exercícios, quizzes, trabalhos e provas
- Status (respondido, em correção, nota publicada)
- Botão de “Enviar” ou “Refazer” com feedback automático (se aplicável)

##### [M05] Interação e Suporte

- Fórum, chat com tutores, FAQ e canal para dúvidas
- Sessões ao vivo ou agenda de plantões (com botão para entrar na sala)
- Espaço para comentários ou avaliações do conteúdo

## 📘 Estilo Visual e Heurísticas Recomendadas

- **Paleta clara e estimulante:** tons suaves ou cores da instituição (ex: azul, verde, laranja)
- **Tipografia:** amigável e altamente legível, com foco em leitura longa e compreensão
- **Layout previsível:** navegação lateral (módulos), foco no conteúdo principal ao centro
- **Ritmo visual:** alternância entre blocos visuais e textuais para manter atenção
- **Acessibilidade:** suporte a leitores de tela, contraste forte, controle de fonte e espaçamento
- **Gamificação leve (opcional):** barras de progresso, selos, pontuação simbólica

---

### Instrução Final para Geração - Educação

> Use este modelo como base para descrever ou gerar prompts de interfaces educacionais digitais.  
> A tela deve priorizar clareza, foco na jornada de aprendizagem e interação contínua entre estudante, conteúdo e instrutor.  
> Evite nomes de cursos ou instituições; foque na estrutura, componentes pedagógicos e estilo visual voltado ao ensino.

---

### #07 - Esporte

#### Blocos Típicos – Indústria: Esportes

##### [M01] Header com Identidade e Status de Partida

- Logotipo ou escudo, nome da equipe ou evento
- Cor da identidade aplicada como tema visual dominante
- Notificações, login, configurações
- Indicador de próxima partida ou placar em tempo real (com botão “Acompanhar ao vivo”)

##### [M02] Calendário de Jogos e Compra de Ingressos

- Lista visual de partidas (data, adversário, local) com CTA visível
- Botão: “Comprar ingresso” com destaque em cor da marca
- Status do jogo (em breve, esgotado, em andamento) com visual distinto
- Opção para adicionar ingresso à carteira digital ou gerar QR code

##### [M03] Programa de Fidelidade e Benefícios

- Card do plano de sócio torcedor com status, pontuação, benefícios ativos
- Seções como: “Resgatar pontos”, “Meus benefícios”, “Histórico”
- Integração com ações: pontuar ao assistir jogo, comprar produto, convidar amigo

##### [M04] Bloco de Apostas Esportivas

- Odds em destaque para jogos do dia ou da rodada
- Botões rápidos: “Ver estatísticas”, “Fazer aposta”, “Ver resultados”
- Indicador de saldo, histórico de apostas, bônus ativos
- Elementos gráficos como barras de aposta popular, odds em movimento

##### [M05] Conteúdo e Engajamento Multimídia

- Destaques: melhores momentos, bastidores, treinos
- Feed de vídeos e galerias integradas com botão “Reagir” ou “Compartilhar”
- Enquetes ao vivo, ranking de torcida, quizzes interativos

##### [M06] Loja Oficial e Produtos Personalizados

- Cards com camisetas, acessórios, memorabilia
- Produtos conectados ao jogo (ex: “camisa usada hoje”, “oferta do dia”)
- Checkout ágil com integração com fidelidade (“compre com pontos”)

## 🎨 Estilo Visual e Heurísticas Recomendadas

- **Paleta emocional:** vermelho, azul, preto, branco ou as cores do clube
- **Tipografia:** impactante para títulos, leve e legível para descrições
- **Layout centrado na ação:** elementos grandes, com foco em engajamento rápido
- **Gestalt aplicada:** contraste, agrupamento visual por tema (jogo, ingresso, aposta, loja)
- **Acessibilidade:** contraste alto, botões grandes e bem espaçados, feedback visual em apostas e compras
- **Tempo real:** muitos elementos se atualizam dinamicamente (placares, odds, contadores regressivos)

---

## 🧩 Instrução Final para Geração – Esportes

> Use este modelo como base para gerar prompts de interfaces digitais no setor de esportes.  
> A estrutura deve priorizar **ação, emoção e recorrência**  
> Evite dados reais de partidas ou jogadores; foque nos elementos visuais, comportamentais e de fluxo mais comuns nesse setor.

---

### #08 - Industrial

#### Blocos Típicos – Indústria: Industrial

##### [M01] Painel de Processos e Fluxo Operacional

- Diagrama do processo produtivo com indicadores em tempo real
- Visual com Sankey, flowcharts ou pipelines industriais
- Estados: operando, ocioso, bloqueado, falha, setup
- Indicadores animados de fluxo, gargalos ou travamentos

##### [M02] Dashboard com Data Visualization

- KPIs de produção e eficiência (OEE, ciclo, perdas)
- Heatmaps, radar charts, gauge charts e timelines
- Comparativos entre turnos, setores ou operadores
- Destaques visuais com alertas em tempo real

##### [M03] Mapa Interativo da Planta ou Equipamentos

- Layout visual da planta fabril com status por equipamento
- Hover ou click para exibir: tempo de ciclo, operador, falhas recentes
- Suporte a filtros, zoom, e visão setorial

##### [M04] Gestão de Ordens, Turnos e Workflows

- Timeline de ordens com fases: agendada → execução → auditoria
- Kanban de processos com reordenação por drag & drop
- Cards com dados operacionais e ações rápidas
- Acesso e visibilidade conforme perfil (ex: operador não vê área financeira)

##### [M05] Gestão de Colaboradores e Permissões

- Lista de operadores e técnicos com filtros por turno/setor
- Cards de perfil: nome, função, foto, produtividade
- Atribuição de tarefas por drag & drop
- Logs de ação por usuário (assinatura digital, QR code, checklists)

##### [M06] Alertas e Diagnóstico Operacional

- Linha do tempo de falhas com filtros e visualização por severidade
- Ícones de risco: falha, parada, inspeção pendente
- Drill-down por causa, máquina, ou colaborador
- Integração com gráficos de dispersão, histograma ou Ishikawa

## 🧪 Estilo Visual e Heurísticas Recomendadas

- **Paleta:** Azul técnico, branco, cinza escuro, verde (ok), amarelo (alerta), vermelho (falha)
- **Tipografia:** Sans-serif legível; monoespaçada para dashboards numéricos
- **Layout modular:** Blocos reativos e reorganizáveis por prioridade
- **Gestalt aplicada:** Agrupamento funcional, repetição visual e codificação por cor
- **Suporte a perfis e permissões:** Diferenciação por tipo de usuário
- **Feedback imediato:** Animações, confirmação sonora ou visual (modo operador)

---

## 🧩 Instrução Final para Geração – Industrial

> Use este modelo como base para gerar prompts de interfaces no setor industrial.  
> As telas devem representar sistemas com **visualização orientada a processos**, **dashboards ricos em DataViz**, e **gestão de colaboradores com controle de permissões**.  
> Evite dados ou nomes específicos. Foque na composição, visualidade e comportamento esperado para esse tipo de ambiente.

---

### #09 - Logística

#### Blocos Típicos – Indústria: Logística

##### [M01] Mapa Interativo com Modais Integrados

- Visualização de veículos em tempo real por modal:
  - Ícones distintos para caminhão, van, bicicleta, barco, drone
- Filtros por tipo de transporte, região, status da entrega
- Exibição de tráfego, condições climáticas e áreas de risco (urbano ou fluvial)
- Possibilidade de clicar em um modal para ver itinerário, pontos de parada, velocidade média

##### [M02] Lista de Entregas / Coletas com Rastreamento Detalhado

- Cards por item com:
  - Número de rastreamento
  - Tipo de item
  - Modal envolvido
  - Status (em preparo, em rota, entregue, devolvido, sinistro)
  - Datas estimada e real de entrega
  - Nome e foto do entregador (se urbano)
- Barra de progresso visual e botão “rastrear entrega”
- Ação rápida: abrir detalhes, reagendar, confirmar recebimento

##### [M03] Painel de Ocorrências e Exceções

- Exibição em lista ou timeline de eventos: falha, reentrega, perda de rota
- Códigos visuais de severidade e tipo
- Acesso rápido a evidências (foto, assinatura, geolocalização, observação do entregador)
- Botão para “resolver” ou “reabrir”

##### [M04] Dashboard de Performance e SLA

- Gráficos: OTIF, custo por km, % entregas no prazo, tempo médio por modal
- Mapas de calor logísticos por rota, CEP, centro de distribuição
- Rankings por transportadora, região ou operador
- Filtros por modal (urbano, fluvial, aéreo etc.)

##### [M05] Gestão de Motoristas, Entregadores e Frota

- Lista com veículos e status (em rota, manutenção, disponível)
- Perfis de entregadores com foto, rota atual, entregas do dia, nota do cliente
- Atribuição manual ou automática de entregas por zona geográfica
- Visualização de compliance (ex: pausa obrigatória, uso de EPI, tempo em trânsito)

## 🧭 Estilo Visual e Heurísticas Recomendadas

- **Paleta funcional:** branco, cinza claro, verde (entregue), amarelo (atrasado), vermelho (falha), azul (em rota)
- **Tipografia:** clara, adaptável ao contexto mobile e painel
- **Layout:**
  - Desktop: mapa à esquerda, painel de entregas à direita
  - Mobile: cards verticais com botão para abrir mapa
- **Feedback visual e sonoro:** mudança de status gera alerta (badge, vibração ou som discreto)
- **Interações rápidas:** prioridade para toques rápidos, leitura em movimento e acesso offline a algumas informações
- **DataViz aplicada à rastreabilidade:** linha do tempo por entrega, pontos de parada, status em cores distintas

---

## 🧩 Instrução Final para Geração – Logística

> Use este modelo como base para gerar prompts de interfaces voltadas à logística multimodal.  
> A interface deve apresentar **mapas em tempo real**, **rastreabilidade de entregas com entregador e datas estimadas**, **integração com modais fluvial e urbano**, **painéis de desempenho e ocorrências**.  
> Evite dados reais — concentre-se em componentes visuais, estrutura da jornada e tipos de informação esperada.

---

### #10 - Recursos Naturais

#### Blocos Típicos – Indústria: Recursos Naturais

##### [M01] Mapa Geoespacial com Camadas Ativas

- Exibição de áreas de extração, proteção, operação ou energia gerada
- Camadas visuais: topografia, zonas de risco ambiental, cobertura vegetal, clima
- Sensores IoT exibindo dados de solo, ar, temperatura, pressão ou vibração
- Alertas geográficos em tempo real (ex: proximidade de áreas sensíveis)

##### [M02] Painel de Equipamentos, Frentes e Produção

- Cards com máquinas, sondas, torres e estações com status visual
- KPIs: produtividade, tempo ativo, eficiência, consumo de recursos
- Indicadores de falhas, manutenção pendente, risco de sobrecarga
- Agrupamento por site, frente ou unidade extrativa

##### [M03] Bloco ESG – Ambiental, Social e Governança

- Emissões de carbono por operação (com curva de redução por métrica)
- Uso de água, descarte, reaproveitamento de insumos
- Indicadores sociais: comunidade impactada, licenciamento, relatórios públicos
- Histórico de ações ESG por frente, projeto ou região

##### [M04] Prevenção de Desastres e Risco Ambiental

- Matriz de risco por tipo de impacto (deslizamento, vazamento, incêndio, erosão)
- Linha do tempo de alertas críticos, inspeções e planos de contingência
- Checklists de conformidade regulatória (IBAMA, ANP, ONS etc.)
- Integração com plano de ação e evidência (imagens, documentos, sensores)

##### [M05] Cadeia Logística e Transporte de Recursos

- Visualização de carga por lote: minério, madeira, água, energia
- Status: extraído, em transporte, em processamento, armazenado
- Modal utilizado (rodoviário, ferroviário, duto, fluvial)
- Previsão de chegada, rastreamento e análise de perdas

##### [M06] Gestão de Colaboradores e Permissões

- Lista de usuários com papel (operador, supervisor, auditor ambiental)
- Atribuição de áreas e limites de acesso por tipo de risco ou sensibilidade
- Logs de ações críticas (quem aprovou, quem executou, quando)
- Integração com treinamentos obrigatórios e status de conformidade individual (EPI, formação, habilitação)

##### [M07] Relatórios e Auditorias Automatizadas

- Geração de relatórios técnicos, operacionais e ambientais por período
- Exportação PDF/CSV/JSON para ANP, IBAMA, investidores ou stakeholders
- Gráficos de tendência, mapas de risco acumulado, evolução ESG
- Histórico completo com versão e assinatura digital

## 🌱 Estilo Visual e Heurísticas Recomendadas

- **Paleta técnica com camadas ambientais:** verde (operacional), azul (hídrico), amarelo (atenção), vermelho (risco), cinza (inativo)
- **Tipografia:** legível sob condições extremas (reflexo, baixa luz, equipamentos)
- **Layout modular:** com painéis reordenáveis e áreas críticas em destaque
- **DataViz aplicada à natureza:** curvas de emissão, mapas de calor, radar de risco, barras empilhadas por frente
- **Gestalt de risco:** codificação por proximidade, cor e agrupamento funcional
- **Offline-first e sincronização controlada:** coleta em campo, sincronização segura posterior

---

## 🧩 Instrução Final para Geração – Recursos Naturais

> Use este modelo como base para gerar prompts de interfaces digitais voltadas à gestão de recursos naturais.  
> A tela deve priorizar **controle operacional técnico**, **responsabilidade ESG**, **prevenção de impactos ambientais** e **rastreabilidade de recursos extraídos e transportados**.  
> Descreva estrutura, componentes visuais e comportamentos esperados — sem citar locais, empresas ou dados reais.

---

### #11 - Saúde

#### Blocos Típicos – Indústria: Saúde

##### [M01] Header com Identificação e Navegação – Saúde

- Logotipo da instituição, nome do usuário/paciente, foto ou avatar
- Acesso rápido a notificações, configurações, suporte e área segura (logout)
- Indicação visual de ambiente seguro (cadeado, selo de privacidade)

##### [M02] Painel de Agendamento e Consultas

- Calendário visual com datas disponíveis, próximas consultas e histórico
- Botão destacado para “Agendar Consulta” ou “Solicitar Telemedicina”
- Cards de consulta: profissional, especialidade, local, status (confirmada, pendente, cancelada)
- Opção para reagendar, cancelar ou adicionar lembrete

##### [M03] Prontuário Eletrônico e Histórico Médico

- Bloco com resumo de dados clínicos: alergias, condições crônicas, medicamentos em uso
- Lista de exames realizados, prescrições, laudos e vacinas
- Botão para visualizar detalhes, baixar PDF ou compartilhar com outro profissional
- Alertas para pendências (ex: exame vencido, atualização de cadastro)

##### [M04] Área de Exames e Resultados

- Cards ou lista de exames: tipo, data, status (em análise, disponível, reagendar)
- Visualização de resultados com gráficos, tabelas ou imagens (ex: raio-x, ultrassom)
- Opção para enviar dúvidas ao médico ou solicitar segunda opinião

##### [M05] Comunicação e Suporte

- Chat seguro com equipe médica, assistente virtual ou central de atendimento
- FAQ, orientações rápidas e links para serviços de emergência
- Botão de chamada rápida para suporte ou teleorientação

##### [M06] Área de Pagamentos e Autorizações

- Histórico de faturas, coparticipações, reembolsos e autorizações pendentes
- Botão para gerar boleto, pagar online ou enviar comprovante
- Status visual de autorização de procedimentos (aprovado, em análise, negado)

## 🩹 Estilo Visual e Heurísticas Recomendadas

- **Paleta:** branco, azul claro, verde, tons suaves que transmitam calma e segurança
- **Tipografia:** legível, sem serifa, tamanhos adaptáveis para idosos ou baixa visão
- **Layout modular:** blocos bem separados, foco em informações críticas e navegação simples
- **Acessibilidade:** contraste forte, suporte a leitores de tela, navegação por teclado, botões grandes
- **Feedback visual:** confirmações claras para agendamento, envio de exames e mensagens
- **Privacidade:** áreas sensíveis sempre protegidas por autenticação e avisos de segurança

---

## 🧩 Instrução Final para Geração – Saúde

> Use este modelo como base para gerar prompts de interfaces digitais para o setor de saúde.  
> A estrutura deve priorizar **segurança, clareza, empatia e acessibilidade**, com foco em jornadas de pacientes e profissionais.  
> Evite nomes de pacientes, médicos ou dados reais; descreva blocos visuais, estrutura e comportamentos esperados para o contexto de saúde.

---

### #12 - Software e Plataformas

#### Blocos Típicos – Indústria: Software e Plataformas

##### [M01] Header Global e Navegação Modular

- Barra superior com logo, busca, notificações, perfil e menu de contexto
- Navegação lateral ou tabular para módulos: dashboard, projetos, integrações, configurações

##### [M02] Dashboard e Painéis de Controle

- Cards ou widgets com KPIs, gráficos, listas rápidas e atalhos de ação
- Personalização de layout (drag & drop, esconder/exibir blocos)
- Filtros dinâmicos e atualização em tempo real

##### [M03] Listagens, Tabelas e Grids

- Tabelas responsivas com ordenação, filtros, seleção múltipla e ações em lote
- Visualização detalhada ao clicar em item (side panel, modal ou página dedicada)
- Suporte a exportação/importação de dados

##### [M04] Formulários e Fluxos de Cadastro

- Campos dinâmicos, validação em tempo real, feedback visual de erro/sucesso
- Passos em wizard para fluxos longos
- Ações rápidas: salvar, duplicar, cancelar, avançar

##### [M05] Integrações, APIs e Webhooks

- Listagem de integrações ativas, status, logs de eventos e configuração de endpoints
- Documentação embutida e exemplos de uso
- Testes rápidos de conexão e feedback de status

##### [M06] Suporte, Ajuda e Comunidade

- Chatbot, FAQ, base de conhecimento e abertura de chamados
- Links para comunidade, fóruns ou grupos de usuários
- Feedback do usuário e sugestões de melhoria

## 🖥️ Estilo Visual e Heurísticas Recomendadas

- **Paleta:** tons neutros (cinza, branco, azul, verde), com cores de destaque para alertas e ações primárias
- **Tipografia:** moderna, sem serifa, tamanhos adaptáveis
- **Layout modular:** blocos reordenáveis, foco em produtividade e clareza
- **Acessibilidade:** contraste forte, navegação por teclado, suporte a leitores de tela
- **Microinterações:** feedback visual em ações, loaders, confirmações e alertas

---

## 🧩 Instrução Final para Geração – Software e Plataformas

> Use este modelo como base para gerar prompts de interfaces digitais para produtos de software e plataformas.  
> Priorize modularidade, integração, clareza visual e suporte a fluxos complexos.  
> Evite nomes de clientes ou dados sensíveis; foque na estrutura, componentes e comportamentos esperados.

---

### #13 - Telecomunicação

#### Blocos Típicos – Indústria: Telecomunicação

##### [M01] Área de Identificação e Status do Cliente

- Saudação, nome, número do contrato/linha, status do plano
- Indicadores de pagamento, pendências ou promoções ativas

##### [M02] Painel de Consumo e Serviços

- Gráficos de uso de dados, minutos, SMS, franquias e limites
- Cards de serviços ativos, adicionais e opções de upgrade

##### [M03] Faturas, Pagamentos e Histórico

- Lista de faturas, status (paga, em aberto, vencida), download de PDF, código de barras
- Botão para pagar online, negociar ou parcelar

##### [M04] Suporte Técnico e Atendimento

- Abertura de chamados, acompanhamento de protocolos, chat com atendente ou assistente virtual
- Diagnóstico rápido de rede, agendamento de visita técnica

##### [M05] Contratação e Gerenciamento de Serviços

- Ofertas personalizadas, contratação de pacotes, upgrade/downgrade de plano
- Visualização de benefícios, fidelidade e pontos

##### [M06] Notificações e Alertas (Varejo)

- Mensagens importantes, promoções, alertas de consumo ou manutenção programada

---

### 🧩 Instrução Final para Geração – Telecomunicação

> Use este modelo como base para gerar prompts de interfaces digitais para o setor de telecomunicação.  
> Priorize clareza, autoatendimento, status de consumo e suporte eficiente.  
> Evite nomes de clientes ou dados reais; foque na estrutura, componentes e comportamentos esperados.

---

### #14 - Varejo

#### Blocos Típicos – Indústria: Varejo

##### [M01] Vitrine de Produtos e Promoções

- Grid de produtos com imagem, preço, desconto, selo de destaque
- Banners rotativos com ofertas e campanhas sazonais

##### [M02] Busca, Filtros e Navegação por Categoria

- Barra de busca com sugestões, filtros por preço, marca, avaliação, categoria
- Navegação lateral ou superior por departamentos

##### [M03] Detalhe do Produto

- Imagens ampliáveis, descrição, especificações, avaliações de clientes
- Botões de compra, adicionar à lista de desejos, comparar

##### [M04] Carrinho, Checkout e Pagamento

- Lista de itens, resumo de valores, cálculo de frete, cupons de desconto
- Fluxo de checkout simplificado, múltiplos métodos de pagamento

##### [M05] Área do Cliente e Pós-Venda

- Histórico de pedidos, rastreamento, devoluções, suporte e chat
- Programa de fidelidade, pontos, recomendações personalizadas

##### [M06] Notificações e Alertas

- Promoções, status de pedido, lembretes de carrinho abandonado

---

### 🛍️ Instrução Final para Geração – Varejo

> Use este modelo como base para gerar prompts de interfaces digitais para o setor de varejo.  
> Priorize exposição de produtos, fluxo de compra ágil e pós-venda eficiente.  
> Evite nomes de produtos ou dados reais; foque na estrutura, componentes e comportamentos esperados.
