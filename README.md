# John Marquard's Resume Website

Simple static website to host my resume. Website is hosted at [https://johnmarquard.me](https://johnmarquard.me).

## Deploying website

To deploy the website push to master branch.

Travis CI is used to deploy website. See `.travis.yml` for deployment config.

Firebase is used to host the website. `$PROJECT_ID` and `$FIREBASE_TOKEN` are set in the repo config in Travis CI.

#### Manual deployment

To deploy manually:
- Install firebase: `npm i -g firebase-tools`
- Login to firebase: `firebase login`
- Change to firebase directory: `cd firebase`
- Deploy project: `firebase deploy`

## Making Changes

Requirements:
- Firebase

Make changes and run `firebase serve` from `./firebase/` to serve the website locally to check changes. Commit changes and then push to master to deploy website (as above).
