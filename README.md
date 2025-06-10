# Jogo de Xadrez em Java

Este repositório contém um jogo de xadrez desenvolvido em Java, utilizando os princípios da Programação Orientada a Objetos (POO). O objetivo principal deste projeto é demonstrar a aplicação de conceitos de POO em um jogo de tabuleiro clássico.

## Como Rodar o Jogo

Para compilar e executar o jogo de xadrez no seu terminal, siga os passos abaixo:

### Pré-requisitos

Certifique-se de ter o Java Development Kit (JDK) instalado em sua máquina. Você pode verificar a instalação e a versão do Java executando os seguintes comandos no terminal:

```bash
java -version
javac -version
```

Se o Java não estiver instalado, você pode baixá-lo e instalá-lo a partir do site oficial da Oracle ou através de um gerenciador de pacotes, dependendo do seu sistema operacional.

### Compilação

1.  **Clone o repositório:**

    Primeiro, clone este repositório para o seu ambiente local usando o Git:

    ```bash
    git clone https://github.com/enzomorgan/chess-game.git
    ```

2.  **Navegue até o diretório do projeto:**

    Entre na pasta do projeto clonado:

    ```bash
    cd chess-game
    ```

3.  **Compile os arquivos Java:**

    Assumindo que o arquivo principal do jogo seja `Program.java` (ou o nome do arquivo que contém o método `main`), compile todos os arquivos `.java` no diretório `src`:

    ```bash
    javac src/*.java
    ```

    *Nota:* Se houver uma estrutura de pacotes, a compilação pode exigir o uso da opção `-d` para especificar o diretório de saída para os arquivos `.class` e a execução deve ser feita a partir do diretório raiz do projeto, especificando o nome completo da classe.

### Execução

Após a compilação bem-sucedida, você pode executar o jogo:

```bash
java -cp src Program
```

*Nota:* Substitua `Program` pelo nome da sua classe principal, se for diferente.

## Funcionalidades

-   Implementação das regras básicas do xadrez.
-   Movimentação de peças.
-   Verificação de xeque e xeque-mate.

## Tecnologias Utilizadas

-   Java
-   Programação Orientada a Objetos (POO)

## Contribuição

Contribuições são bem-vindas! Se você tiver sugestões de melhoria ou quiser adicionar novas funcionalidades, sinta-se à vontade para abrir uma *issue* ou enviar um *pull request*.
