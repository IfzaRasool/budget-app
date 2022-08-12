
![](https://img.shields.io/badge/Microverse-blueviolet)
# Budget-app

### Description 
The Baig Budget app is a mobile web application where you can manage your budget: you have a list of transactions associated with a category, so that you can see how much money you spent and on what. built with Ruby on Rails

[Live Demo Here](https://baigbudgetapp.herokuapp.com/) view after merge


### Cloning the project

 git clone https://github.com/IfzaRasool/budget-app.git <Your-Build-Directory>
``` 
- cd Budget-app
- rails s
```


## Built with
- Ruby 3.1.2 on Rails 7.0.3.1
- PostgreSQL

## Prerequisites

Vscode or anyother
Setup

## Install
    Ruby
    Rails

### Development Database

```sh
# Create user
sudo -u postgres createuser -e ced00 -s
# Load the schema
rails db:schema:load
#----- If you want prefer this approach
# Create the database
rake db:create
# Create database Migration
rails db:migrate
```

### Run

```sh
rails s
```

## Run tests
```sh
bundle install
rspec
```

## Author

👤 **IFZA Rasool**
- GitHub: [@ifzarasool](https://github.com/IfzaRasool
- Twitter: [@ifzaarain](https://twitter.com/ifzaarain)
- LinkedIn: [@ifza-arain]https://www.linkedin.com/in/ifza-arain/

## Acknowledgment
For the desgin of this app thanks to the author of [the original design](https://www.behance.net/gallery/31579789/Ballhead-App-(Free-PSDs)) 

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](https://github.com/IfzaRasool/budget-app/issues).

## Show your support

Give a ⭐️ if you like this project!

## 📝 License

This project is [MIT](./MIT.md) licensed.
