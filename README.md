# ozo

Documents
Get Started and Demos

For development (Uncompressed)
You can download the uncompressed files for development

Latest : https://naver.github.io/egjs-agent/release/latest/dist/agent.js
Specific version : https://naver.github.io/egjs-agent/release/[VERSION]/dist/agent.js

$ npm install @egjs/agent
Supported Browsers
The following are the supported browsers.

Internet Explorer	Chrome	Firefox	Safari	iOS	Android
7+	latest	latest	latest	3+	2.1+
How to start developing egjs-agent?
For anyone interested to develop egjs-agent, follow the instructions below.

Development Environment
1. Clone the repository
Clone the egjs-agent repository and install the dependency modules.

# Clone the repository.
$ git clone https://github.com/naver/egjs-agent.git
2. Install dependencies
npm is supported.

# Install the dependency modules.
$ npm install
3. Build
Use npm script to build eg.agent

# Run webpack-dev-server for development
$ npm start

# Build
$ npm run build

# Generate jsdoc
$ npm run jsdoc
Two folders will be created after complete build is completed.

dist folder: Includes the agent.js and agent.min.js files.
doc folder: Includes API documentation. The home page for the documentation is doc/index.html.
Linting
To keep the same code style, we adopted ESLint to maintain our code quality. The rules are modified version based on Airbnb JavaScript Style Guide. Setup your editor for check or run below command for linting.

$ npm run lint
Test
Once you created a branch and done with development, you must perform a test running npm run test command before you push code to a remote repository.

$ npm run test
Running a npm run test command will start Mocha tests via Karma-runner.

Bug Report
If you find a bug, please report it to us using the Issues page on GitHub.
