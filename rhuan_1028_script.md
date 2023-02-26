**Instituição**: UMFG EDUCACIONAL LTDA S/S

**Curso**: Análise e Desenvolvimento de Sistemas

**Período**: 5º

**Matéria**: Tópicos especiais em computação aplicada

**Docente**: Rafael Albuquerque Rasso

<br>

**Aluno**: Rhuan Patriky de Sousa Ferrer

**R.A.**: 1028

<br>

## Atividade - Git

Exercício **1**:
```bash
git init ./git-basics/
```

Exercício **2**:
```bash
touch ./file.txt
```

Exercício **3**:
```bash
git add ./
```

Exercício **4**:
```bash
git commit -m 'initial commit'
```

Exercício **5**:
```bash
touch ./file{1..3}.txt
```

Exercício **6**:
```bash
git stash push -um 'Stash 1' file1.txt; git stash push -um 'Stash 2' file2.txt; git stash push -um 'Stash 3' file3.txt
```

Exercício **7**:
```bash
git stash pop stash@'{2}'; git add ./; git commit -m 'Comitando o stash 1'
```

Exercício **8**:
```bash
git stash pop stash@'{1}'; git stash pop stash@'{0}'; git add ./; git commit -m 'Comitando os stashes restantes'
```

Exercício **9**:
```bash
# nothing to do.
```
Exercício **10**:
```bash
# nothing to do.
```

Exercício **11**:
```bash
git remote add origin https://github.com/rhuan-pk/git-basics.git
```

Exercício **12**:
```bash
git push -u origin main
```

Exercício **13**:
```bash
# nothing to do.
```

Exercício **14**, **15**:
```bash
git switch -c my-primary-branch-1028
```

Exercício **16**:
```bash
touch ./new-file.txt; git add ./; git commit -m 'new file'; git push origin `git branch --show-current`
```

Exercício **17**:
```bash
# nothing to do.
```

Exercício **18**:
```bash
git switch main
```

Exercício **19**:
```bash
git pull origin main
```

Exercício **20**:
```bash
git switch -c minha-segunda-branch-1028
```

Exercício **21**:
```bash
touch ./other-file.txt; git add ./; git commit -m 'que desejar'
```

Exercício **22**:
```bash
git switch main; git merge minha-segunda-branch-1028
```

Exercício **23**:
```bash
git push origin main
```

Exercício **24**:
```bash
git switch -c minha-terceira-branch-1028
```

Exercício **25**:
```bash
touch terceiro-arquivo.txt; git add ./; git commit -m 'Esta mensagem vai no squash'
```

Exercício **26**:
```bash
touch quarto-arquivo.txt; git add ./; git commit -m 'Esta mensagem não vai no squash, mas o arquivo vai'
```

Exercício **27**:
```bash
git switch main; git merge --squash minha-terceira-branch-1028
```

Exercício **28**:
```bash
git commit -m 'Local squash merge #1 from minha-terceira-branch-1028'; git push origin main
```

Exercício **29**:
```bash
git switch my-primary-branch-1028; git pull origin main
```

Exercício **30**:
```bash
git push origin `git branch --show-current`
```

Exercício **31**:
```bash
rm -rf ./git-basics/
```

Exercício **32**:
```bash
git clone https://github.com/rhuan-pk/git-basics.git
```
