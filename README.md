# Spotify Rundown App

There's two methods to run the app. Either by the link provided below or running it locally.

I have an demo account should you like to try out the app. Just send me a quick email and ill send you the demo account.

## Running the app

### Link

[Spotify Rundown](https://spotify-rundown.herokuapp.com/)

## Local Installation & Set Up

1. Register a Spotify App in your [Spotify Developer Dashboard](https://developer.spotify.com/dashboard/) and add `http://localhost:8888/callback` as a Redirect URI in the app settings

2. Create a `.env` file at the root of the project based on `.env.example` and add your unique `CLIENT_ID` and `CLIENT_SECRET` from the Spotify dashboard

3. Ensure [nvm](https://github.com/nvm-sh/nvm) and [npm](https://www.npmjs.com/) are installed globally

4. Install the correct version of Node

   ```shell
   nvm install
   ```

5. Install dependencies

   ```shell
   npm install
   ```

6. Run the React app on <http://localhost:3000> and the Node server on <http://localhost:8888>

   ```shell
   npm start
   ```

# Status

The app is currently in development mode which means in order to access the application through your own spotify account. I would need add your spotify account in the Users and Access tab of development mode. I've requested an extension which means should they approve my request, i will not be limited to manually adding users in the test mode and anyone would be able to access it or running it locally.
