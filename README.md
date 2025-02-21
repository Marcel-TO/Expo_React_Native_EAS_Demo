# React_Native_Demo

## Prerequisites for CI/CD
- Expo Account [Homepage](https://expo.dev/)
- Create EXPO_TOKEN (and set Github Action Secret)
- Install EAS CLI [Docs](https://docs.expo.dev/build/setup/)
  ```bash
    npm install -g eas-cli
    ```
- Setup EAS inside the project directory
  ```bash
    eas init
    ```

The project is a simple React Native application that uses the Expo framework. It even contains a simple Github Action workflow that builds the app and publishes it to Expo for Preview purposes.
