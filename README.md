# Aprendizado de NotebookLM com a História de Resident Evil
> **Projeto DIO Riachuelo - Cibersegurança — NotebookLM como Ferramenta de Aprendizagem Ativa**

---

## 📋 Sumário

- [Contexto e Objetivos](#contexto-e-objetivos)
- [Curadoria de Fontes](#curadoria-de-fontes)
- [Engenharia de Prompts e Cicatrizes](#engenharia-de-prompts-e-cicatrizes)
- [Miniguia de Estudo — Entrega Final](#miniguia-de-estudo--entrega-final)
  - [Resumos Estruturados](#resumos-estruturados)
  - [Glossário](#glossário)
  - [Prompts Reutilizáveis](#prompts-reutilizáveis)

---

## Contexto e Objetivos

### Por que Resident Evil?

Resident Evil é minha franquia favorita de jogos. Tendo Resident evil 3 Nêmesis que foi primeiro jogo que joguei na minha vida.  Desde o primeiro título lançado em 1996, a série moldou o gênero de survival horror e continua relevante até hoje com remakes aclamados, novos jogos, séries e um universo expandido de filmes, mangás e HQs. Mais do que entretenimento, RE é um estudo de caso fascinante sobre narrativa, design de jogos, evolução de mecânicas e impacto cultural.

Este projeto nasceu da vontade de usar o NotebookLM para organizar de forma séria e estruturada tudo que sei (e quero aprender) sobre a história da franquia, transformando horas de gameplay e leitura informal em conhecimento documentado.

### Objetivos de Estudo

| Objetivo | Descrição |
|---|---|
| 🎯 **Narrativo** | Compreender a linha do tempo completa do universo de RE, do incidente de Raccoon City até os eventos de RE: Requiem |
| 🏢 **Institucional** | Entender a estrutura e história da Umbrella Corporation e suas ramificações (TRICELL, Connections, etc.) |
| 🧬 **Científico-ficcional** | Mapear os vírus, parasitas e bioarmas que aparecem na franquia (T-Vírus, G-Vírus, Las Plagas, C-Vírus, etc.) |
| 🎮 **Game Design** | Analisar como a franquia evoluiu em mecânicas: de câmera fixa para primeira pessoa |
| 📊 **Cultural** | Entender o impacto cultural e comercial de RE no mercado de jogos e na cultura pop |


## 📋 Sumário

- [Contexto e Objetivos](#contexto-e-objetivos)
- [Curadoria de Fontes](#curadoria-de-fontes)
- [Engenharia de Prompts e Cicatrizes](#engenharia-de-prompts-e-cicatrizes)
- [Miniguia de Estudo — Entrega Final](#miniguia-de-estudo--entrega-final)
  - [Resumos Estruturados](#resumos-estruturados)
  - [Glossário](#glossário)
  - [Prompts Reutilizáveis](#prompts-reutilizáveis)

---

## Contexto e Objetivos

### Por que Resident Evil?

Resident Evil é minha franquia favorita de jogos — e Resident Evil 3: Nemesis foi o primeiro jogo que joguei na vida. Desde o primeiro título lançado em 1996, a série moldou o gênero de survival horror e continua relevante até hoje, com remakes aclamados, novos jogos, séries e um universo expandido de filmes, mangás e HQs.

Este projeto nasceu da vontade de usar o NotebookLM para organizar de forma séria tudo que sei (e quero aprender) sobre a história da franquia, transformando horas de gameplay e leitura informal em conhecimento documentado.

### Objetivos de Estudo

| Objetivo | Descrição |
|---|---|
| 🎯 **Narrativo** | Compreender a linha do tempo completa do universo de RE, do incidente de Raccoon City até RE: Requiem |
| 🏢 **Institucional** | Entender a estrutura e história da Umbrella Corporation e suas ramificações |
| 🧬 **Científico-ficcional** | Mapear os vírus e bioarmas da franquia (T-Vírus, G-Vírus, Las Plagas, C-Vírus, etc.) |
| 🎮 **Game Design** | Analisar como a franquia evoluiu em mecânicas: de câmera fixa para primeira pessoa |
| 📊 **Cultural** | Entender o impacto cultural, financeiro e os bastidores da criação da Capcom |

---

## Curadoria de Fontes

As fontes abaixo foram selecionadas por serem abertas, textuais e ricas em conteúdo factual sobre a franquia. Todas foram inseridas no NotebookLM para análise.

### Fonte 1 — Resident Evil Wiki (Fandom)
- **Link:** [https://residentevil.fandom.com/wiki/Resident_Evil_Wiki](https://residentevil.fandom.com/wiki/Resident_Evil_Wiki)
- **Por que escolhi:** Enciclopédia colaborativa mais completa sobre o universo RE, com artigos sobre personagens, vírus, organizações e cronologia.
- **Como usei:** Exportei artigos-chave em PDF (Umbrella Corporation, T-Virus, cronologia geral) e subi como documentos base.

### Fonte 2 — REVIL Wiki
- **Link:** [https://residentevil.com.br/revil-wiki/](https://residentevil.com.br/revil-wiki/)
- **Por que escolhi:** O maior site de Resident Evil da América Latina, com conteúdo em português e cobertura ampla da franquia.
- **Como usei:** Base principal para os módulos de história e personagens, com a vantagem do conteúdo em PT-BR.

### Fonte 3 — Capcom Investor Relations
- **Link:** [https://www.capcom.co.jp/ir/english/](https://www.capcom.co.jp/ir/english/)
- **Por que escolhi:** Fonte primária oficial com dados de vendas, marcos históricos e declarações da Capcom sobre a franquia.
- **Como usei:** Releases sobre os remakes (RE2, RE3, RE4) e dados de vendas globais.

### Fonte 4 — IGN: "The Complete History of Resident Evil"
- **Link:** [https://www.ign.com/articles/2016/01/11/the-complete-history-of-resident-evil](https://www.ign.com/articles/2016/01/11/the-complete-history-of-resident-evil)
- **Por que escolhi:** Artigo abrangente cobrindo os bastidores do desenvolvimento da série, com entrevistas com Shinji Mikami.
- **Como usei:** Upload em texto para análise das decisões criativas por trás de cada jogo.

### Fonte 5 — Retro Gamer: "The Making of Resident Evil"
- **Link:** [https://www.gamesradar.com/the-making-of-resident-evil/](https://www.gamesradar.com/the-making-of-resident-evil/)
- **Por que escolhi:** Cobre os bastidores do desenvolvimento do primeiro RE, incluindo protótipos e influências do cinema de terror.
- **Como usei:** Base para o módulo de criação da franquia.

---

## Engenharia de Prompts e Cicatrizes

Esta seção documenta minha jornada com o NotebookLM: os prompts que funcionaram, os que não funcionaram e o que aprendi.

---

### 🧪 Experimento 1 — Linha do Tempo

**Objetivo:** Criar uma cronologia clara dos eventos do universo RE.

**Prompt v1.0 (genérico):**
```
Me fale sobre a história de Resident Evil.
```
**Resultado:** Resposta ampla e superficial, sem organização temporal. Informações misturadas sem hierarquia.

**⚠️ Problema:** O prompt não delimitou escopo nem pediu formato específico.

---

**Prompt v2.0 (refinado):**
```
Com base nos documentos carregados, crie uma linha do tempo cronológica dos principais 
eventos do universo de Resident Evil, desde a fundação da Umbrella Corporation até 
os eventos de Resident Evil Village. Organize por décadas e inclua apenas eventos 
confirmados pelos materiais de origem.
```
**Resultado:** ✅ Timeline estruturada com referências diretas às fontes.

**💡 Aprendizado:** Especificar formato, escopo e critério de confiabilidade transforma completamente a qualidade da resposta.

> <img width="1003" height="822" alt="image" src="https://github.com/user-attachments/assets/2060a190-6dba-45c7-a93d-afdae6bea2c5" />


---

### 🧪 Experimento 2 — Análise dos Vírus

**Objetivo:** Entender as diferenças entre os principais agentes biológicos da série.

**Prompt v1.0:**
```
Quais são os vírus de Resident Evil?
```
**Resultado:** Lista simples sem profundidade.

---

**Prompt v2.0:**
```
Crie uma tabela comparativa dos principais agentes biológicos de Resident Evil 
(T-Vírus, G-Vírus, Las Plagas, Progenitor, C-Vírus, Mold). Para cada agente, inclua: 
jogo em que aparece, organização responsável, efeito nos hospedeiros e personagens 
afetados notáveis.
```
**Resultado:** ✅ Tabela comparativa gerada corretamente, muito mais fácil de estudar.

**💡 Aprendizado:** Pedir formato de tabela com colunas definidas é uma das estratégias mais eficazes para conteúdo comparativo.

> <img width="977" height="782" alt="image" src="https://github.com/user-attachments/assets/787c6136-77d8-4788-95d1-ade0d82094e6" />


---

### 🧪 Experimento 3 — Geração de Quiz

**Objetivo:** Criar questões para autoteste do conteúdo estudado.

**Prompt:**
```
Com base nos documentos, crie 10 perguntas de múltipla escolha sobre a história de 
Resident Evil, com 4 alternativas cada e resposta correta indicada. Varie entre 
perguntas sobre personagens, vírus, organizações e cronologia. Nível: intermediário.
```
**Resultado:** ✅ Quiz bem calibrado, usei para testar meu conhecimento ao fim de cada sessão.

**💡 Aprendizado:** Especificar nível de dificuldade e variedade temática melhora muito o resultado.

> <img width="978" height="822" alt="image" src="https://github.com/user-attachments/assets/3a097978-98e1-4218-87e3-4e2c9a8b524c" />

---

### 📊 Resumo de Aprendizados (Troubleshooting)

| Problema | Causa | Solução |
|---|---|---|
| Resposta genérica | Prompt sem escopo definido | Adicionar delimitadores de tempo, tema e formato |
| Informações misturadas | Fontes com conteúdo sobrepostos | Pedir citação de fonte específica |
| NotebookLM recusou responder | Pedido de info externa às fontes | Limitar perguntas ao conteúdo dos documentos |
| Resposta sem estrutura | Prompt aberto demais | Pedir formato específico (tabela, lista, tópicos) |

---

## Miniguia de Estudo — Entrega Final

### Resumos Estruturados

---

#### 📖 Módulo 1: A Criação da Franquia (1993–1996)

Resident Evil nasceu em 1993 como projeto interno da Capcom, inicialmente concebido como remake do Famicom Sweet Home (1989). Shinji Mikami assumiu a direção e redirecionou o projeto para um survival horror com câmera fixa — inspirado em Alone in the Dark (1992) e no cinema de terror B europeu.

O jogo original, lançado em 1996 para PlayStation, introduziu elementos que definiriam o gênero: recursos escassos, puzzles ambientais, gestão de inventário e atmosfera opressiva.

**Marcos:**
- 1993 — Início do desenvolvimento na Capcom
- 1996 — Lançamento do Resident Evil 1 no PlayStation
- Mais de 3 milhões de cópias vendidas, salvando financeiramente a Capcom na época

---

#### 📖 Módulo 2: A Umbrella Corporation

Fundada em 1968 por Ozwell E. Spencer, Edward Ashford e James Marcus, a Umbrella operava como farmacêutica enquanto desenvolvia armas biológicas com base no Vírus Progenitor. A narrativa de RE gira em torno da exposição gradual das atividades ilegais da empresa — até seu colapso definitivo em RE: The Umbrella Chronicles (2007).

**Organizações derivadas:**
- **TRICELL** — Sucessora parcial da Umbrella (RE5)
- **The Connections** — Criadores do Mold/E-Vírus (RE7)
- **The Village** — Comunidade isolada com experimentos próprios (RE8)

---

#### 📖 Módulo 3: Evolução das Mecânicas (1996–2023)

| Era | Jogos | Perspectiva |
|---|---|---|
| **Clássica** | RE1, RE2, RE3, CV | Câmera fixa |
| **Ação** | RE4, RE5, RE6 | Terceira pessoa (OTS) |
| **Retorno ao Horror** | RE7, RE8 | Primeira pessoa |
| **Remakes Modernos** | RE2R, RE3R, RE4R | Terceira pessoa (OTS) |

---

#### 📖 Módulo 4: Personagens que me marcaram

**Leon .S. Kennedy** — Co-protagonista de RE2, protagonista de RE4, Co-protagonista de RE: Requiem e etc. Sua luta pela sobrevivência em Raccoon City sendo seu primeiro dia é uma das histórias mais intensas da franquia.

**Albert Wesker** — O grande vilão da era clássica. Traidor da S.T.A.R.S. e agente duplo da Umbrella. Seu arco vai de RE1 até seu fim em RE5. Um dos personagens mais estilosos e com construções de vilão mais bem feitas dos videogames.

---

### Glossário

> Os principais termos do universo Resident Evil

**B.O.W. (Bio-Organic Weapon)** — Arma biológica orgânica criada pela Umbrella. Inclui o Nemesis-T Type, Lickers, Tyrants e muitas outras criaturas.

**G-Vírus** — Criado por William Birkin (RE2). Produz mutações extremas e contínuas, tornando o hospedeiro quase imortal, porém cada vez menos humano.

**Las Plagas** — Parasita de RE4. Diferente dos vírus, mantém os infectados (Ganados) com inteligência limitada e coordenação coletiva quase que como uma mente comeia controlada pelo variante controladora (Osmond Saddler).

**Progenitor Virus** — O vírus original, descoberto na África por Spencer. Base para todos os outros agentes biológicos da série.

**S.T.A.R.S.** — Unidade especial do Departamento de Polícia de Raccoon City. descobriram as atividades da Umbrella na Mansão Spencer.

**T-Vírus (Tyrant Virus)** — O agente biológico mais icônico da franquia. Transforma humanos em zumbis e causou o incidente de Raccoon City.

**Umbrella Corporation** — Corporação farmacêutica e fachada para desenvolvimento de armas biológicas. Fundada em 1968, entrou em colapso após Raccoon City.

---

### Prompts Reutilizáveis

#### 🔁 Cronologia
```
Com base nos documentos, crie uma linha do tempo de [JOGO OU ERA], destacando os 
5 eventos mais importantes e suas consequências para a narrativa geral.
```

#### 🔁 Análise de Personagem
```
Faça uma ficha do personagem [NOME]: aparições, motivações, arco narrativo e 
impacto na história. Use apenas os documentos carregados.
```

#### 🔁 Comparação de Elementos
```
Crie uma tabela comparativa entre [A] e [B], com as colunas: origem, criador, 
efeitos nos hospedeiros e jogos em que aparece.
```

#### 🔁 Quiz
```
Crie [N] perguntas de múltipla escolha sobre [TEMA], com 4 alternativas e resposta 
indicada. Nível: [iniciante / intermediário / avançado].
```

#### 🔁 Análise Financeira/Histórica
```
Com base nos documentos, explique o impacto financeiro de [JOGO] para a Capcom: 
vendas esperadas vs realizadas, consequências para a franquia e decisões tomadas 
em resposta ao resultado.
```

---

## 🛠️ Ferramentas Utilizadas

- **[NotebookLM](https://notebooklm.google.com/)** — Organização e análise das fontes
- **[GitHub](https://github.com/)** — Versionamento e portfólio
- **[DIO](https://dio.me/)** — Plataforma do desafio

---

## 👤 Autor

Rodrigo OLiveira Vilalta

> *"Whatever it takes, I'll stop Umbrella."* — Chris Redfield

---

*Projeto desenvolvido como parte do desafio **"Explorando o NotebookLM como Ferramenta de Aprendizagem Ativa"** — Bootcamp DIO Riachuelo Cibersegurança.*
