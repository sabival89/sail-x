<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo_text.svg" width="320" alt="Nest Logo" /></a>
  <a href="http://nestjs.com/" target="blank"><img src="https://www.svgrepo.com/show/303500/react-1-logo.svg" width="320" alt="React Logo" /></a>
</p>


[circleci-image]: https://img.shields.io/circleci/build/github/nestjs/nest/master?token=abc123def456
[circleci-url]: https://circleci.com/gh/nestjs/nest

[circleci-image]: https://camo.githubusercontent.com/787ba2bfb6fea1ec9110055cdfd71b89e05ccbe7aa2730913a40efa2aa5c0e6b/68747470733a2f2f6372656174652d72656163742d6170702e6465762f696d672f6c6f676f2e737667](https://www.google.com/url?sa=i&url=https%3A%2F%2Ficonscout.com%2Ffree-icon%2Freact-1&psig=AOvVaw2sz5vwskKJl3M-HFb4lln_&ust=1713672140967000&source=images&cd=vfe&opi=89978449&ved=0CBIQjRxqFwoTCMjY34L1z4UDFQAAAAAdAAAAABAE)



# Description

### Tasks
- ❌ Due to time constraints, I was unable to implement the functionality for users to search for stock tickers and view real-time prices, execute trades, and compile a portfolio with personalized performance metrics and overall portfolio returns.
- ✅ While I successfully developed the backend service to retrieve Alpha and calculate historical prices, I also implemented its integration with the frontend to fetch and display this data to users.

- `Frontend`: Using ReactJS for the front end is an excellent choice due to its component-based architecture, declarative syntax, and robust ecosystem of libraries and tools for building user interfaces. React allows for efficient rendering and state management, crucial for a dynamic trading application.
- `Backend`:  NestJS provides a scalable and maintainable framework for building efficient and modular server-side applications with TypeScript. It leverages the power of Express.js under the hood while providing a higher level of abstraction and structure.

### In this architecture:
![image](https://github.com/sabival89/sail-x/assets/2057169/889bfc9e-853f-4791-862f-895c2fffc7b6)

- `ReactJS` interacts with the NestJS backend to fetch real-time stock prices, execute trades, and manage user portfolios.
- `NestJS` handles business logic, data processing, and communication with external APIs such as IEX Cloud and brokerage services.
- `PostgreSql` PostgreSQL stores user portfolios and transaction data securely. ❌ Not Implemented
- `Docker` I containerized the application using Docker, which ensures portability, scalability, isolation, and easy deployment. It encapsulates each component within its container, providing consistent behaviour across environments and enabling horizontal scaling. This approach simplifies management and updates, making the application more resilient and easier to maintain.


 #### Frameworks
  - [Nest](https://github.com/nestjs/nest) framework `BACK-END`.
  - [React](https://github.com/facebook/react) framework `FRONT-END`.


 #### Languages
  - [Typescript](https://www.typescriptlang.org/)
  - CSS
  - HTML

 #### Relevant Libraries
 - [Swagger](https://swagger.io/)
 - TailwindCss
 - Twin.Macro
 - React Datepicker

## Running the app
You can choose to run the app via `npm` or `Docker`
- [API Repo](https://github.com/sabival89/sail-x-api)
- [Front End Repo](https://github.com/sabival89/sail-x-portal)


```bash
# using npm
$ npm run start

# using docker
$ docker-compose up
```

## Using the app
#### Swagger Api Documentation
   - On your web browser, navigate to `http://localhost:3000/api`
   - > If you chose to run the app using `Docker`, please navigate to `http://localhost:3001/api` instead.
```

