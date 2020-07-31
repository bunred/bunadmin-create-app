The [BunAdmin](https://github.com/bunred/bunadmin) template for [Create React App](https://github.com/facebook/create-react-app)

## Quick Start

```shell script
yarn update-plugins && yarn dev
```

## Environment Variables

You can create DEV/PROD `.env` file with: `cp e.g/env-*.env env-dev.env`
`NEXT_PUBLIC_MAIN_URL` is required
```
NEXT_PUBLIC_SITE_NAME=SiteName-DEV \
NEXT_PUBLIC_MAIN_URL=http://192.168.2.2:51800/api/v1 yarn dev
```

## Available Scripts

### `yarn update-plugins`

Runs `yarn install --froce` and copy Plugins defined in `plugins-info.json` to `@bunred/bunadmin/plugins/`.<br />

### `yarn dev`

Runs the app in the development mode.<br />
Open [http://localhost:1911](http://localhost:1911) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `yarn build`

Builds the app for production to the `@bunred/bunadmin/.next/` folder.<br />
Your app is ready to be deployed!

### `yarn start`

Runs the app in the production mode.<br />
Open [http://localhost:1912](http://localhost:1912) to view it in the browser.

### See more on [bunadmin](https://github.com/bunred/bunadmin)
