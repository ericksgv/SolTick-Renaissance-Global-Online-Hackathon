# SolTick
The inspiration behind SolTick arises from the need to combat fraud in ticket sales and provide transparency to the market. Using blockchain technology, each ticket is tokenized as an NFT, ensuring its authenticity and preventing fraudulent practices. The platform connects promoters, artists, users and resellers in a secure ecosystem. Additionally, the inclusion of royalties in each NFT transaction benefits creators and adds an exclusive component through the unique graphic design of each ticket, allowing users to sell them to collectors or keep them as souvenirs.

## Logo
![SolTickLogo](https://github.com/ericksgv/SolTick/assets/103967100/687d58a4-748f-4112-a8bc-c02ed1437738)

## Solution diagram:

![image](https://github.com/ericksgv/SolTick-Renaissance-Global-Online-Hackathon/assets/103967100/51f833c9-e06d-4e48-a3ec-aa97f84ca257)

SolTick revolutionizes ticket sales using blockchain technology and NFTs, ensuring authenticity and eliminating fraud. We connect promoters, artists and users in a transparent market. NFTs generate royalties and offer exclusive art to fans after the event.

This project is generated with the [create-solana-dapp](https://github.com/solana-developers/create-solana-dapp) generator.

## Team
[**Santiago Castro**](https://www.linkedin.com/in/santiago-castro-2b2a77276/)
[**Daniel Gutiérrez**](https://www.linkedin.com/in/daniel-guti%C3%A9rrez-rodr%C3%ADguez-194499200/)
[**Erick Garavito**](https://www.linkedin.com/in/erick-santiago-garavito-villamil-974275250/)


## Getting Started

### Prerequisites

- Node v18.18.0 or higher

- Rust v1.70.0 or higher
- Anchor CLI 0.29.0 or higher
- Solana CLI 1.17.0 or higher

### Installation

#### Clone the repo

```shell
git clone <repo-url>
cd <repo-name>
```

#### Install Dependencies

```shell
pnpm run install
```

#### Start the web app

```
pnpm run dev
```

## Apps

### anchor

This is a Solana program written in Rust using the Anchor framework.

#### Commands

You can use any normal anchor commands. Either move to the `anchor` directory and run the `anchor` command or prefix the command with `pnpm run`, eg: `pnpm run anchor`.

#### Sync the program id:

Running this command will create a new keypair in the `anchor/target/deploy` directory and save the address to the Anchor config file and update the `declare_id!` macro in the `./src/lib.rs` file of the program.

You will manually need to update the constant in `anchor/lib/counter-exports.ts` to match the new program id.

```shell
pnpm run anchor keys sync
```

#### Build the program:

```shell
pnpm run anchor-build
```

#### Start the test validator with the program deployed:

```shell
pnpm run anchor-localnet
```

#### Run the tests

```shell
pnpm run anchor-test
```

#### Deploy to Devnet

```shell
pnpm run anchor deploy --provider.cluster devnet
```

### web

This is a React app that uses the Anchor generated client to interact with the Solana program.

#### Commands

Start the web app

```shell
pnpm run dev
```

Build the web app

```shell
pnpm run build
```
