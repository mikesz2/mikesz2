# 🛒 Shopee Deal Machine V7.1 — Case de Portfólio

## Contexto

Projeto criado para automatizar o processo de encontrar, avaliar e distribuir ofertas da Shopee.

A solução reúne descoberta de produtos, leitura de fontes autorizadas, deduplicação, scoring, filtros, geração de link de afiliado e distribuição multicanal.

## Fluxo

```text
Shopee + fontes Telegram
          |
          v
      Ingestão
          |
          v
Deduplicação / Score
          |
          v
     Revalidação
          |
     +----+----+
     |         |
 Telegram  WhatsApp
```

## Stack

Python · FastAPI · SQLAlchemy · HTTPX · Telethon · Telegram Bot API · Evolution API v2 · Docker · Redis · PostgreSQL

## Recursos importantes

- fila persistente;
- deduplicação;
- cooldown;
- retries;
- recuperação por cursor;
- histórico de preços;
- filtros de qualidade;
- tracking por destino;
- publicação Telegram + WhatsApp;
- painel web operacional;
- execução Windows e Docker/Linux.

## Segurança

O repositório público não inclui:

- `.env` real;
- banco de dados de produção;
- sessões Telegram;
- chaves Shopee;
- tokens de bot;
- credenciais da Evolution API;
- logs ou backups com dados operacionais.

➡️ [Abrir repositório](https://github.com/mikesz2/SHOPEE-DEAL-MACHINE)

## Evidências visuais

Os screenshots serão adicionados usando somente o **projeto real em execução**.
