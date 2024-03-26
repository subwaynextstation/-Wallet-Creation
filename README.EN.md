# Ethereum address wallet random generator
English | [简体中文](https://github.com/subwaynextstation/Wallet-Creation/blob/main/README.md)

The BIP39 Ethereum address wallet generator can specify the number of digits and use regular patterns (such as ending in 888) to generate beautiful numbers, mnemonic words and private keys.

## Install
- Install NodeJs first, version v20+ or ​​above is recommended [NodeJs official website](https://nodejs.org/en)
- git clone this project

## Usage
- cd to enter the project directory
- `npm install`
- Modify the corresponding configuration of wallet-generate.js
- node ./wallet-generate.js or npm run start and wait to generate output.txt

## Options
- Provider_API needs to be applied for by yourself, in the form: `https://mainnet.infura.io/v3/xxxxxx`
- Regular expression, for example, it ends with 88 here. You can adjust it yourself. Too many bits are not recommended. `return /88$/.test(input)`
- Generate quantity, it is also not recommended to use too much, just enough is enough `numberOfSpecialData = 10; `


## contribute
Everyone is welcome to contribute to this project! Welcome PR & STAR

## License
This project is licensed under the MIT license.
