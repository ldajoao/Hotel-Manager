## Hotel Manager

## Sobre o projeto

O **Hotel Manager** é um sistema de gerenciamento de hospedagens desenvolvido em C/C++ como projeto acadêmico.

O programa permite realizar o cadastro, consulta, listagem e exclusão de hospedagens, além de exportar informações para um arquivo de texto e contabilizar os registros cadastrados.

## Funcionalidades

- **Cadastrar hospedagem:** registra os dados do hóspede e da hospedagem.
- **Consultar hospedagem:** pesquisa uma hospedagem pelo código.
- **Listar hospedagens:** exibe todas as hospedagens ativas.
- **Excluir hospedagem:** desativa uma hospedagem cadastrada.
- **Exportar para TXT:** gera um arquivo de texto com os dados das hospedagens ativas.
- **Contar registros:** informa a quantidade de registros totais, ativos e excluídos.

## Tecnologias utilizadas

- Linguagem C/C++.
- Bibliotecas padrão: `stdio.h`, `stdlib.h` e `string.h`.
- Compilador GCC/G++.
- Dev-C++ (opcional).

## Estrutura do projeto

```text
Hotel-Manager/
│
├── main.cpp
└── README.md
```

Durante a execução, o programa também poderá gerar automaticamente:

- `hospedagens.dat`: arquivo utilizado para armazenar os registros.
- `hospedagens.txt`: arquivo gerado pela opção de exportação.

## Como baixar o projeto

1. Acesse o repositório no GitHub:
   https://github.com/ldajoao/Hotel-Manager

2. Clique no botão **Code**.

3. Selecione **Download ZIP**.

4. Extraia os arquivos para uma pasta no computador.

Também é possível clonar o repositório pelo terminal:

```bash
git clone https://github.com/ldajoao/Hotel-Manager.git
```

## Como compilar e executar

### Opção 1 - Utilizando Dev-C++

1. Abra o Dev-C++.
2. Clique em **Arquivo → Abrir**.
3. Selecione o arquivo `main.cpp`.
4. Pressione **F11** ou clique em **Compilar e Executar**.
5. O programa será compilado e executado.

### Opção 2 - Utilizando GCC/G++

É necessário ter um compilador GCC/G++ instalado e configurado no computador.

**1. Abra o terminal na pasta do projeto.**

**2. Execute o comando abaixo para compilar:**

```bash
g++ main.cpp -o HotelManager
```

**3. Para executar no Windows:**

```bash
HotelManager.exe
```

**No Linux:**

```bash
./HotelManager
```

## Menu principal

Ao executar o programa, será apresentado o seguinte menu:

```text
==============================
        HOTEL MANAGER
==============================
1. Cadastrar hospedagem
2. Consultar por codigo
3. Listar hospedagens
4. Excluir hospedagem
5. Exportar para TXT
6. Contar registros
0. Sair
------------------------------
Escolha uma opcao:
```

O usuário deverá selecionar a opção desejada e seguir as instruções apresentadas na tela.

## 👥 Projeto acadêmico

Projeto desenvolvido em equipe como atividade acadêmica, com o objetivo de aplicar conceitos de programação, estruturas de dados, funções e manipulação de arquivos.

**Repositório:** https://github.com/ldajoao/Hotel-Manager

---
