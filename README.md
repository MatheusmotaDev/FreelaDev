# FreelaDev

**FreelaDev** é uma plataforma que conecta desenvolvedores freelancers a empresas e indivíduos com projetos de desenvolvimento de software.

A plataforma permite:
- Publicação de projetos em andamento.
- Propostas de desenvolvedores baseadas em horas de trabalho mensal.
- Transparência e facilidade na comunicação entre freelancers e clientes.

## 📜 Features

- **Publicação de Projetos**: Clientes podem publicar detalhes sobre seus projetos e as habilidades necessárias.
- **Propostas de Freelancers**: Desenvolvedores podem enviar propostas de trabalho com valores baseados em horas mensais.
- **Gestão de Projetos**: Acompanhe o andamento de projetos e propostas em uma interface simples e direta.


## 🚀 Tecnologias Utilizadas

- **Backend**: [Laravel](https://laravel.com/) (PHP Framework)
- **Frontend**: [Blade](https://laravel.com/docs/9.x/blade) (Template engine do Laravel), [Tailwind CSS](https://tailwindcss.com/) para estilização
- **Banco de Dados**: [MySQL](https://www.mysql.com/)
- **Hospedagem**: AWS EC2 (Elastic Compute Cloud)


## 🛠️ Instalação e Execução

1. Clone este repositório:
    ```bash
    git clone https://github.com/MatheusmotaDev/freeladev.git
    ```

2. Navegue até o diretório do projeto:
    ```bash
    cd freeladev
    ```

3. Instale as dependências do projeto:
    ```bash
    composer install
    npm install
    ```

4. Configure o arquivo de ambiente `.env`:
    - Copie o arquivo `.env.example` e renomeie para `.env`:
      ```bash
      cp .env.example .env
      ```
    - Atualize as variáveis do arquivo `.env` com suas credenciais do MySQL e outras configurações (como as credenciais da AWS, se necessário).

5. Gere a chave da aplicação:
    ```bash
    php artisan key:generate
    ```

6. Execute as migrações para criar as tabelas no banco de dados:
    ```bash
    php artisan migrate
    ```

7. Inicie o servidor local:
    ```bash
    php artisan serve
    npm run dev
    ```

8. Acesse a aplicação em `http://localhost:8000`.



## ⚖️ Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

## 🤝 Contribuições

Contribuições são bem-vindas! Se você quiser ajudar a melhorar o **FreelaDev**, siga os passos abaixo:

1. Faça um **fork** do projeto.
2. Crie uma **branch** para sua feature:
    ```bash
    git checkout -b minha-feature
    ```
3. Faça o **commit** das suas alterações:
    ```bash
    git commit -m 'Minha nova feature'
    ```
4. Envie para o repositório original:
    ```bash
    git push origin minha-feature
    ```
5. Abra um **Pull Request**.

## 📧 Contato

Se tiver dúvidas ou sugestões, sinta-se à vontade para entrar em contato:  
**Email**: [matheusmota.webdev@gmail.com](mailto:matheusmota.webdev@gmail.com)


