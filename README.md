🚀 Fila Zero - Sistema de Login
📌 Descrição

Este projeto é uma aplicação simples em C# (.NET Console) que simula um sistema básico de login.
O usuário informa nome de usuário e senha, e o sistema valida os dados exibindo se o login foi bem-sucedido ou não.

🧠 Objetivo

Demonstrar:

Entrada de dados pelo usuário
Validação de informações
Uso de estruturas condicionais (if/else)
Organização do código em métodos
Interface simples no terminal
🛠️ Como funciona
O sistema desenha uma tela inicial com o título.
Solicita o nome de usuário.
Solicita a senha.
Verifica se os dados são válidos.
Exibe o resultado do login.
🔐 Credenciais de teste
Usuário: admin
Senha: senha123
▶️ Como executar

No terminal, dentro da pasta do projeto:

dotnet build
dotnet run
📂 Estrutura do código
DesenharTela() → Exibe o layout inicial do sistema
ExecutarLogin() → Responsável por capturar e validar os dados do usuário
💡 Exemplo de uso
=====================================
         Fila Zero - Login
=====================================
Digite seu nome de usuário: admin
Digite sua senha: senha123

Login bem-sucedido! Bem-vindo, admin.
🎯 Melhorias futuras
Ocultar senha digitada
Permitir múltiplas tentativas
Cadastro de usuários
Validação com banco de dados
Mensagens mais detalhadas
