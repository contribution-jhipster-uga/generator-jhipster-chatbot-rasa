# generator-jhipster-chatbot-rasa
[![NPM version][npm-image]][npm-url] [![Build Status][travis-image]][travis-url] [![Dependency Status][daviddm-image]][daviddm-url]
> JHipster module, This module integrates an interface to use with a bot using the Rasa Stack.

# Introduction

This is a [JHipster](http://jhipster.github.io/) module, that is meant to be used in a JHipster application. This module integrates an interface to use with a bot using the [Rasa](https://rasa.com/) stack. The interface used is from this [webchat](https://github.com/mrbot-ai/rasa-webchat) used on [Rasa](https://rasa.com/).

# Prerequisites

As this is a [JHipster](http://jhipster.github.io/) module, we expect you have JHipster and its related tools already installed:

- [Installing JHipster](https://jhipster.github.io/installation.html)

You will also need a bot using the Rasa Stack and expose it with SocketIO : [See instructions in the Rasa Core Documentation](https://rasa.com/docs/core/connectors/#socketio-connector), on the [react webchat](https://github.com/mrbot-ai/rasa-webchat) README or on the [angular webchat](https://www.npmjs.com/package/angular-chat-widget-rasa).

# Installation

## With Yarn

To install this module:

```bash
yarn global add generator-jhipster-chatbot-rasa
```

To update this module:

```bash
yarn global upgrade generator-jhipster-chatbot-rasa
```

## With NPM

To install this module:

```bash
npm install -g generator-jhipster-chatbot-rasa
```

To update this module:

```bash
npm update -g generator-jhipster-chatbot-rasa
```

# Usage

First, you have to run the generator using the following command :

```bash
yo jhipster-chatbot-rasa
```

Then, you can launch your bot on your own and run the app with :
```bash
./mvnw
```

## React

It will modify 2 files (package.json and app.tsx) and you must agree to overwrite them.

If you need to modify some parameters of the widget, it has been added in src/main/webapp/app/app.tsx under
```bash
<Footer />
```
and you can refer to the [webchat github](https://github.com/mrbot-ai/rasa-webchat) to know what you can do with it.

## Angular

It will modify 3 files (package.json, app.module.ts and main.component.html) and you must agree to overwrite them.

If you need to modify some parameters of the component, it has been added in src/main/webapp/app/layouts/main/main.component.html

and you can refer to the [webchat npm page](https://www.npmjs.com/package/angular-chat-widget-rasa) to know what you can change.

# License

MIT © [contributionjhipsteruga](github.com/contribution-jhipster-uga)
Julien COURTIAL, Hugo GROS-DAILLON, Cédric LAFRASSE et Bastien TERRIER
Our contribution uses the open source work of mrbotai.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

[npm-image]: https://img.shields.io/npm/v/generator-jhipster-chatbot-rasa.svg
[npm-url]: https://npmjs.org/package/generator-jhipster-chatbot-rasa
[travis-image]: https://travis-ci.org/contributionjhipsteruga/generator-jhipster-chatbot-rasa.svg?branch=master
[travis-url]: https://travis-ci.org/contributionjhipsteruga/generator-jhipster-chatbot-rasa
[daviddm-image]: https://david-dm.org/contributionjhipsteruga/generator-jhipster-chatbot-rasa.svg?theme=shields.io
[daviddm-url]: https://david-dm.org/contributionjhipsteruga/generator-jhipster-chatbot-rasa
