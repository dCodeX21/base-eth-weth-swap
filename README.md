# Base ETH/WETH Swap Script

## Requirements

- [Node.js](https://nodejs.org/dist/v22.20.0/node-v22.20.0-x64.msi) >= v18.x
- npm >= v9 (usually bundled with Nodejs)
- [git bash](https://github.com/git-for-windows/git/releases/download/v2.51.0.windows.1/Git-2.51.0-64-bit.exe) (for command terminal)
<br/>

## Getting Started

### Clone Repository

```
git clone https://github.com/dCodeX21/base-eth-weth-swap.git
```

Go to the downloaded repository
```
cd base-eth-weth-swap
```

Install dependencies by running:

```
npm install
```

### Config .env

Create new .env file by running:

```
cp .env.example .env
```

Then define all the variables needed.
<br/>
<br/>

## Running the script

Run the following command to start the script:

```
$ node executeSwap.js
```

This will execute the new script which will give you an option on which transaction will run first.
