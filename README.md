# SenaiSystem

Projeto Integrador desenvolvido no âmbito do curso do SENAI, com o objetivo de criar uma aplicação de anotações chamada **Senai Notes**.

## Sobre o Projeto

O **SenaiSystem** é uma aplicação desenvolvida em C#, utilizando o Visual Studio, que permite aos usuários criar, editar e gerenciar anotações de forma eficiente.  
Este projeto visa aplicar na prática os conhecimentos adquiridos durante o curso, integrando conceitos de programação orientada a objetos, manipulação de arquivos e interfaces gráficas.

## Tecnologias Utilizadas

-  Linguagem: C#
-  IDE: Visual Studio
-  Controle de Versão: Git
-  Plataforma: GitHub

## Estrutura do Projeto

A seguir, estão os principais diretórios e arquivos do projeto, organizados por função:

### Controllers — Camada de Controle da Aplicação
Responsáveis por receber requisições e retornar respostas, conectando as views aos serviços.
- `CategoriaController.cs`
- `LembreteController.cs`
- `NotaCategoriaController.cs`
- `NotaController.cs`
- `UsuarioController.cs`

### DTOs (Data Transfer Objects)
Objetos usados para transferência de dados entre camadas de forma segura.
- `CadastroEditarCategoriaDto.cs`
- `CadastroEditarLembreteDto.cs`
- `CadastroEditarNotaCategoriaDto.cs`
- `CadastroEditarNotaDto.cs`
- `CadastroEditarUsuarioDto.cs`
- `LoginDto.cs`
- `TrocarSenhaDto.cs`

### Interfaces — Contratos dos Repositórios
Definem os métodos que as classes de repositório devem implementar.
- `ICategoriaRepository.cs`
- `ILembreteRepository.cs`
- `INotaCategoriaRepository.cs`
- `INotaRepository.cs`
- `IUsuarioRepository.cs`

### Models — Entidades do Domínio
Representam as tabelas e entidades principais do sistema.
- `AuditoriaGeral.cs`
- `Categoria.cs`
- `Lembrete.cs`
- `Nota.cs`
- `NotaCategoria.cs`
- `Usuario.cs`

### Repositories — Implementações de Acesso a Dados
Classes que acessam o banco de dados com base nas interfaces.
- `CategoriaRepository.cs`
- `LembreteRepository.cs`
- `NotaCategoriaRepository.cs`
- `NotaRepository.cs`
- `UsuarioRepository.cs`

### Services — Serviços de Regras e Utilitários
Contém lógicas como geração de token e criptografia de senha.
- `PasswordService.cs`
- `TokenService.cs`

### Uploads
Imagens e arquivos enviados pelo usuário.
- `tigre(8).jpg`

### ViewModels — Estruturas de Visualização
Modelos usados para exibir informações específicas na interface ou retornos.
- `CategoriaViewModel.cs`
- `ListarCategoriaViewModel.cs`
- `ListarLembreteViewModel.cs`
- `ListarNotaCategoriaViewModel.cs`
- `ListarNotaViewModel.cs`
- `ListarUsuarioViewModel.cs`

###  Configurações e Arquivos Globais
- `appsettings.json` – Configurações gerais da aplicação
- `appsettings.Development.json` – Configurações específicas para ambiente de desenvolvimento
- `Program.cs` – Ponto de entrada da aplicação

## Como Executar o Projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/m4thi4ss/SenaiSystem.git
2. Abra o arquivo SenaiSystem.sln no Visual Studio.
3. Compile e execute o projeto utilizando as ferramentas do Visual Studio.

## Contribuições

Este projeto foi desenvolvido por João Mathias e Lucas Baptista como parte de um Projeto Integrador do curso SENAI.
