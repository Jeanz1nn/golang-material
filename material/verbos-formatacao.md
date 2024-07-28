# Verbos de Formatação do Go

Os verbos de formatação no Go são utilizados com o pacote `fmt` para formatar diferentes tipos de dados em strings. Abaixo estão as explicações para cada verbo de formatação, organizados em principais e adicionais.

## Verbos de Formatação Principais

### Verbos de Formatação Básicos

- **`%v`**: Exibe o valor no formato padrão. É o verbo de formatação mais genérico.
- **`%+v`**: Exibe o valor com informações adicionais, como os nomes dos campos para structs.
- **`%#v`**: Exibe o valor em forma de sintaxe Go, útil para debugging e exibição de código.
- **`%T`**: Exibe o tipo do valor.
- **`%%`**: Exibe um caractere `%` literal.

### Verbos de Formatação para Números Inteiros

- **`%b`**: Exibe o número como um binário.
- **`%c`**: Exibe o número como o caractere correspondente na tabela Unicode.
- **`%d`**: Exibe o número como decimal.
- **`%o`**: Exibe o número como octal.
- **`%x`**: Exibe o número como hexadecimal, usando letras minúsculas.
- **`%X`**: Exibe o número como hexadecimal, usando letras maiúsculas.

### Verbos de Formatação para Números de Ponto Flutuante e Complexos

- **`%e`**: Exibe o número em notação científica com `e` minúsculo.
- **`%E`**: Exibe o número em notação científica com `E` maiúsculo.
- **`%f`**: Exibe o número em ponto flutuante, com uma quantidade fixa de casas decimais.
- **`%g`**: Exibe o número no formato mais compacto entre notação científica e ponto flutuante.
- **`%G`**: Exibe o número no formato mais compacto entre notação científica e ponto flutuante, usando `E` maiúsculo.

### Verbos de Formatação para Strings e Caracteres

- **`%s`**: Exibe a string como está.
- **`%q`**: Exibe a string entre aspas, escapando caracteres especiais.

## Verbos de Formatação Adicionais

### Verbos de Formatação para Números Inteiros Adicionais

- **`%U`**: Exibe o número como o caractere Unicode correspondente com a forma `U+XXXX`.

### Verbos de Formatação para Strings Adicionais

- **`%x`**: Exibe a string como uma sequência de bytes em hexadecimal, usando letras minúsculas.
- **`%X`**: Exibe a string como uma sequência de bytes em hexadecimal, usando letras maiúsculas.

### Verbos de Formatação para Tempo

- **`%v`**: Quando usado com `time.Time`, exibe o tempo no formato padrão.
- **`%t`**: Exibe booleanos (`true` ou `false`), mas geralmente não é usado com tempos.

### Verbos de Formatação Adicionais

- **`%p`**: Exibe o ponteiro para o valor.

Estes verbos de formatação permitem que você personalize como os valores são apresentados ao imprimir ou formatar strings no Go. Para mais detalhes, consulte a [documentação oficial do pacote fmt](https://pkg.go.dev/fmt).
