# PERN Stack Project: Real Time Chat App built using Postgres, TypeScript, Prisma

Techstack:

**Frontend:**  
- **React**  
  For building the user interface.  
- **Socket.io (client-side)**  
  For real-time messaging and handling WebSocket connections.  
- **TailwindCSS**  
  A utility-first CSS framework for styling components.  
- **Zustand**  
  State management library for handling global state.  

**Backend:**  
- **Node.js**  
  JavaScript runtime for server-side code execution.  
- **Express.js**  
  Web framework for building REST APIs and handling HTTP requests.  
- **PostgreSQL**  
  Relational database for storing structured data.  
- **Prisma**  
  ORM (Object Relational Mapper) for database interactions.  
- **Socket.io (server-side)**  
  For handling WebSocket connections and enabling real-time messaging.  
- **JWT (JSON Web Token)**  
  For authentication and authorization via tokens.  

**Additional Tools:**  
- **TypeScript**  
  For adding type safety to both frontend and backend code.

# Run Locally

### Setup .env file

```js
DATABASE_URL=...
JWT_SECRET=...
NODE_ENV=...
PORT=...
```

### Install dependencies

```shell
npm install
```

### Build the app

```shell
npm run build
```

### Start the app

```shell
npm start
```
