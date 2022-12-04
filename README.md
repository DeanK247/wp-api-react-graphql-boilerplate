## Free to use for anyone wanting to get a quick wordpress and react site running
## What's included?

- A Wordpress backend that's been preconfigured to support authentication using [wp-api-jwt-auth](https://github.com/Tmeister/wp-api-jwt-auth) plugin
- Other plugins which expose Custom Fields and WP Menus data via REST API. Which are [acf-to-wp-api](https://wordpress.org/plugins/acf-to-wp-api/) and [wp-rest-api-v2-menus](https://wordpress.org/plugins/wp-rest-api-v2-menus/)
- A pro version of [ACF](https://advancedcustomfields.com/) plugin
- A sample, starter React app that uses `Typescript` & `react-redux`

## Demo

![wp-react](/src/assets/images/dark-mode.gif)

## Installation

In order to run this App in your local machine, run the commands below. Make sure `yarn` or `npm` is already installed in your computer.

```bash
git clone https://github.com/DeanK247/headless-wp-react-typescript-starter-code
cd wp-typescript-starter
yarn install OR npm install
yarn start OR npm start
```

The app will open in **http://localhost:3000/**

<h4>Setting up the included Wordpress backend</h4>

1. Everything is preconfigured except for the database. Replace the database credentials in `wp-config.php`
2. Activate the plugins that are included in the WP backend
3. Replace the API configuration found in your `/src/constants/index.ts` file. Make sure to replace the `baseUri` value with your WP API's url.

This app is also fully tested. To check the test status run:

```bash
yarn test OR npm test
```

## License

MIT
