## About The Project
This project consists of UI testing and API testing. I use Cypress to build test automation framework. I also introduce POM and DDT into this design. I utilize Postman to test API automatically by loading testdata stored in a file.

Test_framework
    |--config（配置文件）
    |--data（数据文件）
    |--drivers（驱动）
    |--log（日志）
    |--report（报告）
    |--test（测试用例）
    |--utils（公共方法）
    |--src（main函数）
    |--ReadMe.md（自述说明性文件，框架所需要的环境及用法）

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
