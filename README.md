# ✦ Manifestar — App de Lei da Atração

PWA baseado na teoria de manifestação do livro **O Segredo** (Rhonda Byrne).

## Funcionalidades

- **Afirmações diárias** — crie e marque afirmações no presente
- **Diário de gratidão** — registre gratidão, intenções e manifestações recebidas
- **Quadro de Visão** — visualize as 8 áreas da sua vida ideal
- **Rastreador de metas** — defina metas com progresso e prazo

## Tecnologia

- HTML, CSS e JavaScript puro (sem frameworks)
- PWA com Service Worker (funciona offline)
- Dados salvos em `localStorage`
- Deploy via Railway com `npx serve`

## Deploy local

```bash
npx serve .
```

Acesse `http://localhost:3000`

## Deploy Railway

1. Suba para o GitHub
2. Conecte o repositório no Railway
3. Railway detecta o `railway.toml` automaticamente
4. Gere o domínio em **Settings → Networking → Generate Domain**

## Estrutura

```
manifestar/
├── index.html       # App completo (single file)
├── manifest.json    # PWA manifest
├── sw.js            # Service Worker
├── railway.toml     # Config de deploy
└── .gitignore
```

---

Desenvolvido com ✦ por Elisabeth Motta
