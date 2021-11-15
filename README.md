# Kavithai image maker

![build-test](https://github.com/mskian/kavithai-image-maker/workflows/build-test/badge.svg)  

[![Free Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/mskian/kavithai-image-maker)  

Convert HTML to image with fully Designed for Tamil kavithai image.  

> Tamil Kavithai image Maker - Just add your Tamil Kavithai it will Generate the image with the text you add - Free kavithai Maker.  

Just Fork and Download this Repo & modify the Content/Design According to your Needs and don't use it Directly - **it's a Source code of Production Site**.  

we ❤ Open Source  

This Project Was Developed and Maintained by the Team tamilsms.blog
it's Fully Free to use - Zero Ads and Zero Promotions.  

- Web App Powered by `node-html-to-image` Module  - <https://github.com/frinyvonnick/node-html-to-image>  

## Developent

- Download or Clone the Repo

```sh
git clone https://github.com/mskian/kavithai-image-maker.git
cd kavithai-image-maker
yarn
```

- Server Test

```sh
yarn dev
```

- image Generatin test

```sh
yarn test
```

## usage

- Homepage URL

```html
http://localhost:3006/
```

- API - POST Method with CSRF Token

```html
http://localhost:3001/kavithai
```

## Reference

- line break <https://github.com/frinyvonnick/node-html-to-image/issues/134>
- Heroku puppeteer - <https://elements.heroku.com/buildpacks/jontewks/puppeteer-heroku-buildpack>
- Heroku Emoji Support - <https://github.com/SimonBriche/heroku-buildpack-emoji-support>

## LICENSE

MIT
