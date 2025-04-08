# Paulista Language: A linguagem de programação inspirada nas gírias paulistas.

## Autores: Gabriel e Suellen

### Comentários

A sintaxe dos comentários em Paulista Language é semelhante as outras linguagens

```bash
// Comentário em linha

/* Isto é um comentário em bloco
    Legal né?
*/
```

### Tipos de dados
| Tipos  | Descrição | Exemplo |
| ------------- | ------------- | ------------- |
| int  | Valor inteiro  | 10 |
| String  | Texto  | "Isso é uma string nota 10" |
| float  | Valor com ponto flutuante  | 10.0 |
| boolean  | Valor lógico  | true/false |

### Operadores relacionais
| Tipos  | Descrição |
| ------------- | ------------- |
| <  | Menor que  |
| <=  | Menor ou igual  |
|  > | Maior que  |
| >=  | Maior ou igual  |
| ==  |  Igual |
| !=  | Diferente  |

### Operadores artiméticos
| Tipos  | Descrição |
| ------------- | ------------- |
| +  | Soma  |
| -  | Subtração  |
|  * | Multiplicação  |
| /  | Divisão  |

### Estruturas de repetição

Existem duas estruturas de repetição:

*trampo* que é o equivalente ao while em outras linguagens
```bash
trampo(condição)
    declaração
```

Enquanto a condição for verdadeira o loop trampo executará a declaração

Exemplo:
o trampo a seguir executará enquanto o valor de i for menor ou igual a 10
```bash
int i = 0;
trampo(i <= 10){
    i++;
}
```

*mocota* que é o equivalente ao for em outras linguagens
```bash
mocota([expressaoInicial];[condicao];[incremento])
    declaração
```

A expressão incial é inicializada e caso possível executada

Caso o resultado da condição seja verdadeiro o laço é executado

A expressão incremento executa e retorna para a condição

Exemplo:
o mocota a seguir executará enquanto o valor de i for menor ou igual a 10
```bash
mocota(int i =0; i<= 10; i++){
    // faça algo aqui
}
```

### Estrutura de decisão

*sepa* que é o equivalente ao if em outras linguagens
```bash
sepa(condição)
    declaração
```

Além disso o *sepa* pode ser aninhado e possuir um *sepaqnao* que seria o equivalente ao else
```bash
sepa(condição)
    sepa(condição)
        declaração
sepaqnao
    declaração
```

Exemplo:
```bash
sepa(10 > 5){
    // Se 10 for maior que 5 faça algo aqui
} sepaqnao{
    // Senão faça algo aqui
}
```
### Leitura e Escrita de dados

Na Paulista Language, *desembucha* e *chegaai* são responsáveis pela leitura e escrita respectivamente

Exemplo:
```bash
String nome;
desembucha(nome); // Aqui ele lerá o valor digitado e armazenará na variável nome
chegaai("Estou escrevendo algo, ass: ", nome);
```
