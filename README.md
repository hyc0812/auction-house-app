# auction-house-app

### Prerequisite

- Node.js
- Truffle
- Ganache
- MetaMask


## Run the project

1. go to root directory of this project (**/auction-house-app**), run:

```linux
cd client
npm install
```
> NOTE: using `sudo su` if necessary.

2. Run Ganache UI, and modify the RPC Server as: HTTP://127.0.0.1:8545
3. Import the first two account into MetaMask
4. In CLI go back to the root directory of this project:

```linux
cd ..
```
5. Run the following:

```linux
truffle compile
truffle migrate
```
6. Copy the second contract address ( named "Auction" ) and paste into line 6 of **App.js** file at **/auction-house-app/client/src**. Save the file App.js;
7. go to**/auction-house-app/client** and run the app:
```linux
cd client
yarn start
```
8. Connect your two account to localhost:3000
9. play and have fun!
