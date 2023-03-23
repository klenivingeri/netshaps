# NetShaps
O projeto será organizado seguindo o padrão MVC (Model-View-Controller), que é uma arquitetura de software comumente utilizada em aplicações web. A arquitetura é composta por três componentes principais: o modelo (Model), a visualização (View) e o controlador (Controller). O modelo representa os dados e a lógica de negócio da aplicação, a visualização é responsável pela apresentação dos dados ao usuário e o controlador é o intermediário que recebe as solicitações do usuário, faz a chamada ao modelo correspondente e retorna a resposta para a visualização.

## Guidelines de Versionamento:
 - Cada funcionalidade ou correção de bug deve ser desenvolvida em uma branch separada, com nome descritivo e com as inicias do nome do desenvolvedor
 - Antes de começar a trabalhar em uma nova funcionalidade ou correção de bug, sempre faça um pull da branch principal para garantir que está trabalhando com a versão mais atualizada do código.
 - Commits devem ser feitos com mensagens descritivas e concisas em ingles, explicando o que foi feito naquele commit.
 - Commits devem possuir identificados de tipos, exemplo: "chore: adjust button colors"
 - Pull requests devem ser criados após a finalização do desenvolvimento da funcionalidade ou correção de bug, com uma descrição detalhada do que foi feito e quais os impactos que a alteração pode ter no projeto.
 - O código deve ser revisado por pelo menos um outro membro da equipe antes de ser mergeado na branch principal.
 - Merge requests só devem ser realizados após a revisão do código e aprovação da equipe responsável.
 - Ao realizar o merge, deve-se utilizar a opção de squash, para que todos os commits sejam agrupados em um único commit e a mensagem seja ajustada para resumir as mudanças realizadas.

### Commit Types
 - "x.x.x+1" - refactor: melhoria lógica/semantica em um código pré existente
 - "x.x+1.x" - feat: Adição de nova funcionalidade
 - "x.x.x+1" - fix: Correção de bug
 - "x.x.x+1" - chore: Uma pequena melhoria que não tem um impacto direto no negócio ou em algum dos outros tipos
 - "x.x.x+1" - test: Adição de testes de qualquer tipo
