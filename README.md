# Meu projeto


@startuml
title Diagrama Básico de Python

package "Tipos de Dados" {
    class Inteiros
    class Float
    class String
    class Boolean
    class Lista
    class Tupla
    class Dicionario
    class Conjunto
}

package "Estruturas de Controle" {
    class If_Else
    class For
    class While
    class Try_Except
}

package "Funções e Classes" {
    class Funcao
    class Classe
    class Metodo
    class Heranca
}

Inteiros --> "Operações Matemáticas"
Float --> "Operações Matemáticas"
String --> "Manipulação de Texto"
Lista --> "Coleções"
Tupla --> "Coleções"
Dicionario --> "Coleções"
Conjunto --> "Coleções"

Funcao --> "Reutilização de Código"
Classe --> "Programação Orientada a Objetos"
Metodo --> Classe
Heranca --> Classe

If_Else --> "Fluxo de Controle"
For --> "Fluxo de Controle"
While --> "Fluxo de Controle"
Try_Except --> "Tratamento de Erros"

@enduml

