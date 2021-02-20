# Use TypeScript to Create a Secure API with Node.js and Express

[Securing the API](https://auth0.com/blog/use-typescript-to-create-a-secure-api-with-nodejs-and-express-adding-authentication-authorization/)

[Role-Based Access Control](https://auth0.com/blog/use-typescript-to-create-a-secure-api-with-nodejs-and-express-adding-role-based-access-control/)

## Setup

```bash
cd express-api-auth0
```

- Install the project dependencies:

```bash
npm i
```

- Create a `.env` hidden file:

```bash
touch .env
```

- Populate `.env` with your Auth0 information:

```bash
PORT=7000
AUTH0_ISSUER=https://dev-ha2csa52.us.auth0.com/
AUTH0_AUDIENCE=https://menu-api.danny.com
```

- Start webpack Hot-Module Replacement (HMR):

```bash
npm run webpack
```

- Start the Express server:

```bash
npm start
```
