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

👨‍💻 Licença: MIT (ver arquivo `LICENSE`)
📬 Contato: [jefferson20042011@protonmail.com]