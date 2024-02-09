<h1 align="center">Wallet UI Template using GoldRush Kit & Particle Connect</h1>

<div align="center">
Powered by <span><a href="https://github.com/covalenthq/goldrush-kit">GoldRush Kit.</a></span> Open-source. Customizable. 200+ Chains.
</div>

## Ready-to-use customizable template

<a href="https://goldrush-wallet-portfolio-ui.vercel.app/">View live template</a>

## One-click deploy

Deploy your own Wallet UI template powered by GoldRush Kit and Particle Connect.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fcovalenthq%2Fgoldrush-wallet-portfolio-ui&env=NEXT_PUBLIC_COVALENT_API_KEY&envDescription=Visit%20Covalent%20to%20sign%20up%20for%20an%20API%20key&envLink=https%3A%2F%2Fwww.covalenthq.com%2Fplatform%2Fauth%2Fregister%2F)

## Local Setup

1. Install package dependencies using `npm install`.
2. Create `.env.local` in your root directory and add your Covalent API key and Particle Network Project, Client and App IDs.
```
NEXT_PUBLIC_COVALENT_API_KEY = "<YOUR_API_KEY>"
NEXT_PUBLIC_PARTICLE_PROJECT_ID = "<YOUR_PARTICLE_NETWORK_PROJECT_ID>"
NEXT_PUBLIC_PARTICLE_CLIENT_KEY = "<YOUR_PARTICLE_NETWORK_CLIENT_KEY>"
NEXT_PUBLIC_PARTICLE_APP_ID = "<YOUR_PARTICLE_NETWORK_APP_ID>"

```
3. To run the application, type the following into your terminal.
```
npm run dev
```

## Documentation
See the following documentation resources:
- A detailed guide on [Using Covalent's GoldRush Kit with Particle Connect](https://developers.particle.network/docs/using-covalents-goldrush-with-particle-connect).

- GoldRush's [component documentation](https://www.covalenthq.com/docs/unified-api/quickstart/goldrush-kit/) or [github](https://github.com/covalenthq/goldrush-kit).

- Particle Connect's [documentation](https://developers.particle.network/docs/particle-connect)

## Features

- Particle Connect web modal for user onboarding with social logins and external wallets.
- Cross chain selector for the connected wallet
- Token balances list component for ERC20 and NFTs
- Token transfers list


## 🤝 Contributing

Contributions, issues and feature requests are welcome!


## Show your support

Give a ⭐️ if this project helped you!



## 📝 License

This project is <a href="https://github.com/covalenthq/goldrush-wallet-portfolio-ui/blob/main/LICENSE">MIT</a> licensed.

