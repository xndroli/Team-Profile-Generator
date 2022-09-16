<a name="readme-top"></a>

<h3 align="center">OOP: Team Profile Generator </h3>

<div align="center">

[![Node.js](https://img.shields.io/badge/nodejs-yellow.svg)](https://nodejs.org/)

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![Repo Size](https://img.shields.io/github/repo-size/xndroli/Team-Profile-Generator.svg)](https://github.com/xndroli/Team-Profile-Generator/issues)
[![GitHub Issues](https://img.shields.io/github/issues/xndroli/Team-Profile-Generator.svg)](https://github.com/xndroli/Team-Profile-Generator/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/xndroli/Team-Profile-Generator.svg)](https://github.com/xndroli/Team-Profile-Generator/pulls)

</div>

---

## 🔗 Description <a name = "description"></a>

This week, I'll build a Node.js command-line application that takes in information about employees on a software engineering team and generates an HTML webpage that displays summaries for each person. Because testing is key to making code maintainable, I will also write unit tests for each part of my code and ensure that it passes all of them.

Because this application is not deployed, I will also provide a link to a walkthrough video that demonstrates its functionality and all of the tests passing.

[Link to Demo]()

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 📝 Table of Contents

- [Description](#description)
- [User Story](#user_story)
- [Acceptance Criteria](#acceptance_criteria)
- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [Technology](#built_with)
- [Authors](#authors)
- [Contributing](../CONTRIBUTING.md)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 💡 User Story <a name = "user_story"></a>

```md
AS A manager
I WANT to generate a webpage that displays my team's basic info
SO THAT I have quick access to their emails and GitHub profiles
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## ⛓️ Acceptance Criteria <a name = "acceptance_criteria"></a>

```md
GIVEN a command-line application that accepts user input
WHEN I am prompted for my team members and their information
THEN an HTML file is generated that displays a nicely formatted team roster based on user input
WHEN I click on an email address in the HTML
THEN my default email program opens and populates the TO field of the email with the address
WHEN I click on the GitHub username
THEN that GitHub profile opens in a new tab
WHEN I start the application
THEN I am prompted to enter the team manager’s name, employee ID, email address, and office number
WHEN I enter the team manager’s name, employee ID, email address, and office number
THEN I am presented with a menu with the option to add an engineer or an intern or to finish building my team
WHEN I select the engineer option
THEN I am prompted to enter the engineer’s name, ID, email, and GitHub username, and I am taken back to the menu
WHEN I select the intern option
THEN I am prompted to enter the intern’s name, ID, email, and school, and I am taken back to the menu
WHEN I decide to finish building my team
THEN I exit the application, and the HTML is generated
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🎞️ Demo <a name = "demo"></a>

As you can see in the following animation, a user can type a search term (in this case, "star wars") in a search box and the results appear:

[![OOP: Team Profile Generator](./assets/images/googlebooks-app-demo-01.gif)](https://github.com/xndroli/Team-Profile-Generator/)

[Link to Demo]()

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🏁 Getting Started <a name = "getting_started"></a>

Clone the repo by running:

`git clone https://github.com/xndroli/Team-Profile-Generator.git`

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### 💾 Installation <a name = "installation"></a>

Input basic project information in include in your package by running:

`npm init`

Install the package, and any packages that it depends on by running:

`npm install`

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 💻 Usage <a name="usage"></a>

Run the following command at the root of your project:

`node index.js`

Follow the command line prompts to the end. Then check the dist folder for the generated index.html.

If the index.html successfully generated, open it and hit:

`Alt+L Alt+O`

to open the generated HTML in your browser.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## ⛏️ Built With <a name = "built_with"></a>

- [MongoDB](https://www.mongodb.com/) - Database
- [Mongoose.js](https://mongoosejs.com/) - Object Data Modeling
- [Express.js](https://expressjs.com/) - Server Framework
- [React.js](https://reactjs.org/) - Front End Library
- [Node.js](https://nodejs.org/) - Server Environment

- [GraphQL](https://graphql.org/) - Data Query and Manipulation
- [Apollo Server](https://www.apollographql.com/) - GraphQL Server
- [Heroku](https://www.heroku.com/) - Platform As A Service (PaaS)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## ✍️ Authors <a name = "authors"></a>

- [@xndroli](https://github.com/xndroli)

See also the list of [contributors](https://github.com/xndroli/Team-Profile-Generator/contributors) who participated in this project.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

© 2022 xndroli. All Rights Reserved.
