# Student-Registration
Decentalized Student Registration Dapp, Calculates the fee by taking Caste and merit Scholarship into consideration.

![image of Student Registration] (https://github.com/ShivaSunny9/Student-Registration/blob/master/rsz_screenshot_from_2020-04-10_14-07-47.png)

git clone https://github.com/ShivaSunny9/Student-Registration.git

cd truffle-Student-Registration

npm install -g truffle

npm install

truffle compile

Configure settings variables to ropsten in truffle.js file:

var infura_apikey = "you need to register in Infura for an Access Token.";

var mnemonic = "< twelve words you can find in metamask/settings/reveal seed words >";

var address = "rinkeby address with ether";

truffle migrate --reset --network rinkeby

Note: If you receive an error Error: Exceeds block gas limit, you may need to manually set the gas limit for your contract. See the Truffle Configuration documentation for details.

npm run dev

