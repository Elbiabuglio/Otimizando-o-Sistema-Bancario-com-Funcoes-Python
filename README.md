# Desafio de projeto da plataforma [DIO](https://web.dio.me/track/coding-future-vivo-python-ai-backend-developer) - Otimizando um sistema bancário em Python

## Objetivo:
- Modificar o projeto: Sistema bancário em Python
- Separar as funções existentes de saque, depósito e extrato em funções.
- Criar novas funções: Cadastrar e Listar Clientes, Cadastrar e Listar Contas Bancárias.

## Requisitos:
### 1. Função Saque
- Receber argumentos por nome (keyword only)
- Sugestão parâmetros: saldo, valor, extrato, limite, num_saques, limite_saques
- Sugestão retorno: saldo, extrato
  
### 2. Função Deposito
- Receber argumentos por posição (positional only)
- Sugestão argumentos: saldo, valor, extrato
- Sugestão retorno: saldo, extrato
  
### 3. Função Extrato
- Receber argumentos por posição (positional only) e nome (keyword only)
- Argumentos posicionais: saldo, argumentos nomeados: extrato
 
### 4. Função Criar Conta-Corrente
- Armazenar usuário em uma lista
- Uma conta é composta por: agência, número da conta e usuário
- O número da agência é fixo (0001)
- O número da conta é sequqencial começando em 1
- O usuário pode ter mais de uma conta
- Uma conta pertence a um único usuário
  
### 5. Função Criar Usuario
- Armazenar usuário em uma lista
- Atributos do usuário: nome, data de nascimento, cpf, endereço
- Endereco = string com o formato "logradouro, nro, bairro, cidade/US
- CPF: armazenar comente números
- CPF: não permitir mais de um usuário com o mesmo CPF
  
### 6. Função Listar Conta-Corrente
- Listar contas cadastradas
  
### 7. Função Listar Usuarios
- Listar contas cadastradas
