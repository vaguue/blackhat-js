# Blackhat Js [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated and opinionated list of hacking with JavaScript resources

## Contents

- [Reverse Engineering](#reverse-engineering)
- [Networking](#networking)
- [Code packing](#code-packing)

## Reverse Engineering

Dynamic analysis, static analysis, assemblers.

- [frida](https://github.com/frida/frida-node)
- [ghidra.js](https://github.com/vaguue/ghidra.js)

Honestly Ghidra.js + Frida + claude code just solves everything, but the options bellow could be useful in some scenarious: 

- [r2pipe](https://github.com/radareorg/radare2-r2pipe/tree/master/nodejs)
- [unicorn.js](https://github.com/AlexAltea/unicorn.js)
- [capstone.js](https://github.com/AlexAltea/capstone.js)
- [keystone.js](https://github.com/AlexAltea/keystone.js)

## Networking

Capture & manipulate traffic, crawl internet.

### Web

- [axios](https://github.com/axios/axios) (*Goated HTTP client*).

Use it with

- [socks-proxy-agent](https://github.com/TooTallNate/proxy-agents/tree/main/packages/socks-proxy-agent)
- [tough-cookie](https://github.com/salesforce/tough-cookie)
- [faker](https://github.com/faker-js/faker)
- [jsdom](https://github.com/jsdom/jsdom)
- [cheerio](https://github.com/cheeriojs/cheerio)

or just use [puppeteer](https://github.com/puppeteer/puppeteer) - still prefer it over the alternatives, has a bunch of plugins, easy to use

### Low level attacks
- [over-the-wire](https://github.com/vaguue/over-the-wire) - my man, still in dev for how many years idk
- [bettercap](https://github.com/jsdom/jsdom) (Has JS scripting)
- [k6](https://github.com/grafana/k6) goated shit

## Code packing

Turn JS code to binary, minimize, uglify. [Built in Single Executable feature](https://nodejs.org/api/single-executable-applications.html) is not included it, since it's currently under development.

### Code2executable

- [boxednode](https://github.com/mongodb-js/boxednode)
- [pkg](https://github.com/vercel/pkg)

### Uglifiers

- [UglifyJS](https://github.com/mishoo/UglifyJS)
- [jsFuck](https://github.com/aemkei/jsfuck)

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
