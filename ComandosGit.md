<h3>Comandos Git básicos</h3>
<h5>1. git config</h5>
$ git config –global user.name “Seu nome” <p>
$ git config –global user.email “Seu email”
<h5>2. git init</h5>
$ git init <p>
$ git init (O nome do seu repositório) <p>
<h5>3. git clone</h5>
git clone (URL do seu projeto)
<h5>4. git add</h5>
$ git add seu_arquivo (esse comando irá adicionar o arquivo em específico ao repositório) <p>
$ git add * (esse comando irá adicionar todos os arquivos novos e/ou modificados ao repositório)
<h5>5. git commit</h5>
$ git commit -m “seu comentário”
<h5>6. git branch</h5>
$ git branch (lista todas as ramificações) <p>
$ git branch (nome_do_branch) (cria um branch com o nome especificado) <p>
$ git branch -d (nome_do_branch) (deleta o branch com o nome especificado)
<h5>7. git checkout</h5>
$ git checkout (nome_do_branch) <p>
$ git checkout -b (nome_do_branch_novo)
<h5>8. git remote</h5>
$ git remote add (nomecurto) (url)
<h5>9. git push</h5>
$ git push -u (nome_curto) (nome_do_branch) <p>
$ git push –set-upstream (nome_curto) (nome_do_branch)
<h5>10. git fetch</h5>
$ git fetch
<h5>11. git pull</h5>
$ git pull (URL)
<h5>12. git stash</h5>
$ git stash <p>
$ git stash list <p>
$ git stash apply
<h5>13. git show</h5>
$ git show (hash_do_commit)
<h5>14. git rm</h5>
$ git rm (nome_do_arquivo)
<h5>15. git help</h5>
$ git help (comando que se tem dúvida)
<h5>16. git merge</h5>
$ git merge (nome_do_branch)
<h5>17. git rebase</h5>
$ git rebase (base)
<h5>18. git pull –rebase</h5>
$ git pull –rebase
<h5>19. git cherry-pick</h5>
$ git cherry-pick (commit-hash)
<h5>20. git archive</h5>
$ git archive –format zip HEAD > archive-HEAD.zip
<h5>21. git blame</h5>
$ git blame (nome_do_arquivo)
<h5>22. git tag</h5>
$ git tag -a v1.0.0
<h5>23. git diff</h5>
$ git diff HEAD (nome_do_arquivo) <p>
$ git diff (branch de origem) (branch de destino)
<h5>24. git citool</h5>
$ git citool
<h5>25. git whatchanged</h5>
$ git whatchanged
