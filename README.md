# 🚗 Sistema de Estacionamento em C#
![.NET](https://img.shields.io/badge/.NET-8-blue)
![C#](https://img.shields.io/badge/C%23-Fundamentos-brightgreen)

Este repositório é um **fork** do desafio da **DIO**, desenvolvido para praticar conceitos fundamentais de **C#** e programação orientada a objetos.

## ✨ Funcionalidades implementadas
- ✅ Adicionar veículo: permite cadastrar uma placa no estacionamento.
- ✅ Remover veículo: calcula o valor total a pagar com base no preço inicial e preço por hora, removendo o veículo da lista.
- ✅ Listar veículos: exibe todos os veículos cadastrados no estacionamento.
- ✅ Menu interativo: opções para gerenciar veículos e encerrar o programa.

## 📌 Estrutura do projeto
- **Estacionamento.cs**: contém as variáveis `precoInicial`, `precoPorHora` e a lista de veículos, além dos métodos `AdicionarVeiculo`, `RemoverVeiculo` e `ListarVeiculos`.
- **Program.cs**: arquivo principal com o menu interativo que permite executar as operações.

![Diagrama de classe estacionamento](diagrama_classe_estacionamento.png)

## 🚀 Como rodar


1. Clone o repositório:

   ```bash
   git clone https://github.com/andreza1freitas/trilha-net-fundamentos-desafio.git

2. Navegue até o diretório do projeto:

   ```bash
   cd trilha-net-fundamentos-desafio

3. Restaure os pacotes NuGet necessários:

   ```bash
   dotnet restore DesafioFundamentos.csproj

4. Compile o projeto:

   ```bash
   dotnet build DesafioFundamentos.csproj

5. Execute o projeto:

   ```bash
   dotnet run --project DesafioFundamentos.csproj
<br> 

## 💡 Observações

- Projeto criado como aplicação console em **.NET 8**; recomenda-se ter a versão mais recente do SDK instalada.
- Exercício prático para reforçar conceitos de listas, condicionais, laços de repetição e entrada/saída no console.

## 📜 Licença

Projeto desenvolvido para fins de estudo e prática educacional, sem fins comerciais.