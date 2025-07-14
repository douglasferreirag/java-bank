# Sistema Bancário em Java (POO)

Este repositório contém um projeto simples de sistema bancário desenvolvido com foco na prática de Programação Orientada a Objetos (POO). A ideia é simular funcionalidades comuns de um banco, como criação de contas, movimentações financeiras, transferências via PIX e até investimentos, utilizando os principais conceitos da orientação a objetos em Java.

## Sobre o projeto

Este projeto foi feito como parte de um laboratório da plataforma DIO (Digital Innovation One). O objetivo principal é colocar em prática tudo o que foi aprendido nas aulas, usando Java como linguagem base.

Além disso, ele serve como um bom exercício para reforçar conceitos como:

    * Herança
    
    * Encapsulamento
    
    * Abstração
    
    * Polimorfismo
    
    * Reutilização de código

## O que o sistema faz?

    * Criar contas bancárias
    
    * Realizar depósitos e saques
    
    * Transferir valores via PIX
    
    * Registrar e simular investimentos
    
    * Exibir histórico de transações por conta
    
    * Menu interativo no terminal para navegar pelas opções

## Tecnologias usadas

    * Java 17+
    
    * Lombok (para reduzir boilerplate)
    
    * Enums e Records (para organização e clareza)
    
    * IDE ( Utilizei o IntelliJ)



## Estrutura do projeto

📦 src
 ┣ 📂 app          → Ponto de entrada da aplicação e menus
 ┣ 📂 model        → Classes que representam as entidades (conta, cliente, investimento)
 ┣ 📂 repository   → Armazena dados em memória (sem banco de dados real)
 ┣ 📂 exception    → Exceções a serem lançadas em determinada execução do código.
