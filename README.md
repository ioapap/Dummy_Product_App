# Dummy Product React App 🛍️
This project is a simple example of how to replace Redux with alternative state management solutions such as the Context API and custom hooks ✨
## Features 🌟
- Toggling product favorites with the Context API
- Managing multiple state slices with a custom store hook
- Optimizing the custom hook store
- Demonstrating the power of the Context API and custom hooks as an alternative to Redux
## App Overview 📖
The app consists of a list of products, where each product has an ID, title, description, and favorite status. Users can toggle the favorite status of each product.

The app's state is managed using the following techniques:
1. **Context API**: We use the Context API to toggle product favorites.
2. **Custom Hook** as a Store: We create a custom hook to manage the app's store, along with a concrete store for the app's state.
3. **Optimizing the Custom Hook Store**: We optimize the custom hook store for better performance.

## What's Inside 📦
- `products.js`: The main products page, using the useSelector hook from react-redux.
- `favorites.js`: A page displaying all favorite products, also using the useSelector hook.
- `productitem.js`: A component representing each product item, using the useDispatch hook from react-redux to toggle the favorite status.
- `actions` and `reducers`: Traditional Redux approach with a single action and reducer.

## Summary 📚
This Dummy Product React App showcases alternatives to Redux, such as the Context API and custom hooks, for state management in a simple React application.