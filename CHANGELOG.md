# Changelog

## [Unreleased]

### Template

- Change scripts commands, cra commands now have `cra` prefix and `start:dev` becoms `start`

### React

- Fix App test issue caused by missing `CordovaProvider`

### Console

- Replace fixed hostname and port with `location.host` for websocket
- Replace getting addresses using `Fetch` with `WebSocket`

### Scripts

- Add dynamic port support for dev-serve and webpack-dev-server
- Add `get-port` helper module to select next open port
- Replace getting addresses using `GET REST` with `WebSocket`
- Use `chalk` to enhance logging

### Client App

- Fix storing platform with `null` in SessionStorage

## 0.2.0 (Jun 1, 2019)

### React

- Set/Get platform in sessionStorage to avoid full page reload issue
- Add 'Device Status' to App component similar to Cordova hello-world

### Cordova

- Implement Cordova component containing `CordovaProvider` and `useCordova`

### Client App

- Fix browser not showing correct message

### Dependencies

- Add devDependency eslint@5.16.0
- Add devDependency tslint@5.17.0
- Add devDependency @types/cordova@0.0.34
- Add devDependency @types/webpack-env@1.13.9
- Update devDependency typescript@3.4.5 to 3.5.1
- Update devDependency @types/node@12.0.3 to 12.0.4

## 0.1.0 (May 30, 2019)

- Create Cordova project using Cordova@9.0.0
- Create React app using CRA@3.0.0
- Add cordova-plugin-qrscanner@2.6.0
- Add cordova-plugin-ionic-webview@4.0.1
- Implement Cordova Development App
- Implement Cordova Development Console
- Use material-components-web@2.3.0
- Use material-icons
- Use QRious@4.0.2
- Use xterm@3.13.2
- Use dependency ngrok@3.1.1
- Use dependency cordova-lib@9.0.1
- Use dependency ws@7.0.0
- Implement script for symlinking resources
- Implement script for running webpack dev server
- Implement script for starting dev server
- Implement script for creating tunnel for webpack dev server
- Implement script for setting dev environment
- Implement Cordova hook for running dev mode
- Implement Cordova hook for running prod mode
- Implement Cordova hook for collecting app data