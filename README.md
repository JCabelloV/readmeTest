# Grou APP Mobile (Nombre del proyecto que se almacena en el repo)

## Table of Contents

- [Description](#description)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [State Management](#state-management)
- [Testing Tools](#testing-tools)
- [Contribution](#contribution)
- [License](#license)

---

## Descripcion

Descripción breve de lo que se almacena en el repositorio, por ejemplo:

> Este repositorio contiene el código fuente de la app mobile de grou.

---

## Technologies

Ejemplo:

- **Languages:** TypeScript, HTML, CSS
- **Frameworks:** React Native
- **Testing Tools:** Jest, Cypress
- **State Management:** Redux Toolkit

---

## Installation

Instrucciones para poder configurar el proyecto de manera local

Ejemplo:

1. Clone the repository:

```bash
git clone https://github.com/repositorio-a-usar
```

2. Install dependencies:

```bash
npm install
```

3. Set up environment variables:

- Create a .env file in the root directory and add the following:

```js
API_KEY = api - key;
```

4. Start the local development server:

```bash
npm start
```

---

## Usage

Explicar como usar el proyecto despues de la instalacion

Ejemplo:

- Run the project in development mode:

```bash
npm start
```

- Build for production:

```bash
npm run build
```

---

## Project Structure

Explicacion basica de la estructura de carpetas del proyecto

Ejemplo:

```perl
src/
├── components/        # Reusable components
├── pages/             # Main pages
├── state/             # State management (e.g., Redux slices)
├── tests/             # Unit and integration tests
├── services/          # API call logic
├── utils/             # Helper functions
├── assets/            # Images, icons, and static files
├── App.js             # Main application configuration
```

---

Explicar brevemente las herramientas usadas, por ejemplo las de control de estado y testing

Ejemplo:

## State Management

The project uses [Redux Toolkit](https://redux-toolkit.js.org/) for state managemente, enable structures state handling.

```javascript
import { configureStore } from "@reduxjs/toolkit";
import parentalControlReducer from "./parentalControlSlice";

export const store = configureStore({
  reducer: {
    parentalControl: parentalControlReducer,
  },
});
```

---

## Testing Tools

The following tools are used for testing:

- [Jest](https://jestjs.io/): For unit test.
- [Cypress](https://www.cypress.io/): For end-to-end testing.

To run test:

```bash
npm test
```

To run end-to-end test:

```bash
npx cypress open
```

---

## Contribution

Explicacion sobre el uso de los pull request

Ejemplo:

Follow these steps to add your changes to the project:

1. Fork the respository.
2. Create a new branch for your changes.

```bash
git checkout -b feature/my-new-feature
```

3. Make your changes and write clear commit messages:

```bash
git commit -m "Added new features"
```

4. Push your changes to your fork:

```bash
git push origin feature/my-new-feature
```

5. Open a Pull request to te `main` or `develop` branch

- Use our [Pull Request Template] and provide all required information

6. Wait for review. Address any comments and make adjustments if necessary
7. Once approved, your PR will be merged by the team

**Make sure to review the coding standards and run linters before submitting your PR.**
