# DIO | Resumos GIT e GitHub

Repositório usado para resumo sobre GIT e GitHub do curso Versionamento de Código da [Digital Innovation One](https://web.dio.me/home).

## 💾 Resumos das aulas
### - Conteúdo:
    - Versionamento refere-se as novas versões(alterações) feitas em um projeto;
    - Caso: Criando um repositório remoto a partir de local já existente.
        - 1° Criar um repositório com o mesmo nome do repositório local, sem README.md;
        - 2° No GIT Bash, seguir com as instruções correspondentes.
    - Caso: Salvar alterações feitas remotamente no local.
        - No GIT Bash escrever o comando git pull que puxa e mescla as alterações.
### - Comandos:
    - git add . : Usado para adicionar alterações;
    - mkdir - Cria pastas;
    - cd .. | cd pasta/ - Usado para navegar pelas pastas no terminal;
    - git init - Inicia um repositório novo;
    - git clone - Usado para clonar um repositório já existente;
    - touch - Usado para criar arquivos;
    - rm -rf : Usado para remover um repertório recursivamente e todo seu conteúdo;
    - git restore : Apaga as últimas mudanças feitas no arquivo;
    - git log : Mostra os últimos commits realizados;
    - git commit --amend -m"exemplo" : Altera o comentário;
    - git reset --(soft|mixed|hard) : Apaga um commit;
    - git checkout -b exemplo : Cria uma nova branch;
    - git checkout exemplo : Usado para mudar de branch;
    - git branch -v : Usado para visualizar todas as branchs existentes;
    - git branch merge : Usado para mesclar branchs;
    - git branch -d exemplo : Usado para deletar uma branch;
    - git fetch (origin main): Usado para buscar alterações do repositório remoto para o repositório local, sem mesclar;
    - git diff (origin main): Mostra as diferenças entre arquivos, exibindo as seções que foram alteradas;
### - Obs:
    - Atenção em qual pasta se está dentro do terminal;