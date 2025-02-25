| Comando Git | Xyms :) |
|------------|------------|
| `git clone` | 📥 Copia o repositório do GitHub para sua máquina local. |
| `cd nome-repositorio` | 📂 Acessa a pasta do projeto após cloná-lo. |
| `git init` | 🏁 Inicializa um novo repositório Git na pasta atual. |
| `git add .` | ➕ Adiciona todas as mudanças feitas ao repositório local. |
| `git commit -m "Mensagem do commit"` | 💾 Salva as mudanças localmente com uma mensagem descritiva. |
| `git push origin main` | 🚀 Envia as mudanças locais para o repositório remoto no GitHub. |
| `git pull origin main --rebase` | 🔄 Garante que seu código esteja atualizado antes de fazer novas alterações. |
| `git push origin main --force` | ⚠️ Sobrescreve as mudanças remotas com as locais. **Use apenas se necessário!** |
| `git log` | 📜 Exibe o histórico de commits do repositório. |
| `git log --oneline` | 🔍 Mostra um resumo compacto dos commits. |
| `git status` | 📢 Mostra o estado atual dos arquivos no repositório. |
| `git remote add origin <URL>` | 🔗 Conecta seu repositório local a um repositório remoto. |
| `git branch` | 🌿 Lista todas as branches do repositório. |
| `git checkout -b nova_branch` | 🌱 Cria uma nova branch e muda para ela. |
| `git checkout main` | 🔄 Alterna para a branch principal do projeto. |
| `git branch -d nome_da_branch` | ✂️ Deleta uma branch localmente. |
| `git merge nome_da_branch` | 🔗 Mescla uma branch específica na branch atual. |
| `git reset --hard` | ❌ Remove todas as alterações locais e reseta o código para o último commit. |
| `git rm --cached nome_do_arquivo` | 🗑️ Remove um arquivo do rastreamento do Git sem deletá-lo do sistema. |
| `touch .gitignore` | 🚫 Cria um arquivo `.gitignore` para ignorar arquivos desnecessários no repositório. |
| `echo "node_modules/" >> .gitignore` | 📂 Adiciona `node_modules` ao `.gitignore`, evitando o upload da pasta para o repositório. |
| `git fetch` | 🔄 Obtém as últimas atualizações do repositório remoto sem aplicá-las. |
| `git rebase main` | 🛠️ Aplica as mudanças da branch principal na branch atual de forma linear. |
| `git stash` | 💾 Salva temporariamente mudanças locais sem fazer um commit. |
| `git stash pop` | 🔄 Restaura as mudanças salvas anteriormente com `git stash`. |
| `git cherry-pick <commit-hash>` | 🍒 Aplica um commit específico de outra branch na branch atual. |
| `git revert <commit-hash>` | ⏪ Desfaz um commit específico sem apagar o histórico. |
| `git reset --soft HEAD~1` | 🛠️ Desfaz o último commit, mantendo as alterações no stage. |
| `git reset --hard HEAD~1` | ⚠️ Remove completamente o último commit e suas alterações. |

🚀
