***Note: This section is archived as Kovan, Rinkeby and Ropsten test networks are now deprecated. You can try this with other test networks like Goerli and Sepolia.***

# Introduction
Staking offers crypto holders a way of putting their digital assets to work and earning passive
income without needing to sell them.

You can think of staking as the crypto equivalent of putting money in a high-yield savings
account. When you deposit funds in a savings account, the bank takes that money and
typically lends it out to others. In return for locking up that money with the bank, you receive
a portion of the interest earned from lending – albeit a very low portion.
Similarly, when you stake your digital assets, you lock up the coins in order to participate in
running the blockchain and maintaining its security. In exchange for that, you earn rewards
calculated in percentage yields. These returns are typically much higher than any interest rate
offered by banks. Staking has become a popular way to make a profit in crypto without
trading coins. As of April 2022, the total value of cryptocurrencies staked exceeded the $280
billion threshold, according to Staking Rewards.

Staking is only possible via the proof-of-stake consensus mechanism, which is a specific
method used by certain blockchains to select honest participants and verify new blocks of
data being added to the network.

Our decentralised application allows users to stake their token for rewards by connecting
their meta mask account. The portal would allow the user to stake 3 tokens - WETH , FAU
and DAPP. The DAPP token would be a reward token given to the users as an incentive for
staking on our platform. Our portal also allows the users to unstake their tokens. Staking is
useful because it is the simplest way to deploy your idle crypto holdings and establish a
passive income. Most importantly – staking is much more eco-friendly than mining.

# Prerequisite
Install the below programs in your machine before running the commands given in `Steps`.
1. `brownie` 
2. `truffle` - use the test accounts given here to log in to meta mask account or you can use your own if you have balance.
3. `node`
4. `ganache-cli`
5. `yarn`
6. `python`

# Steps
1. Clone the repo.
```
git clone https://github.com/itsnotsagar/staking_reward.git
```
2. Open the repo in `VS-Code`.
3. Edit the `.env` and `.env.example` file by pasting in your own APIs and private keys.
4. Install the required dependencies and modules.
```
yarn install
```
5. Deploy the smart contracts on the kovan test network.
```
brownie run scripts/deploy.py --network kovan
```
6. Change directory to `front_end` folder and run the following to start the website in localhost.
```
cd front_end
yarn
yarn start
```
7. To issue staking reward run the `issue_token.py` script in the `/scripts` directory.
# Screenshots
<p align="center">
<img width="579" alt="Screenshot 2023-02-12 at 12 03 43 PM" src="https://user-images.githubusercontent.com/56265949/218296758-3e48fc7e-1523-4519-b061-63e509a31432.png">
<img width="579" alt="Screenshot 2023-02-12 at 12 04 08 PM" src="https://user-images.githubusercontent.com/56265949/218296763-d82061b4-a934-4236-a4d4-9be5acc74f8f.png">
<br><br><br>
<img width="540" alt="Screenshot 2023-02-12 at 12 04 40 PM" src="https://user-images.githubusercontent.com/56265949/218296775-5173c480-8fcb-41c4-ad9b-99c1b6e211bd.png">
<img width="581" alt="Screenshot 2023-02-12 at 12 05 06 PM" src="https://user-images.githubusercontent.com/56265949/218296786-60619fd4-cdee-4819-9351-b3148f9ea5ee.png">
<img width="581" alt="Screenshot 2023-02-12 at 12 05 21 PM" src="https://user-images.githubusercontent.com/56265949/218296791-e4ac9168-babb-432b-a5a9-ed023862d498.png">
<img width="581" alt="Screenshot 2023-02-12 at 12 05 40 PM" src="https://user-images.githubusercontent.com/56265949/218296800-1ac1d10a-5394-475f-8851-03a80262de1d.png">
<img width="581" alt="Screenshot 2023-02-12 at 12 05 53 PM" src="https://user-images.githubusercontent.com/56265949/218296809-c3c49306-1725-423a-8d17-ef1787fb5b33.png">
<img width="581" alt="Screenshot 2023-02-12 at 12 06 06 PM" src="https://user-images.githubusercontent.com/56265949/218296815-e0c097d0-f2a0-410b-af29-9633c467ce4a.png">
<img width="581" alt="Screenshot 2023-02-12 at 12 06 25 PM" src="https://user-images.githubusercontent.com/56265949/218296830-64857b43-a7d9-40a8-90b8-97655b7917ae.png">
<img width="581" alt="Screenshot 2023-02-12 at 12 06 34 PM" src="https://user-images.githubusercontent.com/56265949/218296842-8d98bff6-4ede-46ae-96c5-47a8e929a025.png">
<img width="581" alt="Screenshot 2023-02-12 at 12 06 48 PM" src="https://user-images.githubusercontent.com/56265949/218296854-afc6fa85-3bef-4aff-84c4-50fd1f1e15b0.png">
<img width="581" alt="Screenshot 2023-02-12 at 12 07 01 PM" src="https://user-images.githubusercontent.com/56265949/218296864-2d838e0e-fc92-4914-976f-f85958a9a61d.png">
<img width="581" alt="Screenshot 2023-02-12 at 12 07 16 PM" src="https://user-images.githubusercontent.com/56265949/218296869-af8dab6d-a748-4ef3-866f-e5fd2e99f22b.png">
<img width="581" alt="Screenshot 2023-02-12 at 12 07 29 PM" src="https://user-images.githubusercontent.com/56265949/218296878-8a676417-a2c7-44c7-825a-ceae1bb18687.png">
<img width="581" alt="Screenshot 2023-02-12 at 12 07 42 PM" src="https://user-images.githubusercontent.com/56265949/218296883-dc3bf4e0-b36b-4a3c-aeb9-c8ccc8b27bae.png">
<img width="581" alt="Screenshot 2023-02-12 at 12 07 56 PM" src="https://user-images.githubusercontent.com/56265949/218296890-a880c821-32c6-437f-9f28-80013877c5d7.png">
<img width="581" alt="Screenshot 2023-02-12 at 12 08 10 PM" src="https://user-images.githubusercontent.com/56265949/218296894-47aaaeef-c1a2-43d4-a75b-18d16304e2f8.png">
<img width="581" alt="Screenshot 2023-02-12 at 12 08 23 PM" src="https://user-images.githubusercontent.com/56265949/218296902-595a2b79-88dc-4101-bdde-bf7a00390834.png">
</p>




