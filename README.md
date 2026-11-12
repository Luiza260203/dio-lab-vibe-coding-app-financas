# 💸 App de Controle Finnceiro

PRD refinado no Copilot

````
# PRD — Agente Financeiro IA

## Princípio Fundamental

Toda a solução deve seguir os princípios de Design Universal, priorizando simplicidade, acessibilidade, clareza de linguagem, compatibilidade com tecnologias assistivas e baixa carga cognitiva.

O produto deve ser utilizável por iniciantes, idosos, pessoas com diferentes níveis de alfabetização digital e usuários com necessidades de acessibilidade, sem exigir treinamento prévio.

---

# 1. Visão Geral do Produto

## Nome Provisório

Agente Financeiro IA

## Objetivo

Criar uma aplicação de finanças pessoais baseada em conversas em linguagem natural, permitindo que usuários registrem gastos, acompanhem metas financeiras e recebam recomendações de economia sem precisar preencher formulários complexos.

O produto deve transformar o controle financeiro em uma experiência simples, acessível e humanizada através de um agente conversacional inteligente.

---

# 2. Problema

Muitas pessoas abandonam aplicativos financeiros porque:

- Exigem cadastro manual de despesas.
- Possuem interfaces complexas.
- Não oferecem orientação personalizada.
- Geram excesso de informações difíceis de interpretar.

Como consequência, usuários iniciantes não conseguem criar o hábito de acompanhar sua vida financeira.

---

# 3. Público-Alvo

## Público Primário

Pessoas entre 18 e 45 anos que desejam organizar suas finanças pessoais, mas possuem pouco conhecimento financeiro.

## Características

- Utilizam aplicativos de mensagens diariamente.
- Preferem experiências simples e intuitivas.
- Não gostam de planilhas.
- Desejam economizar e alcançar metas financeiras.
- São iniciantes em educação financeira.

---

# 4. Proposta de Valor

"O jeito mais simples de organizar suas finanças: converse, registre e receba orientação personalizada."

## Diferenciais

- Registro por conversa em linguagem natural.
- Classificação automática de gastos.
- Feedback financeiro instantâneo.
- Recomendações práticas de economia.
- Visualizações simples e fáceis de entender.

---

# 5. Funcionalidades do MVP

## F1. Registro de Gastos via Conversa

O usuário poderá escrever mensagens como:

"Gastei R$ 35 com almoço."

"Paguei R$ 120 de internet."

O sistema deverá identificar:

- Valor
- Categoria
- Data
- Descrição

E registrar automaticamente a transação.

---

## F2. Classificação Automática

Categorias iniciais:

- Alimentação
- Transporte
- Moradia
- Saúde
- Educação
- Lazer
- Compras
- Outros

A IA deverá sugerir automaticamente uma categoria para cada transação registrada.

---

## F3. Histórico Financeiro

O usuário poderá fazer consultas como:

- Quanto gastei este mês?
- Quanto gastei com alimentação?
- Quais foram meus maiores gastos?

O sistema deverá responder em linguagem natural.

---

## F4. Metas Financeiras

Permitir a criação de metas como:

- Economizar R$ 5.000
- Criar reserva de emergência
- Comprar um notebook
- Fazer uma viagem

O sistema deverá exibir:

- Valor da meta
- Valor acumulado
- Percentual concluído
- Previsão de conclusão

---

## F5. Agente Financeiro

Gerar sugestões automáticas baseadas no comportamento financeiro do usuário.

Exemplos:

- Você gastou 20% mais com delivery nesta semana.
- Se reduzir R$ 10 por dia em alimentação, economizará R$ 300 por mês.
- Sua meta de viagem está 65% concluída.

---

## F6. Relatórios Simplificados

Exibir:

- Gastos por categoria
- Evolução mensal
- Metas financeiras
- Resumo do mês
- Insights gerados pela IA

---

# 6. Principais Telas

## Tela 1 — Onboarding

Objetivos:

- Explicar o funcionamento do aplicativo.
- Criar perfil inicial.

Dados:

- Nome
- Objetivo financeiro principal

---

## Tela 2 — Chat Principal

Elementos:

- Histórico de mensagens
- Campo de entrada
- Sugestões rápidas

Ações rápidas:

- Registrar gasto
- Ver relatório
- Criar meta
- Receber dicas

---

## Tela 3 — Histórico Financeiro

Exibir:

- Lista de transações
- Busca
- Filtros por período
- Filtros por categoria

---

## Tela 4 — Metas Financeiras

Exibir:

- Lista de metas
- Progresso individual
- Valores acumulados
- Percentuais concluídos

---

## Tela 5 — Dashboard

Exibir:

- Gastos do mês
- Principais categorias
- Economia acumulada
- Metas em andamento
- Insights gerados pela IA

---

# 7. Fluxo Principal do Usuário

## Primeiro Acesso

1. Usuário cria perfil.
2. Define seu principal objetivo financeiro.
3. Acessa o chat.

## Registro de Despesa

1. Usuário envia mensagem.
2. IA interpreta o texto.
3. Categoria é identificada.
4. Gasto é salvo.
5. Usuário recebe confirmação.

## Consulta Financeira

1. Usuário faz uma pergunta.
2. Sistema consulta o histórico.
3. Responde em linguagem natural.

---

# 8. Critérios de Sucesso do MVP

## Métricas

- 80% dos gastos registrados sem edição manual.
- Registro de despesa em menos de 15 segundos.
- Pelo menos 70% dos usuários criam uma meta financeira.
- Retenção superior a 30% após 7 dias.
- Taxa de satisfação superior a 80% nos testes iniciais.

---

# 9. Requisitos Técnicos

## Frontend

- Interface mobile-first.
- Design simples e amigável.
- Experiência semelhante a aplicativos modernos de chat.
- Compatibilidade com modos claro e escuro.

## Backend

- Cadastro de usuários.
- Base de dados para transações.
- Gestão de metas financeiras.
- Armazenamento seguro de informações.

## IA

Capacidade de extrair:

- Valor
- Categoria
- Data
- Descrição

Além disso:

- Responder perguntas financeiras.
- Gerar recomendações personalizadas.
- Utilizar linguagem simples e acessível.

---

# 10. Design Universal e Acessibilidade

## Objetivo

Garantir que a aplicação ofereça boa experiência para o maior número possível de usuários.

## Diretrizes

### Simplicidade

- Linguagem sem jargões.
- Fluxos curtos.
- Navegação intuitiva.

### Comunicação Multimodal

- Texto e ícones.
- Texto e gráficos.
- Feedback visual e textual.

### Legibilidade

- Alto contraste.
- Fontes adequadas.
- Espaçamento confortável.
- Não depender apenas de cores para transmitir informações.

### Linguagem Inclusiva

O agente deve:

- Explicar conceitos financeiros quando necessário.
- Adaptar respostas para iniciantes.
- Evitar termos excessivamente técnicos.

### Mobile First

A experiência principal deve funcionar perfeitamente em smartphones.

### Acessibilidade Digital

Garantir:

- Compatibilidade com leitores de tela.
- Navegação por teclado.
- Labels descritivos.
- Textos alternativos em gráficos e imagens.
- Contraste compatível com WCAG.
- Indicadores visuais de foco e seleção.

### Redução de Carga Cognitiva

- Exibir apenas informações relevantes.
- Evitar telas sobrecarregadas.
- Priorizar clareza sobre quantidade de dados.

## Critério de Aceitação

Um usuário sem experiência prévia em aplicativos financeiros deve conseguir:

- Registrar um gasto.
- Consultar gastos.
- Criar uma meta.
- Entender o resumo financeiro do mês.

Sem necessitar de treinamento ou ajuda externa.

---

# 11. Restrições do MVP

Não incluir nesta primeira versão:

- Open Finance
- Integrações bancárias
- Investimentos
- Importação automática de extratos
- Cartão de crédito automatizado
- Compartilhamento entre usuários
- Planejamento tributário

---

# 12. Plano de Validação Inicial

## Hipótese Principal

Usuários preferem registrar despesas por conversa em linguagem natural em vez de utilizar formulários tradicionais.

## Teste

Recrutar de 5 a 10 usuários iniciantes e acompanhar o uso durante 7 dias.

## Avaliar

- Facilidade de uso
- Tempo para registrar gastos
- Precisão da categorização
- Utilidade das recomendações
- Intenção de uso contínuo

## Critério de Validação

Pelo menos 70% dos participantes devem afirmar que a experiência conversacional é mais simples que os aplicativos financeiros já utilizados.

---

# Entregável Esperado da IA

Gerar:

- Estrutura completa do MVP
- Principais telas
- Arquitetura básica da solução
- Fluxos do usuário
- Modelo de dados inicial
- Estratégia de validação
- Sugestões de UX alinhadas com Design Universal

Toda a comunicação deve utilizar linguagem simples, educativa e em português do Brasil.
````
Interações com o App Base44

> Crie um App de Finanças Pessoais com base no seguinte PRD (Product Requirements Document): {PRD}

<img width="1867" height="957" alt="image" src="https://github.com/user-attachments/assets/48241192-bf73-41e8-8187-3d46a3c4d874" />

  
# Agente Financeiro IA

Aplicativo de organização financeira pessoal baseado em conversas em linguagem natural, desenvolvido para ajudar usuários iniciantes a controlar gastos, acompanhar metas e receber orientações financeiras de forma simples, acessível e intuitiva.

## Objetivo

Transformar o controle financeiro em uma experiência natural e amigável, eliminando a necessidade de planilhas complexas e formulários extensos.

O usuário pode conversar com o sistema para registrar despesas, acompanhar objetivos financeiros e receber recomendações personalizadas para melhorar sua saúde financeira.

---

## Principais Funcionalidades

### Dashboard Financeiro

Visualização simplificada da situação financeira do usuário.

Funcionalidades:

- Resumo dos gastos do mês
- Total de receitas registradas
- Saldo disponível
- Indicador de utilização do orçamento
- Visão geral da situação financeira

Benefício:

Permite compreender rapidamente a situação financeira atual.

---

### Registro de Gastos por Conversa

Cadastro de despesas utilizando linguagem natural.

Exemplos:

- "Gastei R$ 35 com almoço"
- "Paguei R$ 120 de internet"
- "Comprei roupas por R$ 90"

O sistema identifica automaticamente:

- Valor
- Categoria
- Descrição
- Data

Benefício:

Reduz o esforço necessário para registrar movimentações financeiras.

---

### Histórico Financeiro

Consulta de todas as movimentações registradas.

Funcionalidades:

- Visualização de gastos e receitas
- Consulta de registros anteriores
- Organização cronológica das transações
- Acompanhamento da movimentação financeira

Benefício:

Mantém o usuário informado sobre seu histórico financeiro.

---

### Metas Financeiras

Criação e acompanhamento de objetivos financeiros.

Funcionalidades:

- Cadastro de metas
- Indicador de progresso
- Percentual de conclusão
- Valor acumulado
- Valor alvo

Exemplos de metas:

- Reserva para imprevistos
- Reserva de emergência
- Viagem
- Compra de equipamentos
- Fundo para estudos

Benefício:

Estimula hábitos financeiros saudáveis e planejamento de longo prazo.

---

### Relatórios Financeiros

Análise simples dos dados financeiros.

Funcionalidades:

- Distribuição de gastos por categoria
- Visualização dos principais gastos
- Resumos mensais
- Indicadores financeiros simplificados

Benefício:

Ajuda o usuário a compreender para onde o dinheiro está sendo direcionado.

---

### Agente Financeiro Inteligente

Sistema de recomendações personalizadas baseado no comportamento financeiro registrado.

Funcionalidades:

- Geração automática de insights
- Sugestões de economia
- Alertas sobre padrões de gastos
- Recomendações relacionadas às metas financeiras

Exemplos:

- Identificação de gastos elevados em determinada categoria
- Sugestões para reduzir despesas recorrentes
- Recomendações para acelerar o alcance de metas

Benefício:

Transforma dados financeiros em orientações práticas.

---

## Navegação

Estrutura principal do aplicativo:

- Início
- Conversar
- Histórico
- Metas
- Relatórios

Objetivo:

Facilitar a navegação e reduzir a carga cognitiva do usuário.

---

## Design Universal

O aplicativo foi desenvolvido seguindo princípios de Design Universal para garantir acessibilidade e facilidade de uso para o maior número possível de pessoas.

### Simplicidade

- Linguagem clara
- Fluxos curtos
- Navegação intuitiva

### Legibilidade

- Alto contraste
- Tipografia de fácil leitura
- Espaçamento adequado

### Acessibilidade

- Compatibilidade com navegação por teclado
- Estados visuais claros
- Componentes com áreas de toque ampliadas
- Estrutura preparada para tecnologias assistivas

### Mobile First

- Experiência otimizada para smartphones
- Interface responsiva
- Uso confortável em dispositivos móveis

---

## Diferenciais

- Registro financeiro por conversa
- Categorização automática de despesas
- Metas financeiras integradas
- Insights inteligentes
- Interface simples para iniciantes
- Design acessível e inclusivo
- Baixa curva de aprendizado

---

## Público-Alvo

Pessoas que desejam organizar suas finanças de maneira simples e prática, especialmente:

- Iniciantes em educação financeira
- Usuários que não gostam de planilhas
- Pessoas que preferem experiências conversacionais
- Usuários que buscam acompanhamento financeiro sem complicação

---

## Status do Projeto

MVP funcional desenvolvido com foco em:

- Controle financeiro simplificado
- Experiência conversacional
- Design Universal
- Educação financeira prática
- Boa experiência para usuários iniciantes

**reflexão sobre o processo**:

## O que funcionou bem?  
O refinamento do PRD previamente feito no Copilot ajudou muito, pois os créditos do Base44 acabaram em 1 alteração. 

## O que não funcionou como o esperado?
Esperava poder finalizar a primeira versão do app no Lovable, mas os créditos acabaram antes mesmo de finalizar o primeiro protótipo. Tentei então criar no Base44. Neste, esperava poder interagir mais vezes gratuitamente com o Base44, não foi possível fazer alterações posteriores no protótipo, mas a primeira versão do app já contava com funcionalidades desejadas, como criar metas a partir do próprio chat, interface de gráficos, relatórios, etc.

## O que aprendeu sobre conversar com IAs?
Aprendi que é basicamente igual a conversar com uma pessoa confiável e muito inteligente, quanto mais detalhes e clareza você dá, melhor é a interação e os resultados gerados.

