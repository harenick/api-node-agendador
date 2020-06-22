
# Agendador API

```A Rest API that helps you to manage schedules for a small company``` 🚀

# 🧰 Tools

In this project was made with:

* Nodejs
* Express
* Sequelize
* Cors
* Youp
* Youch
* Queu
* Sentry

and Postgres, MongoDB and Redis.


# 📌 Table of Contents
* [Features](#features)<br />
* [Installation](#instalation) <br />
* [Getting Started](#gs)<br />
* [FAQ](#faq)<br />
* [Found a bug? Missing a specific feature?](#bug)<br />
* [Contributing](#contrib)<br />
* [License](#license)<br />

# 🚀 Features <a name="features"></a>
* Login
* Users CRUD
* Users Scheduling 
* Users Appointmets
* Users Notifications
* Enrollments CRUD

users also are able to schedule something and the service providers given an app and email notification. 

In order to explore the others, feel free to click in the links above:


# 👷 Installation <a name="instalation"></a>
You need to install Node.js and Yarn first, then in order to clone the project via HTTPS, run this command:

``` git clone https://github.com/harenick/api-node-agendador.git```

SSH URLs provide access to a Git repository via SSH, a secure protocol. If you have a SSH key registered in your Github account, clone the project using this command:

``` git clone git@github.com:harenick/api-node-agendador.git```

# 🏃 Getting Started
Run the transactions in order to configure the database schema

``` npx sequelize-cli db:migrate```

Run the following command in order to start the application in a development environment:

``` 
// Start the server
yarn dev

// Run the queue responsable for the mail job
yarn queue-dev
```

---
Status Codes
---
API returns the following status codes in its API:

| Status Code	  | Description           |
|:---------------:|:---------------------:|
|200	          | OK                    |
|400              |	BAD REQUEST           |
|401              |	UNAUTHORIZED          |
|404              |	NOT FOUND             |
|500              |INTERNAL SERVER ERROR  |

# 📮 Faq <a name="faq"></a>
Question: What are the tecnologies used in this project?

Answer: The tecnologies used in this project are NodeJS + Express Framework to handle the server and Sequelize

# 🐛 Issues <a name="bug"></a>
Feel free to file a new issue with a respective title and description on the the Agendador API repository. If you already found a solution to your problem, i would love to review your pull request! Have a look at our contribution guidelines to find out about the coding standards.

# 🎉 Contributing <a name="contrib"></a>
Check out the contributing page to see the best places to file issues, start discussions and begin contributing.

# 📕 License
Released in 2020. This project is under the MIT license. <a name="license"></a>

## Made with love by Raphael Dias 🚀
