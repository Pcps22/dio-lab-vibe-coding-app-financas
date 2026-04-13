# 💸 App de Assistente financeiro pessoal com Vibe Coding

Aprenda a **criar soluções com IA** de forma criativa, guiando ferramentas como o **Copilot** e o **Lovable** com uma comunicação simples e natural. O foco é desenvolver o conceito de um **App de Organização de Finanças Pessoais**, mas, acima de tudo, aprender o **jeito Vibe de programar com IA**.

## ✨ O que é Vibe Coding

**Vibe Coding** é uma forma leve e criativa de desenvolver com IA, baseada em **conversas naturais e bem estruturadas**. Você não precisa escrever código linha por linha. Em vez disso, aprende a **guiar a IA** descrevendo suas ideias de forma clara, com **intenção e contexto**. Em outras palavras:

> Você mostra a vibe da sua ideia e a IA transforma em solução (ou em um caminho para ela).

## 🎯 Desafio

Problema: Muitas pessoas não conseguem manter um controle financeiro porque os aplicativos exigem muita entrada de dados manual, e a criação de orçamentos é vista como algo tedioso. 

Precisamos de uma solução que permita **controlar as finanças por meio de uma conversa simples**, com **agentes de IA** capazes de criar **planos de economia personalizados e automatizados**. Você deve utilizar as ideias de **Vibe Coding** e **MVP (Produto Mínimo Viável)** para desenvolver o **conceito de um aplicativo** que resolva o problema citado.

> [!IMPORTANT]
> Você **não precisa construir o código**! O foco está em **usar a IA como sua parceira criativa**, transformando boas ideias e prompts em conceitos funcionais que simulam um produto real.

## 🪄 Etapas do Desafio

### 1. Saber o que Pedir é a Chave! Otimize seus Prompts!

Antes de pedir para a IA "criar um app", é importante definir com clareza o que você quer construir e por quê. Para isso, você vai criar um **PRD (Product Requirements Document)** simplificado, uma especificação que serve como _briefing_ para a IA entender sua ideia.

Um bom PRD deve descrever o problema, quem será beneficiado, as principais funcionalidades e o que você espera que a IA entregue. Use o modelo abaixo como ponto de partida e adapte conforme o seu estilo:

```txt
# Contexto
Quero criar um aplicativo de Organização de Finanças Pessoais que funcione por meio de conversas com o usuário.  
A ideia é facilitar o controle financeiro de forma simples e natural, sem formulários manuais ou planilhas complexas.

# Problema
Muitas pessoas desistem de controlar seus gastos porque os apps atuais exigem muita entrada manual e pouca personalização.  
Quero resolver isso com uma experiência de conversa e recomendações automáticas de economia.

# Público-Alvo
Pessoas que querem começar a organizar suas finanças de forma prática e sem complicação, principalmente iniciantes.

# Funcionalidades-Chave
1. Registrar gastos via chat em linguagem natural.  
2. Classificar automaticamente as transações.  
3. Definir e acompanhar metas financeiras.  
4. Receber dicas de economia do “Agente Financeiro”.  
5. Visualizar relatórios simples e personalizados.

# Entregável da IA
Gerar um plano de MVP com as principais telas, recursos necessários e um esboço de validação inicial.  
Usar tom educativo e linguagem acessível, em português.
```

Depois de preencher o modelo, use o Copilot Web para revisar e melhorar o seu prompt antes de ir ao Lovable. A ideia é lapidar o texto até que ele fique claro, direto e reflita exatamente a sua intenção.

> [!TIP]
> Pense no PRD/Prompt como “o briefing que a IA precisa para entender sua vibe”. Portanto, quanto mais claro e intencional for o texto, mais próximas do ideal serão as respostas da IA.

### 2. Explorando o Lovable na Prática

Com seu PRD pronto e revisado, é hora de colocar a IA em ação. Abra o Lovable, cole seu prompt completo e peça o plano inicial do MVP do seu aplicativo. Como o plano gratuito limita você a 5 interações por dia, seja estratégico:
- Faça perguntas diretas e construtivas, como “crie o fluxo de telas com base nas funcionalidades listadas” ou “gere uma versão resumida do plano de MVP”;
- Priorize clareza nas instruções para aproveitar ao máximo cada resposta;

Durante essa etapa, você pode orientar a IA para três entregas principais:
1. Agente Financeiro: defina o comportamento e o tom de voz de um consultor financeiro pessoal, alinhado ao público e objetivo do app.
2. Fluxo de Telas: peça à IA para gerar o fluxo conceitual de telas com base nas funcionalidades descritas no PRD, simulando a interação por conversa.
3. Plano de MVP: solicite um resumo das 5 funcionalidades principais, dos recursos necessários e um plano de validação inicial (como medir se o app cumpre seu propósito).

> [!TIP]
> Se preferir, você pode fazer tudo com o **Copilot**. O importante é exercitar a habilidade de transformar intenções em instruções claras e testar os limites da IA como parceira criativa.

### 3. Entregando o Desafio na DIO

Finalize seu projeto criando um **repositório no GitHub** (pode ser um **fork** deste).  
No README do seu repositório, inclua:

- Seu **prompt final** (PRD);
- ´´´
- {# PRD – Assistente Financeiro Conversacional com Open Finance Seguro

[product]
name = "Assistente Financeiro Conversacional"
goal = "Organizar finanças pessoais via conversa, com automação por Open Finance e arquitetura segura e escalável."

[context]
problem = """
Pessoas desistem de controlar finanças porque apps exigem muita entrada manual, pouca personalização e relatórios complexos.
"""
solution = """
Um agente financeiro conversacional que entende linguagem natural, registra e classifica gastos automaticamente, integra Open Finance, sugere metas, dá dicas e mostra relatórios simples.
"""
target_audience = """
Iniciantes em organização financeira, pessoas que querem praticidade, sem planilhas e sem complexidade técnica.
"""

[vision]
value_proposition = """
Experiência de chat simples + motor financeiro profissional (estilo Dashplan/Grão) + dados automáticos via Open Finance (Pluggy-like) + arquitetura segura (modelo vibecode).
"""

########################################################
# 1. FUNCIONALIDADES DO MVP
########################################################

[features.chat]
description = "Interface principal baseada em conversa com o usuário."
capabilities = [
  "Registrar gastos via linguagem natural.",
  "Consultar saldo, gastos, categorias, metas.",
  "Explicar relatórios em linguagem simples.",
  "Sugerir metas e ajustes de orçamento.",
  "Alertar sobre gastos excessivos ou desvios."
]
examples = [
  "Gastei 35 reais no iFood ontem.",
  "Quanto gastei com Uber este mês?",
  "Estou gastando mais do que ganho?",
  "Quanto posso investir sem apertar meu mês?"
]

[features.open_finance]
description = "Integração com provedor Open Finance (ex.: Pluggy) via serviço de integração isolado."
capabilities = [
  "Conectar contas bancárias, cartões e investimentos.",
  "Importar transações, saldos e posições de investimento.",
  "Sincronização inicial (primeira carga).",
  "Sincronização incremental (novas transações).",
  "Sincronização manual (botão atualizar).",
  "Sincronização automática (jobs agendados)."
]
constraints = [
  "Nunca expor tokens ou credenciais no front-end.",
  "Guardar apenas IDs de conexão e metadados necessários.",
  "Toda comunicação com o provedor é feita pelo back-end."
]

[features.transactions]
description = "Gestão de lançamentos financeiros."
capabilities = [
  "Registro manual via chat ou formulário simples.",
  "Registro automático via Open Finance.",
  "Classificação automática por categoria.",
  "Uso de tags (ex.: Uber, iFood, gasolina).",
  "Edição e reclassificação via chat.",
  "Filtros básicos por período, categoria e conta."
]

[features.goals]
description = "Metas financeiras simples e práticas."
capabilities = [
  "Sugestão automática de metas com base no histórico.",
  "Metas por categoria (ex.: alimentação, transporte).",
  "Acompanhamento mensal de metas.",
  "Alertas de estouro de meta.",
  "Projeção de economia mensal e anual."
]

[features.reports]
description = "Relatórios simples e personalizados."
capabilities = [
  "Resumo mensal: entradas, saídas, saldo.",
  "Gastos por categoria.",
  "Evolução mensal de gastos e saldo.",
  "Resumo de metas: atingidas, em risco, estouradas.",
  "Consultas via chat (ex.: 'como está meu mês?')."
]

[features.security]
description = "Arquitetura segura, multi-usuário e auditável (modelo vibecode)."
principles = [
  "Isolamento de camadas (Auth, API, Integração, Banco, Front).",
  "Zero trust interno entre serviços.",
  "Criptografia em trânsito (HTTPS) e em repouso (campos sensíveis).",
  "Multi-tenant desde o início (tudo filtrado por user_id).",
  "Logs e trilha de auditoria para ações financeiras.",
  "Gestão de segredos em serviço seguro (Vault/Secrets Manager)."
]

########################################################
# 2. ARQUITETURA DO SISTEMA
########################################################

[architecture.layers]

auth_service = """
Responsável por identidade e autenticação.
- Cadastro, login, logout.
- JWT + Refresh Token.
- Suporte futuro a MFA.
- Perfis: ROLE_USER, ROLE_ADMIN.
"""

domain_api = """
API de domínio financeiro (núcleo do produto).
- Lançamentos (transactions).
- Categorias e tags.
- Metas (goals).
- Plano financeiro (plan summary).
- Projeções simples (saldo projetado, economia).
- Investimentos (estrutura básica).
- Patrimônio (saldo consolidado).
- Proteção (estrutura inicial, opcional no MVP).
Não depende diretamente do provedor Open Finance.
"""

open_finance_service = """
Serviço de integração com provedor Open Finance (ex.: Pluggy).
- Adapter para mapear dados externos → modelo interno.
- Endpoints internos para:
  - Criar conexão (connection_id).
  - Listar contas, cartões, investimentos.
  - Importar transações.
- Jobs de sincronização (cron).
- Tratamento de erros e reconexões.
- Nunca expor tokens ao front.
"""

conversational_agent = """
Camada de inteligência conversacional.
- Interpretação de linguagem natural (NLP/NLU).
- Extração de entidades: valor, data, estabelecimento, categoria.
- Identificação de intenção: registrar gasto, consultar saldo, metas, relatórios.
- Motor de regras financeiras para:
  - Sugestão de metas.
  - Alertas de gastos.
  - Recomendações de economia.
- Geração de respostas em português, tom educativo e acessível.
"""

frontend = """
Interface do usuário (web ou mobile).
- Tela principal: Chat.
- Tela de Dashboard simples.
- Tela de Metas.
- Tela de Relatórios.
- Tela de Configurações (inclui conexão Open Finance).
"""

########################################################
# 3. MODELAGEM DE DADOS (RESUMO)
########################################################

[database.tables]

users = """
id (PK)
nome
email
senha_hash
data_criacao
"""

accounts = """
id (PK)
user_id (FK users)
nome
tipo (corrente, poupança, corretora)
instituicao
saldo_atual
data_atualizacao
"""

cards = """
id (PK)
user_id (FK users)
nome
instituicao
limite_total
limite_usado
data_atualizacao
"""

categories = """
id (PK)
user_id (FK users, permite categorias customizadas)
nome
tipo (obrigatória, não_obrigatória, renda, investimento, dívida, financiamento, empresa, neutra, projeto)
"""

tags = """
id (PK)
user_id (FK users)
nome
"""

transactions = """
id (PK)
user_id (FK users)
account_id (FK accounts, opcional)
card_id (FK cards, opcional)
category_id (FK categories, opcional)
tag_id (FK tags, opcional)
valor
data
tipo (entrada, saida)
descricao
estabelecimento
meio_pagamento
origem (manual, open_finance)
"""

goals = """
id (PK)
user_id (FK users)
categoria_id (FK categories)
valor_meta_mensal
ativo (bool)
"""

plan_summary = """
id (PK)
user_id (FK users)
renda_media
gastos_medios
saldo_plano
economia_mensal
economia_anual
data_referencia
"""

provider_connections = """
id (PK)
user_id (FK users)
provider_nome (ex.: pluggy)
external_connection_id
status
data_criacao
data_ultima_sincronizacao
"""

provider_accounts = """
id (PK)
user_id (FK users)
provider_connection_id (FK provider_connections)
external_account_id
tipo (conta, cartao, investimento)
instituicao
nome_exibicao
"""

provider_transactions = """
id (PK)
user_id (FK users)
provider_account_id (FK provider_accounts)
external_transaction_id
valor
data
descricao
categoria_raw
tipo_raw
"""

########################################################
# 4. FLUXOS PRINCIPAIS
########################################################

[flows.register_expense_via_chat]
steps = [
  "Usuário envia mensagem: 'Gastei 35 reais no iFood ontem.'",
  "NLP identifica intenção: registrar_gasto.",
  "Extrai entidades: valor=35, estabelecimento=iFood, data=ontem.",
  "Classificador sugere categoria: Alimentação.",
  "Cria registro em transactions com origem=manual.",
  "Agente responde: 'Anotado! R$ 35 em Alimentação (iFood, ontem)'."
]

[flows.import_open_finance]
steps = [
  "Usuário acessa Configurações > Conectar bancos.",
  "Front chama API de integração para iniciar fluxo com provedor.",
  "Provedor retorna connection_id.",
  "Serviço open_finance salva em provider_connections.",
  "Job ou endpoint importa contas, cartões, investimentos e transações.",
  "Dados são normalizados e salvos em accounts, cards, transactions.",
  "Agente notifica: 'Recebi novas transações das suas contas. Quer que eu categorize para você?'."
]

[flows.suggest_goals]
steps = [
  "Sistema calcula média de gastos por categoria nos últimos meses.",
  "Identifica categorias com potencial de economia.",
  "Sugere meta: ex.: reduzir alimentação de 1200 para 900.",
  "Usuário aceita ou ajusta.",
  "Meta é salva em goals.",
  "Agente acompanha progresso e alerta se estiver perto de estourar."
]

[flows.simple_report_via_chat]
steps = [
  "Usuário pergunta: 'Como está meu mês?'",
  "Sistema calcula: entradas, saídas, saldo, principais categorias.",
  "Agente responde com resumo em linguagem simples.",
  "Opcional: oferece link/botão para ver gráfico na tela de Relatórios."
]

########################################################
# 5. TELAS DO MVP
########################################################

[screens.chat]
name = "Tela de Chat (principal)"
elements = [
  "Área de mensagens (histórico).",
  "Campo de texto para o usuário digitar.",
  "Botão enviar.",
  "Sugestões rápidas (chips): 'Registrar gasto', 'Ver mês', 'Metas', etc."
]
behavior = [
  "Toda interação principal acontece aqui.",
  "Respostas do agente sempre em tom educativo e acessível."
]

[screens.dashboard]
name = "Dashboard simples"
elements = [
  "Entradas do mês.",
  "Saídas do mês.",
  "Saldo do mês.",
  "Resumo por categoria (top 3).",
  "Indicador simples: 'Você está dentro/fora do seu plano'."
]

[screens.goals]
name = "Metas"
elements = [
  "Lista de metas por categoria.",
  "Valor meta mensal.",
  "Valor gasto no mês.",
  "Progresso (%).",
  "Status: dentro, em risco, estourada."
]

[screens.reports]
name = "Relatórios"
elements = [
  "Gráfico de gastos por categoria.",
  "Gráfico de evolução mensal (entradas x saídas).",
  "Filtros básicos por período."
]

[screens.settings]
name = "Configurações"
elements = [
  "Conectar bancos (Open Finance).",
  "Preferências de notificação.",
  "Opções de segurança (logout, redefinir senha)."
]

########################################################
# 6. SEGURANÇA E MULTI-TENANT
########################################################

[security]
principles = [
  "Toda requisição à API exige autenticação (JWT).",
  "Toda consulta ao banco é filtrada por user_id.",
  "Dados sensíveis podem ser criptografados em repouso.",
  "Tokens e segredos nunca são armazenados em código.",
  "Logs não devem conter dados sensíveis (ex.: números completos de conta/cartão)."
]

[security.roles]
roles = [
  "ROLE_USER: acesso aos próprios dados.",
  "ROLE_ADMIN: acesso administrativo (monitoramento, suporte), sem ver dados sensíveis em texto puro."
]

########################################################
# 7. ROADMAP DO MVP
########################################################

[roadmap.phase1]
name = "Fundamentos"
items = [
  "Implementar Auth Service (login, cadastro, JWT).",
  "Criar banco de dados com tabelas principais (users, accounts, cards, transactions, categories, tags, goals).",
  "Implementar API de domínio básica (CRUD de lançamentos, categorias, metas)."
]

[roadmap.phase2]
name = "Open Finance"
items = [
  "Integrar com provedor Open Finance (ex.: Pluggy) via serviço separado.",
  "Criar tabelas de integração (provider_connections, provider_accounts, provider_transactions).",
  "Implementar fluxo de importação inicial e incremental.",
  "Criar endpoint para 'sincronizar agora'."
]

[roadmap.phase3]
name = "Agente Conversacional"
items = [
  "Implementar camada de NLP/NLU (intenção + entidades).",
  "Criar intents principais: registrar_gasto, consultar_mes, consultar_categoria, metas, ajuda.",
  "Conectar agente à API de domínio.",
  "Definir respostas padrão em português, tom educativo."
]

[roadmap.phase4]
name = "Interface MVP"
items = [
  "Tela de Chat.",
  "Dashboard simples.",
  "Tela de Metas.",
  "Tela de Relatórios.",
  "Tela de Configurações (conectar bancos)."
]

[roadmap.phase5]
name = "Validação"
items = [
  "Uso pessoal intensivo (você mesmo).",
  "Teste com 5–10 usuários próximos.",
  "Coletar feedback sobre clareza, utilidade e fluidez do chat.",
  "Ajustar classificação automática, metas e mensagens do agente."
]

########################################################
# 8. MÉTRICAS DE SUCESSO DO MVP
########################################################

[metrics]
items = [
  "% de mensagens entendidas corretamente pelo agente.",
  "% de transações classificadas automaticamente sem correção.",
  "Número médio de interações por usuário por semana.",
  "Número de metas criadas e acompanhadas.",
  "Retenção semanal (usuário volta a usar o app?)."
]

<img width="1917" height="865" alt="image" src="https://github.com/user-attachments/assets/3ddd2383-ff18-4416-a091-d55bcd9d5edf" />

- 
- 
- Um resumo do que o seu **App de Finanças Pessoais** faz;
- # FinChat – Resumo das Funcionalidades (MVP)

O **FinChat** é um assistente financeiro conversacional que ajuda pessoas a organizarem suas finanças de forma simples, via chat, com foco em iniciantes.

---

## 1. Chat Financeiro Inteligente (Core do Produto)

O chat é o centro da experiência:

- Registrar gastos em linguagem natural  
- Consultar informações financeiras  
- Perguntar sobre categorias, metas e relatórios  
- Receber alertas e recomendações  
- Obter explicações simples sobre o mês, gastos e hábitos  

**Exemplos de uso:**

- `Gastei 35 reais no iFood ontem`  
- `Quanto gastei com Uber este mês`  
- `Como está meu mês`  
- `Estou gastando mais do que ganho?`

---

## 2. Dashboard Financeiro

Resumo visual e simples do mês:

- Entradas  
- Saídas  
- Saldo  
- Gastos por categoria  
- Indicador de saúde financeira do mês (ex.: dentro/fora do plano)

---

## 3. Metas Financeiras

Ferramentas para ajudar o usuário a economizar:

- Criar metas por categoria  
- Acompanhar progresso mensal  
- Receber alertas ao se aproximar ou ultrapassar a meta  
- Receber sugestões de metas com base no comportamento de gastos

---

## 4. Relatórios

Relatórios simples e acessíveis:

- Gastos por categoria  
- Evolução mensal (entradas x saídas)  
- Comparação entre meses  
- Resumo de metas atingidas, em risco ou estouradas  

---

## 5. Configurações

Tela de configurações baseada na interface atual:

### 5.1. Perfil

- Exibição do e-mail do usuário  
- Gerenciamento básico de conta  

### 5.2. Categorias

- Criar categorias personalizadas  
- Definir tipo da categoria (ex.: obrigatória, não obrigatória)  
- Listar categorias criadas  

### 5.3. Open Finance (em breve)

- Área reservada para conexão com bancos via Open Finance  
- Mensagem informando que a funcionalidade estará disponível futuramente  

### 5.4. Logout

- Botão para sair da conta  

---

## 6. Arquitetura e Segurança

Baseado no modelo definido no PRD:

- Autenticação e banco com RLS (ex.: Supabase/Lovable Cloud)  
- Edge Functions para lógica de servidor  
- Agente conversacional via AI Gateway  
- Separação de camadas:
  - Frontend  
  - API de domínio  
  - Integração Open Finance  
  - Banco de dados  
- Preparado para multi-usuário  
- Dados sensíveis protegidos e acesso sempre filtrado por `user_id`

---

## 7. Open Finance (Planejado)

Funcionalidade planejada para versões futuras:

- Conectar contas bancárias  
- Importar transações automaticamente  
- Atualizar saldos periodicamente  
- Classificar transações importadas  
- Sincronização manual (botão) e automática (jobs agendados)

---

## 8. O que o MVP já entrega

- Chat funcional  
- Registro de gastos via conversa  
- Classificação básica de transações  
- Dashboard simples  
- Metas financeiras  
- Relatórios básicos  
- Categorias personalizadas  
- Autenticação e perfil  
- Estrutura preparada para integração com Open Finance  

---

## 9. Próximos Passos

- Implementar integração com agregador Open Finance (ex.: Pluggy)  
- Criar fluxo de sincronização automática de transações  
- Aprimorar a classificação automática  
- Adicionar projeções financeiras simples  
- Incluir dicas personalizadas do agente com base no comportamento real


- Uma breve **reflexão sobre o processo**:
  - O que funcionou bem?
  - O acesso ficou bom, com necessidade de validação de email.
  - O que não funcionou como o esperado?
  - Esperava que o agregador do open finance fosse mais pratico e simples
  - O que aprendeu sobre conversar com IAs?
  - è muito mais facil do que parece

> [!TIP]
> Publique seu repositório e compartilhe o link na plataforma da DIO! Sua entrega é a prova de que você domina o raciocínio de Vibe Coding, mesmo sem escrever uma única linha de código.

## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.
