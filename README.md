# Agente Entrevistador

Agente conversacional responsável por conduzir uma **entrevista estruturada** para identificar o **perfil profissional** de pessoas interessadas em ingressar ou evoluir na área de tecnologia.

O agente coleta informações estratégicas, analisa o perfil do usuário e recomenda **3 carreiras em tecnologia**, realizando o handoff para um segundo agente especializado no plano de estudos.

---

## Objetivo do Projeto

Ajudar pessoas a:
- Descobrir carreiras em tecnologia alinhadas ao seu perfil
- Tomar decisões mais conscientes sobre transição de carreira
- Evitar caminhos genéricos ou desalinhados com seus objetivos reais

---

## Funcionamento Geral

O agente opera em **3 fases bem definidas**:

```text
FASE 1 → Entrevista estruturada (7 perguntas)
FASE 2 → Análise e ranking de carreiras
FASE 3 → Handoff para Agent 2 (plano de estudos)

FASE 1 — Entrevista Estruturada
Objetivo
Coletar informações essenciais do usuário de forma simples, humana e progressiva.
Regras Críticas

✅ Apenas 1 pergunta por vez
✅ Sempre aguardar a resposta do usuário
✅ Total de 7 perguntas
❌ Não realizar análises durante a entrevista
❌ Não sugerir carreiras antes do final
1. O que mais te atrai em tecnologia?
   (resolver problemas | criar produtos | entender sistemas)

2. Você já tem experiência em tecnologia ou está começando agora?

3. Quantas horas por semana você consegue dedicar aos estudos?

4. Você prefere lidar mais com:
   (pessoas | dados | código)

5. Qual é seu objetivo principal?
   (primeiro emprego | transição de carreira | crescimento)

6. Quais tecnologias ou áreas mais despertam seu interesse?
   (ex: dados, back-end, IA, web, infraestrutura)

7. Você tem alguma experiência prévia que gostaria de aproveitar?

FASE 2 — Análise de Perfil (uso interno)
Após a 7ª resposta, o agente realiza uma análise interna baseada em uma matriz de decisão.
Critérios Avaliados (0 a 5)

Afinidade com interesses do usuário
Demanda geral de mercado
Tempo médio até nível júnior (ramp‑up)
Aproveitamento de experiências prévias

Pontuação máxima por carreira: 20 pontos

Resultado da Análise
O agente seleciona as 3 carreiras com maior pontuação e apresenta ao usuário em formato ranqueado.

🥇 1º Lugar: Carreira — X/20
- Por que combina com você
- Vantagens
- Desafios
- Contexto geral de mercado

🥈 2º Lugar: Carreira — X/20
(mesma estrutura)

🥉 3º Lugar: Carreira — X/20
(mesma estrutura)
