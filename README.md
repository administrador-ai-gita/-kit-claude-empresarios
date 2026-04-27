# Kit Claude Code para Empresários

Skills prontos para instalar no Claude Code. Cada arquivo é um comando personalizado que você usa direto no chat.

## Instalação

```bash
# Crie a pasta de skills (só na primeira vez)
mkdir -p ~/.claude/skills

# Copie todos os skills de uma vez
cp skills/*.md ~/.claude/skills/
```

Pronto. Os comandos ficam disponíveis automaticamente no Claude Code.

## Skills incluídos

| Comando | O que faz |
|---|---|
| `/brief-comercial` | Gera proposta comercial estruturada a partir do contexto do cliente |
| `/metricas-semanais` | Transforma dados de performance em dispatch executivo semanal |
| `/resposta-qualificada` | Analisa conversa com lead e sugere a melhor resposta para o momento |
| `/analise-concorrencia` | Analisa concorrentes e gera ideias de conteúdo e posicionamento |

## Como usar

Após instalar, abra o Claude Code no VS Code, digite `/` no chat e o skill aparece na lista.

Exemplo:

```
/brief-comercial

Cliente: Empresa X
Problema: precisa reduzir tempo de atendimento
O que estou ofertando: implantação de agente de WhatsApp
Investimento: R$ 5.000
```

## Kit completo

Este repositório faz parte do **Kit Claude Code para Empresários**.

O guia completo está no ClickUp: https://app.clickup.com/9010129117/docs/8cgqa6x-14393

---

*Por Júnior Maia — Engenharia aplicada a negócio.*
