# Block-Currency
This project is Submission is for Coder's Week which is simple Blockchain Based web UI crated with react ,trufflesuite and Metamask

Before we get started make sure you have following things installed on your system:

  1.[node.js](https://nodejs.org/en/download/)  
  2.[Truffle](https://www.trufflesuite.com/truffle)  
  3.[Ganache](https://www.trufflesuite.com/ganache)  
  4.[Metamask](https://metamask.io/)
  
To get started git clone this project and open command prompt and run command: 

```
npm install
```

If you dont have node.js installed on your system properly this will cause error. To check use command node -v

```
node -v
```

This will install all the dependencies for project. Next fire up Ganache. (It is one click blockchain network and can be used in Blockcahin development)

Now make sure that you connected your Metamask wallet to Ganache through Custom RPC option or you can simply copy seed phrase given by Ganache and paste it into Metamask.

In terminal (open project folder) run following commands

```
truffle compile
```

```
truffle migrate
```
  
This will connect our code to blockchain Network. To know more you can follow this (https://www.trufflesuite.com/tutorials)

and finally run command: npm run start

```
npm run start
```

New Window will be opned in your bowser and you can see UI for currency exchange.
