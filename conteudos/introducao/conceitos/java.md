# Introdução Java

Tópicos abordados:

- [Instalação do Java](##Instalação-do-Java)
- [Modo de Execução](##Modo-de-Execução)
- [Convenções de Código](##Convenções-de-Código)

## Instalação do Java

Para desenvolver utilizando o Java é necessário baixar os pacotes necessários para compilação e execução do mesmo, ou seja, o JDK e o JRE.

Links de tutoriais de instalação:

- [Windows e Mac OS](https://www.externcode.com/install-java/)

- [Ubuntu](https://www.digitalocean.com/community/tutorials/how-to-install-java-with-apt-on-ubuntu-18-04)

## Modo de Execução

Para se executar um arquivo em java é necessário a compilação de mesmo, ou seja, transformar o codigo escrito em uma linguagem de maquina para que a Java Virtual Machine (JVM) consiga entender o arquivo compilado do java (ByteCode) e depois a executar o gerado.

### Instruções

Execução de um arquivo em um cenário onde temos um arquivo chamado [HelloWorld.java](../../../exemplos/introducao/conceitos/HelloWorld.java) com o intuito de mostrar os seus passos para execução.

Passos para execução:

1. Copie o código do arquivo linkado acima e crie ele em alguma área do seu computador com o mesmo nome.

2. Abra o prompt de comando ou o terminal na pasta onde você criou o arquivo.

3. Compile ele com o seguinte comando:

        javac HelloWorld.java

    Com isso será gerado um arquivo chamado HelloWorld.class, esse arquivo é composto de códigos na linguagem maquina, para que se possa executar no seu sistema operacional.

    OBS: O arquivo .class não pode ser executado em dois sistemas operacionais diferentes, sendo necessário a compilação do arquivo .java sempre que for executar em um ambiente diferente.

4. Execute o arquivo gerado:

        java HelloWorld

    Ao executar esse comando a mensagem `Hello World!` aparecerar no console, mostrando que o comando contido no arquivo.

## Convenções de Código

Padrões estabelecidos por um grupo de pessoas responsável por determinar a forma recomendada para desenvolver na linguagem de programação utilizada.

### Nomes

O Java nomenclaturas recomendadas para nomes de classe, métodos e variáveis. O padrão utilizado nos nomes é o CamelCase como mostrada no exemplo a seguir:

- Classes: Em nomes de classe é recomendado começar com a primeira letra maiúscula e o resto da palavra em minúsculo, e se a classe for uma junção de duas palavras, seguir o padrão da primeira letra maiúscula.

    Exemplos:

        - Usuario
        - UsuarioAssociado

- Método: Em nomes de métodos é recomendado deixar a palavra toda em minúscula e se for duas palavras uma seguida de outra recomenda-se deixar a primeira letra da segunda palavra em maiúsculo.

    Exemplo:

        - comprar
        - acharUsuario

- Variável: Em nomes de variáveis é recomendado utilizar o mesmo formato de nomeação de um método.

    Exemplo:

        - nome
        - nomeDoResponsavel