# Descomplicando o GIT

*******
- [Descomplicando o GIT](#descomplicando-o-git)
  - [A proposta do material](#a-proposta-do-material)
  - [O Livro: DevChef](#o-livro-devchef)
  - [Sobre o material Descomplicando o Git](#sobre-o-material-descomplicando-o-git)
  - [Vamos começar!](#vamos-começar)
    - [Git?](#git)
    - [Criando o repo do nosso livro](#criando-o-repo-do-nosso-livro)

*******
<div id='proposta-do-material'/>  
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

## O Livro: DevChef
<div id='livro-devchef'/> 
&nbsp;

Precisamos ter um nome para o nosso livro, eu vou deixar como DevChef por enquanto, mas é claro, se alguém tiver uma ideia melhor é só falar, abre uma issue aqui no Github com a sugestão!

O endereço do repositório do nosso livro de receitas é o:

🔗 [github.com/badtuxx/DevChef](https://github.com/badtuxx/DevChef)

Muito bem, dito isso acho que já podemos começar!

Lembre-se, o nosso livro será vegano! Mesmo que você não seja, vamos fazer esse esforço para que possamos celebrar juntos todo esse aprendizado!

&nbsp;
## Sobre o material Descomplicando o Git
<div id='descomplicando-git'/>  

Vamos criar o nosso livro de receitas, mas o objetivo principal é aprender sobre o Git. E aqui não queremos aprender o Git decoreba, queremos aprender o Git que é usado no dia a dia! 

Eu tenho mais de 12 anos de experiência trabalhando com Git em ambientes grandes e complexos, com times que de centenas de pessoas compartilhando o mesmo repositório Git, e essa experiência acumulado que quero trazer aqui para vocês!

Esse material é a base do Workshow Descomplicando o Git que criei para a LINUXtips!
Se você está afim de aprender muito sobre o Git em formato de vídeo, colá lá no site da LINUXtips!

Iremos ainda criar um e-book com esse conteúdo, então se você está lendo esse conteúdo em um PDF bonitinho e bem formatadinho, parabéns e muito obrigado por ter adquirido a cópia do e-book!

E claro, temos o repositório desse material lá no Github no seguinte endereço:

🔗 [github.com/badtuxx/DescomplicandoGit](https://github.com/badtuxx/DescomplicandoGit)

O material está sobre a licensa GPL-3, então fique a vontade em aprender de forma totalmente gratuita, e ainda, ajudar adicionando ainda mais conteúdo nesse sensacional repositório, combinado?

E claro, caso queira utilizar esse material para ensinar outras pessoas, fique a vontade! Evidente, respeitando o que diz a licensa do código!

As pessoas que mais contribuirem para esse repo serão consideradas pessoas mantenedoras e com isso terá acesso ao e-book e também ao workshop. E claro, o nome nos agradecimentos do e-book! 

Teremos 3 vagas para pessoas mantenedoras!

Se você ainda está vendo esse texto, significa que ainda não temos essas pessoas escolhidas, então aqui está uma boa oportunidade!

Como base para esse material nós vamos utilizar a documentação oficial do projeto, que você pode acessar através dessa url:


🔗 [https://git-scm.com/docs](https://git-scm.com/docs)

Ahhh, e parabéns demais para a galera envolvida na construção dessa doc, e mais do que isso, parabéns para a galera empenhada em fazer a tradução desse material para o Português! Boa parte da documentação está em Português e com uma qualidade excelente!

&nbsp;

## Vamos começar!

### Git?

<div id='git'/>  

A primeira coisa que temos que ter em mente, que o **Git** nada mais é do que um sistema de versionamento de código (DVCS), o git auxilia no compartilhamento de código, muito utilizado em empresas ou cenários opensource.

Eu poderia ficar aqui falando que o Git é um VCS como nós tinhamos o Subversion e outras velharias, mas com todo o respeito, a maioria das pessoas que trabalham hoje com código versionado e compartilhado, não tem nem a menor ideia do que um VCS, elas apenas sabem que quando você precisa versionar e ter um gerenciamento descente de código, você utiliza o Git.

Ela foi criada em 2005 por Linus Torvalds, o criador do Linux. Ele criou o Git pois estava insatisfeito com os versionadores de código da época, queria algo mais robusto, e que poderia atender da melhor forma possível.

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

Outra coisa, você viu que a o final do nome do arquivo é terminado com **.md**, isso indica que estamos querendo criar um arquivo utilizando a linguigem de marcação Markdown, que você pode ver mais detalhes [aqui](https://pt.wikipedia.org/wiki/Markdown).

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
