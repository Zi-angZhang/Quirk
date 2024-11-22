# <a href="http://algassert.com/quirk">Quirk <img src="doc/favicon.ico" alt="Icon" title="Icon" /></a>

Deploy the [Original Quirk Project](https://github.com/Strilanc/Quirk) to Github Pages using [grunt-gh-pages](https://github.com/tschaub/grunt-gh-pages)


## Fork&Clone the Repository

Fork the repository to your own account. It is important because you will need to deploy the project to your own Github Pages. Once you have forked the repository, clone it to your local machine.

## Install Dependencies

The dependency Puppeteer is not needed for the deployment to Github Pages. To avoid the potential installation error of Puppeteer, set the environment variable `PUPPETEER_SKIP_CHROMIUM_DOWNLOAD` to `true` before installing the browser toolkit.

```bash
PUPPETEER_SKIP_CHROMIUM_DOWNLOAD=true npm i
```

## Build and Deploy

```bash
npm run build   # Build the output
npm run deploy
```

## Enjoy

Open your github pages. In my case, it is [https://zziangz.github.io/Quirk/](https://zziangz.github.io/Quirk/)

