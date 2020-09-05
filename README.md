# Atividade Projeto Estruturado [11]
Atividade solicitada pelo professor Carlos, com o fim de pesquisar o que é Git e como utilizá-lo na prática, através do GitHub. Abaixo as perguntas elencadas pelo professor.

**Felipe Gabriel Rodrigues** *| www.ofelipegabrieu.com | felipegabrielrodrigues@gmail.com*

### 1. O que é o Git?

O Git é um software open source criado em 2005 por Linus Torvalds, enquanto desenvolvia o kernel do sistema operacional Linux. Sua funcionalidade principal é gerir o versionamento de códigos, fornecer segurança e organização, para quem trabalha com desenvolvimento de software e afins. Atualmente, o conhecimento de Git é exigido por muitas empresas pois, pela sua robustez e alto desempenho, se tornou o melhor programa para versionamento de códigos.
Seu formato de versionamento se baseia no DVCS (Sistema de Controle de Versão Distribuído), que permite armazenar o histórico completo de um software em vários locais, podendo ser usado em vários estações ao mesmo tempo, ou também, trabalhando local em uma só máquina.

### 2. O que é versionamento de software?

Em um projeto de software, o processo comum, sendo super simplista, se baseia em cronstuir e depois publicar uma aplicação (build and deploy), e no momento de realizar o *build*, irão ocorrer inclusões, alterações e exclusões de arquivos. Caso alguma destas tarefas seja feita incorretamente, ou exista a necessidade de desafazer uma ação, você precisa ter o backup do projeto. E é isso que o versionamento entrega, só que com mais funções, e claro, como o próprio nome diz, disponbilizando várias versões do mesmo projeto.
Então em resumo, o versionamento permite salvar os estágios da construção e manutenção de um software, e com isso, é possível retrocer para versões anteriores, ou desfazer ações específicas, como: desfazer tudo o que foi alterado ontem, pois após publicar, gerou um erro em que os usuários não conseguem acessar a aplicação.

### 3. Por que utilizar o Git como controle de versionamento?

O Git é um projeto open-source, por isso, é gratuito para todos, permitindo o acesso à qualquer um, sem limitações em suas funções. Neste momento, o Git já possui 15 anos de existência, e deste então, contou com um grupo de desenvolvedores que mostraram dedicação e maturidade para manter o projeto atualizado até hoje, desta forma, passa maior segurança para quem irá utilizá-lo, mostrando que é um software sólido e de qualidade. Além disso, esse tempo agregou uma vasta comunidade que auxilia a manter o código-fonte do Git com patchs de segurança e novas funcionalidades, além de disponbilizar na Internet, muitos conteúdos, como tutoriais em vídeo, livros e podcasts.

### 4. Quais as vantagens do Git?

**[Free]**
Conforme citado na pergunta 3, o Git é gratuito, e com isso, já se diferencia dos demais softwares que cobram mensalidades ou licenças para adquirí-los.

**[Segurança]**
Criado e mantido por uma equipe competente (possui até mesmo pessoas que participaram do kernel do Linux), o Git salva históricos e logs de ações no código-fonte, utilizando uma hash de criptografia chamada SHA1, que protege seus dados de ataques, exigindo uma chave para desbloquear as informações, diferente de outros softwares que deixam livre o histórico de alterações. Além disso, o Git também salva o log de todas as ações, contendo usuário e data que realizou a mesma.

**[Desempenho]**
Claro, de nada adianta ter segurança, se o desempenho deixa a desejar, e isso não acontece com o Git. Ele possui uma otimização incomum nos seus concorrentes, pois ao invés de trabalhar com os arquivos, se baseando nas ramificações (pastas e nomes de arquivos), ele trabalha com o conteúdo do arquivo. Desta forma, ele foca somente no que é alterado no nome do arquivo, e reconhece se um arquivo teve seu nome ou localização alterados, comparando o conteúdo novo com o já salvo em versões anteriores.

### 5. Qual a importância da utilização do controle de versionamento no desenvolvimento de um software?

Existem vários fatores que *forçam* a utlização de um controle de versionamento no desenvolvimento de uma aplicação, isto porque suas vantagens trazem segurança, flexibilidade, trabalho em equipe, administração de mudanças e atualizações, reparação de bugs e outros benefícios. Citarei abaixo, dois dos benefícios elencados, que para mim, são grandes diferençais quando falamos de desenvolvimento de software em corporações.

**[Trabalho em equipe]**
Quando imagino o desenvolvimento de uma aplicação, consigo ver alguns *grupos com tipos* de desenvolvedores. Existem os freelancers que trabalham sozinhos, ou os dois colegas que se conheceram e querem bancar uma nova ideia, e também, aquele grande grupo de pessoas que trabalha desenvolvendo para uma empresa. Em alguns casos, cada um está em um local diferente, seja uma sala diferente, cidade ou país. Para conectar essas pessoas, o versionamento permite que seja verificado quem realizou qual alteração em qual momento, também traz a função de trabalho remoto, em que uma equipe pode trabalhar resolvendo um bug, e outra desenvolvendo uma nova interface, tudo dentro do mesmo projeto, mas cada um, em um ambiente de desenvolvimento diferente, trabalhando colaborativamente.

**[Administração de mudanças e atualizações]**
Em algumas carreiras, é comum que um profissional passe pela faculdade e não necessite de mais estudos ou especializações e esse, com certeza, não é o caso de um desenvolvedor de software. Na Tecnologia da Informação, tudo muda, nada está na versão final, e sempre existe uma forma de melhorar ou um bug para arrumar **(rsrs)**. Então o versionamento permite que um código-fonte possa ser gerido como merece, realizando atualizações periódicas, permitindo desfazer essas atualizações caso necessário, e, mantendo um código legível e documentado por anos, para que assim, a aplicação continue viva, sendo que, independente de quem a desenvolva, esta pessoa possa entender o histórico do código, e dê continuidade no mesmo.


###  6. Cite três ferramentas de controle de versão

**Mercurial** *| software livre | desenvolvido por Matt Mackall*
É uma ferramenta utilizada por corporações gigantes como o Google e o Facebook, para administração de software com grandes equipes. Foca na alta performance, escabilidade, *descentralização* e operações avanádas com merges e branchs.

**Apache Subversion** *| software livre | desenvolvido pela Apache*
Ferramenta desenvolvida e mantida pela Apache, tem como foco, o trabalho colaborativo de usuários em rede. Permite a reserversão e versões e históricos de alterações. Sua diferença com outros produtos, é que pode ser usado para qualquer conjunto de arquivo, sendo eles código-fonte, imagens, edições de fotos e vídeos, e outros.

**Rational ClearCase** *| software licenciado | criado pela Atria e mantido pela IBM*
Aplicação utilizada por empresa de grande e médio porte, possui seu foco em gerenciamento de grande número de usuários e projetos, suportante grandes pastas, repositórios e arquivos binários. Além disso, fornece suporte à ramificação, rotulagem e controle de versão dos diretórios.


*[Fontes]*
atlassian.com/br/git/tutorials
pt.wikipedia.org/wiki/Mercurial
pt.wikiversity.org/wiki/Subversion_-_SVN
en.wikipedia.org/wiki/Rational_ClearCase