# Meu projeto

```mermaid
graph TD
    subgraph "Tipos de Dados"
        A1[Inteiros]
        A2[Float]
        A3[String]
        A4[Boolean]
        A5[Listas]
        A6[Tuplas]
        A7[Dicionários]
        A8[Conjuntos]
    end

    subgraph "Estruturas de Controle"
        B1[If / Else]
        B2[For]
        B3[While]
        B4[Try / Except]
    end

    subgraph "Funções e Classes"
        C1[Função]
        C2[Classe]
        C3[Método]
        C4[Herança]
    end

    %% Conexões de tipos de dados
    A1 --> Z[Operações Matemáticas]
    A2 --> Z
    A3 --> Y[Manipulação de Texto]
    A5 --> X[Coleções]
    A6 --> X
    A7 --> X
    A8 --> X

    %% Conexões de estruturas de controle
    B1 --> W[Fluxo de Controle]
    B2 --> W
    B3 --> W
    B4 --> V[Tratamento de Erros]

    %% Conexões de funções e classes
    C1 --> U[Reutilização de Código]
    C2 --> T[Programação Orientada a Objetos]
    C3 --> C2
    C4 --> C2
