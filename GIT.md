# 🧰 Guia Prático de Git

Este guia contém comandos essenciais e boas práticas para usar o Git de forma eficiente no controle de versões de seus projetos.

---

## 📦 Inicialização e configuração

### Iniciar um repositório Git:
```bash
git init
```

### Configurar nome e e-mail:
```bash
git config --global user.name "Jeffersonmk"
git config --global user.email "seu-email@email.com"
```

### Ver configurações atuais:
```bash
git config --list
```

---

## 📁 Trabalhando com commits

### Verificar status:
```bash
git status
```

### Adicionar arquivos:
```bash
git add arquivo.txt          # arquivo específico
git add .                    # todos os arquivos modificados
```

### Fazer um commit:
```bash
git commit -m "tipo: mensagem do commit"
```

### Ver histórico:
```bash
git log                      # lista todos os commits
git log --oneline            # versão compacta
```

---

## 🌐 Repositórios remotos

### Adicionar um repositório remoto:
```bash
git remote add origin https://github.com/seu-usuario/repositorio.git
```

### Enviar para o repositório remoto:
```bash
git push -u origin main      # primeira vez
```

### Clonar um repositório existente:
```bash
git clone https://github.com/usuario/repositorio.git
```

---

## 🌿 Ramificações (branches)

### Criar uma nova branch:
```bash
git checkout -b nome-da-branch
```

### Mudar de branch:
```bash
git switch nome-da-branch
```

### Mesclar branches:
```bash
git merge nome-da-branch
```

### Deletar uma branch:
```bash
git branch -d nome-da-branch
```

---

## 🔄 Atualizando repositórios

### Puxar atualizações do remoto:
```bash
git pull
```

### Buscar atualizações (sem aplicar):
```bash
git fetch
```

---

## 🚑 Outros comandos úteis

### Ver alterações em arquivos:
```bash
git diff
```

### Cancelar modificações locais:
```bash
git restore arquivo.txt
```

### Remover arquivo do controle do Git:
```bash
git rm --cached arquivo.txt
```

---

👨‍💻 Licença: MIT (ver arquivo `LICENSE`)
📬 Contato: [jefferson20042011@protonmail.com]
