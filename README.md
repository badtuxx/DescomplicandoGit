<p align="center">
<img alt="Discord" src="https://img.shields.io/discord/769953234965889026?label=Pessoas%20no%20Discord&style=plastic">
</p>

<p align="center">
  <a href="http://youtube.com/linuxtips?sub_confirmation=1">
    <img alt="YouTube Channel Subscribers" src="https://img.shields.io/youtube/channel/subscribers/UCJnKVGmXRXrH49Tvrx5X0Sw?style=social">
  </a>
  <a href="http://youtube.com/linuxtips?sub_confirmation=1">
    <img alt="YouTube Channel Views" src="https://img.shields.io/youtube/channel/views/UCJnKVGmXRXrH49Tvrx5X0Sw?style=social">
  </a>
  <a href="http://twitch.tv/linuxtips?sub_confirmation=1">
    <img alt="Twitch Status" src="https://img.shields.io/twitch/status/linuxtips?style=social">
  </a>
  <a href="http://github.com/badtuxx">
    <img alt="GitHub followers" src="https://img.shields.io/github/followers/badtuxx?style=social">
  </a>
  <a href="http://twitter.com/badtux_">
    <img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/badtux_?style=social">
  </a>
  <a href="http://twitter.com/linuxtipsbr">
    <img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/LINUXtipsBR?style=social">
  </a>
</p>

<p align="center">
  <a href="https://hub.docker.com/r/linuxtips/alertmanager_alpine">
    <img alt="Docker Pulls" src="https://img.shields.io/docker/pulls/linuxtips/alertmanager_alpine?label=alertmanager_alpine%20image%20pulls&style=plastic">
  </a>
  <a href="https://hub.docker.com/r/linuxtips/prometheus_alpine">
    <img alt="Docker Pulls" src="https://img.shields.io/docker/pulls/linuxtips/prometheus_alpine?label=prometheus_alpine%20image%20pulls&style=plastic">
  </a>
  <a href="https://hub.docker.com/r/linuxtips/node-exporter_alpine">
    <img alt="Docker Pulls" src="https://img.shields.io/docker/pulls/linuxtips/node-exporter_alpine?label=node-exporter_alpine%20image%20pulls&style=plastic">
  </a>
</p>

<p align="center">
  <a href="https://github.com/badtuxx/DescomplicandoKubernetes">
    <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/badtuxx/descomplicandokubernetes?label=Descomplicando%20Kubernetes&style=social">
  </a>
  <a href="https://github.com/badtuxx/descomplicandoDocker">
    <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/badtuxx/descomplicandoDocker?label=Descomplicando%20Docker&style=social">
  </a>
  <a href="https://github.com/badtuxx/descomplicandoPrometheus">
    <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/badtuxx/descomplicandoPrometheus?label=Descomplicando%20Prometheus&style=social">
  </a>
  <a href="https://github.com/badtuxx/CertifiedContainersExpert">
    <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/badtuxx/CertifiedContainersExpert?label=CertifiedContainersExpert&style=social">
  </a>
  <a href="https://github.com/badtuxx/DescomplicandoGit">
    <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/badtuxx/DescomplicandoGit?label=Descomplicando%20Git&style=social">
  </a>
  <a href="https://github.com/badtuxx/DescomplicandoArgoCD">
    <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/badtuxx/DescomplicandoArgoCD?label=Descomplicando%20ArgoCD&style=social">
  </a>
  <a href="https://github.com/badtuxx/Giropops-Monitoring">
    <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/badtuxx/Giropops-Monitoring?label=Giropops%20Monitoring&style=social">
  </a>
  <a href="https://github.com/badtuxx/DescomplicandoHelm">
    <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/badtuxx/DescomplicandoHelm?label=Descomplicando%20Helm&style=social">
  </a>
                <a href="https://github.com/badtuxx/convencendo-seu-chefe">
    <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/badtuxx/convencendo-seu-chefe?label=convencendo-seu-chefe&style=social">
</p>

# Descomplicando o GIT

*******
- [Descomplicando o GIT](#descomplicando-o-git)
  - [A proposta do material](#a-proposta-do-material)
  - [O Livro: DevChef ???](#o-livro-devchef-)
  - [Sobre o material Descomplicando o Git](#sobre-o-material-descomplicando-o-git)
  - [Vamos come??ar!](#vamos-come??ar)
    - [O que ?? o git?](#o-que-??-o-git)
    - [Criando o repo do nosso livro](#criando-o-repo-do-nosso-livro)
    - [Compartilhando o nosso reposit??rio](#compartilhando-o-nosso-reposit??rio)
    - [Adicionando a nossa chave SSH no GitHub](#adicionando-a-nossa-chave-ssh-no-github)
    - [Conectando o reposit??rio local com o reposit??rio remoto](#conectando-o-reposit??rio-local-com-o-reposit??rio-remoto)
    - [Enviando o conte??do para o reposit??rio remoto](#enviando-o-conte??do-para-o-reposit??rio-remoto)
    - [Clonando o reposit??rio remoto](#clonando-o-reposit??rio-remoto)
    - [Adicionando a nossa primeira receita](#adicionando-a-nossa-primeira-receita)
    - [Branches](#branches)
    - [Fazendo o merge da branch segunda-receita para a branch main](#fazendo-o-merge-da-branch-segunda-receita-para-a-branch-main)
    - [Deletando a branch segunda-receita](#deletando-a-branch-segunda-receita)
    - [Conflitos](#conflitos)

*******


## A proposta do material

Durante o conte??do do material, a pessoa estudante tera a oportunidade de aprender desde conceitos b??sicos sobre o Git, at?? tarefas mais avan??adas que s??o parte do dia a dia de uma pessoa senior que trabalha como TI.

Se voc?? ?? uma pessoa desenvolvedora, DevOps Engineer, SRE, Platform Engineer, etc... Qualquer carreira dentro de tecnologia precisa conhecer como gerenciar os seus c??digos de forma organizada e compartilhada com outras pessoas.

Dito isso, precisamos ter um projeto de exemplo para a nossa jornada. Eu pensei em criar um projeto de IaC ou ainda uma App em Python, mas acabei optando por escrever sobre algo que todo mundo j?? conhece, ou pelo menos j?? teve contato uma vez na vida.

Para utilizar como exemplo, n??s vamos criar um pequeno livro de receitas, sim receitas! 
E n??o estou falando de receitas do Chef da OpsCode, estou falando sobre um livro de receitas de comidas, e de preferencia comidas vegana! 

Ent??o ?? isso, enquanto vamos aprendendo sobre o sensacional Git, j?? vamos ainda aprendendo sobre como fazer um rango bem gostoso vegano! 

No final desse material, eu quero que al??m do almo??o, voc?? tamb??m crie um reposit??rio no Github com o seu livro, que seria um fork do nosso repo do material, com uma nova receita adicionada por voc??!

Depois ?? s?? abrir um PR l?? no Github que faremos o commit para a main!

Assim teremos um livro bem foda, totalmente criado pela comunidade Dev!

&nbsp;
## O Livro: DevChef ???

Precisamos ter um nome para o nosso livro, eu vou deixar como DevChef por enquanto, mas ?? claro, se algu??m tiver uma ideia melhor ?? s?? falar, abre uma issue aqui no Github com a sugest??o!

O endere??o do reposit??rio do nosso livro de receitas ?? o:

```bash
https://github.com/badtuxx/**DevChef**
```

Muito bem, dito isso acho que j?? podemos come??ar!

Lembre-se, o nosso livro ser?? vegano! Mesmo que voc?? n??o seja, vamos fazer esse esfor??o para que possamos celebrar juntos todo esse aprendizado!

&nbsp;
## Sobre o material Descomplicando o Git

Vamos criar o nosso livro de receitas, mas o objetivo principal ?? aprender sobre o Git. E aqui n??o queremos aprender o Git decoreba, queremos aprender o Git que ?? usado no dia a dia! 

Eu tenho mais de 12 anos de experi??ncia trabalhando com Git em ambientes grandes e complexos, com times que de centenas de pessoas compartilhando o mesmo reposit??rio Git, e essa experi??ncia acumulado que quero trazer aqui para voc??s!

Esse material ?? a base do Workshow Descomplicando o Git que criei para a LINUXtips!
Se voc?? est?? afim de aprender muito sobre o Git em formato de v??deo, col?? l?? no site da LINUXtips!

Iremos ainda criar um e-book com esse conte??do, ent??o se voc?? est?? lendo esse conte??do em um PDF bonitinho e bem formatadinho, parab??ns e muito obrigado por ter adquirido a c??pia do e-book!

E claro, temos o reposit??rio desse material l?? no Github no seguinte endere??o:

```bash
https://github.com/badtuxx/DescomplicandoGit
```

O material est?? sobre a licensa GPL-3, ent??o fique a vontade em aprender de forma totalmente gratuita, e ainda, ajudar adicionando ainda mais conte??do nesse sensacional reposit??rio, combinado?

E claro, caso queira utilizar esse material para ensinar outras pessoas, fique a vontade! Evidente, respeitando o que diz a licensa do c??digo!

As pessoas que mais contribuirem para esse repo ser??o consideradas pessoas mantenedoras e com isso ter?? acesso ao e-book e tamb??m ao workshop. E claro, o nome nos agradecimentos do e-book! 

Teremos 3 vagas para pessoas mantenedoras!

Se voc?? ainda est?? vendo esse texto, significa que ainda n??o temos essas pessoas escolhidas, ent??o aqui est?? uma boa oportunidade!


Como base para esse material n??s vamos utilizar a documenta????o oficial do projeto, que voc?? pode acessar atrav??s dessa url:

```bash
https://git-scm.com/docs
```

Ahhh, e parab??ns demais para a galera envolvida na constru????o dessa doc, e mais do que isso, parab??ns para a galera empenhada em fazer a tradu????o desse material para o Portugu??s! Boa parte da documenta????o est?? em Portugu??s e com uma qualidade excelente!

&nbsp;

## Vamos come??ar!


### O que ?? o git?

A primeira coisa que temos que ter em mente, ?? o que ?? o Git. O Git nada mais ?? do que uma ferramenta para que voc?? possa versionar o seu c??digo, e mais do que isso, versionar o seu c??digo e deixo organizado mesmo que compartilhado com milhares de pessoas desenvolvedoras.

Eu poderia ficar aqui falando que o Git ?? um VCS como n??s tinhamos o Subversion e outras velharias, mas com todo o respeito, a maioria das pessoas que trabalham hoje com c??digo versionado e compartilhado, n??o tem nem a menor ideia do que um VCS, elas apenas sabem que quando voc?? precisa versionar e ter um gerenciamento descente de c??digo, voc?? utiliza o Git.

Ela foi criada em 2005 por Linus Torvalds, o criador do Linux. Ele criou o Git pois estava insatisfeito com funcionavam os versionadores de c??digos da ??poca. F??cil n??. hahahha

Pode ser uma opini??o muito forte sobre, mas ?? a realidade que eu tenho visto nos ??ltimos 10 anos, pelo menos.

Pois bem, dito isso, o que precisamos entender ?? como o Git funciona, e para isso ?? fundamental come??armos entender isso praticando, essa ?? a nossa maneira de ensinar!

Ent??o chegou a hora de come??ar a criar o nosso livro de receitas DevChef e iniciar a nossa jornada de aprendizado com o Git.


### Criando o repo do nosso livro

Muito bem, agora j?? sabemos que o nosso projeto ser?? um livro de receitas, o que precisamos fazer ?? come??ar a trabalhar!

Para isso vamos criar um diret??rio chamado DevChef, conforme abaixo:

```bash
mkdir DevChef
```

&nbsp;
Pronto, agora vamos acessa-lo:

```bash
cd DevChef/
```
&nbsp;

Agora vamos criar uma arquivo chamado README.md e te explico no caminho o porque ?? importante ter esse cara em nosso repo.

```bash
touch README.md
```
&nbsp;

Agora que j?? criamos o arquivo, eu posso te explicar a sua utilidade e porque ele ?? importante.

O README.md ?? o arquivo onde voc?? coloca os detalhes do seu repo, do seu projeto.

E como se fosse o p??gina principal de um site, a primeira p??gina do nosso repo. Quando algu??m acessar o nosso repo, ele ser?? recebido por essa p??gina.

Para o nosso livro, vamos deixar nesse arquivo todo o conte??do. N??s vamos deixar bonitinho, vai ser f??cil!

Outra coisa, voc?? viu que a o final do nome do arquivo ?? terminado com .md, isso indica que estamos querendo criar um arquivo utilizando a linguigem de marca????o Markdown, que voc?? pode ver mais detalhes [aqui](https://pt.wikipedia.org/wiki/Markdown).

N??s vamos aprender algumas coisa sobre como utilizar o Markdown, pois precisamos deixar o nosso livro bonitinho!

Muito pooom! Todo mundo j?? sabe o que ?? esse tal de README.md, agora vamos colocar algum conte??do l?? dentro!

Para isso voc?? pode utilizar o VI ou outro editor de textos de sua preferencia. Enquanto eu escrevo esse material, estou utilizando o Visual Studio Code, super recomendo pois ele vai agilizar e muito a sua vida. Mas se voc?? n??o tiver, n??o tem problemas, utilize o editor que voc?? achar melhor.

Durante a constru????o desse material estou utilizando o Linux, ent??o todos os exemplos de linha de comando s??o realizadas no Linux.


Adicione o seguinte conte??do no arquivo:

```markdown
# DevChef

## Sobre o Projeto

Livro criado por pessoas que estavam aprendendo a ferramenta de versionamento de c??digos Git com o Jeferson na LINUXtips.

&nbsp;
## Livro de Receitas Veganas

O Livro foi iniciado com cinco receitas adicionadas e testadas pelo Jeferson, as demais foram adicionadas pela comunidade de pessoas que estavam focadas em aprender Git e ter um almo??o vegano!

&nbsp;
## Receitas

&nbsp;
#### Conte??do 

&nbsp;
#### Receita 1

&nbsp;
#### Receita 2

&nbsp;
#### Receita 3

&nbsp;
#### Receita 4

&nbsp;
#### Receita 5
```

&nbsp;

Pronto, acho que temos uma boa defini????o inicial do nosso livro, e ainda montamos o esqueleto inicial do nosso livro.

Muito bem, j?? temos o arquivo mas ainda n??o fizemos nada em rela????o ao Git.

Precisamos falar para o Git que queremos que ele cuide de nosso arquivo, do nosso diret??rio. Para isso, antes de mais nada precisamos instalar o Git no Linux caso ainda voc?? n??o tenha.

Para realizar a instala????o do Git no Ubuntu, utilize o comando abaixo:

```bash
sudo apt install git
```

&nbsp;

Voc?? pode verificar se o Git foi instalado corretamente utilizando o comando abaixo:

```bash
git --version
```

&nbsp;

Para ver como instalar o git no Windows, voc?? pode acessar o link [aqui](https://git-scm.com/download/win). 

J?? para o MacOS, voc?? pode acessar o link [aqui](https://git-scm.com/download/mac).

&nbsp;

Ap??s fazer a instala????o, ?? hora de falar para ele que queremos que ele comece a cuidar de nosso diret??rio.

Mas antes de come??ar, precisamos fazer algumas configura????es em nosso git. Informa????es como o nome do usu??rio, email, editor de texto e principalmente o nome da branch. Hoje em dia o nome dca branch padr??o ?? o main, se ainda n??o ?? o seu caso, voc?? pode alterar utilizando o comando abaixo:

```bash
git config --global init.defaultBranch main
```

N??s ainda vamos falar muito sobre branches e vou te explicar com todos os detalhes, mas por enquanto pensa que ?? o nome da sua mesa de trabalho atual, vamos imaginar que ?? a vis??o que voc?? tem do seu projeto atual. Eu digo vis??o, pois voc?? pode ter v??rias mesas de trabalho, e cada uma delas ?? uma branch, e cada uma com uma vis??o diferente do seu projeto.

Confuso? Sim! Mas somente agora!
Logo menos voc?? vai entender tudo e ver o quanto isso salva vidas!

Vamos somente definir uma coisa, a nossa branch main vai ser a nossa principal, como se fosse a vers??o est??vel, a vers??o que poderia ser publicada em produ????o, certo?

Por enquanto ?? isso sobre branches, mas como eu disse, vamos falar muito sobre elas.

Vamos fazer algumas configura????es b??sicas do Git, para isso vamos utilizar o comando abaixo:

```bash
git config --global user.name "Seu Nome"
git config --global user.email "
```

Essas s??o as configura????es b??sicas, mas voc?? pode configurar outras coisas, como por exemplo, o editor de texto que voc?? quer utilizar, para isso utilize o comando abaixo:

```bash
git config --global core.editor "vim"
```

&nbsp;

Agora sim podemos iniciar o nosso reposit??rio Git. Para isso, vamos utilizar o comando abaixo:

```bash
git init
```

A sa??da do comando ser?? a seguinte:

```bash
Initialized empty Git repository in /home/jeferson/REPOS/DevChef/.git/
```

&nbsp;

O comando git init ?? o comando utilizado para iniciar o nosso repositorio, ou seja, ele vai criar o nosso .git, que ?? o diret??rio onde o Git vai guardar todas as informa????es sobre o nosso projeto.

```bash
ls .git/
```

&nbsp;

Dentro do diret??rio, voc?? vai encontrar todos os arquivos que o Git precisa para organizar a nossa casa, o nosso projeto. N??s ainda vamos voltar algumas vezes aqui para explicar o que est?? acontecendo, mas por enquanto, somente saiba que ele existe e ?? aqui que est??o todas as informa????es do nosso projeto, como as branches, os commits, as tags, etc.

Mais uma vez, eu sei que ainda n??o vimos nada disso, mas vamos ver, ?? s?? pra deixar voc?? ainda mais curiosa!

&nbsp;

Vamos voltar as aten????es para o nosso repo e para o conte??do que estamos criando.

Um comando que ?? muito ??til e que vai trazer o status atual do nosso projeto ?? o comando git status.

```bash
git status
```

A sa??da do comando ser?? a seguinte:

```bash
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	README.md

nothing added to commit but untracked files present (use "git add" to track)
```

&nbsp;

Perceba que o Git nos informa que estamos na branch main, que ainda n??o temos nenhum commit e que temos um arquivo, que existe, mas que ainda n??o foi adicionado ao nosso reposit??rio.

Para adicionarmos o nosso arquivo ao nosso reposit??rio, vamos utilizar o comando git add.

```bash
git add README.md
```

&nbsp;

Vamos executar o comando git status novamente para ver o que aconteceu.

```bash
git status
```

A sa??da do comando ser?? a seguinte:

```bash
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   README.md
```

&nbsp;

Agora n??s temos um arquivo que foi adicionado ao nosso reposit??rio, mas isso ainda n??o garante o controle de vers??o, pois ainda n??o fizemos nenhum commit.

Para entender melhor o que o comando acima fez, precisamos entender os tr??s estados do Git.

O Git trabalha com tr??s estados, o estado de trabalho, o estado de prepara????o e o estado de commit.

?? bem comum voc?? ver esses tr??s estados em ingl??s, ent??o normamente voc?? vai ver o Working Directory, o Staging Area e o Repository.

- O Working Directory ?? o diret??rio onde voc?? est?? trabalhando, onde voc?? est?? criando os seus arquivos, onde voc?? est?? fazendo as suas altera????es.

- O Staging Area ?? o local onde voc?? vai adicionar os arquivos que voc?? quer que o Git comece a controlar, ou seja, o Git vai come??ar a monitorar as altera????es que voc?? fizer nesses arquivos.

- O Repository ?? o local onde o Git vai guardar todas as informa????es sobre o seu projeto, como as branches, os commits, as tags, etc. Esse ?? o nosso diret??rio .git.

Quando estamos usando o comando git add, n??s estamos adicionando os arquivos que queremos que o Git comece a controlar, ou seja, estamos adicionando os arquivos ao Staging Area.

Ent??o temos esse arquivo controlado pelo Git, mas ainda n??o temos um commit. O commit ?? o ato de adicionar as altera????es que voc?? fez no seu arquivo ao seu reposit??rio.

?? importante voc?? conhecer esses tr??s estados, pois l?? pra frente voc?? vai precisar deles para saber como atuar em cada situa????o.

&nbsp;

Agora que j?? entendemos o que o comando git add faz, vamos fazer o nosso primeiro commit.

```bash
git commit -m "Adicionando o arquivo README.md"
```

&nbsp;


A sa??da do comando ser?? a seguinte:

```bash
[main (root-commit) 1cd4e1b] Adicionando o arquivo README.md
 1 file changed, 31 insertions(+)
 create mode 100644 README.md
```

&nbsp;

Perceba que o Git nos informa que estamos na branch main, que fizemos um commit e que adicionamos um arquivo.

Vamos chamar novamente o git status para ver o que aconteceu.

```bash
git status
```

A sa??da do comando ser?? a seguinte:

```bash
On branch main
nothing to commit, working tree clean
```

&nbsp;

O que ele est?? dizendo que n??o precisamos adicionar mais nada, pois j?? adicionamos o arquivo que quer??amos adicionar.

Para cada commit, o git cria um checksum, que ?? um c??digo que identifica o commit. Esse c??digo ?? gerado a partir do conte??do do arquivo, ent??o se voc?? fizer uma altera????o no arquivo, o checksum vai mudar. Isso ?? pra garantir que voc?? n??o vai perder nenhuma altera????o.

&nbsp;

Uma coisa bem legal ?? utilizar o comando git log para ver os commits que voc?? fez.

```bash
git log
```

&nbsp;

A sa??da do comando ser?? a seguinte:

```bash
commit 1cd4e1b20df73c2cb24694ab6b9fbb518a19a62e (HEAD -> main)
Author: Jeferson Fernando <jeferson@linuxtips.io>
Date:   Sat Feb 4 18:33:30 2023 +0100

    Adicionando o arquivo README.md
```

&nbsp;

O que o git log faz ?? listar todos os commits que voc?? fez, mostrando o checksum, o autor, a data e a mensagem do commit.

Podemos deixar essa sa??da mais bonita, utilizando o comando git log --oneline.

```bash
1cd4e1b (HEAD -> main) Adicionando o arquivo README.md
```

&nbsp;

Nesse caso ele nem mostra o autor, nem a data, apenas o checksum e a mensagem do commit, e ainda o checksum fica mais curto, pois ele adiciona somente as 7 primeiras letras do checksum.

Iremos ver muito o git log, pois ?? muito ??til para entender todo o hist??rico do seu projeto.

&nbsp;

### Compartilhando o nosso reposit??rio

Agora que j?? temos o nosso repo criado e gerenciado pelo Git, precisamos compartilhar ele com todo mundo, assim todas as pessoas poder??o adicionar novas receitas ou corrigir os erros que existem no conte??do que criamos.

Para compartilhar o nosso reposit??rio, precisamos criar um reposit??rio remoto no GitHub. Temos outras op????es, como o GitLab, Bitbucket, etc, mas vamos utilizar o GitHub por ser o mais popular e por ser gratuito, pelo menos para o que vamos utilizar.

&nbsp;

Para criar o seu repositorio no GitHub, voc?? precisa acessar o site do GitHub e fazer o login. Depois de fazer o login, clique no bot??o com o sinal '+' e depois New Repository, que fica no canto superior direito da tela.

![Criando um novo reposit??rio no GitHub](images/tela-criando-repositorio-github.png)

&nbsp;

Agora voc?? precisa preencher o nome do seu reposit??rio, lembre-se, o nome do reposit??prio precisa ser igual ao do nosso e-book, somente para que fique mais f??cil de eu conferir o trabalho de voc??s depois.

Ent??o o nome do reposit??rio deve ser **DevChef-LINUXtips** e dever?? ser p??blico. N??o esquente a cabe??a com a descri????o e o README, pois j?? criamos. N??o precisa mudar mais nada por enquanto, ent??o clique em Create repository.

![Criando um novo reposit??rio no GitHub](images/tela-criando-repositorio-github-2.png)

&nbsp;

Pronto, repo criado no GitHub. Agora precisamos conectar o nosso reposit??rio local com o reposit??rio remoto.

Perceba que quando voc?? criou o repo no Github, a pr??xima tela que apareceu foi essa:

![Criando um novo reposit??rio no GitHub](images/tela-criando-repositorio-github-3.png)

&nbsp;

Onde ele exibe algumas algumas instru????es de como conectar o seu reposit??rio local com o reposit??rio remoto, seja um reposit??rio que voc?? j?? tenha ou um reposit??rio que voc?? acabou de criar. 

No nosso caso, n??s j?? temos um reposit??rio local, ent??o vamos utilizar a segunda op????o, que ?? a que est?? com o t??tulo **???or push an existing repository from the command line**.

&nbsp;

Vamos voltar para o nosso terminal para que possamos conectar o nosso repositorio local com o reposit??rio remoto.


### Adicionando a nossa chave SSH no GitHub

Antes de conectar o reposit??rio local com o reposit??rio remoto, precisamos adicionar a nossa chave SSH no GitHub. Isso ?? necess??rio para que o GitHub saiba que voc?? ?? o dono do reposit??rio e que voc?? tem permiss??o para fazer altera????es no reposit??rio. 

Voc?? pode utilizar autenticacao via senha, mas vamos fazer da maneira mais elegante e segura, que ?? utilizando a autentica????o via chave SSH.

Antes de mais nada, vamos criar uma chave SSH. Para isso, vamos utilizar o comando ssh-keygen.

```bash
ssh-keygen -t rsa -b 4096 -C "Nossa chave SSH"
```

&nbsp;

O que esse comando faz ?? criar uma chave SSH com o algoritmo RSA, com 4096 bits e com a descri????o **Nossa chave SSH**.

A saida do comando ser?? essa:

```bash
Generating public/private rsa key pair.
Enter file in which to save the key (/home/jeferson/.ssh/id_rsa): /home/jeferson/.ssh/id_rsa_git
Enter passphrase (empty for no passphrase): 
Enter same passphrase again: 
Your identification has been saved in /home/jeferson/.ssh/id_rsa_git
Your public key has been saved in /home/jeferson/.ssh/id_rsa_git.pub
The key fingerprint is:
SHA256:+JCvAhk34WLjAbkDBA3IvtsaZBdEhMkV6CfmrrxkasQ Nossa chave SSH
The key's randomart image is:
+---[RSA 4096]----+
|O=B*.            |
|=*o .            |
|+o o .           |
|o=*.=  o         |
|+*+O .+ S        |
|oE=    +         |
|o+o.    o        |
|=+...  .         |
|=+o  ..          |
+----[SHA256]-----+
```

&nbsp;

Eu criei a chave SSH com o nome **id_rsa_git**, mas voc?? pode criar com o nome que quiser, o padr??o ?? **id_rsa**.

Agora vamos adicionar a nossa chave SSH no GitHub. Para isso, vamos utilizar o comando ssh-add.

```bash
ssh-add ~/.ssh/id_rsa_git
```

Caso voc?? j?? possua uma chave SSH, voc?? pode utiliza-la sem problemas, normalmente ela fica em **~/.ssh/id_rsa.pub**.


&nbsp;

Agora vamos copiar a nossa chave SSH para o clipboard. Para isso, vamos utilizar o comando cat.

```bash
cat ~/.ssh/id_rsa_git.pub | xclip -selection clipboard
```

&nbsp;

Se voc?? n??o tem o comando xclip instalado, voc?? pode instalar com o comando abaixo:

```bash
sudo apt install xclip
```

&nbsp;

Agora vamos adicionar a nossa chave SSH no GitHub: 

- V?? at?? a p??gina de configura????es do GitHub
- Depois em **SSH and GPG keys**
- Clique em **New SSH key**
- Cole a sua chave SSH no campo **Key**
- Adicione um t??tulo para a sua chave SSH no campo **Title**
- Click em **Add SSH key**

Pronto! Sua chave SSH foi adicionada com sucesso.

Agora volte no seu terminal e execute o comando abaixo:

```bash
ssh -T git@github.com
```

&nbsp;

A saida do comando ser?? essa:

```bash
Hi badtuxx! You've successfully authenticated, but GitHub does not provide shell access.
```

&nbsp;

Pronto! Agora voc?? j?? pode conectar o seu reposit??rio local com o reposit??rio remoto, afinal voc?? acabou de validar que a sua chave est?? correta.

&nbsp;

### Conectando o reposit??rio local com o reposit??rio remoto

Para conectar o reposit??rio local com o reposit??rio remoto, precisamos executar o comando git remote add origin e o endere??o do reposit??rio remoto.

```bash
git remote add origin git@github.com:badtuxx/DevChef.git
```

&nbsp;

Aqui estamos utilizando o comando git remote para fazer essa conex??o entre o repo local e o remoto. Vou explicar abaixo o que cada parte do comando faz.

- **git remote** - Esse comando ?? utilizado para gerenciar os reposit??rios remotos. Ele ?? utilizado para adicionar, remover e listar os reposit??rios remotos.

- **add** - Esse comando ?? utilizado para adicionar um reposit??rio remoto.

- **origin** - Esse ?? o nome que vamos dar para o nosso reposit??rio remoto. Podemos dar qualquer nome, mas o nome origin ?? o mais comum, ?? o nosso padr??o e que voc?? vai ver em todos os lugares.

- **git@github.com:badtuxx/DevChef.git** - Esse ?? o endere??o do reposit??rio remoto. Esse endere??o ?? gerado pelo GitHub, quando voc?? cria o reposit??rio. Voc?? pode copiar esse endere??o e colar no seu terminal.

Pronto, voc?? j?? sabe o que o comando acima fez.


Para vizualizar os reposit??rios remotos que voc?? tem, basta executar o comando:

```bash
git remote -v
```

&nbsp;

O comando acima ir?? listar todos os reposit??rios remotos que voc?? tem, e o nome que voc?? deu para cada um deles.

```bash
origin	git@github.com:badtuxx/DevChef.git (fetch)
origin	git@github.com:badtuxx/DevChef.git (push)
```

&nbsp;

Agora que j?? conectamos o nosso repositorio local com o reposit??rio remoto, precisamos enviar o nosso conte??do para o reposit??rio remoto, enviar o nosso conte??do para o GitHub.

### Enviando o conte??do para o reposit??rio remoto

Para enviar o conte??do para o reposit??rio remoto, precisamos executar o comando git push.

```bash
git push origin main
```

&nbsp;

O comando git push ?? o comando utilizado para enviar o conte??do do nosso reposit??rio local para o reposit??rio remoto. No comando acima estamos passando alguns parametros importantes, onde o **origin** ?? o nome do reposit??rio remoto que voc?? deu e o **main** ?? o nome da branch que voc?? quer enviar, a nossa branch principal.

A saida do comando do comando acima ser?? algo parecido com isso:

```bash
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 32 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 510 bytes | 510.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:badtuxx/DevChef.git
 * [new branch]      main -> main
```

&nbsp;

Pronto! Agora j?? temos o nosso conte??do no reposit??rio remoto, no GitHub.

Voc?? pode acessar o seu reposit??rio remoto e ver que o conte??do j?? est?? l??.

Com isso, mesmo que o nosso repositorio local seja apagado, n??s podemos clonar o reposit??rio remoto e teremos o nosso conte??do de volta. M??gico n???

&nbsp;

### Clonando o reposit??rio remoto

Vamos imaginar a seguinte situa????o: Sem querer voc?? apagou o seu reposit??rio local, e agora voc?? quer ter o seu conte??do de volta. Como voc?? faz isso?

A nossa sorte ?? que j?? temos o conte??do do nosso projeto tamb??m repositorio remoto, no GitHub. Ent??o, para ter o nosso conte??do de volta, basta clonar o reposit??rio remoto.

Antes de clonar, vamos remover o nosso reposit??rio local, para simularmos a situa????o de ter apagado o nosso reposit??rio local.

```bash
cd ..  
rm -rf DevChef
```

&nbsp;

Agora vamos clonar o reposit??rio remoto.

```bash
git clone git@github.com:badtuxx/DevChef.git
```

&nbsp;

O comando git clone ?? utilizado para clonar um reposit??rio remoto. No comando acima estamos passando o endere??o do reposit??rio remoto, que ?? o mesmo que utilizamos para conectar o reposit??rio local com o reposit??rio remoto.

A saida do comando ser?? algo parecido com isso:

```bash
Cloning into 'DevChef'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 3 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.
```

&nbsp;

Pronto, voc?? j?? tem o seu conte??do de volta. Agora voc?? pode continuar trabalhando no seu projeto, no nosso livro de receitas.

&nbsp;

### Adicionando a nossa primeira receita

Agora que j?? temos o nosso projeto configurado, vamos come??ar a adicionar as nossas receitas.

Lembrando que o nosso projeto ?? criar um livro de receitas veganas para um nosso almo??o de comemora????o, ap??s finalizarmos o conte??do de material, ser?? o nosso ritual de comemora????o. Claro, se voc?? quiser e puder.

A nossa primeira receita ser?? uma receita de uma arroz para iniciar o card??pio do nosso almo??o. Simples, sem muita frescura, mas que vai deixar todo mundo com ??gua na boca.

Vamos criar um arquivo chamado **arroz.md** dentro da pasta **receitas**.

```bash
cd DevChef
mkdir receitas
cd receitas
touch arroz.md
```

&nbsp;

Pronto, o arquivo **arroz.md** j?? est?? criado. Agora vamos adicionar o conte??do do nosso arquivo. Para isso voc?? pode utilizar o editor de texto de sua prefer??ncia.

```bash
# Receita 1 - Arroz

&nbsp;
## Para quantas pessoas?

- 4 pessoas

&nbsp;
## Ingredientes

- 3 x??cara de arroz
- 6 x??caras de ??gua
- 1 colher de sal
- 3 colheres de azeite ou ??leo de sua prefer??ncia
- 3 dentes de alho picados
- Sementes de girassol a gosto

&nbsp;
## Modo de preparo

Adicione o azeite ou ??leo em uma panela com fogo m??dio, em seguida adicione o alho e as sementes de girassol e deixe fritar at?? o alho ficar dourado. Em seguida adicione o arroz e o sal, mexa bem at?? o arroz ficar bem brilhoso. Adicione a ??gua, e deixe cozinhar at?? a agua secar. Quando a agua secar, desligue o fogo e deixe descansar por 5 minutos com a panela tampada.

Em seguida est?? pronto para servir.

&nbsp;

## Dicas

- Voc?? pode adicionar temperos a gosto, como cebola, pimenta, cebolinha, etc.
```

&nbsp;

Pronto, j?? temos a nossa primeira receita criada, o que precisamos agora ?? adicionar o arquivo ao nosso reposit??rio local.

```bash
git add arroz.md
```

&nbsp;

Vamos verificar o status do nosso reposit??rio local.

```bash
git status
```

&nbsp;

A saida do comando ser?? algo parecido com isso:

```bash
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	new file:   arroz.md

```

&nbsp;

Na sequ??ncia vamos fazer o commit do nosso arquivo.

```bash
git commit -m "Adicionando a receita para fazer o arroz"
```

&nbsp;

A saida do comando ser?? algo parecido com isso:

```bash
[main 135f391] Adicionando a receita para fazer o arroz
 1 file changed, 29 insertions(+)
 create mode 100644 receitas/arroz.md

```

&nbsp;

Hora de enviar o nosso conte??do para o reposit??rio remoto.

```bash
git push origin main
```

&nbsp;

A saida do comando ser?? algo parecido com isso:

```bash
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 32 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 774 bytes | 774.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:badtuxx/DevChef.git
   1cd4e1b..135f391  main -> main

```

&nbsp;

Pronto, a nossa primeira receita j?? est?? em nosso repositorio remoto e voc?? j?? pode conferir no GitHub.

&nbsp;

Para finalizar, vamos adicionar o nosso arquivo **arroz.md** ao nosso arquivo **README.md** no campo de nossa primeira receita.

```markdown
# DevChef

## Sobre o Projeto

Livro criado por pessoas que estavam aprendendo a ferramenta de versionamento de c??digos Git com o Jeferson na LINUXtips.

&nbsp;
## Livro de Receitas Veganas

O Livro foi iniciado com cinco receitas adicionadas e testadas pelo Jeferson, as demais foram adicionadas pela comunidade de pessoas que estavam focadas em aprender Git e ter um almo??o vegano!

&nbsp;
## Receitas

&nbsp;
#### Conte??do 

&nbsp;
#### Receita 1
- [Arroz dos Devs!](receitas/arroz.md)

&nbsp;
#### Receita 2

&nbsp;
#### Receita 3

&nbsp;
#### Receita 4

&nbsp;
#### Receita 5
```

&nbsp;

Pronto, j?? ficou melhor o nosso README.md, assim as pessoas conseguiram ver a nossa primeira receita.

&nbsp;


### Branches

&nbsp;

Uma coisa super importante quando estamos falando sobre um reposit??rio que est?? sendo utilizado por mais de uma pessoa ?? o uso de branches. Branches s??o utilizados para que voc?? possa trabalhar em um projeto sem afetar o trabalho de outras pessoas.

Com isso, podemos deixar a nossa branch principal **main** sempre est??vel e pronta para ser utilizada em produ????o. E podemos criar outras branches para trabalhar em novas funcionalidades, corre????es de bugs, etc.

No nosso caso, vamos imaginar que temos que deixar na nossa branch main apenas as receitas que j?? foram testadas e aprovadas por mim, pois assim eu posso garantir que as pessoas que forem utilizar o nosso livro de receitas n??o v??o ter problemas com as nossas receitas.

Uma branch nada mais ?? do que um espa??o onde voc?? pode trabalhar de forma isolada e muito mais seguro, pois a branch principal tem que ser sempre muito protegida, afinal os nossos usu??rios podem estar utilizando ela.

&nbsp;

Vamos criar uma nova branch para trabalhar em uma nova receita.

```bash
git checkout -b segunda-receita
```

&nbsp;

A saida do comando ser?? algo parecido com isso:

```bash
Switched to a new branch 'segunda-receita'
```

&nbsp;

Agora n??s temos uma nova branch chamada segunda-receita, e seu conte??do ?? exatamente igual a branch main, pois foi como se tivessemos tirado uma foto da branch main e criado uma nova branch com esse conte??do.
Todas as altera????es que fizermos na branch segunda-receita n??o afetar??o a branch main, somente quando fizermos o merge da branch segunda-receita para a branch main, mas isso ?? uma assunto para outro momento.

&nbsp;

Vamos criar um novo arquivo para a nossa segunda receita.

```bash
touch receitas/farofa-vegana.md
```

&nbsp;

Agora vamos adicionar o conte??do do nosso arquivo **farofa-vegana.md**.

```markdown
# Farofa Vegana

&nbsp;
## Para quantas pessoas?

- 4 pessoas

&nbsp;
## Ingredientes
- 1 cebola picada
- 2 bananas picadas
- 4 colheres de azeite ou ??leo de sua prefer??ncia
- Sal a gosto 
- Pimenta do reino a gosto
- Salsinha a gosto
- Paprica a gosto
- 3 x??caras de farinha de mandioca
- 4 dentes de alho picados

&nbsp;
## Modo de Preparo

Primeiro aque??a uma panela e adicione o azeite ou ??leo, na sequ??ncia adicione a cebola e deixe refogar por alguns minutos em fogo baixo, em seguida adicione o alho e deixe refogar at?? o alho ficar mais dourado, mas cuidado para n??o queimar nada.

Agora j?? podemos adicionar a banana, o sal, a pimenta, a salsinha e a paprica, misture bem mas sempre com muito cuidado para n??o desmanchar ou quebrar muito as bananas. Quando a banana come??ar a ficar mais mole, ?? a hora de adicionar a farinha de mandioca, misture bem e deixe cozinhar por alguns minutos, sempre mexendo para n??o grudar no fundo da panela.

A farinha de mandioca vai ficar bem sequinha, mas n??o pode queimar, pois sen??o ir?? mudar o sabor da farofa.

Ap??s alguns minutos, com a farinha de mandioca mais sequinha e com a cor bem dourada, ?? hora de desligar o fogo e servir.

&nbsp;

## Dicas

- Se voc?? quiser, pode adicionar um pouco de molho de tomate na farofa e um pouco de tofu defumado, sua farofa ficar?? ainda mais saborosa.
```

&nbsp;

Pronto, j?? temos o conte??do da nossa segunda receita, j?? podemos atualizar o nosso repo. Lembrando que estamos modificando somente a branch segunda-receita, a branch main continua intacta.

```bash
git add .
git commit -m "Adicionando a receita de farofa vegana"
git push origin segunda-receita
```

&nbsp;

Agora a nossa segunda receita j?? est?? no nosso reposit??rio remoto, mas ainda n??o est?? na branch main.

&nbsp;

Se voc?? for no seu reposit??rio remoto, vai ver que a branch segunda-receita foi criada e que ela tem um commit a mais que a branch main.

[Branches](images/branches.png)


&nbsp;

Para que voc?? possa verificar todas as branches do seu reposit??rio, voc?? pode utilizar o comando:

```bash
git branch -a
```

&nbsp;

A saida do comando ser?? algo parecido com isso:

```bash
  main
* segunda-receita
  remotes/origin/main
  remotes/origin/segunda-receita

```

&nbsp;

Onde:

- **main**: ?? a branch principal do seu reposit??rio
  
- **segunda-receita**: ?? a branch que criamos para trabalhar na nossa segunda receita

- **remotes/origin/main**: ?? a branch principal do seu reposit??rio remoto

- **remotes/origin/segunda-receita**: ?? a branch que criamos para trabalhar na nossa segunda receita no reposit??rio remoto

E como voc?? pode ver, a branch segunda-receita est?? com um asterisco na frente, isso significa que estamos trabalhando nela.

Simples, n??o?

&nbsp;

Vamos atualizar o nosso README.md para adicionar a nossa segunda receita.

```markdown
# DevChef

## Sobre o Projeto

Livro criado por pessoas que estavam aprendendo a ferramenta de versionamento de c??digos Git com o Jeferson na LINUXtips.

&nbsp;
## Livro de Receitas Veganas

O Livro foi iniciado com cinco receitas adicionadas e testadas pelo Jeferson, as demais foram adicionadas pela comunidade de pessoas que estavam focadas em aprender Git e ter um almo??o vegano!

&nbsp;
## Receitas

&nbsp;
#### Conte??do 

&nbsp;
#### Receita 1
- [Arroz dos Devs!](receitas/arroz.md)

&nbsp;
#### Receita 2
- [Farofa Vegana!](receitas/farofa-vegana.md)

&nbsp;
#### Receita 3

&nbsp;
#### Receita 4

&nbsp;
#### Receita 5
```

&nbsp;

Vamos atualizar o nosso repo.

```bash
git commit -m "Adicionando a receita de farofa vegana no README.md" -a
git push origin segunda-receita
```

&nbsp;

Pronto! Branch segunda-receita atualizada.

&nbsp;

### Fazendo o merge da branch segunda-receita para a branch main

Vamos imaginar que o time que est?? desenvolvendo esse livro de receitas, decidiu que a segunda receita est?? pronta para ser adicionada ao livro, portanto, podemos fazer o merge da branch segunda-receita para a branch main.

Mas o que ?? um merge?

O merge ?? a uni??o de duas branches, onde voc?? est?? unindo o conte??do da branch A para a branch B. No nosso caso, estamos unindo a branch segunda-receita para a branch main.

Durante o merge voc?? est?? pedindo para o Git, que ele fa??a a uni??o das duas branches, mas o Git n??o vai fazer isso de qualquer forma, ele vai verificar se existe algum conflito entre as duas branches, se existir, ele vai te avisar e voc?? ter?? que resolver o conflito manualmente.

N??s ainda vamos falar sobre conflitos, mas por enquanto, vamos fazer o merge da branch segunda-receita para a branch main.

Lembrando que o que queremos ?? adicionar todo o conte??do novo que criamos na branch segunda-receita para a branch main.

&nbsp;

Vamos para a branch main.

```bash
git checkout main
```

&nbsp;

Agora vamos fazer o merge da branch segunda-receita para a branch main.

```bash
git merge segunda-receita
```

&nbsp;

O comando acima pediu para o Git pegar o conte??do da branch segunda-receita e adicionar para a branch main, uni-las, atualizando a nossa branch main.

A saida do comando ser?? algo parecido com isso:

```bash
Updating 7def92f..9eb025b
Fast-forward
 README.md | 1 +
 1 file changed, 1 insertion(+)
```

&nbsp;

Se tivesse algum conflito para resolver, seria nesse momento que o Git iria reclamar e pedir para voc?? resolver o conflito.

Lembrando que sempre voc?? poder?? utilizar o comando git log para verificar o hist??rico de commits do seu reposit??rio.

O pr??ximo passo ?? atualizar o nosso reposit??rio remoto.

```bash
git push origin main
```

&nbsp;

Pronto! Agora a nossa branch main est?? com o conte??do da branch segunda-receita.

[Branch main](images/branch-main.png)

&nbsp;

### Deletando a branch segunda-receita

Agora n??o precisamos continuar com a branch segunda-receita, pois j?? fizemos o merge dela para a branch main, portanto, podemos deletar a branch segunda-receita.

```bash
git branch -d segunda-receita
```

&nbsp;

A saida do comando ser?? algo parecido com isso:

```bash
Deleted branch segunda-receita (was 9eb025b).
```

&nbsp;

Vamos verificar se a branch segunda-receita foi realmente deletada.

```bash
git branch
```

&nbsp;

A saida do comando ser?? algo parecido com isso:

```bash
* main
```

&nbsp;

Se voc?? usar o comando git branch -a, voc?? vai ver que a branch segunda-receita n??o existe mais no reposit??rio local, mas ela ainda existe no reposit??rio remoto.

```bash
* main
  remotes/origin/main
  remotes/origin/segunda-receita
```

&nbsp;

Vamos atualizar o nosso reposit??rio remoto.

```bash
git push origin --delete segunda-receita
```

&nbsp;

A saida do comando ser?? algo parecido com isso:

```bash
To github.com:badtuxx/DevChef.git
 - [deleted]         segunda-receita

```

&nbsp;

Vamos listar as branches do nosso reposit??rio local e remoto novamente.

```bash
git branch -a
```

&nbsp;

A saida do comando ser?? algo parecido com isso:


```bash
* main
  remotes/origin/main
```

&nbsp;

J?? era! A branch segunda-receita foi deletada do nosso reposit??rio local e remoto.

&nbsp;

N??s poderiamos ter feito esse processo de merge e de delete da nossa branch diretamente na interface do GitHub, mas como estamos aprendendo, vamos fazer tudo pelo terminal. O foco aqui ?? o Git e n??o o GitHub. :D

&nbsp;

### Conflitos

WIP



