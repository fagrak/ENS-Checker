# ENS-Checker

![image](https://user-images.githubusercontent.com/63971790/230515824-b180dd6f-7a54-4333-ac16-8e1ed324cbd8.png)


The ENS Checker App is a simple web application that allows users to check if an Ethereum address has an associated ENS name. The app utilizes the Ethereum Name Service (ENS), which maps human-readable names to Ethereum addresses, making it easier to send and receive cryptocurrency.

## Background
Before DNS, the only way to explore information on the web was by entering its IP address. DNS helped us to link a domain name to an IP address. Similarly, ENS translates wallet addresses, hashes, and other Ethereum identifiers into readable domains which are saved on the Ethereum blockchain.

Unlike DNS, which relies on centralized servers, ENS works with the help of a smart contract that is censorship-resistant. With ENS, you can send someone a human-readable name instead of a long and complicated wallet address.

## How to Use
To check if your address has an associated ENS name, click the "Connect your wallet" button. If an ENS name is associated with your address, it will be displayed else just display the full 0x... address.

## Run the development server:

Open terminal and go `/my-app` directory.

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [localhost](http://localhost:3000) with your browser to see the result.

For more info: [LearnWeb3 Junior Track](https://github.com/LearnWeb3DAO/Junior-Track/blob/main/Ethereum-Name-Service.md)


## License
This project is licensed under the MIT License.
