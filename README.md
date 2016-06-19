# A React/Redux starter

This is a small sample project you can use to start a new React/Redux app. It contains:

* all of the needed dependencies.
  - To begin using it, `npm install` after cloning.
* a webpack setup with its dev server and hot module reloading.
  - To use it, `npm start` and take your browser to [http://localhost:8080](http://localhost:8080).
* an Express server with API routes and a `/static` folder to hold the webpack assets.
  - To use it, `npm run server` in a separate terminal if your frontend will be using it.
  - The server can be found at [http://localhost:3000](http://localhost:3000) and includes the necessary CORS configuration to permit access from client assets served from the `webpack-dev-server`.
  - It includes `node-inspector` for server-side debugging. For the debugging interface, go to [http://localhost:8888/?debug=5858](http://localhost:8888/?debug=5858).
  - It uses `node-dev` so it will restart after detected changes.
* a test setup for running tests with `ava` and `enzyme`.
  - To run the tests, run `npm test`.

## What's next?

There is currently only a single `App` component and no Redux implementation (only references). Reasonable steps to take next might include:

1. Wireframe your application.
2. Write the UI in static HTML.
3. Decompose the HTML into JSX components.
4. Decide which _components_ are stateful (containers) and which are only UI (presentation).
5. Define the potential _actions_ in the app.
6. Define the structure of the _state_ of the app.
7. Using _reducers_, decide how actions will alter the state (store) of the app.
