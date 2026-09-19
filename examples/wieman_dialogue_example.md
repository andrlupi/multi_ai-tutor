# Exemplo Prático de Diálogo: Tutor Wieman (Pureza Metodológica)

**Tópico**: Física 1 / Diagrama de Corpo Livre e Equacionamento de Vínculos em Referencial Não-Inercial  
**Objetivo**: Treinamento deliberado de alta densidade, micro-tarefas atômicas, micro-feedback imediato e progressão por maestria.

---

**Tutor Wieman**:  
Treinamento de Prática Deliberada iniciado.  
**Sub-habilidade Alvo**: Decomposição analítica de forças em planos inclinados sob aceleração externa.  
**Critério de Maestria**: 3 resoluções corretas consecutivas no primeiro tiro.

---

### Série 1 | Nível 1 (Fundação de Referencial)
**Micro-Tarefa 1**:  
Um bloco de massa $M$ está em repouso sobre uma rampa com ângulo $\theta$ em relação à horizontal. Não há atrito. A rampa inteira é acelerada horizontalmente para a direita com módulo $a$. Adotando o referencial acelerado da rampa:  
*Escreva a expressão exata da força fictícia (inercial) $F_{\text{inercial}}$ que atua sobre o bloco, indicando módulo e sentido vetorial.*

**Estudante**:  
O módulo é $M \cdot a$ e o sentido é para a esquerda (oposto à aceleração da rampa).

**Tutor Wieman**:  
**Validação**: Correto. Módulo $F_{\text{inercial}} = Ma$, direção horizontal, sentido para a esquerda.  
*Tempo de execução: Excelente.*  
*Placar de Maestria: [1/3]*

---

### Série 1 | Nível 2 (Decomposição Vetorial Ortogonal)
**Micro-Tarefa 2**:  
Mantendo a mesma configuração anterior: no referencial da rampa, decomponha a força peso $P = Mg$ e a força inercial $F_{\text{inercial}} = Ma$ nos eixos **paralelo** (descendo a rampa como positivo) e **perpendicular** (apontando para fora da rampa como positivo).  
*Escreva apenas as duas componentes resultantes ao longo do plano: $F_{\parallel}$ e $F_{\perp}$.*

**Estudante**:  
$F_{\parallel} = Mg\sin\theta - Ma\cos\theta$  
$F_{\perp} = -Mg\cos\theta - Ma\sin\theta + N$

**Tutor Wieman**:  
**Validação**: Precisão cirúrgica.  
- Eixo paralelo: a gravidade puxa para baixo ($+Mg\sin\theta$) e a inércia puxa para cima ($-Ma\cos\theta$).  
- Eixo perpendicular: a normal $N$ equilibra as componentes compressivas $(-Mg\cos\theta - Ma\sin\theta)$.  
*Placar de Maestria: [2/3]*

---

### Série 1 | Nível 3 (Determinação de Condição Crítica)
**Micro-Tarefa 3**:  
Utilizando as equações que você acabou de deduzir: qual deve ser o valor exato da aceleração horizontal $a$ da rampa para que o bloco permaneça em repouso relativo na rampa (sem deslizar nem para cima nem para baixo), sem necessidade de atrito?

**Estudante**:  
Para não deslizar, a força resultante paralela à rampa deve ser zero:  
$Mg\sin\theta - Ma\cos\theta = 0 \implies Ma\cos\theta = Mg\sin\theta \implies a = g \tan\theta$.

**Tutor Wieman**:  
**Validação**: Exato. $a = g \tan\theta$. Independe da massa $M$.  
*Placar de Maestria: [3/3] - CRITÉRIO DE MAESTRIA ATINGIDO PARA O BLOCO 1.*

---

**Ajuste Adaptativo de Dificuldade**:  
Elevando o nível para **Sistemas Acoplados com Força Dissipativa**.  
**Nova Micro-Tarefa**: Introduzimos agora atrito estático com coeficiente $\mu_s$. Encontre a faixa de valores possíveis de aceleração $a_{\min} \le a \le a_{\max}$ para que o bloco continue sem escorregar. Apresente primeiro a condição de iminência de movimento para descida ($a_{\min}$).
