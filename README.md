# reactjs-custom-webpack - Live Coding

1. Install NodeJS (14.x or newer)
2. Install NPM
3. Install Webpack 5 and webpack-cli
3. From the root directory run: `npm install`. This will download all of the npm dependencies
4. Try `npm run dev` and check if you have the dev server up and running
5. Once the web server is running, visit [http://localhost:3000](http://localhost:3000).

## Some important things

- Webpack config file is on config/webpack.dev.js
- dist/ - contains the code for production
- src/ - contains all the development code
- We are using the copy plugin to copy all the images from src/images to dist/images
- main.js is loading react and it's rendering the <App /> component on the react-root div on the index.html
- Using babel-core for jsx