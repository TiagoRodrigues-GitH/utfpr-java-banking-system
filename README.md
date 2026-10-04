# Banking System in Java

Console application that registers individual and corporate bank clients, written to practise the pillars of object-oriented programming: inheritance, polymorphism, encapsulation and exception handling.

| | |
|---|---|
| **Author** | Tiago Rodrigues · Universidade Tecnológica Federal do Paraná (UTFPR) |
| **Date** | 2026-06-01 |
| **Context** | Postgraduate Program in Java Technologies, UTFPR (Java I) |
| **Stack** | Java |
| **Other languages** | [Português](README.pt.md) · [Deutsch](README.de.md) |

> **Resumo (PT).** Sistema bancário em Java para clientes pessoa física e jurídica; exercício de herança, polimorfismo, encapsulamento e exceções personalizadas.

## 🧱 Project Structure

- `ClienteBanco` (abstract)
- `PessoaFisica` (final)
- `PessoaJuridica` (final)
- `Endereco` (final)
- `NumException` (checked exception)
- `Verifica` (interface)
- `TstConta` (main test class)

## ⚙️ Features

- Register Individual and Legal Entity clients
- Validate CPF (range between 10 and 20)
- Validate responsible person's name (Legal Entity)
- Prevent negative account numbers with a custom exception
- Check if the account number is even or odd

<img width="563" height="410" alt="Captura de tela 2026-06-01 142451" src="https://github.com/user-attachments/assets/43482eef-08e3-461c-8552-8df0ee555f7c" />


## ▶️ How to run

```bash
javac *.java
java TstConta
```
