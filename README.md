# Especificação do Jogo da Forca no Simulador Cesar

Esta especificação descreve a implementação do jogo da forca no Simulador Cesar. O jogo funcionará da seguinte forma:

## Passo 1: Cadastro da Palavra

- Inicialmente, o usuário deverá cadastrar uma palavra para o jogo.
- O programa exibirá a seguinte mensagem no visor:

    ```
    CADASTRAR PALAVRA
    ```

## Passo 2: Salvando a Palavra

- Após pressionar "Enter", a palavra digitada pelo usuário deverá ser armazenada sem ser mostrada no visor.

## Passo 3: Número de Letras da Palavra

- Após salvar a palavra, o programa exibirá no visor o número de letras da palavra, representadas por asteriscos.
- Por exemplo, se a palavra cadastrada tiver 5 letras, o visor mostrará:

    ```
    *****
    ```

## Passo 4: Opções Disponíveis

- O programa exibirá as seguintes opções no visor:

    ```
    1 – DIGITAR LETRA
    2 – DIGITAR PALAVRA
    ```

## Passo 5: Digitar uma Letra

- Quando o usuário digitar a opção 1, o programa verificará se a letra digitada corresponde a alguma posição na palavra cadastrada.

## Passo 6: Substituição das Letras

- O programa substituirá os asteriscos pelas letras corretas nas posições corretas quando uma letra correta for digitada.

## Passo 7: Contagem de Erros

- O programa contabilizará o número de caracteres digitados que não estão presentes na palavra.
- Quando ocorrerem mais de 6 erros, o jogador perderá a jogada e o jogo reiniciará para o cadastro de uma nova palavra.

## Passo 8: Digitar a Palavra Completa

- Se o jogador desejar, poderá informar a palavra completa.
- Nesse caso, ele deverá escolher a opção 2 e todos os caracteres informados deverão coincidir em posição com os caracteres da palavra cadastrada.

## Passo 9: Fim do Jogo

- Quando todos os caracteres coincidirem (antes dos 6 erros), o programa exibirá a seguinte mensagem no visor:

    ```
    PARABÉNS!! VOCÊ ACERTOU!!
    ```

## Instruções de Teste

Para testar o código do jogo da forca no Simulador Cesar, siga as instruções abaixo:

1. Acesse o link do Simulador Cesar: [https://www.inf.ufrgs.br/arq/wiki/doku.php?id=cesar](https://www.inf.ufrgs.br/arq/wiki/doku.php?id=cesar)

2. Baixe e instale o simulador seguindo as instruções fornecidas no site.

3. Após instalar o simulador, abra o código-fonte do jogo da forca.

4. Compile e execute o programa no Simulador Cesar.

5. Siga as etapas descritas nesta especificação para interagir com o jogo da forca.

## Contribuições

Contribuições são bem-vindas! Se você encontrar algum problema, tiver sugestões ou desejar adicionar recursos adicionais, fique à vontade para abrir uma issue ou enviar um pull request.

## Licença

Este programa é distribuído sob a licença [MIT](LICENSE), o que significa que você pode fazer uso do código, modificar e distribuir conforme sua necessidade.
