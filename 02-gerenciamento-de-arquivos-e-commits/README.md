# 📄 Gerenciamento de Arquivos e Commits

## 📚 Resumo das Aulas e Conceitos

### 1. Gerenciamento de Arquivos e Estados do Git
* **Como o Git enxerga os arquivos?**
  * **Untracked:** Arquivo novo que ainda não está sendo rastreado pelo Git.
  * **Staged (Index):** Arquivo preparado para entrar no próximo commit (`git add <arquivo>`).
  * **Committed:** Alteração salva com sucesso no histórico do repositório.

### 2. Gerenciamento de Commits
* **O que é um Commit?**  
  Um "snapshot" (foto) do estado dos seus arquivos no tempo, identificado por um código hash único.
* **Comandos principais:**
  * `git status`: Exibe o estado atual dos arquivos na pasta de trabalho.
  * `git add .`: Adiciona todas as modificações para a Staging Area.
  * `git commit -m "mensagem explicativa"`: Salva as alterações da Staging Area com uma mensagem.

### 3. Ignorando arquivos com `.gitignore`
* **Para que serve o `.gitignore`?**  
  Um arquivo especial onde se listam arquivos e pastas que **não** devem ser rastreados ou enviados ao repositório (ex: senhas, variáveis de ambiente `.env`, diretórios `node_modules/` ou arquivos compilados).
  * *Exemplo de conteúdo:*
    ```text
    node_modules/
    .env
    *.log
    ```
