## About The Project
This project consists of UI testing and API testing. I use Cypress to build test automation framework. I also introduce POM and DDT into this design. I utilize Postman to test API automatically by loading testdata stored in a file.

__jobadder-1__ (project folder) <br/>
&ensp;&ensp;__|--fixtures__（folder）<br/>
&ensp;&ensp;&ensp;&ensp;|--products.json（testdata file）<br/>
&ensp;&ensp;__|--integration__（folder）<br/>
&ensp;&ensp;&ensp;&ensp;|--ui_autotest.spec.js（test file）<br/>
&ensp;&ensp;__|--PageObject__（folder）<br/>
&ensp;&ensp;&ensp;&ensp;|--CartPage.js（cart page file）<br/>
&ensp;&ensp;&ensp;&ensp;|--LoginPage.js（login page file）<br/>
&ensp;&ensp;&ensp;&ensp;|--ProductsPage.js（products page file）<br/>
&ensp;&ensp;__|--API_Auto__（folder）<br/>
&ensp;&ensp;&ensp;&ensp;|--jobadder.postman_collection.json（postman collection file）<br/>
&ensp;&ensp;&ensp;&ensp;|--jobadder_API_testdata.txt（API testdata file）<br/>
&ensp;&ensp;|--ReadMe.md（self discription file）<br/>
&ensp;&ensp;|--cypress.json (cypress configuration file) <br/>



### Built With
* Cypress
* POM
* DDT
* Postman

## Getting Started


### Prerequisites
You need to install some software in your local computer

* Cypress
* Postman

### Installation
Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services.

1. Get a free API Key at https://example.com
2. Clone the repo
3. git clone https://github.com/your_username_/Project-Name.git
Install NPM packages
npm install
Enter your API in config.js
const API_KEY = 'ENTER YOUR API';
