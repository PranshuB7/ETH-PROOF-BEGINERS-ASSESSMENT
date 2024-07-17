Project Title : ETH Proof Beginers Assessment
 We will be creating token and further we will use mint and burn functions.

Description
This is a assessment project in which you create a token. In the token i fulfilled the following requirements: -it consists of three public variables TNAME, TAbbrv., TotSuplly. -it contains a mapping address to balances -it has a mint function in which you add tokens. it has two parameters _baddress and _bvalue. The TotSupply increases by the bfvalue value. -it has a burn function which deducts the tokens on transaction. It has two parameters same as mint function but instead of adding it to the TotSupply it deducts it From the TotSupply and balances. -lastly there is a condition on burn function that balances should be greater than or equal to the amount to be burned.

Getting Started
Step 1: Creating a token.
Step 2: We will create 3 variables NAME, Abbrv, TotSuplly.
Step 3: Stet the corressponding values or names to the variables like here NAME = "BASKETBALL",TAbbrv = "BTBL" ,TotSuplly = 0.
Step 4: We will create a mint function which will take into account address and value.
Step 5: We have at last created a burn function which means that it will destroy tokens in the balances.
 
Executing program
1 First of all we will compile the program and then deploy it. 
2 Then having done this we will copy the address of thr token we have created and paste into the address of Bmint then balance and then Bburn. This should be done in order.
3. Then we can type any value in the mint value and then burn value.
4. One condition should be kept in mind that the value of bun cant be more than the value of the mint value.
Help
There is one condition that the value of the burn can not be more than the value of the balance.


My Token
This project aims to develop a simple token contract. It provides minting and burning features and also these features are only accessible by the owner(Here owner is the address of the person who deploys the contract and it cannot be changed) of the contract.

Getting started
To test this contract you can either just copy and paste it in remix ide or test it locally in your code editors or ides.

Set-Up Locally
To set it up locally start by clonning the repo

git clone https://github.com/Ayush-Thakur-geek/My_Token_Contract.git
now for compilling the contract use solc.js and to install solc use

npm install solc
or

yarn add solc
once compiled use ethers.js to deploy the contract and for installing ethers.js use

npm install ethers
or

yarn add ethers
 
 
 
