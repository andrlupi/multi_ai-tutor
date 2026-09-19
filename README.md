# Multi-AI-Tutor: Suíte Pedagógica Pura para Gemini e Antigravity

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

O **`multi-ai-tutor`** é um framework de tutoria cognitiva baseada em evidências científicas de aprendizagem em STEM (Ciência, Tecnologia, Engenharia e Matemática). Ele transforma modelos de linguagem de meros *"geradores de respostas prontas"* em **verdadeiros parceiros cognitivos**, modelados a partir das teorias e métodos de grandes educadores e cientistas:

1. **Richard Feynman**: Autoexplicação pura e caça a jargões vazios (*Explain-to-me*).
2. **George Pólya**: Heurística canônica de resolução de problemas em 4 etapas (*Plan-with-me*).
3. **Eric Mazur**: Instrução pelos Pares e confronto de *misconceptions* (*Debate-with-me*).
4. **Carl Wieman**: Prática deliberada e progressão por maestria em STEM (*Practice-with-me*).
5. **Seymour Papert**: Construcionismo e copiloto de depuração de artefatos (*Build-with-me*).
6. **Ruth Chabay & Bruce Sherwood**: Modelagem em física por Primeiros Princípios (*Matter & Interactions*).
7. **Tutor Router**: Orquestrador e triador cognitivo para direcionamento inteligente sem fricção.

---

## 1. O Princípio Fundamental: Pureza Metodológica Positiva

Assistentes educacionais genéricos costumam cair na armadilha de um "tutor socrático rígido e inquisidor" ou ceder ao *cognitive offloading* (dar o gabarito pronto).

O **`multi-ai-tutor`** implementa **Pureza Metodológica**:
* **Sem Contaminação**: Cada skill mantém exclusivamente a identidade de seu referencial científico.
* **Engenharia de Prompt Positiva**: Substituição completa de proibições negativas ("NÃO faça X") por reforços condicionais afirmativos ("Quando o aluno fizer X $\to$ Aja com Y").
* **Válvulas de Escape (*Graceful Degradation*)**: Protocolos em até 3 níveis para evitar que o aluno caia em becos sem saída (*deadlocks*) quando não souber como responder.

---

## 2. Mapa do Ecossistema Pedagógico

| Skill | Papel da IA | Papel do Aluno | Foco Metodológico Puro | Válvula de Escape (Anti-Deadlock) |
| :--- | :--- | :--- | :--- | :--- |
| [**`tutor-router`**](file:///C:/Users/andre/.gemini/antigravity/scratch/ai_tutor/skills/tutor-router/SKILL.md) | Triador e guia de acolhimento | Estudante com necessidade de estudo | Diagnóstico rápido da dor em 1 turno e encaminhamento justificado para o método ideal. | Pergunta orientadora de esclarecimento com opções claras. |
| [**`tutor-feynman`**](file:///C:/Users/andre/.gemini/antigravity/scratch/ai_tutor/skills/tutor-feynman/SKILL.md) | Ouvinte inteligente, leigo e curioso | O professor que leciona | **Autoexplicação pura**: caça jargões vazios, aponta saltos causais e convida à criação de analogias do cotidiano. | Imagem mental $\to$ início de metáfora aberta $\to$ recuo para pré-requisito elementar. |
| [**`tutor-polya`**](file:///C:/Users/andre/.gemini/antigravity/scratch/ai_tutor/skills/tutor-polya/SKILL.md) | Mentor heurístico analítico | O arquiteto e executor da solução | **Heurística de resolução pura**: 4 fases canônicas (Compreender, Planejar, Executar, Retrospecto) com pistas graduadas. | Pista de foco $\to$ pista de teorema $\to$ sub-passo $\to$ **exemplo isomórfico resolvido**. |
| [**`tutor-mazur`**](file:///C:/Users/andre/.gemini/antigravity/scratch/ai_tutor/skills/tutor-mazur/SKILL.md) | Colega de turma / par em debate | O debatedor científico | **Peer Instruction pura**: *ConcepTests*, confronto com a *misconception* clássica defendida com paixão pela IA. | **Autodúvida do colega IA** com contradição intuitiva $\to$ analogia de contraste extremo. |
| [**`tutor-wieman`**](file:///C:/Users/andre/.gemini/antigravity/scratch/ai_tutor/skills/tutor-wieman/SKILL.md) | Treinador cognitivo de STEM | O atleta em treino deliberado | **Prática deliberada pura**: micro-tarefas atômicas, micro-feedback imediato e progressão por maestria (regra de 80%). | Micro-pergunta binária $\to$ regra de ouro de especialista em 1 frase $\to$ reset de dificuldade. |
| [**`tutor-papert`**](file:///C:/Users/andre/.gemini/antigravity/scratch/ai_tutor/skills/tutor-papert/SKILL.md) | Copiloto de criação e depuração | O criador/autor do artefato | **Construcionismo puro**: micromundos, modelagem/código e investigação de discrepâncias modelo mental vs comportamento real. | Pergunta de contraste $\to$ indicação da linha exata para inserir `print/log` $\to$ mini-script MRE. |
| [**`tutor-chabay-sherwood`**](file:///C:/Users/andre/.gemini/antigravity/scratch/ai_tutor/skills/tutor-chabay-sherwood/SKILL.md) | Físico modelador contemporâneo | O modelador científico ativo | **Matter & Interactions pura**: Primeiros Princípios Fundamentais (Momento, Energia, Momento Angular), delimitação de Sistema vs Vizinhança, modelo atômico esfera-mola e predição iterativa $\Delta t$. | Pergunta de fronteira do sistema $\to$ mapa temporal vs espacial $\to$ ponte microscópica esfera-mola. |

---

## 3. Estrutura do Repositório

```
multi-ai-tutor/
├── LICENSE                             # Licença Apache 2.0 (permissiva, padrão em IA)
├── README.md                           # Guia mestre do ecossistema
├── skills/                             # Skills prontas para o Google Antigravity
│   ├── tutor-router/SKILL.md           # Roteador / Triagem pedagógica
│   ├── tutor-feynman/SKILL.md          # Autoexplicação pura
│   ├── tutor-polya/SKILL.md            # Heurística de resolução pura
│   ├── tutor-mazur/SKILL.md            # Peer instruction e debate de misconceptions
│   ├── tutor-wieman/SKILL.md           # Prática deliberada em STEM pura
│   ├── tutor-papert/SKILL.md           # Construcionismo e copiloto de criação
│   └── tutor-chabay-sherwood/SKILL.md  # Modelagem por Primeiros Princípios (Matter & Interactions)
├── gems_system_prompts/                # Prompts prontos para copiar e colar no Google Gemini Gems
│   ├── 00_tutor_router.md              # Gem de Triagem Inteligente (Recomendado como entrada)
│   ├── 01_feynman_explain_to_me.md
│   ├── 02_polya_plan_with_me.md
│   ├── 03_mazur_debate_with_me.md
│   ├── 04_wieman_practice_with_me.md
│   ├── 05_papert_build_with_me.md
│   └── 06_chabay_sherwood_matter_interactions.md
├── examples/                           # Diálogos reais comprovando a pureza metodológica
│   ├── feynman_dialogue_example.md     # Explicando Entropia e 2ª Lei da Termodinâmica
│   ├── polya_dialogue_example.md       # Resolução analítica de plano inclinado com mola
│   ├── mazur_dialogue_example.md       # ConcepTest de lançamento vertical no ápice
│   ├── wieman_dialogue_example.md      # Treino deliberado de Diagrama de Corpo Livre
│   ├── papert_dialogue_example.md      # Simulação numérica de órbita em Python (Euler vs Verlet)
│   └── chabay_sherwood_dialogue_example.md # Princípio do Momento e força normal microscópica
└── tests/                              # Bateria de testes de estresse e resiliência
    └── adversarial_stress_tests.md     # Cenários de urgência, pressão emocional, derivação e impasses
```

---

## 4. Como Utilizar

### Opção A: No Antigravity (CLI / IDE)
Todas as skills estão sincronizadas no diretório global do Antigravity (`~/.gemini/config/skills/`).
- Para triagem automática:  
  * *"Ative o tutor-router para me orientar nos estudos de física"*
- Para chamar diretamente um método:  
  * *"Ative o tutor-feynman para eu te explicar o potencial elétrico"*  
  * *"Ative o tutor-chabay-sherwood para modelarmos este sistema por Primeiros Princípios"*

### Opção B: No Google Gemini (Web / Gemini Advanced Gems)
1. Acesse [gemini.google.com](https://gemini.google.com) $\to$ **Gems** $\to$ **Novo Gem**.
2. Abra qualquer um dos arquivos da pasta [`gems_system_prompts/`](file:///C:/Users/andre/.gemini/antigravity/scratch/ai_tutor/gems_system_prompts).
3. Copie o nome, a descrição e o bloco de instruções para o formulário do Gem e salve.

---

## 5. Licença

Este projeto é distribuído sob os termos da licença **Apache 2.0**. Consulte o arquivo [`LICENSE`](file:///C:/Users/andre/.gemini/antigravity/scratch/ai_tutor/LICENSE) para mais detalhes.
