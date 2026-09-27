# Evidence Adjudicator Website

A small Vite + React frontend for the deployed GenLayer Evidence Adjudicator contract.

## Contract

`0x6bAa91F409CF5f88a2c59624Bf8C4eF50f238856`

Explorer:
https://explorer-studio.genlayer.com/address/0x6bAa91F409CF5f88a2c59624Bf8C4eF50f238856

## Run locally

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

## Deploy to Vercel

Import this project into Vercel. Vercel automatically detects the Vite build, or deploy from the project root with:

```bash
npm install
npm run build
npx vercel --prod
```

The generated `vercel.app` URL can be used as the GenLayer Portal Website URL.

## Notes

The frontend calls the deployed contract methods:
- `adjudicate(url, claim)`
- `get_result()`

The wallet must be connected to the GenLayer network used by the deployment.
