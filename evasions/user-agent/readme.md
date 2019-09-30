## API

<!-- Generated by documentation.js. Update this documentation by updating the source code. -->

#### Table of Contents

-   [Plugin](#plugin)

### [Plugin](https://git@github.com/:berstend/puppeteer-extra/blob/ff112879545e8e68d6500d731ceeafc22d187dd3/packages/puppeteer-extra-plugin-stealth/evasions/user-agent/index.js#L13-L19)

**Extends: PuppeteerExtraPlugin**

A small shim to require the `puppeteer-extra-plugin-anonymize-ua` plugin.

Let's make use of `puppeteer-extra`'s modular nature and not re-invent things. :-)

Note: If you want to customize it's settings just require the above mentioned
plugin directly and specify your desired options, it won't be required if you already did so.

Type: `function (opts)`

-   `opts`   (optional, default `{}`)

* * *