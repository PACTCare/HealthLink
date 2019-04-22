<img src="https://pact.online/dist/img/Healthlink.png" width="240">

[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)

> The Healthcare DNS

HealthLink connects as well as validates Patient-Generated Health Data in a distributed way and put users in control of their own data.

## Table of Contents
- [Background](#background)
- [Install](#install)
- [Usage](#usage)
- [Maintainer](#maintainer)
- [Contributing](#contributing)
- [License](#license)

## Background

## Install

If you haven’t installed [Substrate](https://www.parity.io/substrate/) before, check out the official [Substrate documentation](https://substrate.readme.io/docs/getting-started). If you are a windows user, I also suggest taking a look at the [Substrate GitHub](https://github.com/paritytech/substrate).

## Usage

Clone this repository and run the following commands:
```
./build.sh
cargo build --release
./target/release/starlog purge-chain --dev
./target/release/starlog --dev
```

You can interact with your local chain using the [Polkadot-JS Apps UI](https://polkadot.js.org/apps/).
Therefore, you need to adjust the Settings:
```
Remote node/endpoint to connect to > Local Node (127.0.0.1:9944)
Default Interface Theme > Substrate
```

Under the developer tab upload and save the [Metadata.json](https://github.com/PACTCare/Starlog/blob/master/Metadata.json) to register the custom struct. 

## Maintainer

[David Hawig](https://github.com/Noc2)

## Contributing

If you want to help either join our **[discord server](https://discord.gg/VMj7PFN)** or you can open issues for bugs you've found or features you think are missing. You can also submit pull requests to this repository.

If editing the README, please conform to the [standard-readme specification](https://github.com/RichardLitt/standard-readme).

## License
[MIT License](https://github.com/PACTCare/HealthLink/blob/master/LICENSE) © PACT Care B.V.



