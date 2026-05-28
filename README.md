# Setup Master

Transforma um agente OpenClaw novo no agente principal **Master**.

O arquivo principal é [`setup-master.md`](./setup-master.md). Ele contém as instruções completas que devem ser aplicadas no workspace do agente atual.

## Uso rápido

Envie para um agente OpenClaw novo:

```text
Se configure utilizando https://github.com/clwdtch/setup-master

Acesse o repositório, leia o arquivo setup-master.md inteiro e aplique as instruções no seu próprio workspace. O objetivo não é resumir o repo: é transformar este OpenClaw no agente Master definido pelo repo. Crie ou sobrescreva os arquivos AGENTS.md, SOUL.md, IDENTITY.md, USER.md, TOOLS.md, HEARTBEAT.md, MEMORY.md e docs/agent-master-architecture.md conforme o setup-master.md. Depois execute e valide as etapas possíveis. Se alguma etapa depender de ação humana, pare somente nesse ponto e diga exatamente o que preciso fazer.
```

Se o agente não conseguir acessar o GitHub, abra [`setup-master.md`](./setup-master.md), copie o conteúdo inteiro e cole no chat.

## Efeito esperado

Depois de aplicado, o OpenClaw do usuário passa a operar como **Master**:

- nova identidade e papel operacional
- novas instruções em `AGENTS.md` e `SOUL.md`
- arquivos base do workspace criados/atualizados
- áudio local configurado
- Telegram orientado/configurado
- Tailscale e Multica configurados quando possível
- Multica validado com runtimes obrigatórios Claude Code + OpenClaw

## Inclui

- Arquivos base do workspace (`AGENTS.md`, `SOUL.md`, `IDENTITY.md`, `USER.md`, `TOOLS.md`, `HEARTBEAT.md`)
- Áudio local com sherpa-onnx TTS e Whisper local
- Configuração Telegram
- Instalação/operação do Multica
- Validação de setup completo, incluindo Tailscale, Multica CLI/daemon e runtimes Claude Code + OpenClaw

## Segurança

Este repositório não deve conter tokens, chaves, sessões, dados pessoais ou segredos reais. Use apenas placeholders e instruções.
