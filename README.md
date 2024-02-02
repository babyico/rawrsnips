# RawrSnips

Save time and energy by using **RawrSnips** extension for VS Code, the ultimate tool for building amazing Discord.JS bots with ease and speed using **Snippets** system, you can write common code patterns in just a few keystrokes, making your work faster and efficient.

## Installation

Just simply go to [VS Marketplace](https://marketplace.visualstudio.com/) and follow their installation guide and you should be good to go.

## Supported languages, frameworks and etc...
* Discord.JS (.js)
* JavaScript (.js)
* TypeScript (.ts)
* ReactJS (.jsx)
* React (.tsx)
* Html (.html)
* Vue (.vue)

## Snippets

Below is a list of all available snippets and the triggers of each one. The **⇥** means the `TAB` key.

### Discord exclusive
| Trigger  | Content |
| -------: | ------- |
| `req.djs→`   | require discord.js to const `const { X } = require('discord.js');`|
| `req.client→`   | require discord for discord client `const { Client } = require('discord.js');`|
| `req.discord→`   | default req for usual constants `const { Client, Collection, GatewayIntentBits, Partials, Events } = require('discord.js');`|
| `djs.scratch→`   | Imports the discord.js library and creates a simple client instance |
| `djs.channelCreate→`   | Create a channelCreate |
| `djs.embed→`   | Creates an embed object with fields to add content |
| `djs.embed+→`   | Creates an embed object with advanced fields to add content (Press tab to navigate) |
| `djs.msg→`   | Sends a message to the channel where the command was called `${1:message}.channel.send(`${2:urmessage}`)` |
| `djs.slash→`   | Creates a basic slash command for Discord bot using the discord.js |
| `djs.event→`   | Creates a basic event for Discord bot using the discord.js |
| `djs.XXX→`   | many other snippets, use F1 or ctrl+shift+p ... |

### Import and export
| Trigger  | Content |
| -------: | ------- |
| `imp→`   | imports entire module `import fs from 'fs';`|
| `imn→`   | imports entire module without module name `import 'animate.css'` |
| `imd→`   | imports only a portion of the module using destructing  `import {rename} from 'fs';` |
| `ime→`   | imports everything as alias from the module `import * as localAlias from 'fs';` |
| `ima→`   | imports only a portion of the module as alias `import { rename  as localRename } from 'fs';` |
| `rqr→`   | require package `require('');`|
| `req→`   | require package to const `const packageName = require('packageName');`|
| `mde→`   | default module.exports `module.exports = {};`|
| `env→`   | exports name variable `export const nameVariable = localVariable;` |
| `enf→`   | exports name function `export const log = (parameter) => { console.log(parameter);};` |
| `edf→`   | exports default function `export default function fileName (parameter){ console.log(parameter);};` |
| `ecl→`   | exports default class `export default class Calculator { };` |
| `ece→`   | exports default class by extending a base one `export default class Calculator extends BaseClass { };` |

### Class helpers
| Trigger  | Content |
| -------: | ------- |
| `con→`   | adds default constructor in the class `constructor() {}`|
| `met→`   | creates a method inside a class `add() {}` |
| `pge→`   | creates a getter property `get propertyName() {return value;}` |
| `pse→`   | creates a setter property `set propertyName(value) {}` |

### Various methods
| Trigger  | Content |
| -------: | ------- |
| `fre→`   | forEach loop in ES6 syntax `array.forEach(currentItem => {})`|
| `fof→`   | for ... of loop `for(const item of object) {}` |
| `fin→`   | for ... in loop `for(const item in object) {}` |
| `anfn→`  | creates an anonymous function `(params) => {}` |
| `nfn→`   | creates a named function `const add = (params) => {}` |
| `dob→`   | destructing object syntax `const {rename} = fs` |
| `dar→`   | destructing array syntax `const [first, second] = [1,2]` |
| `sti→`   | set interval helper method `setInterval(() => {});` |
| `sto→`   | set timeout helper method `setTimeout(() => {});` |
| `prom→`  | creates a new Promise `return new Promise((resolve, reject) => {});`|
| `thenc→` | adds then and catch declaration to a promise `.then((res) => {}).catch((err) => {});`|

### Console methods
| Trigger  | Content |
| -------: | ------- |
| `cas→`   | console alert method `console.assert(expression, object)`|
| `ccl→`   | console clear `console.clear()` |
| `cco→`   | console count `console.count(label)` |
| `cdb→`   | console debug `console.debug(object)` |
| `cdi→`   | console dir `console.dir` |
| `cer→`   | console error `console.error(object)` |
| `cgr→`   | console group `console.group(label)` |
| `cge→`   | console groupEnd `console.groupEnd()` |
| `clg→`   | console log `console.log(object)` |
| `clo→`   | console log object with name `console.log('object :>> ', object);` |
| `ctr→`   | console trace `console.trace(object)` |
| `cwa→`   | console warn `console.warn` |
| `cin→`   | console info `console.info` |
| `clt→`   | console table `console.table` |
| `cti→`   | console time `console.time` |
| `cte→`   | console timeEnd `console.timeEnd` |