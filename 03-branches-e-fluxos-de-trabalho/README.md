# 🌿 Branches e Fluxos de Trabalho

## 📚 Resumo das Aulas e Conceitos

### 1. Gerenciamento básico de Branches
* **O que é uma Branch (ramificação)?**  
  Uma linha de desenvolvimento paralela que permite criar novas funcionalidades sem afetar o código principal (geralmente chamado de `main` ou `master`).
  * `git branch <nome>`: Cria uma nova branch.
  * `git checkout -b <nome>` ou `git switch -c <nome>`: Cria e muda imediatamente para a nova branch.
  * `git branch`: Lista todas as branches locais.

### 2. Unindo código: Merge vs. Rebase
* **`git merge <branch>`:**  
  Junta o histórico da branch informada com a branch atual criando um "commit de merge". Preserva o histórico exatamente como aconteceu.
* **`git rebase <branch>`:**  
  Aplica os seus commits por cima da versão mais recente da branch base, mantendo um histórico linear e limpo.

### 3. Cherry-pick
* **O que é o Cherry-pick?**  
  Permite selecionar e aplicar **um commit específico** de outra branch na sua branch atual, sem precisar trazer todas as alterações daquela branch.
  ```bash
  git cherry-pick <hash-do-commit>
  ```

### 4. Git Tag
* **O que é uma Tag?**  
  Uma marcação usada para sinalizar pontos importantes no histórico de commits, geralmente usada para versionamento de releases (ex: `v1.0.0`).
  ```bash
  git tag -a v1.0.0 -m "Versão 1.0.0 lançada"
  ```
