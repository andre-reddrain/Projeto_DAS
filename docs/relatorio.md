# Relatório Final - Página Colaborativa de Receitas

## Integrantes do Grupo
- Nome do projeto: Projeto DAS
- Integrantes: André Rosa, Pedro Jesus, Cláudio Ignat
- Repositório: [https://github.com/andre-reddrain/Projeto_DAS]

## Branches Criadas
- **feature/salame**
    - **Objetivo**: Adicionar uma receita de salame á página web.
    - **Merge**: Através de Pull Request. Foi o 1º branch a dar merge.
- **feature/vinagrete**
    - **Objetivo**: Adicionar uma receita de vinagrete á página web.
    - **Merge**: Através de Pull Request. Foi o 2º branch a dar merge, e deu conflitos, que foram registados por um issue.
- **feature/mousse**
    - **Objetivo**: Adicionar uma receita de mousse á página web.
    - **Merge**: Através de Pull Request. Foi o 3º branch a dar merge, e deu conflitos, que foram registados por um issue.

Todos os pull requests, antes do merge, foram revistos por todos os membros do grupo. Só se fez o merge quando ambos os reviewers deram o OK para tal.

## Histórico de Commits
Cada commit criado tem uma mensagem simples e explicativa do que faz. Ex: ***Nova Receita - Salame*** / ***Receita de Vinagrete***
[https://github.com/andre-reddrain/Projeto_DAS/graphs/contributors]

## Issues Criadas
- **Issue #1** - Receita de Vinagrete - Merge Conflict - André Rosa
- **Issue #2** - Mousse - Merge Conflict - André Rosa

## Pull Requests
Quando o branch estava pronto para ser merged com o branch **dev**, era criado um pull request.
Cada pessoa dava assign a si mesmo, e adicionava os outros colegas como reviewers.
Quando ambos os reviewers dessem o OK, o pull request era realizado.

Foram realizados 3 Pull Requests.

## Conflitos e Resoluções
Houve conflitos, a partir do 2º merge. Como todos os branches usaram o mesmo template de HTML, era inevitável haver conflitos.
Os conflitos foram resolvidos através do GitHub, no editor de código. O código do branch a ser merged foi simplesmente colocado no fim da página, mantendo a mesma estrutura de código.

## Dificuldades Enfrentadas
Resolver os conflitos. Apesar do GitHub providenciar um editor online de código, é um bocado complicado perceber se está tudo OK, sem haver uma visualização do código a funcionar. O IDE do GitHub parece que por vezes não dá highlight a erros (ex: >>>>> feature/salame), que em casos de projetos grandes, pode ser complicado encontrar estas linhas que bloqueiam o conflito de ser resolvido.

## Principais Comandos Git Utilizados
**git fetch** - Download dos objetos e referências de um repositório.
**git add .** - Adicionar os ficheiros modificados localmente como Staged.
**git commit -m "msg"** - Commit dos ficheiros Staged com uma mensagem de commit.
**git push** - Push do commit para o repositório.
**git push --set-upstream origin branch_name** - Cria o branch no repositório.
**git pull** - Atualiza o projeto com as alterações do repositório.
**git checkout branch_name** - Navegar para o branch local pretendido.

## Conclusão
Aprendemos a:
* Trabalhar com Git localmente e remotamente
* Trabalhar com branches
* Fazer Pull Requests
* Criar Issues
* Resolver merge conflicts
* Fazer reviews
