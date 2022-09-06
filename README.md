# watermelon-db-plugin 🍉
Config plugin to auto configure `@nozbe/watermelondb`

## Install

> Tested against Expo SDK 43

```
yarn add @mauro-codes/watermelondb-expo-plugin
```

After installing this npm package, add the [config plugin](https://docs.expo.io/guides/config-plugins/) to the [`plugins`](https://docs.expo.io/versions/latest/config/app/#plugins) array of your `app.json` or `app.config.js`. Then rebuild your app as described in the ["Adding custom native code"](https://docs.expo.io/workflow/customizing/) guide.

## Example

In your app.json `plugins` array:

```json
{
  "plugins": ["@maurocodes/watermelondb-expo-plugin"]
}
```
