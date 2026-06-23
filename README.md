# Gisele English — Painel de Gestão

App web progressivo (PWA) para gestão do Projeto Gisele English.

## Como subir no Vercel

### Opção 1 — GitHub + Vercel (recomendado)

1. Crie um repositório no GitHub (pode ser privado)
2. Faça upload de todos os arquivos desta pasta
3. Acesse [vercel.com](https://vercel.com) e clique em "Add New Project"
4. Conecte o repositório do GitHub
5. Clique em Deploy — pronto

### Opção 2 — Vercel CLI

```bash
npm i -g vercel
cd gisele-english
vercel --prod
```

## Adicionar ao celular (como app)

**iPhone (Safari):**
1. Abra o link do Vercel no Safari
2. Toque no botão de compartilhar (quadrado com seta)
3. "Adicionar à Tela de Início"
4. O app aparece como ícone na home

**Android (Chrome):**
1. Abra o link no Chrome
2. Menu (3 pontos) → "Adicionar à tela inicial"
3. Confirme

## Estrutura

```
gisele-english/
├── index.html      ← app completo
├── manifest.json   ← configuração PWA
├── vercel.json     ← roteamento Vercel
└── README.md
```

## Funcionalidades

- 6 seções: Visão Geral, Metas, Avatar, Conteúdo, Gerador IA, Ações
- Gerador de scripts com IA (Claude)
- Gerador de mensagem WhatsApp personalizada
- Checklist interativo com progresso salvo localmente
- Funciona em celular como app (PWA)
- Dark mode automático
