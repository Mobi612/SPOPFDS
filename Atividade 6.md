# Gabarito dos Exercícios - PROVA A

**Questão 1) Sobre os conceitos de Git e GitHub, assinale a alternativa CORRETA:**
* **Resposta certa:** b) O Git é um sistema de controle de versão distribuído, enquanto o GitHub é uma plataforma de hospedagem de repositórios baseada no Git.

---

**Questão 2) Os arquivos rastreados pelo Git podem se encontrar em três estados principais. Assinale a alternativa que apresenta corretamente esses três estados:**
* **Resposta certa:** b) modified, staged, committed (unmodified)

---

**Questão 3) Qual comando é utilizado para INICIAR um novo repositório Git em um diretório local, criando a estrutura .git?**
* **Resposta certa:** c) git init

---

**Questão 4) Após modificar um arquivo, qual comando é responsável por adicioná-lo à staging área (área de preparação) antes do commit?**
* **Resposta certa:** d) git add 

---

**Questão 5) Qual comando envia os commits do repositório local para o repositório remoto (por exemplo, no GitHub)?**
* **Resposta certa:** b) git push

---

**Questão 6) Você precisa baixar um repositório existente no GitHub para sua máquina local pela primeira vez. Qual comando deve ser utilizado?**
* **Resposta certa:** d) git clone 

---

**Questão 7) Após desenvolver uma nova funcionalidade em uma branch separada chamada "feature-login", você deseja unir essas alterações à branch main. Qual sequência de comandos realiza essa tarefa corretamente?**
* **Resposta certa:** b) git checkout main && git merge feature-login

---

**Questão 8) Sobre o sistema operacional Linux, assinale a alternativa CORRETA:**
* **Resposta certa:** b) O Linux é um sistema operacional gratuito e de código aberto (open source), cujo Kernel foi desenvolvido por Linus Torvalds em 1991.

---

**Questão 9) Qual a diferença entre Shell e Bash no ambiente Linux?**
* **Resposta certa:** c) Shell é a interface (genérica) que o usuário utiliza para se comunicar com o Kernel; Bash é um interpretador de comandos específico (Bourne-Again SHell), uma evolução do Bourne Shell (sh).

---

**Questão 10) Considere que você está no diretório /home/aluno e deseja: (1) criar um diretório chamado "projeto", (2) entrar nele e (3) verificar o caminho completo do diretório atual. Qual sequência de comandos realiza essas três tarefas, NESSA ORDEM?**
* **Resposta certa:** b) mkdir projeto && cd projeto && pwd

# Gabarito dos Exercícios - PROVA B

**Questão 1) Sobre o conceito de Sistema de Controle de Versão (VCS), assinale a alternativa CORRETA:**
* **Resposta certa:** b) VCS é um software que realiza o controle e versionamento de código-fonte e arquivos, podendo ser do tipo centralizado (ex.: Subversion/SVN) ou distribuído (ex.: Git).

---

**Questão 2) Sobre o armazenamento de dados no Git, assinale a alternativa CORRETA:**
* **Resposta certa:** b) O Git armazena snapshots ("fotos") do projeto a cada commit; quando um arquivo não muda, ele cria apenas um ponteiro (link) para a versão anterior, otimizando o armazenamento.

---

**Questão 3) Você acabou de fazer alterações em vários arquivos e quer salvá-las DEFINITIVAMENTE no histórico do repositório local, com uma mensagem descritiva. Qual comando faz isso (após o git add)?**
* **Resposta certa:** c) git commit -m "mensagem"

---

**Questão 4) Qual comando traz para o repositório local as alterações mais recentes que estão no repositório remoto, já as integrando à sua branch atual?**
* **Resposta certa:** b) git pull

---

**Questão 5) Para verificar quais arquivos foram modificados, quais estão na staging area e quais ainda não foram rastreados, qual comando deve ser executado?**
* **Resposta certa:** d) git status

---

**Questão 6) Você quer criar uma nova branch chamada "desenvolvimento" e MUDAR para ela imediatamente. Qual comando realiza as duas ações?**
* **Resposta certa:** c) git checkout -b desenvolvimento

---

**Questão 7) Considere o seguinte fluxo: você editou o arquivo "index.html" em seu repositório local. Qual a sequência CORRETA de comandos para enviar essa alteração ao repositório remoto no GitHub?**
* **Resposta certa:** b) git add index.html → git commit -m "alteração" → git push

---

**Questão 8) O que é o Kernel em um sistema operacional como o Linux?**
* **Resposta certa:** d) É o núcleo do sistema operacional, responsável por gerenciar os recursos de hardware e software, permitindo que os programas façam uso desses recursos (memória, dispositivos, processos).

---

**Questão 9) Sobre o conceito de software de Código-Fonte Aberto (Open Source), assinale a alternativa CORRETA:**
* **Resposta certa:** b) Em uma licença open source, os usuários têm liberdade para executar o código para qualquer propósito, estudá-lo, modificá-lo e distribuí-lo.

---

**Questão 10) No Linux, qual comando é utilizado para REMOVER um arquivo chamado "relatorio.txt" e qual comando é utilizado para LISTAR os arquivos do diretório atual, respectivamente?**
* **Resposta certa:** b) rm relatorio.txt; ls

# Gabarito dos Exercícios - PROVA C

**Questão 1) Quais das alternativas abaixo apresenta corretamente VANTAGENS do uso de um sistema de versionamento como o Git?**
* **Resposta certa:** b) Controle de histórico, facilitação do trabalho em equipe, ramificação de projetos (branches), segurança e organização.

---

**Questão 2) Sobre os conceitos de branch (ramo), merge e conflito no Git, assinale a alternativa CORRETA:**
* **Resposta certa:** b) Branches são ramos utilizados para novas codificações de forma isolada; o comando merge é usado para unir ramos, e podem ocorrer conflitos quando duas branches alteram o mesmo trecho de código.

---

**Questão 3) Qual comando é utilizado para LISTAR todas as branches existentes no repositório local?**
* **Resposta certa:** c) git branch

---

**Questão 4) Você está na branch "main" e deseja MUDAR para uma branch já existente chamada "hotfix". Qual comando deve ser utilizado?**
* **Resposta certa:** a) git checkout hotfix

---

**Questão 5) Considere o comando: git commit -m "Correção do bug de login". O que esse comando faz?**
* **Resposta certa:** c) Confirma (registra) os arquivos da staging area no repositório local com a mensagem "Correção do bug de login".

---

**Questão 6) Qual comando exibe o HISTÓRICO de commits do repositório, mostrando autor, data e mensagem de cada commit?**
* **Resposta certa:** b) git log

---

**Questão 7) Você quer adicionar TODOS os arquivos modificados e novos do diretório atual à staging area de uma só vez. Qual comando faz isso?**
* **Resposta certa:** a) git add .

---

**Questão 8) Sobre as distribuições (distros) Linux, assinale a alternativa CORRETA:**
* **Resposta certa:** b) Distribuição Linux é o conjunto formado pelo Kernel + Sistema GNU + Aplicativos + Empacotamento, sendo Ubuntu, Debian, Fedora, CentOS e Red Hat alguns exemplos.

---

**Questão 9) Sobre a estrutura de diretórios do Linux, assinale a alternativa CORRETA:**
* **Resposta certa:** b) O diretório /home contém os diretórios pessoais dos usuários, /etc armazena arquivos de configuração e /bin contém binários executáveis básicos como ls e bash.

---

**Questão 10) Você está no diretório /home/usuario e precisa COPIAR de forma RECURSIVA toda a pasta "projeto" (incluindo subpastas e arquivos) para o diretório /home/usuario/backup. Qual comando realiza isso corretamente?**
* **Resposta certa:** b) cp -R projeto /home/usuario/backup
