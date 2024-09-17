# Remove redundant code with Vite and enhance bundle size

![](/assets/vite-dev-mode.jpeg)


My work requires heavy testing in mobile application inside a webview so i built my own debugger so i can make heavy testing before going out for production the bundler includes network logger, console logger, Super app debugger which results an additional 5kb to my production bundle even if the debugger is hidden but still the js code is shipped with the production build which results for a less performant application + introduced a major security issue that got reported by the security team ( Thanks to the seucrity team to mention it out  😁 ) since i use constant jwt tokens to make testing faster and automated in the dev environment 

After the report from the security team i found out that Vite the bundler i use is not very intelligent which i was not expecting, I thought out that treeshaking would work by default and remove redundant code that i don't use in a specific environment ( production ) . What was actually happening tree shaking is not working for user specified ENV variables ( VITE_ENV_NAME ) and to make the tree shaking works I should use the internal env that integrated by Vite

after migrating my env to the Vite variables which result to reduce my js bundle size by 5 kb + Fixed the security issue

