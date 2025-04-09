# 🌿 Guia de Estratégia de Branches

## 🗂️ Estrutura Recomendada

- `main` → Versão estável em produção
- `develop` → Versão de desenvolvimento principal
- `feature/*` → Novas funcionalidades
- `fix/*` → Correções pontuais
- `hotfix/*` → Correções urgentes em produção
- `release/*` → Preparação para nova versão

## 🔄 Fluxo de Trabalho Sugerido (Git Flow)

1. Desenvolva novas features a partir de `develop`
2. Faça o merge da feature quando estiver finalizada
3. Crie uma `release/x.x.x` a partir de `develop` para preparar o deploy
4. Após testes, faça merge da `release` em `main` e `develop`
5. Em caso de bugs críticos, crie `hotfix` a partir de `main` e depois faça merge em `develop` também

## 📝 Exemplo de Nomes de Branches

```bash
git checkout -b feature/login-page
git checkout -b fix/navbar-position
git checkout -b hotfix/login-redirect-error
git checkout -b release/1.0.0
```

## 📌 Boas Práticas

- Use nomes descritivos e separados por hífens
- Sempre remova branches antigas após merge
- Trabalhe com pull requests para revisão
- Mantenha `main` sempre pronta para deploy

---

👨‍💻 Licença: MIT (ver arquivo `LICENSE`)
📬 Contato: [jefferson20042011@protonmail.com]