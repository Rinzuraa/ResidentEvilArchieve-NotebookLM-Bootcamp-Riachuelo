# 🧟 Caderno Temático: A História de Resident Evil
> **Projeto DIO — NotebookLM como Ferramenta de Aprendizagem Ativa**

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

Resident Evil é minha franquia favorita de jogos. Desde o primeiro título lançado em 1996, a série moldou o gênero de survival horror e continua relevante até hoje — com remakes aclamados, séries na Netflix e um universo expandido de filmes, mangás e HQs. Mais do que entretenimento, RE é um estudo de caso fascinante sobre narrativa, design de jogos, evolução de mecânicas e impacto cultural.

Este projeto nasceu da vontade de usar o NotebookLM para organizar de forma séria e estruturada tudo que sei (e quero aprender) sobre a história da franquia, transformando horas de gameplay e leitura informal em conhecimento documentado.

### Objetivos de Estudo

| Objetivo | Descrição |
|---|---|
| 🎯 **Narrativo** | Compreender a linha do tempo completa do universo de RE, do incidente de Raccoon City até os eventos de RE: Village |
| 🏢 **Institucional** | Entender a estrutura e história da Umbrella Corporation e suas ramificações (TRICELL, Connections, etc.) |
| 🧬 **Científico-ficcional** | Mapear os vírus, parasitas e bioarmas que aparecem na série (T-Vírus, G-Vírus, Las Plagas, C-Vírus, etc.) |
| 🎮 **Game Design** | Analisar como a franquia evoluiu em mecânicas: de câmera fixa para primeira pessoa |
| 📊 **Cultural** | Entender o impacto cultural e comercial de RE no mercado de jogos e na cultura pop |

---

## Curadoria de Fontes

As fontes abaixo foram selecionadas por serem abertas, textuais e ricas em conteúdo factual sobre a franquia. Todas foram inseridas no NotebookLM para análise.

### Fonte 1 — Resident Evil Wiki (Fandom)
- **Link:** [https://residentevil.fandom.com/wiki/Resident_Evil_Wiki](https://residentevil.fandom.com/wiki/Resident_Evil_Wiki)
- **Por que escolhi:** É a enciclopédia colaborativa mais completa sobre o universo RE, com artigos detalhados sobre personagens, vírus, organizações e cronologia.
- **Como usei no NotebookLM:** Exportei artigos-chave em PDF (Umbrella Corporation, T-Virus, cronologia geral) e subi como documentos base.

### Fonte 2 — Artigo Acadêmico: "Survival Horror and the Expansion of Video Game Aesthetics"
- **Link:** [https://www.semanticscholar.org/paper/Survival-horror-video-games-and-the-construction-of/](https://www.semanticscholar.org/paper/)
- **Por que escolhi:** Oferece uma análise acadêmica do gênero survival horror com Resident Evil como estudo de caso central.
- **Como usei no NotebookLM:** Upload do PDF completo para cruzar com análises de game design.

### Fonte 3 — Capcom Investor Relations / Press Releases sobre RE
- **Link:** [https://www.capcom.co.jp/ir/english/](https://www.capcom.co.jp/ir/english/)
- **Por que escolhi:** Fonte primária oficial com dados de vendas, marcos históricos e declarações da Capcom sobre a franquia.
- **Como usei no NotebookLM:** Inserção de releases sobre os remakes (RE2, RE3, RE4) e dados de vendas globais.

### Fonte 4 — IGN: "The Complete History of Resident Evil"
- **Link:** [https://www.ign.com/articles/2016/01/11/the-complete-history-of-resident-evil](https://www.ign.com/articles/2016/01/11/the-complete-history-of-resident-evil)
- **Por que escolhi:** Artigo jornalístico de grande abrangência cobrindo os bastidores do desenvolvimento da série, com entrevistas com Shinji Mikami e Yoshiki Okamoto.
- **Como usei no NotebookLM:** Upload da versão em texto para análise das decisões criativas por trás de cada jogo.

### Fonte 5 — Retro Gamer: "The Making of Resident Evil"
- **Link:** [https://www.gamesradar.com/the-making-of-resident-evil/](https://www.gamesradar.com/the-making-of-resident-evil/)
- **Por que escolhi:** Cobre os bastidores do desenvolvimento do primeiro RE, incluindo protótipos, influências do cinema (Romero, Argento) e decisões de design.
- **Como usei no NotebookLM:** Base para o módulo de história da criação da franquia.

---

## Engenharia de Prompts e Cicatrizes

Esta seção documenta minha jornada com o NotebookLM: os prompts que funcionaram, os que não funcionaram e o que aprendi com cada tentativa.

---

### 🧪 Experimento 1 — Linha do Tempo

**Objetivo:** Criar uma cronologia clara dos eventos do universo RE.

**Prompt v1.0 (genérico):**
```
Me fale sobre a história de Resident Evil.
```
**Resultado:** Resposta muito ampla e superficial, sem organização temporal. O NotebookLM trouxe informações misturadas de fontes diferentes sem hierarquia.

**⚠️ Problema identificado:** O prompt não delimitou escopo nem pediu formato específico.

---

**Prompt v2.0 (refinado):**
```
Com base nos documentos carregados, crie uma linha do tempo cronológica dos principais eventos do universo de Resident Evil, desde a fundação da Umbrella Corporation até os eventos de Resident Evil Village. Organize por décadas e inclua apenas eventos confirmados pelos materiais de origem.
```
**Resultado:** ✅ Muito melhor! O NotebookLM gerou uma timeline estruturada com referências diretas às fontes. Consegui verificar cada evento citado.

**💡 Aprendizado:** Especificar formato (linha do tempo), escopo (fundação da Umbrella até RE Village) e critério de confiabilidade (apenas eventos confirmados) transformou completamente a qualidade da resposta.

---

### 🧪 Experimento 2 — Análise dos Vírus

**Objetivo:** Entender as diferenças entre os principais agentes biológicos da série.

**Prompt v1.0:**
```
Quais são os vírus de Resident Evil?
```
**Resultado:** Lista simples sem profundidade. Apenas nomeou T-Vírus, G-Vírus e Las Plagas sem explicar mecanismos ou relações entre eles.

---

**Prompt v2.0:**
```
Crie uma tabela comparativa dos principais agentes biológicos presentes em Resident Evil (T-Vírus, G-Vírus, Las Plagas, Progenitor, C-Vírus, Mold/E-Vírus). Para cada agente, inclua: jogo em que aparece, organização responsável, efeito nos hospedeiros e personagens afetados notáveis.
```
**Resultado:** ✅ Excelente! A tabela comparativa foi gerada corretamente com base nas fontes, tornando muito mais fácil estudar e memorizar as diferenças.

**💡 Aprendizado:** Pedir formato de tabela com colunas definidas é uma das estratégias mais eficazes no NotebookLM para conteúdo comparativo.

---

### 🧪 Experimento 3 — Bastidores do Desenvolvimento

**Objetivo:** Entender as decisões criativas por trás dos jogos principais.

**Prompt testado:**
```
Com base nos artigos sobre o desenvolvimento de Resident Evil, quais foram as principais decisões criativas que definiram o estilo da série? Cite decisões específicas de Shinji Mikami e explique como elas influenciaram o gênero survival horror.
```
**Resultado:** ✅ Bom resultado, com referências às fontes do IGN e Retro Gamer. O NotebookLM identificou corretamente as citações de Mikami sobre a influência do cinema de terror europeu.

**⚠️ Dificuldade encontrada:** Quando pedi para "comparar com outros jogos do gênero fora das fontes", o NotebookLM recusou corretamente, limitando-se ao que havia nos documentos. Aprendi a não pedir informações externas às fontes carregadas.

---

### 🧪 Experimento 4 — Geração de Quiz

**Objetivo:** Criar questões para autoteste do conteúdo estudado.

**Prompt:**
```
Com base nos documentos, crie 10 perguntas de múltipla escolha sobre a história de Resident Evil, com 4 alternativas cada e resposta correta indicada. Varie entre perguntas sobre personagens, vírus, organizações e cronologia. Nível: intermediário.
```
**Resultado:** ✅ Quiz gerado com sucesso e perguntas bem calibradas. Usei para testar meu conhecimento ao fim de cada sessão de estudo.

**💡 Aprendizado:** O NotebookLM é excelente para gerar material de revisão ativa. Especificar o nível de dificuldade e a variedade temática melhora muito o resultado.

---

### 📊 Resumo de Aprendizados (Troubleshooting)

| Problema | Causa | Solução |
|---|---|---|
| Resposta genérica e rasa | Prompt sem escopo definido | Adicionar delimitadores de tempo, tema e formato |
| Informações misturadas | Muitas fontes com conteúdo sobrepostos | Separar notebooks por tema ou pedir citação de fonte específica |
| NotebookLM recusou responder | Pedido de informação externa às fontes | Limitar perguntas ao conteúdo dos documentos carregados |
| Resposta muito longa e sem estrutura | Prompt aberto demais | Pedir formato específico (tabela, lista numerada, tópicos) |

---

## Miniguia de Estudo — Entrega Final

### Resumos Estruturados

---

#### 📖 Módulo 1: A Criação da Franquia (1993–1996)

Resident Evil nasceu em 1993 como um projeto interno da Capcom, inicialmente concebido como remake do jogo Famicom Sweet Home (1989). Shinji Mikami assumiu a direção e redirecionou o projeto para um survival horror em 3D com perspectiva de câmera fixa — inspirado fortemente em Alone in the Dark (1992) e no cinema de terror B europeu, especialmente George Romero e Dario Argento.

O jogo original, lançado em 1996 para PlayStation, introduziu elementos que definiriam o gênero: recursos escassos, puzzles ambientais, gestão de inventário e atmosfera opressiva. A mansão Spencer tornou-se um dos cenários mais icônicos dos videogames.

**Marcos:**
- 1993 — Início do desenvolvimento interno na Capcom
- 1996 — Lançamento do Resident Evil 1 (JP: Biohazard) no PlayStation
- Vendas: mais de 3 milhões de cópias, salvando financeiramente a Capcom na época

---

#### 📖 Módulo 2: A Umbrella Corporation e o Universo Expandido

A Umbrella Corporation é a grande antagonista institucional da série. Fundada em 1968 por Ozwell E. Spencer, Edward Ashford e James Marcus, a empresa operava publicamente como farmacêutica enquanto desenvolvia armas biológicas secretamente com base no Vírus Progenitor, descoberto na África.

A estrutura narrativa de RE gira em torno da exposição gradual das atividades ilegais da Umbrella — um processo que dura da trilogia original até RE: The Umbrella Chronicles (2007), quando a empresa finalmente entra em colapso definitivo.

**Organizações derivadas:**
- **TRICELL** — Sucessora parcial da Umbrella (RE5)
- **The Connections** — Criadores do Mold/E-Vírus (RE7)
- **The Village** — Comunidade isolada com experimentos próprios (RE8)

---

#### 📖 Módulo 3: Evolução das Mecânicas (1996–2023)

| Era | Jogos | Mecânica Central | Perspectiva |
|---|---|---|---|
| **Clássica** | RE1, RE2, RE3, CV | Câmera fixa, recursos escassos | Terceira pessoa (câmera fixa) |
| **Transição** | RE0, REmake (2002) | Refinamento do sistema clássico | Terceira pessoa (câmera fixa) |
| **Ação** | RE4, RE5, RE6 | Over-the-shoulder, combate expandido | Terceira pessoa (OTS) |
| **Retorno ao Horror** | RE7, RE8 | Imersão e exploração | Primeira pessoa |
| **Remakes Modernos** | RE2R, RE3R, RE4R | Fusão clássica com moderno | Terceira pessoa (OTS) |

---

#### 📖 Módulo 4: Personagens Centrais

**Leon S. Kennedy** — Policial novato em RE2, agente do governo em RE4 e RE6. Representa a evolução do herói relutante ao agente experiente.

**Chris Redfield** — Membro fundador da S.T.A.R.S. e posteriormente da BSAA. Presente em RE1, Code Veronica, RE5, RE6 e RE8. É o personagem com maior presença na franquia.

**Jill Valentine** — Co-protagonista de RE1 e protagonista de RE3. Sua história envolve sobrevivência, captura pela Umbrella e recuperação da autonomia — uma das arcs mais complexas da série.

**Albert Wesker** — O grande vilão da era clássica. Traidor da S.T.A.R.S., agente duplo da Umbrella e posteriormente antagonista independente. Seu arco vai de RE1 até seu fim em RE5.

---

### Glossário

> Principais conceitos do universo de Resident Evil

**B.O.W. (Bio-Organic Weapon)** — Arma biológica orgânica criada pela Umbrella ou outras organizações. Inclui criaturas como Tyrant, Licker, Verdugo e muitas outras.

**C-Vírus (Chrysalid Virus)** — Vírus sintético criado pelo Neo-Umbrella em RE6, combinação do G-Vírus e T-Veronica. Capaz de criar casulos de transformação.

**E-Vírus / Mold** — Agente biológico controlado por Eveline em RE7. Diferente dos vírus anteriores, age através de fungos e cria conexões psíquicas entre hospedeiros.

**G-Vírus** — Criado por William Birkin em RE2. Produz mutações extremas e contínuas no hospedeiro, tornando-o quase imortal, porém cada vez menos humano.

**Las Plagas** — Parasita introduzido em RE4. Diferente dos vírus, não cria zumbis — os infectados (Ganados) mantêm inteligência limitada e coordenação coletiva.

**Licker** — B.O.W. criado pela mutação de zumbis infectados pelo T-Vírus. Cegos, mas com audição aguçadíssima. Icônico de RE2.

**Progenitor Virus** — O vírus original, descoberto na África por Spencer. Base para o desenvolvimento de todos os outros vírus da série.

**S.T.A.R.S. (Special Tactics and Rescue Service)** — Unidade especial do Departamento de Polícia de Raccoon City. Seus membros Alpha e Bravo foram enviados à Mansão Spencer e descobriram as atividades da Umbrella.

**T-Vírus (Tyrant Virus)** — O agente biológico mais icônico da franquia. Derivado do Progenitor, transforma humanos em zumbis e animais em B.O.W.s. Causador do incidente de Raccoon City.

**T-Veronica Virus** — Variante experimental do T-Vírus criada por Alexia Ashford. Requer 15 anos de hibernação para integração completa com o hospedeiro sem matar o indivíduo.

**Tyrant** — B.O.W. mais avançado da Umbrella, criado com o T-Vírus em hospedeiros humanos de genética compatível. O Mr. X (T-103) e o Nemesis são variantes notáveis.

**Umbrella Corporation** — Corporação farmacêutica multinacional e fachada para o desenvolvimento de armas biológicas. Fundada em 1968, entrou em colapso após o incidente de Raccoon City e a revelação de suas atividades.

**Virus Progenitor** — Veja *Progenitor Virus*.

**Zumbi (Zombie)** — Humano infectado pelo T-Vírus em fase avançada. Perde consciência, torna-se agressivo e busca instintivamente consumir carne viva. Símbolo visual da franquia.

---

### Prompts Reutilizáveis

> Coleção de prompts testados e validados para revisão futura no NotebookLM

#### 🔁 Para Revisão de Cronologia
```
Com base nos documentos, crie uma linha do tempo dos eventos de [JOGO OU ERA ESPECÍFICA], ordenada cronologicamente, destacando os 5 eventos mais importantes e suas consequências para a narrativa geral da franquia.
```

#### 🔁 Para Análise de Personagem
```
Faça uma ficha completa do personagem [NOME], incluindo: aparições na franquia, motivações principais, desenvolvimento de arco narrativo, relações com outros personagens e impacto na história geral. Use apenas informações presentes nos documentos carregados.
```

#### 🔁 Para Comparação de Elementos
```
Crie uma tabela comparativa entre [ELEMENTO A] e [ELEMENTO B] (ex: T-Vírus vs G-Vírus), incluindo as colunas: origem, criador, efeitos nos hospedeiros, jogos em que aparece e nível de ameaça.
```

#### 🔁 Para Geração de Quiz
```
Crie [NÚMERO] perguntas de múltipla escolha sobre [TEMA] com 4 alternativas cada, indicando a resposta correta e uma breve explicação. Nível de dificuldade: [iniciante / intermediário / avançado].
```

#### 🔁 Para Resumo de Jogo Específico
```
Faça um resumo narrativo completo de [NOME DO JOGO], cobrindo: contexto pré-jogo, protagonistas, antagonistas, principais revelações do enredo, e como os eventos se conectam com o restante da franquia.
```

#### 🔁 Para Exploração de Temas
```
Quais são os principais temas filosóficos, sociais ou científicos explorados em Resident Evil [JOGO OU SÉRIE GERAL]? Cite exemplos concretos presentes nos documentos que ilustrem cada tema.
```

#### 🔁 Para Identificar Lacunas de Conhecimento
```
Com base nos documentos carregados, quais aspectos da história de Resident Evil ficaram sem resposta ou são ambíguos? Liste as principais questões em aberto que poderiam ser exploradas com fontes adicionais.
```

---

## 🛠️ Ferramentas Utilizadas

- **[NotebookLM](https://notebooklm.google.com/)** — Organização, análise e geração de conteúdo a partir das fontes
- **[GitHub](https://github.com/)** — Versionamento e portfólio do projeto
- **[DIO](https://dio.me/)** — Plataforma de desafio e entrega do projeto

---

## 👤 Autor

Feito com 🧟 e muito amor pela franquia para o desafio de projeto da DIO.

> *"Whatever it takes, I'll stop Umbrella."* — Chris Redfield

---

*Projeto desenvolvido como parte do desafio **"Explorando o NotebookLM como Ferramenta de Aprendizagem Ativa"** na plataforma DIO.*
