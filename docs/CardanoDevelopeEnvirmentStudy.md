# Cardano Develope Environment Study



## Introduce:

Cardano so far has two major layers, each layer represent different side chain and contract language.

This two different layers are  ***IELE*** & ***KEVM***.

### IELE:

"NOT" compatible with Ethereum ( partially compatible, but not directly )

Will feature Plutus, Marlow(Blockly), and K-compatible languages( java, C# ,etc....)



### KEVM:

Completely compatible with Ethereum, all the solidity contract will be launched here.





## How To Developed on ***IELE*** & ***KEVM***

****



### IELE:



#### Explore:

https://iele-testnet.iohkdev.io



#### HttpProvider:

https://iele-testnet.iohkdev.io:8546



#### Request Testnet Token:



1. Remix on IELE:

   https://iele-testnet.iohkdev.io/remix/#optimize=false

2. Install Mallet:

   Using `requestFunds()` to get testnet token on IELE.


   ***NOT SURE IF IELE CAN INTERACT WITH WEB3 ***




### KEVM:



#### Explore:

https://kevm-testnet.iohkdev.io/



#### HttpProvider:

https://kevm-testnet.iohkdev.io:8546



#### Request Testnet Token:

You need to using POST HTTP REQUEST to the faucet URL to get testnet token on KEVM.

Type this command on your terminal:

```$ curl -X POST  https://kevm-testnet.iohkdev.io:8099/faucet?address=youraddresshere```

And it will return a TXhash that you can search on KEVM explorer.









