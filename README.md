# Sistema de Análise de Sequências de DNA em Linguagem C

## Sobre o Projeto

Este projeto foi desenvolvido como atividade prática da disciplina de Linguagem de Programação do curso de Análise e Desenvolvimento de Sistemas (ADS). O principal objetivo da proposta foi proporcionar o aprendizado da linguagem C por meio da construção de uma aplicação baseada em um problema real da área de Bioinformática.

A escolha do contexto da Bioinformática permitiu aplicar conhecimentos computacionais em um cenário científico, demonstrando como a programação pode ser utilizada para processar e analisar informações biológicas de forma automatizada.

---

## Objetivos do Projeto

O desenvolvimento deste sistema teve como finalidade consolidar os conceitos estudados durante a disciplina de Linguagem de Programação, aplicando-os em um projeto completo desenvolvido em linguagem C.

Entre os principais objetivos estão:

* Desenvolver habilidades de programação estruturada;
* Aplicar conceitos de modularização e reutilização de código;
* Trabalhar com estruturas de dados definidas pelo usuário;
* Manipular cadeias de caracteres utilizando sequências genéticas;
* Implementar algoritmos de busca e ordenação;
* Utilizar manipulação de arquivos para persistência de dados;
* Simular aplicações computacionais utilizadas na área de Bioinformática.

---

## Contexto de Bioinformática

A Bioinformática é uma área interdisciplinar que combina Computação, Biologia, Estatística e Matemática para armazenar, processar e analisar informações biológicas.

Uma das principais aplicações dessa área é o estudo de sequências de DNA, que são representadas computacionalmente por cadeias formadas pelas bases nitrogenadas Adenina (A), Timina (T), Citosina (C) e Guanina (G).

Neste projeto, as sequências de DNA são utilizadas como objeto de estudo para a implementação das funcionalidades do sistema, servindo como base para o desenvolvimento e aplicação dos conceitos de programação abordados na disciplina.

---

## Funcionalidades Implementadas

O sistema permite o cadastro e gerenciamento de sequências genéticas, oferecendo recursos de análise e manipulação dos dados armazenados.

As principais funcionalidades implementadas são:

* Cadastro de sequências de DNA;
* Validação de bases nitrogenadas;
* Listagem das sequências cadastradas;
* Contagem das bases A, T, C e G;
* Cálculo do conteúdo GC;
* Busca de padrões genéticos (motifs);
* Ordenação de sequências por tamanho;
* Comparação genética utilizando Distância de Hamming;
* Salvamento e carregamento de dados em arquivos.

---

## Conceitos de Linguagem C Aplicados

Durante o desenvolvimento do projeto foram utilizados diversos recursos fundamentais da linguagem C, permitindo a aplicação prática dos conteúdos estudados na disciplina.

Entre os principais conceitos empregados destacam-se:

* Variáveis e tipos de dados;
* Estruturas condicionais;
* Estruturas de repetição;
* Vetores e matrizes;
* Strings;
* Funções;
* Modularização em múltiplos arquivos;
* Estruturas (`struct`);
* Ponteiros;
* Manipulação de arquivos;
* Compilação modular;
* Utilização de bibliotecas da linguagem C.

---

## Estrutura do Projeto

O sistema foi organizado de forma modular, separando as responsabilidades em diferentes arquivos-fonte e arquivos de cabeçalho. Essa abordagem segue boas práticas de desenvolvimento e facilita a manutenção do código.

```text
.
├── main.c
├── cadastro.c
├── cadastro.h
├── analise.c
├── analise.h
├── comparacao.c
├── comparacao.h
├── ordenacao.c
├── ordenacao.h
├── arquivo.c
├── arquivo.h
├── sequencia.h
├── sequencias.txt
└── Makefile
```

---

## Tecnologias Utilizadas

* Linguagem C
* GCC (GNU Compiler Collection)
* Make
* Biblioteca Padrão da Linguagem C

---

## Compilação

Para compilar o projeto, execute o comando:

```bash
make
```

O Makefile é responsável por compilar automaticamente todos os módulos do sistema e gerar o executável final.

---


## Resultados Obtidos

O desenvolvimento deste projeto permitiu aplicar de forma prática os conceitos estudados na disciplina de Linguagem de Programação, demonstrando a utilização da linguagem C na construção de um sistema completo.

Além de reforçar conhecimentos relacionados à programação estruturada, o projeto também proporcionou contato inicial com problemas computacionais inspirados na Bioinformática, evidenciando a importância da computação em áreas científicas e multidisciplinares.

