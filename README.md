# 🏨 Desafio - Sistema de Hospedagem com C#

Este é um projeto prático desenvolvido como parte da trilha .NET na plataforma DIO. O objetivo é simular um sistema de hospedagem em hotel, onde é possível 
cadastrar hóspedes, uma suíte e realizar uma reserva com cálculo de valor da diária.

---

## 📌 Objetivo

Construir um sistema que relacione hóspedes e suítes através de uma reserva, aplicando regras de negócio como:

- Verificar a capacidade da suíte antes de cadastrar os hóspedes.
- Calcular o valor da diária conforme o número de dias.
- Aplicar desconto de 10% se a reserva for de 10 dias ou mais.

---

## 🧠 Tecnologias Utilizadas

- C#
- .NET 6+
- Programação Orientada a Objetos (POO)
- Git e GitHub

---

## 📁 Estrutura de Classes

### `Pessoa`

- `Nome`
- `Sobrenome`
- `NomeCompleto` (get-only)

### `Suite`

- `TipoSuite`
- `Capacidade`
- `ValorDiaria`

### `Reserva`

- `DiasReservados`
- `Hospedes`
- `Suite`
- Métodos:
  - `CadastrarHospedes(List<Pessoa>)`
  - `CadastrarSuite(Suite)`
  - `ObterQuantidadeHospedes()`
  - `CalcularValorDiaria()`

---

## 🧪 Como Executar

1. Clone o repositório:

```bash
git clone https://github.com/Wricardo81/DesafioProjetoHospedagem.git
cd DesafioProjetoHospedagem
