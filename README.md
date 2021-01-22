# ReactNativeWindowsApp
A windows desktop app using ReactNative

Install dependencies
```
npm install <https://github.com/ReyBernDia/ReactNativeWindowsApp.git>
```
You can also do the following to check that all your dependencies have been installed...

Start an elevated PowerShell window and run:
```
Set-ExecutionPolicy Unrestricted -Scope Process -Force; iex (New-Object System.Net.WebClient).DownloadString('https://raw.githubusercontent.com/microsoft/react-native-windows/master/vnext/Scripts/rnw-dependencies.ps1')
```
Then you can run the following from the project directory
```
npx react-native run-windows
```
