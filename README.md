# 🧩 Exercícios de Programação Orientada a Objetos em C#

Este repositório contém uma coleção de **exercícios práticos** de **Programação Orientada a Objetos (POO)** em **C#**, desenvolvidos com o objetivo de reforçar conceitos fundamentais da linguagem e aplicar boas práticas de desenvolvimento.

A ideia é simular **mini projetos** que utilizam classes, métodos, construtores, herança e polimorfismo de forma progressiva.  
Cada exercício está organizado em uma pasta separada, facilitando a navegação e execução.

---

## 🎯 Objetivos do repositório
- Praticar conceitos de **POO em C#** (classes, objetos, construtores, encapsulamento, herança, polimorfismo).  
- Exercitar a criação de **estruturas mais próximas de projetos reais**.  
- Consolidar lógica de programação aplicada a problemas do dia a dia.  
- Evoluir os exercícios gradualmente, até chegar em exemplos que envolvem herança e até simulações mais complexas.  

---

## 📂 Estrutura dos exercícios
Cada pasta corresponde a um desafio independente:

1. **Biblioteca** → cadastro e listagem de livros.  
2. **Sistema de Alunos** → alunos, turmas e cálculo de média.  
3. **Loja de Produtos** → produtos, carrinho de compras e valor total.  
4. **Funcionários (Herança)** → hierarquia de funcionários, gerente e desenvolvedor.  
5. **Banco** → contas bancárias com depósitos, saques e transferências.  
6. **Jogo RPG (Extra)** → personagens, guerreiros e magos em uma batalha simples.  

---

## 🛠️ Tecnologias utilizadas
- C#
- .NET SDK (versão 6.0 ou superior)
- Git/GitHub para versionamento

---

## Exercício 1 – Biblioteca simples
**Descrição:**  
Criar uma classe `Livro` com propriedades **Título**, **Autor** e **Ano**, incluindo construtor padrão e personalizado, além de método `ExibirInfo()`. Criar também a classe `Biblioteca` com lista de livros, métodos `AdicionarLivro()` e `ListarLivros()`.  
**Objetivo:** Praticar criação de classes, construtores e listas de objetos.

**Exercise 1 – Simple Library**  
Create a `Book` class with properties **Title**, **Author**, and **Year**, including default and custom constructors, and a method `DisplayInfo()`. Also, create a `Library` class with a list of books, methods `AddBook()` and `ListBooks()`.  
**Goal:** Practice class creation, constructors, and object lists.

---

## Exercício 2 – Sistema de Alunos
**Descrição:**  
Criar uma classe `Aluno` com **Nome**, **Matrícula** e **Nota**, construtor personalizado, métodos `DefinirNota()` e `ExibirAluno()`. Criar a classe `Turma` com lista de alunos, método `AdicionarAluno()` e `MediaDaTurma()`.  
**Objetivo:** Praticar manipulação de listas e cálculo de médias em objetos.

**Exercise 2 – Student System**  
Create a `Student` class with **Name**, **Enrollment**, and **Grade**, custom constructor, methods `SetGrade()` and `DisplayStudent()`. Also, create a `Classroom` class with a list of students, method `AddStudent()` and `ClassAverage()`.  
**Goal:** Practice working with lists and calculating averages.

---

## Exercício 3 – Loja de Produtos
**Descrição:**  
Criar uma classe `Produto` com **Nome**, **Preço** e **Quantidade**, construtor personalizado, métodos `ValorTotal()` e `ExibirInfo()`. Criar uma classe `Carrinho` com lista de produtos e métodos `AdicionarProduto()` e `ExibirCarrinho()`.  
**Objetivo:** Praticar classes, listas e cálculos simples de objetos.

**Exercise 3 – Product Store**  
Create a `Product` class with **Name**, **Price**, and **Quantity**, custom constructor, methods `TotalValue()` and `DisplayInfo()`. Create a `Cart` class with a list of products and methods `AddProduct()` and `DisplayCart()`.  
**Goal:** Practice classes, lists, and simple calculations.

---

## Exercício 4 – Herança: Funcionários
**Descrição:**  
Criar classe `Funcionario` com **Nome** e **SalárioBase**, método `ExibirInfo()`. Criar classes `Gerente` e `Desenvolvedor` que herdam de `Funcionario`, adicionando **Bônus** e **Linguagem principal**, respectivamente, sobrescrevendo métodos quando necessário.  
**Objetivo:** Exercitar herança, construtores e sobrescrita de métodos.

**Exercise 4 – Inheritance: Employees**  
Create an `Employee` class with **Name** and **BaseSalary**, method `DisplayInfo()`. Create `Manager` and `Developer` classes inheriting from `Employee`, adding **Bonus** and **MainLanguage**, overriding methods as needed.  
**Goal:** Practice inheritance, constructors, and method overriding.

---

## Exercício 5 – Banco
**Descrição:**  
Criar classe `ContaBancaria` com **Número da conta**, **Titular** e **Saldo**, métodos `Depositar()`, `Sacar()` e `ExibirSaldo()`. Criar classe `Banco` com lista de contas e métodos `AdicionarConta()`, `Transferir()` e `ListarContas()`.  
**Objetivo:** Simular contas bancárias e operações financeiras simples.

**Exercise 5 – Bank**  
Create a `BankAccount` class with **AccountNumber**, **Owner**, and **Balance**, methods `Deposit()`, `Withdraw()`, and `DisplayBalance()`. Create a `Bank` class with a list of accounts and methods `AddAccount()`, `Transfer()`, and `ListAccounts()`.  
**Goal:** Simulate bank accounts and simple financial operations.

---

## Exercício Extra – Sistema de Jogo RPG
**Descrição:**  
Criar classe `Personagem` com **Nome**, **Vida** e **Ataque**, método `Atacar()`. Criar classes `Guerreiro` e `Mago` que herdam de `Personagem`, adicionando **Defesa** e **Mana**, respectivamente, com métodos especiais.  
**Objetivo:** Praticar herança, construtores e interações entre objetos.

**Extra Exercise – RPG Game System**  
Create a `Character` class with **Name**, **Health**, and **Attack**, method `Attack()`. Create `Warrior` and `Mage` classes inheriting from `Character`, adding **Defense** and **Mana**, with special methods.  
**Goal:** Practice inheritance, constructors, and object interactions.
