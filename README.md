# :wave: Fundamentos Git e GitHub

## 🤓 Visão Geral

O objetivo deste conteúdo é oferecer uma breve introdução ao Git e GitHub. 🚀

## :octocat: Git e GitHub

Git é um **sistema de controle de versão distribuído (VCS)**, ou seja, uma ferramenta útil para rastrear facilmente mudanças no seu código, colaborar e compartilhar. Com o Git, você pode rastrear as mudanças feitas em seu projeto, mantendo um registro do que foi trabalhado e permitindo reverter para uma versão anterior se necessário. Isso também facilita o trabalho em equipe, onde várias pessoas podem colaborar em um mesmo projeto e unir suas mudanças em uma fonte final!

O GitHub é uma forma de usar o poder do Git online, com uma interface fácil de usar. É amplamente utilizado no mundo do software e além, para colaborar e manter o histórico de projetos. Vamos explorar mais detalhes em breve.

## Entendendo o fluxo do Git

O Git é um fluxo de trabalho que permite experimentar e colaborar em seus projetos facilmente, sem o risco de perder seu trabalho anterior. Ao utilizarmos o GitHub aumentamos a facilitade de colaboração e a garantia dos dados que estarão no serviço do próprio GitHub.

### Repositórios

Um repositório é onde seu trabalho de projeto acontece – pense nele como a pasta do seu projeto. Ele contém todos os arquivos e o histórico de revisões do seu projeto. Você pode trabalhar em um repositório sozinho ou convidar outros para colaborar com você nesses arquivos.

Repositórios também contêm **README**s. Você pode adicionar um arquivo README ao seu repositório para informar outras pessoas sobre a utilidade do seu projeto, o que podem fazer com ele e como usá-lo. Estamos usando este README para comunicar como aprender Git e GitHub com você. 😄
Para saber mais sobre repositórios, leia ["Sobre repositórios"](https://docs.github.com/pt/github/creating-cloning-and-archiving-repositories/about-repositories) e ["Sobre READMEs"](https://docs.github.com/pt/github/creating-cloning-and-archiving-repositories/about-readmes).

👊 Você está lendo este arquivo em um repositório chamado **fundamentos-git-github**. Verifique a url. Perceba quantos arquivos ele possui. Quem fez e quanto fez a última edição. 

### Clonagem 

Quando um repositório é criado no GitHub, ele é armazenado remotamente na ☁️. Você pode clonar um repositório para **criar uma cópia local** no seu computador e, em seguida, usar o Git para sincronizar os dois. Isso facilita a resolução de problemas, adicionar ou remover arquivos e realizar commits maiores. Você também pode usar a ferramenta de edição de sua preferência em vez da interface do GitHub. A clonagem de um repositório também baixa todos os dados do repositório que o GitHub possui naquele momento, incluindo todas as versões de cada arquivo e pasta do projeto! Isso pode ser útil se você quiser experimentar com seu projeto e depois voltar para uma versão anterior. Para saber mais sobre clonagem, leia ["Clonar um repositório"](https://docs.github.com/pt/repositories/creating-and-managing-repositories/cloning-a-repository). 

👊 Vamos fazer um clone deste repositório na sua máquina? Primeiro verifique se o Git está instalado em sua máquina. Se não estiver, veja como instalar em [https://git-scm.com/downloads](https://git-scm.com/downloads). Git instalado? Vamos continuar... Neste repositório clique no botão verde CODE, selecione LOCAL, copie a url HTTPS. Agora em um terminal faça o download do código usando o comando a seguir:
`git clone https://link-com-o-nome-do-repositório` - substitua a url
Acesse o arquivo usando o VSCode ou outro editor.

### Commit e Push

**Commit** e **push** são como você pode adicionar as mudanças feitas em sua máquina local ao repositório remoto no GitHub. Dessa forma, seu instrutor e/ou colegas de equipe podem ver seu trabalho mais recente quando você estiver pronto para compartilhar. Você pode fazer um commit quando tiver feito alterações no seu projeto e quiser fazer um "ponto de verificação". Também pode adicionar uma **mensagem de commit** para lembrar a si mesmo ou aos colegas de equipe sobre o que foi feito (por exemplo, “Adicionado README com informações sobre nosso projeto”).

Depois de ter um ou mais commits que você deseja adicionar ao repositório no GitHub (ou outro em outro serviço semelhante), você pode usar o comando push para adicionar essas mudanças ao repositório remoto. Comitar e fazer push podem parecer novos no início, mas prometemos que você se acostumará! 🙂

### Branches (Ramificações)

Você pode usar branches no GitHub para isolar o trabalho que você ainda não deseja mesclar ao projeto final. As branches permitem desenvolver recursos, corrigir bugs ou experimentar novas ideias em uma área separada do seu repositório principal. Tipicamente, você cria uma nova branch a partir da branch padrão do seu repositório – geralmente chamada de **main**. Isso cria uma nova cópia de trabalho do repositório para você experimentar. Depois que as novas alterações forem revisadas por um colega de equipe, ou quando você estiver satisfeito, poderá mesclar as mudanças na branch padrão do repositório.
Para saber mais sobre branches, leia ["Sobre Branches"](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-branches).


## 📚 Recursos

* [Treine conceitos git nesta ferramenta](https://git-school.github.io/visualizing-git/)
* [Um vídeo curto explicando o que é o GitHub](https://www.youtube.com/watch?v=w3jLJU7DT5E&feature=youtu.be)
* [Recursos de aprendizado sobre Git e GitHub](https://docs.github.com/en/github/getting-started-with-github/git-and-github-learning-resources)
* [Entendendo o GitHub flow](https://guides.github.com/introduction/flow/)
* [Como usar branches no GitHub](https://www.youtube.com/watch?v=H5GJfcp3p4Q&feature=youtu.be)
* [Materiais interativos de treinamento em Git](https://githubtraining.github.io/training-manual/#/01_getting_ready_for_class)
* [GitHub's Learning Lab](https://lab.github.com/)
* [Fórum da comunidade de Educação](https://education.github.community/)
* [Fórum da comunidade do GitHub](https://github.community/)

## 💻 Principais Comandos Git

`git clone https://link-com-o-nome-do-repositório` - clona um repositório

`git status` - verifica as alterações vigentes

`git add <arquivo>` ou `git add -A` ou `git add .` - adiciona arquivos

`git commit -m "mensagem do commit"`- commita as alterações prontas

`git push -u local-remoto nome-da-branch` - envia as alterações para um repositório remoto

`git push -u origin nome-da-branch`- normalmente o local reomoto é chamado de origin

`git pull repositório-remoto` - baixa as atualizações

`git branch nova-branch` - criar uma nova branch

`git switch nova-branch` - vai para nova branch

`git branch` - informa em qual branch você está

`git merge` - mescla as alterações de duas branches
