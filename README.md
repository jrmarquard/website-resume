# John Marquard's Resume Website

Simple static website to host my resume. Website is hosted at [https://johnmarquard.me](https://johnmarquard.me).

## Deploying website

To deploy the website push to follow deployment steps below.

Firebase is used to host the website.

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
