# Inspire for more 2026 Q3
**This sandbox helps to create my new portfolio website. it will support me hunting for a job in 2026 Q4**
## Dev architecture strategy
I want to create a simple dev environment where I can use my custom SASS modules to create the website. The code is completely hand made from skretch. All I need is a watcher for my SASS Modules and a local server that also allows to watch all other assets like images, html and Java Script.
## Initial Vite sandbox setup
To set up the Vite sandbox in my project folder I used the following terminal command:
```
npm create vite@latest my-sandbox -- --template vanilla cd my-sandbox
```
To be able to set up my SASS modules, I install the corresponding module for Vite:
```
npm install -D sass
```
This is all I need to start with my custom made SASS amd JS modules.
## Start the sandbox server and the watcher
The cleanest way to run the sandbox environment is to start the server and the watcher separatly. In order to do this I'm using 2 Terminal windows. To start the SASS watcher first I run the command:
```
npm run watch:css
```
In order to run the server I type into the Terminal prompt:
```
npm run dev
```

