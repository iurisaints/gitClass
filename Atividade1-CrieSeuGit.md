## Construindo seu Próprio Git: Um Projeto em TypeScript

Neste projeto, você será desafiado a criar um sistema de controle de versão simplificado, similar ao Git, utilizando os conceitos de orientação a objetos em TypeScript. Imagine construir uma ferramenta que rastreia cada mudança em seu código, permitindo que você volte no tempo, crie diferentes versões do seu projeto e colabore com outros desenvolvedores de forma eficiente.

### Atividade 1: Crie um Diagrama de como funciona o GIT e seu fluxo.

### Atividade 2: Criar um código orientado a objeto que simule um git:

**Conceitos-chave:**

* **Commits:** Cada commit representa um "instantâneo" do seu projeto em um determinado momento.
* **Tree:** Organiza os arquivos e diretórios dentro de um commit.
* **Blob:** Contém o conteúdo de um arquivo.
* **Branch:** Uma linha de desenvolvimento independente do seu projeto.
* **Head:** Aponta para o último commit de um branch.
* **Index:** Uma área de preparação para o próximo commit.

**Funcionalidades Essenciais:**

* **Inicialização:** Crie um novo repositório vazio.
* **Adição:** Adicione arquivos modificados ao staging area, preparando-os para o commit.
* **Commit:** Crie um novo commit, armazenando o estado atual do projeto.
* **Histórico:** Visualize a lista de todos os commits realizados.
* **Branches:** Crie e alterne entre diferentes branches.
* **Merge:** Combine as alterações de dois branches.

**Desenvolvimento:**

1. **Modelagem:** Crie classes para representar commits, trees, blobs, repositórios e outras entidades relevantes.
2. **Implementação:** Implemente as funcionalidades de acordo com a especificação do Git.
3. **Persistência:** Decida como armazenar os dados do seu repositório (arquivos, banco de dados).
4. **Interface:** Crie uma interface de linha de comando (CLI) para interagir com seu sistema.

**Desafios Adicionais:**

* **Gerenciamento de conflitos:** Como lidar com situações em que duas versões diferentes de um mesmo arquivo são mescladas?
* **Otimização:** Como garantir o bom desempenho do seu sistema, especialmente para repositórios grandes?
* **Funcionalidades avançadas:** Explore a implementação de tags, submódulos e suporte a redes remotas.

* Uma compreensão profunda dos princípios de um sistema de controle de versão.
* Habilidades sólidas em programação orientada a objetos em TypeScript.
* Um projeto prático para adicionar ao seu portfólio.
