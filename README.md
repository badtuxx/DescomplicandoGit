# Descomplicando o GIT

&nbsp;
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