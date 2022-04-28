
## NESP-project

#### About:

- [NESP project](https://github.com/Arakel2811/nesp)
- [Published Postman collection URL](https://documenter.getpostman.com/view/12515029/UyrEhvGp)

> Blog-like API for testing purposes.
> Features:
> - Users JWT authentication
> - Categories
> - Posts CRUD
> - Tags CRUD
> - Post-Tag relationship

#### Stack:

- NodeJS
- Express
- Sequelize
- PostgreSQL

#### Requirements

- NPM with NodeJS (or Nginx server) installed
- PostgreSQL installed

#### Installation:

- Create DB

- Run following commands
```
git clone <REPO> project
cd project/
npm i
```

- [Optional] Use the exported Postman API collection (v2.1) for testing.

- Create .env file inside your project root folder, and define required variables as described in .env.example

- Run migrations and seeds
```
sequelize db:migrate:undo:all
sequelize db:migrate
sequelize db:seed:all

# in one-line command
sequelize db:migrate:undo:all; sequelize db:migrate; sequelize db:seed:all
```

- Run the app
```
# for development
npm run dev
# for production
npm start
```

#### Author:

- [LinkedIn profile](https://www.linkedin.com/in/arakel-galeyan/)
