# amanda-allison.org

Personal website hosted on Google Firebase.

## Initial Setup

`.firebaserc` is gitignored. After cloning, link to the Firebase project before deploying:

```sh
firebase use --add
```

## Local Development

```sh
firebase emulators:start
```

Opens at `http://localhost:5000`.

## Deploy (Local)

```sh
firebase deploy
```

If you get an auth error:

```sh
firebase logout
firebase login
```

## Project Structure

All site content is static HTML/CSS in `public/`. Fonts are self-hosted in `public/fonts/`. No build step.
