<h1 align="center">
  <br>
    <a href=""><img src="https://image.ibb.co/mDgm3U/cpoints.png" width="546" alt="cyberpoints" /></a>
  <br>
</h1>
<h4 align="center">Awesome Endpoints For Developers</h4>
<p align="center">
  <a><img src="https://img.shields.io/circleci/build/github/kendinikertenkelebek/cyberpoints/master?style=flat-square" alt="CircleCI"></a>
  <a><img src="https://badges.greenkeeper.io/kendinikertenkelebek/cyberpoints.svg?style=flat-square" alt="Greenkeeper"></a>
  <a href="https://www.npmjs.com/package/cyberpoints"><img src="https://img.shields.io/npm/dt/cyberpoints.svg?maxAge=3600&style=flat-square" alt="NPM downloads" /></a>
  <a><img src="https://img.shields.io/github/issues/kendinikertenkelebek/cyberpoints?style=flat-square" alt="Issues"></a>
  <a><img src="https://img.shields.io/github/stars/kendinikertenkelebek/cyberpoints?style=flat-square" alt="Stars"></a>
</p>
<p align="center">
  <a><img src="https://img.shields.io/github/languages/code-size/kendinikertenkelebek/cyberpoints?style=flat-square" alt="Code Size"></a>
  <a><img src="https://img.shields.io/github/package-json/v/kendinikertenkelebek/cyberpoints/master?color=red&style=flat-square" alt="Version"></a>
  <a><img src="https://img.shields.io/github/contributors/kendinikertenkelebek/cyberpoints?style=flat-square" alt="Contributors"></a>
  <a><img src="https://img.shields.io/github/license/kendinikertenkelebek/cyberpoints?style=flat-square" alt="Licance"></a>
</p>
<p align="center">
  <a href="https://nodei.co/npm/cyberpoints/"><img src="https://nodei.co/npm/cyberpoints.png?downloads=true&downloadRank=true&stars=true" alt="NPM Info" /></a>
</p>

# About

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

**cyberpoints** was developing for _CyberEngine_. And now, she is **open source**! She will generate endpoint links for make an request. All validation process is done by **cyberpoints**.
If you're used correct values, returns an request link. Otherwise returns 'undefined'. This method saves your request limits and time! Also cyberpoints is a powerful Node.JS module that allows you to interact with the API's very easily. Usability, consistency, and performance are key focuses of cyberpoints, and it also has nearly 100% coverage of the listed API's. It receives new features shortly after they arrive in the API's.

### Why?

- Object-oriented
- Speedy and efficient
- Modular and flexible
- Feature-rich
- Maintainable

### Supported API's

- Blizzard (WiP)
- Riot Games (in Future)

### Installation

_cyberpoints_ requires [Node.JS](https://nodejs.org/en/download/) **LTS** version for run.

```sh
$ npm i cyberpoints
```

or

```sh
$ yarn add cyberpoints
```

### Configuration File

Default configurations are listed below. 

```json
{
  "region": "eu",
  "locale": "en_GB",
  "key": null,
  "secret": null,
  "debug": false
}
```

### Usage

```js
// how can i use it?
const { Wow } = require('cyberpoints')
const wow = new Wow(configs)
console.log(wow.community.guild.profile())
console.log(wow.community.guild.members())
console.log(wow.community.guild.news())

// how can i access all blizzard endpoints?
const { Blizzard } = require('cyberpoints')
const blizzard = new Blizzard(configs)
console.log(blizzard.wow.data.keystone.leaderboard())
console.log(blizzard.sc2.community.ledder())
console.log(blizzard.diablo.community.skill())
console.log(blizzard.outh2.user())

// how can i access specific blizzard enpoints?
const { SC2, WoW } = require('cyberpoints')
const sc2 = new SC2(configs)
const wow = new WoW(configs)
console.log(sc2.community.ledder())
console.log(wow.data.keystone.leaderboard())
```

### Technology

_cyberpoints_ uses a number of open source projects to work properly:

- [Node.js] - _cyberpoints_ uses this powerful programming language.
- [VScode] - We're highly recommending this awesome code editor.

And of course _cyberpoints_ itself is open source with a [public repository][repository] on _GitHub_.

### Dependencies

_cyberpoints_ is currently extended with the following dependencies for high user experience. Instructions on how to use them in your own application are linked below.

| Plugin      | README                                    |
| ----------- | ----------------------------------------- |
| Chalk       | [dependencies/chalk/README.md][plc]       |

### dev-Dependencies

| Plugin      | README                                    |
| ----------- | ----------------------------------------- |
| Eslint      | [dev-dependencies/eslint/README.md][ple]  |
| Jest        | [dev-dependencies/jest/README.md][plj]    |

### Semantic Versioning

We're using [SemVer][semver] for this project.

### Development

Want to contribute? Great!

_cyberpoints_ uses eslint and jest for stable developing.
Make a change in your file and instantanously see your updates!

Open your favorite Terminal and run these commands.

```sh
$ git clone <url>
$ cd <cloned_folder_name>
$ npm i
$ npm test
```

### Our Contributors

- Yankı Küçük - [Twitter][yk]
- Elif Eryıldırım - [Github][ee]

And you can see also all contributors [here][contributors].

[twitter]: https://developer.twitter.com/en/docs/basics/twitter-ids.html
[node.js]: http://nodejs.org
[vscode]: https://code.visualstudio.com/insiders/
[repository]: https://github.com/kendinikertenkelebek/cyberpoints
[plc]: https://github.com/chalk/chalk/blob/master/readme.md
[plj]: https://github.com/facebook/jest/blob/master/README.md
[ple]: https://github.com/eslint/eslint/blob/master/README.md
[semver]: https://semver.org
[yk]: https://twitter.com/leithrien
[ee]: https://github.com/elifery06
[contributors]: https://github.com/kendinikertenkelebek/cyberpoints/graphs/contributors

## License

Aphace 2.0
