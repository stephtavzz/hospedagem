# 🏨 Sistema de Hospedagem em C#

![C#](https://img.shields.io/badge/C%23-10.0%2B-purple)
![.NET](https://img.shields.io/badge/.NET-8.0-blue)

## 📌 Sobre o Projeto

Este projeto foi desenvolvido como parte de um desafio prático da **DIO (Digital Innovation One)** no módulo de **Explorando a Linguagem C#** da trilha **.NET**.  
O objetivo é implementar um **sistema de hospedagem** para gerenciar reservas de hóspedes, com funcionalidades como **cadastro de hóspedes**, **atribuição de suítes** e **cálculo de diárias**.

## ⚙️ Funcionalidades Implementadas

1. **Cadastrar hóspede**
   - O usuário informa o nome completo do hóspede;
   - O hóspede é adicionado a uma lista de hóspedes.

2. **Cadastrar suíte**
   - O usuário informa o tipo, capacidade e valor da diária de uma suíte;
   - A suíte é associada à reserva.

3. **Realizar reserva**
   - O sistema verifica se a quantidade de hóspedes não excede a capacidade da suíte;
   - Se a quantidade de hóspedes for maior que a capacidade da suíte, uma exceção é lançada.

4. **Calcular valor da diária**
   - O sistema calcula o valor da diária com base nos dias reservados e no valor da diária da suíte;
   - Se a reserva for maior ou igual a 10 dias, um desconto de 10% é aplicado no valor total.

5. **Listar quantidade de hóspedes**
   - O sistema exibe a quantidade total de hóspedes cadastrados na reserva.

6. **Menu interativo**
   - O usuário pode realizar as seguintes ações:
     - Cadastrar hóspede
     - Cadastrar suíte
     - Realizar reserva
     - Exibir a quantidade de hóspedes
     - Calcular o valor da diária

## 🖥️ Exemplo de Uso

Ao executar o programa, o usuário interage com o menu para realizar as operações desejadas:

Digite a sua opção:
1 - Cadastrar hóspede
2 - Cadastrar suíte
3 - Realizar reserva
4 - Exibir quantidade de hóspedes
5 - Calcular valor da diária
6 - Encerrar

As operações são realizadas conforme a escolha do usuário, com mensagens claras de sucesso ou falha.

## ✅ Regras de Negócio

- A suíte só pode acomodar um número de hóspedes igual ou inferior à sua capacidade;
- O valor da diária é calculado com base no número de dias reservados;
- Se a reserva for para 10 ou mais dias, é concedido um **desconto de 10%** sobre o valor da diária;
- Caso a quantidade de hóspedes ultrapasse a capacidade da suíte, uma exceção é gerada;
- O sistema exibe a quantidade total de hóspedes cadastrados e o valor total da diária.

## 🛠️ Tecnologias Utilizadas

- C# 10+
- .NET 8.0
- **Visual Studio Code** como ambiente de desenvolvimento

## 📂 Como Executar o Projeto

1. Clone o repositório:
```bash
git clone https://github.com/stephtavzz/hospedagem.git
```

2. Navegue até o diretório do projeto:
```bash
cd hospedagem
```

3. Execute o projeto:
```bash
dotnet run
```
## 👩‍💻 Autora

**Stephanie Tavares dos Santos**  
🔗 [LinkedIn](https://www.linkedin.com/in/stephanie-t-santos/)  
💻 [GitHub](https://github.com/stephtavzz)  


Este projeto foi desenvolvido para fins educacionais, como parte de um desafio da plataforma DIO, visando a prática de sintaxe básica com C# e .NET.
