## Vue Aplication // Imgur Auth // File Upload

### VueX:

#### Auth Store Module:

- State
    - token | null

- Getters
    - isLoggedIn | look at value of 'token' in state object

- Mutations
    - setToken

- Actions
    - login
    - finalizeLogin (setToken)
    - logout (setToken)