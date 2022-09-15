![](https://img.shields.io/badge/Microverse-blueviolet)

## Recipe-App
The Recipe app keeps track of all your recipes, ingredients, and inventory. It will allow you to save ingredients, keep track of what you have, create recipes, and generate a shopping list based on what you have and what you are missing from a recipe. Also, since sharing recipes is an important part of cooking the app should allow you to make them public so anyone can access them.

##  Built with
- Rails
- Ruby
- HTML & CSS

##  Set up
This README documents steps necessary to get the application up and running.

* Ruby version
  - 2.7.4
* PSQL version
  - PostgreSQL 14.0

* System dependencies
  - See [Dependencies](./Gemfile) gem file

* Configuration
  - Install ruby  - [Installation guides](https://www.ruby-lang.org/en/documentation/installation/)
  - install PostgreSQL - [Installation guides](https://www.postgresql.org/download/linux/)
  - install libpqdev ``` sudo apt install libpq-dev  ``` (linux)
  - Make sure your Postgresql is running. If not, start the service by typing ```sudo service postgresql start``` in your terminal (linux)

* Installation 
  - ```git clone``` this [repo](https://github.com/Smart1-hub/blog)
  - Run:
    - ```cd blog-app```
    - ```bundle install```
  
* Database creation
  - Run
       - ```rake db:create```

* Tests
  - Run (*ensure your postgreSQL is running as well*)
      - Integrations
        - **Method 1:** ```bundle exec rspec test/integration/ ```
        > if fails, try
        - **Method 2:**  ```rspec test/integration/```

* Run project
  - ```rails db:migrate:reset db:seed``` then
  - Run ```rails s``` and visit [http://localhost:3000/](http://localhost:3000/) in your browser!

## Authors
👤 **Ademola Adebaya**

- Github: [@Smart1-hub](https://github.com/Smart1-hub)
- Twitter: [@ademola_adebayo](https://twitter.com/ademola_adebayo)
- LinkedIn: [Ademola Adebayo](https://www.linkedin.com/in/ademola-adebayo-81051578/)

👤 **Yusuf Nviiri**
- GitHub: [@yusufnviiri](https://github.com/yusufnviiri)
- Twitter: [@YNviiri](https://twitter.com/YNviiri)
- LinkedIn: [yusufnviiri]( https://www.linkedin.com/in/yusuf-nviiri-8b4146206/)

## Acknowledgement

- Microvers Org.

## Contributing

Contributions, issues, and feature requests are welcome!

## Show your support

Give a ⭐ if you like this project and how it is built!


## 📝 License

This project is [MIT](https://github.com/microverseinc/readme-template/blob/master/MIT.md) licensed.