# pipeline

This project contain all pipeline configuration for the server and client

## server

- ci.yml -> will build and run test for gradle project
  - ./gradlew build --info
  - ./gradlew test --info
- node.yml -> will build and run test for node project
  - npm install
  - npm run test

## client

- react.yml -> will build and run linter for react project
  - yarn && yarn build
  - yarn lint
- typescript.yml -> will build and run test for typescript project
  - yarn
  - yarn test
