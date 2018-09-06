# Tasit

Tasit Labs makes 3rd party mobile apps for using features of popular Ethereum dapps directly via their smart contracts.

Tasit Labs has two major projects that dovetail together: the Tasit SDK (for developers) and the Tasit mobile apps (for pretty much anyone who uses a smartphone).

The Tasit SDK is a standardized, open-source set of tools and components for interacting with major classes of already-on-chain dapp smart contracts, and Tasit is a suite of mobile apps for mainstream users that lets them use features of these popular dapps through a Tasit third-party client.

**Tasit SDK**

Early, popular classes of smart contracts we support include NFTs, TCRs, DAOs, and two-sided marketplaces. The tools for each class of smart contract include:

1. Middleware for reading from and writing to smart contracts via an expressive JavaScript library with function names tailored to that type of dapp, and
1. Styled-but-customizable React components for using each feature of the dapp, leveraging the js middleware

The Tasit SDK also provides a standalone tool for discovering the current address of a high-profile dapp project’s primary smart contract interface.

We support Ethereum-based dapps to start, and in the long run the Tasit SDK will work with any blockchain that uses EVM and/or eWASM. In the case of Ethereum, we detect the interface / ERC standard a smart contract implements using ERC-165 standard interface detection whenever possible. As long as we’ve built the tooling to interact with that class of dapp at least once before, the Tasit SDK can “automagically” support any new dapp of that type. We'll (obviously) encourage contributions by the community.

[Tasit SDK repo](https://github.com/tasitlabs/tasitsdk)

**Tasit**

In the short run, the focus for the Tasit product is providing simple, third-party clients for viral dapps. Tasit will provide (a) more delightful UX for particular features of the dapp (for example, sell your CryptoKitty with no fee through a beautiful UI) and in some cases (b) ancillary features for the dapp.

We have a separate app for each major class of dapp.

1. Tasit Nifty (NFTs)
1. Tasit List (TCRs / FCRs)
1. Tasit Org (DAOs)
1. Tasit Market (Two-sided marketplaces)
1. ...with more to come

In the long run, Tasit will stitch together components from multiple dapps into novel experiences, like delegating your vote for a particular TCR to a preexisting Aragon organization, or decorating your Dharma loans with the same hats you use for your CryptoKitties because...reasons?

[Tasit repo](https://github.com/tasitlabs/tasit)

### Notes

Tasit Labs' repo for our website is on [GitLab](https://gitlab.com/tasit) and it's private, at least for now. The codebases for TasitSDK and the Tasit mobile apps are public and live here on GitHub!
