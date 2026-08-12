# ☁️ Repositórios Remotos e GitHub

## 📚 Resumo das Aulas e Conceitos

### 1. Conectando o Repositório Local ao GitHub
* **Adicionando origem remota:**  
  Após criar o repositório no GitHub, conecta-se a pasta local ao servidor remoto:
  ```bash
  git remote add origin [https://github.com/usuario/repositorio.git](https://github.com/usuario/repositorio.git)
  git push -u origin main
  ```

### 2. Trabalhando com Repositório Remoto
* `git push`: Envia os commits locais para o repositório remoto no GitHub.
* `git pull`: Baixa e aplica imediatamente as alterações do GitHub na sua máquina local.
* `git fetch`: Baixa o histórico do repositório remoto **sem** mesclar no seu código atual, permitindo inspecionar as novidades antes do merge.

### 3. Lidando com Conflitos
* **O que provoca um conflito de Merge?**  
  Ocorre quando duas pessoas alteram a mesma linha de um mesmo arquivo de formas diferentes. O Git pausa o processo e insere marcadores no arquivo (`<<<<<<<`, `=======`, `>>>>>>>`).
* **Como resolver?**  
  O desenvolvedor abre o arquivo, escolhe qual versão manter, remove os marcadores, adiciona o arquivo (`git add`) e finaliza com um commit (`git commit`).
