<h1>
    <a href="https://www.oracle.com/java/">
     <img align="center" width="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/java/java-original.svg"></a>
    <span>Java</span>
</h1>

## O que é o Java?

O Java, como plataforma de programação, nasceu no ano de 1995 dentro dos laboratórios da empresa Sun Microsystem como resultado de uma extensa pesquisa científica e tecnológica. A plataforma Java entrega um ambiente completo para o desenvolvimento e execução de programas, sendo composta por:

- Uma **linguagem de programação de alto nível orientada a objetos**;
- **Java Virtual Machine (JVM)**, garante independência de plataforma, pois o código executa na máquina virtual e essa pode ser portada para outras plataformas como Windows ou Linux;
- **Java Runtime Environment (JRE)**, agrega a máquina virtual e alguns recursos para a execução de aplicações Java;
- **Java Development Kit (JDK)**, é um conjunto de utilitários que oferece suporte ao desenvolvimento de aplicações.

No Java, os programas são escritos em um arquivo com a extensão `.java`, que em um processo posterior serão compilados para arquivos com a extensão `.class`. Esses, por sua vez, contêm os códigos a serem executados na máquina virtual, os `bytecodes`.

![](https://www.alura.com.br/artigos/assets/java/java-compilacao-class-bytecodes.jpg)

A **JVM** está disponível para a maioria dos sistemas operacionais do mercado, sendo assim conseguimos rodar a mesma aplicação Java no Windows, macOS, Linux, Solaris, entre outros. Essa funcionalidade implementa um dos conceitos que nasceram forte com o Java:

> **"Escreva uma vez e execute em qualquer lugar!"**

## Um pouco de História

No longínquo ano de 1991, iniciou-se o desenvolvimento do que viria a se tornar a plataforma Java como uma parte do programa Green, que agrupava projetos que tinham como objetivo estabelecer a **nova geração de softwares inteligentes** para dispositivos eletrônicos, como televisores, videocassetes, torradeiras e demais utensílios, para que esses pudessem se comunicar com outros do mesmo tipo e também com computadores.

Para alcançar esse objetivo, foi decidida a criação de uma plataforma que fosse **portável** entre **diferentes tipos de equipamentos**. A linguagem a ser adotada foi o C + + devido a experiência dos desenvolvedores do projeto, porém, observou-se que essa linguagem não permitia realizar de maneira fácil tudo o que eles esperavam.

Neste momento, um dos líderes do projeto, James Gosling, propôs **criar uma nova linguagem** que pudesse atender aos requisitos esperados para o projeto e que fosse o mais simples possível. Assim, surge a linguagem Oak (em tradução livre, “Carvalho”), por ser um tipo de árvore que nascia nos arredores do escritório de Gosling. Junto à nova linguagem foi desenvolvido o sistema `Green OS`.

Nos idos de 1993, a equipe da Sun Microsystem finalizou um **protótipo** de dispositivo que ficou conhecido como Star 7, ou simplesmente 7, um PDA (Personal Digital Assistant) que utilizava a nova linguagem. Então, surge a oportunidade de participação de uma concorrência pública para a criação de tecnologia interativa que fosse compatível para TV a cabo, que foi vencida pela Silicon Graphics.

OK, mas e o Java? Por problemas com copyright, no ano de 1994, foi necessário **trocar o nome** de Oak para o seu nome definitivo: Java. Impulsionados pelo crescimento da internet, os desenvolvedores Patrick Naughton e Jonathan Payne criaram o WebRunner, um programa para o navegador com a capacidade de download e execução de código Java.

Em 1995, no evento conhecido como SunWorl’95, a Sun apresenta ao mundo o navegador HotJava e a linguagem Java, que empolgou a comunidade de tecnologia da época. No ano seguinte, a gigante NetScape Corp lança a versão 2 do seu famoso navegador, o Navigator, que incorpora a funcionalidade de executar aplicações Java conhecidas como applets.

Com a chegada do ano de 1996, a Sun, em uma ação até então inédita, liberou de forma gratuita para a comunidade de software um conjunto de **ferramentas para desenvolvimento** usando a **linguagem Java**. Esse conjunto foi o conhecido `JDK 1.02`, que tinha como foco a plataforma Sun Solaris e o Windows 95/NT.

Um detalhe importante: a Sun liberou o Java e as ferramentas, mas continuou detentora dos direitos até 2009, quando a empresa foi comprada pela Oracle que continuou com a evolução da linguagem e da plataforma. Mas a aquisição da Sun não gerou impacto para os desenvolvedores Java, pois a linguagem continua gratuita e opera sob a licença GNU.

Abaixo você pode conferir uma **linha do tempo** com as **versões** e as **novidades implementadas** no Java no decorrer dos anos desde o seu lançamento:

![](https://www.alura.com.br/artigos/assets/java/historia-java.jpg)

Vale a pena destacar também que o Java, em sua **evolução**, parou de nomear as versões a partir do **Java 8**, e seu **versionamento atualizado é liberado de 6 em 6 meses**, adotando as formas Preview e LTS (Long Time Support).

## Tecnologia Java

A plataforma Java é estruturada em um portfólio de produtos para desenvolvimento e execução de aplicações, idealizando que um mesmo **programa** possa **funcionar em diferentes sistemas operacionais e dispositivos**. Atualmente a plataforma está dividida em duas grandes áreas:

- **Java Standard Edition (JavaSE)**
- **Java Enterprise Edition (JavaEE)**

### Java Standard Edition (JavaSE)

Componente padrão do Java que fornece um **ambiente** para o **desenvolvimento de aplicações** de **pequeno e médio porte**, além de um conjunto de APIs base da plataforma e a JVM padrão.

### Java Enterprise Edition (JavaEE)

Componente baseado no `JavaSE`, é **focado** no **desenvolvimento de aplicações empresariais multicamadas** de **grande porte** e provê serviços adicionais, ferramentas e APIs para simplificar a criação de aplicações complexas.

## O Java é gratuito?

Desde o seu lançamento oficial em 1996 até as suas mais recentes versões, o Java sofreu **evoluções** e **melhorias** que o permitiram se manter como uma plataforma e linguagem competitiva, o que explica sua grande popularidade.

Mas uma dúvida muito comum, principalmente para quem está iniciando, é a seguinte: o Java é gratuito? Uma pergunta pertinente, uma vez que a gigante de tecnologia Oracle comprou a Sun e a plataforma Java.

A resposta para essa pergunta encontramos no site da Oracle. **O Java é gratuito para estudo e testes**, porém, para **uso comercial e suporte** você deverá desembolsar um **valor para licenciamentos**. Mas, e agora?

### Kit de Ferramentas Java: OpenJDK

Hoje existe também uma versão totalmente gratuita do Java e de suas ferramentas que é mantida pela comunidade, contando também com o apoio da Oracle. Trata-se do OpenJDK, que é o **kit de ferramentas** para o desenvolvimento Java. Ele existe desde 2006, porém, desde a compra do Java pela Oracle, o kit passou a ganhar ainda mais força.

### Qual a diferença entre o Java Oracle e o OpenJDK?

Mas, então, existe diferença? O Java Oracle é desenvolvido com base no código oficial do projeto Open e permite uso completo e comercial, sendo **diferenciado pelo suporte e a forma de licenciamento**, mas tecnicamente ambas as versões são o mesmo Java.

## A Plataforma Java

Devido ao sucesso da linguagem Java e de sua máquina virtual, com alta adesão do mercado de desenvolvimento, outras linguagens passaram a buscar incorporar as características que deram tanta popularidade à linguagem, em principal, as que eram proporcionadas pela JVM.

Então, pensando que a JVM é uma especificação, pessoas responsáveis pelo desenvolvimento de linguagens de programação passaram a desenvolver implementações da JVM para suas linguagens. Assim surgiram algumas linguagens como o Jruby, implementação do Ruby para a JVM, e o Jython, baseada no Python!

Além disso, começaram a surgir linguagens escritas para a JVM visando explorar as mesmas características, similar ao que aconteceu com o Java no início. É o caso das linguagens Kotlin, Clojure, Scala, Groovy, entre outras. Essas linguagens cobrem, de suas maneiras, diversas áreas do desenvolvimento, como desenvolvimento Web, Mobile, Ciência de Dados e desenvolvimento desktop.

Para conseguir rodar na JVM, todas essas linguagens possuem uma característica em comum: **todas elas compilam para bytecode**! Na prática, isso significa que ao serem compiladas elas podem ser interpretadas pela máquina virtual, que cumpre seu papel de traduzir as instruções para a máquina nativa.

Hoje em dia, por conta dessa imensidão de linguagens suportadas pela JVM, o Java deixou de ser apenas uma linguagem de programação. Assim, podemos dizer que existe a **Plataforma Java**, que abrange todo o ecossistema de linguagens e implementações da JVM no desenvolvimento de aplicações.

### Como utilizar a Plataforma Java

O Java como **plataforma de computação** é muito utilizado, pois existe um grande número de aplicações para computador, sites e aplicativos que dependem do Java para funcionar. Por isso, é muito comum a pergunta: “Eu preciso do Java no meu computador?”.

Para executar as **aplicações Java** no nosso computador é necessária a **instalação** do **ambiente de execução do Java** ou **JRE**. Ela é uma camada de aplicação e é instalada no sistema operacional, **fornecendo a biblioteca de classes** e os **recursos necessários** para a execução do código Java pela JVM.

Como exemplo de aplicações que precisam do Java para funcionar, temos o aplicativo do Imposto de Renda de Pessoa Física (IRPF), utilizado pelo Ministério da Fazenda do Brasil. Aliás, muitos aplicativos oficiais do governo brasileiro foram desenvolvidos com o Java, como os utilizados para a Declaração do Imposto de Renda Retido na Fonte (DIRF) e a Relação Anual de Informações Sociais (GDRAIS).

Para configurar o Java em seu computador, executar aplicativos e componentes criados em Java, você pode baixar a JRE na [página oficial da plataforma](https://www.java.com/en/download/manual.jsp) e efetuar a instalação para o sistema operacional de sua escolha.

## A Linguagem Java

O Java, como **linguagem de programação**, possui algumas características que o destacam das demais linguagens e lhe conferem a **popularidade** que tem hoje. Vamos elencar abaixo as principais:

### Independência de plataforma

Os programas escritos em Java não são compilados para uma plataforma específica como Windows, Linux ou Mac; eles são transformados para uma **linguagem intermediária**, chamada de `bytecodes`, que é interpretada para uma **máquina virtual**, e essa sim possui uma versão para os principais sistemas operacionais de mercado.

### Orientação a Objetos

O Java é uma linguagem orientada a objetos, que é uma forma de programar que possibilita trabalharmos **abstração**, **encapsulamento de código** e **herança**, o que lhe confere também uma **curva de aprendizagem** bem **suave**.

### Não usa ponteiros

Diferentemente de algumas linguagens de programação, o Java torna transparente o **uso** de **ponteiros**, pois **não** permite o **acesso direto à memória do computador** e o programador não precisa se preocupar em gerenciar os objetos na memória. A plataforma Java traz o coletor de lixo, que se encarrega de **limpar a memória** de objetos não referenciados.

### Multithread

A plataforma permite a **execução concorrente** de várias rotinas de uma aplicação, o que possibilita a construção de aplicações Java **robustas** e **modernas**.

### Performance

Desde o início, o Java foi pensado com foco em ser **compacto**, independente de plataforma e para funcionar em rede. Na utilização da **JVM**, durante a evolução da plataforma, foi incorporado o **JIT (Just In Time)**, que converte os `bytecodes` em código nativo, o que trouxe ainda mais **performance** em sua **utilização**.

### Segurança

Pensando na implementação de **aplicações em redes**, o Java entrega uma boa solução para **segurança** das aplicações nele desenvolvidas. Há possibilidade de se especificar o nível de segurança ou determinar que aplicativos como applets sejam seguros ou não.

Além dessas características, a linguagem Java é bastante robusta e permite o trabalho com **tipos numéricos**, como inteiro ou ponto flutuante, de acordo com padrões internacionais, além de implementar e incentivar o controle de erros pela aplicação. A **Sintaxe** da linguagem também é bem simples, o que explica em parte como ela se tornou uma das linguagens orientadas a objetos mais populares do mundo.

## JVM: Conhecendo o processo de execução de código

### Como um programa é executado?

Desde os mainframes até os dias atuais muita coisa mudou no processo de desenvolvimento, ainda que olhemos apenas para código. Na década de 1950, o compilador era uma pessoa de verdade. Isso mesmo! Uma pessoa recebia o código escrito em papel e compilava manualmente. Com o tempo, a tecnologia foi evoluindo e eventualmente foi criado o primeiro compilador como conhecemos hoje em dia.

Apesar da evolução dos compiladores, uma característica se manteve: o processo da escrita à execução do programa!

![](https://www.alura.com.br/artigos/assets/jvm-conhecendo-processo-execucao-de-codigo/imagem1.jpg)

O **compilador** é responsável por receber o código-fonte, que é escrito por uma pessoa desenvolvedora, e traduzi-lo em código binário, gerando um arquivo executável, que é a aplicação.

Neste modelo, o compilador está intimamente ligado ao sistema operacional, pois ele precisa gerar um código binário compatível com o sistema, que é o que faz a comunicação com o processador.

Para executar o mesmo programa em diferentes sistemas, devido a essa característica, era necessário passar o código-fonte por um outro compilador específico de outro sistema operacional. E ainda assim não era garantido o funcionamento da aplicação, pois muitas bibliotecas utilizadas para o desenvolvimento do programa eram específicas de um sistema operacional e não tinham funcionalidade garantida em outros.

![](https://www.alura.com.br/artigos/assets/jvm-conhecendo-processo-execucao-de-codigo/imagem2.jpg)

Então, para ter um programa com exatamente o mesmo comportamento em diferentes sistemas operacionais, era necessário adaptar o código para as bibliotecas específicas do sistema, alterar o gerenciamento de memória e passar por um compilador compatível.

Esse modelo, apesar de funcional, dificulta a vida das pessoas que desenvolvem pela necessidade de usar muito mais tempo na adaptação de código-fonte para inúmeras plataformas. Além disso, pode até ser prejudicial ao usuário, que pode ter aplicações indisponíveis em sua plataforma de preferência.

De frente com esse problema, pessoas desenvolvedoras começaram a buscar maneiras de tornar esse processo simplificado e excluir a necessidade da reescrita e recompilação de um mesmo código baseado no sistema operacional alvo. Para isso, um grupo de cientistas da computação liderado por Alan Kay (um dos inventores do Smalltalk) idealizou a criação de uma plataforma intermediária, que ficaria encarregada pela comunicação com diferentes sistemas a partir de um mesmo código-fonte.

![](https://www.alura.com.br/artigos/assets/jvm-conhecendo-processo-execucao-de-codigo/imagem3.jpg)

Neste novo modelo, o código-fonte escrito por uma pessoa desenvolvedora passa por um compilador, como já acontecia, mas ao invés de gerar um programa executável, é gerado um código intermediário chamado **bytecode**, que contém instruções para uma máquina virtual encarregada de traduzir as instruções para diversos sistemas operacionais a partir de um mesmo código-fonte.

A criação de uma máquina virtual responsável pela comunicação com o sistema operacional possibilitou a portabilidade de código entre diferentes sistemas, uma vez que essa nova camada adicionada ao processo ficou responsável por gerenciar as dificuldades do modelo tradicional.

### A Java Virtual Machine

Apesar do sucesso em garantir a portabilidade de código, o Smalltalk não tinha muita adesão dentro do desenvolvimento voltado ao grande mercado, pois se tratava de uma linguagem voltada à educação.

Pensando nos problemas do processo tradicional de desenvolvimento, um grupo de cientistas da computação da então Sun Microsystems, que visava desenvolver aplicações distribuídas entre plataformas (sistemas embarcados e diferentes sistemas operacionais), mas não queriam passar pelas dificuldades de reescrita e readaptação de código para cada uma delas, desenvolveu uma **especificação de máquina virtual**, isto é, um padrão para a implementação de máquinas virtuais que executam código e que, como o Smalltalk, possibilita a portabilidade de código. Essa especificação foi lançada inicialmente para dar suporte à linguagem Java, e por esse motivo recebeu o nome **Java Virtual Machine**, ou **Máquina Virtual Java**.

A criação dessa especificação possibilitou que o desenvolvimento para múltiplos sistemas fosse facilitado e acessível para empresas de desenvolvimento do mercado, trazendo a facilidade de a partir de um único código-fonte ser possível executar um mesmo programa em diferentes plataformas. Essa característica originou até o Slogan da linguagem: **Write Once, Run Anywhere (“Escreva uma vez, execute em qualquer lugar”)**, que popularizou bastante o Java!

Para isso, a JVM adotou uma estrutura de execução muito parecida com a proposta anteriormente adotada pelo Smalltalk:

![](https://www.alura.com.br/artigos/assets/jvm-conhecendo-processo-execucao-de-codigo/imagem4.jpg)

O código-fonte é enviado a um compilador, o **javac**, que o transforma em bytecode (um arquivo com a extensão `.class`) para ser interpretado pela Java Virtual Machine, encarregada do gerenciamento de memória e recursos, a fim de executar o programa de maneira que ele seja compreendido pelo sistema operacional em que está rodando.

## Instalando no Windows

**JDK (Java Development Kit)** é um conjunto de ferramentas e bibliotecas de software que permite o desenvolvimento de aplicativos Java.

**01.** Para instalar no Windows, acessar o site da **[Oracle](https://www.oracle.com/java/technologies/downloads/#jdk21-windows)** 
ou buscar no navegador por **“Java Download Oracle”** e acessar o primeiro link.

**02.** Escolher a versão do Java. 
- Escolher a verssão **LTS**, por ser a versão de suporte de longo prazo mais recente para a plataforma Java SE.

![img.png](img/img.png)

**03.** Selecionar o Windows como sistema operacional e fazer o download.

![img_1.png](img/img_1.png)

**04.** Após baixado, executar o instalador e prosseguir com a instalação.

![img_2.png](img/img_2.png)

![img_3.png](img/img_3.png)

![img_4.png](img/img_4.png)

**05.** Após a instalação, vamos testar o nosso Java. Para isso, utilizar o **Prompt de Comando**. Testar os seguintes comandos 
e verificar se tudo correu como o esperado:
```bash
$ java -version

$ javac -version
```

Resultado:

![img_5.png](img/img_5.png)

## Configurações do PATH no Windows

**01.** Ir em **Painel de Controle** e procurar por **“Sistema”**, após isso, clicar em **“Configurações avançadas do sistema”**.

![img_6.png](img/img_6.png)

**02.** Na aba **"Avançado"**, clicar em **“Variáveis de Ambiente”**.

![img_7.png](img/img_7.png)

**03.** Agora foi aberta uma nova janela na parte inferior da tela, selecionar a variável de ambiente chamada **“Path”** e 
clicar em **“Editar”**.

![img_8.png](img/img_8.png)

**04.** Nessa nova janela, clicar no botão **“Novo”** e na linha que foi selecionada, colocar o caminho para o diretório 
bin dentro da pasta jdk, que está dentro da pasta Java.

![img_9.png](img/img_9.png)

**05.** Após feito, fechar o **Prompt de Comando** e abrir novamente. Testar os seguintes comandos:
```bash
$ java -version

$ javac -version
```