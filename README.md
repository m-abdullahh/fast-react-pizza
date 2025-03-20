# Fast React Pizza

## Introduction

Fast React Pizza is a simple pizza ordering application developed to learn and practice Redux. This project demonstrates how Redux can be used to manage the state of a React application efficiently. The app allows users to browse a menu, add pizzas to their cart, and place an order.

## Features

- Browse a list of pizzas with details.
- Add or remove pizzas from the cart.
- View the total price of the order.
- Place an order.

## Technologies and Libraries Used

- **React**: For building the user interface.
- **Redux**: For state management, including actions, reducers, and the Redux store.
- **React-Redux**: To connect Redux with React components.
- **Redux Toolkit**: To simplify Redux setup and development.
- **React Router**: For navigation and routing between pages.
- **CSS Modules**: For styling components in a modular way.

## How Redux is Used

1. **Store**: The global state of the app is managed in a Redux store.
2. **Actions**: Actions are dispatched to indicate user interactions, such as adding a pizza to the cart.
3. **Reducers**: Reducers handle the actions and update the state accordingly.
4. **Selectors**: Selectors are used to retrieve specific pieces of state from the store.
5. **Middleware**: Middleware like Redux Thunk can be added for handling asynchronous operations (if needed).

## Getting Started

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/fast-react-pizza.git
    ```
2. Install dependencies:
    ```bash
    npm install
    ```
3. Start the development server:
    ```bash
    npm start
    ```

## Future Improvements

- Add user authentication.
- Implement order history.
- Add animations for a better user experience.

Feel free to explore the code and customize it to your needs. Happy coding!