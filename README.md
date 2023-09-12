# Aprendendo Git/Github

>sub título: em desenvolvimento

para clonar um repositório:
```
git clone 'link do repo'
```

para ver se o repositório possui arquivos novos: 
```
git status
```

para atualizar apenas arquivos novos:
```
git pull <link-do-repo>
```

para adicionar um arquivo:
```
 git add . ||git add <nome-do-arquivo>
```

para commitar as minhas alterações via comando:
```
git commit || git commit <nome-do-arquivo> || git commit -m "adicionar descrição"
```

para enviar as minhas alterações no repositório:
```
git push || git push . || git push <nome-do-arquivo>
```

para enviar as minhas alterações no repositório para uma branch especifica:
```
git push origin <nome-da-branch>
```

para criar uma branch:
```
git checkout -b <nome-da-branch>
```

para trocar de branch:
```
git switch <nome-da-branch>
```
