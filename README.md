# Setup Master

Prompt de bootstrap para configurar um agente principal **Master** no OpenClaw.

O arquivo principal é [`setup-master.md`](./setup-master.md). Cole o conteúdo inteiro no chat com um agente OpenClaw novo para criar/configurar o workspace do Master.

## Uso rápido

Envie para um agente OpenClaw novo:

```text
Se configure utilizando https://github.com/clwdtch/setup-master

Acesse o repositório, leia o arquivo setup-master.md inteiro e siga todas as instruções dele. Não faça apenas um resumo. Execute o setup no ambiente atual, crie/atualize os arquivos solicitados e valide cada etapa. Se alguma etapa depender de ação humana, pare somente nesse ponto e diga exatamente o que preciso fazer.
```

Se o agente não conseguir acessar o GitHub, abra [`setup-master.md`](./setup-master.md), copie o conteúdo inteiro e cole no chat.

## Inclui

- Arquivos base do workspace (`AGENTS.md`, `SOUL.md`, `IDENTITY.md`, `USER.md`, `TOOLS.md`, `HEARTBEAT.md`)
- Áudio local com sherpa-onnx TTS e Whisper local
- Configuração Telegram
- Criação de sub-agentes
- Instalação/operação do Multica
- Validação de setup completo, incluindo Tailscale, Multica CLI/daemon e runtimes Claude Code + OpenClaw

## Segurança

Este repositório não deve conter tokens, chaves, sessões, dados pessoais ou segredos reais. Use apenas placeholders e instruções.
