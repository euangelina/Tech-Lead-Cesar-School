# 📘 Disciplina 01: Liderança e Gestão de Projetos (Guia IBPS)

## 1. 🎯 Questão Central (The Core Issue)
> **"Como um Tech Lead deve conduzir projetos de software da concepção à entrega, alinhando maturidade da equipe, governança de escopo/riscos, ecossistema de ferramentas e autonomia para garantir previsibilidade e geração contínua de valor?"**

---

## 2. 🌳 Árvore de Questões (Issue Tree — Princípio MECE)

O domínio da disciplina foi decomposto em **4 pilares mutuamente exclusivos e coletivamente exaustivos** que cobrem todas as decisões críticas de um Tech Lead:

```text
[Questão Central: Previsibilidade e Geração de Valor na Entrega de Projetos]
│
├── 1. Alinhamento de Liderança e Maturidade do Time (Pessoas & Estilo)
│   ├── 1.1. Qual estilo de liderança aplicar conforme o nível de competência e empenho da equipe (Hersey & Blanchard)?
│   ├── 1.2. Como ativar princípios situacionais (Integridade, Visão Compartilhada, Empoderamento) em crises vs. rotina?
│   └── 1.3. Como escalar a auto-organização e motivação intrínseca via Management 3.0 (Delegation Poker, Moving Motivators)?
│
├── 2. Governança do Ciclo de Vida, Escopo e Riscos (Processo & Execução)
│   ├── 2.1. Como estruturar a iniciação e o planejamento (EAP/WBS, Milestones, T-Shirt Sizing e Cronograma)?
│   ├── 2.2. Como gerenciar a Tríplice Restrição (Escopo, Prazo, Custo -> Qualidade) diante de mudanças frequentes?
│   └── 2.3. Como mitigar, evitar ou aceitar riscos técnicos e de negócio antes que paralisem a entrega?
│
├── 3. Ecossistema de Ferramentas e Visibilidade (Operação & Dados)
│   ├── 3.1. Qual stack de gestão (Jira, Azure DevOps, Trello/Asana) adequar ao porte e complexidade do projeto?
│   └── 3.2. Como integrar colaboração síncrona/assíncrona (Teams, Slack, Confluence) a indicadores executivos (Power BI)?
│
└── 4. Habilidades Essenciais e Gestão de Conflitos (Cultura & Segurança Psicológica)
    ├── 4.1. Como construir influência técnica sem depender exclusivamente de autoridade hierárquica?
    └── 4.2. Como diagnosticar a causa-raiz de conflitos e mediá-los usando Comunicação Não-Violenta (CNV)?
```

---

## 3. 🧪 Hipóteses de Trabalho, Anti-padrões e Casos Práticos

### Ramo 1: Liderança Situacional, Princípios e Management 3.0
* **Hipótese de Trabalho:** Se o Tech Lead calibrar seu nível de direção e apoio de acordo com a maturidade técnica e emocional da equipe — evoluindo de um modelo comando-controle (*Management 1.0*) para autonomia guiada (*Management 3.0*) —, o time ganha velocidade decisória sem perder alinhamento estratégico.
* **Anti-padrões Comuns:**
  * Aplicar microgestão (*Autocrático/Direção*) em times seniores sob pressão (gera desengajamento e gargalo no líder).
  * Dar liberdade total (*Laissez-Faire/Delegação*) para times juniores em domínios complexos como IA ou dados (gera paralisia e retrabalho).

#### Matriz de Decisão Aplicada (Cenários Práticos)

| Contexto / Cenário Real | Estilo & Princípios Recomendados | Ferramentas / Ações Práticas |
| :--- | :--- | :--- |
| **Time sênior em projeto complexo com prazo apertado** (ex.: *Cybersecurity* ou corte de prazo de 6 para 3 semanas) | **Transformacional** + **Autoconfiança, Comunicação Clara e Empoderamento** | Cortar escopo para MVP, blindar o time de reuniões burocráticas, *Daily* de 10 min focada em remoção de bloqueios e recompensa pós-crise. |
| **Time pouco experiente em domínio complexo** (ex.: sistema de IA / Big Data) | **Situacional (Diretiva + Orientadora)** | Quebra granular de tarefas, acompanhamento próximo, definição clara de expectativas e ambiente seguro para aprendizado contínuo. |
| **Time com conflitos internos e falha de comunicação** (ex.: projeto *Cloud*) | **Democrático + Situacional** + **Escuta Ativa** | Rituais de alinhamento, transparência nas decisões e mediação ativa para reconstruir confiança. |
| **Time multidisciplinar criando produto inovador** (ex.: app móvel) | **Democrático + Transformacional** + **Visão Compartilhada** | Uso de **OKRs** para alinhamento, **Moving Motivators** para engajamento individual e **Delegation Poker** para clarear fronteiras de autonomia. |

#### Evolução do Gerenciamento (Management 1.0 a 5.0)
* **Management 1.0:** Estrutura rígida, hierárquica e centralizada (*Comando e Controle*). Desafio: desmotivação e falta de espaço para iniciativa.
* **Management 2.0:** Gestão participativa, mas ainda com resquícios hierárquicos. Desafio: implementação inconsistente.
* **Management 3.0:** Gestão como prática de todos, foco em motivação intrínseca, colaboração e auto-organização. Ferramentas-chave: **Delegation Poker** (decidir, consultar, informar), **Moving Motivators** (10 motivadores intrínsecos), **Kudo Cards** e **OKRs**.
* **Management 4.0:** Liderança orientada por dados e tecnologias avançadas. Desafio: *reskilling* constante da força de trabalho.
* **Management 5.0:** Experiência humana no centro do trabalho. Desafio: equilibrar alta performance com cuidado genuíno pelas pessoas.

---

### Ramo 2: Governança do Ciclo de Vida, Escopo e Riscos
* **Hipótese de Trabalho:** A previsibilidade em projetos híbridos (planejamento macro preditivo + execução iterativa ágil) depende de decompor o escopo em pacotes entregáveis (**EAP/WBS**), vincular marcos verificáveis (**Milestones**) e tratar riscos de alto impacto com planos de contingência antes da execução.
* **Anti-padrões Comuns:**
  * Aceitar mudanças de escopo informalmente (*scope creep*) sem registrar impacto na Tríplice Restrição (*Escopo, Prazo, Custo e Qualidade*).
  * Listar riscos apenas como formalidade burocrática, sem definir estratégia (*Mitigar, Evitar, Aceitar*) nem dono da ação.

#### Modelo de Referência (Estudo de Caso: Projeto *Book Store*)
1. **Iniciação:** Definição do objetivo central, limites de escopo, mapeamento de *Stakeholders* (Equipe técnica, Usuários Finais PF/PJ, CEO/Negócio) e Termo de Abertura.
2. **Decomposição (EAP/WBS $\rightarrow$ Milestones):**
   * `M1`: Definição e aprovação de requisitos funcionais e não funcionais.
   * `M2`: Conclusão do desenvolvimento *core* da solução (MVP Front-end e Back-end).
   * `M3`: Implementação e integração funcional do Sistema de Recomendação.
   * `M4`: Conclusão dos testes de usabilidade, funcionais e de vulnerabilidade (QA).
   * `M5`: Lançamento da V0, Operação Assistida e Campanha de Marketing.
3. **Estimativa e Cronograma:** Dimensionamento macro via *T-Shirt Sizing* (`M` = 3 sem, `L` = 3–5 sem, `XL` = 6 sem) combinado com *Planning Poker* nas sprints e acompanhamento visual via Gráfico de Gantt.
4. **Matriz de Resposta a Riscos Técnicos:**
   * *Atraso na entrega de funcionalidades (Alta/Alta):* **Mitigar** revisando o cronograma semanalmente e repriorizando o backlog.
   * *Instabilidade de integração externa / Gateway de Pagamento (Média/Alta):* **Mitigar** implementando fila de contingência para processamento assíncrono.
   * *Falha de integração Front-end e Back-end (Média/Alta):* **Evitar** via contratos de API documentados, plano de testes integrados e alinhamento contínuo.
   * *Mudanças de especificação em voo (Alta/Média):* **Mitigar** isolando a nova demanda como *feature* versionada para *release* posterior.
   * *Dados insuficientes para treinar modelo de ML/IA (Média/Média):* **Aceitar** integrando algoritmo evolutivo que aprende continuamente em produção.
   * *Adaptação de novos membros no time (Baixa/Baixa):* **Aceitar** criando um *Onboarding Kit* estruturado.

---

### Ramo 3: Arquitetura de Ferramentas e Visibilidade
* **Hipótese de Trabalho:** A ferramenta de gestão não substitui o processo, mas o ecossistema escolhido deve espelhar a complexidade organizacional: ferramentas leves para descoberta/startups e plataformas rastreáveis conectadas a BI para ambientes *enterprise* multi-time.

#### Matriz de Seleção de Stack por Perfil de Projeto

| Perfil do Projeto | Gestão de Tarefas & Fluxo | Documentação & Suporte | Colaboração & BI Executivo |
| :--- | :--- | :--- | :--- |
| **Startup / App Móvel (Agilidade & Discovery)** | **Miro** (ideação/jornada) + **Trello / Asana** (Kanban leve) | Docs compartilhados | **Slack / Teams** (alertas de bloqueio) + **Power BI** (*Velocity* e progresso) |
| **Enterprise / ERP (Múltiplos Times & Fornecedores)** | **Jira** (boards por módulo + visão consolidada de portfólio e *burndown*) | Confluence / Especificações formais | **Teams / Slack** (alinhamento de dependências) + **Power BI** (status executivo) |
| **Produto Educacional (Dev + Conteúdo + Feedback)** | **Jira Software** (sprints de engenharia) | **Confluence** (base de conhecimento) + **Jira Service Management (JSM)** (triagem de feedback/bugs) | Macros ao vivo Jira $\leftrightarrow$ Confluence (fonte única de verdade) + **Slack** |
| **E-commerce Corporativo (Dev + Marketing + Suporte)** | **Azure DevOps Boards** (fluxos customizados Scrum/Kanban para todas as áreas) | Suíte Microsoft (Docs/Excel/Whiteboard) | **Microsoft Teams** (canais `#dev`, `#marketing`, `#suporte`) + **Power BI** |

---

### Ramo 4: Habilidades Essenciais, Influência e Gestão de Conflitos
* **Hipótese de Trabalho:** Como o Tech Lead frequentemente lidera sem autoridade hierárquica formal sobre todas as áreas, sua eficácia depende de **credibilidade técnica + inteligência emocional + comunicação estruturada** para converter tensões em acordos colaborativos.
* **Pilares de Influência Técnica:** Demonstrar domínio técnico, ser confiável, ouvir ativamente, definir expectativas claras, envolver o time nas decisões de arquitetura e manter transparência.
* **Protocolo de Resolução de Conflitos:**
  1. **Diagnosticar a causa-raiz:** Diferenças de personalidade, expectativas/objetivos divergentes, recursos limitados ou falha de comunicação.
  2. **Selecionar a técnica:** *Mediação* (terceiro imparcial), *Negociação* (acordo ganha-ganha) ou *Comunicação Não-Violenta (CNV)*.
  3. **Aplicar o roteiro CNV (4 passos):**
     * **Observação** (fato objetivo sem julgamento): *"Percebi que o entregável X não foi enviado na sexta-feira..."*
     * **Sentimento** (impacto emocional/no time): *"...isso gerou frustração porque dependíamos dessa entrega para avançar..."*
     * **Necessidade** (valor/objetivo em risco): *"...é importante cumprirmos os prazos para manter a confiança e eficiência do time..."*
     * **Pedido** (ação concreta e negociável): *"...você pode me ajudar a entender o que houve e alinharmos uma nova data?"*

---

## 4. 📊 Critérios de Validação & Métricas (Evidências de Sucesso)

Para comprovar na prática se a liderança e a gestão do projeto estão gerando resultados, o Tech Lead deve monitorar:
* **Previsibilidade de Entrega:** Aderência aos *Milestones* planejados, taxa de conclusão de itens comprometidos na Sprint e estabilidade do gráfico de *Burndown*.
* **Saúde do Escopo e Qualidade:** Percentual de *scope creep* (mudanças não planejadas absorvidas sem repriorização) e taxa de defeitos/falhas de integração pós-release.
* **Engajamento e Autonomia do Time:** Redução de dependências diretas do Tech Lead para decisões operacionais (evolução nos níveis do *Delegation Poker*), frequência de feedbacks contínuos e tempo de *ramp-up* de novos membros.

---

## 5. ⚡ Playbook de Decisão Rápida (Síntese do Tech Lead)

* **Ao iniciar um projeto:** Não pule direto para o código. Garanta a visão e limites de escopo, mapeie *Stakeholders*, quebre o trabalho em **EAP**, defina **Milestones** e levante os **3 principais riscos técnicos** com planos de mitigação e donos definidos.
* **Diante de mudança de escopo ou prazo apertado:** Ative o protocolo de 4 passos:
  1. **Alinhamento transparente** imediato com o time e stakeholders;
  2. **Corte objetivo para MVP** mantendo o núcleo de valor;
  3. **Registro formal** de impacto em prazo/custo e isolamento de novas demandas para releases futuras;
  4. **Blindagem do foco** da equipe (remoção de reuniões desnecessárias e *Dailies* curtas para desbloqueio).
* **Ao assumir um time novo ou desmotivado:** Rode uma sessão de **Moving Motivators** para mapear o que engaja cada pessoa individualmente e aplique o **Delegation Poker** para deixar explícito o que o time decide sozinho, o que consulta e o que apenas informa.