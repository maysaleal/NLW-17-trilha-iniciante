## Linguagem de programação

Memoria de dar introdução aop computador
Como um lego, você irá utilizar peças para criar algoritmos, ou seja, para resolver problemas.

    **Algoritmo**: Sequencia de passos lógica e finita para resolução de um problema.

## Peças de uma linguagem

- Comentários
- Declaração de variáveis (const, let)
- Operadores (atribuição, concatenação, matemáticos, lógicos)
- Tipos de dados (string, number, boolean)
- Estrutura de dados (funcions, object, array)
- Controle de fluxo (if/else)
- Estrutura de repetição (for. while)

# Fases da resolução de um problema

Coletar os dados
Processar os dados (manipular, alterar...)
Apresentar os dados

## Escopos e variaveis

Variaveis globais e locais
Constantes

## Tipos de dados

Strings (textos): Podem ser escritas com "" '' `` tem comportamentos diferentes
number: 2, 1.4
Boolean: true, false

## Operadores

- Operadores de atribuição de valor
- Operador de concatenação: +
- Operadores de comparação: ==(igual) / != (diferente) / <= / >= / <>
- spread operator: ...

## Estruturas de dados

### Arrays:

- Uma lista que contem qualquer tipo de dado
- Métodos de array: push, [find, forEach, filter] : HCF (Highter Order Function)

### Objetos:

- Atributos e métodos
- Criação e manipulação de abjetos
- Acesso a propriedades de objetos

## Function

- Criar, passar argumento
- Executar
- Arrow function / named function

# Estrutura de repetição

- while

const start = () => {
    let count = 0
    while(count < 10){
        console.log(count)
        count = count + 1
    }
}
start()

# Condicionais

- switch -> Controle de fluxo da aplicação (condicionais)
const start = () => {

    while(true){
        let opcao = "cadastrar"
        switch(opcao){
            case "cadastrar":
                console.log("vamos cadastrar")
                break
            case "listar":
                console.log("vamos listar")
                break
            case "sair":
                return
        }
    }
}
start()

- if/else

## Módulos em Node.js:

- Importação de módulos (require, CommonJS)
- Biblioteca 'inquirer' para criar prompts interativos

## Proramação assíncrona e Promises:

- Uso de funções assíncronas (async/await)