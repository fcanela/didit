<h1 align="center">Welcome to didit 👋</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-1.0.0-blue.svg?cacheSeconds=2592000" />
  <a href="https://www.gnu.org/licenses/gpl-3.0.html" target="_blank">
    <img alt="License: GPL" src="https://img.shields.io/badge/License-GPL-yellow.svg" />
  </a>
  <a href="https://twitter.com/fjcanela" target="_blank">
    <img alt="Twitter: fjcanela" src="https://img.shields.io/twitter/follow/fjcanela.svg?style=social" />
  </a>
</p>

> Get notified when a shell command finishes

## Usage

Simply run `didit` at the end of a terminal command or command chain to receive a desktop notification when it finishes.

For example, to get notified after running a big JavaScript test suite:
```sh
npm test ; didit
```

`didit` also redirects the `stdin` to `stdout`, so you can also use it in the middle of a pipe sequence without breaking anything:
```sh
echo hello world | didit | figlet
```

## Author

👤 **Francisco Canela**

* Website: http://www.fcanela.com
* Twitter: [@fjcanela](https://twitter.com/fjcanela)
* Github: [@fcanela](https://github.com/fcanela)
* LinkedIn: [@franciscocanela](https://linkedin.com/in/franciscocanela)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/fcanela/didit/issues). 

## Show your support

Give a ⭐️ if this project helped you!

## 📝 License

Copyright © 2020 [Francisco Canela](https://github.com/fcanela).<br />
This project is [GPL](https://www.gnu.org/licenses/gpl-3.0.html) licensed.

***
_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_
