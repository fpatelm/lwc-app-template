# LWC Opensource Starter Project

Hi! I have created this Lightning Web Components starter project that can be deployed outside Salesforce, can be deployed in any web server. 

Fell free to fork, start this project and start building your custom Lightining App.


This repo contains the SLDS (Salesforce Lightning Design System) and Lignining Web Components, except fgor the ones that are speficif to use with Salesforce data.
Reference: ([lightning-base-components - npm (npmjs.com)](https://www.npmjs.com/package/lightning-base-components))

## Run the LWC App Development Mode

The source code is located in [`src`](./src).
All web components are within the [`src/modules`](./src/modules) folder. The folder hierarchy also represents the naming structure of the web components.

```console
npm install
npm run watch
```


## Build the Release App
```console
npm install
nm run build
```
The generated files will be **/dist** folder.
