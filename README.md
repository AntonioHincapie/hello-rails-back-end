# Hello Rails Back-end API

Now that you're familiar with Rails and React, it's time to put them together in a new kind of 'Hello World!' app. This exercise is going to have you create a React front-end with a Rails back-end and connect them to display a random message.

## Front-end Repo

- [Link to front-end repo](https://github.com/AntonioHincapie/hello-react-front-end)

## Built With

- Ruby on Rails
- PostgreSQL

### Prerequisites

- Ruby ruby-3.1.2 installed
- PostgreSQL dbms running

### Setup

- Clone repository.

- bundle install.

- bundle exec figaro install (to create environment variables)

- Edit file application.yml

  - Provide the values for the variables
    - DATABASE_HOST
    - DATABASE_USER
    - DATABASE_PASSWORD

- rails db:create.

- rails db:migrate.

### Run app

- First run this rails server before run the front-end react-app.

  - rails server

## Author

## 👤 **Marco Antonio Hincapié Montes**

- GitHub: [@AntonioHincapie](https://github.com/AntonioHincapie)

- Twitter: [@MarcoHincapie](https://twitter.com/MarcoHincapie)

- LinkedIn: [LinkedIn](https://www.linkedin.com/in/antoniohincapie/)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments

- [Curriculum-Microverse](https://github.com/microverseinc/curriculum-rails/blob/main/connect-frontend-frameworks/hello_world_two_apps.md) from Microverse.

## 📝 License

This project is [MIT](./LICENSE) licensed.
