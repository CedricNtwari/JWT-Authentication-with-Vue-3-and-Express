# JWT Authentication with Vue 3 and Express

A minimalistic project to demonstrate secure user authentication using JSON Web Tokens (JWT). This application showcases the following features:

- **User Registration:** A simple sign-up process with client-side form validation.
- **User Login:** Secure login flow with token generation upon successful authentication.
- **Token-Based Authentication:** Using JWT to protect sensitive routes and ensure secure access.
- **User Data Recovery:** Fetch user details for authenticated sessions.
- **Logout Functionality:** Efficient token invalidation to log out users securely.
- **Express.js Integration:** Backend implementation with Node.js and Express.js for API creation.
- **Responsive Frontend:** Clean UI for registration and login forms.

## Key Technologies

- **Frontend:** Vue.js (with reusable components)
- **Backend:** Node.js and Express.js
- **Authentication:** JSON Web Tokens (JWT)
- **Validation:** Form validation for user input
- **Environment:** Developed and tested with modern web technologies

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur).

## Type Support for `.vue` Imports in TS

TypeScript cannot handle type information for `.vue` imports by default, so we replace the `tsc` CLI with `vue-tsc` for type checking. In editors, we need [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) to make the TypeScript language service aware of `.vue` types.

## Customize configuration

See [Vite Configuration Reference](https://vite.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Type-Check, Compile and Minify for Production

```sh
npm run build
```

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```

## Usage

This project is designed as a learning resource for developers interested in understanding the fundamentals of JWT-based authentication in a full-stack application. It is also an excellent starting point for implementing similar authentication systems in production-grade projects.
