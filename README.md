# Fluidify
Todo app

### UP & RUNNING
* Run `npm install`

**FOR DEVELOPMENT**
* Run `npm run dev` to fire up Webpack
* In another terminal window run `npm start` to start electron

**FOR PRODUCTION**
* Run `npm run postinstall` to compile all your assets into `dist/bundle.js`
* Change the script tag in `dist/index.html` to use `bundle.js` as its source
* Run `npm start` to start electron


CefSharp WebBrowser Control
(UPDATE: I will probably go with Electron for the desktop application instead of embedding CefSharp in a Windows app.)

Installation was a pain in the rump. Here is the article that saved me:
http://www.codeguru.com/columns/dotnet/if-you-like-it-put-an-html5-ui-on-it.html


ReactJS

React Static Boilerplate (not sure if there is a VS 2015 template for this).
This scaffold has Babel, Webpack, and ES2015 in it...all the stuff I wanted to try and use.
https://github.com/kriasoft/react-static-boilerplate

React Starter Kit
This scaffold can be added using a VS 2015 template.
This has some stuff that I don't care to use necessarily such as gulp tasks. But if the scaffolding
I want to use is not available, I can start with this and then change out the innards.
https://github.com/kriasoft/react-starter-kit


Server Side

Take a serious look at Azure functions or Amazon Lambda. These appear to be microservices that allow you to call from SPA's and do simple tasks.
With Azure Functions it seems you are only charged for the actual execution time of your function calls!!!!!! This could be an amazing development
for running stuff in the cloud for low, low cost.

Azure Functions: https://azure.microsoft.com/en-us/pricing/details/functions/
