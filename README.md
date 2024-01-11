# pipeline

This project contain all pipeline configuration for selected languages and framework.

- gradle.yml -> will build and run test for gradle project
  - ./gradlew build --info
  - ./gradlew test --info
- node.yml -> will build and run test for node project
  - yarn
  - yarn test
- react.yml -> will build and run linter for react project
  - yarn && yarn build
  - yarn lint
