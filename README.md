<div align="center">
  <img src="https://github.com/zkSuite/zkforms-frontend/blob/main/public/static/logo.png" alt="Logo" width="350" height="100">
  
  <h3 align="center">zkForms</h3>

  <p align="center">
zkForms is a web3-focused form builder to construct online forms and surveys with multiple question formats, restrictions and better analysis that can be accessed from any device, anytime, and anywhere.
  </p>
    <br />
    <a href="https://zkforms.vercel.app/">View Demo</a>
    ·
    <a href="https://github.com/zkSuite/zkforms-frontend/issues">Report Bug</a>
    ·
    <a href="https://github.com/zkSuite/zkforms-frontend/issues">Request Feature</a>
  </p>
</div>
  
## About The Project
An open source interface for zkForms -- a platform to easily create and share online forms in a censorship resistant decentralized environment

## How it's Made

To save form data, responses and analytics, zkForms leverages Filecoin and IPFS in the background. We used the Web3.Storage to store the necessary data and polygon network to host the smart contracts.

To create the frontend which includes form builder, form renderer, and data viewer, we used React, Next.js, TailwindCSS, and RainbowKit.

In order to provide Zero-Knowledge Proofs that demonstrate the user's membership in the DAO, zkForms also makes use of SnarkJS and Circom2.0.

You can also generate proofs locally and submit on the client using the zkForms cli tool: [https://github.com/zkSuite/zkforms-cli](https://github.com/zkSuite/zkforms-cli)

All the smart contracts and circom circuits are available at: [https://github.com/zkSuite/zkForms-core](https://github.com/zkSuite/zkForms-core)

Check it out here: [https://zkforms.vercel.app/](https://zkforms.vercel.app/)

## Accessing the zkForms Interface

To access the zkForms Interface, use an IPFS gateway link from the latest release, or visit [zkforms.vercel.app](https://zkforms.vercel.app/)

## What's Next
