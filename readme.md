# Mini Expression Language

Um interpretador simples para uma linguagem de expressões matemáticas, desenvolvido com **ANTLR** e **Python**.

O projeto define uma gramática própria para expressões aritméticas e operações de memória, gera o parser com ANTLR e executa as expressões usando um listener em Python.

## Funcionalidades

- Parsing de expressões matemáticas
- Suporte a operações aritméticas:
  - soma
  - subtração
  - multiplicação
  - divisão
  - divisão inteira
  - módulo
  - potenciação
- Operações de memória
- Avaliação baseada em stack
- Tratamento de erros para operações inválidas
- Gramática definida com ANTLR

## Exemplo de expressões

```txt
2 + 3 * 4
(10 - 2) / 4
2 ^ 3
