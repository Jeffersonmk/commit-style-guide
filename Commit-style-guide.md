![Banner do Projeto](./img/banner.png)

# 📘 Guia de Commits Estruturados

Este repositório contém um guia completo para escrever mensagens de commit de forma padronizada, clara e eficiente, usando o padrão **Conventional Commits**.

## 🧭 Objetivo
Organizar e padronizar o histórico de versões de projetos, tornando o desenvolvimento mais colaborativo, compreensível e fácil de manter.

---

## 📚 Índice do Repositório

- [`COMMIT-STYLE-GUIDE.md`](./Commit-style-guide): Guia de commits estruturados (este arquivo)
- [`MARKDOWN.md`](./MARKDOWN.md): Sintaxe básica de Markdown
- [`GIT.md`](./GIT.md): Comandos e boas práticas com Git
- [`BRANCHES.md`](./BRANCHES.md): Estratégias de ramificação no Git
- [`LICENSE`](./LICENSE): Licença do projeto (MIT)

### 📦 Download dos Arquivos Individuais

Você pode baixar os arquivos separadamente aqui:

- [📄 Commit-style-guide.md](https://raw.githubusercontent.com/Jeffersonmk/commit-style-guide/main/Commit-style-guide.md)
- [📄 MARKDOWN.md](https://raw.githubusercontent.com/Jeffersonmk/commit-style-guide/main/MARKDOWN.md)
- [📄 GIT.md](https://raw.githubusercontent.com/Jeffersonmk/commit-style-guide/main/GIT.md)
- [📄 BRANCHES.md](https://raw.githubusercontent.com/Jeffersonmk/commit-style-guide/main/BRANCHES.md)
- [📜 LICENSE](https://raw.githubusercontent.com/Jeffersonmk/commit-style-guide/main/LICENSE)

---

# ✅ Tipos de Commit

### `feat` → **Nova funcionalidade**
Adiciona um novo recurso ao sistema.
```bash
feat: adicionar sistema de autenticação com JWT
```

### `fix` → **Correção de bugs**
Corrige um comportamento inesperado ou problema no código.
```bash
fix: corrigir erro na validação de formulário
```

### `docs` → **Documentação**
Modifica ou adiciona arquivos de documentação.
```bash
docs: atualizar instruções de instalação no README
```

### `style` → **Estilo e formatação**
Mudanças que não afetam a lógica do código (espaços, ponto e vírgula, indentação).
```bash
style: remover espaços em branco desnecessários
```

### `refactor` → **Refatoração**
Melhora a estrutura do código sem alterar sua funcionalidade.
```bash
refactor: extrair função para evitar duplicação de código
```

### `test` → **Testes**
Adiciona ou modifica testes (unitários, integração, etc).
```bash
test: adicionar testes para o componente Header
```

### `chore` → **Tarefas auxiliares**
Alterações que não impactam diretamente o código da aplicação (renomeações, configs, dependências).
```bash
chore: renomear pastas e atualizar dependências
```

### `build` → **Build e dependências**
Mudanças no processo de build, bundlers, ou dependências.
```bash
build: configurar Webpack para produção
```

### `ci` → **Integração Contínua**
Mudanças nos pipelines de CI/CD.
```bash
ci: adicionar workflow de deploy automático
```

### `perf` → **Performance**
Alterações que visam melhorar o desempenho da aplicação.
```bash
perf: otimizar carregamento de imagens
```

### `revert` → **Reversão de commit**
Desfaz um commit anterior.
```bash
revert: remover alteração que causava falha no login
```

---

# 📌 Boas Práticas

- Commits pequenos e coesos
- Mensagens no imperativo e na forma curta
- Usar a descrição expandida para mudanças maiores

### Exemplo com descrição detalhada:
```bash
git commit -m "feat: criar componente de login"

# Linha em branco obrigatória

- Adicionado formulário de login
- Integração com backend
- Validação básica de campos
```

---

# 📂 Organização futura
Este repositório pode incluir outros guias, como:

- MARKDOWN.md → Guia de sintaxe Markdown
- GIT.md → Comandos e boas práticas com Git
- BRANCHES.md → Estratégia de ramificação

---

> Feito para desenvolvedores que valorizam código limpo, histórico legível e colaboração eficiente.

---

👨‍💻 Licença: MIT (ver arquivo `LICENSE`)
📬 Contato: [jefferson20042011@protonmail.com]

