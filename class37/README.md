## Combined Redux :

1. **Why create multiple reducers?**
   In Redux, multiple reducers are created to manage different parts of the application's state separately. This helps organize and modularize the state management logic, making the codebase more maintainable and scalable. Each reducer focuses on a specific slice of the overall state, which makes it easier to reason about and update state changes.

2. **How would you combine multiple reducers?**
   Redux provides a utility function called `combineReducers` to combine multiple reducers into a single reducer function. You pass an object to `combineReducers`, where each key represents a slice of the state and the corresponding value is the reducer responsible for that slice. The combined reducer produced by `combineReducers` manages the entire state tree by delegating actions to the appropriate individual reducers.

3. **How will you manage state as an immutable object? Why?**
   In Redux, it's best practice to manage state as an immutable object to ensure predictability and maintainability. Immutable state means that once a piece of state is created, it cannot be directly modified. Instead, when an action triggers a state change, a new state object is created with the desired modifications, leaving the original state untouched. This immutability helps prevent unintended side effects, simplifies debugging, and enables efficient change detection for UI updates.

4. **Redux Docs: Using Combined Reducers**
   The missing terms in the sentence are: "reducers" and "state updates."

   - **Explain how combineReducers assembles the new state tree:**
     `combineReducers` takes an object where each key represents a slice of the state and the corresponding value is a reducer function. When actions are dispatched, `combineReducers` calls each individual reducer with its corresponding slice of the state and combines the results into a new state object. It constructs a new state tree by aggregating the state updates from each individual reducer.

5. **How would you define initial state in an app using combineReducers?**
   You can define the initial state for each slice of the state tree in the object passed to `combineReducers`. Each reducer can specify its initial state as the default value for its corresponding slice of the state. For example:

   ```javascript
   const rootReducer = combineReducers({
     counter: counterReducer,
     todos: todosReducer,
   });

   const initialState = {
     counter: 0,
     todos: [],
   };
   ```

6. **Redux Docs: Combined Reducer Syntax**
   - **Why will you want to split your reducing functions as your app becomes more complex?**
     As an app becomes more complex, the state management logic can become unwieldy if it's all contained in a single reducer function. Splitting reducing functions into multiple reducers offers several benefits:
     - Improved code organization and maintainability: Each reducer focuses on a specific aspect of the state, making the codebase more organized and easier to understand.
     - Better scalability: It's easier to add new features or modify existing ones when reducers are modular and specific to certain state slices.
     - Reusability: Reducers can be reused in different parts of the application, promoting code reuse.
   
   - **The _____ helper function turns an object whose values are different reducing functions into a single reducing function you can pass to ____.**
     The missing terms are "combineReducers" and "createStore." The sentence refers to `combineReducers` as the helper function that combines individual reducers into a single reducer function that can be used with `createStore` to create the Redux store.

7. **What is a popular convention when naming reducers?**
   A popular convention when naming reducers is to use descriptive names that indicate the slice of state they manage. For example, if a reducer manages the user's authentication state, it might be named `authReducer`. This naming convention helps developers quickly understand the purpose of each reducer and how they fit into the overall state management of the application.