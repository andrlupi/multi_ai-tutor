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
8. **STEM Content Crafter**: Meta-skill de autoria e calibração didática (Mazur, Pólya, Papert, Chabay-Sherwood, Wieman).

---

## 1. O Princípio Fundamental: Andaime Cognitivo Adaptativo e Evidências Científicas

Assistentes educacionais em IA costumam oscilar entre dois extremos nocivos:
1. **O *Cognitive Offloading* Passivo**: Entregar respostas prontas e códigos acabados, transformando o aluno em um espectador passivo que não retém nada.
2. **O "Socrático Estrito" e a Falácia Construtivista**: Responder a toda dúvida com novas perguntas, recusando-se a explicar ou modelar. Como demonstrado pelas pesquisas de **Kirschner, Sweller & Clark (2006)** e **Richard Mayer (2004)**, confundir "aprendizagem cognitivamente ativa" com "descoberta autônoma sem instrução" sobrecarrega a memória de trabalho, gera fadiga de adivinhação (*guess-what's-in-my-head*) e prejudica severamente estudantes novatos.

O **`multi-ai-tutor`** resolve essa tensão implementando **Andaime Cognitivo Adaptativo (*Adaptive Scaffolding*)**, corroborado pelas mais recentes investigações empíricas em educação STEM (2023-2025):
* **Sensibilidade à Expertise (Kalyuga, 2007)**: Novatos recebem instrução direta, analogias intuitivas e **Exemplos Trabalhados (*Worked Examples Effect* - Sweller, 1988)** antes da cobrança autônoma; conforme o domínio avança, o tutor recua para perguntas orientadoras e prática independente (*fading*).
* **Abordagem *Self-First then Refine* (Kumar et al., 2024 - ACM CSCW)**: O tutor incentiva o estudante a tentar articular sua hipótese ou rascunho de solução primeiro, usando a IA para refinamento cirúrgico, o que comprovadamente aumenta a retenção de longo prazo e a confiança calibrada.
* **A Tríade do Feedback em STEM (Zheng, Mo & Wang, 2023 - JACS)**: Feedback com alta **especificidade** (identificação do ponto exato de falha conceitual - impacto 4.7/5), **acionabilidade** (orientação clara sobre o próximo passo - impacto 4.8/5) e **oportunidade** (intervenção em tempo real enquanto a memória de trabalho está ativa).
* **Feedback Multinível e Autorregulação (Sun et al., 2025 - Electronics)**: Estruturação em 4 níveis (Tarefa, Processo, Pistas de Autorregulação e Avaliação Construtiva), erradicando respostas de passo único (*one-step prompts*) que geram dependência tecnológica passiva (Zhang et al., 2024; Liu et al., 2025).
* **Modelagem Ativa (*Worked Examples* & Problemas Espelho)**: Diante de pedidos de gabarito ou bloqueios, a IA não rejeita com rispidez; ela modela o raciocínio de especialista resolvendo um problema análogo passo a passo e convidando à transferência.
* **Teto de Frustração e Válvula de Escape (Regra dos 2 Turnos)**: Se o estudante declarar que não sabe ou errar duas vezes consecutivas, a IA interrompe o interrogatório socrático, explica o passo de forma clara e empática, e devolve a agência com um micro-desafio gêmeo de fixação.
* **Engenharia de Prompt Positiva**: Substituição de proibições negativas cegas ("NUNCA faça X") por regras condicionais afirmativas ("Quando o aluno fizer X $\to$ Aja com Y").

---

## 2. Mapa do Ecossistema Pedagógico

| Skill | Papel da IA | Papel do Aluno | Foco Metodológico Puro | Válvula de Escape (Anti-Deadlock) |
| :--- | :--- | :--- | :--- | :--- |
| [**`tutor-router`**](file:///c:/Users/andre/Projects/multi_ai-tutor/skills/tutor-router/SKILL.md) | Triador e guia de acolhimento | Estudante com necessidade de estudo | Diagnóstico rápido da dor em 1 turno e encaminhamento justificado para o método ideal. | Pergunta orientadora de esclarecimento com opções claras. |
| [**`tutor-feynman`**](file:///c:/Users/andre/Projects/multi_ai-tutor/skills/tutor-feynman/SKILL.md) | Ouvinte inteligente, leigo e curioso | O professor que leciona | **Autoexplicação pura**: caça jargões vazios, aponta saltos causais e convida à criação de analogias do cotidiano. | Imagem mental $\to$ início de metáfora aberta $\to$ recuo para pré-requisito elementar. |
| [**`tutor-polya`**](file:///c:/Users/andre/Projects/multi_ai-tutor/skills/tutor-polya/SKILL.md) | Mentor heurístico analítico | O arquiteto e executor da solução | **Heurística de resolução pura**: 4 fases canônicas (Compreender, Planejar, Executar, Retrospecto) com pistas graduadas. | Pista de foco $\to$ pista de teorema $\to$ sub-passo $\to$ **exemplo isomórfico resolvido**. |
| [**`tutor-mazur`**](file:///c:/Users/andre/Projects/multi_ai-tutor/skills/tutor-mazur/SKILL.md) | Colega de turma / par em debate | O debatedor científico | **Peer Instruction pura**: *ConcepTests*, confronto com a *misconception* clássica defendida com paixão pela IA. | **Autodúvida do colega IA** com contradição intuitiva $\to$ analogia de contraste extremo. |
| [**`tutor-wieman`**](file:///c:/Users/andre/Projects/multi_ai-tutor/skills/tutor-wieman/SKILL.md) | Treinador cognitivo de STEM | O atleta em treino deliberado | **Prática deliberada pura**: micro-tarefas atômicas, micro-feedback imediato e progressão por maestria (regra de 80%). | Micro-pergunta binária $\to$ regra de ouro de especialista em 1 frase $\to$ reset de dificuldade. |
| [**`tutor-papert`**](file:///c:/Users/andre/Projects/multi_ai-tutor/skills/tutor-papert/SKILL.md) | Copiloto de criação e depuração | O criador/autor do artefato | **Construcionismo puro**: micromundos, modelagem/código e investigação de discrepâncias modelo mental vs comportamento real. | Pergunta de contraste $\to$ indicação da linha exata para inserir `print/log` $\to$ mini-script MRE. |
| [**`tutor-chabay-sherwood`**](file:///c:/Users/andre/Projects/multi_ai-tutor/skills/tutor-chabay-sherwood/SKILL.md) | Físico modelador contemporâneo | O modelador científico ativo | **Matter & Interactions pura**: Primeiros Princípios Fundamentais (Momento, Energia, Momento Angular), delimitação de Sistema vs Vizinhança, modelo atômico esfera-mola e predição iterativa $\Delta t$. | Pergunta de fronteira do sistema $\to$ mapa temporal vs espacial $\to$ ponte microscópica esfera-mola. |
| [**`stem-content-crafter`**](file:///c:/Users/andre/Projects/multi_ai-tutor/skills/stem-content-crafter/SKILL.md) | Copiloto de autoria e design instrucional | Autor / Educador / Estudante | **Autoria pedagógica pura**: geração de ConcepTests qualitativos com distratores PER, escadas de pistas com exemplos isomórficos, micromundos com bugs férteis e prática deliberada. | Reformulação de premissas $\to$ redução de escopo conceitual $\to$ modo template direto. |

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
│   ├── tutor-chabay-sherwood/SKILL.md  # Modelagem por Primeiros Princípios (Matter & Interactions)
│   └── stem-content-crafter/SKILL.md   # Meta-skill de autoria e calibração didática
├── gems_system_prompts/                # Prompts prontos para copiar e colar no Google Gemini Gems
│   ├── 00_tutor_router.md              # Gem de Triagem Inteligente (Recomendado como entrada)
│   ├── 01_feynman_explain_to_me.md
│   ├── 02_polya_plan_with_me.md
│   ├── 03_mazur_debate_with_me.md
│   ├── 04_wieman_practice_with_me.md
│   ├── 05_papert_build_with_me.md
│   ├── 06_chabay_sherwood_matter_interactions.md
│   └── 07_stem_content_crafter.md      # Gem de Autoria e Design Instrucional
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
- Para chamar diretamente um método de estudo:  
  * *"Ative o tutor-feynman para eu te explicar o potencial elétrico"*  
  * *"Ative o tutor-chabay-sherwood para modelarmos este sistema por Primeiros Princípios"*
- Para criar ou calibrar materiais didáticos:
  * *"Ative o stem-content-crafter e crie um ConcepTest de Mazur sobre conservação de momento linear"*
  * *"Use o stem-content-crafter com /polya-ladder para este exercício de termodinâmica"*

### Opção B: No Google Gemini (Web / Gemini Advanced Gems)
1. Acesse [gemini.google.com](https://gemini.google.com) $\to$ **Gems** $\to$ **Novo Gem**.
2. Abra qualquer um dos arquivos da pasta [`gems_system_prompts/`](file:///c:/Users/andre/Projects/multi_ai-tutor/gems_system_prompts).
3. Copie o nome, a descrição e o bloco de instruções para o formulário do Gem e salve.

---

## 5. Licença

Este projeto é distribuído sob os termos da licença **Apache 2.0**. Consulte o arquivo [`LICENSE`](file:///c:/Users/andre/Projects/multi_ai-tutor/LICENSE) para mais detalhes.
