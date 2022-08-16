# DSMovie

[![NPM](https://img.shields.io/npm/l/react)](https://github.com/santosediego/dsmovie/blob/main/LICENSE) 
[![Netlify Status](https://api.netlify.com/api/v1/badges/80359c2e-8149-42d0-b7ec-36e0b30632c0/deploy-status)](https://app.netlify.com/sites/dsmoviediegosantos/deploys)

## Sobre o projeto

DSMovie é uma aplicação web construída durante o evento Semana Spring React da Devsuperior. A aplicação lista filmes e dá a capacidade do usuário dar uma
nota. Também é demostrado em tela a média da nota daquele filme.

## Layout
<section align="center">
  <img src="https://raw.githubusercontent.com/santosediego/assets/main/dsmovie/dsmovieHomeDesktop.png" width="825" alt="Página principal">
  <img src="https://raw.githubusercontent.com/santosediego/assets/main/dsmovie/dsmovieFormMobile.jpg" width="200" alt="Formulário de voto vizualizado por smartphone">
</section>

## Tecnologias utilizadas
### Back end
- Java
- Spring Boot
- JPA / Hibernate
- Maven
### Front end
- HTML / CSS / TypeScript / Bootstrap
- ReactJS
- React-toastify
- Axios

## Implantação em produção
- Back end: Heroku
- Front end: Netlify
- Banco de dados: PostgreSQL

## Como executar o projeto

### Back end
Pré-requisito: Java 17

```bash
# clonar repositório
git clone https://github.com/santosediego/dsmovie.git

# entrar na pasta do projeto back end
cd dsmovie/backend/

# executar o projeto (por padrão será executado com perfil de teste)
./mvnw spring-boot:run
```

### Front end
Pré-requisitos: 
- npm / yarn
- Back end em execução

```bash
# clonar repositório
git clone https://github.com/santosediego/dsmovie.git

# entrar na pasta do projeto front end web
cd dsmovie/frontend/

# instalar dependências
yarn

# executar o projeto
yarn start
```

## Autor

[Diego Santos](https://www.linkedin.com/in/santosediego/ "Perfil Linkedin Diego Santos")

