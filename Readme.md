# Git e GitHub

    Arquivo da aula de Git e GitHub para iniciantes

    este é um repositorio teste para ensinar como o Git funciona.

Saiba mais em [EmersonCob](https://github.com/EmersonCob)

# Alguns comandos do Git:

### configurando o Git (nome de usuario):

    git config --global user.name "Emerson Costa"

### configurando o Git (e-mail do usuario):

    git config --global user.email "ercosta90@gmail.com"

## inicializando 

    git init

### Criar um arquivo Readme.md ou abrir para edição

    vi Readme.md

        * Ao abrir apertar a tecla de atalho "i" para iniciar a edição ou inserir.

        * Ao concluir usar a tecla ESC e digitar :wq pra salvar e sair do arquivo.

        * Caso tenha aberto apenas para visualizar, digitar :q! para sair do arquivo.

### Para verificar o status do repositorio

    git status

### Para adcionar um arquivo modificado 

    git add 

### Para commitar um arquivo com comentario

    git commit -m "teste"

### Para commitar um arquivo sem precisar usar o git add

    git commit -am "teste"

### Para exibir todas as diferenças entre a cópia local e o índice sincronizado

    git diff

### Para verificar os log's 

    git log

### Para verificar os log's de forma resumida

    git shortlog

### Para verificar o que foi modificado no arquivo

    git show

### Para restaurar um arquivo modificado antes do commit

    git checkout Readme.md 

### Para retornar o arquivo a uma posição anterior

    git reset HEAD Readme.md

### Para retornar um arquivo já commitado a posição anterior

    git reset --hard a1ec8e60ea5b8af6996f4403c6ac0f2c513e5430

     * OBS.: Usar o hash do commit anterior ao do erro.

     * OBS.2: É necessario muito cuidado pois modifica o historico de commit's, principalmente se já foi aplicado um push 


### Para enviar todos os arquivos commitados para o repositorio remoto 

    git push origin master

### Para clonar um repositorio 

    git clone https://github.com/EmersonCob/github-curse.git

### Para criar um branch

    git checkout -b 'testeing'

    * Para verificar quais são as branches existentes e exibir na qual estámos.

### Para navegar entre as branches

    git checkout master 

    * digitar o nome da branch que deseja acessar.

### Para deletar uma branch

    git branch -D testing

    * Após o comando informar o nome da branch que deseja apagar.

### Criando um arquivo .gitignore

    vi .gitignore

    * Para evitar que aquivos que contenham senhas ou algum outro arquivo que não queria subir para o repositorio remoto devemos inserir no .gitignore
    * O arquivo pode ser criado em qualquer ferramenta.



