# Guidelines para IA

## 01 - Classificação de Indústrias, Categorias e Subcategorias

### Objetivo – Classificação

Definir a estrutura de classificação que o agente de IA deve usar para identificar a indústria, categoria e subcategoria de um projeto de produto digital com base em dados fornecidos pelo usuário.

## 📌 Lista de Indústrias e Exemplos

1. **Aeroespacial e Defesa**
    - Exemplos: Companhias aéreas nacionais e internacionais, Jatinhos particulares
2. **Automotiva**
    - Exemplos: Marcas de automóveis
3. **Bancos**
    - Exemplos: Bancos privados e públicos
4. **Bens de Consumo e Serviços**
    - Exemplos: Empresas de dispositivos móveis, televisões, geladeiras
5. **Comunicações e Mídia**
    - Exemplos: Sites de notícias, entretenimento
6. **Educação**
    - Exemplos: E-books, Cursos Online
7. **Esportes**
    - Exemplos: Marcas de roupas de esportes, Empresas de estádios de futebol
8. **Industrial**
    - Exemplos: Empresas de serralheria e materiais brutos como aço e ferro
9. **Logística**
    - Exemplos: Empresas de mobilidade urbana, rodoviária e ferroviária.
10. **Recursos Naturais**
    - Exemplos: Extração de matérias como ouro, cobre, ferro
11. **Saúde**
    - Exemplos: Farmácias, Hospitais e redes de saúde
12. **Software e Plataformas**
    - Exemplos: Sistemas internos corporativos
13. **Telecomunicação**
    - Exemplos: Empresas de telefonia móvel, residencial e provedoras de internet
14. **Varejo**
    - Exemplos: E-commerces de multiprodutos

## 🧩 Categorias e Subcategorias por Indústria

### Varejo

- **Compra e Pagamento**
  - Subcategorias: Carrinho, Check-out, Pagamento com 1 clique
- **Descoberta de Produtos**
  - Subcategorias: Busca, Filtros, Recomendação
- **Atendimento**
  - Subcategorias: Chat, FAQ, Suporte ao Cliente

### Bancos

- **Acesso Seguro**
  - Subcategorias: Login, Autenticação biométrica, Token
- **Transações**
  - Subcategorias: Transferência, Pix, Recarga
- **Gerenciamento de Conta**
  - Subcategorias: Faturas, Limites, Investimentos

### Saúde

- **Agendamento e Consulta**
  - Subcategorias: Marcação online, Confirmação via SMS
- **Histórico Clínico**
  - Subcategorias: Prontuário, Prescrição, Exames
- **Atendimento Digital**
  - Subcategorias: Telemedicina, Chat com especialista

(Os demais setores seguem modelo similar — detalhamento contínuo nos documentos de guidelines por indústria)

## 🔍 Estratégia de Identificação Automática

### Quando houver identificação direta

Se o usuário mencionar marcas, contextos ou termos específicos ligados a um setor, classificar automaticamente.

**Exemplo:**

"Quero um app de e-commerce renomado para facilitar check-out."

→ Indústria: Varejo / Categoria: Compra e Pagamento / Subcategoria: Check-out

### Quando houver ambiguidade

O agente deve perguntar:

- “Seu produto se aproxima mais de qual desses setores?” (lista)
- “Qual função principal você quer resolver?”

### Método para Verificação de Similaridade

Detectar itens redundantes, agrupando por similaridade e sugerindo consolidação com base na nomenclatura, semântica e função dos elementos.

#### Etapas do Processo de Análise de Similaridade

1. **Definição de Parâmetros de Filtro:**
    - **Tipo de elemento:** Permitir seleção granular (ex: botão, input, card, modal).
    - **Contexto de uso:** Filtrar por fluxo, tela ou jornada específica.
    - **Intervalo de similaridade:** Ajuste dinâmico do limiar (ex: SSIM ≥ 0.6), com possibilidade de refino por feedback manual.

2. **Pré-processamento dos Elementos:**
    - Conversão para escala de cinza para uniformizar análise visual.
    - Extração de metadados (função, rótulo, estado visual).
    - Redimensionamento padronizado: 200x400 (Mobile) ou 400x200 (Desktop).
    - Identificação automática da função principal do elemento (ex: ação primária, modal de alerta, aba ativa).

3. **Clusterização e Comparação:**
    - Aplicação de SSIM (Structural Similarity Index) para agrupamento visual.
    - Análise semântica complementar (nome, função, contexto).
    - Limiar padrão: 0.6, ajustável conforme necessidade do projeto.

4. **Geração de Relatórios e Recomendações:**
    - Diagnóstico técnico detalhado, destacando redundâncias e inconsistências.
    - Sugestão de consolidação ou padronização de componentes.
    - Tabela comparativa: Tipo, Itens, Grau de Similaridade (SSIM), Ação Recomendada.
    - Relatório visual: Tela ou elemento representante de cada grupo, justificativa técnica para cada decisão.
    - Registro de feedbacks manuais para aprimoramento contínuo do processo.

### Aprendizado e refinamento

O agente deve registrar padrões de resposta e corrigir casos de erro com aprendizado contínuo.

## 02 - Guidelines Gerais de UX/UI

### Objetivo – UX/UI Gerais

Estabelecer diretrizes universais de experiência do usuário (UX) e interface (UI) que o agente deve aplicar independentemente da indústria, servindo como base para o design de protótipos digitais codáveis.

## 🎨 Princípios Visuais

### Tipografia

- Usar no máximo 3 estilos por tela (título, corpo, destaque).
- Hierarquia visual clara: `Título > Subtítulo > Texto > Legenda`
- Fontes recomendadas: Inter, Roboto, SF Pro Display (variar conforme plataforma).

### Cores

- Paleta limitada: 1 cor primária, 1 secundária, 2-3 tons neutros, 1 cor de alerta.
- Alto contraste para acessibilidade (mínimo AAA para texto essencial).

### Ícones

- Estilo coeso e consistente.
- Evitar ícones ambíguos: adicionar rótulo textual quando necessário.

### Espaçamento e Layout

- Usar grid system 8px como base.
- Considerar margens internas de componentes.
- Considerar espaçamentos entre componentes, entre imagens etc.
- Margens externas de no mínimo 16px.
- Espaçamento vertical entre blocos de 24px (títulos, cards, listas).

## 🧑‍🦱 Componentes Universais

### Botões

- Estados: default, hover, focus, disabled.
- Cores adaptáveis ao contexto (primário/ação principal, secundário).
- Altura mínima: 44px para área de toque.

### Inputs

- Labels sempre visíveis.
- Feedback imediato para erros (ex: "campo obrigatório").
- Ícones opcionais (ex: mostrar/ocultar senha).

### Navegação

- Fixar menu principal em mobile.
- No máximo 5 itens visíveis na navegação principal.
- Utilizar breadcrumbs em estruturas profundas.

### Modais

- Evitar excesso de uso.
- Sempre ter botão de fechar visível.
- Modal nunca deve ser o único caminho de ação (ex: login bloqueado).

## 🧑‍🦳 Acessibilidade

- Compatível com leitores de tela (uso correto de ARIA e semantic HTML).
- Navegação 100% por teclado (foco visível, tab index).
- Legibilidade mínima de 16px para textos informativos.
- Elementos clicáveis com área mínima de 44x44px.

## 🧑‍🦱 Princípios de Usabilidade

- Feedback imediato a cada ação do usuário.
- Redução de passos desnecessários em fluxos.
- Confirmação de ações críticas (ex: apagar, pagar).
- Padrões reconhecíveis por usuários (ex: ícone de lupa para busca).

## 🔁 Reutilização e Consistência

- Priorizar uso de Design Systems existentes.
- Componentes devem ser reutilizáveis e customizáveis via tokens (ex: cor, tamanho).
- Interface deve manter consistência visual entre telas.

## 📱 Responsividade

- Projetar interfaces pensando primeiro em smartphones.
- Garantir adaptação fluida para tablets e desktops.
- Garantir visibilidade dos principais elementos na primeira dobra.
- Considerar componentes flutuantes ou fixos apareçam em uma primeira dobra.
- Esconder, colapsar ou reestruturar conteúdos de baixa prioridade em telas pequenas.

## 📊 Indicadores de Qualidade Visual

- Coerência visual entre telas.
- Clareza e legibilidade.
- Contraste adequado.
- Feedback apropriado em interações.
- Número de componentes únicos minimizado.

## 03 - Guidelines Específicos por Indústria

### Objetivo – Específicos por Indústria

Estabelecer diretrizes detalhadas de design e uso de componentes adaptados às particularidades de cada indústria, garantindo alinhamento entre UX, objetivos de negócio e contexto de uso.

## 🔧 Estrutura por Indústria

Cada indústria é descrita com:

- Componentes-chave
- Padrões de layout
- Comportamentos esperados
- Objetivos de negócio específicos
- Cuidados especiais

### 🚀 Aeroespacial e Defesa

- **Componentes-chave:** Dashboards, alertas críticos, relatórios visuais
- **Layout:** Escuro, denso em dados, legibilidade em ambientes adversos
- **Comportamento esperado:** Confiabilidade, foco em segurança
- **Objetivos:** Precisão, tempo de resposta, controle operacional

### 🚗 Automotiva

- **Componentes-chave:** Galeria de veículos, simulador de customização, agendamento
- **Layout:** Visual limpo, foco em imagens, experiência premium
- **Comportamento esperado:** Navegação fluida e inspiradora
- **Objetivos:** Test-drive, configuração personalizada, conversão

### 💳 Bancos

- **Componentes-chave:** Inputs seguros, gráficos financeiros, botões fixos
- **Layout:** Estruturado por seções (conta, cartão, empréstimos)
- **Comportamento esperado:** Fluxos lineares, sensação de segurança
- **Objetivos:** Redução de erro, agilidade em transações, fidelização

### 📱 Bens de Consumo e Serviços

- **Componentes-chave:** Cards, reviews, botão comprar, integração com entrega
- **Layout:** Imagens grandes, foco em produto
- **Comportamento esperado:** Decisão rápida, compras recorrentes
- **Objetivos:** Conversão, retenção, fidelidade à marca

### 📰 Comunicações e Mídia

- **Componentes-chave:** Cards de notícia, carrosséis, destaques ao vivo
- **Layout:** Modular, visual com hierarquia editorial
- **Comportamento esperado:** Scroll fluido, leitura rápida
- **Objetivos:** Retenção, engajamento com conteúdo, tempo de tela

### 📚 Educação

- **Componentes-chave:** Progresso, cards de aula, calendário, gamificação
- **Layout:** Sequencial, checkpoints, microvitórias
- **Comportamento esperado:** Continuidade, reforço positivo
- **Objetivos:** Engajamento, redução de churn, conclusão

### ⚽ Esportes

- **Componentes-chave:** Galeria, ingressos, live stats, catálogo
- **Layout:** Imagens grandes, contraste forte, emoção visual
- **Comportamento esperado:** Compartilhamento, personalização
- **Objetivos:** Engajamento, vendas indiretas, experiência social

### 🏭 Industrial

- **Componentes-chave:** Dashboards de sensores, alertas operacionais
- **Layout:** Visual direto, foco em dados em tempo real
- **Comportamento esperado:** Precisão, foco em leitura e ação rápida
- **Objetivos:** Eficiência operacional, produtividade

### 🚚 Logística

- **Componentes-chave:** Rastreamento, status de entrega, mapa
- **Layout:** Mobile-first, foco em atualização dinâmica
- **Comportamento esperado:** Atualização em tempo real, pouca fricção
- **Objetivos:** Agilidade, transparência, redução de erros

### 🌱 Recursos Naturais

- **Componentes-chave:** Indicadores ambientais, relatórios ESG
- **Layout:** Neutro, clean, sem ruídos visuais
- **Comportamento esperado:** Interação mínima, leitura focada
- **Objetivos:** Conformidade, sustentabilidade, governança

### 🏥 Saúde

- **Componentes-chave:** Agendamento, histórico, alertas críticos
- **Layout:** Contraste alto, clareza, prioridade na informação
- **Comportamento esperado:** Empatia, segurança, precisão
- **Objetivos:** Confiança, acolhimento, redução de erros

### 💻 Software e Plataformas

- **Componentes-chave:** Dashboards, cards de tarefa, tabelas
- **Layout:** Modular, orientado à produtividade
- **Comportamento esperado:** Eficiência, personalização
- **Objetivos:** Redução de cliques, tempo de execução

### 📡 Telecomunicação

- **Componentes-chave:** Planos, consumo, atendimento digital
- **Layout:** Limpo, organizado por funcionalidades
- **Comportamento esperado:** Navegação autônoma, comparação de opções
- **Objetivos:** Redução de suporte humano, upsell, fidelização

### 🛒 Varejo

- **Componentes-chave:** Lista de produtos, filtros, carrinho, botão comprar
- **Layout:** Grid visual, promoções evidentes
- **Comportamento esperado:** Navegação rápida, senso de urgência
- **Objetivos:** Conversão, recompra, experiência intuitiva

## 04 - Fluxos e Jornadas UX

### Objetivo – Fluxos e Jornadas

Catalogar fluxos e jornadas comuns em produtos digitais, adaptados a cada indústria e otimizados para usabilidade, eficiência e clareza. Esses fluxos servirão de base para os protótipos gerados pelo agente IA.

## 🔁 Fluxos Universais (Comuns a Todas as Indústrias)

Estes fluxos são aplicáveis à maioria dos produtos digitais e devem ser priorizados como templates básicos:

### 1. Login/Autenticação

- **Componentes:** E-mail, senha, botão entrar, recuperação de senha
- **Variações:** MFA, biometria, autenticação via token (ex: bancos)

### 2. Cadastro de Conta

- **Componentes:** Nome, e-mail, senha, confirmação, aceite de termos
- **Requisitos adicionais:** CPF, endereço ou telefone em setores regulados

### 3. Onboarding

- **Componentes:** Slides, configuração inicial, questionário de perfil
- **Objetivo:** Personalizar a experiência inicial com base no usuário

### 4. Navegação Principal

- **Componentes:** Menu, busca, categorias, filtros
- **Aplicação:** Estrutura base de navegação presente em todo sistema

### 5. Dashboard/Área Logada

- **Componentes:** KPIs, cards informativos, histórico de ações
- **Adaptação:** Exibir dados contextuais da indústria (financeiros, operacionais, acadêmicos, etc.)

### 6. Suporte/Atendimento

- **Componentes:** Chat, botão de ajuda, FAQ
- **Objetivo:** Reduzir fricções durante a jornada e evitar abandonos

## 🌐 Fluxos Especializados por Jornada e Indústria

### Check-out / Pagamento

- **Etapas:** Carrinho > Endereço > Pagamento > Confirmação
- **Variações:**
  - Varejo: 1 clique, cupom
  - Saúde: upload de receita

### Busca e Filtros

- **Componentes:** Barra de busca com sugestão, filtros removíveis
- **Aplicações específicas:**
  - Mídia: filtros por editoria
  - Logística: status de entrega

### Agendamento

- **Componentes:** Calendário, horários disponíveis, confirmação
- **Indústrias:** Saúde, Esportes, Educação, Serviços Técnicos

### Avaliação/Feedback

- **Componentes:** Estrelas, comentários, NPS
- **Indústrias:** Educação, Varejo, Telecom, Serviços

## 🧠 Recomendações para o Agente

- Sugira fluxos universais como base, adaptando-os com variações por indústria
- Limitar jornadas a 5 etapas visuais no máximo
- Incluir elementos de progressão (barra, indicadores, breadcrumbs)
- Fluxos críticos devem ter confirmação dupla ou etapas de revisão

## 🔍 Priorização por Indústria

| **Indústria** | **Fluxos Prioritários** |
| --- | --- |
| Bancos | Login seguro, transações, dashboards |
| Varejo | Check-out, busca, recomendação |
| Saúde | Agendamento, histórico clínico |
| Educação | Onboarding, progresso, avaliações |
| Logística | Rastreamento, dashboards operacionais |

## 05 - Referências e Benchmarking

### Objetivo – Referências

Fornecer um conjunto de referências visuais e funcionais que o agente IA pode consultar para validar decisões de design, inspirar fluxos e componentes e comparar boas práticas por indústria.

## 🔍 Estratégia de Benchmarking

- O agente deve sugerir benchmarks relevantes com base na indústria e objetivo do projeto.
- Referências podem incluir produtos reais, relatórios de pesquisa, estudos de caso e padrões estabelecidos.
- As recomendações devem ser baseadas em critérios como: usabilidade, acessibilidade, eficiência, conversão e consistência visual.

## 📚 Referências por Indústria

### 🛒 Varejo (Referências)

- **Amazon:** Check-out rápido, sugestões baseadas em comportamento
- **Mercado Livre:** Reputação do vendedor, busca eficiente
- **Fonte:** Baymard Institute – UX de E-commerce ([https://baymard.com/](https://baymard.com/))

### 💳 Bancos (Referências)

- **Nubank:** Simplicidade, clareza e confiança
- **Itaú:** Navegação estruturada por produto
- **Fonte:** BBVA UX Strategy ([https://www.bbva.com/en/design/](https://www.bbva.com/en/design/))

### 🏥 Saúde (Referências)

- **Dr. Consulta:** Agendamento prático e amigável
- **Fleury:** Layout limpo para exames e resultados
- **Fonte:** IDEO – Design for Health ([https://www.ideo.com/work/designing-for-health](https://www.ideo.com/work/designing-for-health))

### 📚 Educação (Referências)

- **Duolingo:** Gamificação e progressão motivacional
- **Khan Academy:** Conteúdo modular e didático
- **Fonte:** UX Collective – UX em Educação ([https://uxdesign.cc/tagged/education](https://uxdesign.cc/tagged/education))

### 📰 Mídia

- **GloboPlay:** Recomendação personalizada e destaque editorial
- **The New York Times:** Tipografia e legibilidade
- **Fonte:** Nielsen Norman Group – UX para News ([https://www.nngroup.com/topic/news/](https://www.nngroup.com/topic/news/))

### 💻 Software e Plataformas (Referências)

- **Notion:** Modularidade e simplicidade
- **Slack:** Comunicação fluida e centrada na produtividade
- **Fonte:** Figma Community & Atlassian Design Guidelines

### 🚚 Logística (Referências)

- **Uber:** Feedback em tempo real, mapa e status visual
- **Loggi:** Rastreamento detalhado por etapa
- **Fonte:** UX Planet – Logistics UX

### 🏭 Industrial (Referências)

- **Siemens:** Interfaces para ambientes industriais críticos
- **GE Predix:** Painéis de controle e IoT
- **Fonte:** UXMatters – Industrial Interfaces ([https://www.uxmatters.com/](https://www.uxmatters.com/))

## 🧠 Como o Agente Deve Utilizar

- **Durante geração de protótipos:** Sugerir visual ou fluxo com base em benchmark reconhecido
- **Durante explicação de decisão de design:** Referenciar boas práticas ou padrões consagrados
- **Durante testes com usuário:** Propor variações com base em soluções já validadas por grandes players

## 🏷️ Tags recomendadas por tipo de benchmark

| Tag | Quando usar |
| --- | --- |
| #conversao | Telas com foco em finalização de ação |
| #acessibilidade | Ajustes para público amplo ou sensível |
| #retencao | Elementos que promovem continuidade de uso |
| #velocidade | Interfaces leves e diretas |
| #confiança | Setores regulados ou com dados sensíveis |

## 06 - Métricas e Avaliação UX/UI

### Objetivo – Métricas

Definir um conjunto de métricas que o agente IA deve utilizar para avaliar a qualidade de uma interface ou fluxo gerado, considerando aspectos de usabilidade, desempenho, acessibilidade, conversão e satisfação do usuário.

## 📊 Métricas Quantitativas

### 1. Taxa de Conversão (CR)

- **Uso:** Avaliar se os usuários concluem o objetivo principal (ex: compra, cadastro)
- **Aplicável a:** Varejo, Serviços, Plataformas

### 2. Taxa de Abandono

- **Uso:** Identificar pontos de fricção ou desistência durante o fluxo
- **Aplicável a:** Check-out, formulários, onboarding

### 3. Tempo Médio por Tarefa

- **Uso:** Medir eficiência do fluxo. Tempo ideal varia conforme contexto
- **Aplicável a:** Dashboards, transações, consultas

### 4. Número de Erros

- **Uso:** Quantidade de mensagens de erro ou ações inválidas
- **Aplicável a:** Formulários, login, sistemas críticos

### 5. Retenção (D1, D7, D30)

- **Uso:** Avaliar engajamento e fidelização
- **Aplicável a:** Mídia, Educação, Apps recorrentes

### 6. NPS (Net Promoter Score)

- **Pergunta:** "Você recomendaria este serviço a um amigo?"
- **Mede:** Satisfação geral e fidelidade

## 📋 Métricas Qualitativas

### 1. Clareza Visual

- **Critérios:** Hierarquia, contraste, legibilidade, foco na ação

### 2. Coerência de Componentes

- **Critérios:** Uso padronizado de botões, campos e interações

### 3. Facilidade de Navegação

- **Critérios:** Lógica da arquitetura da informação, profundidade de cliques

### 4. Acessibilidade Perceptível

- **Critérios:** Legibilidade mínima, navegação por teclado, contraste de cor

### 5. Satisfação da Jornada

- **Critérios:** Feedback do usuário após completar ações-chave

## 🧠 Avaliação Automática pelo Agente

O agente pode atribuir uma **pontuação UX entre 0–100** com base em:

- Conformidade com guidelines visuais e de acessibilidade
- Aplicação correta de componentes por contexto
- Redução de fricções na navegação
- Uso de padrões reconhecidos e benchmarking

### Exemplo de Pontuação por Critério

| Critério | Peso (%) |
| --- | --- |
| Acessibilidade | 25% |
| Clareza e hierarquia visual | 20% |
| Consistência de componentes | 15% |
| Eficiência do fluxo | 20% |
| Aderência a benchmarks | 20% |

## 🧠 Relevância por Indústria

| Indústria | Métricas mais críticas |
| --- | --- |
| Bancos | Erros, tempo por tarefa, clareza visual |
| Varejo | Conversão, abandono de carrinho |
| Saúde | Acessibilidade, clareza, confiança |
| Educação | Retenção, satisfação, tempo médio por aula |
| Mídia | Engajamento, retenção, tempo por sessão |

## 07 - Regras e Exceções para o Agente IA

### Objetivo – Regras e Exceções

Definir o comportamento do agente especialista em design quando confrontado com ambiguidade, cenários incomuns, dados incompletos ou solicitações fora do padrão. Também inclui instruções para adaptação contínua com base no feedback.

## ⚙️ Regras Gerais de Comportamento

### 1. Priorização por contexto

- Sempre priorizar o **objetivo principal do usuário** sobre padrões visuais genéricos
- Exemplo: Em banco, clareza e segurança > estética

### 2. Hierarquia de Decisão

1. Identificar indústria correta
2. Escolher categoria mais próxima
3. Sugerir fluxo com base no objetivo de negócio
4. Aplicar componentes e padrões visuais relevantes

### 3. Quando não houver dados suficientes

- O agente deve perguntar de forma orientada:
  - “Qual o objetivo principal desse produto?”
  - “Com qual empresa esse projeto mais se parece?”

### 4. Uso de linguagem e tom

- Adotar tom técnico, mas acessível.
- Evitar jargões sem explicação.
- Quando possível, contextualizar a escolha (ex: “Esse componente é ideal nesse cenário porque…”)

## ❗ Tratamento de Ambiguidades e Exceções

### Indústria híbrida

- Exemplo: sistema de logística para hospital
- Regra: adotar fluxos de logística com componentes visuais de saúde

### Multifunção ou multiserviço

- Exemplo: plataforma de educação com loja integrada
- Regra: classificar por objetivo predominante e tratar funções secundárias com guidelines complementares

### Componentes não padronizados

- Regra: sugerir criação de novo componente baseado em combinação de elementos já existentes
- O agente deve justificar a escolha (Ex: "Não há componente nativo, mas podemos adaptar X com Y")

### Usuário solicita algo visualmente problemático

- Exemplo: cor com baixo contraste, fontes pequenas
- Regra: alertar o usuário e propor alternativa com justificativa de acessibilidade/usabilidade

## 🔄 Aprendizado Contínuo

- Registrar feedbacks manuais (positivo e negativo) dos protótipos gerados
- Aprender com padrões frequentes de edição feitos por humanos
- Adaptar sugestões futuras com base em correções históricas

## 🧠 Estratégias Avançadas para Cenários Complexos

### 1. Uso de Personas

- Quando possível, simular uso a partir de persona base (ex: consumidor final, gestor, operador)

### 2. Decisão por Objetivo de Negócio

- Se múltiplos caminhos forem possíveis, o agente deve filtrar por intenção:
  - “Esse fluxo visa aumentar conversão, reduzir custo ou melhorar experiência?”

### 3. Modularização

- Quando o escopo for muito amplo, o agente deve sugerir dividir o projeto em módulos e tratá-los separadamente

## ✅ Checklist Final de Conformidade (por sugestão gerada)

- [ ]  Indústria e categoria compatíveis
- [ ]  Fluxo alinhado ao objetivo do usuário
- [ ]  Componentes consistentes com guidelines
- [ ]  Acessibilidade considerada
- [ ]  Benchmark usado (quando aplicável)
- [ ]  Métricas atribuídas
