# Swift Fundamentals I

    /
    /: Playground - noun: a place where people can play
    // Author: Cauê Scalzaretto
    // SWIFT 4
    
    
    import UIKit
    
    print("Hello, world")
    
    var myVariable = 42 // variável
    
    let π = 3.1415926 // constante
    
    // Escopo (var/let) nome : tipo = valor
    var notaSemestre : Int = 9
    print(notaSemestre)
    
    
    
    // Tipos de Dado Descrição Exemplo
    //====================================================================================================
    // Character um único carácter "A"
    //----------------------------------------------------------------------------------------------------
    // String texto em geral "lorem ipsum"
    //----------------------------------------------------------------------------------------------------
    // Int valores inteiros que 25
    // podem ser 32 ou 64 bits
    // conforme a plataforma
    //----------------------------------------------------------------------------------------------------
    // Float ponto flutuante (32 bits) 3.1415926
    //----------------------------------------------------------------------------------------------------
    // Double ponto flutuante (64 bits) 3.14159265359
    //----------------------------------------------------------------------------------------------------
    // Array coleção de valores ordenados ["A","B","C"]
    // de um mesmo tipo
    //----------------------------------------------------------------------------------------------------
    // Dictionary coleção que associa chaves e ["cliente":1, "tipo":"A", "credito": true]
    // valores
    //----------------------------------------------------------------------------------------------------
    // Set coleção de valores sem ordena [10,11,12,13,14,15]
    // ção que náo permite valores
    // repetidos
    //----------------------------------------------------------------------------------------------------
    // Bool verdadeiro ou falso true / false
    //----------------------------------------------------------------------------------------------------
    
    
    let t: Dictionary = ["cliente":1, "tipo":"A", "valor": 1] as [String : Any]
    
    let a: Set = [10,11,12,13,14,15]
    
    let x: Bool = true
    
    let caracter1 = "caf\u{E9}"
    let caracter2: Character = "\u{24}"
    let caracter3 = "\u{2665}"
    print("palavra acentuada: \(caracter1)")
    print("símbolo cifrão...: \(caracter2)")
    print("coração..........: \(caracter3)")
    
    print("texto\ntexto")
    print("texto\ttexto\ttexto")
    
    var preco = 300.00
    //O preço é igual a preço mais 59.90
    preco += 59.90
    //O preço é igual a preço menos 10.10
    preco -= 10.10
    
    var nome = "Geraldo"
    var resultado = (nome == "Geraldo") ? "Seja bem vindo" : "Desconhecido"
    
    var parOuImpar = (10 % 2 == 0) ? "Par" : "Impar" //Retornará par
    parOuImpar = (3 % 2 == 0) ? "Par" : "Impar" //Retornará ímpar
