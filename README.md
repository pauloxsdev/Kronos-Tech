# Kronos Tech 🛍️

> Trabalho de Conclusão de Curso (TCC) realizado na Escola Técnica de Ceilândia.

O **Kronos Tech** é uma aplicação web de e-commerce desenvolvida como projeto final de curso. O sistema permite que usuários naveguem por produtos, adicionem itens ao carrinho e realizem pedidos, além de contar com uma área administrativa para gestão.


## 🛠️ Tecnologias Utilizadas

O projeto foi desenvolvido utilizando as seguintes tecnologias:

* **Back-end:** PHP (Nativo)
* **Front-end:** HTML5, CSS3, JavaScript
* **Banco de Dados:** MySQL
* **Servidor Web:** Apache (via XAMPP/WAMP)

## ⚙️ Funcionalidades

- [x] Cadastro e Login de Usuários
- [x] Catálogo de Produtos (`shop.php`)
- [x] Carrinho de Compras (`cart.php`)
- [x] Checkout e Pagamento (`checkout.php`, `pagamento.php`)
- [x] Painel do Usuário (`account.php`)
- [x] Painel Administrativo (Pasta `/admin`)

## 🚀 Como rodar o projeto

Para rodar o projeto localmente, você precisará de um ambiente de servidor local como o **XAMPP** ou **WAMP**.

### Pré-requisitos

* Ter o [XAMPP](https://www.apachefriends.org/pt_br/index.html) instalado.

### Passo a passo

1.  **Clone o repositório**
    ```bash
    git clone [https://github.com/pauloxsdev/Kronos-Tech.git](https://github.com/pauloxsdev/Kronos-Tech.git)
    ```

2.  **Mova os arquivos**
    Copie a pasta do projeto para dentro do diretório do seu servidor local:
    * No XAMPP: `C:\xampp\htdocs\Kronos-Tech`

3.  **Configuração do Banco de Dados**
    * Abra o **phpMyAdmin** (geralmente em `http://localhost/phpmyadmin`).
    * Crie um novo banco de dados (verifique o nome correto no arquivo de conexão dentro da pasta `server`, provavelmente algo como `php_project` ou `kronostech`).
    * Importe o arquivo `kronostech.sql` que está na raiz deste projeto para dentro do banco criado.

4.  **Acesse o projeto**
    Abra seu navegador e digite:
    ```
    http://localhost/Kronos-Tech/index.php
    ```

## 📂 Estrutura de Pastas

* `/admin` - Arquivos da área administrativa.
* `/assets` - Imagens, CSS e JS do front-end.
* `/server` - Lógica de conexão com banco de dados e processamento backend.
* `/layouts` - Cabeçalhos e rodapés reutilizáveis.

## ✒️ Autor

* **Paulo (pauloxsdev)** - *Desenvolvimento* - [Perfil GitHub](https://github.com/pauloxsdev)

---
*Projeto desenvolvido para fins educacionais na Escola Técnica de Ceilândia.*
