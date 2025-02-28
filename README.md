# Comandos Git Essenciais
| Comando Git | Xyms :) 

## 🔹 **Trabalhando com Repositórios**
| `git clone` | 📥 Copia o repositório do GitHub para sua máquina local. 

| `git init` | 🏁 Inicializa um novo repositório Git na pasta atual. 

| `git remote add origin <URL>` | 🔗 Conecta seu repositório local a um repositório remoto. 

| `git remote set-url origin https://github.com/usuario/novo-repo.git` | 💨 Mudar o repositório remoto padrão. 

| `git fetch` | 🔄 Obtém as últimas atualizações do repositório remoto sem aplicá-las. 

---

## 🔹 **Trabalhando com Branches**
| `git branch` | 🌿 Lista todas as branches do repositório. 

| `git branch -a` | 🌍 Exibe todas as branches locais e remotas. 

| `git branch -d nome_da_branch` | ✂️ Deleta uma branch localmente. 

| `git branch -D nome_da_branch` | ✂️ Deleta uma branch localmente, mesmo que ela não tenha sido mesclada (forçado). 

| `git checkout -b nova_branch` | 🌱 Cria uma nova branch e muda para ela. 

| `git checkout main` | 🔄 Alterna para a branch principal do projeto. 

---

## 🔹 **Trabalhando com Commits**
| `git commit -m "Mensagem do commit"` | 💾 Salva as mudanças localmente com uma mensagem descritiva. 

| `git commit --amend` | ✍️ Modifica o último commit (útil para corrigir mensagens ou adicionar arquivos). 

| `git reset --soft HEAD~1` | 🛠️ Desfaz o último commit, mantendo as alterações no stage. 

| `git reset --hard HEAD~1` | ⚠️ Remove completamente o último commit e suas alterações. 

| `git revert <commit-hash>` | ⏪ Desfaz um commit específico sem apagar o histórico. 

---

## 🔹 **Trabalhando com Arquivos**
| `git add .` | ➕ Adiciona todas as mudanças feitas ao repositório local. |

| `git rm --cached nome_do_arquivo` | 🗑️ Remove um arquivo do rastreamento do Git sem deletá-lo do sistema. 

| `touch .gitignore` | 🚫 Cria um arquivo `.gitignore` para ignorar arquivos desnecessários no repositório. 

| `echo "node_modules/" >> .gitignore` | 📂 Adiciona `node_modules` ao `.gitignore`, evitando o upload da pasta para o repositório. |

---

## 🔹 **Atualizando o Repositório Remoto**
| `git push origin main` | 🚀 Envia as mudanças locais para o repositório remoto no GitHub. 

| `git pull origin main --rebase` | 🔄 Garante que seu código esteja atualizado antes de fazer novas alterações. 

| `git push origin main --force` | ⚠️ Sobrescreve as mudanças remotas com as locais. **Use apenas se necessário!** 

---

## 🔹 **Resolvendo Conflitos e Ferramentas**
| `git merge nome_da_branch` | 🔗 Mescla uma branch específica na branch atual. 

| `git mergetool` | 🛠️ Abre uma ferramenta de merge para resolver conflitos (se configurado). 

---

## 🔹 **Verificando o Status e Log**
| `git status` | 📢 Mostra o estado atual dos arquivos no repositório. 

| `git log` | 📜 Exibe o histórico de commits do repositório. 

| `git log --oneline` | 🔍 Mostra um resumo compacto dos commits. 

---

## 🔹 **Outros Comandos Úteis**
| `git cherry-pick <commit-hash>` | 🍒 Aplica um commit específico de outra branch na branch atual. 

| `git stash` | 💾 Salva temporariamente mudanças locais sem fazer um commit. 

| `git stash pop` | 🔄 Restaura as mudanças salvas anteriormente com `git stash`. 
