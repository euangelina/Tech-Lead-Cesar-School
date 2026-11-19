# 📚 Tech Lead Playbook: Aprendizado Baseado em IBPS

Este repositório reúne meus estudos, anotações e guias práticos da **Pós-Graduação em Tech Lead**, estruturados sob a ótica do **IBPS (*Issue-Based Problem Solving*)**.

O objetivo deste projeto é transformar o conteúdo teórico das disciplinas e o compilado dos entregáveis em um **repertório acionável de tomada de decisão**, conectando conceitos de arquitetura, engenharia de software e liderança técnica diretamente aos problemas reais do dia a dia.

## 🧠 O que é IBPS (*Issue-Based Problem Solving*)?

O **IBPS** é uma metodologia estruturada de análise e resolução de problemas originada e difundida na consultoria estratégica. Em vez de estudar ferramentas isoladas ou acumular teoria passiva ("ferver o oceano" de dados), o IBPS parte de uma **pergunta-chave de negócio ou arquitetura** e a decompõe em questões menores e testáveis.

### Pilares da Metodologia Aplicados aos Estudos

1. **Definição do Problema Central (*The Core Issue*):** Qual dor real de engenharia, produto ou time essa disciplina resolve?

2. **Decomposição MECE (*Mutually Exclusive, Collectively Exhaustive*):** Quebra do problema em pilares independentes que cobrem todo o escopo sem sobreposição ou lacunas.

3. **Abordagem Orientada a Hipóteses (*Hypothesis-Driven*):** Formulação de causas prováveis, anti-padrões e soluções arquiteturais ou de gestão antes da coleta exaustiva de dados.

4. **Validação por Evidências:** Definição de métricas, KPIs e sinais observáveis para comprovar ou refutar cada hipótese na prática.

5. **Síntese Executiva (*Bottom-Up* / Princípio da Pirâmide):** Consolidação dos achados de baixo para cima para entregar uma recomendação clara, direta e embasada.

## 🗂️ Estrutura Padrão de Cada Disciplina

Cada módulo deste repositório segue rigorosamente o mesmo template para facilitar a consulta rápida em cenários reais de liderança:

1. **🎯 Questão Central da Disciplina (The Core Issue)**

   * A grande pergunta acionável e mensurável que norteia o tema.

2. **🌳 Árvore de Questões (Issue Tree - MECE)**

   * Mapeamento visual/estruturado dos subproblemas e pilares técnicos abordados na matéria.

3. **🧪 Hipóteses de Trabalho & Anti-padrões**

   * Diagnóstico de falhas comuns na indústria e as hipóteses de solução baseadas nos fundamentos da disciplina.

4. **📊 Critérios de Validação & Métricas**

   * Como medir sucesso ou falha (ex.: DORA Metrics, SLOs/SLAs, métricas de fluxo, saúde do time, qualidade de código).

5. **⚡ Playbook de Decisão (Síntese do Tech Lead)**

   * Checklist prático: *quando aplicar*, *principais trade-offs*, *riscos* e *primeiros passos* para conduzir o time.

## 📁 Organização do Repositório

```
.
├── README.md
└── modulos/
    ├── 01-lideranca-e-gestao-de-projetos/
    |   ├── guia-ibps.html
    │   └── guia-ibps.md
    ├── 02-agilidade-e-gestao-de-equipes/
    |   ├── guia-ibps.html
    │   └── guia-ibps.md
    └── ...
```

## 🚀 Disciplinas e Questões Centrais

| # | Disciplina | Questão Central (Core Issue) |
| :--- | :--- | :--- |
| 01 | **Liderança e Gestão de Projetos** | Como conduzir projetos da concepção à entrega garantindo alinhamento estratégico, previsibilidade e geração de valor? |
| 02 | **Agilidade e Gestão de Equipes** | Como estruturar e liderar times ágeis para maximizar a adaptabilidade, o ritmo de entrega e a autonomia técnica? |
| 03 | **Gestão de Produtos e Portfólios** | Como priorizar iniciativas e gerenciar o ciclo de vida de produtos para otimizar recursos e maximizar o retorno de mercado? |
| 04 | **Arquitetura de Software** | Como projetar sistemas escaláveis, resilientes e evolutivos que sustentem os objetivos de negócio sem gerar dívida técnica crítica? |
| 05 | **Data Science e IA** | Como transformar grandes volumes de dados em *insights* acionáveis e modelos preditivos para fundamentar decisões estratégicas? |
| 06 | **Qualidade de Software e Entrega** | Como assegurar entregas contínuas e confiáveis mantendo altos padrões de qualidade técnica, usabilidade e estabilidade? |
| 07 | **Cloud Computing** | Como arquitetar e operar soluções em nuvem equilibrando elasticidade, alta disponibilidade, desempenho e eficiência de custos (FinOps)? |
| 08 | **Cyber Security** | Como proteger ativos, dados e sistemas críticos contra ameaças cibernéticas em ambientes híbridos (*On-Premises* e *Cloud*)? |
| 09 | **DevSecOps** | Como incorporar práticas e automações de segurança desde o início do ciclo de desenvolvimento sem criar gargalos no fluxo de entrega? |
| 10 | **Gestão de Conflitos e Negociação** | Como mediar divergências técnicas e interpessoais para converter tensões em acordos colaborativos de alto impacto? |
| 11 | **Design Thinking** | Como aplicar empatia e experimentação rápida para validar problemas reais e desenhar soluções centradas no usuário? |
| 12 | **Seleção e Onboarding** | Como estruturar processos de atração, avaliação técnica e integração para acelerar o *ramp-up* e a retenção de talentos? |
| 13 | **Métricas e Tomada de Decisão Baseada em Dados** | Como definir, coletar e interpretar métricas de engenharia e produto para substituir achismos por decisões baseadas em evidências? |
| 14 | **Modelagem de Estratégias e OKRs** | Como desdobrar a visão estratégica em objetivos claros e resultados-chave mensuráveis que conectem a execução técnica ao sucesso do negócio? |
| 15 | **Ferramentas de IA para Produtividade** | Como integrar ferramentas de Inteligência Artificial no fluxo de trabalho do time para automatizar tarefas operacionais e escalar a capacidade analítica? |

## 🛠️ Como Utilizar Este Repositório

* **Como material de revisão:** Consulte a *Issue Tree* para relembrar rapidamente a conexão entre conceitos de uma disciplina.

* **Como ferramenta de trabalho:** Diante de um gargalo técnico, organizacional ou arquitetural, localize o módulo correspondente e utilize o *Playbook de Decisão* e as *Métricas de Validação* para estruturar seu plano de ação.

## 📚 Referências e Fontes Metodológicas

A estruturação deste repositório fundamenta-se na literatura clássica de resolução estruturada de problemas, pensamento lógico e métricas de engenharia de software:

* **Minto, Barbara (2009).** *The Pyramid Principle: Logic in Writing and Thinking* (3ª ed.). Financial Times / Prentice Hall. — *Fonte primária para o princípio MECE, estruturação lógica de Issue Trees, framework SCQ (Situation, Complication, Question) e síntese executiva.*

* **Rasiel, Ethan M. (1999).** *The McKinsey Way: Using the Techniques of the World's Top Strategic Consultants to Help You and Your Business*. McGraw-Hill. — *Referência fundamental sobre a origem e aplicação prática do Issue-Based Problem Solving, abordagem orientada a hipóteses (hypothesis-driven) e o conceito de evitar "ferver o oceano".*

* **Chevallier, Arnaud (2016).** *Strategic Thinking in Complex Problem Solving*. Oxford University Press. — *Aprofundamento moderno sobre construção de árvores de questões (Issue Trees) e árvores de hipóteses aplicadas a problemas complexos e ambíguos.*

* **Forsgren, N., Humble, J., & Kim, G. (2018).** *Accelerate: The Science of Lean Software and DevOps*. IT Revolution Press. — *Base para os critérios de validação e métricas de engenharia (DORA Metrics) sugeridas nos playbooks.*
