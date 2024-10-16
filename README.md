<p align="center">
    <a href="https://laravel.com" target="_blank">
        <img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo">
    </a>
</p>

# Torneio y Torneio

Este é um projeto de criação de torneios desenvolvido em Laravel, utilizando Vue.js com Inertia.js para a renderização do lado do servidor (SSR) e Tailwind CSS para o design.

## Sobre o Projeto

O **Torneio y Torneio** permite que os usuários criem, gerenciem e participem de torneios online de forma simples e intuitiva. Este aplicativo é ideal para organizadores de torneios e jogadores que desejam se conectar e competir.

### Funcionalidades

- Criação e gerenciamento de torneios
- Registro de jogadores
- Acompanhamento de partidas
- Painel de controle intuitivo
- Suporte para diferentes formatos de torneios

## Tecnologias Utilizadas

- **Laravel**: Framework PHP para desenvolvimento web.
- **Vue.js**: Biblioteca JavaScript para construção de interfaces de usuário.
- **Inertia.js**: Permite criar aplicativos de página única (SPA) usando Laravel e Vue.
- **Tailwind CSS**: Framework CSS para estilização responsiva.
- **PHPUnit**: Ferramenta de testes para garantir a qualidade do código.

## Instalação

Para instalar e executar este projeto, siga os passos abaixo:

1. Clone o repositório:
    ```bash
    git clone https://github.com/UltraGalaxyBro/torneio-y-torneio.git
    ```

2. Navegue até o diretório do projeto:
    ```bash
    cd torneio-y-torneio
    ```

3. Instale as dependências do projeto:
    ```bash
    composer install
    npm install
    ```

4. Crie um arquivo `.env` baseado no arquivo `.env.example` e configure suas variáveis de ambiente.

5. Execute as migrações do banco de dados:
    ```bash
    php artisan migrate
    ```

6. Inicie o servidor de desenvolvimento:
    ```bash
    php artisan serve
    ```

7. Acesse o aplicativo em `http://localhost:8000`.

## Contribuição

Contribuições são bem-vindas! Se você deseja contribuir, por favor, siga as diretrizes de contribuição.

## Licença

Este projeto é licenciado sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
