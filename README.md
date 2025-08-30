# BarStockV1 Firebase Hosting

This project is hosted on Firebase App Hosting.

## Setup Instructions

1. Clone this repository
2. Install dependencies: `npm install`
3. Deploy to Firebase: `firebase deploy`

## Project Structure

- `public/` - Static files (create this directory for HTML, CSS, JS)
- `package.json` - Project configuration and dependencies
- `firebase.json` - Firebase deployment configuration
- `apphosting.yaml` - App Hosting specific configuration

## Build Process

Firebase will automatically:
1. Install dependencies from package.json
2. Run the build command defined in package.json
3. Deploy the output to Firebase Hosting
