# Suíte Pedagógica de Tutoria Pura para Gemini e Antigravity

Esta suíte de **Skills e Gems de Tutoria Pura** transforma a Inteligência Artificial de um mero *"motor de respostas prontas"* em um **parceiro cognitivo de alto nível**, fundamentado nas teorias de cinco dos maiores cientistas e educadores da história: **Richard Feynman**, **George Pólya**, **Eric Mazur**, **Carl Wieman** e **Seymour Papert**, orquestrados por uma **Meta-Skill de Triagem (Tutor Router)**.

---

## 1. O Princípio Fundamental: Pureza Didática sem a Armadilha Socrática Genérica

A maioria dos assistentes educacionais comete um de dois erros fatais:
1. **O motor de cola / Offloading Cognitivo**: entrega a resposta pronta, fórmulas mastigadas ou código pronto para o aluno copiar, aniquilando o aprendizado real.
2. **O falso socrático rígido**: adota um tom artificial de interrogatório com respostas misteriosas ou perguntas retóricas desconexas.

Esta suíte adota o princípio de **Pureza Metodológica Positiva**: cada skill incorpora a mecânica real de sua teoria pedagógica, implementada através de **reforços comportamentais afirmativos** e protegida por **válvulas de escape anti-deadlock** (*graceful degradation*).

---

## 2. Mapa do Ecossistema Pedagógico

| Skill | Papel da IA | Papel do Aluno | Foco Metodológico Puro | Válvula de Escape (Anti-Deadlock) |
| :--- | :--- | :--- | :--- | :--- |
| [**`tutor-router`**](file:///C:/Users/andre/.gemini/antigravity/scratch/ai_tutor/skills/tutor-router/SKILL.md) | Triador e guia de acolhimento | O estudante que busca orientação | Diagnóstico rápido da dor do aluno em 1 turno e encaminhamento para a abordagem ideal. | Se a dúvida for ambígua, faz 1 pergunta de esclarecimento com opções claras. |
| [**`tutor-feynman`**](file:///C:/Users/andre/.gemini/antigravity/scratch/ai_tutor/skills/tutor-feynman/SKILL.md) | Ouvinte inteligente, leigo e curioso | O professor que leciona | **Autoexplicação pura**: caça jargões vazios, aponta saltos causais e convida à criação de analogias do cotidiano. | Escada de escape: foco em imagem mental $\to$ início de metáfora aberta $\to$ recuo para pré-requisito atômico. |
| [**`tutor-polya`**](file:///C:/Users/andre/.gemini/antigravity/scratch/ai_tutor/skills/tutor-polya/SKILL.md) | Mentor heurístico analítico | O arquiteto e executor da solução | **Heurística de resolução pura**: 4 fases canônicas (Compreender, Planejar, Executar, Retrospecto) com pistas graduadas. | Escada de escape: pista de foco $\to$ pista de teorema $\to$ sub-passo isolado $\to$ **exemplo isomórfico resolvido**. |
| [**`tutor-mazur`**](file:///C:/Users/andre/.gemini/antigravity/scratch/ai_tutor/skills/tutor-mazur/SKILL.md) | Colega de turma / par em debate | O debatedor científico | **Peer Instruction pura**: *ConcepTests*, confronto com a *misconception* clássica defendida com paixão pela IA. | Escada de escape: **autodúvida do colega IA** com contradição intuitiva $\to$ analogia de contraste extremo. |
| [**`tutor-wieman`**](file:///C:/Users/andre/.gemini/antigravity/scratch/ai_tutor/skills/tutor-wieman/SKILL.md) | Treinador cognitivo de STEM | O atleta em treino deliberado | **Prática deliberada pura**: micro-tarefas atômicas, micro-feedback imediato e progressão por maestria (regra de 80%). | Escada de escape: micro-pergunta binária $\to$ regra de ouro de especialista em 1 frase $\to$ reset de dificuldade. |
| [**`tutor-papert`**](file:///C:/Users/andre/.gemini/antigravity/scratch/ai_tutor/skills/tutor-papert/SKILL.md) | Copiloto de criação e depuração | O criador/autor do artefato | **Construcionismo puro**: micromundos, modelagem/código e investigação de discrepâncias modelo mental vs comportamento real. | Escada de escape: pergunta de contraste $\to$ indicação da linha exata para inserir `print/log` $\to$ mini-script MRE. |

---

## 3. Estrutura de Arquivos do Projeto

```
C:\Users\andre\.gemini\antigravity\scratch\ai_tutor/
├── README.md                           # Guia mestre da suíte
├── skills/                             # Formato padrão Antigravity Skills (com YAML frontmatter)
│   ├── tutor-router/SKILL.md           # Roteador / Triagem pedagógica
│   ├── tutor-feynman/SKILL.md          # Autoexplicação pura
│   ├── tutor-polya/SKILL.md            # Heurística de resolução pura
│   ├── tutor-mazur/SKILL.md            # Peer instruction e debate de misconceptions
│   ├── tutor-wieman/SKILL.md           # Prática deliberada em STEM pura
│   └── tutor-papert/SKILL.md           # Construcionismo e copiloto de criação
├── gems_system_prompts/                # Prompts prontos para copiar e colar no Google Gemini Gems
│   ├── 00_tutor_router.md              # Gem de Triagem Inteligente
│   ├── 01_feynman_explain_to_me.md
│   ├── 02_polya_plan_with_me.md
│   ├── 03_mazur_debate_with_me.md
│   ├── 04_wieman_practice_with_me.md
│   └── 05_papert_build_with_me.md
├── examples/                           # Diálogos reais comprovando a pureza metodológica
│   ├── feynman_dialogue_example.md     # Explicando Entropia e 2ª Lei da Termodinâmica
│   ├── polya_dialogue_example.md       # Resolução analítica de plano inclinado com mola
│   ├── mazur_dialogue_example.md       # ConcepTest de lançamento vertical no ápice
│   ├── wieman_dialogue_example.md      # Treino deliberado de Diagrama de Corpo Livre
│   └── papert_dialogue_example.md      # Simulação numérica de órbita em Python (Euler vs Verlet)
└── tests/                              # Bateria de testes de estresse e resiliência
    └── adversarial_stress_tests.md     # Cenários de urgência, pressão emocional, derivação e impasses
```

---

## 4. Como Utilizar

### Opção A: No Antigravity (CLI / IDE)
Todas as skills estão instaladas no diretório global `C:\Users\andre\.gemini\config\skills/`.
- Se você não souber qual método usar, basta chamar:  
  * *"Ative o tutor-router para me orientar com meus estudos"*
- Se já souber qual método quer:  
  * *"Ative a skill tutor-feynman para eu te explicar capacitores"*  
  * *"Use a abordagem do tutor-polya para resolver este exercício de cálculo"*

### Opção B: No Google Gemini (Web / Gemini Advanced Gems)
1. Acesse [gemini.google.com](https://gemini.google.com) $\to$ **Gems** $\to$ **Novo Gem**.
2. Abra qualquer um dos arquivos da pasta [`gems_system_prompts/`](file:///C:/Users/andre/.gemini/antigravity/scratch/ai_tutor/gems_system_prompts).
3. Copie o nome, a descrição e o bloco de instruções para o formulário.
4. Recomendação: crie o **`00_tutor_router`** como seu Gem padrão de entrada!
