# Fastify-Prisma-Nexus-GraphQL-Jest Boilerplate

Jumpstart your next GraphQL project with this powerful and flexible boilerplate, which combines Fastify, Prisma, Nexus, and Jest! This project is designed to make it easy for developers to create high-performance GraphQL servers with minimal setup and configuration.

## Requirements

To use this boilerplate, you'll need the following:

- Node.js v19.6.1 or later
- PostgreSQL (for the database)
- Yarn (recommended) or npm

Check the `engines` and `dependencies` sections in the `package.json` for the specific versions of required packages.

## Installation

Follow these steps to set up the project:

1. Clone the repository: `git clone https://github.com/yourusername/fastify-prisma-nexus-graphql-jest.git`
2. Change to the project directory: `cd fastify-prisma-nexus-graphql-jest`
3. Install dependencies: `yarn install` or `npm install`
4. Set up environment variables by creating a `.env` file in the project root, based on the provided `.env.example` file.
5. Update the `prisma/schema.prisma` file with your database connection details.
6. Run database migrations: `yarn migrate:dev` or `npm run migrate:dev`
7. Start the development server: `yarn dev` or `npm run dev`

Now you're ready to build your next amazing GraphQL server!
## Features

This boilerplate comes packed with a variety of features to help you kickstart your GraphQL server:

### Authentication

The project includes built-in authentication using Fastify, Passport, and bcryptjs. You can easily integrate your preferred authentication provider or extend the current implementation to suit your needs.

### Migration

Effortlessly manage your database schema using Prisma migrations. This boilerplate includes scripts for running, resetting, and deploying migrations, ensuring that your database schema remains in sync with your code.

## Use Cases

This boilerplate is perfect for projects that require a GraphQL API with a robust set of features, such as:

- Full-stack web applications
- Mobile applications
- Microservices

The template includes sample code for the following models:

- Users
- Tasks
- Comments
- UserTasks
- TaskRoles

You can use these sample models as a starting point for your application or modify them to fit your specific requirements.

## Sample Schema

The boilerplate comes with a sample schema that demonstrates how to define your GraphQL types and resolvers using Nexus. This schema covers the models listed above and includes relationships between them. You can easily customize the schema to match your application's needs.

## Seeding Data into Production

To bootstrap your production database with initial data, you can use the provided seed file. This file can be found in the `prisma/seed.ts` directory. Modify it to include your desired seed data and run the `db:push` script to populate your production database.
## Test

The boilerplate includes a comprehensive testing setup using Jest. You'll find sample tests for the included models in the `tests` directory. These tests cover various aspects of the application, such as resolvers, middleware, and utility functions. To run the tests, simply execute the `test` or `test:all` script.

## Test Coverage

Keep track of your project's test coverage with Jest's built-in coverage reporting. The boilerplate is pre-configured to generate coverage reports when running the tests. You can view the coverage report in the `coverage` directory after running the tests.

## Contributing

We welcome contributions to this open-source boilerplate! If you have any ideas or suggestions, please feel free to open an issue or submit a pull request. We'll review your changes and work with you to ensure that this boilerplate remains a top choice for developers building Fastify GraphQL servers.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more information.

## Acknowledgments

We'd like to thank the developers and maintainers of Fastify, Prisma, Nexus, GraphQL, and Jest for their excellent work on these libraries. This boilerplate wouldn't be possible without their efforts.
