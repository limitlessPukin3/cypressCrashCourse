# Cypress Crash Course

This repo contains three projects that can be used to introduce the Cypress framework

## Installation
git clone this repo

For Project 1
```bash
cd project-1 && npm install
npm start
```

For Project 2
To start client
```bash
cd project-2/client && npm install
npm start
```

To start server
```bash
cd project-2/server && npm install
node index.js
```

## Launching Cypress
For Project 1
```bash
cd project-1 && npx cypress open
```

For Project 2
```bash
cd project-2/client && npx cypress open
```

## How to generate single reprots for all test suite
Launch web application before 
```bash
cd project-1
npx cypress run
npm run merge
npm run generate_mochawesome_report
```
Single report will be located in : project-1/cypress/report/output.html