# TDEVN03---NP1---PARTE-2
Parte 2 - NP1


# Avaliação Prática — Programação Orientada a Objetos com Python

## Sobre o projeto

Este projeto consiste em um exercício prático de avaliação da disciplina de **Programação Orientada a Objetos (POO) com Python**.

O objetivo é desenvolver um sistema simples de cadastro e avaliação de alunos, aplicando conceitos fundamentais da linguagem Python e da orientação a objetos.

## Objetivos de aprendizagem

- Criar classes e instanciar objetos.
- Definir atributos e utilizar o construtor `__init__()`.
- Criar métodos para executar operações.
- Utilizar parâmetros e valores de retorno.
- Trabalhar com entrada e saída de dados.
- Aplicar estruturas condicionais.
- Calcular médias e determinar a situação acadêmica de um aluno.

## Requisitos funcionais

O programa deverá:

1. Criar uma classe chamada `Aluno`.
2. Inicializar os atributos `nome`, `nota1` e `nota2`.
3. Implementar o método `calcular_media()` para calcular a média aritmética das duas notas.
4. Implementar o método `verificar_situacao()` para determinar a situação do aluno.
5. Solicitar ao usuário o nome e as duas notas.
6. Criar um objeto da classe `Aluno`.
7. Exibir o nome, as notas, a média e a situação final.

## Regra de aprovação

A situação acadêmica será definida pela seguinte regra:

- **Aprovado:** média maior ou igual a 7,0.
- **Reprovado:** média inferior a 7,0.

A média será calculada pela fórmula:

\[
\text{Média} = \frac{\text{Nota 1}+\text{Nota 2}}{2}
\]

## Exemplo de execução

```text
Nome do aluno: Ana
Primeira nota: 8
Segunda nota: 6

Aluno: Ana
Nota 1: 8.0
Nota 2: 6.0
Média: 7.0
Situação: Aprovado
```

## Tecnologias utilizadas

- Python 3
- Programação Orientada a Objetos
- Terminal ou ambiente de desenvolvimento Python

## Como executar

1. Instale o Python 3, caso ainda não esteja instalado.
2. Clone este repositório ou baixe os arquivos.
3. Abra o terminal na pasta do projeto.
4. Execute o arquivo Python que contém a solução:

```bash
python main.py
```

Se necessário, utilize `python3 main.py`, conforme a configuração do ambiente.

## Critérios de avaliação

| Critério | Pontuação |
|---|---:|
| Criação da classe `Aluno` | 0,75 |
| Construtor `__init__()` e atributos | 0,75 |
| Método `calcular_media()` | 1,00 |
| Método `verificar_situacao()` | 0,75 |
| Entrada de dados e criação do objeto | 0,75 |
| Exibição dos resultados e organização do código | 1,00 |
| **Total** | **5,00 pontos** |

## Público-alvo

Estudantes iniciantes em Python que estão desenvolvendo conhecimentos sobre funções, classes, objetos, atributos, métodos e estruturas condicionais.

## Licença

Material didático para fins educacionais. A licença de reutilização poderá ser definida pelo responsável pelo repositório.
