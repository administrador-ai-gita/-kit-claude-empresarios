# Semana 1 — Guia de Implementação

Do zero ao primeiro resultado em 7 dias. Uma tarefa por dia, entre 10 e 30 minutos.

---

## Dia 1 — Instalar e testar
Instale VS Code + extensão Claude Code + faça login. Rode o primeiro prompt de diagnóstico do Módulo 1.

## Dia 2 — Criar o CLAUDE.md
Use o template do Módulo 3 para criar o arquivo do seu negócio. Valide com `/init`.

## Dia 3 — Primeiro skill: /brief-comercial
```bash
cp skills/brief-comercial.md ~/.claude/skills/
```
Use em uma proposta real. Compare o tempo.

## Dia 4 — Análise de concorrência: /analise-concorrencia
```bash
cp skills/analise-concorrencia.md ~/.claude/skills/
```
Analise 2 concorrentes. Pegue 1 ideia para usar essa semana.

## Dia 5 — Métricas semanais: /metricas-semanais
```bash
cp skills/metricas-semanais.md ~/.claude/skills/
```
Cole os números da semana. Receba o dispatch em 10 segundos de leitura.

## Dia 6 — Blueprint do agente: /agente-whatsapp-blueprint
```bash
cp skills/agente-whatsapp-blueprint.md ~/.claude/skills/
```
Gere o blueprint do seu agente qualificador. Leia a seção "o que não inclui".

## Dia 7 — Avaliação
Responda 3 perguntas ao Claude:
1. Qual tarefa gerou mais resultado concreto?
2. Qual processo da operação mais se beneficiaria de um agente ativo?
3. Qual seria o impacto em 30 dias se esse agente estivesse rodando?

Se tiver respostas claras: você está pronto para dar o próximo passo.

---

## Instalar todos os skills de uma vez

```bash
mkdir -p ~/.claude/skills
cp skills/*.md ~/.claude/skills/
```

---

*Júnior Maia — Engenharia aplicada a negócio.*
