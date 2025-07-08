# Sistema de Cadastro (CRUD) em Linguagem C

![Linguagem C](https://img.shields.io/badge/Linguagem-C-blue.svg)

## 🚀 Sugestões de Nomes para o Repositório

Para tornar o projeto mais fácil de ser encontrado e entendido, aqui estão algumas sugestões de nomes técnicos e descritivos:

-   `crud-c-txt` (Simples e direto)
-   `sistema-cadastro-c` (Indica a finalidade de "cadastro")
-   `crud-simples-c-arquivo-txt` (Mais descritivo sobre a forma de armazenamento)
-   `gerenciador-contatos-c` (Caso seja para gerenciar contatos)
-   `controle-estoque-c-txt` (Se for um controle de estoque)

---

## 📝 Descrição do Projeto

Este projeto é um sistema simples de CRUD (Create, Read, Update, Delete) desenvolvido em linguagem C. O objetivo é demonstrar as operações básicas de manipulação de dados, utilizando um arquivo de texto (`.txt`) como forma de persistência para armazenar as informações.

Este projeto foi desenvolvido como parte da Atividade de Entrega de Bimestre (AEP) da faculdade.

## ⚙️ Principais Funcionalidades

-   **Adicionar (Create):** Permite inserir novos registros (ex: clientes, produtos, etc.) que são salvos no arquivo `dados.txt`.
-   **Listar (Read):** Exibe todos os registros atualmente salvos no arquivo.
-   **Atualizar (Update):** Permite modificar as informações de um registro existente.
-   **Excluir (Delete):** Remove um registro do arquivo.

## 💻 Tecnologias Utilizadas

-   **Linguagem:** C
-   **Compilador:** GCC (ou qualquer outro compilador C padrão)
-   **Armazenamento:** Arquivo de texto (`.txt`) para persistência de dados.

## 📁 Estrutura de Pastas e Arquivos (Exemplo)

```

/SEU-PROJETO
├── main.c
├── dados.txt
└── README.md

````

-   `main.c`: Contém todo o código-fonte da aplicação.
-   `dados.txt`: Arquivo onde os dados são salvos, criados e atualizados.
-   `README.md`: Este arquivo com a documentação do projeto.

## ▶️ Passo a Passo de Execução

Para compilar e executar o projeto, você precisará de um compilador C, como o GCC.

1.  **Clone o repositório (opcional):**
    ```bash
    git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/seu-usuario/seu-repositorio.git)
    ```

2.  **Navegue até a pasta do projeto:**
    ```bash
    cd seu-repositorio
    ```

3.  **Compile o código-fonte:**
    ```bash
    gcc main.c -o programa
    ```
    *Este comando irá gerar um arquivo executável chamado `programa`.*

4.  **Execute o programa:**
    - No Windows:
      ```bash
      programa.exe
      ```
    - No Linux/Mac:
      ```bash
      ./programa
      ```

## 💡 Exemplo de Uso

Após executar o programa, um menu interativo será exibido no terminal:

````

============================== 
|   SISTEMA DE CADASTRO      |
| 1 - Adicionar Novo Registro| 
| 2 - Listar Registros       | 
| 3 - Atualizar Registro     | 
| 4 - Excluir Registro       | 
| 0 - Sair                   |

Escolha uma opcao: 1

Digite o nome: Usuario Teste
Digite o email: teste@email.com

Registro salvo com sucesso\!

```

_Desenvolvido com ❤️ para a Atividade de Entrega de Bimestre._
```
