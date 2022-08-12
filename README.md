<h1 align="center">
  <img src="assets/reprograma-fundos-claros.png" alt="logo reprograma" width="500">
</h1>

# Tema da Aula

Turma Online 18 - Todas em Tech  | Backend-end | Semana 1 | 2022 | Professora: Jéssica Osko

### Instruções
Antes de começar, vamos organizar nosso setup.
* Fork esse repositório 
* Clone o fork na sua máquina (Para isso basta abrir o seu terminal e digitar `git clone url-do-seu-repositorio-forkado`)
* Entre na pasta do seu repositório (Para isso basta abrir o seu terminal, lembre-se da pasta que você clonou o repositório. 
* Exemplo de comando para acessar a pasta: `cd nome-do-seu-repositorio-forkado`)

### Resumo
O que veremos na aula de hoje?
* [O que é Programação?](#o-que-e-programacao)
* [O que é Linguagem de Programação?](#tema1)
* [O que é Linha de comando?](#tema1)
* [Para que serve um sistema de Controle de Versão?](#tema1)
* [Vantagens](#tema2)
* [Git](#tema2)
* [Comandos Github](#tema2)
* [Comandos Git](#tema2)
___

## Conteúdo
### O que é Programação? 

Para que os computadores funcionem de forma útil para nós, precisamos dizer a eles o que fazer. Fazemos isso com a programação. No geral, programação é uma forma de instruir o computador a executar diversas tarefas ou um processo de criação de aplicações.

___

### O que é Linguagem de Programação? 

O computador lê e interpreta bits binários 1s (uns) e 0s (zeros). Imaginar se tudo que fazemos no computador tivesse que ser escrito apenas com bits 1s e 0s? Seria inviável! Por isso existem as linguagens de programação. Elas são o meio pelo qual as desenvolvedoras/es (chamadas também de programadoras/es) se comunicam com as máquinas. A função da linguagem de programação é entender a tarefa determinada por programadores e traduzir as instruções de forma que o computador consiga ler e executar. 

 O código, portanto, nada mais é do que a instrução (ou o comando) da tarefa que você deseja que o computador realize, em uma determinada linguagem. As linguagens de programação permitem escrever códigos de maneira mais próxima da linguagem escrita humana, ao invés de escrever cada comando com bits binários. Assim, permitiram um avanço sem tamanho para a programação, tornando o aprendizado e a prática da programação mais rápidos e acessíveis (sim, ainda dá para melhorar). Com isso, cada vez mais soluções para o nosso cotidiano são desenvolvidas por meio de códigos. 

___


### O que é Linha de comando?

A linha de comando é uma interface baseada em texto por meio da qual é possível navegar, criar, executar e atuar nos arquivos e diretórios de um computador com precisão, inclusive o versionamento do seu código. O git é sempre utilizado através da linha de comando.

___

### Para que serve um sistema de Controle de Versão? 

> Controle de versão é fundamental para o desenvolvimento de software.

O controle de versão é um método ou uma categoria de ferramentas de software que ajuda a acompanhar as alterações no código para que, se algo der errado, possamos fazer comparações em diferentes versões de código e possamos reverter facilmente para versões anteriores.

Usar o controle de versão permite uma maior flexibilidade e controle do que muitas outras soluções. Por exemplo, seria possível que duas pessoas trabalhassem em um arquivo ao mesmo tempo e depois os mesclassem. Se houvesse 'conflitos' entre as duas versões, o sistema de controle de versão permitiria que você visse esses conflitos e tomasse uma decisão ativa sobre como 'mesclar' essas diferentes versões em um novo 'terceiro' documento. Com essa abordagem, você também manteria um 'histórico' da versão anterior, caso desejasse voltar a uma delas mais tarde. 

 #### Vantagens
 
> Esses sistemas permitem que pessoas desenvolvedoras, designers, analistas de qualidade - entre outras profissões, trabalhem no mesmo projeto. Também conhecido como VCS (Version Control System), esses sistemas são essenciais para garantir que todos tenham acesso ao código mais recente. Conforme o desenvolvimento fica mais complexo, há uma necessidade maior de gerenciar várias versões de produtos inteiros.

* Acompanhar desenvolvimentos e mudanças em seus arquivos.
* Registar as alterações feitas em seu arquivo de uma forma que você possa entender mais tarde.
* Experimentar diferentes versões de um arquivo, mantendo a versão original.
* Mesclar duas versões de um arquivo e gerenciar conflitos entre as versões.
* Reverter as alterações, movendo 'para trás' através do seu histórico para versões anteriores do seu arquivo.

> Existem dois tipos de Controle de Versão, o centralizado e distribuído, focaremos no Controle de Versão Distribuído (DVCS).

###  Benefícios de trabalhar com sistemas distribuídos

* **Segurança:** Cada software de controle de versão de mecanismos para evitar possíveis corrupções em arquivos. Além disso, apenas pessoas autorizadas e identificadas podem mexer no código fonte controlado.

* **Versionamento:** Caso se deseje voltar a versão de um determinado arquivo por algum erro cometido ou simplesmente mudança de escopo, é possível fazê-lo de forma simples e estruturada, minimizando eventuais erros e efeitos colaterais.
Rastreabilidade: Quando se trata de algo importante, é sempre interessante saber “Quem”, “Quando”, “Como”, “Por que” e “Onde”. Todos esses metadados estão disponíveis nas ferramentas mais populares de controle de versão.

* **Organização:** Os sistemas que possuem interface visual disponibilizam uma visualização completa do ciclo de vida de cada arquivo controlado, desde sua criação até o momento atual.

* **Colaboração:** O trabalho em equipe, principalmente as distribuídas, é muito facilitado. Pessoas que talvez nem se conhecem pode colaborar num determinado projeto cujo repositório central é disponibilizado a todos os envolvidos.

* **Confiança:** O uso de repositórios remotos ajuda muito na recuperação de eventos imponderáveis. Situações do tipo “Perdemos o projeto inteiro que estava na máquina de fulano” são minimizadas. Além disso, é possível testar novas ideias sem danificar a linha base do desenvolvimento. 

[Fonte](https://blog.wkm.com.br/o-que-%C3%A9-e-porque-usar-um-sistema-de-controle-de-vers%C3%A3o-23f00b08e12d)

___

### Git

> A linha de comando é uma interface baseada em texto por meio da qual é possível navegar, criar, executar e atuar nos arquivos e diretórios de um computador com precisão, inclusive o versionamento do seu código. O git é sempre utilizado através da linha de comando.

[Git](https://git-scm.com/) é um sistema de controle de versão para rastrear alterações em arquivos e coordenar o trabalho nesses arquivos modificados entre várias pessoas. Ele é usado principalmente para gerenciamento de código-fonte no desenvolvimento de programas, mas pode ser usado para controlar as alterações em qualquer conjunto de arquivos. Git foi criado por Linus Torvalds em 2005 para o desenvolvimento do kernel Linux e é um software de código aberto e gratuito. 

Repositórios git públicos e privados gratuitos estão disponíveis em:

* [Bitbucket](https://bitbucket.org/product/)
* [GitHub](https://github.com/)
* [GitLab](https://about.gitlab.com/)

Você encontrará mais sobre todos os comandos [aqui](https://git-scm.com/docs). 

### Conceitos importantes do Git

* Ramificação

De maneira simplificada, os ramos (branches) no Git são semelhantes a um ramo de uma árvore, onde o tronco seria a base do código. Desse modo é possível criar diversos ramos e fazer alterações, enquanto a base permanece intacta. Por padrão o ramo principal é denominado de main (master, na versão antiga).

___

### Github
![N|Solid](https://miro.medium.com/max/1170/1*uA_z31oxsSAMS8dFzAohLQ.jpeg)

[GitHub](https://github.com/) é uma plataforma de hospedagem de código para controle de versão e colaboração.
Ele permite que você e outras pessoas trabalhem juntos em projetos de qualquer lugar.

O Github utiliza os comandos Git para fazer o controle de versão dos seus projetos.

_Para criar o seu repositório, siga as instruções da [documentação](https://docs.github.com/pt/github/getting-started-with-github/create-a-repo)._


### Ferramentas Gráficas

* [GitKraken](https://www.gitkraken.com/)
* [Sourcetree](https://www.sourcetreeapp.com/)

#### Conceitos importantes do Github:

* [Clone](https://docs.github.com/pt/repositories/creating-and-managing-repositories/cloning-a-repository)

Git clone é usado para criar uma cópia ou clone de repositórios remotos. 

* [Fork](https://docs.github.com/pt/pull-requests/collaborating-with-pull-requests/working-with-forks/about-forks)

Um fork é uma cópia de um repositório que você gerencia. Os forks permitem fazer alterações em um projeto sem afetar o repositório original. Você pode fazer fetch de atualizações no repositório ou enviar alterações ao repositório original com pull requests.


* [Pull Request](htps://docs.github.com/pt/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request)

O conceito de pull request é que antes de mesclar as alterações com o código ou repositório original, as pessoas colaboradoras podem revisar, fazer comentários e sugerir melhorias. 


___

### Git: Comandos iniciais

Manter conscistência, fazer:

```sh
$ git config --global user.name "Jéssica"
$ git config --global user.email "jessica@email.com"

```

Listar todas as configurações: 

```sh
$ git config --list
```

Criando um repositório local:

```sh
$ git init
```

Verifica arquivos modificados ou em diferentes condições da árvore de trabalho:

```sh
$ git status
```

Adicionar um arquivo:

```sh
$ git add arquivo.txt
```

Adicionar todos os arquivos que está na pasta - inserido três formas que são iguais:

```sh
$ git add  --all
$ git add  --A
$ git add  .
```

Salvar e rastrear uma alteração:

```sh
$ git commit -m "Frase curta explicando a modificação realizada"

```

Verificar diferenças entre arquivos:

```sh
$ git diff arquivo.txt

```

Verificar diferenças na área de "preparação":

```sh
$ git diff --cached arquivo.txt
$ git diff --staged arquivo.txt
```

Verificar históricos de alterações:

```sh
$ git log
$ git log --oneline
```

Desfazer alterações:

```sh
$ git checkout arquivo.txt
```

Ignorando arquivos:

O ```.gitignore``` informa ao git quais arquivos (ou padrões) ele deve ignorar. Geralmente é usado para evitar a confirmação de arquivos transitórios do diretório de trabalho que não são úteis para outros colaboradores, como produtos de compilação, arquivos temporários criados por IDEs etc.

```bash
    \--📂 projeto
    	   |  .gitignore
    	   |
    		\--📂src
    			    |   app.js
    			    |
    			
```


### Git: Comandos intermediários e avançados

Você encontrará mais sobre os comandos intermediários e avançados realizados em sala de aula [aqui](https://git-scm.com/docs).

Criando uma ramificação(Branch):

```sh
$ git branch novaBranch
```

Atualizar os arquivos na working tree para ficarem na versão especificada.

```sh
$ git checkout --help 
```

```sh
$ git checkout -b novaBranch
```

_Com o comando ```git branch novaBranch``` você não mudará para o ramo criado, com o ```git checkout -b novaBranch``` você mudará imediatamente._


Trazer atualizações do repositório remoto para o local:
```sh
$ git pull
```

Enviar modificações do repositório local para o remoto:
```sh
$ git push
```

Verificar em qual branch estou:
```sh
$ git branch
```

Mudar de ramo:
```sh
$ git checkout nomeBranch
```

Remover branch localmente:
```sh
$ git branch -d nomeBranch
```

Remover branch remotamente:
```sh
$ git push --delete origin nomeBranch
```

Renomear branch remotamente:
```sh
$ git reset
```

Cria um backup das modificações de seus arquivos.
```sh
$ git stash
```

Listar os seus backups: 
```sh
$ git stash list
```

Utilizar um commit específicos de outras branches.
```sh
$ git cherry-pick "hash do commit" 
```

Inserir uma mensagem no stash: 
```sh
$ git stash save "Mensagem"
```

Mostra as alterações que foram realizadas no repositório:  
```sh
$ git fetch 
```

Integra mudanças de um branch para outro:
```sh
$ git rebase 
```

Une dois ou mais históricos de desenvolvimento:

```sh
$ git merge 
```

Verificar os commits e ramificações:

```
$ git log --oneline --all --decorate --graph
```
___

### Boas práticas 

* Deusas, lembre-se que na main manteremos o código ou informações mais consolidadas. O ideal é criar inicialmente uma branch para depois unificar as informações. Ramifique, lembre-se disso. Uma das características da descentralização é a ramificação - branches. Enviar o código direto para main branch não promove a colaboração. O Git simplificou a comparação do código entre dois branches, o que pode gerar discussões saudáveis, melhorar a qualidade do codebase e espalhar o conhecimento entre as pessoas desenvolvedoras.

* Escreva mensagens de confirmação descritivas e resumidas. 

* Geralmente utilizamos prefixos tanto nas branches quanto nos commits.

- bugfix/
Utilizamos quando queremos corrigir uma parte do código que está impactando a aplicação e precisa ser ajustada o quanto antes.

- feature/
Geralmente, quando adicionamos uma nova funcionalidade, colocamos o nome de feature, podemos traduzir como funcionalidade, componentes. No contexto geral, é quando queremos dizer que vamos inserir algo novo. 

- hotfix
Às vezes esse termo pode ser usado de outras formas, até mesmo para usar no lugar do bugfix. Porém, eu prefiro separar, deixar com semânticas diferentes.
Ele é bem similar ao bugfix/, porém, ele não é um BUG, mas sim uma correção, seja ela de cor, textos, alterações não tão urgentes, que não signifiquem BUG's.

- improvement/
Quando vamos subir melhorias para uma implementação que existe, utilizamos esse prefixo.

* Conheça a ferramenta, leia a documentação. Não tenha medo de usá-la. 

[Fonte de alguns significados](https://www.brunodulcetti.com/padroes-e-nomenclaturas-no-git/#:~:text=Prefixos%20do%20commitizen,a%20documenta%C3%A7%C3%B5es%2C%20README%20e%20afins)

***
### Exercícios 
* Em breve
* Em breve


### Links Úteis
- [Nosso quadro de aprendizagem coletiva](https://easyretro.io/publicboard/KYZHJ77eVANTvSNeOQVsGkbGCwr2/ffef43e4-5235-44ef-bbb9-10c20a2692f2)
- [Sobre o Git](https://www.atlassian.com/br/git/tutorials/what-is-git)
- [Sobre Github](https://docs.github.com/pt/github/getting-started-with-github/quickstart)
- [Lorem Ipsum](https://www.lipsum.com/feed/html)

### Referências
- [Algumas dicas para quem quer aprender a programar](https://minasprogramam.com/dicas-para-aprender-a-programar/)


<p align="center">
Desenvolvido com :purple_heart:  
</p>

