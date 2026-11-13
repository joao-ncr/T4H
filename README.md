# Desafio T4H · Hackathon UNIFEI 2026

Código do nosso time para o Desafio T4H (14/11/2026, IEPG · UNIFEI): agentes de IA que trabalham numa empresa fictícia simulada por um servidor MCP.

Este repositório guarda **só o que é do time** (agentes, documentação e configuração de exemplo). O kit oficial do evento e o servidor MCP ficam no repositório da Tech for Humans e **não são copiados aqui**.

## Kit oficial (servidor MCP)

Repositório oficial: <https://github.com/tech4humans-brasil/t4h-desafios>

Cada integrante clona o kit na própria máquina, ao lado deste repositório:

```bash
git clone https://github.com/tech4humans-brasil/t4h-desafios.git
```

Tudo do evento fica na pasta `Hackathon - UNIFEI 2026`. Para subir o servidor, siga a seção **Como rodar** do `README.md` de `Servidor MCP (Compartilhado)`. Com o servidor no ar, o painel abre em <http://localhost:8765> e os agentes se conectam em `http://localhost:8765/mcp`.

> Não alteramos o servidor: os nossos agentes é que se adaptam a ele.

## Como o time trabalha

1. Cada pessoa clona **este repositório** e o **kit oficial**, lado a lado.
2. Cada pessoa trabalha em uma branch própria e junta por Pull Request.
3. A chave de API do evento (entregue no dia) fica **somente** num arquivo `.env` local, que não vai para o Git. Nunca colocar chave no código.

## Estrutura

```
.
├── README.md      # este arquivo
├── .gitignore
└── ...            # agentes e demais arquivos do time
```
