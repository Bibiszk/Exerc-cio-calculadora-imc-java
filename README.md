# Exerc-cio-calculadora-imc-java

# 🧮 Calculadora de IMC em Java

Este projeto foi desenvolvido como parte do **Bootcamp Santander Backend Java 2025**, durante a aula de **Estruturas de Controle** da **DIO (Digital Innovation One)**.

O objetivo do exercício é receber a **altura** e o **peso** do usuário, calcular o **IMC (Índice de Massa Corporal)** e exibir uma **mensagem correspondente à faixa de classificação**.

---

## 📚 Conteúdo abordado

- Entrada de dados com `Scanner`
- Estrutura condicional `if`, `else if`, `else`
- Operações matemáticas com `double`
- Impressão formatada com `System.out.printf`

---

## 🧠 Lógica do IMC

A fórmula do IMC é:

IMC = peso / (altura * altura)

yaml
Copiar
Editar

As classificações de acordo com o valor calculado são:

| IMC                      | Classificação                    |
|--------------------------|----------------------------------|
| Até 18.5                 | Abaixo do peso                   |
| De 18.6 até 24.9         | Peso ideal                       |
| De 25.0 até 29.9         | Levemente acima do peso          |
| De 30.0 até 34.9         | Obesidade Grau I                 |
| De 35.0 até 39.9         | Obesidade Grau II (Severa)       |
| A partir de 40.0         | Obesidade Grau III (Mórbida)     |

---

## 💻 Como executar

1. Certifique-se de ter o **Java JDK** instalado.
2. Compile o arquivo:

javac CalculadoraIMC.java
Execute o programa:

java CalculadoraIMC
🛠️ Tecnologias utilizadas
Java 17+

VS Code

Git e GitHub

✍️ Autor
Feito com dedicação por Bianca Brito 💙
Bootcamp Santander Backend Java 2025 | DIO

📌 Licença
Este projeto é de uso educacional, livre para estudo e aperfeiçoamento pessoal.
