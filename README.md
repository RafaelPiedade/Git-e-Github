# GIT E GITHUB

Guia prático para iniciantes

### Instalação

https://git-scm.com

# SCENES

- [x] Você deseja criar pontos nahistória da produção do seu projeto
- [x] Você deseja verificar mudanças feitas no seu projoto

* `git initi` - Inicia um repositório onde será guardado as alterações do projeto
* `git add` - Adiciona o arquivo para irem para a linha do tempo, ele não é adicionado na linha, quem adiciona é o `git commit`
* `git commit -m "alteração"` - Cria um ponto na história do projeto
* `git commit -am "alteração"`- O `a` é para que seja feito o `git add`(atalho)
* `git log` - Mostra o histórico/log do projeto
* `git status` - Mostra o estado do meu projeto(o que foi alterado, adicionado e não esta no historico do git e oque foi para a linha do tempo)
* `git show ####` - Mostra um ponto do hitórico apartir do codigo do commit que aparece em `git log`, sem o código do commit é mostrado o ultimo commit realizado;

- [x] Você começa uma nova funcionalidade no seu projeto, sem estragar o que ja foi feito.
- [x] Você adiciona as novas funcionalidades ao seu projeto em produção.
- [x] Você quer deletar a branch da nova funcionalidade, depois de aplicar em seu projeto.

* `git branch 'feature/cart'` - Cria uma nova ramificação no histórico.
* `git checkout 'feature/cart'` - Troca de ramificação
* `git checkout -b teste` - Cria e troca para a ramificação
* `checkout` - Manipula a linha do tempo
* `git branch` - Mostra as ramificações do projeto. (a ramificação da branch master,normalmente é onde fica o projeto em produção)
* `git branch -D feacture/cart` - Apaga a ramificação
* `git merge feature/cart` - Unia as ramificação com a principal

- [x] Colocar o projeto na nuvem(Github repositório remoto)

* `git remote add origin https://github.com/RafaelPiedade/Git-e-Github.git` - Adicionar a um repositorio remoto
* `git remote -v` - Mostra os repositórios remotos;
* `git push origin master` - Envia para o repositório remoto

- [x] Você vai pegar um projeto ja iniciado, para trabalhar com o time
- [x] Você precisa resolver um conflito
- [x] Antes de enviar a resolução, precisamos atualizar o projeto local.

* `git clone` - Clona um repositório existente
* `git pull` - Puxa as alterações que estão no remoto

- [x] Você precisa voltar um arquivo para um determinado momento da linha do tempo

* `git checkout 9194c02fbdd20eb30c3d48f16cf0a5c3c7181809 -- <arquivo>` - Recupera o arquivo apartir do codigo da commit.

- [] Você precisa recuperar algo deletado   
* `git checkout -- <file>` - Recupera o arquivo do ultimo commit

## Configuração

- `git config credential.helper store` - Configura login e senha para não precisar ficar colocando toda hora quando realizar o `git push`
