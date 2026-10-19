# Interface Humano-Computador (IHC)

Repositório de estudos da disciplina **Interface Humano-Computador**, do curso de Engenharia de Software da Universidade Estadual de Maringá (UEM).

A disciplina tem carga horária de **68 horas** e aborda fundamentos de Interação Humano-Computador (IHC), experiência do usuário (UX), projeto de interfaces e avaliação de sistemas interativos.

## Sobre a disciplina

A Interação Humano-Computador estuda como as pessoas utilizam sistemas interativos e como projetar interfaces que atendam às suas necessidades, características e contextos de uso. O objetivo não é apenas fazer uma interface visualmente agradável, mas desenvolver experiências compreensíveis, eficientes, acessíveis e adequadas às pessoas que irão utilizá-las.

## Conteúdo programático

### 1. Fundamentos e paradigmas de IHC

Estudo das diferentes perspectivas sobre sistemas interativos, incluindo os conceitos de **interface**, **interação** e **affordance**. Também são abordadas qualidade da experiência do usuário, usabilidade, comunicabilidade, acessibilidade, paradigmas de interação e abordagens teóricas de IHC.

**Por que é importante:** esses fundamentos ajudam a compreender como as pessoas percebem e utilizam um sistema, permitindo tomar decisões de design que tornem as funcionalidades mais claras e previsíveis.

### 2. Necessidades dos usuários e requisitos de IHC

Identificação de quais informações devem ser coletadas, de quem coletá-las e quais cuidados éticos devem ser adotados em pesquisas com pessoas. Inclui técnicas de coleta de dados, definição de perfis de usuários e personas, cenários de uso e análise de tarefas.

**Por que é importante:** conhecer usuários reais evita desenvolver funcionalidades com base apenas em suposições. Os dados coletados ajudam a definir requisitos relevantes e a entender os problemas que a interface precisa resolver.

### 3. Processos de design da IHC

Estudo do que é design em IHC, suas perspectivas e metodologias, como engenharia de usabilidade, design contextual, design baseado em cenários, design dirigido por objetivos e Design Thinking. Também é abordada a integração entre IHC e Engenharia de Software.

**Por que é importante:** processos de design organizam a passagem da compreensão do problema para a criação e melhoria de soluções. Integrar IHC ao desenvolvimento de software permite considerar as pessoas desde as primeiras decisões do projeto.

### 4. Design da IHC

Abrange princípios e diretrizes gerais, princípios de design gráfico, guias de estilo e acessibilidade, design da interação, padrões de design, dispositivos e tipos de interfaces e projeto de sistemas de ajuda.

**Por que é importante:** princípios e padrões ajudam a criar interfaces consistentes e mais fáceis de aprender. Diretrizes de acessibilidade ampliam as condições de uso para pessoas com diferentes capacidades e necessidades.

### 5. Avaliação da IHC

Estudo de por que, o que e quando avaliar em um sistema interativo, além de métodos de avaliação de IHC.

**Por que é importante:** avaliar uma interface permite identificar dificuldades que podem passar despercebidas durante o desenvolvimento. A avaliação fornece evidências para priorizar problemas e orientar melhorias com base na experiência de uso.

### 6. IHC aplicada e acessibilidade

Aplicação dos conceitos de IHC em diferentes domínios, incluindo saúde, educação, jogos, dispositivos móveis e vestíveis, considerando também acessibilidade para usuários.

**Por que é importante:** cada domínio possui objetivos, restrições e públicos específicos. Adaptar o projeto ao contexto de uso contribui para sistemas mais apropriados, inclusivos e úteis.

## Trabalhos e conceitos desenvolvidos

Os trabalhos práticos aplicam conceitos de IHC à análise da experiência de uso de um site de compras. Em vez de se limitar à aparência visual, as atividades exploram como planejar avaliações, observar tarefas, identificar barreiras e justificar melhorias com base em critérios definidos.

### Trabalho 1 — Planejamento e medição da usabilidade

O primeiro trabalho desenvolve a capacidade de **planejar uma avaliação de usabilidade** usando como referência a norma ISO 9241-11. O foco é compreender a usabilidade a partir de três dimensões:

- **Eficácia:** se as pessoas conseguem concluir suas tarefas e alcançar os objetivos pretendidos.
- **Eficiência:** quais recursos são necessários para concluir as tarefas, como tempo, ações e esforço.
- **Satisfação:** como as pessoas avaliam a experiência de uso.

O trabalho também aborda a caracterização do público-alvo, a descrição de tarefas e de seu contexto de execução, a definição de indicadores mensuráveis e a combinação de medidas objetivas e subjetivas. Entre os exemplos utilizados estão taxa de conclusão, erros, tempo de execução, ações desnecessárias, recuperação de erros, questionário System Usability Scale (SUS), escalas de satisfação e intenção de recomendação.

**O que esse trabalho ajuda a aprender:** transformar uma avaliação em um plano estruturado, definir como coletar evidências e estabelecer critérios para interpretar se a interface atende às necessidades dos usuários.

### Trabalho 2 — Avaliação heurística e identificação de problemas de interface

O segundo trabalho aprofunda a **inspeção de uma interface com base nas dez heurísticas de usabilidade de Jakob Nielsen**. A análise procura identificar problemas de interação ao longo de tarefas comuns de compra, relacionando cada problema a princípios de usabilidade.

Além de reconhecer inconsistências ou dificuldades, a atividade trabalha com a descrição do problema, a identificação da heurística relacionada, a classificação da severidade e a proposição de melhorias. A escala de severidade ajuda a diferenciar questões superficiais de problemas que dificultam ou impedem a conclusão de tarefas.

O trabalho também relaciona os achados da inspeção a indicadores de eficácia, eficiência e satisfação, incluindo métricas de execução, SUS e escalas subjetivas. Dessa forma, a avaliação combina o diagnóstico qualitativo das heurísticas com medidas de desempenho e percepção do usuário.

**O que esse trabalho ajuda a aprender:** examinar interfaces sistematicamente, justificar problemas observados, priorizar correções de acordo com seu impacto e propor melhorias conectadas a princípios de design e evidências de uso.

## Por que IHC é importante na Engenharia de Software?

Um software tecnicamente correto ainda pode falhar em atender às pessoas se for difícil de entender, exigir esforço desnecessário ou não considerar diferentes capacidades e contextos. IHC ajuda a aproximar as decisões técnicas das necessidades reais dos usuários.

O conhecimento da disciplina é útil para:

- levantar requisitos a partir de usuários, tarefas e contextos reais;
- planejar interfaces compreensíveis, consistentes e acessíveis;
- avaliar usabilidade antes e depois da implementação;
- identificar e priorizar problemas com base em evidências;
- comunicar decisões de design entre quem analisa, projeta, implementa e avalia o sistema.

## Organização do repositório

```text
interacao-humano-computador/
├── README.md
├── estudos/
├── trabalho-01-avaliacao-usabilidade/
└── trabalho-02-avaliacao-heuristica/
```

- `trabalho-01-avaliacao-usabilidade/`: materiais relacionados ao planejamento e à medição da usabilidade.
- `trabalho-02-avaliacao-heuristica/`: materiais relacionados à inspeção heurística e à análise de problemas de interface.

## Referências indicadas no programa da disciplina

- BARBOSA, Simone D. J.; SILVA, Bruno S. *Interação Humano-Computador*. Elsevier, 2010.
- SHARP, Helen; ROGERS, Yvonne; PREECE, Jennifer. *Interaction Design: Beyond Human-Computer Interaction*. 2. ed. John Wiley & Sons, 2007.
- BENYON, David. *Interação Humano-Computador*. 2. ed. Pearson, 2011.
- LAZAR, Jonathan; FENG, Jinjuan Heidi; HOCHHEISER, Harry. *Research Methods in Human-Computer Interaction*. John Wiley & Sons, 2010.
- RUBIN, Jeffrey; CHISNELL, Dana. *Handbook of Usability Testing: How to Plan, Design, and Conduct Effective Tests*. Wiley, 2008.
- SNYDER, Carolyn. *Paper Prototyping: The Fast and Easy Way to Design and Refine User Interfaces*. Morgan Kaufmann, 2003.

---


