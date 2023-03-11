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
  - [Vamos começar!](#vamos-começar)
    - [O que é o git?](#o-que-é-o-git)
    - [Criando o repo do nosso livro](#criando-o-repo-do-nosso-livro)
    - [Compartilhando o nosso repositório](#compartilhando-o-nosso-repositório)
    - [Adicionando a nossa chave SSH no GitHub](#adicionando-a-nossa-chave-ssh-no-github)
    - [Conectando o repositório local com o repositório remoto](#conectando-o-repositório-local-com-o-repositório-remoto)
    - [Enviando o conteúdo para o repositório remoto](#enviando-o-conteúdo-para-o-repositório-remoto)
    - [Clonando o repositório remoto](#clonando-o-repositório-remoto)
    - [Adicionando a nossa primeira receita](#adicionando-a-nossa-primeira-receita)
    - [Branches](#branches)
    - [Fazendo o merge da branch segunda-receita para a branch main](#fazendo-o-merge-da-branch-segunda-receita-para-a-branch-main)
    - [Deletando a branch segunda-receita](#deletando-a-branch-segunda-receita)
    - [Conflitos](#conflitos)

*******


## A proposta do material

Durante o conteúdo do material, a pessoa estudante tera a oportunidade de aprender desde conceitos básicos sobre o Git, até tarefas mais avançadas que são parte do dia a dia de uma pessoa senior que trabalha como TI.

Se você é uma pessoa desenvolvedora, DevOps Engineer, SRE, Platform Engineer, etc... Qualquer carreira dentro de tecnologia precisa conhecer como gerenciar os seus códigos de forma organizada e compartilhada com outras pessoas.

Dito isso, precisamos ter um projeto de exemplo para a nossa jornada. Eu pensei em criar um projeto de IaC ou ainda uma App em Python, mas acabei optando por escrever sobre algo que todo mundo já conhece, ou pelo menos já teve contato uma vez na vida.

Para utilizar como exemplo, nós vamos criar um pequeno livro de receitas, sim receitas! 
E não estou falando de receitas do Chef da OpsCode, estou falando sobre um livro de receitas de comidas, e de preferencia comidas vegana! 

Então é isso, enquanto vamos aprendendo sobre o sensacional Git, já vamos ainda aprendendo sobre como fazer um rango bem gostoso vegano! 

No final desse material, eu quero que além do almoço, você também crie um repositório no Github com o seu livro, que seria um fork do nosso repo do material, com uma nova receita adicionada por você!

Depois é só abrir um PR lá no Github que faremos o commit para a main!

Assim teremos um livro bem foda, totalmente criado pela comunidade Dev!

&nbsp;
## O Livro: DevChef ???

Precisamos ter um nome para o nosso livro, eu vou deixar como DevChef por enquanto, mas é claro, se alguém tiver uma ideia melhor é só falar, abre uma issue aqui no Github com a sugestão!

O endereço do repositório do nosso livro de receitas é o:

```bash
https://github.com/badtuxx/**DevChef**
```

Muito bem, dito isso acho que já podemos começar!

Lembre-se, o nosso livro será vegano! Mesmo que você não seja, vamos fazer esse esforço para que possamos celebrar juntos todo esse aprendizado!

&nbsp;
## Sobre o material Descomplicando o Git

Vamos criar o nosso livro de receitas, mas o objetivo principal é aprender sobre o Git. E aqui não queremos aprender o Git decoreba, queremos aprender o Git que é usado no dia a dia! 

Eu tenho mais de 12 anos de experiência trabalhando com Git em ambientes grandes e complexos, com times que de centenas de pessoas compartilhando o mesmo repositório Git, e essa experiência acumulado que quero trazer aqui para vocês!

Esse material é a base do Workshow Descomplicando o Git que criei para a LINUXtips!
Se você está afim de aprender muito sobre o Git em formato de vídeo, colá lá no site da LINUXtips!

Iremos ainda criar um e-book com esse conteúdo, então se você está lendo esse conteúdo em um PDF bonitinho e bem formatadinho, parabéns e muito obrigado por ter adquirido a cópia do e-book!

E claro, temos o repositório desse material lá no Github no seguinte endereço:

```bash
https://github.com/badtuxx/DescomplicandoGit
```

O material está sobre a licensa GPL-3, então fique a vontade em aprender de forma totalmente gratuita, e ainda, ajudar adicionando ainda mais conteúdo nesse sensacional repositório, combinado?

E claro, caso queira utilizar esse material para ensinar outras pessoas, fique a vontade! Evidente, respeitando o que diz a licensa do código!

As pessoas que mais contribuirem para esse repo serão consideradas pessoas mantenedoras e com isso terá acesso ao e-book e também ao workshop. E claro, o nome nos agradecimentos do e-book! 

Teremos 3 vagas para pessoas mantenedoras!

Se você ainda está vendo esse texto, significa que ainda não temos essas pessoas escolhidas, então aqui está uma boa oportunidade!


Como base para esse material nós vamos utilizar a documentação oficial do projeto, que você pode acessar através dessa url:

```bash
https://git-scm.com/docs
```

Ahhh, e parabéns demais para a galera envolvida na construção dessa doc, e mais do que isso, parabéns para a galera empenhada em fazer a tradução desse material para o Português! Boa parte da documentação está em Português e com uma qualidade excelente!

&nbsp;

## Vamos começar!


### O que é o git?

A primeira coisa que temos que ter em mente, é o que é o Git. O Git nada mais é do que uma ferramenta para que você possa versionar o seu código, e mais do que isso, versionar o seu código e deixo organizado mesmo que compartilhado com milhares de pessoas desenvolvedoras.

Eu poderia ficar aqui falando que o Git é um VCS como nós tinhamos o Subversion e outras velharias, mas com todo o respeito, a maioria das pessoas que trabalham hoje com código versionado e compartilhado, não tem nem a menor ideia do que um VCS, elas apenas sabem que quando você precisa versionar e ter um gerenciamento descente de código, você utiliza o Git.

Ela foi criada em 2005 por Linus Torvalds, o criador do Linux. Ele criou o Git pois estava insatisfeito com funcionavam os versionadores de códigos da época. Fácil né. hahahha

Pode ser uma opinião muito forte sobre, mas é a realidade que eu tenho visto nos últimos 10 anos, pelo menos.

Pois bem, dito isso, o que precisamos entender é como o Git funciona, e para isso é fundamental começarmos entender isso praticando, essa é a nossa maneira de ensinar!

Então chegou a hora de começar a criar o nosso livro de receitas DevChef e iniciar a nossa jornada de aprendizado com o Git.


### Criando o repo do nosso livro

Muito bem, agora já sabemos que o nosso projeto será um livro de receitas, o que precisamos fazer é começar a trabalhar!

Para isso vamos criar um diretório chamado DevChef, conforme abaixo:

```bash
mkdir DevChef
```

&nbsp;
Pronto, agora vamos acessa-lo:

```bash
cd DevChef/
```
&nbsp;

Agora vamos criar uma arquivo chamado README.md e te explico no caminho o porque é importante ter esse cara em nosso repo.

```bash
touch README.md
```
&nbsp;

Agora que já criamos o arquivo, eu posso te explicar a sua utilidade e porque ele é importante.

O README.md é o arquivo onde você coloca os detalhes do seu repo, do seu projeto.

E como se fosse o página principal de um site, a primeira página do nosso repo. Quando alguém acessar o nosso repo, ele será recebido por essa página.

Para o nosso livro, vamos deixar nesse arquivo todo o conteúdo. Nós vamos deixar bonitinho, vai ser fácil!

Outra coisa, você viu que a o final do nome do arquivo é terminado com .md, isso indica que estamos querendo criar um arquivo utilizando a linguigem de marcação Markdown, que você pode ver mais detalhes [aqui](https://pt.wikipedia.org/wiki/Markdown).

Nós vamos aprender algumas coisa sobre como utilizar o Markdown, pois precisamos deixar o nosso livro bonitinho!

Muito pooom! Todo mundo já sabe o que é esse tal de README.md, agora vamos colocar algum conteúdo lá dentro!

Para isso você pode utilizar o VI ou outro editor de textos de sua preferencia. Enquanto eu escrevo esse material, estou utilizando o Visual Studio Code, super recomendo pois ele vai agilizar e muito a sua vida. Mas se você não tiver, não tem problemas, utilize o editor que você achar melhor.

Durante a construção desse material estou utilizando o Linux, então todos os exemplos de linha de comando são realizadas no Linux.


Adicione o seguinte conteúdo no arquivo:

```markdown
# DevChef

## Sobre o Projeto

Livro criado por pessoas que estavam aprendendo a ferramenta de versionamento de códigos Git com o Jeferson na LINUXtips.

&nbsp;
## Livro de Receitas Veganas

O Livro foi iniciado com cinco receitas adicionadas e testadas pelo Jeferson, as demais foram adicionadas pela comunidade de pessoas que estavam focadas em aprender Git e ter um almoço vegano!

&nbsp;
## Receitas

&nbsp;
#### Conteúdo 

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

Pronto, acho que temos uma boa definição inicial do nosso livro, e ainda montamos o esqueleto inicial do nosso livro.

Muito bem, já temos o arquivo mas ainda não fizemos nada em relação ao Git.

Precisamos falar para o Git que queremos que ele cuide de nosso arquivo, do nosso diretório. Para isso, antes de mais nada precisamos instalar o Git no Linux caso ainda você não tenha.

Para realizar a instalação do Git no Ubuntu, utilize o comando abaixo:

```bash
sudo apt install git
```

&nbsp;

Você pode verificar se o Git foi instalado corretamente utilizando o comando abaixo:

```bash
git --version
```

&nbsp;

Para ver como instalar o git no Windows, você pode acessar o link [aqui](https://git-scm.com/download/win). 

Já para o MacOS, você pode acessar o link [aqui](https://git-scm.com/download/mac).

&nbsp;

Após fazer a instalação, é hora de falar para ele que queremos que ele comece a cuidar de nosso diretório.

Mas antes de começar, precisamos fazer algumas configurações em nosso git. Informações como o nome do usuário, email, editor de texto e principalmente o nome da branch. Hoje em dia o nome dca branch padrão é o main, se ainda não é o seu caso, você pode alterar utilizando o comando abaixo:

```bash
git config --global init.defaultBranch main
```

Nós ainda vamos falar muito sobre branches e vou te explicar com todos os detalhes, mas por enquanto pensa que é o nome da sua mesa de trabalho atual, vamos imaginar que é a visão que você tem do seu projeto atual. Eu digo visão, pois você pode ter várias mesas de trabalho, e cada uma delas é uma branch, e cada uma com uma visão diferente do seu projeto.

Confuso? Sim! Mas somente agora!
Logo menos você vai entender tudo e ver o quanto isso salva vidas!

Vamos somente definir uma coisa, a nossa branch main vai ser a nossa principal, como se fosse a versão estável, a versão que poderia ser publicada em produção, certo?

Por enquanto é isso sobre branches, mas como eu disse, vamos falar muito sobre elas.

Vamos fazer algumas configurações básicas do Git, para isso vamos utilizar o comando abaixo:

```bash
git config --global user.name "Seu Nome"
git config --global user.email "
```

Essas são as configurações básicas, mas você pode configurar outras coisas, como por exemplo, o editor de texto que você quer utilizar, para isso utilize o comando abaixo:

```bash
git config --global core.editor "vim"
```

&nbsp;

Agora sim podemos iniciar o nosso repositório Git. Para isso, vamos utilizar o comando abaixo:

```bash
git init
```

A saída do comando será a seguinte:

```bash
Initialized empty Git repository in /home/jeferson/REPOS/DevChef/.git/
```

&nbsp;

O comando git init é o comando utilizado para iniciar o nosso repositorio, ou seja, ele vai criar o nosso .git, que é o diretório onde o Git vai guardar todas as informações sobre o nosso projeto.

```bash
ls .git/
```

&nbsp;

Dentro do diretório, você vai encontrar todos os arquivos que o Git precisa para organizar a nossa casa, o nosso projeto. Nós ainda vamos voltar algumas vezes aqui para explicar o que está acontecendo, mas por enquanto, somente saiba que ele existe e é aqui que estão todas as informações do nosso projeto, como as branches, os commits, as tags, etc.

Mais uma vez, eu sei que ainda não vimos nada disso, mas vamos ver, é só pra deixar você ainda mais curiosa!

&nbsp;

Vamos voltar as atenções para o nosso repo e para o conteúdo que estamos criando.

Um comando que é muito útil e que vai trazer o status atual do nosso projeto é o comando git status.

```bash
git status
```

A saída do comando será a seguinte:

```bash
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	README.md

nothing added to commit but untracked files present (use "git add" to track)
```

&nbsp;

Perceba que o Git nos informa que estamos na branch main, que ainda não temos nenhum commit e que temos um arquivo, que existe, mas que ainda não foi adicionado ao nosso repositório.

Para adicionarmos o nosso arquivo ao nosso repositório, vamos utilizar o comando git add.

```bash
git add README.md
```

&nbsp;

Vamos executar o comando git status novamente para ver o que aconteceu.

```bash
git status
```

A saída do comando será a seguinte:

```bash
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   README.md
```

&nbsp;

Agora nós temos um arquivo que foi adicionado ao nosso repositório, mas isso ainda não garante o controle de versão, pois ainda não fizemos nenhum commit.

Para entender melhor o que o comando acima fez, precisamos entender os três estados do Git.

O Git trabalha com três estados, o estado de trabalho, o estado de preparação e o estado de commit.

É bem comum você ver esses três estados em inglês, então normamente você vai ver o Working Directory, o Staging Area e o Repository.

- O Working Directory é o diretório onde você está trabalhando, onde você está criando os seus arquivos, onde você está fazendo as suas alterações.

- O Staging Area é o local onde você vai adicionar os arquivos que você quer que o Git comece a controlar, ou seja, o Git vai começar a monitorar as alterações que você fizer nesses arquivos.

- O Repository é o local onde o Git vai guardar todas as informações sobre o seu projeto, como as branches, os commits, as tags, etc. Esse é o nosso diretório .git.

Quando estamos usando o comando git add, nós estamos adicionando os arquivos que queremos que o Git comece a controlar, ou seja, estamos adicionando os arquivos ao Staging Area.

Então temos esse arquivo controlado pelo Git, mas ainda não temos um commit. O commit é o ato de adicionar as alterações que você fez no seu arquivo ao seu repositório.

É importante você conhecer esses três estados, pois lá pra frente você vai precisar deles para saber como atuar em cada situação.

&nbsp;

Agora que já entendemos o que o comando git add faz, vamos fazer o nosso primeiro commit.

```bash
git commit -m "Adicionando o arquivo README.md"
```

&nbsp;


A saída do comando será a seguinte:

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

A saída do comando será a seguinte:

```bash
On branch main
nothing to commit, working tree clean
```

&nbsp;

O que ele está dizendo que não precisamos adicionar mais nada, pois já adicionamos o arquivo que queríamos adicionar.

Para cada commit, o git cria um checksum, que é um código que identifica o commit. Esse código é gerado a partir do conteúdo do arquivo, então se você fizer uma alteração no arquivo, o checksum vai mudar. Isso é pra garantir que você não vai perder nenhuma alteração.

&nbsp;

Uma coisa bem legal é utilizar o comando git log para ver os commits que você fez.

```bash
git log
```

&nbsp;

A saída do comando será a seguinte:

```bash
commit 1cd4e1b20df73c2cb24694ab6b9fbb518a19a62e (HEAD -> main)
Author: Jeferson Fernando <jeferson@linuxtips.io>
Date:   Sat Feb 4 18:33:30 2023 +0100

    Adicionando o arquivo README.md
```

&nbsp;

O que o git log faz é listar todos os commits que você fez, mostrando o checksum, o autor, a data e a mensagem do commit.

Podemos deixar essa saída mais bonita, utilizando o comando git log --oneline.

```bash
1cd4e1b (HEAD -> main) Adicionando o arquivo README.md
```

&nbsp;

Nesse caso ele nem mostra o autor, nem a data, apenas o checksum e a mensagem do commit, e ainda o checksum fica mais curto, pois ele adiciona somente as 7 primeiras letras do checksum.

Iremos ver muito o git log, pois é muito útil para entender todo o histórico do seu projeto.

&nbsp;

### Compartilhando o nosso repositório

Agora que já temos o nosso repo criado e gerenciado pelo Git, precisamos compartilhar ele com todo mundo, assim todas as pessoas poderão adicionar novas receitas ou corrigir os erros que existem no conteúdo que criamos.

Para compartilhar o nosso repositório, precisamos criar um repositório remoto no GitHub. Temos outras opções, como o GitLab, Bitbucket, etc, mas vamos utilizar o GitHub por ser o mais popular e por ser gratuito, pelo menos para o que vamos utilizar.

&nbsp;

Para criar o seu repositorio no GitHub, você precisa acessar o site do GitHub e fazer o login. Depois de fazer o login, clique no botão com o sinal '+' e depois New Repository, que fica no canto superior direito da tela.

![Criando um novo repositório no GitHub](images/tela-criando-repositorio-github.png)

&nbsp;

Agora você precisa preencher o nome do seu repositório, lembre-se, o nome do repositóprio precisa ser igual ao do nosso e-book, somente para que fique mais fácil de eu conferir o trabalho de vocês depois.

Então o nome do repositório deve ser **DevChef-LINUXtips** e deverá ser público. Não esquente a cabeça com a descrição e o README, pois já criamos. Não precisa mudar mais nada por enquanto, então clique em Create repository.

![Criando um novo repositório no GitHub](images/tela-criando-repositorio-github-2.png)

&nbsp;

Pronto, repo criado no GitHub. Agora precisamos conectar o nosso repositório local com o repositório remoto.

Perceba que quando você criou o repo no Github, a próxima tela que apareceu foi essa:

![Criando um novo repositório no GitHub](images/tela-criando-repositorio-github-3.png)

&nbsp;

Onde ele exibe algumas algumas instruções de como conectar o seu repositório local com o repositório remoto, seja um repositório que você já tenha ou um repositório que você acabou de criar. 

No nosso caso, nós já temos um repositório local, então vamos utilizar a segunda opção, que é a que está com o título **…or push an existing repository from the command line**.

&nbsp;

Vamos voltar para o nosso terminal para que possamos conectar o nosso repositorio local com o repositório remoto.


### Adicionando a nossa chave SSH no GitHub

Antes de conectar o repositório local com o repositório remoto, precisamos adicionar a nossa chave SSH no GitHub. Isso é necessário para que o GitHub saiba que você é o dono do repositório e que você tem permissão para fazer alterações no repositório. 

Você pode utilizar autenticacao via senha, mas vamos fazer da maneira mais elegante e segura, que é utilizando a autenticação via chave SSH.

Antes de mais nada, vamos criar uma chave SSH. Para isso, vamos utilizar o comando ssh-keygen.

```bash
ssh-keygen -t rsa -b 4096 -C "Nossa chave SSH"
```

&nbsp;

O que esse comando faz é criar uma chave SSH com o algoritmo RSA, com 4096 bits e com a descrição **Nossa chave SSH**.

A saida do comando será essa:

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

Eu criei a chave SSH com o nome **id_rsa_git**, mas você pode criar com o nome que quiser, o padrão é **id_rsa**.

Agora vamos adicionar a nossa chave SSH no GitHub. Para isso, vamos utilizar o comando ssh-add.

```bash
ssh-add ~/.ssh/id_rsa_git
```

Caso você já possua uma chave SSH, você pode utiliza-la sem problemas, normalmente ela fica em **~/.ssh/id_rsa.pub**.


&nbsp;

Agora vamos copiar a nossa chave SSH para o clipboard. Para isso, vamos utilizar o comando cat.

```bash
cat ~/.ssh/id_rsa_git.pub | xclip -selection clipboard
```

&nbsp;

Se você não tem o comando xclip instalado, você pode instalar com o comando abaixo:

```bash
sudo apt install xclip
```

&nbsp;

Agora vamos adicionar a nossa chave SSH no GitHub: 

- Vá até a página de configurações do GitHub
- Depois em **SSH and GPG keys**
- Clique em **New SSH key**
- Cole a sua chave SSH no campo **Key**
- Adicione um título para a sua chave SSH no campo **Title**
- Click em **Add SSH key**

Pronto! Sua chave SSH foi adicionada com sucesso.

Agora volte no seu terminal e execute o comando abaixo:

```bash
ssh -T git@github.com
```

&nbsp;

A saida do comando será essa:

```bash
Hi badtuxx! You've successfully authenticated, but GitHub does not provide shell access.
```

&nbsp;

Pronto! Agora você já pode conectar o seu repositório local com o repositório remoto, afinal você acabou de validar que a sua chave está correta.

&nbsp;

### Conectando o repositório local com o repositório remoto

Para conectar o repositório local com o repositório remoto, precisamos executar o comando git remote add origin e o endereço do repositório remoto.

```bash
git remote add origin git@github.com:badtuxx/DevChef.git
```

&nbsp;

Aqui estamos utilizando o comando git remote para fazer essa conexão entre o repo local e o remoto. Vou explicar abaixo o que cada parte do comando faz.

- **git remote** - Esse comando é utilizado para gerenciar os repositórios remotos. Ele é utilizado para adicionar, remover e listar os repositórios remotos.

- **add** - Esse comando é utilizado para adicionar um repositório remoto.

- **origin** - Esse é o nome que vamos dar para o nosso repositório remoto. Podemos dar qualquer nome, mas o nome origin é o mais comum, é o nosso padrão e que você vai ver em todos os lugares.

- **git@github.com:badtuxx/DevChef.git** - Esse é o endereço do repositório remoto. Esse endereço é gerado pelo GitHub, quando você cria o repositório. Você pode copiar esse endereço e colar no seu terminal.

Pronto, você já sabe o que o comando acima fez.


Para vizualizar os repositórios remotos que você tem, basta executar o comando:

```bash
git remote -v
```

&nbsp;

O comando acima irá listar todos os repositórios remotos que você tem, e o nome que você deu para cada um deles.

```bash
origin	git@github.com:badtuxx/DevChef.git (fetch)
origin	git@github.com:badtuxx/DevChef.git (push)
```

&nbsp;

Agora que já conectamos o nosso repositorio local com o repositório remoto, precisamos enviar o nosso conteúdo para o repositório remoto, enviar o nosso conteúdo para o GitHub.

### Enviando o conteúdo para o repositório remoto

Para enviar o conteúdo para o repositório remoto, precisamos executar o comando git push.

```bash
git push origin main
```

&nbsp;

O comando git push é o comando utilizado para enviar o conteúdo do nosso repositório local para o repositório remoto. No comando acima estamos passando alguns parametros importantes, onde o **origin** é o nome do repositório remoto que você deu e o **main** é o nome da branch que você quer enviar, a nossa branch principal.

A saida do comando do comando acima será algo parecido com isso:

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

Pronto! Agora já temos o nosso conteúdo no repositório remoto, no GitHub.

Você pode acessar o seu repositório remoto e ver que o conteúdo já está lá.

Com isso, mesmo que o nosso repositorio local seja apagado, nós podemos clonar o repositório remoto e teremos o nosso conteúdo de volta. Mágico né?

&nbsp;

### Clonando o repositório remoto

Vamos imaginar a seguinte situação: Sem querer você apagou o seu repositório local, e agora você quer ter o seu conteúdo de volta. Como você faz isso?

A nossa sorte é que já temos o conteúdo do nosso projeto também repositorio remoto, no GitHub. Então, para ter o nosso conteúdo de volta, basta clonar o repositório remoto.

Antes de clonar, vamos remover o nosso repositório local, para simularmos a situação de ter apagado o nosso repositório local.

```bash
cd ..  
rm -rf DevChef
```

&nbsp;

Agora vamos clonar o repositório remoto.

```bash
git clone git@github.com:badtuxx/DevChef.git
```

&nbsp;

O comando git clone é utilizado para clonar um repositório remoto. No comando acima estamos passando o endereço do repositório remoto, que é o mesmo que utilizamos para conectar o repositório local com o repositório remoto.

A saida do comando será algo parecido com isso:

```bash
Cloning into 'DevChef'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 3 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.
```

&nbsp;

Pronto, você já tem o seu conteúdo de volta. Agora você pode continuar trabalhando no seu projeto, no nosso livro de receitas.

&nbsp;

### Adicionando a nossa primeira receita

Agora que já temos o nosso projeto configurado, vamos começar a adicionar as nossas receitas.

Lembrando que o nosso projeto é criar um livro de receitas veganas para um nosso almoço de comemoração, após finalizarmos o conteúdo de material, será o nosso ritual de comemoração. Claro, se você quiser e puder.

A nossa primeira receita será uma receita de uma arroz para iniciar o cardápio do nosso almoço. Simples, sem muita frescura, mas que vai deixar todo mundo com água na boca.

Vamos criar um arquivo chamado **arroz.md** dentro da pasta **receitas**.

```bash
cd DevChef
mkdir receitas
cd receitas
touch arroz.md
```

&nbsp;

Pronto, o arquivo **arroz.md** já está criado. Agora vamos adicionar o conteúdo do nosso arquivo. Para isso você pode utilizar o editor de texto de sua preferência.

```bash
# Receita 1 - Arroz

&nbsp;
## Para quantas pessoas?

- 4 pessoas

&nbsp;
## Ingredientes

- 3 xícara de arroz
- 6 xícaras de água
- 1 colher de sal
- 3 colheres de azeite ou óleo de sua preferência
- 3 dentes de alho picados
- Sementes de girassol a gosto

&nbsp;
## Modo de preparo

Adicione o azeite ou óleo em uma panela com fogo médio, em seguida adicione o alho e as sementes de girassol e deixe fritar até o alho ficar dourado. Em seguida adicione o arroz e o sal, mexa bem até o arroz ficar bem brilhoso. Adicione a água, e deixe cozinhar até a agua secar. Quando a agua secar, desligue o fogo e deixe descansar por 5 minutos com a panela tampada.

Em seguida está pronto para servir.

&nbsp;

## Dicas

- Você pode adicionar temperos a gosto, como cebola, pimenta, cebolinha, etc.
```

&nbsp;

Pronto, já temos a nossa primeira receita criada, o que precisamos agora é adicionar o arquivo ao nosso repositório local.

```bash
git add arroz.md
```

&nbsp;

Vamos verificar o status do nosso repositório local.

```bash
git status
```

&nbsp;

A saida do comando será algo parecido com isso:

```bash
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	new file:   arroz.md

```

&nbsp;

Na sequência vamos fazer o commit do nosso arquivo.

```bash
git commit -m "Adicionando a receita para fazer o arroz"
```

&nbsp;

A saida do comando será algo parecido com isso:

```bash
[main 135f391] Adicionando a receita para fazer o arroz
 1 file changed, 29 insertions(+)
 create mode 100644 receitas/arroz.md

```

&nbsp;

Hora de enviar o nosso conteúdo para o repositório remoto.

```bash
git push origin main
```

&nbsp;

A saida do comando será algo parecido com isso:

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

Pronto, a nossa primeira receita já está em nosso repositorio remoto e você já pode conferir no GitHub.

&nbsp;

Para finalizar, vamos adicionar o nosso arquivo **arroz.md** ao nosso arquivo **README.md** no campo de nossa primeira receita.

```markdown
# DevChef

## Sobre o Projeto

Livro criado por pessoas que estavam aprendendo a ferramenta de versionamento de códigos Git com o Jeferson na LINUXtips.

&nbsp;
## Livro de Receitas Veganas

O Livro foi iniciado com cinco receitas adicionadas e testadas pelo Jeferson, as demais foram adicionadas pela comunidade de pessoas que estavam focadas em aprender Git e ter um almoço vegano!

&nbsp;
## Receitas

&nbsp;
#### Conteúdo 

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

Pronto, já ficou melhor o nosso README.md, assim as pessoas conseguiram ver a nossa primeira receita.

&nbsp;


### Branches

&nbsp;

Uma coisa super importante quando estamos falando sobre um repositório que está sendo utilizado por mais de uma pessoa é o uso de branches. Branches são utilizados para que você possa trabalhar em um projeto sem afetar o trabalho de outras pessoas.

Com isso, podemos deixar a nossa branch principal **main** sempre estável e pronta para ser utilizada em produção. E podemos criar outras branches para trabalhar em novas funcionalidades, correções de bugs, etc.

No nosso caso, vamos imaginar que temos que deixar na nossa branch main apenas as receitas que já foram testadas e aprovadas por mim, pois assim eu posso garantir que as pessoas que forem utilizar o nosso livro de receitas não vão ter problemas com as nossas receitas.

Uma branch nada mais é do que um espaço onde você pode trabalhar de forma isolada e muito mais seguro, pois a branch principal tem que ser sempre muito protegida, afinal os nossos usuários podem estar utilizando ela.

&nbsp;

Vamos criar uma nova branch para trabalhar em uma nova receita.

```bash
git checkout -b segunda-receita
```

&nbsp;

A saida do comando será algo parecido com isso:

```bash
Switched to a new branch 'segunda-receita'
```

&nbsp;

Agora nós temos uma nova branch chamada segunda-receita, e seu conteúdo é exatamente igual a branch main, pois foi como se tivessemos tirado uma foto da branch main e criado uma nova branch com esse conteúdo.
Todas as alterações que fizermos na branch segunda-receita não afetarão a branch main, somente quando fizermos o merge da branch segunda-receita para a branch main, mas isso é uma assunto para outro momento.

&nbsp;

Vamos criar um novo arquivo para a nossa segunda receita.

```bash
touch receitas/farofa-vegana.md
```

&nbsp;

Agora vamos adicionar o conteúdo do nosso arquivo **farofa-vegana.md**.

```markdown
# Farofa Vegana

&nbsp;
## Para quantas pessoas?

- 4 pessoas

&nbsp;
## Ingredientes
- 1 cebola picada
- 2 bananas picadas
- 4 colheres de azeite ou óleo de sua preferência
- Sal a gosto 
- Pimenta do reino a gosto
- Salsinha a gosto
- Paprica a gosto
- 3 xícaras de farinha de mandioca
- 4 dentes de alho picados

&nbsp;
## Modo de Preparo

Primeiro aqueça uma panela e adicione o azeite ou óleo, na sequência adicione a cebola e deixe refogar por alguns minutos em fogo baixo, em seguida adicione o alho e deixe refogar até o alho ficar mais dourado, mas cuidado para não queimar nada.

Agora já podemos adicionar a banana, o sal, a pimenta, a salsinha e a paprica, misture bem mas sempre com muito cuidado para não desmanchar ou quebrar muito as bananas. Quando a banana começar a ficar mais mole, é a hora de adicionar a farinha de mandioca, misture bem e deixe cozinhar por alguns minutos, sempre mexendo para não grudar no fundo da panela.

A farinha de mandioca vai ficar bem sequinha, mas não pode queimar, pois senão irá mudar o sabor da farofa.

Após alguns minutos, com a farinha de mandioca mais sequinha e com a cor bem dourada, é hora de desligar o fogo e servir.

&nbsp;

## Dicas

- Se você quiser, pode adicionar um pouco de molho de tomate na farofa e um pouco de tofu defumado, sua farofa ficará ainda mais saborosa.
```

&nbsp;

Pronto, já temos o conteúdo da nossa segunda receita, já podemos atualizar o nosso repo. Lembrando que estamos modificando somente a branch segunda-receita, a branch main continua intacta.

```bash
git add .
git commit -m "Adicionando a receita de farofa vegana"
git push origin segunda-receita
```

&nbsp;

Agora a nossa segunda receita já está no nosso repositório remoto, mas ainda não está na branch main.

&nbsp;

Se você for no seu repositório remoto, vai ver que a branch segunda-receita foi criada e que ela tem um commit a mais que a branch main.

[Branches](images/branches.png)


&nbsp;

Para que você possa verificar todas as branches do seu repositório, você pode utilizar o comando:

```bash
git branch -a
```

&nbsp;

A saida do comando será algo parecido com isso:

```bash
  main
* segunda-receita
  remotes/origin/main
  remotes/origin/segunda-receita

```

&nbsp;

Onde:

- **main**: é a branch principal do seu repositório
  
- **segunda-receita**: é a branch que criamos para trabalhar na nossa segunda receita

- **remotes/origin/main**: é a branch principal do seu repositório remoto

- **remotes/origin/segunda-receita**: é a branch que criamos para trabalhar na nossa segunda receita no repositório remoto

E como você pode ver, a branch segunda-receita está com um asterisco na frente, isso significa que estamos trabalhando nela.

Simples, não?

&nbsp;

Vamos atualizar o nosso README.md para adicionar a nossa segunda receita.

```markdown
# DevChef

## Sobre o Projeto

Livro criado por pessoas que estavam aprendendo a ferramenta de versionamento de códigos Git com o Jeferson na LINUXtips.

&nbsp;
## Livro de Receitas Veganas

O Livro foi iniciado com cinco receitas adicionadas e testadas pelo Jeferson, as demais foram adicionadas pela comunidade de pessoas que estavam focadas em aprender Git e ter um almoço vegano!

&nbsp;
## Receitas

&nbsp;
#### Conteúdo 

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

Vamos imaginar que o time que está desenvolvendo esse livro de receitas, decidiu que a segunda receita está pronta para ser adicionada ao livro, portanto, podemos fazer o merge da branch segunda-receita para a branch main.

Mas o que é um merge?

O merge é a união de duas branches, onde você está unindo o conteúdo da branch A para a branch B. No nosso caso, estamos unindo a branch segunda-receita para a branch main.

Durante o merge você está pedindo para o Git, que ele faça a união das duas branches, mas o Git não vai fazer isso de qualquer forma, ele vai verificar se existe algum conflito entre as duas branches, se existir, ele vai te avisar e você terá que resolver o conflito manualmente.

Nós ainda vamos falar sobre conflitos, mas por enquanto, vamos fazer o merge da branch segunda-receita para a branch main.

Lembrando que o que queremos é adicionar todo o conteúdo novo que criamos na branch segunda-receita para a branch main.

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

O comando acima pediu para o Git pegar o conteúdo da branch segunda-receita e adicionar para a branch main, uni-las, atualizando a nossa branch main.

A saida do comando será algo parecido com isso:

```bash
Updating 7def92f..9eb025b
Fast-forward
 README.md | 1 +
 1 file changed, 1 insertion(+)
```

&nbsp;

Se tivesse algum conflito para resolver, seria nesse momento que o Git iria reclamar e pedir para você resolver o conflito.

Lembrando que sempre você poderá utilizar o comando git log para verificar o histórico de commits do seu repositório.

O próximo passo é atualizar o nosso repositório remoto.

```bash
git push origin main
```

&nbsp;

Pronto! Agora a nossa branch main está com o conteúdo da branch segunda-receita.

[Branch main](images/branch-main.png)

&nbsp;

### Deletando a branch segunda-receita

Agora não precisamos continuar com a branch segunda-receita, pois já fizemos o merge dela para a branch main, portanto, podemos deletar a branch segunda-receita.

```bash
git branch -d segunda-receita
```

&nbsp;

A saida do comando será algo parecido com isso:

```bash
Deleted branch segunda-receita (was 9eb025b).
```

&nbsp;

Vamos verificar se a branch segunda-receita foi realmente deletada.

```bash
git branch
```

&nbsp;

A saida do comando será algo parecido com isso:

```bash
* main
```

&nbsp;

Se você usar o comando git branch -a, você vai ver que a branch segunda-receita não existe mais no repositório local, mas ela ainda existe no repositório remoto.

```bash
* main
  remotes/origin/main
  remotes/origin/segunda-receita
```

&nbsp;

Vamos atualizar o nosso repositório remoto.

```bash
git push origin --delete segunda-receita
```

&nbsp;

A saida do comando será algo parecido com isso:

```bash
To github.com:badtuxx/DevChef.git
 - [deleted]         segunda-receita

```

&nbsp;

Vamos listar as branches do nosso repositório local e remoto novamente.

```bash
git branch -a
```

&nbsp;

A saida do comando será algo parecido com isso:


```bash
* main
  remotes/origin/main
```

&nbsp;

Já era! A branch segunda-receita foi deletada do nosso repositório local e remoto.

&nbsp;

Nós poderiamos ter feito esse processo de merge e de delete da nossa branch diretamente na interface do GitHub, mas como estamos aprendendo, vamos fazer tudo pelo terminal. O foco aqui é o Git e não o GitHub. :D

&nbsp;

### Conflitos

WIP



