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
You need to install some software in your local computer. My computer's OS is windows 7.

* Cypress
* Node.js
* Postman

### Installation

__UI automation:__
1. download all folders and file to your local computer.<br/>
   open Git Bash and execute command: git clone https://github.com/DanielXu1978/jobadder-1.git 
2. find cypress.json under your cypress installation path like "E:\Cypress\node_modules\.bin" and modify it referring to my cypress.json.  <br/>
  for example, in my computer the project path is E:/jobadder-1/
  "integrationFolder": "E:/jobadder-1/integration",
	"fixturesFolder": "E:/jobadder-1/fixtures"
3. launch Cypress Studio
  open cmd terminal and execute command "cypress open". For example, "E:\Cypress\node_modules\.bin" is the cypress installation path
  E:\software\Cypress\node_modules\.bin>cypress open
4. the cypress studio lists the test file "ui_autotest.spec.js" in the folder "integration"
  click the file and lunch Test Runner to execute test
 
__API automation:__
1. open Postman
2. import jobadder.postman_collection.json from folder "API_Auto"
3. select this collection and click "Run Collection"
4. set parameters "Delay" and "Data"
  Delay: 20 or other values
  Data: you can select the file "jobadder_API_testdata.txt" from folder "API_Auto"
  
5. click run 
