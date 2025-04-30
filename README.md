# Assembler no z/OS

Este repositório contém meus estudos e exemplos de programação em **Assembler (HLASM)** no ambiente **mainframe z/OS**, abordando desde conceitos básicos até integração com JCL.

## Objetivo

Aprender a programar em linguagem de montagem (Assembler) no z/OS, compreendendo a estrutura de instruções, uso de registradores, chamadas de sistema e montagem de programas reais.

## Conteúdo do Curso

### 1. Introdução ao Assembler
- Estrutura de um programa Assembler
- Registradores e instruções básicas
- Formato das instruções (label, opcode, operandos)
- Comentários e organização do código

### 2. Desenvolvimento de Programas
- Manipulação de dados em registradores
- Operações aritméticas e lógicas
- Uso de loops e condicionais
- Acesso à memória e endereçamento

### 3. Interação com o Sistema
- Chamada de serviços do sistema (SVC)
- Uso de macros como `PUT`, `GET`, `WTO`
- Entrada e saída (I/O) com DCB e macros padrão

### 4. Montagem e Execução
- Como montar programas com JCL
- Análise de listagens (SYSPRINT, SYSOUT)
- Testes e depuração básica

## Estrutura do Repositório

```plaintext
📁 assembler/
    📄 hello.asm            # Programa básico de saída de texto
    📄 soma.asm             # Exemplo de soma de números
    📄 io_basico.asm        # Exemplo com entrada e saída
📁 jcl/
    📄 monta_hello.jcl      # JCL para montagem e execução do hello.asm
    📄 monta_io.jcl
📄 README.md
