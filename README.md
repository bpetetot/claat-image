# Claat Docker image
[![License: Apache2](https://img.shields.io/badge/License-Apache2-yellow.svg)](https://github.com/bpetetot/claat-image/blob/master/LICENSE)
[![Twitter: bpetetot](https://img.shields.io/twitter/follow/bpetetot.svg?style=social)](https://twitter.com/bpetetot)

> Docker image of claat tool used to generate beautiful codelabs from markdown or Google doc

### 🐳 [Image on Docker Hub](https://hub.docker.com/r/bpetetot/claat)

## 🚀 Usage

### 🐚 Launch Claat

```sh
docker container run -it -v $(pwd):/app bpetetot/claat:latest -h
```

## ⚙️ Build the image

Simply use the make target depending on your computer architecture:

```sh
# on amd64 machines
make build

# on arm64 machines (apple M1 for instance)
make build-arm64

# on armv7 machines (Rapsberry PI)
make build-armv7
```

> If your machine lack *make* support, simply run the associated commands from the [makefile](/Makefile) instead.

## Author

👤 **Benjamin Petetot**

* Twitter: [@bpetetot](https://twitter.com/bpetetot)
* Github: [@bpetetot](https://github.com/bpetetot)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!

Feel free to check [issues page](https://github.com/bpetetot/claat-image/issues).

## 🙏 Show your support

Give a ⭐️ if this project helped you!

## 📝 License

Copyright © 2019 [Benjamin Petetot](https://github.com/bpetetot).

This project is [Apache-2.0](https://github.com/bpetetot/claat-image/blob/master/LICENSE) licensed.

***
_This README was initialy generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_
