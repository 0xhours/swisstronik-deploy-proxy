# Swisstronik Tesnet Techinal Task 6 (Deploy Proxy)

link : [Click!](https://www.swisstronik.com/testnet2/dashboard)

Feel free donate to my EVM address

EVM :

```bash
0xAaBFbcbE7C0E1fa53ec926F41c2be559Ce263Eb0
```

## Steps

### 1. Clone Repository

```bash
git clone https://github.com/0xhours/swisstronik-deploy-proxy.git
```

```bash
cd swisstronik-deploy-proxy
```

### 2. Install Dependency

```bash
npm install
```

### 3. Set .env File

create .env file in root project

```bash
touch .env
```
or
```bash
nano .env
```

add this to your .env file

```bash
PRIVATE_KEY="your private key"
```

### 4. Compile Smart Contract

```bash
npm run compile
```

### 5. Deploy Smart Contract

```bash
npm run deploy
```

### 6. Initialize Owner

```bash
npm run initialize
```

### 7. Add Issuer

```bash
npm run add-issuers
```

### 8. Get Issuers list

```bash
npm run list-issuers
```

### 9. Upgrade Smart Contract

```bash
npm run upgrade
```

### 10. Finsihed

- Open the deployed-adddress.ts file (location in utils folder)
- Select SWTRProxy
- Copy the address and paste the address into testnet dashboard(Point1)
- Open address-with-explorer.txt file (location in utils folder)
- Copy the address explorer and paste the address into testnet dashboard(Point2)
- Open tx-hash.txt file (location in utils folder)
- Copy the transaction hash link and paste the address into testnet dashboard(Point3)
- No need push to github


```bash
SWTRProxy = '0x9a9361f330a4A2e0Cb2891109286f8333faAaAf4'
ProxyAdmin = '0xFe7FC81E4af5EEEdddf443EE73aE141A2BD6d88b' 
SWTRImplementation = '0xa5c3b238c3e0620b1D1fb3beb670db98ed4E2fB4'
```
