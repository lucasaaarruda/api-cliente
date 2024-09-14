# API-Cliente 🧑‍💼

Este projeto foi desenvolvido como parte de um curso de Django Rest Framework oferecido pela Alura. Ele implementa uma API completa para a gestão de clientes, aplicando conceitos como paginação, validação, filtros, buscas e ordenação de endpoints. O deploy da API foi feito na AWS, garantindo que o serviço esteja disponível online.

## 🚀 Sobre o Projeto

A **API-Cliente** permite a criação e manipulação de registros de clientes, incluindo informações como CPF, RG, celular, entre outros dados essenciais. A API foi desenvolvida para seguir as melhores práticas de arquitetura de projetos utilizando Django Rest Framework e inclui funcionalidades como:

- Paginação de resultados.
- Validação de dados de entrada.
- Filtros e buscas nos endpoints.
- Ordenação dos registros retornados.

O deploy foi realizado na **AWS**, garantindo que a API esteja disponível de maneira contínua.

## 💻 Tecnologias Utilizadas

### Back-end

- **Python**: Linguagem principal utilizada no desenvolvimento da API.
- **Django**: Framework utilizado para criar a estrutura do projeto.
- **Django Rest Framework**: Biblioteca utilizada para criar a API Restful, facilitando a criação de endpoints, paginação e filtros.
- **AWS**: A infraestrutura de cloud computing da Amazon foi utilizada para fazer o deploy da API.

### Bibliotecas

Além das principais ferramentas citadas, outras bibliotecas podem ser encontradas no arquivo **requirements.txt**.

## 🚀 Como Executar o Projeto

1. **Clone o Repositório:**

    ```bash
    git clone https://github.com/seu-usuario/api-cliente
    ```

2. **Instale as Dependências:**

    Certifique-se de instalar todas as dependências listadas no arquivo **requirements.txt**:

    ```bash
    pip install -r requirements.txt
    ```

3. **Execute as Migrações:**

    Para criar o banco de dados e aplicar as migrações necessárias, execute:

    ```bash
    python manage.py migrate
    ```

4. **Inicie o Servidor:**

    Para rodar a API localmente, utilize o comando:

    ```bash
    python manage.py runserver
    ```

    A API estará disponível em `http://localhost:8000`.

## 🛠️ Funcionalidades

- **Paginação**: Os resultados são paginados para melhorar a navegação pelos dados.
- **Filtros e Buscas**: Filtros e buscas foram implementados para facilitar a consulta de clientes por diferentes critérios.
- **Validação**: O sistema realiza validação de campos, como CPF e RG, garantindo a integridade dos dados inseridos.

## 📦 Deploy

A API está hospedada na **AWS**, garantindo sua disponibilidade constante.

## 🤝 Contribuições

Este projeto está aberto para melhorias e novas funcionalidades. Se você tiver sugestões ou encontrar problemas, sinta-se à vontade para abrir uma issue ou enviar um pull request.

## 📧 Contato

Para mais informações ou dúvidas, entre em contato:

- **LinkedIn:** [Lucas Ribeiro Arruda](https://www.linkedin.com/in/lucasaarruda/)

---

Obrigado por conferir o projeto! Sinta-se à vontade para contribuir e ajudar a melhorar a API.
