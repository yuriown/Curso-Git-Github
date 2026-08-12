# ⚙️ Instalação e Configuração Inicial

## 📚 Resumo das Aulas e Conceitos

### 1. Introdução ao Git
* **O que é o Git?**  
  É um Sistema de Controle de Versões Distribuído (DVCS) projetado para registrar o histórico de alterações no código-fonte, permitindo o trabalho colaborativo sem sobrescrever arquivos.

### 2. Instalação do Git
* **Como instalar o Git na sua máquina?**  
  A instalação varia por sistema operacional:
  * **Linux:** `sudo apt install git`
  * **Windows/Mac:** Download do instalador executável via site oficial (`git-scm.com`).

### 3. Configuração Inicial e Primeiro Repositório Git
* **Identificação do Autor:**  
  Para registrar quem fez cada alteração no código:
  ```bash
  git config --global user.name "Seu Nome"
  git config --global user.email "seuemail@exemplo.com"
  ```
* **Criando o primeiro repositório:**  
  Para transformar qualquer pasta em um repositório Git:
  ```bash
  git init
  ```
