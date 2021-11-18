## About The Project
This project consists of UI testing and API testing. I use Cypress to build test automation framework. I also introduce POM and DDT into this design. I utilize Postman to test API automatically by loading testdata stored in a file.

jobadder-1 (project folder) <br/>
&ensp;&ensp;|--fixtures（folder）<br/>
&ensp;&ensp;&ensp;&ensp;|--products.json（testdata file）<br/>
&ensp;&ensp;|--integration（folder）<br/>
&ensp;&ensp;&ensp;&ensp;|--ui_autotest.spec.js（test file）<br/>
&ensp;&ensp;|--PageObject（folder）<br/>
&ensp;&ensp;&ensp;&ensp;|--CartPage.js（cart page file）<br/>
&ensp;&ensp;&ensp;&ensp;|--LoginPage.js（login page file）<br/>
&ensp;&ensp;&ensp;&ensp;|--ProductsPage.js（products page file）<br/>
&ensp;&ensp;|--ReadMe.md（self discription file）<br/>
&ensp;&ensp;|--cypress.json (cypress configuration file)
### Built With
This section should list any major frameworks/libraries used to bootstrap your project. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.

* Next.js
* React.js
* Vue.js

## Getting Started
This is an example of how you may give instructions on setting up your project locally. To get a local copy up and running follow these simple example steps.

### Prerequisites
This is an example of how to list things you need to use the software and how to install them.

* npm
* npm install npm@latest -g
### Installation
Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services.

1. Get a free API Key at https://example.com
2. Clone the repo
3. git clone https://github.com/your_username_/Project-Name.git
Install NPM packages
npm install
Enter your API in config.js
const API_KEY = 'ENTER YOUR API';
