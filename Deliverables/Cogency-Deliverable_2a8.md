## Deliverable Number
2a.8

## Context

| Number        | Workshop      | Date         | Duration     |
| ------------- | ------------- |------------- |------------- |
| 8.1 | Solution Tech Assessment (1/2) |28.11.2022 - 11.30PM CET|30min|
| 8.2 | Solution Tech Assessment (2/2) |01.12.2022 - 2PM CET|30min|
| 8.3 | Tech Architecture: Q&A  |02.12.2022 - 11AM CET|60min|
| 8.4 | First Architecture approach - review  |02.12.2022 - 4PM CET|60min|

During this sprint we will be working on presenting a more detailed architecture of our solution, including but not limited to the account creation process, the publishing access, the concepts of decentralised identifiers and verifiable credentials, and the CMS integration in Web2.

### Account creation and publishing access

<img width="1000" alt="image" src="https://user-images.githubusercontent.com/114009050/208790687-5b79104a-49e6-44db-ba7a-0cc7533c002a.png">

As discussed previously, once any of the three triggers is met, a form will be presented to the user with a threefold goal:
1. Gather further basic user’s metadata: personal, contextual and behavioural.
2. Creation of a new wallet or attachment of an existing one by the user. 
3. Get user consent for their data to be stored to avoid any future GDPR issue. Inform the user that they will own their own data, not the publisher, not any platform, but the user themselves. 

The Decentralised Identifier (DID) will be attached to the user Verifiable Credentials (VC), and together with their wallet, will be the only three items needed by the user to access any piece of content. Once the account is created, and the user wants to consume a piece of content from a specific publication, the publication (issuer) will double check with the blockchain (verifier) if the user has the right to consume that piece of content (if so, e.g. the green tick will become a blue tick), and the VC will be updated accordingly.

### Consumer’s badge update

<img width="1000" alt="image" src="https://user-images.githubusercontent.com/114009050/208790764-3087b5a1-a2ea-4a6c-90f2-d404edcc554e.png">

Once a threshold of content consumption is reached, the badge of the user will level up (e.g. from silver to bronze) and, again, the VC will be updated accordingly.

### Cogency space detail

<img width="1000" alt="image" src="https://user-images.githubusercontent.com/114009050/208790818-d0ce794f-6f66-4642-b4cb-cceea2c8297c.png">

The user’s Cogency profile, effectively the VC, will hold all the user’s information, including the DID and all their metadata. Any user with a digital identity will also be able to engage with the community. 

### Web2 CMS Integration

<img width="1000" alt="image" src="https://user-images.githubusercontent.com/114009050/208791600-7821b8cc-a8a1-4d27-83da-b61680f7011d.png">

An API/SDK Web2 layer will communicate with the blockchain and, once one of the triggers is met, the user will become a user with a digital identity stored on-chain.

### DID Architecture - Zoom in

<img width="800" alt="image" src="https://user-images.githubusercontent.com/114009050/208790871-3abfdb18-ad6c-4ac4-88ae-5631065bb6ea.png">

The project will use the DID standard[^1][^2][^3], also used by Polkadot, tailored to our needs.

## Next steps

The team has come up with a feasible solution that addresses the need of having a unique digital identity shared across all publishers. With the very basics in place, the rest of the project will aim to complete a blueprint with a business plan, that will be the final project deliverable.

 [^1]: https://w3c.github.io/did-core
 [^2]: https://w3c-ccg.github.io/did-primer
 [^3]: https://portswigger.net/daily-swig/decentralized-identifiers-everything-you-need-to-know-about-the-next-gen-web-id-tech  
