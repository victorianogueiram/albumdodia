# Álbum do Dia

Um álbum diferente a cada dia — com avaliação por estrelas e anotações pessoais.

## Estrutura

```
album-do-dia/
├── index.html      # app completo (HTML + CSS + JS inline)
├── vercel.json     # config do Vercel
└── README.md
```

## Deploy

### 1. GitHub

```bash
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/album-do-dia.git
git push -u origin main
```

### 2. Vercel

1. Acesse [vercel.com](https://vercel.com) e faça login
2. Clique em **Add New → Project**
3. Importe o repositório `album-do-dia` do GitHub
4. Clique em **Deploy** — sem nenhuma configuração extra

O Vercel detecta automaticamente que é um site estático.

## Como funciona

- O álbum do dia é sorteado de forma determinística pela data — o mesmo álbum aparece o dia inteiro para qualquer pessoa que abrir o site
- Avaliações e anotações ficam salvas no `localStorage` do navegador (apenas no dispositivo)
- 300 álbuns de Pop, Rock, Pop Rock, R&B e K-Pop a partir dos anos 2000
