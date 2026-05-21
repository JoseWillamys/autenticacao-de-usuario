# Sistema de Autenticação de Usuário

Este projeto é um exercício prático desenvolvido em **C#** utilizando o **Visual Studio**, com o objetivo de implementar um sistema simples de autenticação de usuários via console.

## 🚀 Funcionalidades

- Login com usuário e senha
- Verificação de credenciais cadastradas
- Cadastro de novos usuários
- Acesso como convidado
- Encerramento do sistema
- Validação de entradas para evitar erros

## 📂 Estrutura do Código

O sistema foi implementado com funções que organizam o fluxo de interação:

- `InteracoesDoMenu()` → Controla a entrada inicial de usuário e senha  
- `VerificacaoDeUsuario()` → Confere se o usuário existe e se a senha está correta  
- `CadastrarUsuario()` → Permite criar novos usuários  
- `ExibirOpcoesDoMenu()` e `AcoesDoMenu()` → Exibem opções quando o login falha  
- `ValidarString()` e `ValidarOpcao()` → Garantem que entradas sejam válidas  

## 🛠️ Tecnologias Utilizadas

- Linguagem: **C#**
- IDE: **Visual Studio**
- Estrutura: **Console Application**
