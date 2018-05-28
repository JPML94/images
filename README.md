## Vue Aplication that handles auth with the Imgur API, a user can see their picture library and upload files to it.

### VueX:

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