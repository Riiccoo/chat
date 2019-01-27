# Mihail's Chat
A single page application (SPA) implementing, Socket.io based chat app, built with the following technical stack:
- React with TypeScript (`create-react-app my-app --scripts-version=react-scripts-ts`)
- Redux
- Express.js with Socket.io
- styled-components (SASS)
- Jest/Enzyme/Sinon

### Screenshots
![screenshot](https://github.com/mihailgaberov/chat-spa/blob/master/screenshots/dark_iphone_678.PNG)


### Deploy to Heroku

1. `npm build` to build the project to `build` folder.
2. Include `build` folder to Git
3. Make sure that express server loads static resources from it.
4. Commit all: `git commit -m 'Deploy to Heroky'`.
5. Run `git push heroku master`.
6. Open the app from the given URL (in this case: [mihails-chat.herokuapp.com](http://mihails-chat.herokuapp.com)).
