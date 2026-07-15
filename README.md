# A75 Co. — Precisão e Exclusividade

Vitrine oficial da A75 Co., marca de relógios e joias de alto padrão.

Este repositório contém a versão **front-end estática** do site (HTML/CSS/JS puro, sem build). Pronta para publicar em qualquer serviço de hospedagem gratuita.

## Estrutura

```
a75-site/
├── index.html       ← site completo (home, coleções, produtos, carrinho, etc.)
├── assets/
│   └── logo-a75.png ← logo original da marca
└── README.md
```

## Como publicar gratuitamente

### Opção 1 — Netlify Drop (mais rápido)
1. Acesse https://app.netlify.com/drop
2. Arraste a pasta `a75-site` inteira
3. Pronto — URL gerada na hora (ex: `a75-co.netlify.app`)

### Opção 2 — GitHub Pages
1. Suba este repositório para o GitHub
2. Vá em **Settings → Pages**
3. Em "Source", selecione a branch `main` e a pasta `/root`
4. Salve — o site fica em `seuusuario.github.io/nome-do-repo`

### Opção 3 — Vercel (recomendada para evoluir com backend depois)
1. Crie conta em https://vercel.com (login com GitHub)
2. Clique em "Add New Project" e selecione este repositório
3. Deploy automático — nenhuma configuração extra necessária
4. A cada `git push`, o site atualiza sozinho

## Domínio próprio

Depois de publicar em qualquer uma das opções acima, é possível conectar um domínio próprio (ex: `a75co.com.br`) gratuitamente nas configurações de "Domain" de cada plataforma. Você só paga pelo registro do domínio em si (num registrador como Registro.br, Namecheap, GoDaddy).

## Próxima fase

Este é o front-end estático da vitrine. As próximas etapas — banco de dados, autenticação, pagamento (Stripe/Mercado Pago) e painel administrativo — exigem um projeto full-stack (Next.js + Prisma) e são ideais para construir com **Claude Code**, evoluindo este mesmo repositório.

---
© 2026 A75 Co. Todos os direitos reservados.
