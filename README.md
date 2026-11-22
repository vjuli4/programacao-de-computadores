# Programacao de Computadores

Repositorio com exercicios, revisoes e atividades praticas da disciplina de **Programacao de Computadores**, desenvolvidos em Python.

![Python](https://img.shields.io/badge/Python-3-blue?logo=python&logoColor=white)
![Disciplina](https://img.shields.io/badge/Disciplina-Programação%20de%20Computadores-green)
![Exercicios](https://img.shields.io/badge/Exercícios-Prática-orange)

## Conteudos por nivel

Os materiais estao organizados em uma progressao de dificuldade. Dentro de cada nivel, as listas trabalham primeiro problemas mais diretos e depois combinam varios conceitos.

### Nivel 1 - Primeiros passos

**Assuntos:** primeiro programa, entrada e saida, variaveis, tipos numericos e operacoes basicas.

| Pasta | Assuntos abordados |
|---|---|
| [aula22.09](./aula22.09) | `print`, leitura com `input`, conversao de tipos, concatenacao de dados e calculo de media |
| [apostila](./apostila) | Conversao de unidades, divisao inteira, resto da divisao e duracao de tempo |
| [lista1](./lista1) | Soma, multiplicacao, area, medias, medias ponderadas, subtracao, divisao e conversao em cedulas |

**Exemplos de exercicios:** saudacao, soma de valores, area do circulo, media de notas, perimetro e troco em notas.

### Nivel 2 - Operacoes e resolucao de problemas

**Assuntos:** expressao numerica, formatacao, divisao inteira, operador de resto, proporcoes e modelos matematicos.

| Pasta | Assuntos abordados |
|---|---|
| [lista2](./lista2) | Calculo de salario, reajuste, bonus, pagamento e troco, tempo de viagem, tomadas, modulo e area de piso |

**Exemplos de exercicios:** salario por hora, percentual de ajuste, velocidade media, distancia em pedagio e calculo de piso.

### Nivel 3 - Condicoes simples

**Assuntos:** `if`, `else`, operadores logicos e comparacoes.

| Pasta | Assuntos abordados |
|---|---|
| [lista3](./lista3) | Igualdade, maior numero, par ou impar, multiplos, cardapio, plano cartesiano e verificacao de dimensoes |

**Exemplos de exercicios:** maior de dois ou tres valores, proximos pares ou impares, lancamento de lanches e quadrantes.

### Nivel 4 - Logica condicional composta

**Assuntos:** combinacao de varias condicoes, intervalos, geometria, porcentagens e analise de casos.

| Pasta | Assuntos abordados |
|---|---|
| [lista4](./lista4) | Multiplos comparadores, desigualdade triangular, maior ou menor valor, consumo, tabuleiro de xadrez e classificacao de triangulos |
| [lista5](./lista5) | Comparacao de tempo, busca de valores, aceleracao, maior elemento e calculo de tarifa por faixa |

**Exemplos de exercicios:** velocidade de veiculos, menor numero par, mediana, ponto no tabuleiro e classificacao geometrica.

### Nivel 5 - Estruturas de repeticao basica

**Assuntos:** introducao a `for`, acumuladores, contadores e percursos em sequencias.

| Pasta | Assuntos abordados |
|---|---|
| [lista7](./lista7) | Tabuada, series numericas, multiplos, divisores, media de elementos, primos e listas |
| [lista8](./lista8) | `while`, condicoes de parada, verificacao de senha, ciclos, buscas, simulacoes e processamento ate `EOF` |

**Exemplos de exercicios:** contagem de divisores, soma de uma serie, numero primo, saldo bancario, tempo percorrido e ocupacao.

### Nivel 6 - Funcoes e listas

**Assuntos:** modularizacao, parametros, retorno de valores, listas, indices, alteracao de elementos e pesquisa.

| Pasta | Assuntos abordados |
|---|---|
| [lista6](./lista6) | Funcoes aritmeticas, maior valor, dias da semana, datas, media de listas e manipulacao de elementos |
| [lista9](./lista9) | Vetores, acumuladores, strings, frequencia, compactacao, somas alternadas e busca em sequencias |
| [lista10](./lista10) | Matrizes, contagem, estoque, padroes de repeticao, sequencias alegres, tabuleiro e subsequencias |

**Exemplos de exercicios:** troca do menor elemento, remocao do minimo, numeros consecutivos, corrida de jogadores, anagramas e barcos em tabuleiro.

### Nivel 7 - Revisoes e aplicacoes combinadas

**Assuntos:** integracao de condicoes, listas, repeticao, funcoes e resolucao de problemas com varios passos.

| Pasta | Assuntos abordados |
|---|---|
| [zrevisao_prova05do02](./zrevisao_prova05do02) | Crescimento de listas, intersecao, maior salto, frequencia, compactacao, picos e repeticoes |

Essa revisao combina conceitos dos niveis anteriores e exige atencao a indices, limites da lista e validacao de casos especiais.

### Nivel 8 - Recursividade

**Assuntos:** casos base, chamadas recursivas, reducao do problema e construcoes sobre listas e numeros.

| Pasta | Assuntos abordados |
|---|---|
| [listaFR/listaFR1](./listaFR/listaFR1) | Divisores, numeros primos, algarismos, representacao binaria, combinacao, soma, busca e inversao recursiva |
| [listaFR/listaFR2](./listaFR/listaFR2) | Exercicios adicionais de recursividade, raiz quadrada e contagem de chamadas |

A lista FR2 possui exercicios em desenvolvimento ou incompletos. Os demais codigos da pasta principal podem ser usados como referencia para o estudo de recursao.

## Mapa rapido por conceito

| Conceito | Pastas |
|---|---|
| Entrada e saida | `aula22.09`, `apostila`, `lista1` |
| Operacoes aritmeticas e formatacao | `lista1`, `lista2`, `apostila` |
| Condicionais | `lista3`, `lista4`, `lista5` |
| Estruturas de repeticao | `lista7`, `lista8` |
| Funcoes | `lista6`, `listaFR/listaFR1`, `zrevisao_prova05do02` |
| Listas e vetores | `lista6`, `lista7`, `lista9`, `lista10` |
| Strings e processamento de texto | `lista9`, `lista10` |
| Matrizes e tabuleiros | `lista10` |
| Recursividade | `listaFR/listaFR1`, `listaFR/listaFR2` |

## Como navegar

1. Comece pela pasta [aula22.09](./aula22.09) e pela [lista1](./lista1).
2. Avance pelas listas numeradas na ordem em que os assuntos aparecem neste README.
3. Leia o enunciado ou o comentario do arquivo antes de executar o codigo.
4. Execute um exercicio em um terminal com:

```bash
python caminho/do/arquivo.py
```

Exemplo:

```bash
python lista3/3A-iguais.py
```

## Estrutura geral

```text
.
├── aula22.09/              # primeiros exercicios em sala
├── apostila/               # exercicios da apostila
├── lista1/                 # entrada, saida e operacoes
├── lista2/                 # calculos e problemas matematicos
├── lista3/                 # condicionais simples
├── lista4/                 # condicionais compostas
├── lista5/                 # comparacoes e casos adicionais
├── lista6/                 # funcoes e listas
├── lista7/                 # repeticoes com for
├── lista8/                 # repeticoes com while
├── lista9/                 # listas, vetores e strings
├── lista10/                # problemas combinados
├── zrevisao_prova05do02/   # revisao de prova
└── listaFR/                # exercicios de recursao
    ├── listaFR1/
    └── listaFR2/
```

## Autora

**Júlia Vitória** — [vjuli4](https://github.com/vjuli4)
