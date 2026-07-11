# Como publicar o perfil no GitHub

## 1. Criar o repositório de perfil

1. Acesse https://github.com/new
2. Nome do repositório: **`DaviAScosta`** (igual ao seu username)
3. Marque como **Public**
4. **Não** adicione README, .gitignore ou licença (já existem aqui)
5. Clique em **Create repository**

## 2. Enviar estes arquivos

```powershell
cd C:\Users\davia\Projects\DaviAScosta
git init
git add .
git commit -m "feat: adicionar README de perfil"
git branch -M main
git remote add origin https://github.com/DaviAScosta/DaviAScosta.git
git push -u origin main
```

## 3. Ajustar links pessoais no README

Edite `README.md` e troque:

- LinkedIn → seu perfil real
- Email → seu email de contato

## 4. Completar o perfil no GitHub

Em https://github.com/settings/profile:

| Campo | Sugestão |
|-------|----------|
| **Bio** | Desenvolvedor · Django & Next.js · Construindo o CountSys |
| **Location** | Brasil |
| **Website** | https://github.com/DaviAScosta/CountSys |

## 5. Melhorar o repositório CountSys

Em https://github.com/DaviAScosta/CountSys/settings:

**Description:**
```
Plataforma de gestão operacional interna para escritórios de contabilidade. Django + Next.js · DDD · Monólito modular.
```

**Topics (sugestão):**
```
django, nextjs, typescript, python, ddd, monorepo, accounting, rest-api, postgresql, docker
```

**Pin:** fixe o CountSys no topo do perfil (Customize your pins).

## 6. Cobrinha de contribuições

O workflow `.github/workflows/snake.yml` roda automaticamente todo dia.
Na primeira vez, vá em **Actions** → **Generate Snake** → **Run workflow**.
